# Ex.05 Book Cover Page Design
## Date:2/11/25

## AIM:
To design a book back cover page using HTML and CSS.

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
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Book Cover</title>
<style>
  body {
    margin: 0;
    padding: 0;
    font-family: "Times New Roman", serif;
    background: linear-gradient(to bottom right, white);
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .book-cover {
    width: 500px;
    height: 700px;
    background: linear-gradient(to bottom right, red, yellow);
    border: 10px solid red;
    box-shadow: 0 0 20px rgba(0,0,0,0.5);
    position: relative;
    color: white;
    padding: 40px;
  }

  .section {
    margin-bottom: 25px;
  }

  .top {
    font-size: 20px;
    border-bottom: 1px solid white;
    padding-bottom: 5px;
  }

  .title {
    text-align: center;
    font-size: 32px;
    font-weight: bold;
    margin-top: 60px;
    line-height: 1.3;
  }

  .subtitle {
    text-align: center;
    font-size: 20px;
    margin-top: 15px;
  }

  .special {
    position: absolute;
    bottom: 90px;
    left: 30px;
    font-weight: bold;
    font-size: 25px;
  }

  .author {
    position: absolute;
    bottom: 30px;
    left: 30px;
    font-size: 25px;
    font-weight: bold;
  }

  .publisher {
    position: absolute;
    bottom: 30px;
    right: 30px;
    font-size: 16px;
  }

  .photo {
    position: absolute;
    bottom: 40px;
    right: 60px;
    border: 2px solid white;
  }

  .photo img {
    width: 200px;
    height: 200px;
  }
</style>
</head>
<body>
  <div class="book-cover">
    <div class="section top">SEC Insights</div>

    <div class="section title">
      FUNDAMENTALS OF<br>
      WEB APPLICATION<br>
      DEVELOPMENT
    </div>

    <div class="section subtitle">
      Deep Dive in HTML, CSS & JS Basics<br>
      Top seller of 2025
    </div>

    <div class="photo">
      <img src="c:\Users\admin\Downloads\MY photo.png" alt="MY Photo">
    </div>

    <div class="special">SPECIAL EDITION</div>
    <div class="author">AT ABHISHEK</div>
  </div>
</body>
</html>
```



## OUTPUT:

<img width="1911" height="1141" alt="image 2" src="https://github.com/user-attachments/assets/9585c3ba-b8e8-47d8-b175-74ce520c6755" />



## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
