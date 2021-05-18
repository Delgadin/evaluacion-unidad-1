<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- PAGE settings -->
  <link rel="icon" href="https://templates.pingendo.com/assets/Pingendo_favicon.ico">
  <title>Restaurant Neon - Pingendo template</title>
  <meta name="description" content="Free Bootstrap 4 Pingendo Neon template for restaurant and food">
  <meta name="keywords" content="Pingendo restaurant food neon free template bootstrap 4">
  <!-- CSS dependencies -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" type="text/css">
  <link rel="stylesheet" href="neon.css" type="text/css">
  <!-- Script: Make my navbar transparent when the document is scrolled to top -->
  <script src="js/navbar-ontop.js"></script>
  <!-- Script: Animated entrance -->
  <script src="js/animate-in.js"></script>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
    <div class="container">
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbar3SupportedContent" aria-controls="navbar3SupportedContent" aria-expanded="false" aria-label="Toggle navigation"> <span class="navbar-toggler-icon"></span> </button>
      <div class="collapse navbar-collapse text-center justify-content-center" id="navbar3SupportedContent">
        <ul class="navbar-nav">
          <li class="nav-item mx-3">
            <a class="nav-link text-light" href="#">Menu</a>
          </li>
          <li class="nav-item mx-2">
            <a class="nav-link" href="#acerca"><b>Acerca de mi</b></a>
          </li>
        </ul>
        <a class="btn navbar-btn btn-secondary mx-2 shadowed" href="#contacto"><b>Contacto</b></a>
      </div>
    </div>
  </nav>
  <!-- Cover -->
  <div class="align-items-center d-flex py-5 cover section-fade-in-out" style="background-image: url(&quot;assets/restaurant/cover_dark.jpg&quot;);">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 align-self-center text-lg-left text-center">
          <h1 class="mb-0 mt-4 display-4">
            <font color="red"><span style="background-color: rgb(241, 205, 49);">&nbsp;Felipe Martin Delgado Alvarado</span></font>
          </h1>
        </div>
      </div>
    </div>
  </div>
  <table class="tabla" id="acerca">
    <tbody>
      <tr>
        <td>Nombre: Felipe Martin Delgado Alvarado</td>
        <td>conocimientos</td>
        <td>certificados</td>
      </tr>
      <tr>
        <td>Educacion basica: completa</td>
        <td>Conocimiento alto del idioma ingles</td>
        <td>Certifiacion de ingles avanzado nivel B2</td>
      </tr>
      <tr>
        <td>educacion media: completa</td>
        <td>conocimiento basico en construccion</td>
        <td>certificacion de cisco NETACAD&lt; </td>
      </tr>
      <tr>
        <td> educacion superior: en proceso</td>
        <td> conocimiento basico en lenguajes java, C# y python</td>
        <td> certificacion basada en artes modernos </td>
      </tr>
    </tbody>
  </table>
  <!-- Intro -->
  <div class="py-5 bg-dark" style="">
    <div class="container">
      <div class="row bg-secondary shadowed">
        <div class="p-4 col-md-6 bg-primary animate-in-left" style="">
          <p class="m-0">De todos los errores se aprende.</p>
          <h2 class="mb-3">Felipe Delgado</h2> <i class="fa d-inline-block fa-star text-white"></i><i class="fa d-inline-block fa-star mx-2 text-white"></i><i class="fa d-inline-block fa-star text-white"></i>
          <p class="my-4">No soy una persona particularmente habladora, siento que se me hace de manera mas sencilla oir a la persona que me habla para despues formular una buena charla.<br><br>Bajo esto me gustaria decir que soy una persona detallista y observadora, intento que los proyectos que realizo salgan lo mas perfecto posible, despues de todo prefiero hacer algo bien y completo porque del no ser asi simplemente no continuo.</p>
          <p></p>
          <p></p>
        </div>
        <div class="p-0 col-md-6 animate-in-right" style="">
          <img class="img-fluid d-block" src="https://i.imgur.com/8kJQ6dY.png" alt="estatua1"><img class="img-fluid d-block" src="https://i.imgur.com/DFRpn7H.png" alt="estatua2" style=""> </div>
      </div>
    </div>
  </div>
  <div class="py-5 section-fade-in-out" id="contacto" style="background-image: url(&quot;assets/restaurant/makereservation_dark.jpg&quot;);">
    <div class="container">
      <div class="row animate-in-down">
        <div class="col-lg-6 mx-auto p-3" style="">
          <form class="p-4 bg-primary shadowed" method="post" action="contactoEnviado.html">
            <h4 class="mb-4 text-center"> Contactar </h4>
            <p class="my-4">Introduce tus datos para contactarme.</p>
            <div class="form-group"> <label>Nombre Completo :</label>
              <input class="form-control" placeholder="Ingresar su nombre acá" required=""> </div>
            <div class="form-group" style=""><label>Ingresar Email</label><input type="email" class="form-control" placeholder="Ingresar Email" required=""></div>
            <button type="submit" class="btn mt-4 btn-block p-2 btn-dark">Enviar Contacto </button>
          </form>
        </div>
      </div>
    </div>
  </div>
  <div class="text-center bg-dark">
    <div class="container">
      <div class="row">
        <div class="col-md-4 p-4">
          <h2 class="mb-4">Contact</h2>
          <p class="m-0">
            <a href="tel:+246-5425505462" class="text-white">+2465425505462</a>
          </p>
          <p>
            <a href="mailto:info@pingendo.com" class="text-white">info@pingendo.com</a>
          </p>
        </div>
        <div class="col-md-4 p-4">
          <h2 class="mb-4">Location</h2>
          <p>
            <a href="https://www.google.it/maps" target="blank" class="text-white">23 Fake Street <br>Seattle, WA 00000</a>
          </p>
        </div>
        <div class="col-md-4 p-4">
          <h2 class="mb-4">Openings</h2>
          <p>11:00 - 15:00 &amp; 19:00 - 00:00 Tue/Fri <br>11:00 - 15:00 &amp; 19:00 - 02:00 Sat/Sun</p>
        </div>
      </div>
      <div class="row">
        <div class="col-12 mt-3">
          <p class="text-muted">© Copyright 2018 Pingendo - All rights reserved. </p>
        </div>
      </div>
    </div>
  </div>
  <table class="tabla">
    <tbody>
      <tr>
        <!-- JavaScript dependencies -->
        <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
        <!-- Script: Smooth scrolling between anchors in the same page -->
        <script src="js/smooth-scroll.js"> </script>
      </tr>
    </tbody>
  </table> Free&nbsp;&nbsp;<img src="https://pingendo.com/site-assets/Pingendo_logo_big.png" class="d-block" alt="Pingendo logo" height="16">
</body>

</html>
