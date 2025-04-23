# Ex03 Time Table
# Date:23-04-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - GOKUL S (212224240045)</title>
</head>
<body>
    <IMG SRC="college logo.png"HEIGHT="100"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - GOKUL S (212224240045)</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>OS</td>
            <td>FREE SLOT</td>
            <td>DE</td>
            <td>OS</td>
            <td>FREE SLOT</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td><EDM/td>
            <td>DE</td>
            <td>EDM</td>
            <td>C PROG</td>
            <td>FWAD</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>C PROG</td>
            <td>PROB</td>
            <td>MENTOR MEET</td>
            <td>SOFT SKILL</td>
            <td>PROB</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>FREE SLOT</td>
            <td></td>
            <td>FWAD</td>
            <td></td>
            <td>EVS</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI304</td>
            <td>FUNDAMENTALS OF C PROGRAMMING (C PROG)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI302</td>
            <td>ENGINEERING DESIGN AND MODELLING (EDM)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19MA222</td>
            <td>PROBABILITY AND QUEUEING MODELS (PROB)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EE404</td>
            <td>DIGITAL ELCTRONICS (DE)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY708</td>
            <td>Soft Skills (SS)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19CS405</td>
            <td>OPERATING SYSTEM (OS)</td>
        <tr>
            <td>8.</td>
            <td>19CY801</td>
            <td>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY (EVS)</tr>
        </tr>

    </table>
</body>
</html>
```
# OUTPUT:
![Screenshot 2025-04-23 150111](https://github.com/user-attachments/assets/f95bd07b-2f57-4172-a1f2-8b31dbb84881)

# RESULT:
The program for creating slot timetable using basic HTML tags is executed successfully.
