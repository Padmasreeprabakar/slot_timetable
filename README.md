# Ex03 Time Table
## Date:23.04.25

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
<head>
    <title>Slot Timetable</title>
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
    <table  width="100" cellspacing="2" border="5" cellpadding="10" bgcolor="lightblue">
        <caption><b>SLOT TIME TABLE </b></caption>
        <br></br>
        <tr align="center">
            <th bgcolor="lightpink">Day/Time</th>
            <th bgcolor="lightpink">Monday</th>
            <th bgcolor="lightpink">Tuesday</th>
            <th bgcolor="lightpink">Wednesday</th>
            <th bgcolor="lightpink">Thursday</th>
            <th bgcolor="lightpink">Friday</th>
        </tr>
        <tr align="center">
            <th bgcolor="plum">8-10</th>
            <td colspan="1">FREE SLOT</td>
            <td> Cloud Security</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</d>
            <td>FREE SLOT</d>


        </tr>
        <tr align="center">
            <th bgcolor="plum">10-12</th>
            <td>C Programming</td>
            <td>EMPD</td>
            <td>Web Development</td>
            <td>C Programming</td>
            <td>FREE SLOT</td>
        </tr>
        <tr align="center">
            <th bgcolor="plum">12-1</th>
            <td colspan="5">L U N C H</td>
        </tr>
        <tr align="center">
            <th bgcolor="plum">1-3</th>
            <td>Computer Architecture</td>
            <td>Probability</td>
            <td>Mentor Meet</td>
            <td>Compute Architecture</td>
            <td>Probability</td>
        </tr>
        <tr align="center">
            <th bgcolor="plum">3-5</th>
            <td colspan="2">FREE SLOT</td>
            <td>Cloud Security</td>
            <td>EMPD</td>
            <td>Web Development</td>
        </tr>
    </table>
    <br></br>
    <table cellspacing="2"  border="3">
        <tr align="center">
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
        </tr>
        
        <tr>
        <td align="center">1.</td>
        <td align="center">19CS416</td>
        <td>Cloud Security</td>
        </tr>
        
        <tr>
        <td align="center">2.</td>
        <td align="center">19A1304</td>
        <td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
        </tr>
        
        <tr>
        <td align="center">3.</td>
        <td align="center">19AIA144</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
        </tr>
        
        <tr>
        <td align="center">4.</td>
        <td align="center">19AI303</td>
        <td>Engineering Mechanics And Product Development </td>
        </tr>
        
        <tr>
        <td align="center">5.</td>
        <td align="center">19MA222</td>
        <td>Probability and Queueing Models </td>
        </tr>
        
        <tr>
        <td align="center">6.</td>
        <td align="center">19HS801</td>
        <td>Human   Values</td>
        </tr>
        <tr>
        <td align="center">7.</td>
        <td align="center">19CS305</td>
        <td>Computer Architecture</td>
        </tr>

        </table>
        
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-04-23 090953.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully
