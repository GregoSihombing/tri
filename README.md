<!doctype html>
<html>
<head>
  <meta charset="utf-8">
	<title>MYTOSIN</title>
    <style>
		*{
			font-family: Arial, Helvetica, sans-serif;
			background-color: #f1efec;
		}
		#container{
			width: 1034px;
			height: 680px;
			margin: auto;
			margin-top: -8px;
		}
		#header{
			width: 1020px;
			height: 101px;
			background-color: #f1d5ad;
			text-align: right;
			margin-left: 7px;
		}
		#box_one{
			width: 167px;
			height: 43px;
			background-color: #000000;
			margin-left: 5px;
			margin-top: 5px;
			float: left;
		}
		#box_two{
			width: 105px;
			height: 32px;
			background-color: #000000;
			float: right;
			margin-right: 5px;
			margin-top: 5px;
		}
		#author{
			color: #ffffff;
			text-decoration: none;
			font-size: 18px;
			margin-right: 9px;
			background-color: #f1d5ad;
		}
		#in{
			color: #ffffff;
			text-decoration: none;
			font-size: 18px;
			margin-right: 27px;
			background-color: #f1d5ad;
		}
		#menu{
			width: 1034px;
			height: 42px;
			margin-top: -48px;
			background-color: #f1b157;
			border-top: solid 1px;
			border-top-color: #b58541;
			border-bottom: solid 1px;
			border-bottom-color: #f8ead6;
		}
		nav ul{
			list-style: none;
			margin-left: -28px;
			margin-top: -12px;
		}
		nav ul li{
			float: left;
			background-color: #f1b157;
		}
		nav ul li a{
			color: #ffffff;
			text-decoration: none;
			font-size: 18px;
			margin-right: 15px;
			background-color: #f1b157;
		}
		#read{
			width: 582px;
			height: 500px;
			background-color: #ffffff;
			float: left;
			margin-left: 7px;
			margin-top: 22px;
			border: solid 1px;
			border-color: #d2d2d2;
		}
		#up{
			width: 416px;
			height: 420px;
			background-color: #ffffff;
			float: left;
			margin-left: 18px;
			margin-top: 22px;
			border: solid 1px;
			border-color: #d2d2d2;
			z-index: -1;
		}
		img{
			background-color: #ffffff;
		}
		#footer{
			width: 1020px;
			border-top: solid 1px;
			border-top-color: #777777;
			float: right;
			margin-top: 20px;
			margin-right: 7px;
			text-align: right;
		}
		a{
			margin-right: 10px;
			text-decoration: none;
			color: #c97d0b;
		}
		#text{
			margin-top: 5px;
			color: #494949;
		}
		label{
			display: block;
			background-color: #ffffff;
			margin-bottom: 8px;
		}
		span{
			display: block;
			float: left;
			width: 105px;
			text-align: left;
			font-size: 16px;
			color: #494949;
			background-color: #ffffff;
			font-weight: 600;
		}
		.input_text{
			margin-left: 5px;
			width: 240px;
			height: 25px;
			border: solid 1px;
			border-color: #d2d2d2;
			background-color: #ffffff;
		}
		select{
			margin-left: 5px;
			border: solid 1px;
			border-color: #d2d2d2;
			background-color: #ffffff;
			padding: 2px;
		}
		#form{
			width: 365px;
			height: 360px;
			background-color: #ffffff;
			margin-left: 33px;
			margin-top: -25px;
			z-index: 2;
			position: fixed;
		}
		#agree{
			width: 240px;
			height: 100px;
			float: right;
			font-size: 16px;
			margin-right: 15px;
			margin-top: -2px;
			background-color: #ffffff;
			color: #494949;
		}
		#policy{
			margin-right: -2px;
		}
		#submit{
			margin-top: 10px;
			width: 75px;
			height: 27px;
			color: #efb156;
			background-color: #424140;
			border-color: #efb156;
			border-bottom-color: #77582b;
			border-right-color: #77582b;
			font-weight: bold;
			padding-bottom: 10px;
		}
		#search{
			background-color: #f1b157;
			float: right;
			margin-right: 8px;
			margin-top: 4px;
		}
		#cari{
			width: 220px;
			height: 23px;
			border: solid 1px;
			border-color: #d2d2d2;
			background-color: #ffffff;
		}
		#button{
			margin-left: 4px;
			width: 63px;
			height: 24px;
			border: solid 1px;
			border-color: #efb156;
			border-bottom-color: #77582b;
			border-right-color: #77582b;
			color: #efb156;
			background-color: #424140;
			font-weight: bold;
			padding-bottom: 10px;
			float: right;
			margin-top: 1px;
		}
	</style>
</head>
<body>
	<div id="container">
	<div id="header">
    	<div id="box_one"></div>
        <a href="" id="author">Become Author</a>
        <a href="" id="in">Sign In</a>
    </div>
    <div id="menu">
    	<nav>
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Tutorial</a></li>
                <li><a href="">Articles</a></li>
            </ul>
        </nav>
        <div id="search">
        	<input type="text" id="cari"/><input type="button" value="Search" id="button"/>
        </div>
    </div>
    <div id="read">
    	<img src="readThis-ribbon.png"/>
    </div>
    <div id="up">
    	<img src="signUp-ribbon.png"/>
        <div id="box_two"></div>
        <form>
        <div id="form">
            <label>
            	<span>Email</span>
                <input type="text" class="input_text"/>
            </label>
            <label>
            	<span>Password</span>
                <input type="text" class="input_text"/>
            </label>
            <label>
            	<span>re-Password</span>
                <input type="text" class="input_text"/>
            </label>
            <label>
            	<span>Author Name</span>
                <input type="text" class="input_text"/>
            </label>
            <label>
            	<span>Sex</span>
                <select>
                	<option>--Choose--</option>
                    <option>Female</option>
                    <option>Male</option>
                </select>
            </label>
            <label>
            	<span>Telephone</span>
                <input type="text" class="input_text"/>
            </label>
            <label>
            	<span>Expert On</span>
                <input type="text" class="input_text"/>
            </label>
            <div id="agree">
            	By clicking sign up, it means that you have agreed to our <a href="" id="policy">policy</a> and <a href="">terms</a><br/>
                <input type="submit" value="Sign Up" id="submit"/>
            </div>
        </div>
        </form>
    </div>
    <div id="footer"><div id="text">Copyright &copy; 2012 &nbsp;<a href="">Webmaster</a><a href="">About</a><a href="">Suggest Us</a></div></div>
    </div>
</body>
</html>