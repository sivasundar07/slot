# Ex03 Time Table
## Date:04/11/2025
## Ref No: 25011320

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
~~~
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - SIVASUNDAR P (25011320)</b></caption>
<tr align="center">
<th bgcolor="red">Day/Time</th>
<th bgcolor="green">Monday</th>
<th bgcolor="pink">Tuesday</th>
<th bgcolor="red">Wednesday</th>
<th bgcolor="pink">Thursday</th>
<th bgcolor="green">Friday</th>
</tr>
<tr align="center">
<th bgcolor="grey">8–10</th>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr align="center">
<th bgcolor="blue">10-12</th>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FREE SLOT</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
</tr>
<tr>
<th bgcolor="red">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="pink">1-3</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>SOFT SKILLS</td>
</tr>
<tr align="center">
<th bgcolor="purple">3-5</th>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
~~~
## OUTPUT
<img width="1909" height="1003" alt="Screenshot 2025-12-04 113644" src="https://github.com/user-attachments/assets/dd7bbd60-0f26-4cc3-89ff-299960e0abad" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
