# Ex.06 Book Front Cover Page Design
# Date:26-11-2024
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
    <title>Book Cover</title>
    <style>
    
        body{
            margin: 0;
            padding: 0;
            display: flex; 
            justify-content: center;
            align-items: center; 
            height: 100vh;
            }


        .book-cover {
           position: relative ;
           display: inline-flex;
        }
        .text-overlay {
            position: absolute;
        }
        .class1{
            top:5% ;
            left:5%;
            transform:translate3d(-50%, -50%);
            color: rgb(23, 1, 1);
            font-family: 'Times New Roman', Times, serif;
            font-size: 40px;
        }
        .class2{
            top:92%;
            left:35%;
            color: black;
            font-family: sans-serif;
            font-size: larger;
        }
        .class3{
            top:36%;
            left:25%;
            color:black;
            font-family: cursive;
            font-size: 24px;
        }
        .flower{
             position: absolute;
             bottom: 25%;
             left: 42%;

        }
    </style>
</head>
<body>
    <center>
    <div class="book-cover">
        <div class="text-overlay class1">BLUSH AND BLOOM</div>
        <img src="pink1.jpg" style="display: block; margin: auto;" width="300" height="450">
        <div class="text-overlay class2">Helen Hardt!</div>
        <div class="text-overlay class3">Blooming garden roses</div>
    </div>
     <div class="flower"> 
        <img src="flower rem.png" alt="flower image">
     </div>
    
    </center>
</body>
</html>
```
# OUTPUT:
![Screenshot (37)](https://github.com/user-attachments/assets/ca6da338-588f-495f-94fd-e51ce639960a)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
