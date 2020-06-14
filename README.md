<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>统一个命名格式吧</title>
<style>
	body,ul,div{
		padding: 0;
		margin: 0;
	}
	body{
		background-image: url("images/bgimg.jpg");
		background-repeat:round;
	}
	#nav{
	margin:0 auto;
	height:36px;
	background-color:hsla(37,91%,58%,1.00);
	border: thin;
}
	#nav ul{
		width:1000px;
		height:36px;
		margin: auto;
	}

	#nav a:link,#nav a:visited{
	line-height:36px;
	text-align:center;
	color:currentColor;
	background-color:hsla(37,91%,58%,1.00);
	text-decoration:none;
	border-right:1px solid #FFF;
		
}
	.bdrl {
		border-left:1px solid #FFF;
	}
	#nav a:hover{
		color:cornflowerblue;
		background-color:bisque;
		font-weight: 600;
	}
	#nav a:visited{
		color: darkolivegreen;
	}
	#nav a{
	display:block;
	box-sizing:border-box;
	
}
	#nav ul li{
	width:200px;
	/*height:36px;*/
	position:relative;
	border-bottom:1px dashed hsla(0,0%,62%,1.00);
	list-style-type:none;
}
	
	
	#nav ul li ul{
	position: absolute;
    display:none;
	
}
	#nav ul li:hover ul{
	display:block;
		
}

	#container{
		width:1200px;
		margin: 0 auto;
		background-color:blanchedalmond;
	}
	.abc{
		float:left;
	}
	#header,#footer{
		width: 1440px;
		margin: 0 auto;
		
	}
	#footer p{
		color: aliceblue;
		text-align: center;
	}
	#header{
		background-image:url("images/ord.JPG");
		background-repeat:repeat-x;
	    height:170px;
	}
	#header h1{
		font-family: neuton;
		font-size: 60px;
	}
</style>

</head>

<body>
<div id="header"><br />
	<h1 align="center">日本🇯🇵美食</h1>
	</div>
<div id="nav">
	<ul>
		
		<li class="abc"><a href="#" class="bdrl"><strong>首页</strong></a></li>
		
		<li class="abc"><a href="#"><strong>本州地区</strong></a>
		 <ul>
          <li><a href="#">东京</a></li>
          <li><a href="#">京都</a></li>
          <li><a href="#">大阪</a></li>
         </ul>
		</li>
		<li class="abc"><a href="#"><strong>九州地区</strong></a>
		<ul>
          <li><a href="#">长崎</a></li>
          <li><a href="#">福冈</a></li>
         </ul>	
		 
		</li>
		<li class="abc"><a href="#"><strong>北海道岛</strong></a></li>
		<li class="abc"><a href="#"><strong>冲绳岛</strong></a></li>
		</ul>
</div>
	
<div id="container">
	<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
	</div>
<div id="footer">
  <p>&copy;咱们的组名哈哈哈哈哈！</p></div>
</body>
</html>
