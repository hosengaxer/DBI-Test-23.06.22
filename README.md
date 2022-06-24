# DBI Übung für 23.06.2022 ( best practice )
Übung für den DBI Test am 23.06.22


```html
<html lang="en">

<head>

    <title>DBI Test ( best practice )</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS v5.2.0-beta1 -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">

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
                    <a class="nav-link" href="javascript:void(0)">Cart <img class="img-fluid" style="width: 30px;" src="/HTML/BS5/shoppingCart.png" alt="cart"></a>
                </li>
            </ul>

        </div>
    </nav>

    <nav class="navbar navbar-expand-sm navbar-dark bg-light" style="padding-left: 1cm">
        <ul class="breadcrumb">
            <li class="breadcrumb-item"><a href="#">Shop</a></li>
            <li class="breadcrumb-item"><a href="#">Sommer</a></li>
            <li class="breadcrumb-item"><a href="#">Bikes</a></li>
            <li class="breadcrumb-item active">"Wo is da jetzt die Challenge" Bike</li>
        </ul>
    </nav>

    <div class="container">
        <div class="row">
            <div class="col-sm-4 ms-5 mt-5">
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
                            <img src="/HTML/BS5/bike1.jpg" alt="Bike1" class="d-block w-100 img-responsive">
                        </div>
                        <div class="carousel-item">
                            <img src="/HTML/BS5/bike2.jpg" alt="Bike2" class="d-block w-100 img-responsive">
                        </div>
                        <div class="carousel-item">
                            <img src="/HTML/BS5/bike3.png" alt="Bike3" class="d-block img-responsive" style=" width:77%">
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
            <div class="col-sm-4 pt-2">
                <div class="card" style="width:400px">
                    <div class="card-body">
                        <h4 class="card-title">"Wo ist jetzt die Challenge" Bike</h4>
                        <p class="card-text">Bestes Bike wenn du eine Challenge haben willst. <br> AHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHhhHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHH
                        </p>
                        <p>100$ 😂😔</p>
                        <a href="#" class="carad-link">Add to cart</a>
                    </div>
                </div>
            </div>
            <div class="col-sm-4 bg-success mt-2 pb-4" style="border-radius: 1cm; width: 25%">
                <form>
                    <div class="mb-3 mt-3">
                        <label for="email" class="form-label">Email:</label>
                        <input type="email" class="form-control" id="email" placeholder="Enter email" name="email">
                    </div>
                    <div class="mb-3">
                        <label for="add" class="form-label">Adresse:</label>
                        <input type="text" class="form-control" id="add" placeholder="Straße/Gasse und Hausnummer" name="add">
                    </div>
                    <div class="row">
                        <div class="mb-3 col-sm-6">
                            <label for="plz" class="form-label">PLZ:</label>
                            <input type="number" class="form-control w-75" id="plz" placeholder="Postleitzahl" name="plz" size="4" maxlength="4" pattern="[1-9]{4}">
                        </div>
                        <div class="mb-3 col-sm-6">
                            <label for="zahl" class="form-label">Zahlungsmethode:</label>
                            <br>
                            <select name="zahl" id="zahl" class="form-select w-75">
                      <option value="paypl">PayPal</option>
                      <option value="master">MasterCard/Visa</option>
                      <option value="sofort">Sofort</option>
                    </select>
                        </div>
                    </div>
                    <div class="form-check mb-3">
                        <label class="form-check-label">
                    <input class="form-check-input" type="checkbox" name="remember"> Remember me
                  </label>
                    </div>
                    <button type="submit" class="btn btn-primary">Submit</button>
                </form>
            </div>
        </div>
        <br>
        <hr>
        <h1 style="text-align: center;">Reviews</h1>
        <div class="container mt-5">
            <div class="row" style="margin-left: 9cm;">
                <div class="col-sm-8">
                    <div class="shadow p-4 mb-4 bg-white">
                        <h4>Hosengaxer</h1>
                            <p>Vallah bruder war scheiße</p>
                    </div>
                </div>
                <div class="col-sm-4">
                </div>
                <div class="col-sm-8">
                    <div class="shadow p-4 mb-4 bg-white">
                        <h4>HY</h4>
                        <p>War super! Die Challenge war da!</p>
                    </div>
                </div>
                <div class="col-sm-4">
                </div>
                <div class="col-sm-8">
                    <div class="shadow p-4 mb-4 bg-white">
                        <h4>Manuellsen</h4>
                        <p>Digga wir sitzen hier so und dann kommt Karbonat Erol und schreibt "Du Neger"</p>
                    </div>
                </div>
            </div>
        </div>

        <hr><br>
        <h1 style="text-align: center;">Features</h2>
            <br>
            <div class="row ps-5">
                <div class="col-sm-3">
                    <div class="card" style="width:400px; width: 50%">
                        <img class="card-img-top" src="/HTML/BS5/amog.jpg" alt="Card image">
                        <div class="card-body">
                            <h4 class="card-title">Amongi</h4>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3">
                    <div class="card" style="width:400px; width: 50%">
                        <img class="card-img-top" src="/HTML/BS5/money.png" alt="Card image">
                        <div class="card-body">
                            <h4 class="card-title">Only 100$😔</h4>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3">
                    <div class="card" style="width:400px; width: 50%">
                        <div class="card-body">
                            <img class="card-img-top" src="/HTML/BS5/speed.png" alt="Card image" style="padding-bottom: 2.1cm;">
                            <h4 class="card-title">Digga Schnell</h4>
                        </div>
                    </div>
                </div>
                <div class="col-sm-3">
                    <div class="card" style="width:400px; width: 50%">
                        <img class="card-img-top" src="/HTML/BS5/truck.jpg" alt="Card image">
                        <div class="card-body">
                            <h4 class="card-title">Schnell da</h4>
                        </div>
                    </div>
                </div>

            </div>
    </div>


    <br><br>
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
        <div class="container-fluid">
            <ul class="navbar-nav navbar-left">
                <li class="nav-item">
                    <a class="nav-link" href="javascript:void(0)">Bruder hier unten is nix was schaust</a>
                </li>
            </ul>
            <ul class="navbar-nav navbar-right">
                <li class="nav-item">
                    <a class="nav-link" href="javascript:void(0)">Kontakt</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="javascript:void(0)">Cart <img class="img-fluid" style="width: 30px;" src="/shoppingCart.png" alt="cart"></a>
                </li>

            </ul>

        </div>
    </nav>











    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.5/dist/umd/popper.min.js" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.min.js" crossorigin="anonymous"></script>
</body>

</html>
´´´
