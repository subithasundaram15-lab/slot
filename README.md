# Ex03 Time Table
## Date:20/09/2025

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
        <title>simplewebserver</title>
    </head>
    <body>
        <img src="logo.png" width="350" height="70">
        <pre>
            <h2>slot timetable subitha (25014966)</h2>
        </pre>

        <table border="2">

            <tr bgcolor="blue">
                <th>time-day</th>
                <th>mon</th>
                <th>tues</th>
                <th>wednes</th>
                <th>thurs</th>
                <th>fri</th>
                <th>sat</th>
            </tr>
            <tr>
                <th bgcolor="blue">8AM-10AM</th>
                <td colspan="2">free slot</td>
                <td>web</td>
                <td colspan="2">free slot</td>
                <td>web</td>
            </tr>
            <tr>
                <th bgcolor="blue">10AM-12PM</th>
                <td>python</td>
                <td>english</td>
                <td>web</td>
                <td>english</td>
                <td colspan="2" >free slot</td>
            </tr>
            <tr>
                <th bgcolor="blue">12PM-1PM</th>
                <td colspan="6">lunch</td>
            </tr>
            <tr>
                <th bgcolor="blue">1PM-3PM</th>
                <td colspan="2" >python</td>
                <td>mentor-mentee</td>
                <td>python</td>
                <td colspan="2">WEB</td>
            </tr>
            <tr>
                <th bgcolor="blue">3PM-5PM</th>
                <td colspan="3">english</td>
                <td>python</td>
                <td>free slot</td>
                <td>english</td>
            </tr>

        </table>
        <br>
        <br>

        <table border="2">
            <tr bgcolor="blue">
                <th>S.NO</th>
                <th>code</th>
                <th>name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>web</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19EN101</td>
                <td>english</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI304</td>
                <td>python</td>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (9).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
