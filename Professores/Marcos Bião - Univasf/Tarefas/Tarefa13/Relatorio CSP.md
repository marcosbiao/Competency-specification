# RELATÓRIO CSP COMPLETO  
## Fase de Autoria de Competências

## Identificação da Task

**Código da Task:** TASK13  
**Título:** Processamento de matriz 5x5 com diagonal principal  
**Nível/Curso:** disciplina introdutória de programação em curso técnico ou graduação inicial  
**Componente Curricular:** Introdução à Programação  
**Contexto:** atividade prática individual, com implementação de algoritmo ou programa para processamento de matriz bidimensional e produção de saídas verificáveis  
**Nível de proficiência:** introdutório com integração entre matriz, repetição, expressões e organização de saída

## Introdução

Este relatório situa a TASK13 na fase de **Autoria de Competências** do CSP, com foco na explicitação rastreável dos conhecimentos, objetivos de aprendizagem e competências mobilizados pela tarefa. A atividade solicita a construção de um algoritmo que trabalhe com uma matriz 5x5, calcule a soma da diagonal principal, calcule a soma dos elementos acima dessa diagonal e imprima os elementos abaixo dela.

A tarefa produz evidências observáveis porque exige um artefato executável e resultados diretamente verificáveis: representação da matriz, percorrimento bidimensional, distinção entre regiões estruturais da matriz, acumulação de valores e apresentação de saídas distintas. Esses elementos tornam possível observar desempenho computacional de forma objetiva.

A atividade também sustenta o modelo **K–S–D** com baixa redundância. Os conhecimentos podem ser delimitados por um subconjunto compacto do catálogo da disciplina, os objetivos de aprendizagem permanecem reutilizáveis para outras tarefas de processamento matricial, e as competências resultantes se mantêm estáveis, exclusivas de Computação e compatíveis com o nível introdutório.

# 1. Análise da Entidade Instrucional

## Título

Processamento de matriz 5x5 com diagonal principal

## Descrição

A tarefa propõe a construção de uma solução algorítmica para manipular uma matriz bidimensional de dimensão fixa. O estudante deve preencher a matriz, percorrê-la por linhas e colunas e distinguir três conjuntos de posições segundo sua relação com a diagonal principal.

Do ponto de vista didático, a atividade consolida o uso integrado de matrizes, estruturas de repetição, variáveis acumuladoras, expressões aritméticas e critérios posicionais baseados em índices. A exigência não se limita ao armazenamento da estrutura, pois demanda também seleção lógica de regiões e processamento verificável.

## Processo de Desenvolvimento da Solução 
1. Definir a estrutura matricial 5x5 e as variáveis necessárias ao processamento.
2. Realizar o preenchimento da matriz com valores numéricos.
3. Percorrer a matriz por linhas e colunas com controle consistente de índices.
4. Identificar os elementos da diagonal principal, os elementos acima dela e os elementos abaixo dela.
5. Acumular as somas pedidas e separar a listagem dos elementos solicitados.
6. Exibir os resultados de forma clara e verificável.

## Resultados Esperados

1. Algoritmo ou programa que represente corretamente uma matriz 5x5.
2. Percorrimento completo e coerente da estrutura bidimensional.
3. Cálculo da soma da diagonal principal.
4. Cálculo da soma dos elementos acima da diagonal principal.
5. Impressão dos elementos abaixo da diagonal principal.
6. Saída organizada para conferência objetiva.

## Contexto de Aquisição

**Curso:** Bacharelado em Ciência da Computação  
**Organização da atividade:** individual  
**Ambiente provável:** avaliação escrita, lista de exercícios ou atividade dirigida em laboratório  
**Forma de avaliação:** resposta final acompanhada de justificativa breve e verificável  
**Natureza da evidência:** análise de código, rastreamento de execução e explicação técnica
## Perfil do Público-Alvo

A atividade se destina a estudantes em fase inicial da aprendizagem de programação, já familiarizados com tipos primitivos, variáveis, expressões aritméticas, estruturas de repetição e noções básicas de arranjos. Espera-se que consigam compreender indexação, percorrimento bidimensional e atualização de acumuladores.

Do ponto de vista pedagógico, a tarefa atende especialmente estudantes que precisam consolidar a transição de problemas lineares para problemas com estruturas bidimensionais. A principal demanda formativa está em relacionar posição, critério lógico e processamento numérico sem perder coerência algorítmica.

## Nível de Proficiência (critérios e dimensões)

| Nível de Proficiência | Representação da matriz | Distinção das regiões da matriz | Processamento numérico | Saída e verificabilidade | Coerência global da solução |
|---|---|---|---|---|---|
| **N1 - Inicial** | Declara a matriz, mas acessa posições com inconsistência. | Reconhece parcialmente a diagonal principal, mas confunde regiões vizinhas. | Realiza somas com erros de seleção ou atualização. | Apresenta resultados incompletos ou pouco identificáveis. | A solução executa apenas parte do que foi solicitado. |
| **N2 - Intermediário** | Representa a matriz corretamente, com pequenas falhas de percorrimento. | Distingue diagonal e regiões, mas com falhas pontuais nos limites. | Calcula parte dos resultados corretamente, com inconsistências localizadas. | Exibe os resultados, mas sem organização suficiente para fácil conferência. | A solução cobre a maior parte da tarefa, embora ainda apresente lacunas. |
| **N3 - Proficiente** | Representa e percorre a matriz integralmente com indexação coerente. | Separa corretamente diagonal principal, elementos acima e elementos abaixo. | Calcula corretamente as somas e imprime os elementos solicitados. | Apresenta saídas distintas, legíveis e verificáveis. | A solução atende integralmente ao enunciado com boa consistência. |
| **N4 - Avançado** | Organiza a representação da matriz com clareza e estabilidade estrutural. | Generaliza corretamente a lógica posicional sem ambiguidade. | Mantém cálculo preciso e facilmente auditável durante todo o processamento. | Produz saída clara, bem estruturada e pronta para inspeção rápida. | A solução é completa, coesa e tecnicamente robusta. |

# 2. Seleção e Enumeração de Conhecimentos 

## K02 — Variáveis, constantes e tipos primitivos

1. Representação de dados simples e uso de identificadores para armazenar e manipular valores.
2. Uso coerente de índices, acumuladores e variáveis de controle.
3. Compatibilidade entre tipo de dado e papel computacional da variável.

**Justificativa de mobilização na tarefa:** a solução requer índices, acumuladores e armazenamento de valores numéricos coerentes com o processamento da matriz.

## K03 — Expressões aritméticas e avaliação

1. Construção e avaliação de expressões aritméticas com atualização por atribuição.
2. Cálculo de resultados numéricos em processamento iterativo.
3. Produção de saídas quantitativas consistentes.

**Justificativa de mobilização na tarefa:** a atividade requer somas parciais e finais sobre subconjuntos da matriz.

## K04 — Expressões lógicas e condições

1. Formulação de critérios booleanos a partir de relações entre valores.
2. Uso de comparações para diferenciar casos e subconjuntos.
3. Interpretação correta de verdade e falsidade em regras posicionais.

**Justificativa de mobilização na tarefa:** a distinção entre diagonal principal, região superior e região inferior depende de relações lógicas entre índices.

## K05 — Estrutura sequencial e E/S básica

1. Organização do programa como sequência de leitura ou geração, processamento e saída.
2. Encadeamento consistente das etapas do algoritmo.
3. Produção de saídas verificáveis e identificáveis.

**Justificativa de mobilização na tarefa:** a atividade exige um fluxo claro entre montagem da matriz, processamento e apresentação separada dos resultados.

## K07 — Estruturas de repetição

1. Uso de laços para percorrer estruturas de dados.
2. Controle de contagem e parada segura.
3. Execução iterativa coerente em problemas de varredura e acumulação.

**Justificativa de mobilização na tarefa:** o processamento da matriz depende de percorrimento sistemático por linhas e colunas.

## K08 — Vetores e matrizes em C

1. Representação de coleções homogêneas indexadas em uma ou mais dimensões.
2. Acesso por linha e coluna com indexação coerente.
3. Percorrimento, consulta e processamento de elementos posicionais.

**Justificativa de mobilização na tarefa:** a matriz 5x5 é o objeto central da atividade e toda a solução depende de sua manipulação correta.

# 3. Identificação de Objetivos de Aprendizagem

## LO1
Traduzir enunciados introdutórios em algoritmos organizados em etapas de representação de dados, processamento e produção de resultados.

**K associados:** (K05, K07, K08)

## LO2
Representar e acessar corretamente os elementos de uma matriz bidimensional de dimensão fixa.

**K associados:** (K02, K08)

## LO3
Distinguir subconjuntos de uma matriz com base em relações entre índices e processá-los de forma consistente.

**K associados:** (K04, K07, K08)

## LO4
Acumular e apresentar resultados numéricos derivados do processamento seletivo de elementos matriciais.

**K associados:** (K02, K03, K05, K07, K08)

# 4. Definição de Competências

## 4.1 Competência Geral (BNCC – quando aplicável)

Desenvolver soluções algorítmicas para representar, percorrer, selecionar e processar dados organizados em matrizes, produzindo resultados verificáveis com coerência estrutural e numérica.

**BNCC:** não aplicada neste relatório, pois a tarefa não exige alinhamento obrigatório e não há necessidade de uso de código específico para sustentar a autoria de competências nesta atividade.

## 4.2 Especificações de Competências

### CT13.1

**Título da Competência**  
Traduzir problemas simples em algoritmos claros por decomposição e abstração

**Descrição Textual (reutilizável; não específica do enunciado)**  
Estruturar soluções algorítmicas para problemas introdutórios, decompondo o enunciado em etapas coerentes de representação de dados, processamento e produção de resultados verificáveis.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO2, LO3, LO4)
- K mobilizados (Núcleo): (K05, K07, K08)

**Especificação de Conhecimentos**

**K05**  
Organização sequencial do algoritmo com articulação entre preparação dos dados, processamento e saída.  
Justificativa de evidência: a solução precisa estruturar claramente as etapas do problema até a produção dos resultados solicitados.

**K07**  
Uso de repetição para percorrimento iterativo e cobertura completa da estrutura.  
Justificativa de evidência: o tratamento da matriz depende de laços consistentes para percorrer linhas e colunas.

**K08**  
Representação e manipulação de matrizes bidimensionais.  
Justificativa de evidência: a matriz 5x5 é o objeto computacional central da tarefa.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio em **Criar**, pois a tarefa exige conceber e implementar uma solução algorítmica completa a partir de um enunciado dado, com decomposição funcional do problema.

**Pareamento Conhecimento–Habilidade**

K05 / Criar → planejar a sequência de geração, processamento e apresentação dos resultados de forma verificável.  
Verbos de Bloom: planejar, desenvolver, produzir

K07 / Criar → organizar o percorrimento iterativo necessário ao tratamento da matriz com fluxo coerente.  
Verbos de Bloom: construir, programar, desenvolver

K08 / Criar → conceber uma solução que represente e processe uma matriz bidimensional de dimensão fixa.  
Verbos de Bloom: conceber, criar, produzir


**Especificação de Disposições**  
1. organização lógica  
2. clareza estrutural  
3. rigor na decomposição do problema

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT13.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | organização lógica; clareza estrutural; rigor na decomposição do problema | K05 | planejar a sequência de geração, processamento e apresentação dos resultados de forma verificável |
| CT13.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | organização lógica; clareza estrutural; rigor na decomposição do problema | K07 | organizar o percorrimento iterativo necessário ao tratamento da matriz com fluxo coerente |
| CT13.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | organização lógica; clareza estrutural; rigor na decomposição do problema | K08 | conceber uma solução que represente e processe uma matriz bidimensional de dimensão fixa |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta: a tarefa exige transformar o enunciado em uma solução completa, articulando estrutura de dados, percorrimento e saída. Sem essa competência, o problema não é sequer operacionalizado.


### CT13.2

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões aritméticas simples

**Descrição Textual (reutilizável; não específica do enunciado)**  
Utilizar variáveis, acumuladores e tipos primitivos de modo coerente com o papel de cada dado, realizando cálculos simples de forma consistente durante a execução do algoritmo.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO4)
- K mobilizados (Núcleo): (K02, K03)

**Especificação de Conhecimentos**

**K02**  
Uso de variáveis, índices e acumuladores com tipos compatíveis com seu papel no algoritmo.  
Justificativa de evidência: a solução requer armazenamento e atualização coerente de índices e somatórios.

**K03**  
Construção e avaliação de expressões aritméticas no processamento do programa.  
Justificativa de evidência: as somas pedidas dependem de atualização correta de expressões numéricas ao longo da execução.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio em **Aplicar**, pois o estudante precisa utilizar corretamente tipos, variáveis e expressões em um contexto computacional concreto e verificável.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar e atualizar variáveis, índices e acumuladores compatíveis com o papel de cada dado na solução.  
Verbos de Bloom: usar, implementar, operar

K03 / Aplicar → calcular somas parciais e finais por meio de expressões aritméticas consistentes.  
Verbos de Bloom: calcular, computar, resolver


**Especificação de Disposições**  
1. precisão numérica  
2. consistência na atualização de estado  
3. atenção ao papel de cada variável

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT13.2 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões aritméticas simples | precisão numérica; consistência na atualização de estado; atenção ao papel de cada variável | K02 | declarar e atualizar variáveis, índices e acumuladores compatíveis com o papel de cada dado na solução |
| CT13.2 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões aritméticas simples | precisão numérica; consistência na atualização de estado; atenção ao papel de cada variável | K03 | calcular somas parciais e finais por meio de expressões aritméticas consistentes |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta: os resultados solicitados dependem diretamente da manipulação correta de variáveis, acumuladores e expressões aritméticas simples.

### CT13.3

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras

**Descrição Textual (reutilizável; não específica do enunciado)**  
Implementar estruturas iterativas com controle estável de contagem, atualização de acumuladores e término garantido, assegurando percorrimento completo e processamento consistente.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3, LO4)
- K mobilizados (Núcleo): (K07, K02, K03)

**Especificação de Conhecimentos**

**K07**  
Estruturas de repetição com controle por contagem e parada segura.  
Justificativa de evidência: a matriz precisa ser percorrida sistematicamente por linhas e colunas.

**K02**  
Variáveis de controle e acumuladores associados ao fluxo iterativo.  
Justificativa de evidência: o processamento depende de índices e somatórios atualizados corretamente durante a repetição.

**K03**  
Expressões aritméticas usadas no cálculo acumulativo.  
Justificativa de evidência: as somas são produzidas durante o percurso iterativo da matriz.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio em **Aplicar**, pois a competência se manifesta na implementação correta de laços e atualizações associadas ao processamento iterativo.

**Pareamento Conhecimento–Habilidade**

K07 / Aplicar → implementar laços contados com término garantido para percorrer a matriz de forma integral.  
Verbos de Bloom: iterar, implementar, executar

K02 / Aplicar → manter contadores e acumuladores atualizados de forma coerente durante a repetição.  
Verbos de Bloom: usar, operar, manipular

K03 / Aplicar → integrar cálculo e atualização numérica ao fluxo iterativo sem inconsistências.  
Verbos de Bloom: calcular, computar, operar


**Especificação de Disposições**  
1. disciplina no controle do laço  
2. atenção ao término  
3. constância na atualização dos acumuladores

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT13.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | disciplina no controle do laço; atenção ao término; constância na atualização dos acumuladores | K07 | implementar laços contados com término garantido para percorrer a matriz de forma integral |
| CT13.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | disciplina no controle do laço; atenção ao término; constância na atualização dos acumuladores | K02 | manter contadores e acumuladores atualizados de forma coerente durante a repetição |
| CT13.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | disciplina no controle do laço; atenção ao término; constância na atualização dos acumuladores | K03 | integrar cálculo e atualização numérica ao fluxo iterativo sem inconsistências |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta: o problema não pode ser resolvido sem repetição controlada, contagem estável e atualização progressiva dos resultados numéricos.


### CT13.4

**Título da Competência**  
Representar e processar coleções homogêneas com vetores e matrizes

**Descrição Textual**  
Modelar e processar coleções homogêneas indexadas, utilizando acesso posicional, percorrimento sistemático e seleção de subconjuntos com base em relações estruturais.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO3, LO4)
- K mobilizados (Núcleo): (K08, K07, K04)

**Especificação de Conhecimentos**

**K08**  
Representação e manipulação de vetores e matrizes em C.  
Justificativa de evidência: a atividade exige matriz bidimensional, acesso por índice e processamento posicional.

**K07**  
Percorrimento iterativo de coleções homogêneas.  
Justificativa de evidência: o tratamento da estrutura depende de laços para leitura e processamento das posições.

**K04**  
Expressões lógicas para distinção de subconjuntos estruturais.  
Justificativa de evidência: a separação entre diagonal principal, elementos acima e elementos abaixo exige comparação entre índices.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio em **Aplicar**, com componente analítico na distinção das regiões da matriz.

**Pareamento Conhecimento–Habilidade**

K08 / Aplicar → representar uma matriz bidimensional e acessar seus elementos por indexação correta.  
Verbos de Bloom: implementar, manipular, recuperar

K07 / Aplicar → percorrer sistematicamente a coleção bidimensional para leitura e processamento de seus elementos.  
Verbos de Bloom: iterar, executar, operar

K04 / Analisar → distinguir diagonal principal, região superior e região inferior a partir da relação entre índices.  
Verbos de Bloom: distinguir, categorizar, relacionar


**Especificação de Disposições**  
1. precisão na indexação  
2. rigor na seleção posicional  
3. cuidado com fronteiras estruturais

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT13.4 | Representar e processar coleções homogêneas com vetores e matrizes | precisão na indexação; rigor na seleção posicional; cuidado com fronteiras estruturais | K08 | representar uma matriz bidimensional e acessar seus elementos por indexação correta |
| CT13.4 | Representar e processar coleções homogêneas com vetores e matrizes | precisão na indexação; rigor na seleção posicional; cuidado com fronteiras estruturais | K07 | percorrer sistematicamente a coleção bidimensional para leitura e processamento de seus elementos |
| CT13.4 | Representar e processar coleções homogêneas com vetores e matrizes | precisão na indexação; rigor na seleção posicional; cuidado com fronteiras estruturais | K04 | distinguir diagonal principal, região superior e região inferior a partir da relação entre índices |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta: a matriz é o objeto computacional central da tarefa, e sua manipulação exige tanto processamento iterativo quanto análise posicional entre índices.

