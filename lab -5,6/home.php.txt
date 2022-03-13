<?php 
	session_start();
	if(isset($_COOKIE['status'])){
?>

<html>
<head>
	<title>Home Page</title>
</head>
<body>
    
	<div>
	<div align="right"> <a href="home.php" >Home |</a> 
	<a href="login.php">Login |</a>
	<a href="reg.php">Registration </a>
	</div>
	<h1>Welcome to xCompany!</h1>	
		
</body>
</html>

<?php

	}else{
		echo "invalid request";
	}
?>