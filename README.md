# Ex03 Time Table
## Date:1-06-2025

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
    <title>TIMETABLE</title>
    <style>
      :root {
        --primary-color: #006064;       
        --secondary-color: #ffffff;    
        --text-color: #263238;         
        --bg-color: #ffffff;         
        --border-color: #004d40;        
        --header-bg: #0288d1;          
        --header-text: white;          
        --highlight-bg: #01579b;              
        --highlight-text: white;
     }

     body {
       font-family: 'Poppins', sans-serif;
       background: var(--bg-color);         
       color: var(--text-color);          
       padding: 30px;
     }

     .container {
       max-width: 1100px;
       margin: auto;
       background: var(--secondary-color); 
       padding: 50px;
       border-radius: 12px;
       box-shadow: 0 6px 20px rgba(0, 96, 100, 0.2); 
       border: 2px solid var(--border-color);         
     }

     .header {
       text-align: center;
       margin-bottom: 10px;
     }

     .header img {
       max-width: 500px;
       height: auto;
       display: block;
       margin: 0 auto;
     }

     h1 {
       font-size: 35px;
       margin-top: 10px;
       color: var(--primary-color); 
       letter-spacing: 1px;
       font-weight: 600;
       text-transform: uppercase;
     }

     .info {
       text-align: center;
       font-size: 22px;              
       margin-bottom: 20px;          
       font-weight: 600;             
       padding: 10px;                
       background-color: var(--secondary-color);  
     }

     table {
       width: 100%;
       border-collapse: collapse;
       margin-bottom: 30px;
       border-radius: 10px;         
     }

     th, td {
       border: 2px solid var(--border-color);
       padding: 15px;                
       text-align: center;
       font-size: 16px;   
     } 

     th {
       background-color: white;  
       color: var(--text-color);  
       font-weight: 600;                   
     }

     td {
       background-color: #ffffff;           
       color: var(--text-color);           
     }

     td.day {
       background-color: transparent;
       color: var(--text-color);
       font-weight: bold;
     }

     td.break {
       background-color: var(--secondary-color); 
       color: var(--text-color);               
       font-weight: bold;
     }

     .subject-title {
       font-size: 26px;
       text-align: center;
       font-weight: 600;
       margin-bottom: 15px;
       color: var(--primary-color);
     }

     .subject-table th {
       background-color: white;
       color: var(--text-color);
     }

     footer {
       text-align: center;
       margin-top: 20px;
       color: var(--primary-color);
     }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <img src="/static/logo.png" alt="Saveetha Engineering College Logo">
        <h1>TIMETABLE</h1>
    </div>

    <div class="info">
        <strong>NAME:</strong> SACHIN S &nbsp; | &nbsp;
        <strong>REG NO:</strong> 212224040283
    </div>

    <table>
        <thead>
            <tr>
                <th>DAY</th>
                <th>8:00 - 10:00</th>
                <th>10:00 - 12:00</th>
                <th>12:00 - 1:00</th>
                <th>1:00 - 3:00</th>
                <th>3:00 - 5:00</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="day">MONDAY</td>
                <td>Python Programming</td>
                <td></td>
                <td class="break">Break</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td class="day">TUESDAY</td>
                <td></td>
                <td>Principles of Chemistry</td>
                <td class="break">Break</td>
                <td>Communicative English</td>
                <td></td>
            </tr>
            <tr>
                <td class="day">WEDNESDAY</td>
                <td>Python Programming</td>
                <td>Computer Architecture</td>
                <td class="break">Break</td>
                <td>Mentor Meet</td>
                <td></td>
            </tr>
            <tr>
                <td class="day">THURSDAY</td>
                <td></td>
                <td>Principles of Chemistry</td>
                <td class="break">Break</td>
                <td>Communicative English</td>
                <td></td>
            </tr>
            <tr>
                <td class="day">FRIDAY</td>
                <td></td>
                <td></td>
                <td class="break">Break</td>
                <td></td>
                <td>Computer Architecture</td>
            </tr>
        </tbody>
    </table>

    <div class="subject-title">Subject Details</div>
    <table class="subject-table">
        <thead>
            <tr>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
        </thead>
        <tbody>
            <tr><td>19AI301</td><td>Python Programming</td></tr>
            <tr><td>19CY205</td><td>Principles of Chemistry</td></tr>
            <tr><td>19EN101</td><td>Communicative English</td></tr>
            <tr><td>19CS305</td><td>Computer Architecture</td></tr>
        </tbody>
    </table>

    <footer>
         ©2025 Saveetha Engineering College
    </footer>
</div>

</body>
</html>

```

## OUTPUT
![Screenshot 2025-06-01 161453](https://github.com/user-attachments/assets/f395abd7-974b-431a-9c1b-36e95a530bd5)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
