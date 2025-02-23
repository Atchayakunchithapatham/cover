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
<style>
    .bookpage{
        width: 414px;
        height: 700px;
        color:moccasin;
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(books.jpg);
        background-size: cover;
    }
        
    
    .insight{
        color: gainsboro;
    
    }
    
    
    .hrstyle{
        width:100px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: BlanchedAlmond;
        top:160px;
        
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family:'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 35px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:175px;
        
    }
    .pub{
        font-size: medium;
        position: relative;
        top:135px;
        left:330px;
        color:
    }
    .ed{
        color:salmon;
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:80px;
    
    }
    .subtitle{
        font-family:'Copperplate', 'Papyrus', 'fantasy';
        font-size:large;
        position: relative;
        top:40px;
        text-align: center;
        color:bisque;
    }
    .mypic{
        position: relative;
        top: 120px;
        left: 260px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body>
    <div class="bookpage">
        <div class="insight">
            INSIGHT EXPERIENCE
        </div>
        <div class="hrstyle">
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1> THE ERA OF BITCOIN</h1></div>
            
        <div class="subtitle">
            Unlocking Tomorrow : Money 2.0 -
			 Redefining the future of Wealth.<br>

			Welcome to the future of finance !!.
        </div>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
    <br>
    
    <br>
        <div class="mypic">
            <img src="mypic.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: goldenrod;">
        </div>
        <div class="author">
           <p><b>ATCHAYA.K</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Extended Edition</b>
        </div>
    </div>
    </body>
</html>
```

## OUTPUT:
![Alt text](<book/Screenshot 2023-11-30 223304.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
