
## INTRODUCTION

Welcome to my portfolio. I am currently at Southern New Hampshire University obtaining a bachelor’s degree in Computer Science. I am aspiring to develop my skills within my current career combining software engineering and information security. Each opportunity and experience I had has helped strengthen and clarify my future career goals within the Computer Science field. 

I love bowling, playing softball, mountain biking, road cycling, riding motorcycle and spending time with family and friends. I am always up for an adventure whether it is on the bicycle, motorcycle or enjoying time with my nephews.

## PROFESSIONAL SELF-ASSESSMENT

During the course of my degree I have exchanged ideas with other students via discussion boards and group assessment. I have collaborated with other co-workers to help understand an element of an assignment or to bounce ideas or thoughts off of. I have learned that computer science involves not only coding, but how to solve problems. Automating a process by creating a program can make you more efficient at work or in your personal life. Applying coding best practices, security measures and learning to take one step at a time throughout the process are critical to success. 

During computer science program, I have learned how to collaborate in a team environment. The skills taught during CS-310, Collaboration and Team Project. This helped me learn how to use GitHub as a team to add, update, and make changes code. We worked on changelogs, and conducted peer reviews.
In CS-250, Software Development Lifecycle, I learned not only how communicate within a team environment, but also how to work with stakeholders.  We made sure the stakeholders understood the reason for computer system security, network security and the need to protect our assets. Ensuring the stakeholders understood why data mining is useful to understand trends within the company.  Conveying why using coding best practices and techniques. This will help protect software from SQL injection, buffer overflow, and other attacks threat actors will try to use.

In IT-253, Computer System Security, taught me best practices in security planning and understanding the purpose of creating a Security plan for the network system that defines purpose, scope, roles and responsibilities, training, access controls and managing vulnerabilities.

The goal of CS-499 Capstone course was for us to take an existing project and make enhancement to it. I used my first coding project, the Zoo Authentication System, to create my capstone project. The capstone project addresses software design and engineering, data structures, and algorithms and databases. In the next sections beginning with the code review and you will see how I addressed and improve each section. The reason why I selected this for the portfolio was because it was my first coding program and throughout obtaining my degree I learned what could be done better to improve program.

This page will give you a glimpse into who I am and display the capstone project and experiences that have shaped me. I will address Software Design and Engineering, Algorithms, and Data Structures and Databases on the Zoo Authentication code and highlight the enhancements that were performed. The artifacts will demonstrate the abilities I have learned in the Computer Science program.


### CODE REVIEW

A code review is a review of your or someone else's code. You are reviewing the code to find mistakes, formatting concerns, coding style, naming scheme of variables, classes, security concerns and more. Code review practices are important as the review can identify issues with the code that may not been seen while in the development phase. 

Prior to starting the enhancements I conducted a review of the original Zoo Authentication code. The review provided an overview of how the system works, demonstration of MD5 hashing use a MD5 calculator. I identified issues that need to be addressed for each of the three enhancement categories. In preparation for the code review I created notes for the review and provided evidence of how the enhancements would better the program. The code review made me identify disorganized, lack of flow and comments hindered the explanation. 

The Original Zoo Authentication Pseudocode was written part of IT-145 final project. Pseudocode provides a description of the steps that I would or could take in developing the program. Writing out the steps and the issues helps you lay out a path before you start coding. Below are the links to the Original Zoo Authentication (which was written in Java) code review, and the original Zoo Authentication Pseudocode.

1. [Original Zoo Authentication](https://github.com/JBFetters/OriginalZooAuthentication)
2. [Code Review](https://youtu.be/7cqPKgaxoDw)
3. Original Zoo Authentication Pseudocode

<img src="https://raw.githubusercontent.com/JBFetters/J.Barrett-Fetters/main/Pseudocode.jpg" width="480" height="312">


## SOFTWARE DESIGN, ENGINEERING and ALGORITHMS and DATA STRUCTURES

The Zoo Authentication System is the main focus for all three elements. The application was created for IT-145, Foundation in Application Development, in the Java language. For this artifact I decided to redesign the program and recode in C++ language. I wanted to display my abilities to take an existing program and rewrite the program in a different language. Throughout this process, besides the professor to bounce ideas off in the journal entries, I enlisted a co-worker and other students helped me when I ran into a code writer’s block. I also found out that after stepping away from the code for a couple hours or a day, the code writer’s block would resolve itself.

During design and engineering of the program I learned to take my time and work on one problem at a time to make sure each step worked correctly. For example, determining the steps that were required when asking the user for the user id, if the user id is correct, the user inputted "exit", or if they exceeded three attempts to log the user into the system. Adding a limit to the number of logon attempts ensures that a threat actor cannot keep inputting an incorrect user id to attempt to discover the user’s password. Another change when rewriting was adding functions. For example, change string function, in line 246 is a block of code which only runs when it is called, and converts user id input from either all capital, a combination between capital or all lower case and converts the input to all lower case letters.

Since C++ language did not have a parsing function, like Java has, I had to create a block of code that would read the credential text file and pull the information required to validate user credentials. Within this block of code there are different algorithms and data structures that are used to parse out the information. Starting at line 64, the block of code I used an array to sort and find the information within the credential file. Once the information is in the array it is accessible when required to compare to the user inputs to validate their credentials. 
Once the code worked I tested all conditions to verify they were working. 

The list of test conditions are as followed:
1. User enter exit and would exit the program
2. User enter wrong user id and after three attempts is logged out of the system
3. User enter correct user id, but wrong password and after three attempts is logged out of the system.
4. User enter correct user id and password and is given access to the correct system based on their roles (Zoo Keeper, Admin, and Vet).
5. User stays logged in until they enter “exit”.

Zoo Authentication Unified Modeling Language (UML) Sequence is a diagram how the rewritten code performs. This provides a visualization design of the system.

1. [Zoo Authentication](https://github.com/JBFetters/ZooAuthentication)
2. Zoo Authentication UML Sequence

<img src="https://raw.githubusercontent.com/JBFetters/J.Barrett-Fetters/main/UML%20Sequence.JPG" width="936" height="624">


## DATABASES

DAD-220, Introduction to Structured Database Environment, was the course that helped me learn Structured Query Language (SQL), and how to manipulate, analyze, construct and query the database. The online software we used for DAD-220, Codio, was useful tool, but had its issues. During the course I accidently locked myself out of my assignment and the professor was the only one who could unlock the module. To submit my assignment on time I reached out to several students request only the data that was pre-populated. I recreated the database and completed the assignment on time. Having to complete this assignment from the bottom up help me better understand databases and how to build and query databases.

Another improvement to the newly re-written Zoo Authentication System was to design and implement a database. From the four text files, the credential file is the one chosen to created and turned into a database. The credential file holds the user credentials, user id, password, password hashed and the user’s role within the zoo. To create the credential database I used Structured Query Language (SQL) syntax to create the database, table and populate the table with the information from the text file. 

The process for this artifact was to first create the credential database and second incorporate the database into the Zoo Authentication System code. To incorporate the database, a function was created to query the database and pull the information required to validate the user credentials for successful logon. As before, all conditions were retested to ensure the user could logon successfully per their role.


1. [Credential Database](https://github.com/JBFetters/Credentials-Database)
2. [Zoo Authentication with Database](https://github.com/JBFetters/ZooAuthenticationDatabase)

 




<!--You can use the [editor on GitHub](https://github.com/JBFetters/JBFetters/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown //files.-->

