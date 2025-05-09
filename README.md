# Ex.06 Book Front Cover Page Design
## Reg.no:212224240029

## Dept:AI/ML

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mind Over Matter Book Cover</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Orbitron', sans-serif;
      background: #121212;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    .book-cover {
      width: 420px;
      height: 620px;
      color: #e0e0e0;
      position: relative;
      background-image: url('imgnew.jpg'); /* Replace with the actual image file name */
      background-size: cover;
      background-position: center;
      border: 2px solid #333;
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.6);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      padding: 40px 30px;
      box-sizing: border-box;
      border-radius: 8px;
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.4);
      z-index: 1;
      border-radius: 8px;
    }

    .content {
      position: relative;
      z-index: 2;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      height: 100%;
    }

    .title {
      font-size: 2.4em;
      font-weight: 700;
      color: #ffffff;
      line-height: 1.3;
      margin-bottom: 10px;
    }

    .tagline {
      font-size: 1.1em;
      font-style: italic;
      color: #d0d0d0;
    }

    .author-section {
      margin-top: auto;
      text-align: right;
      color: #c1c1c1;
    }

    .author-label {
      font-size: 1em;
      font-weight: 600;
      color: #d0d0d0;
      margin-bottom: 5px;
    }

    .author {
      font-size: 1.3em;
      font-weight: 500;
    }

    .bottom-bar {
      height: 4px;
      background: #333;
      width: 100%;
      position: absolute;
      bottom: 0;
      left: 0;
      z-index: 2;
      border-radius: 0 0 8px 8px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="overlay"></div>
    <div class="content">
      <div>
        <div class="title">Mind Over Matter</div>
        <div class="tagline">Unlocking the Power of Mental Resilience</div>
      </div>
      <div class="author-section">
        <div class="author-label">AUTHOR:</div>
        <div class="author">Deepak Kumar V</div>
      </div>
    </div>
    <div class="bottom-bar"></div>
  </div>
</body>
</html>
```



## OUTPUT:

![Screenshot 2025-05-09 105641](https://github.com/user-attachments/assets/ef0c7f5c-0fbd-489b-b761-2f8f9b8b65eb)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
