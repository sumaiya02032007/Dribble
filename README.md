# Project Responsive Web Design using Bootstrap
## Date:16.10.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribble</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #d9dee3;
    }


    .navbar {
      background-color: rgb(156, 199, 215);
      flex-direction: column;
      align-items: flex-start;
      padding-left: 40px;
      padding-top: 15px;
      padding-bottom: 15px;
    }

    .navbar-brand {
      color: rgb(11, 8, 8);
      font-weight: bold;
      font-size: 24px;
    }

    
    .sub-links {
      display: flex;
      gap: 20px;
      margin-top: 8px;
    }

    .sub-links a {
      color: #1e1a14;
      text-decoration: none;
      font-size: 15px;
      transition: all 0.3s ease;
    }

    .sub-links a:hover {
      color: rgb(210, 177, 177);
      text-decoration: underline;
    }

    
    .controls {
      text-align: center;
      margin: 25px 0;
    }

    .controls a {
      margin: 0 20px;
      font-size: 18px;
      color: #181115;
      text-decoration: none;
      position: relative;
      transition: all 0.3s ease;
      font-weight: 500;
    }

    .controls a::after {
      content: " ▼";
      font-size: 12px;
      color: #6c757d;
    }
    .me-4{
      text-align: right;

    }
    .controls a:hover {
      color: #000;
      border-bottom: 3px solid #9f7684;
      padding-bottom: 5px;
    }

    
    .card img {
      transition: transform 0.3s ease;
    }

    .card:hover img {
      transform: scale(1.05);
    }

    .card {
      border: none;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
      border-radius: 10px;
      overflow: hidden;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card-title {
      font-weight: 600;
      font-size: 15px;
      color: #333;
    }

    

    footer {
      text-align: center;
      padding: 20px;
      color: #333;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  
  <nav class="navbar">
    <div>
      <a class="navbar-brand" href="#">Dribble</a>
      <div class="sub-links">
        <a href="#">Teams</a>
        <a href="#">Designers</a>
        <a href="#">community</a>
        <a href="#">...</a>
      </div>
    </div>
  </nav>
  <div class="me-4">
   <ul class="nav navbar-nav navbar-right"></ul>
        <li>Sign up  &nbsp;
         Sign in
             </li>

        </div>
</nav>

  <nav class="nav navbar-default bg-danger text-white">
    <ul class="nav navbar-nav mx-auto py-3">
        <p class="text-center">What are you working on? <span class="text-light">Dribble desing is intelligence made visible</span></p>
       <li> <button type="button" class="btn btn-primary text-white">Learn More</button>
         <button type="button" class="btn btn-danger">Sign up</button></li>
        
    </ul>
</nav>


  
  <div class="controls">
    <a href="#">Popular</a>
    <a href="#">Shots</a>
    <a href="#">Now</a>
  </div>

  
  <div class="container mt-4">
    <div class="row g-4">
      <!-- Repeat your image cards -->
      <div class="col-lg-2 col-md-4 col-sm-6">
        <div class="card">
          <img src="Creative.png" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">Creative</h6>
            
          </div>
        </div>
      </div>

      <div class="col-lg-2 col-md-4 col-sm-6">
        <div class="card">
          <img src="Discover stories.webp" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">Discover stories</h6>
            
          </div>
        </div> 
      </div>

      <div class="col-lg-2 col-md-4 col-sm-6">
        <div class="card">
          <img src="Futtter.jpg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">Futtter</h6>
            
          </div>
        </div>
      </div>

      <div class="col-lg-2 col-md-4 col-sm-6">
        <div class="card">
          <img src="Growing style.webp" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">Growing style</h6>
            
          </div>
        </div>
      </div>

      <div class="col-lg-2 col-md-4 col-sm-6">
        <div class="card">
          <img src="Learns.gif" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">Learns</h6>
           
          </div>
        </div>
      </div>

      <div class="col-lg-2 col-md-4 col-sm-6">
        <div class="card">
          <img src="New Lunacy.jpg" class="card-img-top" alt="">
          <div class="card-body">
            <h6 class="card-title">New Lunacy</h6>
        
          </div>
        </div>
      </div>
        

  <footer>
    <p>© Designed by S.SUMAIYA(25016731)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2025-10-16 124457.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
