# Quadrado Mágico de Ordem Ímpar | JavaScript
<p align="center">
<img src="https://repository-images.githubusercontent.com/630443785/1c9926e4-cb29-4865-b129-b720ce951c14" alt="Quadrado Mágico de Ordem Ímpar | JavaScript"/>
<p/>

<h4 align="center">O algoritmo, abaixo declarado, dá uma solução válida para qualquer Quadrado Mágico de Ordem Ímpar.</h4>


Um Quadrado Mágico é uma Tabela ou Matriz Quadrada preenchida com valores inteiros de 1 até o número total de células.
De modo que a soma dos elementos em cada linha, em cada coluna e em cada diagonal é sempre igual a um mesmo valor.
Esse valor é chamado "Constante Mágica".
O algoritmo, abaixo declarado, dá uma solução válida para qualquer Quadrado Mágico de Ordem Ímpar.

## Algoritmo:

1º Passo: Faça n = 1.

2º Passo: Vá para a última coluna e insira o  valor n=1 na linha do meio.

3º Passo: Partindo da posição atual, mova uma coluna para a direita.
                Se não existir a coluna vá para a 1ª coluna, mantendo a linha atual.              

4º Passo: Partindo da posição atual , mova uma linha para baixo. 
                Se não existir a linha vá para a 1ª linha, mantendo a coluna atual.                

5° Passo: Faça n = n+1.

6º Passo: Se a célula atual estiver vazia, insira o valor de n na célula
                e vá para 8°Passo,  senão continue no próximo passo (7°Passo).                

7ºPasso: Vá para a célula não vazia que contêm o último valor  inserido.
               A partir desta posição mova uma coluna para a  esquerda.               
               Se a coluna não existir vá para a última coluna, mantendo a linha atual.               
               Insira n.                

8°Passo: Se o valor de n for igual ao total de células do quadrado pare e finalize,
               senão: Retorne ao 3°Passo.
              

## Constante Mágica para qualquer ordem (inclusive par): CM = n.(n² + 1)/2  

Exemplo: n=3 

CM = 3.(3² + 1)/2  

CM = 3.(9+1)/2

CM = 3.(10)/2 

CM = 30/2

CM = 15 (Verificado!)   

Confira manualmente se funciona para outras dimensões ímpares.
  
## Bons Estudos!  Marcelo Brito.

  Acesse : https://exatasoft.com/quadm.html e verifique online o algoritmo em javascript.
  
  WebSite: https://exatasoft.com
  
