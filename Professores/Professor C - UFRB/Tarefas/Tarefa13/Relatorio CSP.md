# RELATÓRIO CSP: AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de Autoria de Competências do Competency Specification Process, com foco na explicitação dos conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa introdutória de programação. A tarefa solicita o cadastro de cinco pessoas, com leitura de nome, idade e altura, seguido da emissão de um relatório final legível. As evidências observáveis concentram-se no código produzido, na organização do fluxo de entrada e saída, no tratamento de repetições em quantidade fixa e na consistência do relatório final.

A tarefa sustenta o modelo K-S-D porque permite distinguir, com rastreabilidade, os conhecimentos computacionais mobilizados, as habilidades observáveis no artefato produzido e as disposições necessárias para execução consistente. O relatório prioriza reuso entre tarefas da disciplina, evita hipergranularidade e restringe os conhecimentos ao catálogo fixo da disciplina.

## 1. Análise da Entidade Instrucional

### Título

Cadastro e emissão de relatório de pessoas

### Descrição

A tarefa requer a construção de um programa introdutório que realize cinco cadastros sucessivos e, ao final, apresente um relatório com os dados coletados. Do ponto de vista computacional, a atividade evidencia a necessidade de organizar o fluxo de entrada, armazenar múltiplos valores relacionados a casos sucessivos e produzir uma saída consolidada e verificável.

### Processo de Desenvolvimento da Solução

1. Identificar os dados solicitados no enunciado e o número fixo de cadastros.
2. Definir a organização da solução para leitura repetida dos dados.
3. Representar os dados em variáveis e coleções compatíveis com o problema e com o repertório da disciplina.
4. Executar o cadastro sucessivo das cinco ocorrências previstas.
5. Preservar a correspondência entre os dados referentes a cada posição cadastrada.
6. Emitir um relatório final com os dados organizados de forma legível e verificável.

### Resultados Esperados

1. Código fonte contendo leitura, armazenamento e apresentação dos dados.
2. Execução com cinco cadastros completos.
3. Relatório final organizado, com correspondência consistente entre os dados cadastrados.
4. Justificativa breve sobre a organização computacional adotada.

### Contexto de Aquisição

- **Curso:** graduação inicial em Computação
- **Organização:** atividade individual
- **Ambiente:** laboratório de programação ou avaliação prática introdutória
- **Avaliação:** análise do código, do comportamento final do programa e da justificativa breve apresentada

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em etapa inicial de formação em programação, com contato introdutório com algoritmos, variáveis, entrada e saída, estruturas de repetição e vetores. Esses estudantes ainda consolidam a passagem do enunciado textual para uma solução executável e precisam de tarefas que tornem visível a organização do fluxo do programa e a consistência dos dados produzidos.

### Nível de Proficiência

| Dimensão | N1 - Inicial | N2 - Básico | N3 - Proficiente | N4 - Avançado |
|---|---|---|---|---|
| Organização do fluxo do programa | estrutura parcial ou inconsistente de leitura e saída | organiza o fluxo principal, com fragilidades pontuais | organiza corretamente leitura, armazenamento e exibição | organiza o fluxo com clareza, estabilidade e boa verificabilidade |
| Representação dos dados | usa variáveis ou coleções de modo inadequado | representa parte dos dados de forma funcional | representa os dados de forma coerente com a tarefa | representa os dados com precisão e boa organização interna |
| Repetição para múltiplos casos | não controla adequadamente a quantidade de cadastros | realiza repetição com pequenas inconsistências | controla corretamente a repetição em quantidade fixa | controla a repetição com clareza e integração consistente ao restante da solução |
| Consistência do relatório final | saída incompleta ou com associações incorretas | saída compreensível, porém com fragilidades | saída completa e coerente com os dados cadastrados | saída completa, organizada e facilmente verificável |

## 2. Seleção e Enumeração de Conhecimentos

### K02 - Algoritmos e formas de representação

1. Compreensão de algoritmo como sequência ordenada e finita de passos.
2. Organização da solução em uma forma representável e executável.
3. Relação entre descrição do problema e estrutura geral da solução.

Justificativa de mobilização na tarefa: a tarefa exige organizar uma solução algorítmica para cadastro repetido e geração de relatório, ainda que o foco principal não esteja na notação do algoritmo.

### K03 - Estrutura sequencial, entrada, processamento e saída

1. Organização do programa segundo uma sequência de leitura, processamento e apresentação de resultados.
2. Encadeamento correto entre entrada de dados, armazenamento e emissão de saída.
3. Produção de resultados observáveis ao final da execução.

Justificativa de mobilização na tarefa: o artefato esperado é um programa com fluxo básico de entrada, processamento e saída claramente verificável.

### K04 - Variáveis, constantes, tipos de dados e atribuição

1. Uso de variáveis para representar dados da tarefa.
2. Atualização e manutenção de valores ao longo da execução.
3. Compatibilidade elementar entre o tipo do dado e seu uso no programa.

Justificativa de mobilização na tarefa: o programa depende da representação de idade e altura em variáveis compatíveis, além da atualização organizada dos valores durante o cadastro.

### K07 - Estruturas de repetição

1. Execução iterativa de blocos de instruções em quantidade definida.
2. Controle de inicialização, atualização e parada do laço.
3. Repetição coerente de leituras e processamentos sucessivos.

Justificativa de mobilização na tarefa: o enunciado exige exatamente cinco cadastros, o que torna a repetição por contagem um conhecimento central.

### K08 - Vetores

1. Representação de coleções indexadas de valores.
2. Armazenamento de múltiplos elementos em posições associadas.
3. Percorrimento sequencial para preenchimento e exibição dos dados.

Justificativa de mobilização na tarefa: a tarefa demanda armazenar e recuperar múltiplas ocorrências de dados, o que mobiliza diretamente a ideia de coleções indexadas.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Estruturar programas introdutórios segundo um fluxo verificável de leitura, armazenamento e apresentação de dados.

**K associados:** (K02, K03)

### LO2

Representar dados elementares em variáveis e coleções compatíveis com a solução computacional adotada.

**K associados:** (K04, K08)

### LO3

Empregar repetição por contagem para executar o cadastro sucessivo de uma quantidade fixa de casos.

**K associados:** (K07, K03)

### LO4

Organizar coleções indexadas de modo a preservar a correspondência entre dados relacionados a uma mesma ocorrência cadastrada.

**K associados:** (K08, K07, K04)

### LO5

Produzir uma saída consolidada e verificável a partir dos dados coletados durante a execução.

**K associados:** (K03, K07, K08)

## 4. Definição de Competências

### 4.1 Competência Geral

Implementar soluções introdutórias de programação que articulem fluxo sequencial, repetição controlada, representação de dados e emissão de saídas verificáveis em tarefas de cadastro e relatório.

**Competência alinhada à BNCC:** não se aplica diretamente, por tratar-se de contexto de ensino superior e de catálogo específico da disciplina.

### 4.2 Especificações de Competências

## CT13.1

**Título da Competência**  
Estruturar programas introdutórios de cadastro com fluxo verificável de entrada e saída

**Descrição Textual**  
Capacidade de organizar soluções introdutórias que recebam dados, mantenham um encadeamento sequencial consistente e apresentem resultados de forma verificável ao final da execução.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO5)
- K mobilizados (Núcleo): (K03, K04)

**Especificação de Conhecimentos**

1. K03 - Estrutura sequencial, entrada, processamento e saída  
Justificativa de evidência: o programa evidencia diretamente a organização entre leitura dos dados e emissão do relatório final.

2. K04 - Variáveis, constantes, tipos de dados e atribuição  
Justificativa de evidência: a tarefa torna observável o uso de variáveis para manter e atualizar os dados cadastrados.


**Alinhamento com a Taxonomia de Bloom**

Predomina o nível **Aplicar**, pois a competência requer utilizar de forma operacional variáveis e fluxo sequencial em uma solução executável.

**Pareamento Conhecimento-Habilidade**

K03 / Aplicar → estruturar a sequência de leitura, armazenamento e saída de modo funcional e verificável.  
Verbos de Bloom: executar, programar, usar

K04 / Aplicar → utilizar variáveis compatíveis com os dados da tarefa e manter atribuições coerentes durante a execução.  
Verbos de Bloom: implementar, manipular, operar


**Especificação de Disposições**  
1. rigor na organização do fluxo do programa  
2. atenção à consistência dos dados manipulados  
3. clareza na apresentação da saída


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT13.1 | Estruturar programas introdutórios de cadastro com fluxo verificável de entrada e saída | rigor na organização do fluxo do programa; atenção à consistência dos dados manipulados; clareza na apresentação da saída | K03 | estruturar a sequência de leitura, armazenamento e saída de modo funcional e verificável |
| CT13.1 | Estruturar programas introdutórios de cadastro com fluxo verificável de entrada e saída | rigor na organização do fluxo do programa; atenção à consistência dos dados manipulados; clareza na apresentação da saída | K04 | utilizar variáveis compatíveis com os dados da tarefa e manter atribuições coerentes durante a execução |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa exige que o estudante construa um programa funcional e verificável. O fluxo de entrada e saída e o uso coerente de variáveis aparecem diretamente no artefato produzido e no relatório emitido.

## CT13.2

**Título da Competência**  
Controlar processamento repetitivo de quantidade fixa e organizar coleções indexadas

**Descrição Textual**  
Capacidade de implementar soluções que executem operações repetidas por contagem e armazenem múltiplas ocorrências em coleções indexadas, preservando a posição correspondente de cada caso tratado.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO3, LO4)
- K mobilizados (Núcleo): (K07, K08)

**Especificação de Conhecimentos**

K Núcleo

1. K07 - Estruturas de repetição  
Justificativa de evidência: a solução precisa repetir o procedimento de cadastro exatamente cinco vezes, com controle explícito do laço.

2. K08 - Vetores  
Justificativa de evidência: a tarefa demanda armazenar e recuperar múltiplas ocorrências, o que torna observável o uso de coleções indexadas.

**Alinhamento com a Taxonomia de Bloom**

Predomina o nível **Aplicar**, pois a competência requer implementar laços e coleções em uma situação de uso direta e observável.

**Pareamento Conhecimento-Habilidade**

K07 / Aplicar → controlar a repetição de cadastros em quantidade fixa com início, atualização e término coerentes.  
Verbos de Bloom: executar, iterar, usar

K08 / Aplicar → armazenar múltiplas ocorrências em posições indexadas e recuperar os dados de forma consistente.  
Verbos de Bloom: implementar, manipular, armazenar

**Especificação de Disposições**  
1. precisão no controle da repetição  
2. cuidado com a correspondência posicional dos dados  
3. disciplina na atualização dos valores

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT13.2 | Controlar processamento repetitivo de quantidade fixa e organizar coleções indexadas | precisão no controle da repetição; cuidado com a correspondência posicional dos dados; disciplina na atualização dos valores | K07 | controlar a repetição de cadastros em quantidade fixa com início, atualização e término coerentes |
| CT13.2 | Controlar processamento repetitivo de quantidade fixa e organizar coleções indexadas | precisão no controle da repetição; cuidado com a correspondência posicional dos dados; disciplina na atualização dos valores | K08 | armazenar múltiplas ocorrências em posições indexadas e recuperar os dados de forma consistente |
| CT13.2 | Controlar processamento repetitivo de quantidade fixa e organizar coleções indexadas | precisão no controle da repetição; cuidado com a correspondência posicional dos dados; disciplina na atualização dos valores | K03 | integrar as ações de leitura e exibição ao fluxo sequencial interno da repetição |
| CT13.2 | Controlar processamento repetitivo de quantidade fixa e organizar coleções indexadas | precisão no controle da repetição; cuidado com a correspondência posicional dos dados; disciplina na atualização dos valores | K04 | atualizar contadores, índices e valores armazenados sem perder consistência de atribuição |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a exigência de cinco cadastros torna a repetição por contagem diretamente necessária. Além disso, o relatório final depende de armazenamento recuperável, o que ativa de modo central a organização por coleções indexadas.

