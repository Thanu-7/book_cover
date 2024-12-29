# Ex.06 Book Front Cover Page Design
# Date: 14.11.2024
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
    <title>Book Cover Design</title>
    
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f9;
        }

        .book-cover {
            width: 600px;
            height: 700px;
            background-color: #4b0082;
            color: white;
            display: flex;
            flex-direction: column;
            padding: 20px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            border-radius: 5px;
        }
    
    </style>

</head>

<body>
    
    <div class="book-cover">
        <h3 style="color: yellow;">EXPERT INSIGHT</h3>
        <hr style="color: white; width:35%; margin-left: 0%;" align="left">
        <h1 style="text-align: center; font-size: xx-large; color:greenyellow">Learn Python for Machine Learning, Data Science. </h1>
        <h3 style="color:wheat">Learn python from scratch to advanced level<br> in major domains of tech.</h3>
        {% load static %}
        <img src="{% static 'binarysnake.jpg' %}" alt="Book Cover Image" width="100%" height="250px">
        <h3>THIRD EDITION</h3>
        <hr style="color:white; width:70%; margin-left:0%">
        <img style="margin-right: 0;" src="{% static 'GuidoAvatar.jpg' %}"  align="margin-right" width="60px" height="60px">
        <h2>Guido van Rossum</h2>
    
    </div>

</body>
</html>
```
# OUTPUT:
![alt text](bookcvrsrn.png)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
