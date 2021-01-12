#panda-commarce-bootstrap
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Panda commerse</title>
    <link rel="stylesheet" href="CSS/bootstrap.min.css">
    <link rel="stylesheet" href="CSS/style.css">
    
</head>
<body>
    <header class="container">
        <nav class="navbar navbar-expand-lg sticky-top navbar-light bg-light">
        <div class="container-fluid">
            <img src="images/logo.png" alt="">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
              <a class="nav-link" href="#shoes">Shoes</a>
              <a class="nav-link" href="#backpack">Backpack</a>
              <a class="nav-link " href="#subscribe" tabindex="-1" aria-disabled="true">Subscribe</a>
            </div>
          </div>
        </div>
      </nav>

      <div id="carouselExampleControls" class="carousel slide panda-slide mt-5" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="row d-flex align-items-center p-5">
                <div class="col-md-7">
                    <h1>MEGA LCD TV For Sports</h1>
                    <p>This is the best tv in the world for people who just want to waste time in front of tv.</p>
                    <h3>$1200</h3>
                    <button class="btn btn-warning">BUY NOW</button>
                </div>
                <div class="col-md-5">
                    <img src="images/banner-images/tv.png" class="d-block w-100" alt="...">
                </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row d-flex align-items-center p-5">
                <div class="col-md-7">
                    <h1>Cool Dude Headphone</h1>
                    <p>This is the best headphone in the world for people who just want to waste time in front of funky world.</p>
                    <h3>$420</h3>
                    <button class="btn btn-warning">BUY NOW</button>
                </div>
                <div class="col-md-5">
                    <img src="images/banner-images/headphone.png" class="d-block w-100" alt="...">
                </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row d-flex align-items-center p-5">
                <div class="col-md-7">
                    <h1>X-Box for your living room</h1>
                    <p>This is the best x-box in the world for people who just want to waste time in front of fake sports.</p>
                    <h3>$600</h3>
                    <button class="btn btn-warning">BUY NOW</button>
                </div>
                <div class="col-md-5">
                    <img src="images/banner-images/xbox.png" class="d-block w-100" alt="...">
                </div>
            </div>
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </a>
      </div>

                  
 
    </header>
    <main class="container">
        <section class="container overflow-hidden mt-5 catagories">
            <div class="row g-5">
              <div class="col">
               <div class="p-3 rounded bg-warning d-flex align-items-center justify-content-around">
                   <h1 class=" text-white">Watch</h1>
                   <img src="images/categories/watch.png" alt="">
                </div>
              </div>
              <div class="col">
                <div class="p-3 rounded bg-success d-flex align-items-center justify-content-around">
                    <h1 class=" text-white">Bag</h1>
                    <img src="images/categories/bag.png" alt="">
                </div>
              </div>
              <div class="col">
                <div class="p-3 rounded bg-primary d-flex align-items-center justify-content-around">
                    <h1 class=" text-white">Shoes</h1>
                    <img src="images/categories/shoes.png" alt="">
                </div>
              </div>
            </div>
        </section>

        <section id="shoes" class="mt-5">
            <h3>Shoes</h3>
            <div class="row row-cols-1 row-cols-md-3 g-4">
                <div class="col">
                  <div class="card supply-card h-100 shadow">
                    <img src="images/shoes/shoe-1.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Supply 350</h5>
                      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                    </div>
                    <div class="card-footer supply-card footer">
                      <button class="btn btn-warning">Buy Now >></button>
                    </div>
                  </div>
                </div>
                <div class="col">
                  <div class="card supply-card h-100 shadow">
                    <img src="images/shoes/shoe-2.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Nike 350</h5>
                      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    </div>
                    <div class="card-footer supply-card footer">
                        <button class="btn btn-warning">Buy Now >></button>
                    </div>
                  </div>
                </div>
                <div class="col">
                  <div class="card supply-card h-100 shadow">
                    <img src="images/shoes/shoe-3.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Red AirMax 350</h5>
                      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
                    </div>
                    <div class="card-footer supply-card footer">
                        <button class="btn btn-warning">Buy Now >></button>
                    </div>
                  </div>
                </div>
              </div>
        </section>

        <section id="backpack" class="mt-5">
            <h3>Backpack</h3>
            <div class="row row-cols-1 row-cols-md-3 g-4">
                <div class="col">
                  <div class="card h-100 shadow">
                    <img src="images/bags/bag-1.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Red Laltu Bag</h5>
                      <h5>$120</h5>
                      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                    </div>
                    <div class="card-footer">
                      <button class="btn btn-warning">Buy Now >></button>
                    </div>
                  </div>
                </div>
                <div class="col">
                  <div class="card h-100 shadow">
                    <img src="images/bags/bag-2.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Blue Niltu Bag</h5>
                      <h5>$320</h5>
                      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    </div>
                    <div class="card-footer">
                        <button class="btn btn-warning">Buy Now >></button>
                    </div>
                  </div>
                </div>
                <div class="col">
                  <div class="card h-100 shadow">
                    <img src="images/bags/bag-3.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Black Kaltu Bag</h5>
                      <h5>$169</h5>
                      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
                    </div>
                    <div class="card-footer">
                        <button class="btn btn-warning">Buy Now >></button>
                    </div>
                  </div>
                </div>
              </div>
        </section>

        <section id="subscribe" style="height: 200px;" class="bg-info d-flex justify-content-center align-items-center mt-5">
            <div>
            <h1>LET'S STAY IN TOUCH</h1>
            <h5>Get updates on sales, specials and more</h5>
            <input type="text" placeholder="Enter Your Email Address">
            <button>Submit</button>
            </div>
        </section>
    </main>
    <footer class="text-center mt-5">
        <small >©2020. Panda Commerce. All rights reserved. Sofia, Bulgaria.</small>
    </footer>
    <script src="JS/bootstrap.min.js"></script>
</body>
</html>
