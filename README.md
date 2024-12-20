# Ex.06 Book Front Cover Page Design
## Date:2.12.2024

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
book.html

<!DOCTYPE html>
<html>

<head>
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:red;
            margin-left: auto;
            margin-right: auto;
            padding: 25px;
            font-family: 'georgia', Arial, 'sans-serif';
            background-image: url('bg.png');
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:150px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:blue;
            top: 190px;
            
            font-family:Georgia,serif;
            font-size: medium;
        }
        .booktitle{
            color:red;
            font-family: Georgia;
            font-size: xx-larger;
            text-align: center;
            position: relative;
            top: 5px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 180px;
            
        }
        .pub{
            color: white;
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }
        .ed{
            color:white;
            font-size: medium;
            font-family: georgia;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:red;
            font-family:serif;
            font-size: large;
            position: relative;
            top:20px;
        }
        .mypic{
            position: relative;
            top: 190px;
            left: 320px;
            width: 80px;
            height: 120px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1 style="font-family:georgia; color:blue;">THE FRAMEWORKS BEHIND MODERN INNOVATION</h1></div>
            <div class="subtitle" style="text-align: center;color: beige;">
                 
            </div>
            <div class="subtitle" style="color: rED;text-align: center;">
                 Exploring the Building Blocks of Progress and Creativity
            </div>

            <div class="mypic">
                <img src=  "selva.jpg" width="100 px" height="100px" >
            </div>
            <div class="id">
                <hr>
            </div>
            <div class="author">
               <p>SELVARANI.S</p>
            </div>
            <div class="pub">
                PATHIRANA PUB
            </div>
            <div class="ed">
                <b>THIRD EDITION</b>
            </div>
        </div>
    </body> 

</html>

```

## OUTPUT:
![alt text](<Screenshot (29).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
