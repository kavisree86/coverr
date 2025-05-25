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
<html>

<head>
    <title>Responsive Web Design</title>
    <style>
        .bookpage {
            width: 400px;
            height: 650px;
            margin: 20px auto;
            padding: 20px;
            font-family: 'Arial', sans-serif;
            color: black;
            background-image: url('bg.jpg'); /* Optional background */
            background-size: cover;
            background-color: #f4f4f4;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }

        .booktitle {
            font-size: 24px;
            font-weight: bold;
            text-align: center;
            margin-top: 10px;
        }

        .subtitle {
            text-align: center;
            font-size: 14px;
            margin: 20px 0;
            background-color: rgba(192, 192, 192, 0.6);
            padding: 10px;
            border-radius: 6px;
        }

        .middle-section {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 30px;
        }

        .logo {
            width: 100px;
            height: auto;
        }

        .author-photo {
            width: 100px;
            height: 120px;
            object-fit: cover;
            border: 2px solid #333;
        }

        .edition {
            text-align: left;
            margin-top: 20px;
            font-weight: bold;
            font-size: 16px;
        }

        .footer {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            font-weight: bold;
            font-size: 14px;
        }
    </style>
</head>

<body>
    <div class="bookpage">
        <div class="booktitle">
            Responsive Web<br>Design with HTML5<br>and CSS
        </div>

        <div class="subtitle">
            Develop future-proof responsive websites using the latest HTML5 and CSS techniques
        </div>

        <div class="middle-section">
            <img src="html-css-logo.png" alt="HTML CSS Logo" class="logo">
            <img src="your-photo.png" alt="Author Photo" class="author-photo">
        </div>

        <div class="edition">Seventh Edition</div>

        <div class="footer">
            <div>KAVISREE S</div>
            <div>SEC</div>
        </div>
    </div>
</body>

</html>
```



## OUTPUT:
![Screenshot (7)](https://github.com/user-attachments/assets/68d2cc2a-2a49-47d2-8155-c26a367f6c74)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
