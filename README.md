<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lugares Turísticos na Europa</title>
  <style>
    /* Adicione estilos CSS aqui, se desejar */
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #0066cc;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    h1 {
      margin: 0;
    }
    nav {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
    }
    main {
      padding: 20px;
    }
    section {
      margin-bottom: 30px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      border-radius: 4px;
      padding: 20px;
    }
    h2 {
      color: #0066cc;
      margin-top: 0;
    }
    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 10px auto;
    }
    p {
      margin: 10px 0;
    }
    footer {
      background-color: #f5f5f5;
      text-align: center;
      padding: 10px;
    }
    .btn-top {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #0066cc;
      color: #fff;
      padding: 10px 20px;
      border-radius: 4px;
      display: none;
    }
    .useful-info {
      background-color: #f9f9f9;
      padding: 20px;
      margin-top: 30px;
    }
    .useful-info h3 {
      color: #0066cc;
      margin-top: 0;
    }
  </style>
</head>

<body>
  <header>
    <h1>Lugares Turísticos na Europa</h1>
    <p>Bem-vindo à Europa! O continente repleto de história, cultura e paisagens deslumbrantes. Explore conosco alguns dos lugares turísticos mais encantadores que a Europa tem a oferecer. De cidades icônicas a paisagens naturais deslumbrantes, aqui você encontrará uma variedade de destinos que irão cativar seus sentidos e deixar memórias inesquecíveis.</p>
  </header>

  <nav>
    <a href="#paris">Paris</a>
    <a href="#santorini">Santorini</a>
    <a href="#roma">Roma</a>
    <a href="#amsterda">Amsterdã</a>
    <!-- Adicione mais destinos no menu de navegação conforme necessário -->
  </nav>

  <main>
    <section id="paris">
      <h2>Paris, França</h2>
      <div class="card">
        <img src="imagem-paris.jpg" alt="Imagem de Paris">
        <p>Paris é conhecida como a "Cidade do Amor" e não é difícil entender o porquê. Seus marcos emblemáticos, como a Torre Eiffel, o Louvre e a Catedral de Notre-Dame, são apenas algumas das atrações imperdíveis que esta cidade mágica oferece. Passeie pelas charmosas ruas de paralelepípedos, desfrute da deliciosa culinária francesa e absorva a atmosfera romântica que envolve cada canto da cidade.</p>
      </div>
    </section>

    <section id="santorini">
      <h2>Santorini, Grécia</h2>
      <div class="card">
        <img src="imagem-santorini.jpg" alt="Imagem de Santorini">
        <p>A ilha de Santorini é um verdadeiro paraíso no Mar Egeu. Com suas casinhas brancas e cúpulas azuis empoleiradas nas falésias vulcânicas, é um cenário de tirar o fôlego. Além de suas vistas deslumbrantes, Santorini oferece praias de areia vulcânica, vinhedos pitorescos e um pôr do sol inesquecível. Um destino romântico e deslumbrante que certamente irá encantar qualquer viajante.</p>
      </div>
    </section>

    <section id="roma">
      <h2>Roma, Itália</h2>
      <div class="card">
        <img src="imagem-roma.jpg" alt="Imagem de Roma">
        <p>Roma, a capital da Itália, é um museu a céu aberto, repleta de monumentos históricos e ruínas antigas. Visite o Coliseu, o Panteão e o Fórum Romano para uma verdadeira viagem ao passado. Não deixe de jogar uma moeda na Fontana di Trevi para garantir o seu retorno à Cidade Eterna. A rica cultura italiana, a gastronomia deliciosa e o charme de suas ruas tornam Roma uma experiência turística inesquecível.</p>
      </div>
    </section>

    <section id="amsterda">
      <h2>Amsterdã, Holanda</h2>
      <div class="card">
        <img src="imagem-amsterda.jpg" alt="Imagem de Amsterdã">
        <p>Amsterdã é uma cidade encantadora, famosa por seus canais pitorescos, arquitetura única e cultura vibrante. Explore os museus de classe mundial, como o Rijksmuseum e o Museu Van Gogh, ou alugue uma bicicleta e percorra as ruas da cidade como um local. A atmosfera acolhedora e liberal de Amsterdã é cativante e oferece uma experiência única na Europa.</p>
      </div>
    </section>

    <!-- Adicione mais sections com outros destinos turísticos na Europa -->

    <section class="useful-info">
      <h3>Informações Úteis sobre a Europa</h3>
      <p>A Europa é um continente rico em cultura, história e belezas naturais. Antes de viajar, confira algumas dicas úteis:</p>
      <ul>
        <li>Documentos Necessários: Verifique os requisitos de visto e passaporte para entrar nos países que você pretende visitar.</li>
        <li>Moeda: A maioria dos países da União Europeia usa o Euro, mas alguns têm suas próprias moedas. Verifique a moeda do país que você visitará.</li>
        <li>Idiomas: A Europa tem uma grande diversidade de idiomas. O inglês é amplamente falado, mas aprender algumas palavras básicas do idioma local pode ser útil.</li>
        <li>Transporte: Utilize o eficiente sistema de transporte público da Europa para se locomover nas cidades. Trens e ônibus são opções populares para viagens entre países.</li>
        <li>Gastronomia: Experimente as delícias culinárias de cada país, pois a Europa é famosa por sua comida saborosa e variada.</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>Contato: contato@europatravel.com</p>
    <p>&copy; 2023 Europa Travel</p>
  </footer>

  <button class="btn-top" onclick="topFunction()">Voltar ao Topo</button>

  <script>
    // Botão para voltar ao topo da página
    function topFunction() {
      document.body.scrollTop = 0;
      document.documentElement.scrollTop = 0;
    }

    // Exibir o botão de voltar ao topo quando o usuário rolar a página
    window.onscroll = function() {scrollFunction()};

    function scrollFunction() {
      if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
        document.querySelector(".btn-top").style.display = "block";
      } else {
        document.querySelector(".btn-top").style.display = "none";
      }
    }
  </script>
</body>

</html>
