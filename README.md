# Experiment 03: Time Table

## AIM:
To Write a html webpage page to display your timetable.

## ALGORITHM:

### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

## CODE:
```html
<!DOCTYPE html>
<html>
<head>
<title> Slot Timetable </title>
</head>
<body>
<center>
<image src="/static/images/logo.png/" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding ="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - PRAJEETH K T (212222110034)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>

</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>FREE SLOT</td>
<td>C</td>
<td>FWAD</td>
<td> FWAD </td>
<td>FWAD</td> 
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>PQM</td>
<td>PQM</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td >CC</td>
<td>FREE SLOT</td>
<td>DE</td>
<td>DE</td>
<td>PHY</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>SNM</td>
<td>PHY</td>
<td>C</td>
<td>FREE SLOT</td>
<td>SNM</td>
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
<td>C PROGRAMMING (PYTHON)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EE404</td>
<td>DIGITAL ELECTRONICS (DE)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA222</td>
<td>PROBABILITY AND QUEUEING MODELS (PQM)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY702</td>
<td>CREATIVE SKILLS FOR COMMUNICATION (CC)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19MA211</td>
<td>STATISTICS AND NUMERICAL METHODS (SNM)</td>
</tr>
<td align="center">7.</td>
<td align="center">19PH214</td>
<td>PYHSICS FOR QUANTUM COMPUTING (PHY) </td>
</tr>
</table>
</body>
</html>
```
## OUTPUT:
![](/timetable/static/images/output.png)

## HTML VALIDATOR:
![](/timetable/static/images/valid.png) 

## RESULT:
The program for creating slot time table is completed successfully.