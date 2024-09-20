### Marcação da atividade 01 - PlayList de vídeos de revisão com div's e pseudoclasses.
Repositório para estudo da disciplina de fundamentos

>  Marcação html

```html
<!DOCTYPE html>
<html>
<head>
	<title>Exemplo de aula</title>
	<style>
		#geral{
			width:980px;
			height: 1080px;			
			margin: auto;			
		}
		#menuTop{
			widthf: auto;
			height: 120px;			
		}
		#menuLinks{
			width:430px;
			height: 40px;			
			float: right;
			margin-top: 10px;
			margin-right: 4px;
		}
		#divBanner{
			width: auto;
			height: 480px;
			background-color: #fabaca;
		}
		#bannerLeft{
			width: 465px;
			height: 450px;
			background-color: #cafaba;
			float:left;
			margin-top:16px;
			margin-left:10px;
		}
		#bannerRight{
			width: 465px;
			height: 450px;
			background-color: #cafaba;
			float:right;
			margin-top:16px;
			margin-right:10px;
		}
		#divImg{
			width:auto;
			height: 200px;
			background-color: #cafafa;
		}
		#fotoPerfil{
			float:left;
			width:160px;
			height:160px;
			background-color: blue;
			margin-top:16px;
			margin-left:65px;
		}
		#rodape{
			width:auto;
			height:260px;
			background-color: #fafaca;
		}
		.menuSuspenso{	
			padding:0;
			margin:0;
			display:block;
			width: 60px;
			height:40px;						
			float:right;
			margin-left:8px;
		}
		p.menuSuspenso{
			text-align:center;
			font-family:sans-serif;			
			font-size:18px;
			color:blue;
		}
	</style>
</head>
<body>
	<div id="geral">
		<div id="menuTop">
			<div id="menuLinks">
				<p class="menuSuspenso"><a href="#">Equipe</a></p>				
				<p class="menuSuspenso"><a href="#">Sobre</a></p>
				<p class="menuSuspenso"><a href="#">Home</a></p>				
			</div>
		</div>
		<div id="divBanner">
			<div id="bannerLeft"></div>
			<div id="bannerRight"></div>
		</div>
		<div id="divImg">
			<div id="fotoPerfil"></div>
			<div id="fotoPerfil"></div>
			<div id="fotoPerfil"></div>
			<div id="fotoPerfil"></div>
		</div>
		<div id="rodape"></div>
	</div>
</body>
</html>

```
