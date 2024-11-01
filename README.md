# Ex03 Time Table
## Date:

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
    <title>SLOT TIME TABLE - SHIVARAM M. (23012359)</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid Black;
            text-align: center;
            padding: 8px;
        }

        img {
            width: 100%;
            height: 15%;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 30px;
        }
    </style>
</head>
<body>
    <img src="logo.png">
    <div class="center-text">
        <p><strong>SLOT TIME TABLE - SHIVARAM M. (23012359)</strong></p>
    </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="Yellow">Day/Time</th>
            <th colspan="1" bgcolor="Yellow">Monday</th>
            <th colspan="1" bgcolor="Yellow">Tuesday</th>
            <th colspan="1" bgcolor="Yellow">Wednesday</th>
            <th colspan="1" bgcolor="Yellow">Thursday</th>
            <th colspan="1" bgcolor="Yellow">Friday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">8-10</th>
            <th colspan="3" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">DBMS</th>
            <th colspan="1" bgcolor="Cyan">QA1</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">10-12</th>
            <th colspan="1" bgcolor="Cyan">CN</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">OS</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">12-1</th>
            <th colspan="5" bgcolor="Cyan">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">DBMS</th>
            <th colspan="1" bgcolor="Cyan">CN</th>
            <th colspan="1" bgcolor="Cyan">OS</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">3-5</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">QA2</th>
            <th colspan="1" bgcolor="Cyan">QA1</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
        </tr>
    </table>

    <table>
        <tr>
            <th colspan="1" bgcolor="White">S. No.</th>
            <th colspan="1" bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">1.</th>
            <th colspan="1" bgcolor="White">19AI41</th>
            <th colspan="2" bgcolor="White">Fundamentals of Web Application Development(FWAD)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19EY710</th>
            <th colspan="2" bgcolor="White">Quantitative Ability -1</th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19CS404</th>
            <th colspan="2" bgcolor="White">Database Management Systems and it's applications</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">4.</th>
            <th colspan="1" bgcolor="White">19CS405</th>
            <th colspan="2" bgcolor="White">Operating System</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">5.</th>
            <th colspan="1" bgcolor="White">19CS406</th>
            <th colspan="2" bgcolor="White">Computer Networks</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">6.</th>
            <th colspan="1" bgcolor="White">19EY711</th>
            <th colspan="2" bgcolor="White">Quantitative Ability -2</th> 
        </tr>
    </table>
</body>
</html>
```

## OUTPUT

<img width="1680" alt="Screenshot 2024-11-01 at 11 22 06 AM" src="https://github.com/user-attachments/assets/8a4d6f9a-9804-403b-b6d2-3cc2cbaa80e4">

<img width="1680" alt="Screenshot 2024-11-01 at 11 20 42 AM" src="https://github.com/user-attachments/assets/141d4ed5-82d0-4339-ad63-d2b2b2cbbeea">

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
