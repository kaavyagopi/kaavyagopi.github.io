<!DOCTYPE html>
<html>
<head>
	<title>mod2_solution</title>
	<meta charset="utf-8">
	<meta http-equiv="content-type" content="text/html">
	 <meta name="viewport" content="width=device-width, initial-scale=1.0">
	 <link rel="stylesheet" type="text/css" href="css/style.css">
</head>
<body>

	<h1>Our Menu</h1>
<div class="row">
	<div class="col-lg-1 col-md-1 col-sl-1">
		<div class="container">
		<p class="heading pink">Chicken</p>
		<p class="data">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat.</p>
		</div>
	</div>

	<div class="col-lg-2 col-md-2 col-sl-2">
	<div class="container">
		<p class="heading red">Beef</p>
		<p class="data">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat.</p>
	</div>
	</div>

	<div class="col-lg-3 col-md-3 col-sl-3">
	<div class="container">
		<p class="heading yellow">Sushi</p>
		<p class="data"> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat.</p>
	</div>
	</div>
</div>


</body>
</html>
		<style type="text/css">
			*{
	box-sizing: border-box;
	font-family: inherit;
}


body{
    padding: 0px;
    margin: 0px;
}

p{
    color: black;
}

h1{
	 margin-left: 10px;
    margin-right: 10px;
    width: 100%;
    text-align: center;
    font-size: xxx-large;
}

.heading{

	 font-size: larger;
    text-align: right;
    padding: 10px;
    position: absolute;
    top: 0px;
    right: 0px;
    margin: 0px;
    border: 1px;
    border-color: black;
    border-style: none none solid solid;
    width: max-content;

}

.pink{
	background-color: pink;
}
.red{
	background-color: red;
}
.yellow{
	background-color: yellow;
}

.data{
	text-align: justify;
	margin: 60px 15px 15px 15px;
    color: black;

}


.container{
    position: relative;
    border: 1px solid black;
    background-color: #c8bbbb;
    height: max-content;
}


.col-lg-1, .col-lg-2, .col-lg-3, .col-md-1, .col-md-2, .col-md-3, .col-sl-1, .col-sl-2, .col-sl-3{
    float: left;
    padding: 10px;
}
@media (min-width: 992px){

  .col-lg-1 {
    width: 33.3%;
  }
  .col-lg-2 {
    width: 33.3%;
  }
  .col-lg-3 {
    width: 33.3%;
  }
}
@media (min-width: 768px) and (max-width: 991px){

	 .col-md-1 {
    width: 50%;
  }
  .col-md-2 {
    width: 50%;
  }
  .col-md-3 {
    width:100%;
  }
}
@media (max-width: 767px){

	 .col-sl-1 {
    width: 100%;
    padding: 10px 50px;
  }
  .col-sl-2 {
    width: 100%;
    padding: 10px 50px;
  }
  .col-sl-3 {
    width:100%;
    padding: 10px 50px;
  }
}
		</style>


