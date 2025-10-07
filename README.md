# Ex.06 Book Front Cover Page Design
## Date:7.10.2025

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
```
design.html
<html>
    <head>
          <title>My book</title>
          <link rel="stylesheet" href="style.css">
    </head>
    <body>
          <div class="name">
            <h1>Santhosh Kumar O (25016799)</h1>
          </div>
          <div class="first">
            <div class="heading">
              <h2>SEC Insights</h2>
            </div>
            <div class="title">
              <h1>QUANTUM COMPUTING AND QUANTUM INFORMATION</h1>
              <h3>Witness the Quantum world to redefine Computing</h3>
              <pre>Based on research conducted by 
  eminent scientist Michio Kaku</pre>
            </div>
            <div class="michio">
              <img src="michio.jpg" width="300px" height="250px">
            </div>
            <div class="photo">
              <img src="photo.jpg" width="150px" height="200px">
            </div>
            <div class="horizontal-line"></div>
            <div class="author">
              <pre>Written and published by
   Santhosh Kumar</pre>
            </div>
          </div>
    </body>
</html>

style.css
.first{
    background-image: url(front.jpg);
    margin-top: 10px;
    margin-left: 790px;
    background-size: 650px 950px;
    background-repeat: no-repeat;
    width: 650px;
    height: 950px;
    border-style:groove;
    border:solid 10px black;
    box-shadow: inset 0 0 0 5px red;
    border-radius:2%;
    justify-content: center;
}
.first .heading h2 {
    color: darkturquoise;
    text-decoration:underline;
    margin-left:8px;
}
.first .title h1 {
    color:cornsilk;
    font-size: 50px;
    margin-left: 30px;
    margin-right: 10px;
}
.first .title h3 {
    color:darksalmon;
    font-size: 20px;
    font-style: oblique;
    margin-left: 50px;
    margin-right: 10px;
}
.first .photo img {
    margin-left:450px;
}
.first .title pre {
    color:aliceblue;
    font-style: oblique;
    font-size: 20px;
    margin-left:60px;
}
.first .michio img {
    margin-left: 40px;
}
.first .horizontal-line {
  border-top: 5px solid red; 
  width: 100%; 
  margin: 10px 0; 
}
.first .author {
    margin-left: 40px;
    color:lightcyan;
    font-style: oblique;
    font-size: 20px;
}
.name h1{
    text-align: center;
}
```

## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
