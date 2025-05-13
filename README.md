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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@700&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

    body {
      margin: 0;
      padding: 0;
      background-color: black;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Roboto', sans-serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: #0a0a0a;
      border: 3px solid red;
      padding: 40px 30px;
      box-shadow: 0 0 30px red;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-family: 'Cinzel', serif;
      font-size: 32px;
      color: red;
      text-align: center;
      letter-spacing: 1px;
      text-shadow: 0 0 10px red;
    }

    .subtitle {
      font-size: 16px;
      text-align: center;
      color: #ccc;
      font-style: italic;
      margin-top: 10px;
    }

    .image img {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      margin: 30px 0;
      border-radius: 8px;
      box-shadow: 0 0 15px red;
    }

    .author {
      font-size: 15px;
      text-align: center;
      color: #ff4d4d;
      font-weight: bold;
    }

    .line {
      height: 2px;
      background: red;
      width: 80px;
      margin: 12px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">INTO THE UPSIDE DOWN</div>
      <div class="line"></div>
      <div class="subtitle">A Stranger Tale of Shadows</div>
    </div>
    <div class="image">
      <img src="https://i.pinimg.com/736x/eb/21/31/eb213187c5ebf158ffc7b21e865e5112.jpg">
    </div>
    <div class="author"> LOGU R (212224230141)</div>
  </div>
</body>
</html>
```
## OUTPUT:
![Screenshot 2025-05-13 090305](https://github.com/user-attachments/assets/e6196b99-6780-479f-9202-c32ec38f3e15)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
