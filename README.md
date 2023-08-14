<!DOCTYPE html>
<html>
<head>
    <title>Corretora de Seguros ABC</title>
    <style>
			
 	#floating-button {
            position: fixed;
            right: 50px;
            bottom: 50px;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            text-align: center;
            font-size: 20px;
            line-height: 50px;
            cursor: pointer;
            z-index: 9999;
            transition: transform 0.2s ease-in-out;
        }

        #floating-button:hover {
            transform: scale(1.3);
        }
					/* Adicione media queries para ajustar o botão em dispositivos menores */

        body {
	    background-image: url(image2.png);
            color: #000000; /* Texto preto */
            text-align: center; /* Centraliza o conteúdo */
            margin: 0px;

										font-family: "Helvética", serif;
        }

        /* Estilo da barra de navegação */
        nav {
            background-image: url(image2.png);
            color: #ffffff; /* Texto branco */
            padding: 10px;
												display: flex;
            align-items: center;
        }
 	 nav img.logo {
            width: 130px;
            height: 50px;
            margin-right: 200px;
	margin-left: 20px;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: black; /* Texto branco */
            text-decoration: none;
									cursor: pointer;
								font-size:25px;
									transition: transform 0.2s ease-in-out;
        }
					 #nav ul li a:hover {
            transform: scale(1.3);
        }

 	nav ul.social-logos {
            display: flex;
            justify-content: flex-end;
        }
	nav ul.social-logos2 {
            display: flex;
            justify-content: flex-end;
        }
        nav ul.social-logos li {
            margin-right: 10px;
	margin-left: 150px;
        }
  	nav ul.social-logos2 li {
            margin-right: 10px;

}
        nav ul.social-logos li a img {
            width: 30px;
            height: 30px;
        }
					
	nav ul.social-logos2 li a img {
            width: 30px;
            height: 30px;
        }
					
					 /* Estilização do menu dropdown */
        .dropdown {
            position: relative;
            display: inline-block;
            width: 100px;
        }

        .dropdown-content {
            background-color: aliceblue;
            background-size: cover;
            display: none;
            position: absolute;
            top: 25px;
            z-index: 1;
        }

        .dropdown-content a {
            font-size: 20px;
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        .dropdown-content a:hover {
            background-color: #f1f1f1;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }
							 /* Estilos para o container */
    .container {
      display: flex;
      align-items: center;
					 justify-content: space-around;
					height: 250px;
					border-top: 2px solid blue;
    }

    /* Estilos para o logotipo */
    .logo {
      width: 200px;
      height: 100px;
      /* Adicione seus estilos personalizados para o logotipo aqui */
    }

    /* Estilos para os textos */
    .textos, .onde {
      text-align: center;
					font-size: 20px;
				
      /* Adicione seus estilos personalizados para os textos aqui */
    }
					
					/* Estilos para o rodapé */
     .rodape {
						color: white;
      background-color: royalblue;
      padding: 20px;
      text-align: center;
    }

    /* Estilos para o texto dos direitos reservados */
    .direitos {
      float: left;
					 margin-left:100px;
    }

    /* Estilos para o texto dos criadores */
    .criadores {
      float: right;
					 margin-right:100px;
    }
					.image-container {
            width: 100%;
            height: 500px;
		            max-width: 96%;
            padding: 10px;
												margin-left: 10px;
        }
        
        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
.home {
						            max-width: 90%;
            padding: 1%;
												margin-left: 4%;
												font-size: 25px;
					}
					.home h1,h3 {
						color:blue;
					}
					
					.contratar {
						            max-width: 90%;
            padding: 1%;
												margin-left: 4%;
												font-size: 25px;
					}
					
					.contratar h1{
						color:blue;
						font-family:sans-serif;
					}
					.contratar h3{
						color:mediumblue;
					}
					
					.premio{
						text-align: center;
						max-height: 20%;
						max-width:  80%;
						margin-bottom: 10px;
					}
	</style>
	</head>
					
					<body>

    <!-- Barra de navegação -->
    <nav>
	<img class="logo" src="logo2.png" alt="Logo">
        <ul>
            <li><a href="home.html">Sobre Nós</a></li>
            <li><div class="dropdown">
        <a href="#">Serviços</a>
        <div class="dropdown-content">
            <a href="pag1.html">Serviço para Transportador</a>
            <a href="pag2.html">Serviço para Embargador</a>
        </div>
    </div>
            </li>
            <li><a href="cotacao.html">Cotação</a></li>
        </ul>
	<ul class="social-logos">
          <li><a href="https://instagram.com/venturicorretora?igshid=Y2I2MzMwZWM3ZA==" target='_blank'><img src="instagram.png" alt="Instagram"></a></li>
	</ul>

    </nav>
						<div class="image-container">
      		  <img id="myImage" src="cam5.jpg" alt="Imagem" />
	</div>
						<div class="home">
        <h1>Bem-vindo à Corretora de Seguros ABC</h1>
        <p>Do desejo de inovar no mercado de seguros, nosso CEO Walter Venturi fundou a Venturi Corretora com objetivo de atender a demanda de transportes de maneira mais específica.
</p>
        <p>Trabalhando desde o início com base nas necessidades do cliente, nosso modelo de venda consultiva diferencia-se das demais por entregarmos todo nosso conhecimento em cada atendimento, agregando grande valor aos serviços prestados.
</p>
							<p>Hoje, atendemos transportadores e embarcadores de todo país, visando sempre conseguir as melhores condições para nossos clientes. Além disso, temos parcerias com grandes gerenciadoras, sendo essa mais uma maneira de reduzir os riscos dos embarques.
</p>
							<p>Nosso foco não está na quantidade de clientes, mas sim na qualidade das apólices, que aliadas a experiência do nosso time, asseguram plenamente todas as operações. 
</p>
						</div>
						<div class="contratar">
							      <h1>Motivos para contratar a Venturi </h1>
							<h3>Relacionamento com grandes seguradoras</h3>
        <p>A Venturi se diferencia de outras corretoras por ter um forte relacionamento com as maiores seguradoras do mercado, sendo possível garantir descontos e excelentes condições nas apólices negociadas. 

</p>
							<h3>Agilidade na resolução de problemas
							</h3>
							<p>Em caso de sinistro ou qualquer outro imprevisto, nossa equipe está sempre pronta para te atender e resolver seus problemas com auxílio especializado.

</p>
				<h3>Reconhecimento no ramo de transportes


	</h3>
							<p>Graças ao nosso brilhante trabalho, a Venturi já foi reconhecida em diversos eventos por seguradoras do ramo. Nossa experiência faz com que Venturi se coloque entre as maiores 
</p>
						</div>
						

<img class="premio" src="premio.jpg" alt="premio" />

					
<div class="container">
    <img class="logo" src="logo3.png" alt="Logo">
    <div class="textos">
      <h2>Telefones para contato</h2>
      <p>(11) 2506-2380</p>
					 <p>(11) 2506-2354</p>
	</div>
    <div class="onde">
	     <h2>Onde estamos</h2>
      <p>Rua Serra de Botucatu, 1195 - sala 108 - Tatuapé</p>
					<p>São Paulo - SP - CEP:03317-001</p>
					</div>
  </div>
	
<a id="floating-button" href="#" target="_blank">
        <img src="https://logodownload.org/wp-content/uploads/2015/04/whatsapp-logo-png-0-1080x1080.png" alt="Imagem do botão" width="85" height="85">
    </a>

 <script>
        var floatingButton = document.getElementById('floating-button');
        var link = "https://wa.me/11950524592"; // Coloque o link desejado aqui

        floatingButton.addEventListener('click', function () {
            window.open(link, '_blank');
        });
 var images = [
            "cam5.jpg",
            "cam3.jpg",
            "cam2.jpg"
        ];
        
        var currentIndex = 0;
        
        function changeImage() {
            var img = document.getElementById("myImage");
            img.src = images[currentIndex];
            
            currentIndex++;
            if (currentIndex >= images.length) {
                currentIndex = 0;
            }
        }
        
        setInterval(changeImage, 6000); // 10 segundos em milissegundos
    </script>
						
						<div class="rodape">
    <span class="direitos">&copy; 2023 - Todos os direitos reservados</span>
    <span class="criadores">Criado por Thiago Sorrens e Ana Beatriz Araújo</span>
  </div>




	</body>
</html>
