# Ex-04-Timetable
## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
<!DOCTYPE html>
<html>
    <head>
        <title>Time Table</title>
    </head>
    <body>
<TABLE BORDER="3" width="1050" bgcolor="white" cellspacing="4" cellpadding="10"> 
    <img src="C:\Users\admin\Downloads\saveetha logo.jpg" width="850" alt="Saveetha Engineering College">
    <TR> 
        <TH colspan="6" align="center" bgcolor="cyan">TIME TABLE</TH>
    </TR>  
    <TR>
        <th colspan="2"><b>Reference Number:</b></th> 
        <th><b>23009929</b></th>
        <th colspan="1.5"><b>Name:</b></th>
        <th colspan="2"><b>K.Madhava reddy</b></th>
    </TR>
    <tr>
        <th>DAYS</th>
        <th>8:00-10:00</th>
        <th>10:00-12:00</th>
        <th width="125">12:00-1:00</th>
        <th>1:00-3:00</th>
        <th>3:00-5:00</th>
    </tr>
    <tr>
        <td>MONDAY</td>
        <td>-</td>
        <td>-</td>
        <td rowspan="4">LUNCH BREAK</td>
        <td>19EN101/Sunitha deva kumari</td>
        <td>19AI303/Sridhar.S</td>
    </tr>
    <tr>
        <td>TUESDAY</td>
        <td>19AI303/Sridhar.S</td>
        <td>19EY701/Evangelin Helen</td>
        <td>19AI301C/Archana S H</td>
        <td>19EE305/John D Britto C</td>
    </tr>
    <tr>
        <td>WEDNESDAY</td>
        <td>19AI301C/Archana S H</td>
        <td>19AI414/Karthi Govindharaju</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>THURSDAY</td>
        <td>19AI414/Karthi Govindharaju</td>
        <td>-</td>
        <td>-</td>
        <td>19AI301C/Archana S H</td>
    </tr>
    <tr>
        <td>FRIDAY</td>
        <td>19EN101/Sunitha Deva kumari</td>
        <td>19AI414/Karthi Govindharaju</td>
        <td>Mentor Meet</td>
        <td>19AI301C/Archana S H</td>
        <td>19EE305/John D Britto C</td>
    </tr>
    </TABLE>
    </body>
</html>  
# OUPUT
"C:\Users\admin\Downloads\Screenshot 2023-11-09 120306.png"
