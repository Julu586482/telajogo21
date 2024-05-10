# Resultado
### (algo próximo disto)

![alt text](image.png)

isto para primeira parte em seguida o resultado com reposicionamento dos itens.

com o reposicionamento e ajuste tamanho  deve ficar parecido como abaixo:

![alt text](image-1.png)

<hr>

Agora vamos focar no estudo de como foi escrito o nosso CSS. (vejamos abaixo):

``` css
.mesa{
    position: fixed;
    width:900px;
    height:600px;
    background-color: green;
      }
.robot{
   position: relative;
   top:5px;
   left:15px;
   width:160px;
   height:60px;
   background-color: black;  }      
.jogador{
    position: relative;
    top:390px;
    left:15px;
    width:160px;
    height:60px;
    background-color: black; }   
.baralho{
    position: relative;
    top:200px;
    left:315px;
    width:60px;
    height:80px;
    background-color:yellow;}   
```
Explicação do codigo HTML
```html
<!DOCTYPE html> - Mostra o tipo de documento usado, sendo esse o HTML.
<html lang="en"> - Mostra a linguagem utilizada no HTML.
<head>- Cabeça do sistema.
    <meta charset="UTF-8"> - Define o conjunto para ser utilizado na exibição do site.
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> - Define um espaçamento e a renderização que tera para ocupar a tela não importando qual despositivo.
    <title>Document</title> - O titulo que sera mostrado no site.
    <link rel="stylesheet" href="jogo21style.css"> - ligação o codigo CSS com o codigo do HTML.
</head> - fim da cabeça do sistema.
<body> - Corpo do sistema.
    <div class ="mesa"> - fazendo divisões.
        <div class="robot"> - divisão do robo.
        </div> - fechamento da divisão.
        <div class="player"> - divisão do jogador.
        </div> - fechamento da divisão.
        <div class="baralho"> - divisão do baralho.
        </div> - fechamento da divisão.
    </div> - fechamento da divisão mesa.
</body> - Fim do corpo do sistema.
</html> - final do sistema.
```
Explicação do codigo CSS
```css
.mesa{ - fazendo alteração na div.
    position: fixed; // posição fixa.
    width:900px; - colocando a Largura em pixels.
    height:600px; - colocando o Comprimento em pixels.
    background-color: green; - botando a cor.
      } - botando a cor.
.robot{ - fazendo alteração na div criada.
   position: relative; - posição relativa.
   top:5px; - distância do topo da tela.
   left:15px; - distância da para a esquerda da tela.
   width:160px; - colocando a Largura em pixels.
   height:60px; - colocando o Comprimento em pixels.
   background-color: black; - botando a cor.
 } - botando a cor.
.player{ - fazendo alteração na div.
    position: relative; - posição relativa.
    top:390px; - distância do topo da tela.
    left:15px; - distância da para a esquerda da tela.
    width:160px; - colocando a Largura em pixels.
    height:60px; - colocando o Comprimento em pixels.
    background-color: black; } - botando a cor.   
.baralho{ - fazendo alteração na div.
    position: relative; - posição relativa.
    top:200px; - distância do topo da tela.
    left:315px; - distância da para a esquerda da tela.
    width:60px; - colocando a Largura em pixels.
    height:80px; - colocando o Comprimento em pixels.
    background-color:yellow;} - botando a cor.     
```
