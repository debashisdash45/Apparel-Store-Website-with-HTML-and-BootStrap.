# Apparel-Store-Website-with-HTML-and-BootStrap.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apparel Store</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Apparel Store</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Shop</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Banner -->
  <section class="banner text-center text-white d-flex justify-content-center align-items-center">
    <div>
      <h1>New Fashion Collection</h1>
      <p>Explore our latest apparel for all seasons</p>
      <a href="#" class="btn btn-primary">Shop Now</a>
    </div>
  </section>

  <!-- Products Section -->
  <section class="container my-5">
    <h2 class="text-center mb-4">Featured Products</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card">
          <img src="shirt.jpg" class="card-img-top" alt="Shirt">
          <div class="card-body text-center">
            <h5 class="card-title">Classic Shirt</h5>
            <p class="card-text">$29.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="jacket.jpg" class="card-img-top" alt="Jacket">
          <div class="card-body text-center">
            <h5 class="card-title">Stylish Jacket</h5>
            <p class="card-text">$49.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="jeans.jpg" class="card-img-top" alt="Jeans">
          <div class="card-body text-center">
            <h5 class="card-title">Denim Jeans</h5>
            <p class="card-text">$39.99</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2024 Apparel Store. All Rights Reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
