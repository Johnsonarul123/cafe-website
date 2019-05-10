<!DOCTYPE html>
<html>
<head>
	<title>My cafe</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<link href="https://fonts.googleapis.com/css?family=Flamenco" rel="stylesheet">
	 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.min.css">
	 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
	<header>
		<nav>
			<div class="row">
				<img src="images/lg.jpg" class="logo">
				<ul class="main-nav animated slideInDown"  id="check-class">
					<li><a href="#">cake delivery</a></li>
					<li><a href="#">how to order</a></li>
					<li><a href="#">check more</a></li>
					<li><a href="#">sign up</a></li>
				</ul>
				<a href="#" class="mobile-icon" onclick="slideshow()"> <i class="fa fa-bars"></i> </a>
				
			</div>
		</nav>
		<div class="main content-header">
		<h1>Welcome to <span class="colorchange">My Cafe</span>.<br>
		HOUSE OF CAKE LOVER OO YES</h1>
		<a href="#" class="btn btn-full"> click to order</a>
		<a href="#" class="btn btn-nav"> show me more</a>
	</div>
	</header>

	<script type="text/javascript">
		function slideshow() {
			var x= document.getElementById('check-class');
			if (x.style.display === "none") {
				x.style.display="none";
			}
			// body...
		}
	</script>

</body>
</html>
