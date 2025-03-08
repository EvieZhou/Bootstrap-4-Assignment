# Bootstrap-4-Assignment
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bootstrap 4 Assignment</title>
  <!-- Bootstrap 4 CSS -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css">
  <!-- Optional Custom CSS -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">My Website</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="jumbotron text-center">
    <h1 class="display-4">Welcome to My Bootstrap Website</h1>
    <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
    <a class="btn btn-primary btn-lg" href="#" role="button">Learn More</a>
  </div>

  <!-- Main Content Section -->
  <div class="container">
    <div class="row">
      <div class="col-md-4">
        <h2>Section 1</h2>
        <p>This is the first section of content. You can add more details here.</p>
      </div>
      <div class="col-md-4">
        <h2>Section 2</h2>
        <p>This is the second section of content. Feel free to customize it.</p>
      </div>
      <div class="col-md-4">
        <h2>Section 3</h2>
        <p>This is the third section of content. Add more information as needed.</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3 mt-5">
    <p>&copy; 2023 My Bootstrap Website. All rights reserved.</p>
  </footer>

  <!-- Bootstrap 4 JS and Dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.min.js"></script>
</body>
</html>
