# EspetariaGrupo3
<!DOCTYPE html>

<html lang="pt-BR">
<head>
	<meta charset="UTF-8">
	<title>Code - desenvolvimento de site</title>
	<link rel="stylesheet" type="text/css" href="css/pag_estilo.css">
</head>
<body class="color-page">
	<div class="contanier-principal">
		<header>
			<div class="logo">
				<a href="espetaria.html">
					<img src="C:\Users\PC\Desktop\Leoo\Site_Espetaria\imagens\Logo.jpg" alt="logo site">
				</a>
			</div>
			<nav> 
				<ul>
					<li><a href="espetaria.html">Home</a></li>
					<li><a href="cardapio.html">Cardápio</a></li>
					<li><a href="Sobre.html">Sobre<a/></li>
					<li><a href="Contato.html">Contato</a></li>
				</ul>
			</nav>
		</header>
		<section id='banner'>
			<img src="C:\Users\PC\Desktop\Leoo\Site_Espetaria\imagens\Banner.jpeg" 
					alt="banner-topo">
		</section>


		<div id="openModal" class="modalDialog"> 
			<div>
				<a href="#close" class="close">X</a>
				<h1>Venha conhecer nossa <strong>Espetaria</strong></h1>
				<p>Atualmente atendimento apenas por delivery<i>(Para maoires informações entre em contato conosco em nosso Whatsapp 19 98135-6053)</i>Pedimos colaboração devido a alta demanda de pedidos.<i>    <!--PARA COLOCAR LINK--></i></p>
				<img src="C:\Users\PC\Desktop\Leoo\Site_Espetaria\imagens\Great.png" alt="Great">
			</div>
		</div>

<!--CASO PRECISE ADICIONAR MAIS ITENS AO RODAPÉ

		<div id="openModal1" class="modalDialog"> 
			<div>
				<a href="#close" title="close" class="close">x</a>
				<h1>Tecnologia - Realidade Aumentada</h1>
				<p>De uma forma simples, <b>Realidade Aumentada</b> é uma tecnologia que permite que o mundo virtual seja misturado ao real, possibilitando maior interaçao e abrindo uma nova dimensão na maneira como nós executamos tarefas, ou mesmo as que nós incubimos às maquinas. Assim, se você pensava que os objetos para fora da tela eram elementos de filmes de ficcão científica, está na hora de mudar seus conceitos. Aliás, o que acintece com a <b>Realidade Aumentada</b> é o contrário: você pulará para dentro do mundo virtual para interagir com ojetos que só estão limitados á dia imaginação. - <i>tecmundo.com.br/realidade-aumentada</i></p>
			</div>
		</div>

		<div id="openModal2" class="modalDialog"> 
			<div>
				<a href="#close" title="close" class="close">x</a>
				<h1>Acessibilidade</h1>
				<p><b>Acessibilidade</b> na web significa que oessas com deficiência podem usar a web. Mais especificamente, a acessibilidade na web significa que pessoas com deficiência podem perceber, entender, navegar, interagir e construir para a web. E também beneficia outras pessoas, incluido pessoas idosas com capacidades em mudança devido ao envelhaciemeno - <i>w3c.br/</i></p> 	
			</div>
		</div>
-->
		<!-- ativar pop up Rodapé -->
		<footer>
			<div class='footer-text'>
				<h3>Espetaria</h3>
				<p>Para mais informações sobre nossa espetaria - <a href="#openModal">clique aqui</a>.</p>
			</div>

<!--CASO PRECISE ADICIONAR MAIS ITENS AO RODAPÉ			
			<div class='footer-text'>
				<h3>Tecnologia</h3>
				<p>Você sabe o que é realidade aumentada? Entenda como essa tecnologia funciona. - <a href="#openModal1">clique aqui</a>.</p>
			</div>

			<div class='footer-text'>
				<h3>Acessibilidade</h3>
				<p>Torne seu site acessível utilizando 5 dicas indispensáveis para qualquer site. - <a href="#openModal2">clique aqui</a>.</p>
			</div>
-->			
		</footer>
	</div>
</body>
</html>
