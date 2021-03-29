# PROJETO 1 - Algoritmos de Busca 

O projeto consiste na resolução dos problemas das 8-Rainhas e do Quebra-Cabeças de 8 peças através da implementação de diversos algoritmos.

# PUZZLE-8
  
## Objetivo
O objetivo do jogo é atingir uma posição final a partir de um estado inicial
movimentando-se cada peça por meio do espaço vazio (branco) até chegar ao estado final.
## 
![alt text](https://i.postimg.cc/3Nbtg6H7/Capturar.png)
##

### Algoritmos de Busca
 Para a resolução desse problema utilize algoritmos de busca cega:
largura e profundidade e busca heurística: busca gulosa e A*.
Para a busca heurística utilize duas heurísticas: h1 e h2, ou seja, busca gulosa com h1, busca
gulosa com h2, busca A* com h1 e busca A* com h2.
* h1(n): número de peças fora do lugar
* h2(n): distância Manhattan (número de casas longe da posição final em cada direção)

### Resultados Obtidos
O programa deverá imprimir o tabuleiro inicial e final e a quantidade de
passos encontrados na resolução do problema, bem como qual foi a sequência de ações. Por exemplo:
“A resolução tem 19 passos: -> CIMA -> ESQUERDA -> BAIXO, etc.”
Compare o resultado obtido por cada um dos algoritmos de busca no que se refere a quantidade
de nós expandidos, tempo, etc.


### Algoritmos Implementados:
- Busca Gulosa (GBFS)
- BFS
- DFS
- A* com H1(n) Distância de Manhattan
- A* com H2(n) MisplacedTiles

##

# N-Queens
  
## Objetivo
O objetivo do problema é dispor as rainhas no tabuleiro de forma que nenhuma delas
seja atacada por outra. Para tanto, é necessário que duas rainhas quaisquer não estejam numa mesma
linha, coluna ou diagonal. 
## 
![alt text](https://solarianprogrammer.com/images/2017/11/20/queens_attack_patterns.png)
##

### Algoritmos de Busca</b>
Para a resolução desse problema utilize um algoritmo de busca
heurística (gulosa ou A*) e um algoritmo de busca local (ex: subida da encosta, tempera simulada,
feixe local, algoritmo genético).

### Resultados Obtidos
O programa deverá imprimir o tabuleiro com as rainhas disposta nele e
a quantidade de passos encontrados na resolução do problema.


### Algoritmos Implementados:
- Hill Climbing
- Busca Gulosa


