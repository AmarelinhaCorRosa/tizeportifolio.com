# tizeportifolio.com
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Catálogo de Broches</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<style>body {
    margin: 0;
    padding: 0;
    background-color: #D8A8E4 ;
    color: #3C2E42;
    font-family: 'Quicksand', sans-serif;
}

/* Estilo do topo */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color:  #D8A8E4;
  padding: 10px 20px;
  border-bottom: 2px;
  margin: 0;
  border: none;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

/* Área da logo + título */
.logo-area {
  display: flex;
  align-items: center;
  gap: 10px;
}

.logo {
  width: 40px;
  height: auto;
  border-radius: 8px; /* opcional */
}

.titulo {
  font-size: 1.5rem;
  font-weight: bold;
  color: #3C2E42;
  font-family: 'Quicksand', sans-serif;
}
.menu{
    display: flex;
    gap: 20px;
}

.menu a {
    background-color: #D8A8E4;
    text-decoration: none;
    color: #3C2E42;
    padding: 10px 15px;
    border-radius: 5px;
    transition: background-color 0.3s, color 0.3s;
}
.menu a:hover {
  background-color: #FFEB7E;
}

.container {
            font-family: Arial, sans-serif;
            background:#FDDDE3;
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
.tabs {
    text-align: center;
    margin-bottom: 20px;
}
.tabs button {
    padding: 10px 20px;
    margin: 0 5px;
    border: none;
    border-radius: 5px;
    background-color: #D8A8E4;
    color: white;
    cursor: pointer;
    transition: background 0.3s;
}
.tabs button.active {
    background-color: #F9B7C4;
}
.name {
            text-align: center;
            width: 100%;
            margin-bottom: 20px;
            font-size: 24px;
            color: #333;
        }
        .broches {
            background: #FFF0E6;
            border: 1px solid #7E5DAE;
            border-radius: 8px;
            padding: 15px;
            max-width: 220px; /* Largura máxima dos broches */
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            flex: 1 1 220px; /* Permite que os broches se ajustem */
        }

        .broches img {
            width: 100%;
            max-height: 250px;
            object-fit: cover;
            border-radius: 4px;
        }

        .broches d {
            margin-top: 0;
            font-size: 16px;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 4px;
            display: inline-block;
        }
        .d {
            color: green;
        }

        .i{
            color: red;
        }

        h2 {
            text-align: center;
        }

        h3 {
            margin: 10px 0 5px;
            text-align: center;
        }

        p {
            margin: 4px 0;
            text-align: center;
        }

        .whatsapp-fixo {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 999;
  width: 60px;
  height: 60px;
}

.whatsapp-fixo img {
  width: 100%;
  height: auto;
  border-radius: 50%;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s;
}

.whatsapp-fixo img:hover {
  transform: scale(1.1);
}


        /* Media Query para telas menores (celulares) */
        @media (max-width: 768px) {
            .broches {
                max-width: 36%; /* 2 broches por linha */
            }
        }

        /* Media Query para telas maiores (notebooks e desktops) */
        @media (min-width: 768px) {
            .broches {
                max-width: 13%; /* 7 broches por linha */
            }
        }</style>
<header>
<div class="logo-area">
    <img src="img/logo2.png" alt="Logo" class="logo">
    <span class="titulo">Lojinha da Tize</span>
  </div>
   <nav class="menu">
    <a href="index.html">Central</a>
    <a href="broches.html"style="background-color: #F9B7C4;">Broches</a>
    <a href="Livro.html">Livro</a>
  </nav>
</header>
<body>
    <h1 class="name">Catálogo de Broches</h1>
<div class="tabs">
  <button data-filter="all" class="active">Todos</button>
  <button data-filter="d">Disponíveis</button>
  <button data-filter="i">Indisponíveis</button>
</div>
<div class="container">
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/wanda1.png" alt="Broche 1">
                <h2>Wanda #1</h2>
                <p>Padrinhos Magicos</p>
                <p>Preço: R$ 7.00</p>
            </div>
                <div class="broches">
                <h3 class="i"></h3>
                <img src="img/cosmo1.png" alt="Broche 1">
                <h2>Cosmo #2</h2>
                <p>Padrinhos Magicos</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/cosmowanda.png" alt="Broche 1">
                <h2>Wanda e Cosmo #3</h2>
                <p>Padrinhos Magicos</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/" alt="Broche 1">
                <h2>Capivara e Tartaruga #4</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>   
            </div>
            <div class="broches">   
                <h3 class="i"></h3>
                <img src="img/" alt="Broche 1">
                <h2>Capivara e Sapo #5</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/" alt="Broche 1">
                <h2>Capivara e Filhote #6</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/" alt="Broche 1">
                <h2>Capivara e Gatinho #7</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/" alt="Broche 1">
                <h2>Capivara e Motosserra #8</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
                <div class="broches">
                <h3 class="i"></h3>
                <img src="img/" alt="Broche 1">
                <h2>Capivara e Pelicano #9</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
                            <div class="broches">
                <h3 class="i"></h3>
                <img src=img/fantasma1.png alt="Broche 1">
                <h2>Fantasminha hallowwen flores #10</h2>
                <p>Outros</p>
                <p>Preço: R$ 7.00</p>
            </div>
                            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/fantasma2.png" alt="Broche 1">
                <h2>Fantasminha Peixes azuis #11</h2>
                <p>Outros</p>
                <p>Preço: R$ 7.00</p>
            </div>
                            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/fantasma3.png" alt="Broche 1">
                <h2>Fantasminha Cogumelo #12</h2>
                <p>Outros</p>
                <p>Preço: R$ 7.00</p>
            </div>
                            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/fantasma4.png" alt="Broche 1">
                <h2>Fantasminha Telefone #13</h2>
                <p>Outros</p>
                <p>Preço: R$ 7.00</p>
            </div>
                            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/fantasma5.png" alt="Broche 1">
                <h2>Fantasminha Leitor #14</h2>
                <p>Outros</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/vangogh1.png" alt="Broche 1">
                <h2>Vincent Van Gogh #15</h2>
                <p>Arte e Historico</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/estatua1.png" alt="Broche 1">
                <h2>Estatua com Oculos 3D #16</h2>
                <p>Arte e Historico</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/estatua2.png" alt="Broche 1">
                <h2>Estatua cortada ao meio #17</h2>
                <p>Arte e Historico</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/estatua3.png" alt="Broche 1">
                <h2>Estatua Borrada #18</h2>
                <p>Arte e Historico</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/estatua4.png" alt="Broche 1">
                <h2>Estatua Relogio derretido #19</h2>
                <p>Arte e Historico</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/noface1.png" alt="Broche 1">
                <h2>No-Face Flores #20</h2>
                <p>Chihiro</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/noface3.png" alt="Broche 1">
                <h2>No-Face Lua preta #21</h2>
                <p>Chihiro</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/noface2.png" alt="Broche 1">
                <h2>No-Face Pote #22</h2>
                <p>Chihiro</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/noface4.png" alt="Broche 1">
                <h2>No-Face "But first coffee" #23</h2>
                <p>Chihiro</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/noface5.png" alt="Broche 1">
                <h2>No-Face Foice #24</h2>
                <p>Chihiro</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/noface6.png" alt="Broche 1">
                <h2>No-Face Paisagem #25</h2>
                <p>Chihiro</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/tartaruga1.png" alt="Broche 1">
                <h2>Tartaruga "Turtley cool, Dude" #26</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/sapo1.png" alt="Broche 1">
                <h2>Sapo "Toad you so" #27</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/husky1.png" alt="Broche 1">
                <h2>Husky "Howl you doin'" #28</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/corgi1.png" alt="Broche 1">
                <h2>Corgi "Hot Dog" #29</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/lontra1.png" alt="Broche 1">
                <h2>Lontra "Be kind to otters" #30</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div> 
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/gato1.jpg" alt="Broche 1">
                <h2>Gato preto 1 #31</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div> 
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/gato2.jpg" alt="Broche 1">
                <h2>Gato preto 2 #32</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div> 
             <div class="broches">
                <h3 class="i"></h3>
                <img src="img/gato3.png" alt="Broche 1">
                <h2>Gato preto 3 #33</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>            
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/gato4.jpg" alt="Broche 1">
                <h2>Gato preto 4 #34</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div> 
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/lufalufa1.png" alt="Broche 1">
                <h2>Bração Lufa-Lufa #35</h2>
                <p>Harry Potter</p>
                <p>Preço: R$ 7.00</p>
            </div> 
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/corvinal1.png" alt="Broche 1">
                <h2>Bração Corvinal #36</h2>
                <p>Harry Potter</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/" alt="Broche 1">
                <h2>Bração Sonserina #37</h2>
                <p>Harry Potter</p>
                <p>Preço: R$ 7.00</p>
            </div> 
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/" alt="Broche 1">
                <h2>Bração Grifinoria #38</h2>
                <p>Harry Potter</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/" alt="Broche 1">
                <h2>Hello I'm a Monbebe #39</h2>
                <p>K-pop</p>
                <p>Preço: R$ 7.00</p>
            </div> 
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/gojosatoru1.png" alt="Broche 1">
                <h2>Satoru 1 #40</h2>
                <p>Jujutsu Kaisen</p>
                <p>Preço: R$ 7.00</p>
            </div> 
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/gojosatoru2.png" alt="Broche 1">
                <h2>Satoru 2 #41</h2>
                <p>Jujutsu Kaisen</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/gojosatoru3.png" alt="Broche 1">
                <h2>Satoru 3 #42</h2>
                <p>Jujutsu Kaisen</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/gojosatorucat1.png" alt="Broche 1">
                <h2>Satoru 4 #43</h2>
                <p>Jujutsu Kaisen</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/gojosatorucat2.png" alt="Broche 1">
                <h2>Satoru 5 #44</h2>
                <p>Jujutsu Kaisen</p>
                <p>Preço: R$ 7.00</p>

            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/gojosatorucat3.png" alt="Broche 1">
                <h2>Satoru 6 #45</h2>
                <p>Jujutsu Kaisen</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/gojosatorucat4.png" alt="Broche 1">
                <h2>Satoru 7 #46</h2>
                <p>Jujutsu Kaisen</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/beladama1coraline.png" alt="Broche 1">
                <h2>Bela Dama 1 #47</h2>
                <p>Coraline</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/beladama2coraline.png" alt="Broche 1">
                <h2>Bela Dama 2 #48</h2>
                <p>Coraline</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/olhomagico1coraline.png" alt="Broche 1">
                <h2>Olho Magico #49</h2>
                <p>Coraline</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/gato1coraline.png" alt="Broche 1">
                <h2>Gato Preto #50</h2>
                <p>Coraline</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/gato2coraline.png" alt="Broche 1">
                <h2>Gato preto no tunel #51</h2>
                <p>Coraline</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/borboleta1.png" alt="Broche 1">
                <h2>Borboleta 1 #52</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/borboleta2.png" alt="Broche 1">
                <h2>Borboleta 2 #53</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/borboleta3.png" alt="Broche 1">
                <h2>Borboleta 3 #54</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/borboleta4.png" alt="Broche 1">
                <h2>Borboleta 4 #55</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/borboleta5.png" alt="Broche 1">
                <h2>Borboleta 5 #56</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/espiritos1coraline.png" alt="Broche 1">
                <h2>Espiritos 1 #57</h2>
                <p>Coraline</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/espiritos2coraline.png" alt="Broche 1">
                <h2>Espiritos 2 #58</h2>
                <p>Coraline</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/gato5.jpg" alt="Broche 1">
                <h2>Gato 5 #59</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>

            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/gato6.jpg" alt="Broche 1">
                <h2>Gato 6 #60</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/gato7.jpg" alt="Broche 1">
                <h2>Gato 7 #61</h2>
                <p>Animais</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/helloiamstressed.png" alt="Broche 1">
                <h2>Hello, I am Stressed #62</h2>
                <p>Outros</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/hellokitty1.png" alt="Broche 1">
                <h2>Hello Kitty 1 #63</h2>
                <p>Hello Kitty</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/jujuba1horadeaventura.png" alt="Broche 1">
                <h2>Jujuba #64</h2>
                <p>Hora de Aventura</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/marceline1horadeaventura.png" alt="Broche 1">
                <h2>Marchall Lee/Marceline 1 #65</h2>
                <p>Hora de Aventura</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/marceline2horadeaventura.png" alt="Broche 1">
                <h2>Marceline tocando guitarra 2 #66</h2>
                <p>Hora de Aventura</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/marceline3horadeaventura.png" alt="Broche 1">
                <h2>Marceline "Your Rock" 3 #67</h2>
                <p>Hora de Aventura</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/marceline4horadeaventura.png" alt="Broche 1">
                <h2>Marceline Guitarra "Everithing Stays" #68</h2>
                <p>Hora de Aventura</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/marcelinejujuba1horadeaventura.png" alt="Broche 1">
                <h2>Marceline e Princessa Jujuba #69</h2>
                <p>Hora de Aventura</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/walle2.png" alt="Broche 1">
                <h2>M-O #70</h2>
                <p>Wall-E</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/walle3.png" alt="Broche 1">
                <h2>Wall-E ultimo broto #71</h2>
                <p>Wall-E</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/walle4.png" alt="Broche 1">
                <h2>Wall-E amarelo #72</h2>
                <p>Wall-E</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="d"></h3>
                <img src="img/walle5.png" alt="Broche 1">
                <h2>Eva #73</h2>
                <p>Wall-E</p>
                <p>Preço: R$ 7.00</p>
            </div>
            <div class="broches">
                <h3 class="i"></h3>
                <img src="img/wally.png" alt="Broche 1">
                <h2>Burn-E #</h2>
                <p>Wall-E</p>
                <p>Preço: R$ 7.00</p>
            </div>
</div>
<a href="https://wa.me/5511971834426?text=Oi%2C%20quero%20saber%20mais%20sobre%20os%20broches%21
" class="whatsapp-fixo" target="_blank" title="Fale comigo no WhatsApp">
  <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp" />
</a>
</body>
<script>
  document.querySelectorAll('.broches h3').forEach(function(h3) {
    const status = h3.classList.contains('d') ? 'Disponível' : 'Indisponível';
      h3.textContent = status;
  });
    // Sistema de abas
  document.querySelectorAll('.tabs button').forEach(function(botao) {
    botao.addEventListener('click', function() {
      // Remove a classe 'active' de todos os botões
      document.querySelectorAll('.tabs button').forEach(b => b.classList.remove('active'));
      botao.classList.add('active');

      const filtro = botao.getAttribute('data-filter');
      document.querySelectorAll('.broches').forEach(function(item) {
        const h3 = item.querySelector('h3');
        if (filtro === 'all') {
          item.style.display = 'block';
        } else if (h3.classList.contains(filtro)) {
          item.style.display = 'block';
        } else {
          item.style.display = 'none';
        }
      });
    });
  });

</script>
</html>
