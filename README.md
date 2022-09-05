# Online-Shopping-site-Front-end-
This site will help you to buy any cloths, shoes, etc. This is responsive dynamic website using (HTML, CSS, Bootstrap).


<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>Clothing Site</title>

    <!-- Bootstrap -->
    <link rel="stylesheet" href="bootstrap/css/bootstrap.min.css">
	<link rel="stylesheet" href="new.css">

    
  </head>
  <body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">
     <nav class="navbar navbar-default navbar-fixed-top">
	 <div class="container">
	 <div class="navbar-header">
	 <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#navCollapse">
	 <span class="icon-bar"></span>
	 <span class="icon-bar"></span>
	 <span class="icon-bar"></span>
	 </button>
	  <a class="navbar-brand" href="Front.html"> HoneyBee.com </a>
	 </div>
	 <div class="collapse navbar-collapse" id="navCollapse">
	  <ul class="nav navbar-nav">
	   <li><a href="#"><span class="glyphicon glyphicon-home"></span> </a></li>
	   </ul>
	   <ul class="nav navbar-nav navbar-right">
	   <li class="dropdown"><a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false"> Menu <span class="caret"></span></a>
	   <ul class="dropdown-menu">
	   <li><a href="#todaydeal">Today Faishion Deals</a></li>
	   <li><a href="#latesttrends">Latest Trends</a></li>
	   <li><a href="#sale"> Sale</a></li>
	   </li>
	   </ul>
	   <li><a href="#"><span class="glyphicon glyphicon-envelope"></span> Contact us</a></li>
	   <li><a href="login.html"><span class="glyphicon glyphicon-log-in login"></span> Login </a></li>
	   </ul>
	 </div>
	 </div>
	</nav>
	
	
	<div class="jumbotron">
	  <h1> HoneyBee.com! </h1>
	  <p> Here You shop products easily. </p>
	  <form>
	   <div class="input-group">
	    <input type="search" class="form-control" size="50" placeholder="Search Products" required>
		<div class="input-group-btn">
		<button type="button" class="btn btn-danger">Search</button>
		</div>
		</div>
		</form>
	</div>
	
	<div class="container-fluid">
	<div id="myCarousel" class="carousel slide" data-ride="carousel">
	<ol class="carousel-indicators">
	  <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
	  <li data-target="#myCarousel" data-slide-to="1" class="active"></li>
	  <li data-target="#myCarousel" data-slide-to="2"></li>
	</ol>
	<div class="carousel-inner">
	 <div class="item active">
	   <img src="f1.jpg" alt="Picture">
	   <div class="carousel-caption">
	   <h3> Book Now! </h3>
	   <p> Amazing Hotels Are Available Here. </p>
	 </div>
	 </div>
	 <div class="item">
	   <img src="f2.jpg" alt="Picture">
	   <div class="carousel-caption">
	   <h3> Amazing Restaurants! </h3>
	   <p> Good Food at Good Prizes.  </p>
	 </div>
	 </div>
	 <div class="item">
	   <img src="s3.jpg" alt="Picture">
	   <div class="carousel-caption">
	   <h3> Amazing Places to visit!  </h3>
	   <p> Packages start from 2500 INR. </p>
	 </div>
	 </div>
	</div>
	<a class="left carousel-control" href="#myCarousel" data-slide="prev">
	<span class="glyphicon glyphicon-chevron-left"></span>
	<span class="sr-only">Previous</span>
	</a>
	<a class="right carousel-control" href="#myCarousel" data-slide="next">
	<span class="glyphicon glyphicon-chevron-right"></span>
	<span class="sr-only">Next</span>
	</a>
	</div>
	</div>
	
	<div id="todaydeal">
	<div class="panel panel-default">
	  <div class="panel-heading panel-heading-custom">
	   <H2 CLASS="PANEL-TITLE"> LATEST FASHION DEALS  </H2>
	   </DIV>
	   <div class="panel-body">
	   <div class="row">
	    <div class="col-sm-3 col-md-4">
		<div class="thumbnail">
		<a href="s1.jpg">
		<img src="s1.jpg" alt="shoes">
		<div class="caption">
		<p1> From  INR 1999 </p1>
		 <a href=""><h3> Sneaker </h3></a>
		 <button type="button" class="btn btn-success"> Buy </button>
		</div>
		</div>
		</div>
		
		<div class="col-sm-3 col-md-4">
		<div class="thumbnail">
		<a href="tshirt.jpg">
		<img src="tshirt.jpg" alt="shoes">
		<div class="caption">
		<p1> From  INR 599</p1>
		 <a href=""><h3> T-Shirt </h3></a>
		 <button type="button" class="btn btn-success"> Buy </button>
		</div>
		</div>
		</div>
		
		<div class="col-sm-3 col-md-4">
		<div class="thumbnail">
		<a href="jeans.jpg">
		<img src="jeans.jpg" alt="shoes">
		<div class="caption">
		<p1> From  INR 899 </p1>
		 <a href=""><h3> Jeans </h3></a>
		 <button type="button" class="btn btn-success"> Buy </button>
		</div>
		</div>
		</div>
		</div>
		</div>
		</div>
		</div>
		
		
		
		<div id="latesttrends">
		<div class="panel panel-default">
	  <div class="panel-heading panel-heading-custom">
	   <H2 CLASS="PANEL-TITLE"> Latest trends  </H2>
	   </DIV>
	   <div class="panel-body">
	   <div class="row">
	    <div class="col-sm-3 col-md-4">
		<div class="thumbnail">
		<a href="djeans.jpg">
		<img src="djeans.jpg" alt="shoes">
		<div class="caption">
		<p1> From  INR 999 </p1>
		 <a href=""><h3> Denim jeans </h3></a>
		 <button type="button" class="btn btn-success"> Buy </button>
		</div>
		</div>
		</div>
		
		<div class="col-sm-3 col-md-4">
		<div class="thumbnail">
		<a href="suit.jpg">
		<img src="suit.jpg" alt="shoes">
		<div class="caption">
		<p1> From  INR 5999 </p1>
		 <a href=""><h3> Suit for men </h3></a>
		 <button type="button" class="btn btn-success"> Buy </button>
		</div>
		</div>
		</div>
		
		<div class="col-sm-3 col-md-4">
		<div class="thumbnail">
		<a href="cap.jpg">
		<img src="cap.jpg" alt="shoes">
		<div class="caption">
		<p1> From  INR 499 </p1>
		 <a href=""><h3> Caps </h3></a>
		 <button type="button" class="btn btn-success"> Buy </button>
		</div>
		</div>
		</div>
		
	    </div>
        </div>	   
	   </div>
	   </div>
	   
	   
	   
	   
	   
	   
	   
	   <div class="jumbotron1">
		 <h1> 50% SALE ON Sneakers. </h1>
		 <p> Hurry UP!! </p>
		 <p> <a class="btn btn-btn-primary btn-lg" href="#" role="button">Learn More </a></p>
		 </div>
		 </div>
		 </div><br><br><br>
		 
		 
		 
		 <div id="sale">
		<div class="panel panel-default">
	  <div class="panel-heading panel-heading-custom">
	   <H2 CLASS="PANEL-TITLE"> Sale is Here!  </H2>
	   </DIV>
	   <div class="panel-body">
	   <div class="row">
	    <div class="col-sm-3 col-md-3">
		<div class="thumbnail">
		<a href="s1.jpg">
		<img src="s1.jpg" alt="shoes">
		<div class="caption">
		<p1> 20% OFF</p1>
		 <a href=""><h3> Nike </h3></a>
		</div>
		</div>
		</div>
		
		<div class="col-sm-3 col-md-3">
		<div class="thumbnail">
		<a href="s2.jpg">
		<img src="s2.jpg" alt="shoes">
		<div class="caption">
		<p1> 40% OFF </p1>
		 <a href=""><h3> Nike Air </h3></a>
		</div>
		</div>
		</div>
		
		<div class="col-sm-3 col-md-3">
		<div class="thumbnail">
		<a href="s3.jpg">
		<img src="s3.jpg" alt="shoes">
		<div class="caption">
		<p1> 50% OFF </p1>
		 <a href=""><h3> Flyknit </h3></a>
		</div>
		</div>
		</div>
		
		
		<div class="col-sm-3 col-md-3">
		<div class="thumbnail">
		<a href="s5.jpg">
		<img src="s5.jpg" alt="shoes">
		<div class="caption">
		<p1> 40% OFF </p1>
		 <a href=""><h3> woodland </h3></a>
		</div>
		</div>
		</div>
		
	    </div>
        </div>	   
	   </div>
	   </div>
	   
	   
	   
	   
	   
	   
	   <!-- ************** Footer ***************** -->
	   <footer>
		   <div class="footer-top">
		     <div class="container">
			  <div class="row">
			    <div class="col-md-3 col-sm-6 col-xs-12 segment-one">
				  <h4> HoneyBee.com </h4>
				  <p1> Hello Everyone Welcome to this site hope u liked this site</p>
				</div>
				<div class="col-md-3 col-sm-6 col-xs-12 segment-two">
				 <h4> HELP </h4>
				 <ul>
				    <li><a href="">Payments</a></li>
					<li><a href="">shipping</a></li>
					<li><a href="">FAQ</a></li>
					<li><a href="">Report</a></li>
				 </ul>
				</div>
				<div class="col-md-3 col-sm-6 col-xs-12 segment-three">
				<h4> SOCIAL </h4>
				 <ul>
				    <li><a href="">Facebook</a></li>
					<li><a href="">Twitter</a></li>
					<li><a href="">Youtube</a></li>
					<li><a href="">Instagram</a></li>
				 </ul>
				</div>
				<div class="col-md-3 col-sm-6 col-xs-12 segment-three">
				<h4> ABOUT </h4>
				 <ul>
				    <li><a href="">Contact Us</a></li>
					<li><a href="">About Us</a></li>
					<li><a href="">Careers</a></li>
					<li><a href="">Press</a></li>
				 </ul>
				</div>
				</div>
			</div>
		  </div>
		</footer>
  
  
  
  
  
   <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="bootstrap/js/bootstrap.min.js"></script>
  </body>
</html>
