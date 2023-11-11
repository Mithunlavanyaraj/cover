# Ex.06 Book Front Cover Page Design
## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap" rel="stylesheet">
        <meta charset="UTF-8">
        <style>

        .bookpage{
            width: 400px;
            height: 650px;
            background-image: url(cover\ bg.jpg);
            background-size: cover;
            color: goldenrod;
            margin-left: auto;
            margin-right: auto ;
            padding: 20px;
            font-family: 'poppins' , sans-serif;
        }
        .insight{
            color:goldenrod;
            margin-top: 2px;
            font-weight: 900;
        }
        .hrstyle{
            width: 100px;
        }

        .author{
            color: white;
            display: inline;
            position: relative;
            color: goldenrod;
            top:190px;
            font-family: 'poppins' , sans-serif;
            font-size: medium;
            font-weight: 900;
        }
        .booktitle{
            font-family: 'poppins' , sans-serif;
            font-size: 20px;
            text-align: center;
            position: relative;
            top: 15px;

        }
        .id{
            width: 400px;
            position: relative;
            top: 200px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 300px;
            font-weight: 900;
        }
        .ed{
            color:goldenrod;
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top:85px;

        }
        .subtitle{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: large;
            position: relative;
            top: 40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover</title>
        </head>
        <body>
            <div class="bookpage">
                <div class="insight">
                    SEC INSIGHT
                </div>
                <div class="hrstyle">
                    <hr style="color: goldenrod;">
                </div>
                <div class="booktitle">
                    <h1> Responsive Web Design with HTML5 and CSS </h1></div>
                <div class="subtitle">
                    Develop future-proof responsive websites using the latest HTML5 and CSS techniques
                </div>
                <div class="mypic">
                    <img src="Profile.jpg" width="127" height="155" alt="profile picture">
                </div>
                <div class="id">
                    <hr style="color:gold;">
                </div>
                <div class="author">
                    <p><b>SEC</b></p>
                </div>
                <div class="pub">
                    MITHUN RAJ M
                </div>
                <div class="ed">
                    <b>Seventh Edition</b>
                </div>
            </div> 
        </body> 
</html>

```
## OUTPUT:

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
