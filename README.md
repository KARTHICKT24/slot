# Ex03 Time Table
## Date:2.4.24

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
    <title>SLOT TIME TABLE - KARTHICK KISHORE T (212223220042)</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 1px auto;
        }

        table + table {
            margin-top: 10px;
        }

        th, td {
            border: 3px solid Black;
            text-align: center;
            padding: 5px;
        }

        img {
            width: 100%;
            height: 10%;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 22px;
        }
    </style>
</head>
<body>
    <img src="logo.png">
    <div class="center-text">
        <p><strong>SLOT TIME TABLE - KARTHICK KISHORE T (212223220042) </strong></p>
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
            <th colspan="1" bgcolor="Cyan">WEB</th>
            <th colspan="1" bgcolor="Cyan">PHY</th>
            <th colspan="1" bgcolor="Cyan">CHE</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">10-12</th>
            <th colspan="1" bgcolor="Cyan">MATHS</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
            <th colspan="1" bgcolor="Cyan">SOFT SKILL</th>
            <th colspan="1" bgcolor="Cyan">PHY</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">12-1</th>
            <th colspan="5" bgcolor="Cyan">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
            <th colspan="1" bgcolor="Cyan">MAT</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">3-5</th>
            <th colspan="2" bgcolor="Cyan">ENGLISH</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
            <th colspan="1" bgcolor="Cyan">CHE</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
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
            <th colspan="2" bgcolor="White">WEB (WEB)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19EN612</th>
            <th colspan="2" bgcolor="White">PUBLIC SPEAKING (ENGLISH)</th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19PH206</th>
            <th colspan="2" bgcolor="White">MATRICES AND ALGEBRA (MATHS)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">4.</th>
            <th colspan="1" bgcolor="White">19CY205</th>
            <th colspan="2" bgcolor="White">PRINCIPLES OF CHEMISTRY IN ENGINEERING (CHE)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">5.</th>
            <th colspan="1" bgcolor="White">19MA201</th>
            <th colspan="2" bgcolor="White">FREE CLASS (FREE SLOT)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">6.</th>
            <th colspan="1" bgcolor="White">19EY701</th>
            <th colspan="2" bgcolor="White">SOFT SKILLS(SOFTSKILL)</th> 
        </tr>
    </table>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot (62).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
