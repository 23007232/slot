# Ex03 TIME TABLE
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
## HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="table.css">
</head>
<body>
    <div class="logo">
        <img src="saveetha logo - Copy.jpeg" alt="photo" width="600px">
    </div>
    <div class="table">
        <table>
            <tr class="yellow">
                <td><strong>Day/Time</strong></td>
                <td><strong>Monday</strong></td>
                <td><strong>Tuesday</strong></td>
                <td><strong>Wednesday</strong></td>
                <td><strong>Thursday</strong></td>
                <td><strong>Friday</strong></td>




            </tr>
            <tr >
                <td class="yellow"><strong>8-10</strong></td>
                <td colspan="3">Free slot</td>
                
                <td>Phy</td>
                
                <td>Chem</td>




            </tr>
            <tr>
                <td class="yellow"><strong>10-12</strong></td>
                <td >Ger</td>
                <td >Free slot</td>
                <td >Eng</td>
                
                <td>Phy</td>
                
                <td>Chem</td>

            </tr>
            <tr>
                <td class="yellow"><strong>12-1</strong></td>
                <td colspan="5"><strong>LUNCH</strong></td>
            </tr>
            <tr>
                <td class="yellow"><strong>1-3</strong></td>
                <td >Mat</td>
                <td >Free slot</td>
                <td >Mat</td>
                
                <td>ss</td>
                
                <td>Eng</td>

            </tr>
            <tr>
                <td class="yellow"><strong>3-5</strong></td>
                <td colspan="2" >Free slot</td>
                <td >Mat</td>
                <td >Mat</td>
                
                <td>ss</td>
                
                
            </tr>




        </table>

        <div class="table2">
            <table class="slot" border="2px">
                <tr>
                    <th><strong>S.No</strong></th>
                    <th><strong>Subject Code</strong></th>
                    <th class="name"><strong>Subject Name</strong></th>
                </tr>
                <tr>
                    <td>1.</td>
                    <td>19EE207</td>
                    <td>Quantum Physics</td>
                    
                </tr>
                <tr>
                    <td>2.</td>
                    <td>19CY207</td>
                    <td>Chemistry for Engineering</td>
                    
                </tr>
                <tr>
                    <td>3.</td>
                    <td>19EN612</td>
                    <td>German Basic</td>

                    
                </tr>
                <tr>
                    <td>4.</td>
                    <td>19EN600</td>
                    <td> Environmental Science</td>

                    
                </tr>
                <tr>
                    <td>5.</td>
                    <td>19MA602</td>
                    <td>Probability and Queuing Models</td>

                    
                </tr>
                <tr>
                    <td>6.</td>
                    <td>19EY799</td>
                    <td>Soft Skills</td>

                    
                </tr>





            </table>
        </div>
    </div>
</body>
</html>
```
## CSS:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="table.css">
</head>
<body>
    <div class="logo">
        <img src="saveetha logo.png" alt="photo" width="600px">
    </div>
    <div class="table">
        <table border="2px">
            <tr class="yellow">
                <td><strong>Day/Time</strong></td>
                <td><strong>Monday</strong></td>
                <td><strong>Tuesday</strong></td>
                <td><strong>Wednesday</strong></td>
                <td><strong>Thursday</strong></td>
                <td><strong>Friday</strong></td>




            </tr>
            <tr >
                <td class="yellow"><strong>8-10</strong></td>
                <td colspan="3">Free slot</td>
                
                <td>Phy</td>
                
                <td>Chem</td>




            </tr>
            <tr>
                <td class="yellow"><strong>10-12</strong></td>
                <td >Ger</td>
                <td >Free slot</td>
                <td >Eng</td>
                
                <td>Phy</td>
                
                <td>Chem</td>

            </tr>
            <tr>
                <td class="yellow"><strong>12-1</strong></td>
                <td colspan="5"><strong>LUNCH</strong></td>
            </tr>
            <tr>
                <td class="yellow"><strong>1-3</strong></td>
                <td >Mat</td>
                <td >Free slot</td>
                <td >Mat</td>
                
                <td>ss</td>
                
                <td>Eng</td>

            </tr>
            <tr>
                <td class="yellow"><strong>3-5</strong></td>
                <td colspan="2" >Free slot</td>
                <td >Mat</td>
                <td >Mat</td>
                
                <td>ss</td>
                
                
            </tr>




        </table>

        <div class="table2">
            <table class="slot" border="2px">
                <tr>
                    <th><strong>S.No</strong></th>
                    <th><strong>Subject Code</strong></th>
                    <th class="name"><strong>Subject Name</strong></th>
                </tr>
                <tr>
                    <td>1.</td>
                    <td>19EE207</td>
                    <td>Quantum Physics</td>
                    
                </tr>
                <tr>
                    <td>2.</td>
                    <td>19CY207</td>
                    <td>Chemistry for Engineering</td>
                    
                </tr>
                <tr>
                    <td>3.</td>
                    <td>19EN612</td>
                    <td>German Basic</td>

                    
                </tr>
                <tr>
                    <td>4.</td>
                    <td>19EN600</td>
                    <td> Environmental Science</td>

                    
                </tr>
                <tr>
                    <td>5.</td>
                    <td>19MA602</td>
                    <td>Probability and Queuing Models</td>

                    
                </tr>
                <tr>
                    <td>6.</td>
                    <td>19EY799</td>
                    <td>Soft Skills</td>

                    
                </tr>





            </table>
        </div>
    </div>
</body>
</html>
```
## OUTPUT
![image](https://github.com/23007232/slot/assets/139115574/c84a99a6-a38e-4d84-bb5e-6b92cca78fdd)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
