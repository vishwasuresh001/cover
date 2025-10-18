# Ex.06 Book Front Cover Page Design
## Date:06/10/2025

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
---
book.html
<html>
<head>
  <title>Book  Cover  PAGE </title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="cover">
    <div class="inner-box">
      <h3 class="top">SEC Insights</h3>
      <h1 class="title">CLOUD COMPUTING<br>ENGINEERING<br></h1>
      <p class="subtitle">Deep Dive in HTML,PYTHON &javascripts Basics</p>

      <div class="bottom">
        <p class="special">PREMIUM EDITION</p>
        <div class="line"></div>
        <div class="bottom-row">
          <p class="author">VISHWA(25012636)</p>
          <img class="photo">
          <p class="sec">SEC</p>
        </div>
      </div>
    </div>
  </div>
</body>
</html>


style.css

body{
  margin: 0;
  padding: 0;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #ddd;
}

.cover {
  width: 500px;
  height: 700px;
  background: url("krishna.png");
  border: 8px solid rgb(5, 5, 5); 
  box-sizing: border-box;
  position: relative;
  padding: 10px;
}
 
.inner-box {
  width: 100%;
  height: 100%;
  border: 3px solid rgb(5, 5, 5);
  box-sizing: border-box;
  padding: 30px;
  position: relative;
}

.top {
 color: rgb(24, 24, 23);
  font-weight: bold;
  border-bottom: 2px solid rgb(8, 8, 8);
  display: inline-block;
  padding-bottom: 3px;
  margin-top: 10px;
}

.title {
  color: rgb(42, 148, 240);
  font-weight: bold;
  text-align: center;
  margin-top: 100px;
  line-height: 1.3;
  font-size: 26px;
}

.subtitle {
  color: rgb(10, 10, 10);
  text-align: center;
  margin-bottom: 100px;
}

.bottom {
  position: absolute;
  bottom: 40px;
  left: 30px;
  right: 30px;
}

.special {
  color: rgb(14, 14, 15);
  font-weight: bold;
  margin-bottom: 5px;
}

.line {
  width: 100%;
  height: 2px;
  background-color: rgb(21, 22, 21);
  margin-bottom: 10px;
}

.bottom-row {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.author {
  color: rgb(14, 14, 13);
  font-weight: bold;
}

.photo {
  width: 80px;
  height: 100px;
  border: 2px solid rgb(13, 14, 13);
  background:url("vishwa.png") no-repeat center/cover;
  position: absolute;
  right:0px;
  bottom: 70px;
}

.sec {
  color: rgb(4, 6, 6);
  font-weight: bold;
  bottom: 200px;
  right: 0px;
}
---



## OUTPUT:
![alt text](<vishwa/bookapp/static/Screenshot (58).png>)UT:


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
