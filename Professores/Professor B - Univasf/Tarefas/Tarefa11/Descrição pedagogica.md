## Título da Atividade
Cálculo iterativo do cosseno por série em subprograma

## Contexto Instrucional
Atividade prática de programação em disciplina introdutória, voltada à implementação individual de um programa com saída numérica tabulada. A tarefa mobiliza organização de cálculo iterativo, uso de repetição e decomposição da solução por meio de subprograma.

## Objetivo da Atividade
Desenvolver um programa que produza valores do cosseno para uma faixa de entradas reais previamente definida, utilizando uma estratégia matemática especificada no enunciado e organizando o cálculo em módulo próprio. Espera-se que o estudante demonstre domínio da estrutura geral do programa e da separação entre controle da varredura dos valores de entrada e cálculo numérico da função.

## Descrição da Tarefa
Implementar um programa que percorra valores de x no intervalo de 0 a 6,3, inclusive, com incremento de 0,1, imprimindo para cada valor o respectivo resultado do cosseno. O cálculo do cosseno deve ser realizado em um subprograma específico, com base na série indicada no enunciado e limitado às 30 primeiras parcelas. O produto esperado é um programa funcional que apresente, de forma organizada, os pares compostos pelo valor de entrada e pelo valor calculado.

## Condições de Execução
Utilizar valores numéricos compatíveis com entradas e resultados reais. O cálculo do cosseno deve estar encapsulado em um subprograma, sem substituição por funções prontas da linguagem para essa finalidade. A implementação deve respeitar a quantidade fixa de 30 parcelas da série e a alternância de sinais prevista em sua formulação. A varredura dos valores de x deve garantir a inclusão do limite superior informado no enunciado, mesmo diante de possíveis efeitos de precisão numérica em incrementos sucessivos.

## Evidências Esperadas
* Código-fonte do programa completo.
* Subprograma responsável exclusivamente pelo cálculo do cosseno pela série especificada.
* Saída do programa contendo, para cada valor de x no intervalo solicitado, o correspondente valor calculado do cosseno.
* Organização legível da saída, permitindo verificar a associação entre cada entrada e seu resultado.

## Critérios de Avaliação
* Correção da varredura do intervalo solicitado, com início, incremento e término compatíveis com o enunciado.
* Implementação adequada do cálculo em subprograma, com uso da série especificada e das 30 parcelas requeridas.
* Consistência numérica do resultado produzido para cada valor de entrada.
* Clareza e verificabilidade da saída apresentada.
* Organização coerente do programa, com separação adequada entre controle do fluxo principal e rotina de cálculo.