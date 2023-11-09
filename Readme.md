Library Management System is a system developed as a prototype for IIT Indore Central Library and manages all operations of a libraray along with providing some social features.
<h2>Developers</h2>

 - Vaibhav Chandra (vaibhavviking)
 - Purnadip Chakrabarti (ChakPC)
 - Komal Kumar (kkomalk)
 - Priyanshu Uttam (uttam509)
 - Tushar Goyal(codemaster2911)

<h2>Tech Stack</h2>

 - Front End: HTML, CSS, Bootstrap, Javascript
 - Backend: NodeJS
 - Database: MySQL

<h2>Project Installation Guide</h2>

 - Clone this repository in your local machine
 - Open terminal in the project directory
 - If you have already installed NodeJS then type 'npm init' (without the single quotes). Else, please install NodeJS first.
 - The keys to our database are not put in this repository. You can build your own database using files in Database folder and 
   type credentials of your MySQL database in server.js
 - After doing above steps, type 'node server' in terminal and open your browser
 - You can now use the project by typing localhost:5000 as url
 - To stop the server, go to the terminal and press Ctrl + C 

<h2>Major Features</h2>

 - Books are put on hold/loan/loan&hold for a particular user depending on a set of pre-defined rules like hold-limit/loan-limit/unpaid fines etc.

<h3>User(Student/Professor)</h3>

 - Request hold on a book
 - Mark a book as favourite/ rate books/ review books
 - Search friends and send friend requests to make community
 - See friend's list of favourite/read books
 - Look for other details regarding loan/hold/loan&hold of a book 

<h3>Librarian</h3>

 - Add/Delete/Update details of book
 - Issue/withdraw books to/from users
 - Collect fines from users
 
