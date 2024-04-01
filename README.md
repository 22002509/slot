# Ex03 Time Table
## Date: 01.04.2024

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
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - PRASANNA.R (212222040120)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>WEB</td>
<td> FREE SLOT</td>
<td>CD</td>
<td>ML</td>
<td>CE</td>
<td>TOC</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>CD</td>
<td>TOC</td>
<td> FREE SLOT </td>
<td>CE</td>
<td>ML</td>
<td>ENG</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>ENG</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>MAT</td>
<td>MAT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>WEB</td>
<td>FREE SLOT</td>
<td>WEB</td>
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
<td>Fundamentals of Web Application Development (WEB)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EN102</td>
<td>Technical English (ENG)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS409</td>
<td>Complier Design (CD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS407</td>
<td>Theory of Computation (TOC)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA218</td>
<td>Probability and Queuing Theory (MAT)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI410</td>
<td>Machine Learning (ML)</td>
<tr>
<td align="center">7.</td>
<td align="center">19EC307</td>
<td>Communication Engineering (CE)</td>
</tr>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](slot.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
