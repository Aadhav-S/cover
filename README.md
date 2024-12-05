# Ex.06 Book Front Cover Page Design
## Date:26/11/2024

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
### HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="./cover.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Web Design Poster</title>
    <link rel="stylesheet" href="book.css">
</head>
<body>
    <div class="poster">
        <div class="header">
            <h5>EXPERT INSIGHT</h5>
            <h5>THIRD EDITION</h5>
            <h5>BOOK COVER</h5>
        </div>
        <div class="content">
            <h1>JAVASCRIPT</h1>
            <p>
                JavaScript is a dynamic, high-level programming language primarily used for creating interactive and responsive web pages. It enables features like dynamic content updates, form validation, and animation within web browsers. As one of the core technologies of the web, alongside HTML and CSS, JavaScript is essential for modern front-end and back-end development (via Node.js).


                
            </p>
        </div>
        <div class="edition">
            
        </div>
        <div class="author">
         
            <p>NAME:AADHAV <br>
                REF.NO:24005747
            </p>
        </div>
        <div class="wave">
            <div class="image"><img src="./24005747.jpg" alt="image"></div>
        </div>
        <div class="footer">
            <p></p>
        </div>
    </div>
</body>
</html>

```


### CSS:

```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    color: white;
    background-color: #ffffff;
}

.poster {
    width: 600px;
    height: 800px;
    margin: 50px auto;
    position: relative;
    background: #2d2231;
    border: 2px solid #333;
    padding: 20px;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.header {
    text-align: left;
    font-size: 18px;
    color: #e8ef0c;
    margin-bottom: 20px;
}

.content h1 {
    font-size: 32px;
    font-weight: bold;
    line-height: 1.3;
    margin-bottom: 10px;
}

.content p {
    font-size: 16px;
    line-height: 1.5;
    color: #dcdcdc;
}

.edition {
    font-size: 18px;
    font-weight: bold;
    color: #e8ef0c;
}

.author {
    font-size: 20px;
    font-weight: bold;
    margin-top: auto;
}

.wave {
    position: absolute;
    width: 100%;
    height: 150px;
    bottom: 120px;
    left: 0;
   
    clip-path: polygon(0 100%, 0 0, 100% 0, 100% 100%);
    display: flex;
    flex-direction: row-reverse;
}

.footer {
    text-align: right;
    font-size: 24px;
    font-weight: bold;
    color: white;
}

.image {
    width: 120px;
    height: auto;
    padding-right: 20px;
}

img {
    width: 100%;
}

```


## OUTPUT:

![Screenshot (31)](https://github.com/user-attachments/assets/69fad3fa-41e5-4420-9cc1-ede77b415d12)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
