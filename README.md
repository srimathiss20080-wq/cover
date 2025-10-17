# Ex.06 Book Front Cover Page Design
## Date:8.10.2025

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
cover.html
cover.html

<html>
    <head>
        <title>MyBook
        </title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="page">
            
            <div class="insights">
                SEC Insights
            </div>
            <div class="hr">
                <hr>
            </div>
            <div class="title">
             YOGA 
            </div>
            Python Progranmming
            </div>
            <div class="subtitle">
              Python:A beginners guide to python Programming 2025<br>
                            Top Seller of 2025
            <div class="edit">
             FIRST EDITION
             </div>
             <br><hr>
              <div class="name">
              SRIMATHI.S
                </div>
                <div class="bottom">
                    SEC
                </div>
            <div class="pic">
            </div> 
        </div>
    </body>
</html>

style
body{
    display: flex;
    justify-content:center;
    align-items: center;
    height: 100vh;
}     
.page{
    width: 500px;
    height: 700px;
    background-image: url(frontend.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border: 20px solid pink;
    padding:20px;
    box-sizing:border-box;
    background-clip: padding-box;
    position: relative;
       
}

.insights{
   color: #ffff;
    font-size: 18px;
   font-weight: bold;
   margin-bottom: 10px;
}
.hr{
    color: white;
    width: 120px;
    right: 200%;
}
.title{
    color: #ffff;
    font-size: 45px;
     margin: 13px 0 15px 0;
    
   font-weight: bold;
    text-align: center;
    
}
.subtitle{
    color: #ffff;
    font-size: 18px;
    margin-bottom: 40px;
}
.edit{
    color: #ffff;
    font-size: 18px;
    font-weight: bold;
    margin-top: 400px;
}
.name{
    color: #ffff;
    font-size: 16px;
    font-weight: bold;
    margin-top: 5px;
   
}
.bottom{
    color: #ffff;
    position: absolute;
    bottom: 20px;
    right: 60px;
    font-weight: bold;
}
.pic{
    position: absolute;
    bottom:90px;
    left: 75%;
    width: 100px;
    height:100px;
    background: url(myimage.jpg) no-repeat;
    background-size: 80px;

}
```
## OUTPUT:
<img width="744" height="883" alt="Screenshot 2025-10-17 110249" src="https://github.com/user-attachments/assets/8a4317ad-a5fc-48ac-9a0b-456f66be59ab" />

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
