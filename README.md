
<html lang="en">
<head>
  <title>Arcadia </title>
  <script src="https://code.jquery.com/jquery-3.7.0.min.js" 
  integrity="sha256-2Pmvv0kuTBOenSvLm6bvfBSSHrUJ+3A7x6P5Ebd07/g=" crossorigin="anonymous"></script>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <script src="js/script.js"></script>
  <script src="js/jquery-3.7.0"></script>
  <script src="jquery-ui-1.13.2"></script>
  <script src="/Acadia/css/stylesheet.css">
  </script>
  <script src="/Users/haydancrawford/Documents/Documents - Haydan’s iMac/Acadia/root/css/stylesheet.css"></script>
  <style>
    body {font-family: 'Cambria', sans-serif;
        background-repeat: no-repeat;
        background-position: center;
        background-size: 600px;
        font-family:"Cambria";
        background-position: top center;
        background-repeat:no-repeat;
        background-attachment: fixed;
        background-color: #E5E7E6;
      }
    .jumbotron {background-image:url(images/grouphike.jpg);
      background-repeat: no-repeat;
      background-position: center;
      background-size:cover;
      font-family:"Cambria";
    }
    .container {font-family:"Cambria";
    }
    .navbar {font-family:"Cambria";
      background-color:white;
  
  }
    .navbar-toggle {background-color:#E9692C;}
    .active {background-color: #E9692C;}
  </style>
   <title>jQuery UI Button - Default functionality</title>
   <link rel="stylesheet" href="//code.jquery.com/ui/1.13.2/themes/base/jquery-ui.css">
   <link rel="stylesheet" href="/resources/demos/style.css">
   <script src="https://code.jquery.com/jquery-3.6.0.js"></script>
   <script src="https://code.jquery.com/ui/1.13.2/jquery-ui.js"></script>
   <script>
   $( function() {
     $( ".widget input[type=submit], .widget a, .widget button" ).button();
     $( "button, input, a" ).on( "click", function( event ) {
       event.preventDefault();
     } );
   } );
   </script>
</head>
<body>
  <nav class="navbar navbar-inverse">
    <div class="container-fluid">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span> 
        </button>
        <a class="navbar-brand" href="/README.md"><img src="acadialogo-main copy.jpg" width="50"> </img></a>
      </div>
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav">
          <li class="active"><a href="/README.md">Home</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="shop.html">Shop</a></li> 
        </ul>
        <ul class="nav navbar-nav navbar-right">
          <li><a href="contact.html"> Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>
<div class="jumbotron text-center">
  <h1 class="h1"><font color="#E5E7E6" size="50px">Arcadia Park Equipment Co.</font></h1>
  <p><font color="#FFF000"><i>your adventure, your world.</i></font></p> 
  <div class="widget">
    <button  type="button" style="background-color:#E9692C" href="contact.html">Adventure Awaits</button> 
  </div>
</div>
  
<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <img class="img-responsive" src="backpack.jpg" width="200">
      <h3 style="text-align: center; color:#E9692C;"><a  href="/root/shop.html">hiking gear</a></h3>
      <p>A hiking we will go with the latest packs, coolers, boots, and so much more.</p>
      <p>All the brands you love at a realistic and reasonable price.</p>
    </div>
    <div class="col-sm-4">
      <img  class="img-responsive" src="kayaks.jpg" width="225">
      <h3 style="text-align: center; color:#E9692C;" href="shop.html">water must haves</h3>
      <p>A kayaking we will go with the most resistant and durable of water accessories.</p>
      <p>The choices are endless from floating down the river to high intensitiy tubing.</p>
    </div>
    <div class="col-sm-4">
    <img class="img-responsive" src="tent.jpg" width="225" >
      <h3 style="text-align: center; color:#E9692C;" href="/root/shop.html">camping essentials</h3>        
      <p>A camping we will go with all our tents and supplies.</p>
      <p>Whether you like glamping for roughing it like the old days, we have you covered with tents and accessories. </p>
    </div>
  </div>
</div>

</body>

</html>











































































































































