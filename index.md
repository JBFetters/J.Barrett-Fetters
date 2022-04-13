# Jamie Barrett-Fetters

## INTRODUCTION

Welcome to my portfolio. I am currently at Southern New Hampshire University obtaining a bachelor’s degree in Computer Science. I am aspiring to develop my skills within my current career combining software engineering and information security. Each opportunity and experience I have has helped strengthen and clarify my future career goals within the Computer Science field. 
I love bowling, playing software, mountain biking, road cycling, riding motorcycle and spending time with family and friends. I am always up for an adventure whether it is on the bicycle, motorcycle or enjoying time with my nephews.

## PROFESSIONAL SELF-ASSESSMENT

During the course of my degree I have collaborated with other students on discussion boards and group assessment. I have learned that computer science involves not only coding, but how to solve problems. Creating a program that help automate a process to make you more efficient at work or in personal life. Implementing good coding practices, security measures and learning to take one step at a time throughout the process. 
During computer science program, I have learned how to collaborate in a team environment. The skills taught during CS-310, Collaboration and Team Project. In this class, I learned how to use GitHub as a group to add, update, and make changes code. We creating changelogs, conducted peer reviews, and more. In CS-250 Software Development Lifecycle, I learned how communicate to within a team environment, but also with stakeholders.  so that they understand computer system security, network security and why we need to protect our assets, understanding data by mining understand the trends and conveying why we need to practice standard coding techniques and ensure that the code is secure as possible to avoid SQL injection, buffer overflow, and other attacks threat actors will try to use.
Over the course of CS-499 Capstone I took my first coding project, the Zoo Authentication System, to create my final project. The final project addresses software design and engineering, data structures and algorithms and database. In the next sections you will see why I choses the project from the code review and how I addressed each section. The reason why I selected this for this portfolio was because it was my first coding program and throughout obtaining my degree I learned what could be done to change and improve the code. IT-253 Computer System Security taught me best practices in security planning and understand the purpose of create a Security plan for the network that defines purpose, scope, roles and responsibilities, training, access controls and managing vulnerabilities.
This page will give you a glimpse into who I am, display my capstone project and experience that have shaped me. I will address Software Design and Engineering, Algorithms and Data Structures and Database. The artifacts will demonstrate the abilities I have learned in the computer science program.

## SOFTWARE DESIGN, ENGIEERING, ALGORITMS, and DATA STRCTURES

The Zoo Authentication System was the main focus for all three of the elements. The applications was created in the Java language for IT-145 Foundation in Application Development. For this artifact I decided to redesign the program and recode C++ language. I wanted to display my abilities to take a program that existed and recreated in a different language. While reviewing the original code I noticed how hard it was to read, due to lack of comments, how disorganized the code was and overall clean up. 

While re-writing the program I learned that taking your time and working on one problem at a time to make sure each step that was taken worked correctly. For example ask the user for the user id. Testing different scenarios like correct user id or the user did not enter “exit”. Ensuring if the user inputted the wrong user id that it gave the user the X amount of attempts before the user was locked out of the system. This ensure that a threat actor cannot keep inputting an incorrect user id to attempt to discover the users password.

When re-writing the program I created a more secure logon system. For example if the user inputs the incorrect user id three times it locks them out and does not request the user to input their password. If the user inputs the correct user id, but wrong password it locks the user out after three attempts. I also added a case sensitive function for the user id which takes the user id inputs whether inputted all capital letters or a combination between capitals or lower case letters the function converts it to all lower case letters.


1. ![Zoo Authenticaiton Pseudocode](assets/css/Pseudocode.png)
2. Flow Chart
3. [Zoo Authentication](https://github.com/JBFetters/ZooAuthentication)

### CODE REVIEW

Prior to re-writing the program I conducted a code review of the old code to address all the issues that were found and what needed to be corrected or added. While preparing for the code review I analyzed the old code, create notes for the review and provided evidence of how the enhancements would better the program. I explained how the program worked and provide a demonstration of the MD5 hash. The code review made me realize how disorganized and lack of comments hindered the explanation.

1. [Code Review](Debut 10.mov)

## DATABASES

To improve the newly re-written Zoo Authentication System was to design and implement a database. From the four text files the system uses the credential file is the one that was taken to create the database. The credential file holds the user credentials, user id, password, password hashed and their role within the zoo. Creating the credential database SQLite syntax to create the database, table and populate the table with the information from the text file. DAD-220, Introduction to Structured Database Environment, was the course that helped me learn SQL, how to manipulate, analyze, construct and query the data.
The process for this artifact was first create the credential database and second incorporated the database into the Zoo Authentication System code. To incorporate the database a function was created to query the database to pull the information required to validate the user credentials for successful logon. As before all conditions were tested as before to ensure the user could logon successfully to the correct system per their role.

1. [Credential Database](https://github.com/JBFetters/Credentials-Database)
2. [Zoo Authentication with Database](https://github.com/JBFetters/ZooAuthenticationDatabase)

 




You can use the [editor on GitHub](https://github.com/JBFetters/JBFetters/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown //files.
[Link](url) and ![Image](src)
