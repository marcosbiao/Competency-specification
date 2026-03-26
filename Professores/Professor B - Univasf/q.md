# Atividade Avaliativa I

1. (vale 1.0) Faça um programa para, dados 4 valores armazenados nas variáveis x, y, w, e z, calcular e imprimir as médias aritmética, geométrica, harmônica e ponderada (com peso 2 para a variável x, 4 para a variável y, 6 para a variável w e 8 para a variável z).

2. (vale 1.5) Um hotel com 75 apartamentos deseja fazer uma promoção especial de final de semana, concedendo um desconto de 25% na diária. Com isso, espera aumentar sua taxa de ocupação de 50% para 80%. Dado o valor normal da diária, calcule e imprima:
- o valor da diária promocional;
- o valor arrecadado com 80% de ocupação e diária promocional;
- o valor arrecadado com 50% de ocupação e diária normal;
- a diferença entre os  valores calculados em b e c.

3. (vale 1.5) Faça um programa que calcula a quantidade de latas de tinta necessárias para pintar um aposento. O programa deve receber como entradas as dimensões desse aposento (largura e comprimento). Considere que:
- o aposento tem paredes perpendiculares;
- o pé-direito do aposento mede 2,80m;
- deverão ser pintadas apenas as paredes;
- o aposento tem apenas uma porta (cuja área deve ser descontada), medindo 0,80m de largura por 2,10m de altura;
- cada lata de tinta tem 5,00 litros;
- cada litro de tinta pinta 3,00m².

4. (vale 1.0) Faça um programa para imprimir de forma ordenada (do menor para o maior) 3 números inteiros quaisquer lidos do teclado. A ordenação deve ser implementada de 2 formas diferentes!

5. (vale 1.5) Vai ser realizada uma pesquisa em Porto Alegre  com um número desconhecido de pessoas. De cada entrevistado foram colhidos os seguintes dados:
- qual seu clube de futebol de preferência (1-Grêmio, 2-Internacional, 3-Outros);
- qual o seu salário;
- qual a sua cidade natal (0-Porto Alegre, 1-Outras).
Escreva um programa que informe:
- o número de torcedores por clube;
- média salarial dos torcedores de Grêmio e do Internacional;
- número de pessoas nascidas em Porto Alegre que não torcem por qualquer dos dois principais clubes;
- número de pessoas entrevistadas.

6. (vale 1.0) Faça um programa para:
Deslocar todos os elementos de um arranjo unidimensional de N posições para o elemento seguinte, perdendo o valor contido no último elemento e atribuindo zero ao primeiro elemento do arranjo.
Na sequência, deslocar todos os elementos do arranjo da letra a para o elemento anterior, perdendo o valor contido no primeiro elemento e atribuindo zero ao último elemento do arranjo. 

7. (vale 1.5) Uma matriz esparsa (arranjo bidimensional espaço) é uma matriz que tem aproximadamente dois terços de seus elementos iguais a zero. Escreva um programa que leia uma matriz esparsa de M linhas e N colunas e que forme uma matriz condensada, de apenas 3 colunas, com os elementos não nulos da matriz original, de forma que:
- a primeira coluna contenha o valor não nulo da matriz esparsa;
- a segunda coluna contenha o índice da linha da matriz esparsa onde foi encontrado esse valor;
- a terceira coluna contenha o índice da coluna da matriz esparsa onde foi encontrado esse valor.
ATENÇÃO: Imprima a matriz original e a matriz condensada em formato matricial.
obs.: Para facilitar, a matriz condensada deve ser declarada com um número de linhas igual ao número de elementos da matriz esparsa para que não haja risco de faltar espaço de armazenamento durante o processamento.

8. (vale 1,0) Na Teoria de Sistemas, define-se como elemento minimax de uma matriz o menor elemento da linha em que se encontra o maior elemento da matriz. Escreva um programa que preencha uma matriz M(5x5) por leitura e determine o seu elemento minimax.

# Desafio I - Encontrando a Cobra no Grid

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

# Atividade Avaliativa II

1. (vale 3,0) Uma revenda de automóveis armazena os dados relativos aos carros disponíveis para venda em um arranjo multidimensional. As dimensões desse arranjo e os índices utilizados em cada dimensão são:
- Código de identificação do carro, com índice inteiro, de 1 a 50.
- modelo do carro, com índice tipo enumeração (modA, modB, modC, modD, modE).
- Cor, índice tipo enumeração (branca, prata, vermelho, azul, verde, preto).
- Ano de fabricação, índice tipo enumeração (2009, 2010, 2011).
- Combustível, índice tipo enumeração (gasolina, álcool, flex).
O conteúdo da matriz é o preço de cada um dos automóveis identificado pelos itens que constituem as dimensões. Escreva um programa que inicie preenchendo, a partir de leituras do teclado, todos os dados dessa matriz. Em seguida, o programa deve responder a uma série de consultas, lendo os dados que identificam cada automóvel e informando o seu preço. Crie um controle para identificar quando o programa deve terminar de responder a consultas.

2. (vale 1,5) Faça um programa para calcular o cosseno de x, para x variando de 0 até 6,3 (inclusive), de 0,1 em 0,1. O programa deverá imprimir x e o valor correspondente do cosseno. O cálculo do cosseno deverá ser implementado através de um subprograma que utilize a série:
``` cos(x) = 1 - x²/2! + x⁴/4! - x⁶/6! + x⁸/8! + ... ```
Considerar as primeiras 30 parcelas da série para a obtenção do cosseno de x.

3. (vale 1,5) Construa um subprograma que, recebendo como parâmetros quatro números inteiros, devolva ao módulo que o chamou a soma dos três maiores números dentre os quatro recebidos. Faça um programa que leia tantos conjuntos de quatro valores quantos o usuário deseje e que chame o subprograma para cada conjunto de valores, apresentando a cada vez a soma produzida.

4. (vale 2,0) Defina um tipo registro com dois campos , x e y (reais). Os campos representam as coordenadas de um ponto no sistema cartesiano. Escreva um subprograma que, dados dois pontos, calcule e imprima a distância euclidiana entre eles. As coordenadas dos pontos devem ser lidas a partir do programa principal e passadas ao subprograma por meio de parâmetros do tipo struct Ponto. O resultado da sua execução deve ser informado pelo programa principal.

5. (vale 2,0) Faça um programa que calcule uma média móvel.  O programa deve executar um laço de leitura de valores inteiros positivos; a introdução de um valor negativo servirá como indicador de término do programa. Para cada valor fornecido deverá ser impressa a média calculada. A média móvel é efetuada sobre um número predeterminado de valores. Quando se introduz um novo valor dado, descarta-se o valor mais antigo, abrindo lugar para o novo valor. Considere para a solução deste problema cinco observações (valores) e assuma que pelo menos cinco pontos válidos serão fornecidos.
Use obrigatoriamente subprogramas para:
- armazenar os novos valores no vetor de valores;
- calcular a média móvel.

# Desafio II - Encontrando a Cobra no Grid (Recursivo)

Você recebeu um arranjo bidimensional representando um ambiente onde há uma cobra disposta em um conjunto de células conectadas. A cobra é representada pelos seguintes caracteres:
‘h’ para a cabeça da cobra;
‘<’ e ‘>’ para as partes do corpo na horizontal;
‘v’ e ‘^’ para as partes do corpo na vertical.
A matriz pode conter células vazias representadas por ‘ ‘(o caractere de espaço), que não fazem parte da cobra.
ATENÇÃO: Suponha que a cobra estará sempre conectada corretamente, sem ramificações,  múltiplas cabeças ou extremidades finais do corpo.

Requisitos
Desenvolva um algoritmo **RECURSIVO** que percorra a matriz e retorne uma lista de coordenadas na forma “[coluna, linha]” que representam a posição da cobra, na ordem correta, iniciando pela cabeça e seguindo até a extremidade final do corpo.

Entrada
Uma matriz representando o grid.

Saída
Uma sequência de pares ordenados (coluna, linha) que representam a posição da cobra na matriz, na ordem em que ela aparece a partir da cabeça até a extremidade final do corpo.

Observações:
A cobra estará sempre conectada corretamente.
A matriz pode conter células vazias, mas a cobra nunca estará fragmentada.
O algoritmo deve identificar corretamente a trajetória da cobra e retornar sua posição na ordem correta.
O programa deve funcionar para tamanhos arbitrários MxN de arranjos bidimensionais.

# Projeto Prático: Sistema de Cadastro de Alunos

A manipulação de arquivos e diretórios é um dos pilares da programação de sistemas. Em linguagem C, essa manipulação fornece controle direto sobre o armazenamento persistente, sendo amplamente utilizada em sistemas operacionais, bancos de dados e softwares em geral.

## Este trabalho aborda:
- Arquivos texto e binários
- Operações de leitura/escrita estruturada
- Manipulação de diretórios
- Uso de metadados de arquivos
- Implementação de um sistema prático com menu interativo

## Objetivo
Criar um sistema que:
- Cadastra alunos em arquivo binário
- Lista alunos
- Busca por ID
- Mostra arquivos do diretório

## Este projeto deve utilizar:
- Arquivos binários (fwrite, fread)
- Estruturas (struct)
- Modularização com funções
- Acesso sequencial em arquivos
- Interface via menu

## Este projeto pode utilizar:
- Manipulação de diretórios (dirent.h)