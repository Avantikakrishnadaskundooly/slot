# Ex03 Time Table
## Date:
15/11/2024

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
<html>
<body>
   <img src="logo.png" height="150" width="900">
<table border="2" cellspacing="2" cellpadding="2">
    <caption>TimeTable Avantika Krishnadas Kundooly 24001601</caption>
    <tr bgcolor="blue">
        <th>Date/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
    </tr>
    <tr>
        <td bgcolor="blue">8-10</td>
        <td>prob</td>
        <td>Web</td>
        <td colspan="3">Free Slot</td>
        <td>edm</td>
    </tr>     
    <tr>
        <td bgcolor="blue">10-12</td>
        <td>edm</td>
        <td>calc</td>
        <td>prob</td>
        <td>career</td>
        <td>Eng</td>
        <td>calc</td>
    </tr>
    <tr>
        <td bgcolor="blue">12-1</td>
        <td colspan="6">Lunch Break</td> 
    </tr>
    <tr>
        <td bgcolor="blue">1-3</td>
        <td>crypto</td>
        <td>crypto</td>
        <td>Mentor meet</td>
        <td>Eng</td>
        <td colspan="2">Web</td>
     </tr>
     <tr>
        <td bgcolor="blue">3-5</td>
        <td colspan="6">Free Slot</td>
     </tr>             
</table>
<br>
<table border="2" cellspacing="15" cellpadding="5">
     <caption>Course</caption>
     <tr bgcolor="green"</tr>
         <th>S.no</th>
         <th>Course code</th>
         <th>Course Name</th>
     </tr>
     <tr> 
         <td>1</td>
         <td>19AI302</td>
         <td>Engineering Design and Modelling</td>
     </tr>
     <tr>
         <td>2</td>
         <td>19AI414</td>
         <td>Fundamentals of Web Application Development</td>
     </tr>
     <tr>
         <td>3</td>
         <td>19CS547</td>
         <td>Fundamentals of Cryptocurrency</td>
     </tr>
     <tr> 
         <td>4</td>
         <td>19EN101</td>
         <td>Communicative English</td>
     </tr>
     <tr>
         <td>5</td>
         <td>19MA201</td>
         <td>Calculas and Matrix Algebra</td>
     </tr>
     <tr>
         <td>6</td>
         <td>19EY708</td>
         <td>Career Development Skills</td>
     </tr>
     <tr> 
         <td>7</td>
         <td>SH7101</td>
         <td>Heritage of Tamils</td>
     </tr>
     <tr>
         <td>8</td>
         <td>19MA222</td>
         <td>Probability and Queueing Models</td>
     <tr> 
         <td>9</td>
         <td>ECA-M-SCOFT</td>
         <td>Mentor Meet</td>
     </tr>
</table>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot (23).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
