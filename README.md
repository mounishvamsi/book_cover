# Ex.06 Book Front Cover Page Design
# Date: 23/09/2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
{% load static %}
<!DOCTYPE html>
<html>
  <head>
    <title>book_cover</title>
    <style>
      h1{
        font-weight: bold;
      }
      .parent {
        position: relative;
        top: 0;
        left: 0;
      }
      .image1 {
        height: 100%;
        width:30%;
        position: relative;
        top: 0;
        left: 0;
        border: 10px solid #000000;  
        border-radius: 20px;
        margin:auto;

      }
      .image2 {
        position: absolute;
        bottom: 70px;
        right: 1070px;
        height:20%;
        border: 1px solid #000000;
        border-radius: 10px;
        opacity: 0.53 ;
      }
      .title{
        position:absolute;
        bottom: 90px;
        left: 30px;
        color:aliceblue;
        font-size:70px;
        font-weight: bold;
        opacity:0.65;
        
      }
      .title2{
        position:absolute;
        bottom: 90px;
        left: 34px;
        color:aliceblue;
        font-size:70px;
        font-weight: bold;
        opacity:0.3;
        
      }
      .title3{
        position:absolute;
        bottom: 90px;
        left: 26px;
        color:aliceblue;
        font-size:70px;
        font-weight: bold;
        opacity:0.3;
        
      }
       .title4{
        position:absolute;
        bottom: 90px;
        left: 24px;
        color:aliceblue;
        font-size:70px;
        font-weight: bold;
        opacity:0.2;
        
      }
       .title5{
        position:absolute;
        bottom: 90px;
        left: 35px;
        color:aliceblue;
        font-size:70px;
        font-weight: bold;
        opacity:0.2;
        
      }
      
      .author{
        position:absolute;
        bottom:25px;
        right:1130px;
        color:rgb(223, 181, 126);
        font-size:small;

      }
      .quote{
        position:absolute;
        bottom:20px;
        left:30px;
        color:antiquewhite;
        font-size:small;
      }
    </style>
  </head>
  <body>
    <div class="parent">
      <img class="image1" src="{% static 'images/Mona_Lisa.jpg' %}"/>
      <img class="image2" src="{% static 'images/WhatsApp Image 2025-09-23 at 14.16.05_8cbfb3bb.jpg' %}" />
      <h1 class="title">THE<br>DA<span style="opacity:0">--</span>VINCI<br>CODE</h1>
      <h1 class="title2">THE<br>DA<span style="opacity:0">--</span>VINCI<br>CODE</h1>
      <h1 class="title3">THE<br>DA<span style="opacity:0">--</span>VINCI<br>CODE</h1>
      <h1 class="title4">THE<br>DA<span style="opacity:0">--</span>VINCI<br>CODE</h1>
      <h1 class="title5">THE<br>DA<span style="opacity:0">--</span>VINCI<br>CODE</h1>
      <h3 class="author">Author : <br><span style="font-family: arial;">DAN BROWN</span></h3>
      <h4 class="quote"  >History is always written by the winners.<br> When two cultures clash,<br> the loser is obliterated,<br>
         and the winner writes the history books</h4>
    </div>
  </body>
</html>

```
# OUTPUT:
![alt text](<views.py - ex6 - Visual Studio Code 23-09-2025 20_07_18.png>)
![alt text](<views.py - ex6 - Visual Studio Code 23-09-2025 20_07_26.png>)



# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
