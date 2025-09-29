# Ex03 Time Table
# Date:24/09/2025
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

# PROGRAM
```
<!DOCTYPE html>
 <html>
    <head>
    <title>
        Slot Timetable
    </title>
    </head>
    <body>
        <center>
            <img src="c:\Users\DELL\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\5A4B25AAED25C2EE1B74DE72DC03C14E\WhatsApp Image 2025-09-15 at 08.13.40_3a7a9e91.jpg" height="100" width="540" border="5">
        </center>
        <br>
        <table align="center" width="540" cellspacing="3" cellpadding="4" border="5" bgcolor="white">
            <caption><b><i>SLOT TIME TABLE - MANIKANDAN S (25012138)</i></b></caption>
            <tr align="center">
            <th style="background-color: black;color: white;">Day/Time</th>
            <th style="background-color: gray">8-10</th>
            <th style="background-color: grey">10-12</th>
            <th style="background-color: grey">12-1</th>
            <th style="background-color: grey">1-3</th>
            <th style="background-color: grey">3-5</th>
            </tr>
            <tr align="center">
            <th style="background-color: grey">MONDAY</th>
            <td style="background-color: khaki;">FUNDAMENTALS OF WEB APPLICATION</td>
            <td style="background-color: lightskyblue">-</td>
            <td rowspan="6" style="background-color: crimson;">LUNCH</td>
            <td style="background-color: lightgreen">FUNDAMENTALS OF C PROGRAMMING</td>
            <td style="background-color: lightskyblue">-</td>
            </tr>
            <tr align="center">
            <th style="background-color: grey">TUESDAY</th>
            <td style="background-color: lightsalmon">COMMUNICATIVE ENGLISH</td>
            <td style="background-color: lightsalmon">COMMUNICATIVE ENGLISH</td>
            <td style="background-color: lightskyblue">-</td>
            <td style="background-color: lightskyblue">-</td>
            </tr>
            <tr align="center">
            <th style="background-color: grey">WEDNESDAY</th>
            <td style="background-color: khaki;">FUNDAMENTALS OF WEB APPLICATION</td>
            <td style="background-color: khaki;">FUNDAMENTALS OF WEB APPLICATION</td>
            <td style="background-color: lightgoldenrodyellow">MENTOR MEET</td>
            <td style="background-color: lightgreen">FUNDAMENTALS OF C PROGRAMMING</td>
            </tr>
            <tr align="center">
            <th style="background-color: grey">THURSDAY</th>
            <td style="background-color: lightsalmon">COMMUNICATIVE ENGLISH</td>
            <td style="background-color: lightgreen">FUNDAMENTALS OF C PROGRAMMING</td>
            <td style="background-color: lightsalmon">COMMUNICATIVE ENGLISH</td>
            <td style="background-color: lightgreen">FUNDAMENTALS OF C PROGRAMMING</td>
            </tr>
            <tr align="center">
            <th style="background-color: grey">FRIDAY</th>
            <td style="background-color: lightgreen">FUNDAMENTALS OF C PROGRAMMING</td>
            <td style="background-color: khaki;">FUNDAMENTALS OF WEB APPLICATION</td>
            <td style="background-color: lightskyblue">-</td>
            <td style="background-color: lightskyblue">-</td>
            </tr>
            <tr align="center">
            <th style="background-color: grey">SATURDAY</th>
            <td style="background-color: lightsalmon">COMMUNICATIVE ENGLISH</td>
            <td style="background-color: khaki;">FUNDAMENTALS OF WEB APPLICATIONS</td>
            <td style="background-color: lightsalmon">COMMUNICATIVE ENGLISH</td>
            <td style="background-color: lightskyblue">-</td>
            </tr>
        </table>
        <br>
        <table align="center" width="540" cellspacing="3" cellpadding="4" border="5">
            <tr align="center">
            <th style="background-color: black;color: white;">S.NO</th>
            <th style="background-color: black;color: white;">SUBJECT </th>
            <th style="background-color: black;color: white;">Subject Name</th>
            </tr>
            <tr align="center">
            <td style="background-color: grey;color: white;">1.</td>
            <td style="background-color: grey;color: white;">19A1414</td>
            <td style="background-color: grey;color: white;">Fundamentals of web application</td>
            </tr>
            <tr align="center">
            <td style="background-color: grey;color: white;">2.</td>
            <td style="background-color: grey;color: white;">19A1304</td>
            <td style="background-color: grey;color: white;">Fundamentals of c programming</td>
            </tr>
            <tr align="center">
            <td style="background-color: grey;color: white;">3.</td>
            <td style="background-color: grey;color: white;">19EN101</td>
            <td style="background-color: grey;color: white;">Communicative english</td>
            </tr>
    </body>
 </html>
 ```
# OUTPUT
![alt text](image-1.png)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
