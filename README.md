# EX01 Developing a Simple Webserver
## Date:30.03.24

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
   
    from http.server import HTTPServer, BaseHTTPRequestHandler
content = """
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GT</title>
        a{
            padding: 10px;
            text-decoration: none;
            color:white;
            font-family: arial;
            font-size: 18px;
        }
        a:hover{
            color: rgb(242, 44, 44);
        }   
    </style>
</head>
<body style="background-color:black;">
     <div style="display:flex">
        <div style="width: 20%"><img style="width: 70%" src="logo.webp"></div>
        <div style="width: 55%;padding-top: 13px    ">
            <a href=" ">Home</a>
            <a href="">Tourist Places On Paris</a>
            <a href="">Effiel Tower</a>
            <a href="">Lovure Musem</a>
            <a href="">Best Hotel</a>
            <a href="">Fun Activites</a>
        </div>  
        <div style="width: 20%;padding-top: 8px">
            <input style="width: 80%;height: 30px;background-image: url('search.jpeg');background-color: white; background-size: contain;background-repeat: no-repeat;padding-left: 40px;" type="text" placeholder="search" >
        </div>
     </div>
     
     <h1 style="color:black;text-align: center;font-style: italic;font-size: 50px;">Best Toursist Places On Paris</h1>
     <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="c:\Users\admin\Downloads\home pages paris.jpg" class="d-block w-100" alt="..." width="50%">
            </div>
            <div class="carousel-item">
              <img src="c:\Users\admin\Downloads\best places pic.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="c:\Users\admin\Downloads\effiel tower pic.jpeg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="c:\Users\admin\Downloads\lovure musem pic.jpeg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="c:\Users\admin\Downloads\hotel paris pic.jpeg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <img src="c:\Users\admin\Downloads\Disneyland-Paris.jpg" class="d-block w-100" alt="...">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
       <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>  
  </body>
  </html>
```
## OUTPUT:
![Screenshot 2024-03-30 081317](https://github.com/Nandy-nan/simplewebserver/assets/153698914/ae96a21d-cb5c-462d-8609-78490ac0afe6)


## RESULT:
The program for implementing simple webserver is executed successfully.
