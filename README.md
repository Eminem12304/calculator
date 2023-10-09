# calculator
 ## Personal information
| **The Link My Class** | https://bbs.csdn.net/forums/ssynkqtd-04 |
| --------------- | ----------- |
| **The Link of Requirement of This Assignment** | https://bbs.csdn.net/topics/617332156 |
| **The Aim of This Assignment** | A simple calculator is realized by using front-end and visualization technology |
| **MU STU ID and FZU STU ID** | 21125309_832102209 |
| **The Link of Code of this assignment of GitHub** | |

## catalogue
[1.Project introduction](#q1)
[2. Personal Software Process (PSP) Form](#q2)
[3. Work introduction](#q3)
[4. Ideas for solving problems](#q4)
[5. Steps to solve the problem](#q5)
[6. Project code](#q6)
[7. Result presentation](#q7)
[8. Summary](#qwx)

<span id="q1">**1.Project introduction**<span>
 In this blog post, I will show you how to make a calculator with front-end technology that can perform simple calculations. I will explain from two aspects of thinking and code, and attach the final results and some self-summary.

<span id="q2">**2. Personal Software Process (PSP) Form**<span>
| **Personal Software Process Stages** |Estimated Time（minutes） |Actual Time（minutes）|
|--|--|--|
|**Planning(total)**  | 30 | 50 |
|• Estimate  | 30 | 50 |
|**Development(total)**  |375 | 440 |
|• Analysis  | 30 | 35 |
|• Design Spec  | 10  | 10 |
|• Design Review  | 20 | 15 |
|• Coding Standard  | 45 | 50 |
|• Design  | 45 | 55 |
|• Coding  | 120 | 140 |
|• Code Review  | 60 | 65 |
|• Test  | 45 | 70 |
|**Reporting(total)**  | 100 | 110 |
|• Test Repor  |30  | 45 |
|• Size Measurement  | 30 | 25 |
|• Postmortem & Process Improvement Plan  | 40 | 40 |
|**Sum**  |505 | 600 |

<span id="q3">**3. Work introduction**<span>
1. Collect information online
2. Identify ideas and make plans
3. Write code
4. Verify code functionality and make changes to improve it
5. Document the process, write a blog

<span id="q4">**4. Ideas for solving problems**<span>
Before we start working, we first need to decide what tools to use to implement the calculator. Having learned HTML for a while before, I chose to use VScode as the compiler and HTML as the compiler language.

Before we do that, let's take a look at HTML, what its advantages are, and why you should use it.HTML is the abbreviation of HyperText Markup Language, which is an application under the standard General Markup Language, and also a specification, a standard. It marks various parts of the webpage to be displayed through markup symbols. From the appearance of the first version to now, html has undergone 5 revisions, from HTML 2.0 to HTML 5, html has proved its advantages in the website with its own advantages, so that it has replaced the ancient C language programming to structure part of the website.  
It is a standard markup language for documents, designed to be displayed and viewed online during browser time, and also helps create the structure of web pages. Because it is a markup language, it consists of many tags. There are labels that display text, tables, ordered lists, and unordered lists. There are two main parts on an HTML page: the header and main body. The data describing the page (also known as metadata) is located at the header, while the main section includes all the tags required to represent the visible content of the webpage. HTML is a platform independent language that can be used on any platform, such as Windows, Linux, Macintosh, etc.

**Its advantage lies in**
* HTML5 gives web pages better meaning and structure. More diverse tags will be built with support for RDFa, microdata, and microformats, creating a data-driven web that is more valuable for both programs and users.

* The web app developed based on HTML5 has shorter startup time and faster networking speed, all thanks to the HTML5 APP Cache and local storage function. Indexed DB (one of the most important technologies for html5 local storage) and API documentation.

*   Before the arrival of HTML5, due to the diversity of platforms, it was necessary to develop multiple versions for different platforms for each set of products, which consumed a lot of time and effort, and also increased development costs. However, the emergence of HTML5 technology can effectively solve this problem. As long as developers use one set of programs, they can easily achieve the presentation functions of multiple platforms, reducing development difficulty, Saves development time and cost investment.

* The coolest feature in HTML5 is offline caching. JavaScript provides several different offline storage functions, which have better flexibility and architecture compared to traditional cookies, and can store more content. It has better security and performance, and can be saved even after the browser is closed.

*   Previously, when native applications were launched on the Appstore, they had to wait for a long review time. If there were any issues that needed to be updated, they had to be re reviewed, which invisibly wasted a lot of time. HTML5 is loaded through a browser, so there is no such issue. If any problems occur, it can be updated and launched in a timely manner without waiting for review time.



<span id="q5">**5.Steps to solve the problem**<span>

 **Program Requirements**
Basic requirement: Implement addition, subtraction, multiplication, division, and clear functions.
Advanced requirement: Implement functionality for exponentiation, trigonometric functions, and more.

**Design Process**
A simple calculator should contain numbers, operators and function keys.

**Numbers**: integers from 0 to 9
**Operators**: the basic four operations addition, subtraction, multiplication and division
**Function**: empty, backspace, parentheses, equal functions. On the basis of realizing these functions, trigonometric function and inverse trigonometric function as well as square and square root operations are performed on the results.

**Implementation Process**
1.  The interface only needs to fix the width and height of the calculator panel and the width and height of the button. Then select text styles and page colors to beautify it.
2. If a number (0,1,2,3,4,5,6,7,8,9) and “(”, “)”, “.” is clicked, it will be displayed in the input text box above (hereinafter referred to as the output box) and append (+=) in a string content.
3. If an operator button (+, -, *, /, ^, √, sin, cos, tan, arcsine, arccosine, arctan) is clicked, it will perform related operations and output results.
4. If “C” is clicked, the string content is cleared, and the output box is also cleared.
If “←” is clicked, clear the content string with the last character and set the output box to the value of content.
5. If you click “=”, the result of the calculation is displayed in the output box and the content is cleared.
6. Using the eval () function, this function can execute the js statement in it, and return the result if it can be executed, or directly return the original statement if it cannot be executed.
