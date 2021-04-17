<!doctype html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
    integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  <link rel="stylesheet" href="styles.css">

  <title>Grupo Cero</title>
</head>

<body>
  <div class="container">
    <div class="row">
      <!--NAV-->
      <header id="header" class="col-12  text-white p-2">
        <nav class="navbar navbar-expand-lg navbar-light bg-transparent p-3">
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto ">
              <li class="nav-item active">
                <a class="nav-link" href="index.html">Inicio <span class="sr-only">(current)</span></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Artistas</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
                  aria-haspopup="true" aria-expanded="false">
                  Tipos de Arte
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <a class="dropdown-item" href="#">Escultura</a>
                  <a class="dropdown-item" href="#">Oleo</a>
                  <a class="dropdown-item" href="#">Renacimiento</a>
                  <a class="dropdown-item" href="#">Romanticismo</a>
                  <a class="dropdown-item" href="#">Abstracto</a>
                </div>
              </li>
              <li class="nav-item">
                <a class="nav-link " href="contactanos.html">Contactanos</a>
              </li>
            </ul>
            <img id="logo-pagina" src="img/logo-pagina2.png" alt="">
            <form class="form-inline my-2 my-lg-0">
              <input class="form-control mr-sm-2" type="search" placeholder="Buscar.." aria-label="Search">
              <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Buscar</button>
            </form>
          </div>
        </nav>

        <!--LOGIN-->
        <div class="container">
            <div id="login" class="row">
              <a href="login_registro/login.html" class="btn btn-success" role="button">Iniciar Sesion</a>
              <a href="login_registro/registro.html" class="btn btn-primary" role="button">Registro</a>
                <h3 id="estado-conexion">Estado : Desconectado</h3>
            </div>
        </div>
      </header>
    </div>


    <!--CARRUSELLLLLLLLL!!!!!!!!!-->
      <div id="carrusel" class="row justify-content-sm-start">
        <div class="col-sm-8">
          <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <a href="into_image/escultura.html">
                  <img src="img/small2.jpg" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <a href="escultura/escultura.html"></a>
                  <img src="img/img2.jpg" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <a href="escultura/escultura.html"></a>
                  <img src="img/escultura3.jpeg" class="d-block w-140" alt="..." class="mx-auto d-block" style="width:100%" >
              </div>
            </div> 
            <a class= "carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
        </div>
        <!--TEXTO ASIDE CARRUSEL-->
        <aside id="text-carrusel">
          <h3>Grupo Cero</h3>
            <p> Somos un grupo de artistas plásticos dedicados a la pintura, escultura, orfebrería, tejido y otras expresiones artísticas</p>
        </aside>
    <!--GALERIA DE IMAGENES-->
    <div id="galeria" class="container">
      <div id="titulo-galeria" class="row justify-content-sm-center text-dark">
        <h2>GALERIA DE IMAGENES</h2>
      </div>
      <div class="row justify-content-sm-center">
        <div id="item-galeria">
          <h3 id="autor-galeria" >Oleo de Paul Landers</h3>
          <img id="imagenes-galeria" src="img/small.jpg" alt="">
        </div>
        <div id="item-galeria">
          <h3 id="autor-galeria" >Grafiti Lorena Sierra</h3>
          <img id="imagenes-galeria" src="img/galeria1.jpg" alt="">
        </div>
        <div id="item-galeria">
          <h3 id="autor-galeria" >Oleo de Paul Landers</h3>
          <img id="imagenes-galeria" src="img/galeria2.jpg" alt="">
        </div>
        <div id="item-galeria">
          <h3 id="autor-galeria" >Oleo de Paul Landers</h3>
          <img id="imagenes-galeria" src="img/galeria3.jpg" alt="">
        </div>
        <div id="item-galeria">
          <h3 id="autor-galeria" >Oleo de Paul Landers</h3>
          <img id="imagenes-galeria" src="img/galeria4.jpg" alt="">
        </div>
        <div id="item-galeria">
          <h3 id="autor-galeria" >Oleo de Paul Landers</h3>
          <img id="imagenes-galeria" src="img/galeria5.jpg" alt="">
        </div>
      </div>
    </div>

      <!-- Optional JavaScript -->
      <!-- jQuery first, then Popper.js, then Bootstrap JS -->
      <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
        integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
        crossorigin="anonymous"></script>
      <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
        integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
        crossorigin="anonymous"></script>
      <script src="index.js"></script>

</body>

</html>
