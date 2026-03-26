## Título da Atividade

Implementação de subprograma para soma dos três maiores valores

## Contexto Instrucional

Atividade típica de disciplina introdutória de programação, realizada individualmente em ambiente de laboratório ou em contexto de avaliação prática escrita/computacional. A evidência principal esperada é a implementação de um programa com subprograma, acompanhada de saídas produzidas para diferentes conjuntos de entrada.

## Objetivo da Atividade

Desenvolver uma solução modular para processar conjuntos de quatro números inteiros, delegando a um subprograma o cálculo da soma dos três maiores valores de cada conjunto. A atividade também visa exercitar a repetição controlada pelo usuário para processar múltiplos casos sucessivos.

## Descrição da Tarefa

O estudante deve construir um subprograma que receba quatro números inteiros como parâmetros e devolva ao módulo chamador a soma dos três maiores valores entre eles. Em seguida, deve desenvolver um programa principal que leia sucessivos conjuntos de quatro valores, conforme a decisão do usuário de continuar ou encerrar a execução, chame o subprograma para cada conjunto informado e apresente, a cada iteração, a soma calculada.

O produto esperado é um programa funcional, com clara separação entre o processamento realizado pelo subprograma e o controle de leitura, repetição e exibição realizado pelo programa principal.

## Condições de Execução

1. O subprograma deve receber exatamente quatro valores inteiros por chamada e devolver um único resultado numérico correspondente à soma requerida.
2. O programa principal deve permitir o processamento de múltiplos conjuntos de entrada, mantendo a repetição enquanto o usuário desejar.
3. A lógica adotada deve tratar corretamente quaisquer combinações de valores inteiros, inclusive quando houver números iguais entre si ou valores negativos.
4. Como o enunciado não especifica a forma de sinalização de continuidade, admite-se qualquer mecanismo explícito e consistente para o usuário indicar se deseja informar um novo conjunto de quatro valores.
5. A cada conjunto processado, o programa deve apresentar apenas a soma produzida para aquele conjunto, de forma clara e verificável.

## Evidências Esperadas

1. Código-fonte do programa principal e do subprograma solicitado.
2. Implementação efetiva da chamada do subprograma para cada conjunto de quatro valores lidos.
3. Registro de execução que demonstre o processamento de mais de um conjunto de entrada.
4. Saídas correspondentes às somas produzidas em cada iteração.
5. Breve justificativa textual indicando a função do subprograma e a forma de controle da repetição no programa principal.

## Critérios de Avaliação

1. Correção do resultado devolvido pelo subprograma para cada conjunto de quatro inteiros.
2. Adequação da decomposição da solução entre programa principal e subprograma.
3. Completude do processamento iterativo, com leitura sucessiva de conjuntos enquanto houver decisão de continuidade.
4. Consistência no tratamento de diferentes casos de entrada, incluindo repetições de valores e inteiros negativos.
5. Clareza e verificabilidade do artefato entregue, incluindo organização do código, execução observável e justificativa coerente.
