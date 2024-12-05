# Ex.06 Book Front Cover Page Design
## Date: 5.12.2024

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
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Courier New', monospace;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #1e293b, #64748b);
        }

        .book-cover {
    width: 400px;
    height: 600px;
    background: url('light-black-future-technology-book-cover-background-21_769134-409.avif') center/cover no-repeat; /* Add your image URL here */
    border-radius: 15px;
    position: relative;
    overflow: hidden;
    box-shadow: 0 15px 30px rgba(0, 0, 0, 0.5);
    color: white;
}

        

        .cover-content {
            position: absolute;
            inset: 0;
            padding: 30px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .title {
            font-size: 35px;
            font-weight: bold;
            letter-spacing: 3px;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.7);
        }

        .subtitle {
            font-size: 18px;
            font-style: italic;
            color: #d1d5db;
            text-align: center;
            position:relative;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        .edition {
            color: #ffffff;
            font-weight: bold;
            font-size: 16px;
            margin-bottom: 40px;
        }

        .underline {
    margin-bottom: 5px;
    height: 3px;
    width: 50%;
    background-color: #fffcf9; 
    margin-left:0%;
}


        .author {
            text-align: right;
            font-size: 20px;
            font-style:initial;
            margin-top:0cqmax;
            text-shadow: 0 1px 3px rgba(75, 8, 232, 0.6);
        }

        .tagline {
            font-size: 18px;
            margin-top: 10px;
            font-weight: 300;
            text-align: center;
            color: #9ca3af;
            font-style:italic;
        }

        .author-image {
    position: absolute;
    top: 50%;
    right: 20px; 
    transform: translateY(-50%); 
    width: 80px;
    height: 80px;
    border-radius: 50%; 
    background: url('author.jpg.JPG') center/cover no-repeat; 
    border: 2px solid white; 
}


    </style>
</head>
<body>
    <div class="book-cover">
        <div class="abstract-graphic"></div>
        <div class="cover-content">
            <div>
                <div class="title">Fundamentals Of C Program</div>
                <div class="subtitle">"Start your programming journey from C"</div>
            </div>
            <div>
                <div class="author">Srinithi Muthukumar</div>
                <div class="author-image"></div>
                <div class="tagline">Introduction to Basics of C Program</div>
                <div class="edition">First Edition
                    <div class="underline"></div>
                </div>
            </div>
        </div>
    </div>
   </body>
 </html>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-05 224812.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
