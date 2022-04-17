
## INTRODUCTION

Welcome to my portfolio. I am currently at Southern New Hampshire University obtaining a bachelor’s degree in Computer Science. I am aspiring to develop my skills within my current career combining software engineering and information security. Each opportunity and experience I have has helped strengthen and clarify my future career goals within the Computer Science field. 

I love bowling, playing software, mountain biking, road cycling, riding motorcycle and spending time with family and friends. I am always up for an adventure whether it is on the bicycle, motorcycle or enjoying time with my nephews.

## PROFESSIONAL SELF-ASSESSMENT

During the course of my degree I have collaborated with other students on discussion boards and group assessment. I have learned that computer science involves not only coding, but how to solve problems. Creating a program that help automate a process to make you more efficient at work or in personal life. Implementing good coding practices, security measures and learning to take one step at a time throughout the process. 

During computer science program, I have learned how to collaborate in a team environment. The skills taught during CS-310, Collaboration and Team Project. In this class, I learned how to use GitHub as a group to add, update, and make changes code. We creating changelogs, conducted peer reviews, and more. In CS-250 Software Development Lifecycle, I learned how communicate to within a team environment, but also with stakeholders.  so that they understand computer system security, network security and why we need to protect our assets, understanding data by mining understand the trends and conveying why we need to practice standard coding techniques and ensure that the code is secure as possible to avoid SQL injection, buffer overflow, and other attacks threat actors will try to use.

Over the course of CS-499 Capstone I took my first coding project, the Zoo Authentication System, to create my final project. The final project addresses software design and engineering, data structures and algorithms and database. In the next sections you will see why I choses the project from the code review and how I addressed each section. The reason why I selected this for this portfolio was because it was my first coding program and throughout obtaining my degree I learned what could be done to change and improve the code. IT-253 Computer System Security taught me best practices in security planning and understand the purpose of create a Security plan for the network that defines purpose, scope, roles and responsibilities, training, access controls and managing vulnerabilities.

This page will give you a glimpse into who I am, display my capstone project and experience that have shaped me. I will address Software Design and Engineering, Algorithms and Data Structures and Database on the Zoo Authentication code and what enhancements were performed. The artifacts will demonstrate the abilities I have learned in the computer science program.

### CODE REVIEW

A code review is a review of your or someone else's code. You are reviewing the code to find mistakes, formatting concerns, coding style, naming scheme of variables, classes, security concerns and more. Code review practices are important as the review can identify issues with the code that may not been seen while in the development phase. 

Prior to starting the enhancements I conducted a review of the original Zoo Authentication code. The review provides an overview of how the system works, MD5 hashing and providing a demonstration of the MD5 hashing use a MD5 calculator, and identifying issues that need to be addressed in each of the three enhancement categories. In preparation for the code review I created notes for the review and provided evidence of how the enhancements would better the program. The code review made me realize how disorganized, lack of flow and comments hindered the explanation. 

The Original Zoo Authentication Pseudocode was written part of IT-145 final project. Pseudocode provides a description of the steps that I would or could be taking in developing the program. Writing out the steps and the issues helps you lay out your path before you start coding. Below are the links to the Original Zoo Authentication, which was written in Java,code review, and original Zoo Autenticaiton Pseudocode.

1. [Original Zoo Authentication](zooauthentcationsystem.java)
2. [Code Review](https://youtu.be/7cqPKgaxoDw)
3. Original Zoo Authentication Pseudocode

<img src="https://raw.githubusercontent.com/JBFetters/J.Barrett-Fetters/main/Pseudocode.jpg" width="480" height="312">



## SOFTWARE DESIGN, ENGIEERING and ALGORITHMS and DATA STRUCTURES

The Zoo Authentication System is the main focus for all three elements. The application was created in Java language for IT-145 Foundation in Application Development. For this artifact I decided to redesign the program and recode C++ language. I wanted to display my abilities to take an existing program and rewrite the program in a different language.

During design and engineering of the program I learned to taking my time and working on one problem at a time to make sure each step worked correctly. For example what steps that were required when asking the user for the user id, if the user id is correct, or the user inputted "exit" and if they exceeded three attempts to log the user out of the system. Making sure the user cannot passing the user id ensure that a threat actor cannot keep inputting an incorrect user id to attempt to discover the users password. Another change when rewriting was I added functions. For example lines 246 change string function, which is a block of code which only runs when it is called, that converts user id input from either all captial or a combination between captial or lower case letters to all lower case letters.

Zoo Autetication Unified Modeling Language (UML) Sequence is a diagram how the rewritten code performs. This provides soem with a visualization design of the system.

Since C++ lanuage did not have a parasing function I had a block of code that would read the credential text file and pull the information I needed to validate user credentials. Within this block of code there are different algorithms and data structures that are used to parase out the information. Starting at line 64 the block of code I use an array to sort and find the information within the credential file. Once the information is in the array it is accessable when required to compare to the user inputes to validate their credentials.

1. [Zoo Authentication](https://github.com/JBFetters/ZooAuthentication)
2. Zoo Authentication UML Sequence

<img src="https://raw.githubusercontent.com/JBFetters/J.Barrett-Fetters/main/UML%20Sequence.JPG" width="936" height="624">


## DATABASES

To improve the newly re-written Zoo Authentication System was to design and implement a database. From the four text files the system uses the credential file is the one that was taken to create the database. The credential file holds the user credentials, user id, password, password hashed and their role within the zoo. Creating the credential database SQLite syntax to create the database, table and populate the table with the information from the text file. DAD-220, Introduction to Structured Database Environment, was the course that helped me learn SQL, how to manipulate, analyze, construct and query the data.

The process for this artifact was first create the credential database and second incorporated the database into the Zoo Authentication System code. To incorporate the database a function was created to query the database to pull the information required to validate the user credentials for successful logon. As before all conditions were tested as before to ensure the user could logon successfully to the correct system per their role.

1. [Credential Database](https://github.com/JBFetters/Credentials-Database)
2. [Zoo Authentication with Database](https://github.com/JBFetters/ZooAuthenticationDatabase)

 




You can use the [editor on GitHub](https://github.com/JBFetters/JBFetters/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown //files.
[Link](url) and ![Image](src)
