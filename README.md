# Ex.05 Book Front Cover Page Design
# Date:09-06-2026
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
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Design</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="cover">

        <div class="top-label">EXPERT INSIGHT</div>

        <h1>
            Responsive Web <br>
            Design with <br>
            HTML5 and CSS
        </h1>

        <p class="subtitle">
            Develop future-proof responsive websites
            using the latest HTML5 and CSS techniques
        </p>

        <img src="book.png" alt="Book Cover">

        <div class="edition">Third Edition</div>

        <div class="bottom-section">
            <div class="author">
                MOUNISH VAMSI KUMAR R
            </div>

            <div class="publisher">
                24003774
            </div>
        </div>

    </div>

</body>
</html>
```
## style.css

```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:#333;
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    font-family:Arial, sans-serif;
}

.cover{
    width:700px;
    background:black;
    color:white;
    padding:30px;
}

.top-label{
    color:orange;
    font-size:18px;
    font-weight:bold;
    border-bottom:2px solid orange;
    width:180px;
    padding-bottom:8px;
    margin-bottom:40px;
}

h1{
    font-size:72px;
    line-height:1.1;
    margin-bottom:25px;
}

.subtitle{
    font-size:22px;
    font-weight:bold;
    margin-bottom:40px;
}

img{
    width:100%;
    height:300px;
    object-fit:cover;
}

.edition{
    color:orange;
    font-size:32px;
    font-weight:bold;
    margin-top:25px;
    padding-bottom:15px;
    border-bottom:2px solid orange;
}

.bottom-section{
    display:flex;
    justify-content:space-between;
    margin-top:20px;
}

.author{
    font-size:32px;
    font-weight:bold;
}

.publisher{
    font-size:32px;
    font-weight:bold;
}
```
# OUTPUT:
<img width="632" height="835" alt="Screenshot 2026-06-09 112114" src="https://github.com/user-attachments/assets/d94b2459-37ea-49f2-83ce-f33357728a19" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
