# livros06
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Livros - Avaliação de livros</title>

	<link rel="stylesheet" href="reset.css">
	<link rel="stylesheet" href="livros.css">
	
</head>

<body>
	<header>
		<div class="caixa">
			<h1><img src="Avaliação.png"></h1>
			<nav>
				<ul>
					<li><a href="index.html">Destaque</a></li>
				</ul>
			</nav>
		</div>
	</header>

	<main>
		<ul class="produtos">
			<li>
				<h2>Cinderela está morta</h2>
				<img src="Cinderela.jfif">
				<p>Venha saber mais</p>
			</li>
			<li>
				<h2>O homem de giz</h2>
				<img src="giz.jfif">
				<p>Venha saber mais</p>
			</li>
			<li>
				<h2>Your name</h2>
				<img src="your.jfif">
				<p>Venha saber mais</p>
			</li>
			<li>
				<h2>Os dois morrem no final</h2>
				<img src="dois.jfif">
				<p>Venha saber mais</p>
			</li>
			<li>
				<h2>A CIDADE INFERNAL</h2>
				<img src="Elder.jpg">
				<p>Venha saber mais</p>
			</li>
			<li>
				<h2>Coraline</h2>
				<img src="Cora.jfif">
				<p>Venha saber mais</p>
			</li>
		</ul>
	</main>
</body>
</html>





header {
	background: #BBBBBB;
}

.caixa {
	width: 940px;
	position: relative;
	margin: 0 auto;
}

nav {
	position: absolute;
	top: 220px;
	right: 0;
}

nav li {
	display: inline;
	margin: 0 0 0 45px;
}

nav a {
	text-transform: uppercase;
	color: black;
	font-weight: bold;
	font-size: 30px;
	text-decoration: none;
}

.produtos {
	width: 940px;
	margin: 0 auto;
	padding: 100px;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	margin: 0 1.5%;
} 

.produtos h2 {
	font-size: 20px;
	font-weight: bold;
}

.produtos p {
	font-size: 15px;
	font-weight: bold;
}

@media screen and (max-width: 768px) {
	.caixa {
		width: 90%;
	}

	nav {
		position: static;
		margin-top: 20px;
	}

	.produtos {
		padding: 50px;
	}

	.produtos li {
		width: 48%;
		margin: 0 1%;
	}
}

@media screen and (max-width: 480px) {
	.caixa {
		width: 90%;
	}

	.produtos {
		padding: 30px;
	}

	.prod
