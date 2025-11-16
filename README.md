# Ex.06 Book Front Cover Page Design
## Date:

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
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color: rgb(172, 150, 24);
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url(back.jpg) ;
            background-size: cover;
        }
            
        
        .insight{
            color: rgb(108, 22, 134);
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: lightblue;
            top: 270px;
            font-family: Georgia;
            font-size: medium;
            padding-bottom: 20px;
        }
        .booktitle{
            color: rgb(251, 50, 0);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: rgb(20, 128, 128);
            font-size: medium;
            position: relative;
            top: 235px;
            left: 330px;
        }
        .ed{
            color: rgb(28, 120, 120);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color:gold(24, 38, 78);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
        }
        .subtitle2{
            color: rgb(188, 204, 255);
            font-family: Arial, Helvetica, sans-serif;
            font-size: small;
            position: relative;
            top: 250px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <b>SOFTWARE DEVELOPMENT</b>
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1><b>CYBER SECURITY</b></h1></div>
            <div class="subtitle">
                 <b>Streaming cyber crime</b> 
            <div class="subtitle2">
                <b>>> Managing Code Changes Effectively</b><br>
                <b>>> Bridging Development and Operations</b><br>
                <b>>> Ensuring Software Quality</b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\F7FF233E4ED3E6B13C5D5C7A9201E4EC\WhatsApp Image 2025-11-14 at 02.48.51_68d4d5b5.jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(42, 32, 176)">
            </div>
            <div class="author">
               <p><b>RANJITH J (212224230221)</b></p>
            </div>
            <div class="pub">
                SEC 28'
            </div>
        </div>
    </div>
</body>
</html>
    </html>
```   

## OUTPUT:
<img width="1868" height="1012" alt="image" src="https://github.com/user-attachments/assets/739c3948-60fe-4a69-9a6d-c3e10c6be96a" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
