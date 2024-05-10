<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harry Potter</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <section class="conteudo-principal">
        <h2 class="titulo-principal">Harry Potter<span>_</span></h2>
       
        <div class="conteudo">
        <div class="botoes">
            <button class="botao ativo">A História de Harry Potter </button>
            <button class="botao">Personagens Principais</button>
            <button class="botao">A História de Lord Voldermort</button>
            <button class="botao">Livros e filmes</button>
        </div>
        <div class="abas-textos">
            <div class="aba-conteudo ativo">
                <h4 class="aba-conteudo-titulo-principal">Harry Potter</h4>
                <h4 class="aba-conteudo-titulo-secundario">
                    Harry Potter" é uma série de sete livros escrita por J.K. Rowling, que segue a jornada de um jovem bruxo, Harry Potter, e seus amigos, Hermione Granger e Ron Weasley, enquanto lutam contra o malvado bruxo Lord Voldemort. A história começa quando Harry descobre que é um bruxo aos 11 anos e é convidado a frequentar a Escola de Magia e Bruxaria de Hogwarts. Ao longo dos anos, Harry e seus amigos enfrentam desafios, descobrem segredos sobre suas famílias e lutam para derrotar Voldemort e seus seguidores, os Comensais da Morte. A série aborda temas como amor, amizade, coragem e sacrifício. No final, Harry triunfa sobre Voldemort e salva o mundo mágico.</h4>
            </div>
            <div class="aba-conteudo">
                <h3 class="aba-conteudo-titulo-principal">Principais Personagens</h3>
                <h4 class="aba-conteudo-titulo-secundario">
                    1-Harry Potter: O protagonista da série, um bruxo que sobreviveu ao ataque de Lord Voldemort quando era apenas um bebê. Ele frequenta a Escola de Magia e Bruxaria de Hogwarts e é conhecido por sua cicatriz em forma de raio na testa.
                    2-Hermione Granger: Uma bruxa inteligente e dedicada, amiga próxima de Harry e Ron. Ela é conhecida por sua habilidade em magia e por sua determinação em aprender.
                    3-Ron Weasley: Melhor amigo de Harry, proveniente de uma família grande de bruxos. Ele é leal e corajoso, embora às vezes inseguro em comparação com seus irmãos mais velhos.
                    4-Lord Voldemort: O principal antagonista da série, um bruxo das trevas que busca poder e imortalidade. Seu nome verdadeiro é Tom Riddle.
                    5-Alvo Dumbledore: O diretor de Hogwarts e um dos bruxos mais poderosos de sua época. Ele é um mentor para Harry e lidera a luta contra Voldemort.
                    6-Severo Snape: Um professor em Hogwarts com uma história complicada. Ele é inicialmente retratado como um antagonista, mas sua verdadeira lealdade é revelada ao longo da série.
                    7-Rúbeo Hagrid: O guarda-caça de Hogwarts, meio-gigante e amigo próximo de Harry. Ele muitas vezes o orienta e o protege.</h4>
            </div>
            <div class="aba-conteudo">
                <h3 class="aba-conteudo-titulo-principal">Lord Voldermort</h3>
                <h4 class="aba-conteudo-titulo-secundario">
                    Lord Voldemort, originalmente conhecido como Tom Riddle, é o principal antagonista na série "Harry Potter". Ele nasceu de uma união não natural entre Tom Riddle Sr. e Merope Gaunt, uma bruxa que o amava profundamente e que morreu logo após seu nascimento. Tom cresceu em um orfanato trouxa e descobriu sua herança mágica aos 11 anos, quando recebeu a carta para Hogwarts. Durante seus anos em Hogwarts, ele mostrou um talento excepcional para a magia, mas também revelou uma personalidade manipuladora e sádica. Ao investigar magia negra e a imortalidade, Tom se tornou Lord Voldemort, apagando seu passado e criando Horcruxes para dividir sua alma, tornando-se praticamente imortal. Sua busca por poder o levou a cometer inúmeros crimes, incluindo a tentativa de assassinar Harry Potter quando era apenas um bebê. A história de Voldemort é marcada por sua busca incessante por poder, seu medo da morte e sua incapacidade de compreender o verdadeiro poder do amor e da bondade. No final, ele é derrotado por Harry Potter, perdendo sua forma física e sendo finalmente destruído quando Harry sacrifica sua própria vida para derrotá-lo definitivamente.</h4>
            </div>
            <div class="aba-conteudo">
                <h3 class="aba-conteudo-titulo-principal">Livros e filmes</h3>
                <h4 class="aba-conteudo-titulo-secundario">Harry Potter e a Pedra Filosofal (1997)-Livro
                    Harry Potter e a Câmara Secreta (1998)-Livro
                    Harry Potter e o Prisioneiro de Azkaban (1999)-Livro
                    Harry Potter e o Cálice de fogo (2000)-Livro
                    Harry Potter a Ordem da Fênix (2003)-Livro 
                    Harry Potter e o Enigma do Príncipe (2005)-Livro
                    Harry Potter e as Relíquias da Morte (2007)-Livro
                    Harry Potter e a Criança Amaldiçoada (2016)-Livro
                    Harry Potter e  a Pedra filosofal (2001)-Filme
                    Harry Potter e a Câmara Secreta (2002)-Filme
                    Harry Potter e o Prisioneiro de Azkaban (2004)-Filme
                    Harry Potter e o Cálice de fogo (2005)-Filme
                    Harry Potter a Ordem da Fênix (2007)-Filme 
                    Harry Potter e o Enigma do Príncipe (2009)-Filme
                    Harry Potter e as Relíquias da Morte: Parte 1 (2010)-Filme
                    Harry Potter e as Relíquias da Morte: Parte 2 (2011)-Filme
                    Comemoração de 20 Anos de Harry Potter: De volta a Hogwarts (2022)-Filme


                </h4>
            </div>
        </div>
    </div>
    </section>
    <script src="main.js"></script>
</body>
</html>

Style.css
h1{
    text-align: center;
}
:root {
    --cor-de-fundo: #1E1E1E;
    --azul: #3449eb;
    --branco: #FFFFFF;
    --botao-ativo: #3A375E;
    --botao-inativo: rgba(58, 55, 94, 0.5);
    --texto-fundo: rgba(58, 55, 94, 0.3);
}

body {
    background-color: var(--cor-de-fundo);
    color: var(--branco);
    font-family: 'Chakra Petch', sans-serif;
}


.conteudo-principal {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    max-width: 1200px;
    width: 100%;
    margin: 0 auto;
}

.titulo-principal {
    text-align: left;
    width: 100%;
    font-size: 32px;
}

.titulo-principal span {
    color: var(--azul);
    text-align:center;
}


.botao {
    font-family: 'Chakra Petch', sans-serif;
    background-color: var(--botao-inativo);
    color: var(--branco);
    display: flex;
    justify-content: center;
    padding: 1em;
    font-size: 18px;
    align-items: center;
    width: 100%;
    border-bottom: 4px solid var(--botao-ativo);
    border-left: 2px solid var(--botao-ativo);
    border-right: 2px solid var(--botao-ativo);
    border-top: none;
}

.botao:first-child {
    border-radius: 40px 40px 0 0;
}

.botoes {
    display: block;
}

.botao.ativo{
    background-color: var(--botao-ativo);
    border-bottom: 4px solid var(--azul);
}

.abas-textos{
    background-color: var(--texto-fundo);
    padding: 40px;
    border-radius: 0 0 40px 40px;
}
.aba-conteudo.ativo{
    display:block;
}

.aba-conteudo{
    display: none;
}

.aba-conteudo-titulo-principal{
    font-size: 28px;
    text-align: center;
}
.aba-conteudo-titulo-secundario{
    text-align: center;
    text-transform: uppercase;}

    Main.js
const botoes = document.querySelectorAll(".botao");
const textos = document.querySelectorAll(".aba-conteudo");

for (let i = 0; i < botoes.length; i++) {
    botoes[i].onclick = function () {

        for (let j = 0; j < botoes.length; j++) {
            botoes[j].classList.remove("ativo");
            textos[j].classList.remove("ativo");
        }

        botoes[i].classList.add("ativo");
        textos[i].classList.add("ativo");
    }
}
