<!DOCTYPE html>
<html lang="en">
<head>
    <title>My Webpage</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

    <style> 
        @media (max-width: 768px) {
            .welcome {
                padding: 40px !important;
            }

            .welcome h1 {
                font-size: 28px;
            }

            .navbar-brand {
                font-size: 18px;
            }
        }
    </style>
</head>

<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand fw-bold">MyPage</a>

    <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#menu">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="menu">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="welcome bg-primary text-white text-center p-5">
    <h1>Welcome to My Page</h1>
    <p>This is my first Bootstrap webpage</p>
</div>

<div class="container text-center mt-5" id="about">
    <h2>About</h2>
    <p>This webpage is created using HTML and Bootstrap.</p>
</div>

<div class="container text-center mt-5" id="contact">
    <h2>Contact</h2>
    <p>Email: sreedevi@gmail.com</p>
</div>

<footer class="bg-dark text-white text-center p-3 mt-5">
    <p>© 2026 MyPage</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
