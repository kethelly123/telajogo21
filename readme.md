# Resultado
### (algo próximo disto)

![alt text](image.png)

isto para primeira parte em seguida o resultado com reposicionamento dos itens.

com o reposicionamento e ajuste tamanho  deve ficar parecido como abaixo:

![alt text](image-1.png)

<hr>

Agora vamos focar no estudo de como foi escrito o nosso CSS. (vejamos abaixo):

``` css
.mesa{ \\ local onde será jogado o jogon21
    position: fixed;\\ posição da mesa
    width:900px; \\ largura da mesa 
    height:600px; \\ comprimento da mesa
    background-color: green; \\ cor da mesa 
      }
.robot{ \\ maquina 
   position: relative; \\ posição das cartas do robot
   top:5px; \\ distância entra a altura e o meio 
   left:15px; \\ lado  da proporção do conjunto das cartas que ficara posicionado na tela 
   width:160px; \\ largura do conjuto de cartas 
   height:60px; \\ altura do conjunto de cartas 
   background-color: black;  }      cor do conjunto de cartas 
.jogador{ \\ posição do jogador 
    position: relative; \\ posição das cartas do jogador 
    top:390px;\\ distância entre a altura e o meio
    left:15px; \\ lado da proporção do conjunto das cartas que ficaria posicionado na tela 
    width:160px; \\ largura do conjuntos de cartas 
    height:60px; \\ altura do conjuto de cartas do jogador 
    background-color: black; } \\ cor das cartas do jogador   
.baralho{ \\ cartas do baralo
    position: relative; \\ posição do baralho 
    top:200px; \\ distância entre o baralho e os jogadores 
    left:315px; \\ lado onde esta o baralho 
    width:60px; \\ largura das cartas do baralho 
    height:80px; \\ altura dos baralhos 
    background-color:yellow;}  \\ cor do baralho  
```
