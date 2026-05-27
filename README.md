# Ex.05 Book Front Cover Page Design

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
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About the Book</title>

<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family: Arial, sans-serif;
    }

    body{
        background:#f0c6db;
        display:flex;
        justify-content:center;
        align-items:center;
        min-height:100vh;
        padding:20px;
    }

    .container{
    width:700px;
    min-height:650px;
    background-image:url("back2.webp");
    background-size:100% 100%;
    background-position:center;
    background-repeat:no-repeat;

    border:3px solid #e10891;
    border-radius:15px;

    padding:50px;
    color:#16324f;
    position:relative;
    color:#ad0480;

    margin:auto;
    }

    h1{
        color:#c30778;
        font-size:45px;
        margin-bottom:10px;
    }

    .line{
        width:100%;
        height:3px;
        background:#cc6896;
        margin-bottom:25px;
    }

    .content{
        font-size:20px;
        line-height:1.5;
        text-align:justify;
        font-family: Geneva;
    }

    .highlight{
        background:yellow;
        padding:2px 6px;
        font-weight:bold;
    }

    .quote-box{
        margin-top:35px;
        background:rgba(238, 228, 233, 0.7);
        border-left:8px solid #b90766;
        padding:25px;
        text-align:center;
        font-family: serif;
        font-size:28px;
        color:#d24c9f;
        border-radius:5px;
        line-height:1.2;
    }

    .author-box{
    width:600px;
    height:220px;
    margin-top:40px;
    background:rgba(227, 216, 222, 0.85);

    padding:15px;
    border-radius:20px;

    display:flex;
    gap:20px;

    align-items:flex-start;
    line-height:1.2;
    }

    .author-box img{
    width:120px;
    height:120px;

    object-fit:cover;

    border-radius:15px;
    border:2px solid #6b043e;
    }
    .author-details{
    flex:1;
    }

    .author-details h2{

    color:#a10d63;
    font-size:25px;
    margin-bottom:10px;
    }

    .author-details p{
    font-size:18px;
    line-height:1.8;
    font-family: Geneva;
    text-align:justify;
    line-height:1.5;
    }

    .footer{
    margin-top:180px;

    background:#e0779a;
    color:white;

    padding:25px 30px;

    border-radius:0 0 12px 12px;

    display:flex;
    justify-content:space-between;
    align-items:center;
    }

    .publisher{
        font-size:28px;
        font-weight:bold;
        color:#ffd633;
    }

    .country{
        font-size:22px;
        margin-top:5px;
    }

    .price{
        font-size:32px;
        font-weight:bold;
        color:#ffd633;
    }

</style>
</head>

<body>

<div class="container">
    
    <h1>About the Book</h1>
    <div class="line"></div>

    <div class="content">
        This book 
        <span class="highlight">"Creative Web Design Journey"</span> 
        explores the exciting world of modern web development and user interface design. 
        It introduces readers to creative layouts, responsive web pages, animations, 
        and visually attractive websites. Through practical examples and innovative ideas, 
        this book helps students improve their design thinking and coding skills to create 
        beautiful digital experiences.
    </div>

    <div class="quote-box">
        “A great website is where creativity and technology meet together.”
    </div>

    <div class="author-box">

        <!-- Replace your image name here -->
        <img src="MyPhoto.jpg" alt="Author Photo">

        <div class="author-details">
            <h2>Deetchana S</h2>

            <p>
                Deetchana is an enthusiastic learner and creative web designer 
                passionate about building attractive and user-friendly websites. 
                With a strong interest in technology and design, she enjoys exploring 
                modern web development concepts and transforming ideas into visually 
                engaging digital experiences.
            </p>
        </div>

    </div>

    <div class="footer">

        <div>
            <div class="publisher">Dream Tech Publications</div>
            <div class="country">Printed in India</div>
        </div>

        <div class="price">₹499</div>

    </div>

</div>

</body>
</html>
```
# OUTPUT:
<img width="805" height="532" alt="{7517057E-8102-4886-9F04-EC62DDEF3D0E}" src="https://github.com/user-attachments/assets/03e901d6-9007-40ec-b15b-a540a4c0aee4" />

<img width="808" height="537" alt="{582B437B-AAB0-456A-8F6B-046AC54E6C5D}" src="https://github.com/user-attachments/assets/7a750f74-9220-475d-8c4b-f68f2b45d54e" />


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
