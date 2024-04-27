# Ex.06 Book Front Cover Page Design
## Date:

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
<html>

<head>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color:white;
    }

    .book-cover {
      width: 500px;
      height: 700px;
      background-color:black;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      margin: 50px auto;
      position: relative;
    }
    
    .book-cover .insight {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 24px;
      font-weight: bold;
      color: azure;
    }
    .book-cover .line1
    {
      position: absolute;
      top: 40px;
      left: 10px;
      width: 80px;
    }
    .book-cover .title1 {
      position: absolute;
      top: 80px;
      left: 50px;
      font-size: 40px;
      font-weight: bold;
      color:  white;
    }
    .book-cover .title2 {
      position: absolute;
      top: 50px;
      left: 60px;
      font-size: 60px;
      font-weight: bold;
      color:  rgb(185, 131, 70);
    }

    .book-cover .subtitle1 {
      position: absolute;
      top: 470px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color:  white;
    }
    .book-cover .subtitle2 {
      position: absolute;
      top: 500px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: white;
    }
    .book-cover .subtitle3 {
      position: absolute;
      top: 530px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: white;
    }
    .book-cover .line2
    {
      position: absolute;
      top: 480px;
      left: 20px;
      width: 160px;
    }
    .book-cover .line3
    {
      position: absolute;
      bottom:38px;
      left: 20px;
      width: 115px;
    }

   

    .book-cover .author {
      position: absolute;
      bottom: 25px;
      left: 55px;
      font-size: 18px;
      color: black;
    }

    .book-cover .number {
      position: absolute;
      bottom: 5px;
      left: 55px;
      font-size: 18px;
      color:black;
    }
    
   


    .book-cover .end {
      position: absolute;
      bottom: 5px;
      right: 50px;
      font-size: 18px;
      color: white;
    }
    .book-cover .mypic
    {
      position: relative;
      top:550px;
      left: 370px;
      width : 8px;
      height: 8px;
      background-size:fit;
    }


    .book-cover .image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top:  0;
      left: 10;
    }
  </style>
</head>

<body>
  <div class="book-cover">
    <img src="bit.jpg" alt="Book Cover Image" class="image">
    <div class="insight">Learn The New Future</div>
    <div class="line1"><hr style="color:rgb(23, 15, 2)"></div>
    <div class="title2">Crypto 101</div>
    <div class="line3"><hr style="color:rgb(8, 5, 0)"></div>
    <div class="mypic"><img src="org.jpg" width="105" height="105" ></div>
    <div class="ed"> <b>Limited Edition</b></div>
    <div class="end">SEC</div>
    <div class="text">If any doubts</div>
    <div class="number">8489442512</div>
    <div class="author">KISHORE B</div>

  </div>
</body>
</html>
```

## OUTPUT:
![image](https://github.com/codedbykishore/cover/assets/147139122/d6e2735a-581d-4c59-9b7d-40c5e0ced821)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
