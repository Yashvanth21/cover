# Ex.05 Book Cover Page Design
## Date:23/02/2026
## Name:yashvanth k
## Reg no:212224245003

## AIM:
To design a book back cover page using HTML and CSS.

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
cover.html
<html>
    <head>
        <title>Book cover page</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body>
        <div class="container">
            <div class="header">
                <h1 align="center">About the Book</h1>
                <hr color="black" size="3" width="80%">
            </div>
            <div class="name">
                <h3>Name of the book:Art of Programming</h3>
            </div>
            <div class="content">
                <p>
                    <br><b>This book provides a comprehensive guide to programming concepts and techniques. It covers various programming languages,algorithms,and best practices for writing efficient and maintainable code. Whether you are a beginner or an experienced programmer,this book offers valuable insights and practical examples to enhance your coding skills.</br><b>
                </p>
            </div>
            <div class="quotes">
                <h4>"Programming isn't about what you know;its about what you can figure out"</h4>
            </div>
            <div class="author">
                <img src="photo.jpeg" width="90" height="100" align="left" hspace="10" vspace="10">
                <h3 color="blue">POPURI SAHITHYA(25004681)</h3>
                <p>Popuri Sahithya,A first year B.tech AIML student who is always passionate towards programming and to solve real life problems with the help of coding.</p>
            </div>
            <div class="footer">
                <h3 fontcolor="yellow">SEC PUBLISHERS</h3>
                <h3 align="right">Price:Rs.300/-</h3>
            </div>
        </div>
    </body>
</html>

styles.css
.container
{
    background:url("background.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height:720px;
    width:600px;
    border:4px solid cyan;
    border-radius: 10px 10px 10px 10px;
}
.header
{
    color:black;
}
.name
{
    background-color:yellow;
    width:53%;
    margin-left: 30px;
}
.content
{
    font-size: 20px;
    padding-left: 20px;
    padding-right: 20px;
}
.quotes
{
    width:500px;
    height: 50px;
    background-color: antiquewhite;
    margin-left: 30px;
    padding-left:20px;
    color:hotpink
}
.author
{
    width:500px;
    height:120px;
    background-color:bisque;
    margin-left: 30px;
    padding-left:20px;
    color:cadetblue;
}
.footer
{
    width:500px;
    height:60px;
    background-color:lightslategray;
    margin-left:30px;
    padding-left:20px;
    padding-bottom:15px;
    margin-top:20px;
    color:yellow;
    bottom: 0px;    
}
```

## OUTPUT:
<img width="826" height="437" alt="Screenshot 2026-02-23 114255" src="https://github.com/user-attachments/assets/dc74dc1c-8e0b-4472-a60a-539e1df49f0f" />


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
