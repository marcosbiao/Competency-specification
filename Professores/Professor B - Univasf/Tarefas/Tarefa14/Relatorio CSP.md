## Título da Atividade

Implementação de média móvel com vetor e subprogramas

## Contexto Instrucional

Atividade prática de programação introdutória, adequada a contexto de laboratório ou avaliação individual, com foco na construção de um programa executável. A produção esperada é um artefato verificável, composto por código-fonte e evidências de execução coerentes com o enunciado.

## Objetivo da Atividade

Desenvolver uma solução que processe uma sequência de entradas numéricas inteiras positivas, mantenha uma janela móvel de cinco observações e produza a média correspondente a cada atualização válida dessa janela. Espera-se, ainda, que a solução seja organizada de forma modular, com uso obrigatório de subprogramas para armazenamento dos dados e cálculo da média.

## Descrição da Tarefa

Implementar um programa que leia, em laço, valores inteiros positivos até que seja informado um valor negativo, utilizado exclusivamente como marcador de término. Os valores válidos devem compor um vetor com cinco observações correntes. Sempre que um novo valor for lido após o preenchimento dessa janela, o valor mais antigo deve ser descartado para dar lugar ao novo, preservando a lógica de média móvel. Para cada atualização válida da janela de cinco observações, o programa deve imprimir a média calculada. A solução deve incluir obrigatoriamente um subprograma para armazenar e atualizar os valores no vetor e outro subprograma para calcular a média móvel.

## Condições de Execução

1. Devem ser aceitos como dados de processamento apenas valores inteiros positivos.
2. O valor negativo deve encerrar a leitura e não pode ser armazenado nem considerado no cálculo da média.
3. A média móvel deve ser definida sobre exatamente cinco observações, conforme o enunciado.
4. Em razão dessa definição, a impressão da média deve ocorrer quando houver cinco valores válidos disponíveis na janela; a partir daí, cada nova entrada válida deve gerar uma nova média.
5. Como a média de inteiros pode resultar em valor não inteiro, a solução deve empregar representação numérica compatível com esse cálculo.
6. O programa deve utilizar, no mínimo, os dois subprogramas explicitamente exigidos no enunciado.

## Evidências Esperadas

1. Código-fonte funcional contendo o programa principal e os subprogramas obrigatórios.
2. Implementação verificável da atualização do vetor de cinco posições com descarte do valor mais antigo quando necessário.
3. Saídas produzidas pelo programa mostrando as médias móveis calculadas ao longo da execução.

## Critérios de Avaliação

1. Correção do laço de leitura e do tratamento do valor negativo como sentinela de término.
2. Manutenção correta da janela móvel de cinco valores, com atualização consistente do vetor.
3. Cálculo correto da média móvel e impressão coerente dos resultados a cada atualização válida.
4. Atendimento à exigência de modularização por meio dos subprogramas solicitados.
5. Clareza, organização e verificabilidade do artefato entregue.