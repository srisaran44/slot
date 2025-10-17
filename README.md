# Ex03 Time Table
## Date:07/10/2025

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

<hTml>
    <head>
        <title>WEB EX3</title>
    </head>
    <body>
        <img src="slotapp/tableapp/tableapp/static/logo.png" align="center" width="300" height="70" >
        <pre>
            SLOT TIMETABLE SRISARAN(25015592)
        </pre>

        <table border="2">

            <tr bgcolor="red">
                <th>TIME/DAY</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr>
                <th bgcolor="black">8AM-10AM</th>
                <td colspan="2" align="center">FREE SLOT</td>
                <td>WEB</td>
                <td colspan="2" align="center">FREE SLOT</td>
                <td>WEB</td>
            </tr>
            <tr>
                <th bgcolor="blue">10AM-12PM</th>
                <td>PYN</td>
                <td>C.ENG</td>
                <td>WEB</td>
                <td>C.ENG</td>
                <td colspan="2" align="center">FREE SLOT</td>
            </tr>    
            <tr>
                <th bgcolor="green">12PM-1PM</th>
                <td colspan="6" align="center">LUNCH TIME</td>
            </tr>
            <tr>
                <th bgcolor="violet">1PM-3PM</th>
                <td colspan="2" align="centre">PYN</td>
                <td>MENTOR_MENTEE</td>
                <td>PYN</td>
                <td colspan="2" align="center">WEB</td>
            </tr>
            <tr>
                <th bgcolor="yellow">3PM-5PM</th>
                <td colspan="3" align="center">C>ENG</td>
                <td>PYN</td>
                <td>FREE SLOT</td>
                <td>C.ENG</td>
            </tr>
            
        </table>
        <br>
        <br>
        
        <table border="2">
            <tr bgcolor="yellow">
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>WEB APPLICATIONS</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI304</td>
                <td>PYTHON PROGRAMMING</td>
            </tr>
        </table>
    </body>
</html>

```

## OUTPUT
<img width="1920" height="1020" alt="WEB EX3 and 1 more page - Personal - Microsoft​ Edge 17-10-2025 23_05_35" src="https://github.com/user-attachments/assets/c497d5e8-ca70-4928-bb08-994a1d39334b" />
<img width="1920" height="1020" alt="Welcome - Visual Studio Code 17-10-2025 23_06_30" src="https://github.com/user-attachments/assets/51017fc7-2739-4b1a-adda-6c67a1244ca9" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
