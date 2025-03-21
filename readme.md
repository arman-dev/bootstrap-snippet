# Bootstrap snippet

Boilarplate
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <title>...</title>
</head>

<body>
  haerder
  main
  footer

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

### Meta tags for seo
```html
<meta name="description" content="Discover easy and delicious recipes for beginners.">
<meta name="keywords" content="recipes, cooking, beginners">
<meta name="keywords" content="recipes, cooking, beginners">

<meta property="og:title" content="...">
<meta property="og:description" content="...">
<meta property="og:image" content="https://example.com/image.jpg">
<meta property="og:url" content="https://example.com">
```

### Header NavBar

```html
  <header>
    <nav class="navbar navbar-expand-md bg-dark border-bottom border-body" data-bs-theme="dark">
      <div class="container ">
        <a class="navbar-brand" href="/">
          <img src="..." alt="Logo" height="50px">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="/">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">...</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
```
### Caurosel
```html
    <!-- carousel -->
    <div id="carousel-home" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carousel-home" data-bs-slide-to="0" class="active" aria-current="true"
          aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carousel-home" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carousel-home" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="..." class="d-block w-100" alt="slide1">
        </div>
        <div class="carousel-item">
          <img src="..." class="d-block w-100" alt="slide2">
        </div>
        <div class="carousel-item">
          <img src="" class="d-block w-100" alt="slide3">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carousel-home" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carousel-home" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
```


### Grid with cards & Modal
```html
<section class="container mt-5 shadow-lg p-5 rounded-4" id="farming-guide">
    <div class="row">
      <!-- Card 1 -->
      <div class="col-md-4">`
        <div class="card card-hover">
          <img src="..." class="img-fluid w-100" alt="...">
          <div class="card-body">
            <h5 class="card-title">...</h5>
            <p class="card-text">...</p>

            <!-- Button trigger modal -->
            <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modal1">
              See Details
            </button>
          </div>
        </div>
      </div>
      <!-- Card 2 -->
     

    </div>
  </section>

<!-- Modal1 -->
  <div class="modal fade" id="modal1" tabindex="-1" aria-labelledby="modal1Label" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="modal1Label">...</h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <img src="..." class="img-fluid w-100" alt="...">
          <p>...</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        </div>
      </div>
    </div>
  </div>
```
### Single modal
```html
<!-- modal0 -->
  <div class="modal fade" id="modal-ex" tabindex="-1" aria-labelledby="modal0Label" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="modal0Label">...</h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <img src="..." class="img-fluid w-100" alt="...">
          <p>...</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        </div>
      </div>
    </div>
  </div>
```


#### CSS card Hover
```css
.card-hover {
  transition: all 0.2s ease-in-out;
}

.card-hover:hover {
  transform: translateY(-10px);
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
```



