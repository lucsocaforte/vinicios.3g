# vinicios.3g
Html

<!DOCTYPE html>
<html lang="pt-br">


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus objetivos do ano</title>
    <link rel="stylesheet" href="style.css">
</head>


<body>
    <section class="conteudo-principal">
        <h2 class="titulo-principal">Ganhando money no GTA Online<span>_</span></h2>
        <div class="conteudo">
            <div class="botoes">
                <button class="botao ativo">Task do dax</button>
                <button class="botao">Golpe de caio perico</button>
                <button class="botao">Golpe do cassino</button>
                <button class="botao">Andando de carro</button>
            </div>
            <div class="abas-textos">
                <div class="aba-conteudo ativo">
                    <h3 class="aba-conteudo-titulo-principal">Fazer 20 vendas usando o caminhão</h3>
                    <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
                    <div class="contador">
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="dias0"></p>
                            <p class="contador-digito-texto">dias</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="horas0"></p>
                            <p class="contador-digito-texto">horas</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="min0"></p>
                            <p class="contador-digito-texto">min</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="seg0"></p>
                            <p class="contador-digito-texto">seg</p>
                        </div>
                    </div>
                </div>
                <div class="aba-conteudo">
                    <h3 class="aba-conteudo-titulo-principal">Fazer 15 Golpes</h3>
                    <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
                    <div class="contador">
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="dias1"></p>
                            <p class="contador-digito-texto">dias</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="horas1"></p>
                            <p class="contador-digito-texto">horas</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="min1"></p>
                            <p class="contador-digito-texto">min</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="seg1"></p>
                            <p class="contador-digito-texto">seg</p>
                        </div>
                    </div>
                </div>
                <div class="aba-conteudo">
                    <h3 class="aba-conteudo-titulo-principal">Fazer 10 Golpes usando o carro forte</h3>
                    <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
                    <div class="contador">
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="dias2"></p>
                            <p class="contador-digito-texto">dias</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="horas2"></p>
                            <p class="contador-digito-texto">horas</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="min2"></p>
                            <p class="contador-digito-texto">min</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="seg2"></p>
                            <p class="contador-digito-texto">seg</p>
                        </div>
                    </div>
                </div>
                <div class="aba-conteudo">
                    <h3 class="aba-conteudo-titulo-principal">Criar 36 Pistas de Drift</h3>
                    <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
                    <div class="contador">
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="dias3"></p>
                            <p class="contador-digito-texto">dias</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="horas3"></p>
                            <p class="contador-digito-texto">horas</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="min3"></p>
                            <p class="contador-digito-texto">min</p>
                        </div>
                        <div class="contador-digito">
                            <p class="contador-digito-numero" id="seg3"></p>
                            <p class="contador-digito-texto">seg</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <script src="main.js"></script>
</body>


</html>





:root {
  --cor-de-fundo: #2dce04;
  --verde: #1c6805;
  --branco: #a10446;
  --botao-ativo: #3A375E;
  --botao-inativo: rgba(58, 55, 94, 0.5);
  --texto-fundo: rgba(58, 55, 94, 0.3);
}








body {
  background: #000000 url("https://tm.ibxk.com.br/2022/12/26/26122807014078.jpg") no-repeat center top fixed;
  background-size: cover;
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
  color: var(--verde);
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
  border-bottom: 4px solid var(--verde);
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
  color: var(--verde);
  text-transform: uppercase;
}








.contador{
  display:flex;
  justify-content: center;
  flex-wrap: wrap;
}
.contador-digito{
  padding: 0 16px;
  text-align: center;
  min-width: 100px;
}








.contador-digito-numero{
  font-size: 80px;
  margin: 0;








}








.contador-digito-texto{
  color: var(--verde);
  font-size: 20px;
  margin: 0;








}








@media screen and (min-width: 768px) {
  .botoes {
      display: flex;
  }








  .botao:first-child {
      border-radius: 40px 0 0 0;
  }








  .botao:last-child {
      border-radius: 0 40px 0 0;
  }
}






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








const contadores = document.querySelectorAll(".contador");
const tempoObjetivo1 = new Date("2024-10-05T00:00:00");
const tempoObjetivo2 = new Date("2024-12-05T00:00:00");
const tempoObjetivo3 = new Date("2024-12-30T00:00:00");
const tempoObjetivo4 = new Date("2024-12-01T00:00:00");








const tempos = [tempoObjetivo1,tempoObjetivo2,tempoObjetivo3,tempoObjetivo4];
















function calculaTempo(tempoObjetivo) {
  let tempoAtual = new Date();
  let tempoFinal = tempoObjetivo - tempoAtual;
  let segundos = Math.floor(tempoFinal / 1000);
  let minutos = Math.floor(segundos / 60);
  let horas = Math.floor(minutos / 60);
  let dias = Math.floor(horas / 24);








  segundos %= 60;
  minutos %= 60;
  horas %= 24;
  if (tempoFinal > 0){
      return [dias,horas,minutos,segundos];
  } else {
      return [0,0,0,0];
  }
}








function atualizaCronometro(){
  for (let i=0; i<contadores.length;i++){
      document.getElementById("dias"+i).textContent = calculaTempo(tempos[i])[0];
      document.getElementById("horas"+i).textContent = calculaTempo(tempos[i])[1];
      document.getElementById("min"+i).textContent = calculaTempo(tempos[i])[2];
      document.getElementById("seg"+i).textContent = calculaTempo(tempos[i])[3];
  }
}








function comecaCronometro(){
  atualizaCronometro();
  setInterval(atualizaCronometro,1000);
}








comecaCronometro();







