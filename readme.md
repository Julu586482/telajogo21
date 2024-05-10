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
Explicar o codigo no HTML
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
Explicar o codigo no CSS
