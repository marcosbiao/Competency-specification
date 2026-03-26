# Desafio - Encontrando a Cobra no Grid

Você recebeu um arranjo bidimensional representando um ambiente onde há uma cobra disposta em um conjunto de células conectadas. A cobra é representada pelos seguintes caracteres:
‘h’ para a cabeça da cobra;
‘<’ e ‘>’ para as partes do corpo na horizontal;
‘v’ e ‘^’ para as partes do corpo na vertical.
A matriz pode conter células vazias representadas por ‘ ‘(o caractere de espaço), que não fazem parte da cobra.
ATENÇÃO: Suponha que a cobra estará sempre conectada corretamente, sem ramificações,  múltiplas cabeças ou extremidades finais do corpo.

Requisitos
Desenvolva um algoritmo que percorra a matriz e retorne uma lista de coordenadas na forma “[coluna, linha]” que representam a posição da cobra, na ordem correta, iniciando pela cabeça e seguindo até a extremidade final do corpo.

Entrada
Uma matriz representando o grid.

Saída
Uma sequência de pares ordenados (coluna, linha) que representam a posição da cobra na matriz, na ordem em que ela aparece a partir da cabeça até a extremidade final do corpo.

Observações:
A cobra estará sempre conectada corretamente.
A matriz pode conter células vazias, mas a cobra nunca estará fragmentada.
O algoritmo deve identificar corretamente a trajetória da cobra e retornar sua posição na ordem correta.
O programa deve funcionar para tamanhos arbitrários MxN de arranjos bidimensionais.

## Exemplo I
Entrada: Um arranjo bidimensional 4x4 preenchido como:
```c
char a[4][4] = {{' ','V','<','<'},
                {'V','<',' ','^'},
                {'>','>','V','^'},
                {' ',' ','h','^'}};
```
Saída: Uma lista de pares ordenados, na sequência, da cabeça até o final da cauda:
[3,2]: h
[2,2]: V
[2,1]: >
[2,0]: >
[1,0]: V
[1,1]: <
[0,1]: V
[0,2]: <
[0,3]: <
[1,3]: ^
[2,3]: ^
[3,3]: ^

## Exemplo II
Entrada: Um arranjo bidimensional 4x4 preenchido como:
```c
char a[4][4] = {{' ',' ',' ',' '},
                {' ',' ','h','<'},
                {'>','>','>','^'},
                {'^','<',' ',' '}};
```
Saída: Uma lista de pares ordenados, na sequência, da cabeça até o final da cauda:
[1,2]: h
[1,3]: <
[2,3]: ^
[2,2]: >
[2,1]: >
[2,0]: >
[3,0]: ^
[3,1]: <