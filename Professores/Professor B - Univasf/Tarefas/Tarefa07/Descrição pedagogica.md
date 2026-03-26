# Título da Atividade

Condensação de Matriz Esparsa em Estrutura de Três Colunas

## Contexto Instrucional

Atividade prática de programação introdutória, adequada a contexto de laboratório ou ambiente de desenvolvimento, com realização preferencialmente individual. A tarefa mobiliza leitura, armazenamento, percorrimento e impressão de matrizes, com produção de código executável e saídas verificáveis.

## Objetivo da Atividade

Implementar um programa que represente, de forma mais compacta, os elementos não nulos de uma matriz esparsa. Espera-se que o estudante organize corretamente os dados da matriz original e produza uma estrutura condensada coerente com as posições dos valores encontrados.

## Descrição da Tarefa

O estudante deve desenvolver um programa que leia uma matriz de dimensão `M x N`, considerada esparsa, e gere uma matriz condensada com 3 colunas. Cada linha válida dessa matriz condensada deve registrar um elemento não nulo da matriz original, associando seu valor à linha e à coluna em que ele ocorre.

Além da construção da matriz condensada, o programa deve imprimir a matriz original e a estrutura condensada em formato matricial. O produto esperado é, portanto, um programa funcional que leia os dados, organize a representação condensada e apresente ambas as matrizes de forma legível.

## Condições de Execução

Considerar que a matriz fornecida como entrada já atende à caracterização de matriz esparsa descrita no enunciado, sem exigir etapa adicional de validação, a menos que isso seja solicitado pelo docente.

A matriz condensada deve ser declarada com número de linhas suficiente para armazenar, no pior caso, todos os elementos da matriz original, conforme orientação do enunciado.

Devem ser registrados na matriz condensada apenas os elementos não nulos da matriz original, preservando, para cada ocorrência, o valor e seus respectivos índices de linha e coluna.

Como o enunciado não explicita a convenção de indexação, o estudante deve adotar a convenção trabalhada na disciplina ou na linguagem utilizada e mantê-la de forma consistente em toda a solução.

A impressão das estruturas deve respeitar o formato matricial solicitado, com organização que permita verificar visualmente a correspondência entre a matriz original e os registros condensados.

## Evidências Esperadas

- Código-fonte que realize leitura, armazenamento, processamento e impressão das estruturas.
- Impressão da matriz original em formato matricial.
- Impressão da matriz condensada em formato matricial, contendo os registros dos elementos não nulos.
- Evidência de consistência entre cada valor não nulo e seus índices correspondentes.

## Critérios de Avaliação

- Correção da leitura e da impressão da matriz original.
- Correção da identificação dos elementos não nulos e do preenchimento da matriz condensada.
- Consistência entre valor armazenado e índices de linha e coluna registrados.
- Completude da solução, incluindo geração e exibição das duas matrizes solicitadas.
- Clareza e verificabilidade do artefato entregue, incluindo organização da saída.