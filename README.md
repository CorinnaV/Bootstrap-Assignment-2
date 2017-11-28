# Bootstrap-Assignment-2
<!DOCTYPE html>
<!-- saved from url=(0316)https://d3c33hcgiwev3.cloudfront.net/_f0df73386be32bf8eec39224d56547b8_index.html?Expires=1495411200&Signature=XiTV95cbtkx97S-G-qr0NV2WfxY29AIOueI4vRhCmKTDDlnHAmLcnPfCDaGW6Kmv4eqKTdzUShL6DgMZgvzXkZ86XhjaHT6N3TKrEAFQGs7I4fWoXOhhlPz2DX915oxDjAGvtQQ85ta9W9BFPzeP4ZBLjmxxT3aQ1Z93513DEJU_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A -->
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head 
         content must come *after* these tags -->
    <title>Ristorante con Fusion</title>
            <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/bootstrap-theme.min.css" rel="stylesheet">
    <link href="css/mystyles.css" rel="stylesheet">
    <link href="css/font-awesome.min.css" rel="stylesheet">
    <link href="css/bootstrap-social.css" rel="stylesheet">

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
</head>
<body>
    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
         <div class="container">
           <div class="navbar-header">
                    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>               
                </div>
            </div>
      <div id="navbar" class="navbar-collapse collapse">  
          <ul class="nav navbar-nav">
            <li><a class="navbar-brand" href="file:///C:/A%20-%20MY%20FILES/A%20-%20CURRENT/Coursera%20-%20Full%20Stack%20Web%20Development/Bootstrap/conFusion/index.html"><img src="file:///C:/A%20-%20MY%20FILES/A%20-%20CURRENT/Coursera%20-%20Full%20Stack%20Web%20Development/Bootstrap/conFusion/img/img/logo.png" height=30 width=41></a></li>
            <li class="active"><a href="file:///C:/A%20-%20MY%20FILES/A%20-%20CURRENT/Coursera%20-%20Full%20Stack%20Web%20Development/Bootstrap/conFusion/index.html"><span class="glyphicon glyphicon-home"
                         aria-hidden="true"></span> Home</a></li>
            <li><a href="file:///C:/A%20-%20MY%20FILES/A%20-%20CURRENT/Coursera%20-%20Full%20Stack%20Web%20Development/Bootstrap/conFusion/aboutus.html"><span class="glyphicon glyphicon-info-sign"
                         aria-hidden="true"></span>About</a></li>
            <li class="dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown"
                         role="button" aria-haspopup="true" aria-expanded="false">
                         <span class="glyphicon glyphicon-list-alt"
                         aria-hidden="true"></span>
                         Menu <span class="caret"></span></a>
                        <ul class="dropdown-menu">
                            <li><a href="#">Appetizers</a></li>
                            <li><a href="#">Main Courses</a></li>
                            <li><a href="#">Desserts</a></li>
                            <li><a href="#">Drinks</a></li>
                            <li role="separator" class="divider"></li>
                            <li class="dropdown-header">Specials</li>
                            <li><a href="#">Lunch Buffet</a></li>
                            <li><a href="#">Weekend Brunch</a></li>
                        </ul>
                     </li>
            <li><a href="file:///C:/A%20-%20MY%20FILES/A%20-%20CURRENT/Coursera%20-%20Full%20Stack%20Web%20Development/Bootstrap/conFusion/contactus.html">
            <i class="fa fa-envelope-o"></i>
        Contact</a></li>
         </ul>
<!--TASK 1 - NEW INLINE NAVBAR FORM IS HERE - IS COPIED TO OTHER PAGES-->
<div class="container">
    <ul class="nav navbar-nav navbar-right">
         <form class="form-inline" style="margin-top: 10px; margin-bottom: 10px">
            <div class="form-group">
                <label class="sr-only" for="email">Email</label>
                <input type="email" class="form-control" id="email" placeholder="Email">
            </div>
            <div class="form-group">
                <label class="sr-only" for="password">Password</label>
                <input type="password" class="form-control" id="password" placeholder="Password">
            </div>
            <div class="checkbox">
                <label><input type="checkbox">Remember me</label>
            </div>
            <div class="form-group">
                <button type="submit" class="btn btn-info">Sign in</button>
            </div>
        </form>
    </ul>
</div>
      </div>
    </nav>

    <header class="jumbotron">

        <!-- Call to action -->

        <div class="container">
            <div class="row row-header">
                <div class="col-xs-12 col-sm-8">
                    <h1>Ristorante con Fusion</h1>
                    <p style="padding:40px;"></p>
                    <p>We take inspiration from the World's best cuisines, and create a unique fusion experience. Our lipsmacking creations will tickle your culinary senses!</p>
                </div>
                <div class="col-xs-12 col-sm-2">
                    <p style="padding:20px;"></p>
                    <img src="file:///C:/A%20-%20MY%20FILES/A%20-%20CURRENT/Coursera%20-%20Full%20Stack%20Web%20Development/Bootstrap/conFusion/img/img/logo.png" class="img-responsive">
                </div>
<!--TASK 2 - NEW RESERVE TABLE BUTTON IS HERE -->
                <div class="col-xs-12 col-sm-2">
                    <p style="padding:20px;"></p>
                    <button type="button" class="btn btn-warning btn-lg" style="margin-top: 40px"><a href="#reserveform">Reserve Table</a></button>
                </div> 
            </div>
        </div>
    </header>

<div class="container">
    <div class="row">
      <div class="col-xs-12">
        <ol class="breadcrumb">
          <li><a href="index.html">Home</a></li>
          <li class="active">Home</li>
        </ol>
      </div>
    </div>
</div>

<div class="container">
    <div class="row row-content">
        <div class="col-xs-12 col-sm-3 col-sm-push-9">
                <p style="padding:20px;"></p>
                <h3 align="center">Our Lipsmacking Culinary Creations</h3>
        </div>
        <div class="col-xs-12 col-sm-9 col-sm-pull-3">
            <div class="media">
                <div class="media-left media-middle">
                        <a href="#"><img class="media-object img-thumbnail" src="file:///C:/A%20-%20MY%20FILES/A%20-%20CURRENT/Coursera%20-%20Full%20Stack%20Web%20Development/Bootstrap/conFusion/img/img/uthappizza.png" alt="Uthapizza"></a>
                </div>
                <div class="media-body">
                    <h2 class="media-heading">Uthapizza <span class="label label-danger label-xs">Hot</span> <span class="badge">$4.99</span></h2>
                    <p>A unique combination of Indian Uthappam (pancake) and Italian pizza, topped with Cerignola olives, ripe vine cherry tomatoes, Vidalia onion, Guntur chillies and Buffalo Paneer.</p>
                    <p><a class="btn btn-primary btn-xs" href="#">More &raquo;</a></p>
                </div>
            </div>
        </div>
</div>

<!--TASK 4 - HERE IS NEW ARRANGEMENT OF 2ND ROW WITH ADDED MEDIA AND LABEL-->
<div class="container">
    <div class="row row-content">
        <div class="col-xs-12 col-sm-3">
                <p style="padding:20px;"></p>
                <h3 align="center">This Month's Promotions</h3>
        </div>
        <div class="col-xs-12 col-sm-6">
            <div class="media-body">
                <h2 class="media-heading">Weekend Grand Buffet <span class="label label-danger label-xs">New</span></h2>
                <p>Featuring mouthwatering combinations with a choice of five different salads, six enticing appetizers, six main entrees and five desserts. Free flowing bubbly and soft drinks. All for just $19.99 per person!</p>
                <p><a class="btn btn-primary btn-xs" href="#">More &raquo;</a></p>
            </div>
        </div> 

        <div class="col-xs-12 col-sm-3">
            <div class="media">
                <div class="media-right media-middle">
                        <a href="#"><img class="media-object img-thumbnail" src="file:///C:/A%20-%20MY%20FILES/A%20-%20CURRENT/Coursera%20-%20Full%20Stack%20Web%20Development/Bootstrap/conFusion/img/img/buffet.png" alt="Promotions"></a>
                </div>
            </div> 
        </div>  
    </div>
</div>

<div class="container">
        <div class="row row-content">
            <div class="col-xs-12 col-sm-3 col-sm-push-9">
                <p style="padding:20px;"></p>
                <h3 align="center">Meet our Culinary Specialists</h3>
            </div>
            <div class="col-xs-12 col-sm-9 col-sm-pull-3">
                <div class="media">
                <div class="media-left media-middle">
                    <a href="#"><img class="media-object img-thumbnail" src="file:///C:/A%20-%20MY%20FILES/A%20-%20CURRENT/Coursera%20-%20Full%20Stack%20Web%20Development/Bootstrap/conFusion/img/img/alberto.png" alt="Alberto Somayya"></a>
            </div>
            <div class="media-body">
                <h2 class="media-heading">Alberto Somayya</h2>
                <h4>Executive Chef</h4>
                <p>Award winning three-star Michelin chef with wide International experience having worked closely with who's-who in the culinary world, he specialises in creating mouthwatering Indo-Italian fusion experiences.</p>
                <p><a class="btn btn-primary btn-xs" href="#">More &raquo;</a></p>
            </div>
        </div>
    </div>
</div>

<!--TASK 3 - RESERVE TABLE FORM -->
<div class="container" id="reserveform">
    <div class="row row-content">

        <div class="col-xs-12 col-sm-3">
            <p style="padding:20px;"></p>
            <h3 align="center">Reserve a Table</h3>
        </div>

        <div class="col-xs-12 col-sm-9">

            <form class="form-horizontal">
                <div class="form-group">
                    <label class="control-label col-sm-2" for="email">Number of Guests</label>
                        <div class="col-sm-10">
                            <label class="radio-inline"><input type="radio" name="optradio">1</label>
                            <label class="radio-inline"><input type="radio" name="optradio">2</label>
                            <label class="radio-inline"><input type="radio" name="optradio">3</label>
                            <label class="radio-inline"><input type="radio" name="optradio">4</label>
                            <label class="radio-inline"><input type="radio" name="optradio">5</label>
                            <label class="radio-inline"><input type="radio" name="optradio">6</label>
                        </div>
                </div>
                
                <div class="form-group has-feedback">
                    <label class="control-label col-sm-2">Date and Time</label>
                        
                        <div class="col-sm-4" for="date">
                            <input class="form-control" type="text" placeholder="Date">
                            <i class="glyphicon glyphicon-calendar form-control-feedback"></i>
                        </div>
                                                    
                        <div class="col-sm-4" for="time">
                            <input class="form-control" type="text" placeholder="Time">
                            <i class="glyphicon glyphicon-time form-control-feedback"></i>
                        </div>
                </div>
              
                <div class="form-group"> 
                    <div class="col-sm-offset-2 col-sm-10">
                      <button type="submit" class="btn btn-primary">Reserve</button>
                    </div>
                </div>

                <div class="form-group">
                    <div class="col-sm-10">
                        <div class="alert alert-warning alert-dismissible" role="alert">       
                            <button type="button" class="close" data-dismiss="alert" aria-label="Close">         
                            <span aria-hidden="true">&times;</span>        
                            </button>        
                            <strong>Warning:</strong> Please <a href="tel:+85212345678" class="alert-link">call</a> us to reserve for more than six guests.
                        </div>
                    </div>
                </div>

            </form>
        </div>  
    </div> 
</div>

    <footer>
        <div class="container">
            <div class="row row-footer">             
                <div class="col-xs-5 col-xs-offset-1 col-sm-2 col-sm-offset-1">
                    <h5>Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://d3c33hcgiwev3.cloudfront.net/_f0df73386be32bf8eec39224d56547b8_index.html?Expires=1495411200&amp;Signature=XiTV95cbtkx97S-G-qr0NV2WfxY29AIOueI4vRhCmKTDDlnHAmLcnPfCDaGW6Kmv4eqKTdzUShL6DgMZgvzXkZ86XhjaHT6N3TKrEAFQGs7I4fWoXOhhlPz2DX915oxDjAGvtQQ85ta9W9BFPzeP4ZBLjmxxT3aQ1Z93513DEJU_&amp;Key-Pair-Id=APKAJLTNE6QMUY6HBC5A#">Home</a></li>
                        <li><a href="https://d3c33hcgiwev3.cloudfront.net/_f0df73386be32bf8eec39224d56547b8_index.html?Expires=1495411200&amp;Signature=XiTV95cbtkx97S-G-qr0NV2WfxY29AIOueI4vRhCmKTDDlnHAmLcnPfCDaGW6Kmv4eqKTdzUShL6DgMZgvzXkZ86XhjaHT6N3TKrEAFQGs7I4fWoXOhhlPz2DX915oxDjAGvtQQ85ta9W9BFPzeP4ZBLjmxxT3aQ1Z93513DEJU_&amp;Key-Pair-Id=APKAJLTNE6QMUY6HBC5A#">About</a></li>
                        <li><a href="https://d3c33hcgiwev3.cloudfront.net/_f0df73386be32bf8eec39224d56547b8_index.html?Expires=1495411200&amp;Signature=XiTV95cbtkx97S-G-qr0NV2WfxY29AIOueI4vRhCmKTDDlnHAmLcnPfCDaGW6Kmv4eqKTdzUShL6DgMZgvzXkZ86XhjaHT6N3TKrEAFQGs7I4fWoXOhhlPz2DX915oxDjAGvtQQ85ta9W9BFPzeP4ZBLjmxxT3aQ1Z93513DEJU_&amp;Key-Pair-Id=APKAJLTNE6QMUY6HBC5A#">Menu</a></li>
                        <li><a href="https://d3c33hcgiwev3.cloudfront.net/_f0df73386be32bf8eec39224d56547b8_index.html?Expires=1495411200&amp;Signature=XiTV95cbtkx97S-G-qr0NV2WfxY29AIOueI4vRhCmKTDDlnHAmLcnPfCDaGW6Kmv4eqKTdzUShL6DgMZgvzXkZ86XhjaHT6N3TKrEAFQGs7I4fWoXOhhlPz2DX915oxDjAGvtQQ85ta9W9BFPzeP4ZBLjmxxT3aQ1Z93513DEJU_&amp;Key-Pair-Id=APKAJLTNE6QMUY6HBC5A#">Contact</a></li>
                    </ul>
                </div>
                <div class="col-xs-6 col-sm-5">
                    <h5>Our Address</h5>
                    <address>
		              121, Clear Water Bay Road<br>
		              Clear Water Bay, Kowloon<br>
		              HONG KONG<br>
		            <i class="fa fa-phone"></i>: +852 1234 5678<br>
                    <i class="fa fa-fax"></i>: +852 8765 4321<br>
                    <i class="fa fa-envelope"></i>: 
                                 <a href="mailto:confusion@food.net">confusion@food.net</a>
		           </address>
                </div>
                <div class="nav navbar-nav" style="padding: 40px 10px;">
                        <a class="btn btn-social-icon btn-google-plus" href="http://google.com/+"><i class="fa fa-google-plus"></i></a>
                        <a class="btn btn-social-icon btn-facebook" href="http://www.facebook.com/profile.php?id="><i class="fa fa-facebook"></i></a>
                        <a class="btn btn-social-icon btn-linkedin" href="http://www.linkedin.com/in/"><i class="fa fa-linkedin"></i></a>
                        <a class="btn btn-social-icon btn-twitter" href="http://twitter.com/"><i class="fa fa-twitter"></i></a>
                        <a class="btn btn-social-icon btn-youtube" href="http://youtube.com/"><i class="fa fa-youtube"></i></a>
                        <a class="btn btn-social-icon" href="mailto:"><i class="fa fa-envelope-o"></i></a>
                    </div>

                <div class="col-xs-12 col-sm-12">
                    <p style="padding:10px;"></p>
                    <p align="center">© Copyright 2015 Ristorante Con Fusion</p>
                </div>
            </div>
        </div>
    </footer>
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>

</body></html>
