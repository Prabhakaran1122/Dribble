# Project Responsive Web Design using Bootstrap
## Date:21/05/2025

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
    }

    .hero {
      background-color: #007bff;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }

    .features {
      padding: 50px 0;
    }

    .features .card {
      border: none;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
    }

    .features .card:hover {
      transform: translateY(-5px);
    }

    .gallery {
      padding: 50px 0;
      background-color: #f8f9fa;
    }

    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 15px 0;
    }

    .navbar-light .navbar-nav .nav-link {
      color: black;
      font-weight: 500;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light px-4">
    <a class="navbar-brand" href="#">Dribbble Clone</a>
    <div class="collapse navbar-collapse justify-content-end">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="#">Features</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Gallery</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1>Welcome to Dribbble Clone</h1>
      <p>Showcase your creative projects and find inspiration</p>
      <a href="#gallery" class="btn btn-light mt-3">Explore Gallery</a>
    </div>
  </section>

  <!-- Features Section -->
  <section class="features text-center">
    <div class="container">
      <h2 class="mb-5">Features</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card p-4">
            <h5 class="card-title">Discover</h5>
            <p class="card-text">Explore stunning designs and ideas from creatives worldwide.</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card p-4">
            <h5 class="card-title">Share</h5>
            <p class="card-text">Upload your projects to get feedback and recognition.</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card p-4">
            <h5 class="card-title">Collaborate</h5>
            <p class="card-text">Connect with other designers to work on amazing projects.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery" class="gallery text-center">
    <div class="container">
      <h2 class="mb-5">Gallery</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <img src="img1.jpg" alt="Gallery Image 1">
        </div>
        <div class="col-md-4">
          <img src="img2.jpg" alt="Gallery Image 2">
        </div>
        <div class="col-md-4">
          <img src="img3.jpg" alt="Gallery Image 3">
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Designed and developed by J.F.V.ARPRIYA (AP12224100027). All rights reserved.</p>
  </footer>

</body>
</html>

```


## OUTPUT:
![image](https://github.com/user-attachments/assets/9ef67ec4-ffdf-449f-b0ce-ed17d00ea43e)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
