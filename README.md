# Ex03 Time Table
## Date:22-03-2024

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
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Slot Timetable</title>
    
  </head>

  <body>
    <center>
    <img
        src="/static/logo.png" height="100" width="500"/>
    </center>
    <h3 class="name" align="center" width ="500" cellspacing="3" cellpadding="2">SLOT TIMETABLE - DHANUSHA K (212223040034)</h3>
    <table align="center" width ="500" cellspacing="3" cellpadding="2" border="1" class="table1">
      <tr class="row1"  align="centre">
        <th bgcolor="skyblue">Day/Time</th>
        <th bgcolor="skyblue">Monday</th>
        <th bgcolor="skyblue">Tuesday</th>
        <th bgcolor="skyblue">Wednesday</th>
        <th bgcolor="skyblue">Thursday</th>
        <th bgcolor="skyblue">Friday</th>
        <th bgcolor="skyblue">Saturday</th>
      </tr>
      
        <tr align="center">
        <td bgcolor="lavender">8-10</td>
        <td bgcolor="pink">FWAD</td>
        <td bgcolor="pink">ML</td>
        <td bgcolor="pink">C</td>
        <td bgcolor="pink">JBA</td>
        <td bgcolor="pink">FREE SLOT</td>
        <td bgcolor="pink">ML</td>
      </tr>
      <tr align="center">
        <td bgcolor="lavender">10-12</td>
        <td bgcolor="pink">FREE SLOT</td>
        <td bgcolor="pink">FREE SLOT</td>
        <td bgcolor="pink">PFQC</td>
        <td bgcolor="pink">FREE SLOT</td>
        <td bgcolor="pink">CS</td>
        <td bgcolor="pink">OS</td>
      </tr>
      <tr align="center">
        <td bgcolor="lavender">12-1</td>
        <th colspan="6" class="x" align="center" bgcolor="beige">LUNCH BREAK</th>
      </tr>
      <tr align="center">
        <td bgcolor="lavender">1-3</td>
        <td bgcolor="pink">LC</td>
        <td bgcolor="pink">FREE SLOT</td>
        <td bgcolor="pink">C</td>
        <td bgcolor="pink">FWAD</td>
        <td bgcolor="pink">FWAD</td>
        <td bgcolor="pink">JBA</td>
       
      </tr>
      <tr align="center">
        <td bgcolor="lavender">3-5</td>
        <td bgcolor="pink">OS</td>
        <td bgcolor="pink">PFQC</td>
	    <td bgcolor="pink">JBA</td>
	    <td bgcolor="pink">FREE SLOT</td>
	    <td bgcolor="pink">LC</td>
	    <td bgcolor="pink">FREE SLOT</td>
      </tr>
    </table>
    <br />
    <br />
    <table align="center" width ="500" cellspacing="3" cellpadding="2" border="1" class="table2">
      <tr align="center">
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
      </tr>
      <tr>
        <td align="center">1.</td>
        <td align="center"><b><font color = blue>19AI414</font></b></td>
        <td><b><font color = blue>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</font></b></td>
      </tr>
      <tr>
        <td align="center">2.</td>
        <td align="center">19AI305</td>
        <td >C PROGRAM</td>
      </tr>
      <tr>
        <td align="center">3.</td>
        <td align="center">19AI410</td>
        <td >MACHINE LEARNING</td>
      </tr>
      <tr>
        <td align="center">4.</td>
        <td align="center">19CS405</td>
        <td >OPERATING SYSTEM</td>
      </tr>
      <tr>
        <td align="center">5.</td>
        <td align="center">19EN615C</td>
        <td >JAPANESE BASIC & ADVANCED</td>
      </tr>
      <tr>
        <td align="center">6.</td>
        <td align="center">19EY702</td>
        <td >CREATIVE SKILLS</td>
      </tr>
      <tr>
        <td align="center">7.</td>
        <td align="center">19MA206</td>
        <td >LOGIC AND COMBINATORICS</td>
      </tr>
      <tr>
        <td align="center">8.</td>
        <td align="center">19PH214</td>
        <td >PHYSICS FOR QUANTUM COMPUTING</td>
      </tr>
    </table>
  </body>
</html>
```

## OUTPUT
![Screenshot 2024-03-22 154954](https://github.com/Dhanusha17/slot/assets/151549957/12e6d750-5eb7-4769-ba0b-6c9b6dea570b)
![Screenshot 2024-03-22 154001](https://github.com/Dhanusha17/slot/assets/151549957/cb4ccf42-198f-4f68-a640-e661e4a456d6)
![Screenshot 2024-03-22 155253](https://github.com/Dhanusha17/slot/assets/151549957/9f577fb9-f80d-49f0-94e0-54812b37fec4)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
