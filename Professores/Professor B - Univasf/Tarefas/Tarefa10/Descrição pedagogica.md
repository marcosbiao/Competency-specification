## Título da Atividade

Implementação e consulta de arranjo multidimensional de automóveis

## Contexto Instrucional

Atividade de programação introdutória, preferencialmente individual, realizada em ambiente de laboratório ou em contexto avaliativo prático. A evidência principal esperada é um programa funcional que realize leitura de dados, armazenamento estruturado e consulta de informações com base em múltiplos índices.

## Objetivo da Atividade

Desenvolver uma solução que represente, em memória, um conjunto estruturado de dados de automóveis por meio de um arranjo multidimensional. Exercitar a leitura, o preenchimento completo da estrutura, a recuperação de valores por chave composta e o controle de encerramento de um ciclo de consultas.

## Descrição da Tarefa

O estudante deve implementar um programa que inicialmente preencha, por entradas de teclado, toda a estrutura de dados correspondente aos automóveis disponíveis. Em seguida, deve permitir a realização de consultas sucessivas, nas quais são informados os dados de identificação de um automóvel para que o programa localize e apresente o respectivo preço.

A solução deve contemplar as dimensões informadas no enunciado, isto é, código de identificação, modelo, cor, ano de fabricação e combustível, tratando o preço como valor associado à combinação desses índices. Além disso, o programa deve incluir um mecanismo explícito para encerrar o atendimento das consultas.

## Condições de Execução

- O preenchimento da estrutura deve abranger todas as combinações previstas pelas dimensões indicadas no enunciado.

- As consultas devem utilizar, de forma consistente, todos os dados necessários para identificar univocamente um automóvel na estrutura.

- Como o enunciado define categorias por enumeração, a solução deve adotar uma representação de entrada compatível com a linguagem utilizada, desde que preserve correspondência inequívoca com os valores previstos.

- Como o preço representa valor monetário, deve ser utilizado um tipo numérico coerente para sua leitura, armazenamento e exibição.

- O encerramento das consultas deve ser controlado por uma condição definida no próprio programa e verificável durante a execução.

## Evidências Esperadas

- Código fonte que implemente o preenchimento completo da estrutura multidimensional.
- Rotina de consulta que leia os identificadores do automóvel e informe o preço correspondente.
- Mecanismo funcional de controle de término das consultas.
- Saídas produzidas pelo programa que permitam verificar o comportamento esperado em consultas válidas.

## Critérios de Avaliação

- Correção no armazenamento e na recuperação do preço associado a cada combinação de identificadores.
- Completude da implementação, incluindo preenchimento inicial, consultas sucessivas e encerramento controlado.
- Consistência no tratamento dos índices categóricos e do código de identificação.
- Clareza e verificabilidade do artefato produzido, com entradas e saídas compatíveis com o enunciado.
