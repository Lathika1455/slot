# Ex03 Time Table
## Date:14/03/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SLOT TIME TABLE</title>

</head>
<body>
    <center>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfVHM7lQHBY3fMmzXE1m0bYnMg3dsccFDu2g&s"height="150px"width="500px">
</center>

    <center><h1></h1></center>
    <center><table border="5">   
            <table border=3" bgcolor="cyan" cellspacing="5" cellpadding="5">

        <caption><b>SLOT TIME TABLE - LATHIKA SREE R(24009760)</b></caption>
    <tr align="center">
        <th bgcolor="yellow">Day/Time</th>
        <th bgcolor="yellow">Monday</th>
        <th bgcolor="yellow">Tuesday</th>
        <th bgcolor="yellow">Wednesday</th>
        <th bgcolor="yellow">Thursday</th>
        <th bgcolor="yellow">Friday</th>
    </tr>
    <tr align="center">
        <td bgcolor="yellow">8-10</td>
        <td colspan="3">FREE SLOT</td>
        <td>PHY</td>
        <td>CHE</td>
    </tr>
    <tr align="center">
        <td bgcolor="yellow">10-12</td>
        <td>GER</td>
        <td>FREE SLOT</td>
        <td>FWAD</td>
        <td>FWAD</td>
        <td>PHY</td>
    </tr>
    <tr align="center">
        <td bgcolor="yellow">12-1</td>
        <center><td colspan="5">L U N C H</td></center>
    </tr>
    <tr align="center">
        <td bgcolor="yellow">1-3</td>
        <center><td colspan="2">FREE SLOT</td></center>
        <td>MAT</td>
        <td>MAT</td>
        <td>SS</td>
    </tr>
    <tr align="center">
        <td bgcolor="yellow">3-5</td>
        <td colspan="2">FREE SLOT</td>
        <td>GER</td>
        <td>CHE</td>
        <td>FWAD</td>
    </tr>
</table>
</table></center> 
<br>
<center><table border="3">
<table border="3" cellspacing="5" cellpadding="5">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
    <td> 1. </td>
    <td> 19AI414 </td>
    <td> Fundamentals of Web Applicaton Development(FWAD) </td>
    </tr>
    
    <tr align="center">
    <td> 2. </td>
    <td> 19EN612</td>
    <td> Gernam Basic(GER)</td>
    </tr>
    
    <tr align="center">
    <td> 3. </td>
    <td> 19PH206</td>
    <td> Physics for Information Technology(PHY)</td>
    </tr>
    
    <tr align="center">
    <td> 4. </td>
    <td> 19CY205</td>
    <td> Principles of Chemistry in Engineering(CHE) </td>
    </tr>
    
    <tr align="center">
    <td> 5. </td>
    <td> 19MA201</td>
    <td> Calculas and Matrix Algebra(MAT)</td>
    </tr>
    <tr align="center">
        <td> 6. </td>
        <td>19EY701</td>
        <td>Soft SKills(ss)</td>
        </tr
    </center>
</body>
</html>

## OUTPUT

![ex 3 fwad](https://github.com/user-attachments/assets/7351efc9-ce4a-43d9-adce-159c91a89515)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
