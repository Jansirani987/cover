# Ex.06 Book Front Cover Page Design
## Date:30.11.2024

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
myapp.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color: aqua (221, 39, 39);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                background-image: url(book.jpg);
                background-size: cover;
            }
            .insight {
                color: aqua (221, 39, 39);
            }
            .hr1 {
                width: 130px;
                color: aqua (221, 39, 39);
            }
            .h1 {
                font-size: larger;
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                position: relative;
                top: 30px;
                color: aqua (221, 39, 39);
            }
            .para {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                top: 40px; 
                color: aqua (221, 39, 39); 
            }
            .edition {
                font-size: large;
                font-family: Arial, Helvetica, sans-serif;
                color:aqua (221, 39, 39);
                top: 90px;
                position: relative;
            }
            .pic {
                position: relative;
                top: 150px;
                left: 250px;
                width: 100px;
                height: 100px;
                background-size: cover;
                color:aqua (221, 39, 39);
            }
            .hr2 {
                position: relative;
                width: 400px;
                top: 200px;
                color: aqua (221, 39, 39);
            }
            .name { 
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                position: relative;
                color: aqua (221, 39, 39);
                top: 210px;
            }
            .pub {
                font-size: large;
                position: relative;
                top: 180px;
                left: 330px;
                color: aqua (221, 39, 39);
            }
        </style>
        <title> Book Front Cover Page  </title>
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hr1">
                <hr>
            </div>
            <div class="h1">
                <h1> A Programmer's Prespective</h1>
            </div>
            <div class="para">
                <p> Efficient Problem-Solving Strategies in Programming </p>
            </div>
            <div class="pic">
                <img src= "jansi.pic.jpg" width="150" height="150" >
            </div>
            <div class="hr2">
                <hr>
            </div>
            <div class="name">
                <p><b>Jansi rani A A</b></p>
            </div>
            <div class="pub">
                <b> SEC </b>
            </div>
            <div class="edition">
                <b> first Edition </b>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (27).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
