# Ex.05 Book Front Cover Page Design
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
  <title>The Art of Doing Nothing - Velan-25005466</title>
  <style>
    body {
      background-color: #f4f4f4;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      font-family: 'Arial Black', 'Arial Bold', sans-serif;
    }

    .book-cover {
      width: 320px;
      height: 480px;
      background-color: #FF4500; /* Vibrant Safety Orange */
      border: none;
      border-radius: 4px;
      padding: 30px;
      position: relative;
      box-shadow: 20px 20px 60px rgba(0,0,0,0.4);
      display: flex;
      flex-direction: column;
      color: #000; /* High contrast black text */
      overflow: hidden;
    }

    /* Modern minimalist "X" watermark */
    .book-cover::before {
      content: "✕";
      position: absolute;
      top: -20px;
      right: -10px;
      font-size: 150px;
      color: rgba(0,0,0,0.1);
      transform: rotate(15deg);
    }

    .title-area {
      margin-top: 40px;
      text-align: left;
      z-index: 2;
    }

    h1 {
      font-size: 42px;
      line-height: 0.9;
      text-transform: uppercase;
      margin: 0;
      letter-spacing: -2px;
    }

    .highlight {
      background-color: #000;
      color: #FF4500;
      padding: 0 5px;
      display: inline-block;
    }

    h2 {
      font-size: 16px;
      text-transform: uppercase;
      margin-top: 20px;
      letter-spacing: 1px;
      font-weight: 900;
    }

    .author {
      position: absolute;
      bottom: 40px;
      left: 30px;
      font-size: 16px; /* Slightly smaller for the longer ID */
      text-transform: uppercase;
      border-top: 4px solid #000;
      padding-top: 10px;
      width: 80%;
      letter-spacing: 1px;
    }
  </style>
</head>
<body>

  <div class="book-cover">
    <div class="title-area">
      <h1>The<br>Art of<br><span class="highlight">Doing</span><br>Nothing</h1>
      <h2>A counter-intuitive guide to actually getting things finished</h2>
    </div>
    
    <div class="author">Velan-25005466</div>
  </div>

</body>
</html>

```

## OUTPUT:
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/7b6aca49-b969-497f-85d8-da54a313d0c4" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
