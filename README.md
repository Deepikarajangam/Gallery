# Ex.08 Design of Interactive Image Gallery
# Date: 26-11-2024
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Photo Gallery</title>
    <style>
    body{
        margin: 2%;

        border: 1px solid black;
        background-color: #b3b3b3;
    }
    #image{
    line-height:100px;
        width: 355px;
    height: 170px;
    padding: 100px;
    
        margin:0 auto;
    
    background-image: url('');
    background-repeat: no-repeat;
    color:#FFFFFF;
    text-align: center;
    background-size: 100%;
    margin-bottom:25px;
    font-size: 120%;
    }
    .preview{
        width:10%;
        margin-left:17%;
    border: 9px solid black;
    }
    img{


          width:95%;
    

}
    </style>
</head>
<body>
    <h1>Interactive Photo Gallery</h1>
    
    
    <div class="gallery">
        <img class = "preview" alt = "Night Sky" src = "https://images.pexels.com/photos/1624496/pexels-photo-1624496.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" onmouseover = "upDate(this)" onmouseout = "unDo()">
	<img class = "preview" alt = "Rose" src = "https://images.pexels.com/photos/736230/pexels-photo-736230.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" onmouseover = "upDate(this)" onmouseout = "unDo()">
	<img class = "preview" src = "https://images.pexels.com/photos/2130610/pexels-photo-2130610.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt = "Paris" onmouseover = "upDate(this)" onmouseout = "unDo()">
        <img class = "preview" alt = "Turtle" src = "https://images.pexels.com/photos/5277693/pexels-photo-5277693.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" onmouseover = "upDate(this)" onmouseout = "unDo()">
	<img class = "preview" alt = "Cute Puppy" src = "https://images.pexels.com/photos/3687770/pexels-photo-3687770.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" onmouseover = "upDate(this)" onmouseout = "unDo()">
	<img class = "preview" src = "https://images.pexels.com/photos/1648377/pexels-photo-1648377.jpeg?auto=compress&cs=tinysrgb&w=600" alt = "Baby" onmouseover = "upDate(this)" onmouseout = "unDo()">
    </div>
    <script src="script.js"></script>
    
</body>
</html>




```
# OUTPUT:

![image](https://github.com/user-attachments/assets/12725e94-cf60-40ae-b1d1-4fd581864e63)

# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
