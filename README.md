# Ex.06 Book Front Cover Page Design
# Name : n v mohana krishna
# Date:12/04/25
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
Book.html
```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="book.css">
</head>
<body>
   

<h1>Expert insight</h1>
<hr>
<p align="center"><b>Responsive Web Design with HTML5 and CSS</b></p>
<div class="direct">
  Develop future-proof responsive websites using latest html and css techniques
</div>


<div class="edit">
  Third Edition
  <img src="myphoto.png" alt="">
  <hr>
  
</div>
<div class="name">
    Mohana krishna
</div>


</body>
</html>
```
Book.css
```
body {
    background-image: url("space.png");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    margin-left: 100px;
    color: white;
  }
  
  .edit {
    position: sticky;
    left: 0;
    font-size: 50px;
    color: rgb(247, 82, 12);
      }
  
  h1 {
    color: white;
    font-size: 50px;
  }
  p {
     
     font-size: 100px;
  }
  
  .direct {
    font-size: 50px;
  }
  img {
    bottom: 200px;
    margin-bottom: 100px;
    margin-right: 100px;
    float: right;
  }
  .create {
    position: fixed;
    right: 0;
    margin-bottom: 20px;
    margin-right: 100px;
    bottom: 100px; 
    color: white; 
  }
 .name {
  position: fixed;
  left: 0;
  margin-bottom: 70px;
  margin-left: 100px;
  bottom: 20px; 
  color: white; 
  font-size: 50px;

 }
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/f6ddbfd9-515e-4cc1-acb2-254d2712e107)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
