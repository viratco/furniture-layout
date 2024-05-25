# furniture-layout

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/style.css">
    <!-- bootstrap link -->
    <link rel="stylesheet" href="	https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
    <!-- bootstrap link -->
</head>
<body>

    <!-- navbar -->

    <div class="container">
        <div class="navbar-top">
            <div class="social-link">
                <i><img src="images/twitter.png" alt="" width="30px"></i>
                <i><img src="images/facebook.png" alt="" width="30px"></i>
                <i><img src="images/google-plus.png" alr="" width="30px"></i>
            </div>
            <div class="logo">
                <h3>FURNITURE</h3>
            </div>
            <div class="icons">
                <i><img src="images/search.png" alt="" width="20px"></i>
                <i><img src="images/heart.png" alt="" width="20px"></i>
                <i><img src="images/shopping-cart.png" alt="" width="25px"></i>


            </div>
        </div>
    </div>

    <!-- navbar -->

<!-- main content -->

<div class="main-content">
    <nav class="navbar navbar-expand-md" id="navbar-color">
        <div class="container"></div>
      
         <!-- Toggler/collapsibe Button -->
         <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
          <span><i><img src="images/menu.png" alt="" width="30px"></i></span>
         </button>
      
         <!-- Navbar links -->
         <div class="collapse navbar-collapse" id="collapsibleNavbar">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Shop</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Top chair</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">chair</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Brands</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
              </li>
          </ul>
         </div>
        </div>
    </nav>

      <div class="content">
        <h1>Make Your Home
            <br> Morden Design
        </h1>
        <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et, illum voluptatibus aperiam nostrum volupt</P>
        <div class="btn1">
            <button>Shop Now</button>
        </div>
      </div>
</div>

<!-- main content -->


</body>
</html>

















CSS FILE-
* {
    margin: 0px;
    padding: 0px;
}

/* nav-bar */
.navbar-top  {
    width: 100%;
    height: 10vh;
    display: flex;
    align-items: center;
    text-align: center;
    justify-content: space-between;

}

.social-link i img {
    margin-left: 10px;
    transition: 0.5s ease;
    cursor: pointer;
}
.social-link i img:hover {
    background-color: rgb(238,224,208);
    border-radius: 50px;
}

@media screen and (max-width:420px) {
    .social-link i img{
        width: 20px;
    }
}

.logo h3 {
    font-weight: bold;
}
@media screen and (max-width:420px) {
    .log h3 {
        font-size: 20px;
    }
}

.icons  i img {
    margin-left: 10px;
    cursor: pointer;
}
@media screen and (max-width:420px) {
    .icons i img {
        width: 20px;
    }
}
/* nav-bar */

/* main content */
.main-content {
    width: 100px;
    height: 90vh;
    background-image: url(/images/background.png);
    background-size: cover;
    background-position: 70%;
}
/* navbar */
/* #navbar-color{
    background-color: rgba(238,224,208);
}
.navbar-nav{
    margin: auto;
}
.nav-link{
    margin-left: 30px;
    font-weight: bold;
    color: black;
    transition: 0.5s ease;
    cursor: pointer;
}
.nav-link:hover{
    color: green;
} */
/* navbar */


/* main content */

 
