# DBI Übung für 23.06.2022 ( best practice )
Übung für den DBI Test am 23.06.22


```html
<!doctype html>
<html lang="en">
  <head>
    <title>DBI Test ( best practice )</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS v5.2.0-beta1 -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css"  integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">

  </head>
  <body>
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
        <div class="container-fluid">
          <h1 style="color: white">Bike Shop</h1>
          <ul class="navbar-nav navbar-right">
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">Kontakt</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="javascript:void(0)">Cart <img class="img-fluid" style="width: 30px;" src="/shoppingCart.png" alt="cart"></a> 
            </li>
          </ul>

        </div>
      </nav>

      <nav class="navbar navbar-expand-sm navbar-dark bg-light">
        <ul class="breadcrumb">
          <li class="breadcrumb-item"><a href="#">Photos</a></li>
          <li class="breadcrumb-item"><a href="#">Summer 2017</a></li>
          <li class="breadcrumb-item"><a href="#">Italy</a></li>
          <li class="breadcrumb-item active">Rome</li>
        </ul> 
      </nav>



      <div class="row">
        <div class="col-sm">
          <div id="demo" class="carousel slide center-block col-sm-6" style="width: 70%; text-align: center;" data-bs-ride="carousel">

            <!-- Indicators/dots -->
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
              <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
              <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
            </div>
          
            <!-- The slideshow/carousel -->
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="/bike1.jpg" alt="Los Angeles" class="d-block w-100 img-responsive">
              </div>
              <div class="carousel-item">
                <img src="/bike2.jpg" alt="Chicago" class="d-block w-100 img-responsive">
              </div>
              <div class="carousel-item">
                <img src="/bike3.png" alt="Third Image" class="d-block img-responsive" style=" width:77%">
              </div>
            </div>
          
            <!-- Left and right controls/icons -->
            <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
              <span class="carousel-control-prev-icon"></span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
              <span class="carousel-control-next-icon"></span>
            </button>
          </div>
        </div>
        <div class="col-sm">
          <div class="card" style="width:400px">
            <div class="card-body">
              <h4 class="card-title">"Wo ist jetzt die Challenge" Bike</h4>
              <p class="card-text">Bestes Bike wenn du eine Challenge haben willst. <br> AHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHhhHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHH </p>
              <a href="#" class="card-link">Add to cart</a>
            </div>
          </div>
        </div>
      </div>
      <h1 style="text-align: center;">Reviews</h1>
      <div class="container mt-5">
        <div class="row" style="margin-left: 9cm;">
          
          
          <div class="col-sm-8">
            <div class="shadow p-4 mb-4 bg-white"><h4>Hosengaxer</h1><p>Vallah bruder war scheiße</p></div>
          </div>
          <div class="col-sm-4">
          </div>
          <div class="col-sm-8">
            <div class="shadow p-4 mb-4 bg-white"><h4>HY</h4><p>War super! Die Challenge war da!</p></div>
          </div>
          <div class="col-sm-4">
          </div>
          <div class="col-sm-8">
            <div class="shadow p-4 mb-4 bg-white"><h4>Manuellsen</h4><p>Digga wir sitzen hier so und dann kommt Karbonat Erol und schreibt "Du Neger"</p></div>
          </div>
        </div>
      </div>

    
      
      
      






    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.5/dist/umd/popper.min.js"  crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.min.js" crossorigin="anonymous"></script>
  </body>
  ```
</html>
