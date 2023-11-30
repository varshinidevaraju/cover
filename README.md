# Ex.06 Book Front Cover Page Design
## Date:30.11.2023

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
    <title>Artificial Intelligence</title>
    <style>
        .bookpage{

            width: 400px;
            height: 700px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url("https://img.freepik.com/free-photo/ai-generated-concept-human_23-2150688387.jpg?t=st=1701299449~exp=1701303049~hmac=89d2b8a3bdd86cd01aebbd7e6bf32c16f4c574103d3e842530a7dedbec771ddf&w=360");
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
            width:80px;
            font-size:20px;
        
        }
        
        
        .hrstyle{
            width:100px;

        }
        .name{
        
            display: inline;
            position: relative;
            color:cornflowerblue;
            top:170px;
            
            font-family:Georgia;
            font-size: 25px;
        }
        .booktitle{
            color:red;
            font-family: 'Courier New', Courier, monospace;
            font-size:30px;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            color:orange;
            
        }
        .last{
            color:azure;
            font-size: 25px;
            position: relative;
            top:115px;
            left:330px;
            font-family:Bree serif;
            font-weight:bold;
        }
        .above_line{
            color:azure;
            font-size: medium;
            font-family: Bree serif;
            position:relative;
            top:40px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size:40px;
            position: relative;
            top:30px;
        }
        .photo{
            position: relative;
            top: 70px;
            left: 260px;
            width: 30px;
            height: 40px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                INTRODUCTION TO
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>THE A.I.AGE</h1></div>
            <div class="subtitle">
                 A NON-TECHNICAL EXPLANATION OF 
            </div>
            <div class="subtitle">
                 ARTIFICIAL INTELLIGENCE
            </div>

            <div class="photo">
                <img src="varsh_image.jpg" width="140" height="150" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="name">
               <p><b>VARSHINI.D</b></p>
            </div>
            <div class="last">
                SEC
            </div>
            <div class="above_line">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        

</html>

```

## OUTPUT:
![output](webpage_ss.png)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
