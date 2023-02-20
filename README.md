# Hello, I'm Logan Munoz! (He/Him) :wave:

I'm a student at Seattle Pacific University (although I disagree with their discriminatory hiring policies) double majoring in Computer Science and Applied Mathematics, graduating this June 2023. I have a passion for problem solving and love learning new things no matter the subject matter. I am currently working on my senior project, Envision, and am looking forward to returning to F5 Inc. after graduation as a Software Engineer I. 

Feel free to check out the repositories below to see some projects I have worked on, or use the following link to view my LinkedIn and learn a bit more about me. If you wish to get in contact with me you can use the email in my bio. I hope you have a great day!

LinkedIn: https://www.linkedin.com/in/logan-munoz/

## Projects

The following are short descriptions of projects I have worked on. If you would like to see an in-depth description of any projects, complete with a detailed explanation and even more images, please check out the pinned repositories below, or click the links in any given dropdown. Enjoy!

<details><summary>
  F5 Internship 
  </summary>
  <h2>F5 Internship - Team</h2>
  <h3>- Code -</h3>
  <a href="https://github.com/LoganMunoz16/F5-Internship">Repository pinned below</a>
  
  <h3>- Timeline -</h3>
  June 2023 - September 2023
  
  
  <h3>- Technologies -</h3>
  <ul>
    <li>Javascript</li>
    <li>React</li>
    <li>Redux</li>
    <li>NGINX</li>
  </ul>
  
  
  <h3>- Brief Description -</h3>
  I interned in the Greenhouse department of the Office of the CTO, working on Project NSure. NSure is a web application designed to reduce NGINX configuration complexity to make it more marketable to small or medium sized businesses. I had the honor of working on a global team with members from the US, India, and Germany, and doing many presentations for this team and the company at large about our progress throughout the internship.
  
  
  Below is a calendar created by my intern cohort detailing our activities throughout the internship, created in preparation for our final demo of Project NSure.
<p align="center">
  <img src="https://user-images.githubusercontent.com/59589283/218954868-3651fa1e-6de9-4277-afc2-910d65ea7438.png" />
</p>
</details>

--

<details><summary>
  Course Flowchart 
  </summary>
<h2>Course Flowchart - Team</h2>
  <h3>- Code -</h3>
  <a href="https://github.com/LoganMunoz16/flowchart-alison-logan">Repository pinned below</a>
  
  <h3>- Timeline -</h3>
  February 2022 - March 2022
  
  
  <h3>- Technologies -</h3>
  <ul>
    <li>C++</li>
    <li>C++ Boost</li>
    <li>Graph Data Structure</li> 
  </ul>
  
  
  <h3>- Brief Description -</h3>
  This project was completed by myself and my partner Alison Langer as the final for Algorithms Design and Analysis. Given a text file containing a course list, our program will use C++ Boost's graph libraries to create a possible course flow based on credit limits and a starting quarter. I designed the primary algorithm to create this course flow, and Alison handled all the visualizations using libraries such as graphviz.
  
  
  Below is a picture of an example course flow that can be created with our program. The linked repository has a very in-depth description of the project, along with some more images and an animation of the visuals being created.
  
  If you would like to see a video on how the program operates, please see <a href="https://youtu.be/glKszGwu_r4">this link</a>.
  
  
<p align="center">
  <img src="https://user-images.githubusercontent.com/59589283/159179053-a2b3c372-59cf-4b74-a7a1-80bab38556e4.jpg" />
</p>
</details>

--

<details><summary>
  Full Parser 
  </summary>
  <h2>Full Parser - Solo</h2>
  <h3>- Code -</h3>
  <a href="https://github.com/LoganMunoz16/go-parser">Repository pinned below</a>
  
  <h3>- Timeline -</h3>
  October 2021 - November 2021
  
  
  <h3>- Technologies -</h3>
  <ul>
    <li>Golang</li>
    <li>Basic Lexer and Parser concepts</li>
  </ul>
  
  
  <h3>- Brief Description -</h3>
  This parser was created for my Concepts in Programming Langauges course. The program runs a lexical and syntactical analysis on a mock lanaguge called Three Point. If the input program passes all tests, then the code can be re-printed either in Scheme or Prolog syntax. This was a difficult project because I had no exposure to Golang prior to beginning coding, so I had to learn how to build a full parser while also learning Golang.
  
  
  Below is the grammar used for Three Point. 
  
  
```
START      --> STMT_LIST
STMT_LIST  --> STMT. |
               STMT; STMT_LIST
STMT       --> POINT_DEF |
               TEST
POINT_DEF  --> ID = point(NUM, NUM)
TEST       --> test(OPTION, POINT_LIST)
ID         --> LETTER+
NUM        --> DIGIT+
OPTION     --> triangle |
               square
POINT_LIST --> ID |
               ID, POINT_LIST
LETTER     --> a | b | c | d | e | f | g | ... | z
DIGIT      --> 0 | 1 | 2 | 3 | 4 | 5 | 6 | ... | 9
```
</details>

--

<details><summary>
  Huffman Tree Encoding 
  </summary>
<h2>Huffman Tree Encoding - Solo</h2>
  <h3>- Code -</h3>
  <a href="https://github.com/LoganMunoz16/huffman-tree">Repository pinned below</a>
  
  <h3>- Timeline -</h3>
  April 2020 - June 2020
  
  
  <h3>- Technologies -</h3>
  <ul>
    <li>C++</li>
    <li>Huffman Tree Data Structure</li>
  </ul>
  
  
  <h3>- Brief Description -</h3>
  This program was created as a final for my Data Structures II course. Given an input text document, the program will create a huffman tree based on how often each character in the document is used. Each character will be assigned a unique combination of 0's and 1's, and then replaced in the original document to create an encoded document. 
  
  The following is an example of what the huffman encoding will look like. The "CR" character is representative of a newline character.
  
  ```
{key:   , code: 11}
{key:  a, code: 010}
{key:  e, code: 0010}
{key:  o, code: 0110}
{key:  u, code: 0111}
{key:  r, code: 1000}
{key:  n, code: 1010}
{key:  i, code: 1011}
{key:  l, code: 00001}
{key:  s, code: 00010}
{key:  d, code: 00110}
{key:  m, code: 10011}
{key:  p, code: 000000}
{key:  c, code: 000001}
{key: CR, code: 000110}
{key:  t, code: 000111}
{key:  g, code: 001111}
{key:  q, code: 100100}
{key:  b, code: 100101}
{key:  h, code: 0011100}
{key:  f, code: 00111010}
{key:  z, code: 00111011}
```

</details>

--

<details><summary>
  Library Website  
  </summary>
<h2>Library Website - Solo</h2>
  <h3>- Code -</h3>
  <a href="https://github.com/LoganMunoz16/library-database-front-end">Repository pinned below</a>
  
  <h3>- Timeline -</h3>
  April 2021 - June 2021
  
  
  <h3>- Technologies -</h3>
  <ul>
    <li>Javascript</li>
    <li>Bootstrap</li>
    <li>Express</li> 
    <li>Mongoose</li>
    <li>node.js</li>
  </ul>
  
  
  <h3>- Brief Description -</h3>
  This project was the final for my Netcentric Computing course. This web application is a mock library, allowing a user to add, remove, and edit information on books and their corresponding authors. This was my first step into working with web applications, and creating my own API from scratch to handle database interactions. The back end is kept private for security concerns, but listed in this repository is the code for the front end.
  
  
  Below is a screenshot of what the book list looks like on the website. Feel free to check out the repository for more screenshots and information.
  
  
<p align="center">
  <img src="https://user-images.githubusercontent.com/59589283/141358313-f4656be5-7c8e-48cf-a85a-4854fa141420.png" />
</p>
</details>

--

<details><summary>
  Hunt the Wumpus  
  </summary>
  
<p align="center">
  <img src="https://user-images.githubusercontent.com/59589283/218954868-3651fa1e-6de9-4277-afc2-910d65ea7438.png" />
</p>
</details>
