# Ex.06 Book Front Cover Page Design
## Date:06.05.24

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

```
<!DOCTYPE html>
<html>

<head>
    <title>Book Cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cyber.png);
            background-size: cover;
            background-color: rgb(136, 59, 4);
        }
            
        
        .insight{
            color:rgb(0, 83, 83);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(0, 44, 127);
            top:270px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(80, 195, 118);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:rgb(109, 230, 170);
            font-size: medium;
            position: relative;
            top:235px;
            left:330px;
        }
        .ed{
            color:rgb(8, 68, 68);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:190px;
        
        }
        .subtitle{
            color:rgb(201, 203, 107);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                AI&DS/ML
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(77, 46, 0)">
            </div>
            <div class="booktitle">
                <h1>MASTERING THE DATA PARADOX</h1></div>
            <div class="subtitle">
                 The Key To Winning In The AI Age..... 
                 
            </div>
            <div class="subtitle">
                 ARTIFICIAL INTELLIGENCE & MACHINE LEARNING <br>
                 Basics To Mastery!
            </div>
<br><br>
           
            <div class="id">
                <hr style="color:rgb(93, 56, 0)">
            </div>
            <div class="author">
               <p><b>KIRUTHIKA M</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        

</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-05-14 112645.png>)






## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
