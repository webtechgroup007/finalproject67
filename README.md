<!doctype html> 
<html lang="th"> 
  <head> 
    <!-- Required meta tags --> 
    <meta charset="utf-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1"> 
    <!-- Bootstrap CSS --> 
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
          rel="stylesheet" 
          integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
          crossorigin="anonymous"> 
    <style>
      body {
        background-color: #F8F8FF; /* เปลี่ยนสีพื้นหลัง */
      }
      .header {
        background-image: url('https://mir-s3-cdn-cf.behance.net/project_modules/1400_opt_1/c8cc6474724453.5c381da1ee1d0.png');
        background-size: cover;      
        background-position: center; 
        background-repeat: no-repeat; 
        width: 100%;                 
        height: 50vh;                
        display: flex;               
        align-items: center;         
        justify-content: center;     
        color: white;
        text-align: center;
      }
    </style>
    <title>My Favorite Animal</title> 
  </head> 
  <body> 
    <!-- ส่วนหัวที่มีรูปภาพเป็นพื้นหลัง -->
    <div class="header">
      <h1></h1>
      <p></p>
    </div>
    <!-- Navbar เริ่มต้นที่นี่ -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">My Pets</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="สัตว์ของฉัน">Parrot</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="สัตว์ของฉัน">LiverBird</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="สัตว์ของฉัน">แพนด้าแดง</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Navbar จบที่นี่ -->
    <!-- Content เริ่มที่นี่ -->
    <div class="container my-5">
      <h2 class="text-center text-primary">My Favorite Animal</h2>
      <p class="text-center">I love cats, dogs, and many other wonderful creatures!</p>
    </div>
    <!-- Content จบที่นี่ -->
    <!-- Footer เริ่มที่นี่ -->
    <footer class="bg-dark text-white text-center p-3 mt-5">
      © 2025 My Favorite Animals. All rights reserved.
    </footer>
    <!-- Footer จบที่นี่ -->
    <!-- Bootstrap JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
            integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
            crossorigin="anonymous"></script> 
  </body> 
</html>
