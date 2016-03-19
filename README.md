# First-Html
My first html code
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style>
	*{
		margin:0;
		padding:0;
	}
	body{
		font-size:30px;
		color: white;
		text-align: center;
		background: #DEDEDE;
	}
	#wrap{
		width:70%;
		margin:0 auto;
	}
	#header{
		width:100%;
		background:#FF588E;
		height:60px;
	}
	#main{
		width:100%;
		background:#FBFBD8;
		overflow:hidden;
	}
	#mainText{
		color: black;
		clear:both;
	}
	#left{
		width:60%;
		background:#4E95FE;
		float:left;
		height:300px;
		margin-left: 2.5%;
	}
	#right{
		width:35%;
		height: 900px;
		background:#4E95FE;
		float:right;
		
	}
	#footer{
		width: 100%;
		background:#D98FFE;
		text-align: center;
	}

	</style>
</head>
<body>
	<div id="header">
		<p>This is head</p>
	</div>
	<div id="wrap">
		<div id="main">

			<div id="left">
				<p>left</p>
			</div>

			<div id="right">
				<p>right</p>
			</div>

			<p id="mainText">This is body</p>			
		</div>
		<div id="footer">
			<p>This is foot</p>
		</div>
	</div>
	
</body>
</html>
