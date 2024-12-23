# Ex.06 Book Front Cover Page Design
## Date:5/12/2024

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
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body {
     font-family: Arial, sans-serif;
     margin: 0;
     background-color: #333;
     color: #fff;
     display: flex;
     justify-content: center;
     align-items: center;
     height: 100vh;
        }

    .book-cover {
    background-color: #222;
    width: 750px; 
    height: 700px;
    padding: 20px;
    text-align: center;
    border: 1px solid #444;
    position: relative;
    overflow: hidden;
      }

     .header {
    font-size: 20px;
    color: orange;
    font-weight: bold;
    margin-bottom: 20px;
    }

    .title {
    font-size: 22px;
    font-weight: bold;
    line-height: 2.5;
     } 

    .subtitle {
    font-size: 18px;
    margin: 18px 0;
    color: #ccc;
    }

    .edition {
    font-size: 18px;
    color: orange;
    margin-top: 16px;
    }

    .author {
    font-size: 20px;
    font-weight: bold;
    margin-top: 20px;
    }

    .publisher {
    font-size: 18px;
    color: white;
    font-weight: bold;
    margin-top: 18px;
    background-color: #000;
    display: inline-block;
    padding: 5px 10px;
    }

    .wave {
    background: linear-gradient(90deg, rgba(255, 255, 255, 0.2) 0%, rgba(255, 255, 255, 0.8) 100%);
    height: 100px;
    width: 200%;
    position: a
    bsolute;
    bottom: 60px;
    transform: rotate(-10deg);
       }
    
    .author-photo {
    background: #666 url('C:\Users\admin\Pictures\Saved Pictures\image23.png') no-repeat center center;
    background-size: cover;
    width: 80px;
    height: 80px;
    border-radius: 50%;
    position: absolute;
    bottom: 20px;
    right: 20px;
 }
</style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="book-cover">
        <div class="header">EXPERT INSIGHT</div>
        <div class="title">Responsive Web Design with HTML and CSS</div>
        <div class="subtitle">
    </div>
        <div class="edition">Third Edition</div>
        <div class="author">Ben Frain</div>
        <div class="publisher">Packt</div>
        <div class="wave"></div>
        <div class="author-photo"></div>
    </div>
</body>
</html>


## OUTPUT:
![alt text](<Screenshot 2024-12-05 205832.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
