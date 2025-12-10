# Ex02 Time Table
## Date:10/12/2025

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
<!DOCTYPE HTML>
<html>
    <head>
        <title>Create table</title>
        <style>
            #bg
            {
                background-color: aqua;
                boroder: 1px solid rgb(0, 0, 0);
                text-align: center;
            }
            #sn
            {
                border: 1px solid rgb(2, 2, 2);
                text-align : center;
            }
            #yel
            {
                border: 1px solid rgb(0, 0, 0);
                background-color: yellow;
                text-align: center;
            }
            #pg
            {
                border: 1px solid rgb(0, 0, 0);
                text-align: center;
            }
        </style>
    </head>
    <body>
        <img src="logo.png" alt="Image Not Supported" width="300" height="100">
    </body>
    <body>
        <table id="bg">
            <tr>
                <th id="yel">Day/time</th>
                <th id="yel">Monday</th>
                <th id="yel">Tuesday</th>
                <th id="yel">Wednesday</th>
                <th id="yel">Thursday</th>
                <th id="yel">Friday</th>
            </tr>
            <tr>    
                <td id="yel">8-10</td>
                <td colspan="3" id="pg">Free slot</td>
                <td id="pg">PHY</td>
                <td id="pg">CHEM</td>
            </tr>
            <tr>
                <td id="yel">10-12</td>
                <td id="pg">MATHS</td>
                <td id="pg">PHY</td>
                <td id="pg">CHEM</td>
                <td colspan=2 id="pg">Free slot</td>
                
            </tr>
            <tr>
                <td id="yel">12-1</td>
                <td colspan="5" id="pg">Lunch Break</td>
            </tr>
            <tr>
                <td id="yel">1-3</td>
                <td id="pg">CHEM</td>
                <td id="pg">MATHS</td>
                <td id="pg">PHY</td>
                <td colspan=2 id="pg">Free slot</td>
          
            </tr>
            <tr>
                <td id="yel">3-5</td>
                <td id="pg">CHEM</td>
                <td id="pg">Free slot</td>
                <td id="pg">MATHS</td>
                <td id="pg">PHY</td>
                <td id="pg">Free slot</td>
            </tr>
        
        </table>
    </body>
    <body>
        <table id="sn">
            <tr>
                <th id="sn">S.No </th>
                <th id="sn">Subject Code</th> 
                <th id="sn">Subject Name</th>
            </tr>
            <tr>
                <td id="sn">1</td>
                <td id="sn">19AI401</td> 
                <td id="sn">Fundamentals of webapplication</td>
            </tr>    
            <tr>
                <td id="sn">2</td>
                <td id="sn">19AI402</td> 
                <td id="sn">Data Science</td>
            </tr>
            <tr>
                <td id="sn">3</td>
                <td id="sn">19AI403</td> 
                <td id="sn">Python Programming</td>
            </tr>
            <tr>
                <td id="sn">4</td>
                <td id="sn">19AI404</td> 
                <td id="sn">Database Management System</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](image.png)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.









