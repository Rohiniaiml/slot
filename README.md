# Ex03 Time Table
## Date:21.11.2024

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


# PROGRAM
```
<table border="2" cellspacing="12" cellpadding="12">
    <caption>Timetable</caption>
    <tr bgcolor="cyan">
        <th>time & day</th>
        <tr>MON</th>
        <th>TUE</th>
        <th>WED</th>
        <th>THUR</th>
        <th>FRI</th>
        <th>SAT</th>
    </tr> 
    <tr>
        <td>8-10</td>
        <td>free slot</td>
        <td>FWAD</td>
        <td>python</td>
        <td>free slot</td>
        <td>phy</td>
        <td>english</td>
    </tr>
    <tr>
        <td>10-12</td>
        <td>DE</td>
        <td>phy</td>
        <td>english</td>
        <td>python</td>
        <td>free slot</td>
        <td>python</td>
    </tr>
    <tr>
        <td>1-3</td>
        <td>free slot</td> 
        <td>python</td> 
        <td>free slot</td>
        <td>DE</td> 
        <td>WEB</td>
        <td>WEB</td>
</tr>
</table><table border="2" cellspacing="12" cellpadding="12">
    <caption>Marksheet</caption>
    <tr bgcolor="cyan">
        <th>S.No</th>
        <th>Name</th>
        <th>Subject</th>
        <th>Marks</th>
    </tr>
    <tr>
        <td>1</td>
        <td>AAA</td>
        <td bgcolor="yellow">WEB</td>
        <td>98</td>
    </tr>
    <tr>
        <td>2</td>
        <td>BBB</td>
        <td>C PROG</td>
        <td>96</td>
    </tr>
</table>
```

## OUTPUT
![Screenshot (3)](https://github.com/user-attachments/assets/251ccb7f-a429-4086-b764-6c19ab6cef82)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
