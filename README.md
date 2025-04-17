# Ex03 Time Table
## Date:17-04-2025

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
<html>
<head>
<title>Timetable</title>
</head>
<title>Google
<div class="Timetable"></div>
</title>
<body>
<center>
<img src="image.png" height="150" width="800">
</center>
<h3 align="center"> SLOT TIME TABLE - ABISHA LINU L(212224040011)
</h3>
<table align="center" border="5" cellpadding="6" cellspacing="2"
bgcolor="cyan">
<tr>
<th bgcolor="yellow">Day</th>
<th bgcolor="yellow">8-10</th>
<th bgcolor="yellow">10-12</th>
<th bgcolor="yellow">12-1</th>
<th bgcolor="yellow">1-3</th>
<th bgcolor="yellow">3-5</th>
</tr>
<tr>
<th bgcolor="yellow">MONDAY </th>
<td>WEB DEVELOPMENT</td>
<td>TASK ASSIGNMENT</td>
<td rowspan="5">L<br>U<br>N<br>C<br>H </td>
<td>FUNDAMENTALS OF AI </td>
<td>FREE SLOT </td>
</tr>
<tr>
<th bgcolor="yellow">TUESDAY </th>
<td>TASK COMPLETION </td>
<td>WEB DEVELOPMENT</td>
<td>MODULE COMPLETION</td>
<td>FREE SLOT </td>
</tr>
<tr>
<th bgcolor="yellow">WEDNESDAY </th>
<td>ASSESSMENT HOUR</td>
<td>TASK PRESENTATION </td>
<td>MENTOR </td>
<td>FREE SLOT </td>
</tr>
<tr>
<th bgcolor="yellow">THURSDAY </th>
<td>TASK PRESENTATION</td>
<td>MODULE COMPLETION</td>
<td>FUNDAMENTALS OF AI</td>
<td>FREE SLOT </td>
</tr>
<tr>
<th bgcolor="yellow">FRIDAY </th>
<td>TASK COMPLETION </td>
<td>WEB DEVELOPMENT</td>
<td>TASK COMPLETION</td>
<td>FREE SLOT </td>
</tr>
<tr>
<th bgcolor="yellow">SATURDAY </th>
<td colspan="5" align="center">MODULE ASSESSMENT COMPLETION </td>
</tr>
</table>
<br>
<table border="5" cellpadding="7" cellspacing="2" align="center">
<tr>
<th>
<h4>S.NO</h4>
</th>
<th>
<h4>SUBJECT CODE </h4>
</th>
<th>
<h4>SUBJECT NAME </h4>
</th>
</tr>
<tr>
<th>1.</th>
<td>4S3-1</td>
<td>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT </td>
</tr>
<tr>
<th>2.</th>
<td>4V1-2</td>
<td>DATASCIENCE</td>
</tr>
<tr>
<th>3.</th>
<td>4I3-1</td>
<td>INTRODUCTION TO MECHIN LEARNING</td>
</tr>
<tr>
<th>4.</th>
<td>4L1-1</td>
<td>FUNDAMENDALS OF AI</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-04-17 210740.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
