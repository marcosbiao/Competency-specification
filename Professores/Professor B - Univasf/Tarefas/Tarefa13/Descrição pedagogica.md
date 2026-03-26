## Título da Atividade

Cálculo da Distância entre Dois Pontos com Registro e Subprograma

## Contexto Instrucional

Atividade de implementação em disciplina introdutória de programação, realizada individualmente em ambiente de prática de programação ou avaliação escrita com desenvolvimento de código. A tarefa mobiliza modelagem de dados com registro, organização modular por subprogramas e produção de evidência verificável por meio do código e da saída gerada na execução.

## Objetivo da Atividade

Modelar pontos do plano cartesiano por meio de um tipo registro e organizar a solução em programa principal e subprograma, de modo que o estudante represente adequadamente os dados, realize o processamento solicitado e apresente o resultado de forma coerente com o enunciado.

## Descrição da Tarefa

O estudante deve definir um tipo registro para representar um ponto cartesiano com dois campos reais, `x` e `y`. Em seguida, deve construir um programa no qual o programa principal leia as coordenadas de dois pontos, encaminhe esses dados a um subprograma por parâmetros do tipo `struct Ponto` e obtenha o cálculo da distância euclidiana entre os pontos. Ao final, o programa deve informar o resultado da execução e apresentar uma solução modularmente organizada.

## Condições de Execução

1. O tipo estruturado deve representar explicitamente um ponto por meio de dois campos nomeados `x` e `y`, ambos reais.

2. As coordenadas dos dois pontos devem ser lidas no programa principal, sem substituir essa etapa por valores fixos no código.

3. O subprograma deve receber os dois pontos por parâmetros do tipo `struct Ponto`, conforme exigido no enunciado.

4. O processamento deve corresponder ao cálculo da distância euclidiana entre dois pontos no plano cartesiano, considerando corretamente valores reais.


## Evidências Esperadas

1. Código-fonte contendo a definição do tipo registro `Ponto`.

2. Programa principal responsável pela leitura das coordenadas dos dois pontos.

3. Subprograma que receba dois parâmetros do tipo `struct Ponto` e realize o processamento solicitado.

4. Saída do programa informando a distância calculada entre os dois pontos.


## Critérios de Avaliação

1. Correção da modelagem do dado, com uso adequado do tipo registro para representar pontos por coordenadas reais.

2. Atendimento ao enunciado quanto à leitura das coordenadas no programa principal e à passagem dos dois pontos ao subprograma por parâmetros estruturados.

3. Correção do cálculo produzido, compatível com a distância euclidiana entre dois pontos.

4. Coerência modular da solução, com definição clara do papel do programa principal e do subprograma.

5. Clareza e verificabilidade do artefato entregue, incluindo código legível, saída observável e justificativa breve consistente.
