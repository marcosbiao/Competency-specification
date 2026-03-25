# Relatório CSP
## Fase de Autoria de Competências

## Introdução

Este relatório situa a tarefa na fase de **Autoria de Competências** do CSP, com foco na identificação rastreável de **Conhecimentos (K)**, **Objetivos de Aprendizagem (LO)** e **Competências (CT)** mobilizados por uma atividade introdutória de programação. A tarefa exige a construção de um programa que leia o número de lados de um polígono regular e a medida do lado, distinguindo casos específicos e produzindo saídas textuais e numéricas verificáveis.

A atividade elicita evidências observáveis porque requer um artefato executável ou equivalente, com leitura de dados, processamento condicional e apresentação de resultados compatíveis com as regras do enunciado. No modelo K–S–D, a tarefa mobiliza conhecimentos de tipos primitivos, expressões, entrada e saída e estruturas de seleção, articulados a habilidades observáveis de implementação e a disposições relacionadas à precisão, consistência e verificabilidade. O relatório foi organizado para manter reuso e evitar redundância.

# 1. Análise da Entidade Instrucional

## Título

**Código da Task:** TASK11  
**Título adotado:** Classificação de Polígono Regular com Cálculo Condicional  
**Nível/Curso:** disciplina introdutória de programação  
**Componente Curricular:** Introdução à Programação  
**Contexto:** resolução de problema com dados numéricos, classificação por condição e produção de saída verificável  
**Nível de proficiência da task:** introdutório a intermediário

## Descrição

A tarefa requer a construção de um programa capaz de ler dois dados de entrada, distinguir comportamentos com base em um valor discreto e produzir saídas diferentes conforme a regra do problema. O estudante precisa articular leitura de dados, uso de variáveis, cálculo numérico quando exigido e decisão condicional para classificar corretamente os casos previstos. A evidência principal é a coerência entre entrada, processamento e saída.

## Processo de Desenvolvimento da Solução 

1. Identificar os dados de entrada e seus papéis no problema.
2. Organizar a leitura e o armazenamento dos valores em variáveis compatíveis.
3. Estruturar a decisão condicional a partir do número de lados.
4. Acionar o cálculo numérico apenas nos casos em que o enunciado exige valor de área.
5. Produzir a saída correspondente a cada caso, com texto e valor quando aplicável.
6. Verificar se a solução cobre, sem contradições, todos os casos explicitamente previstos.

## Resultados Esperados

1. Programa ou algoritmo implementado.
2. Leitura correta dos dados de entrada.
3. Saída textual coerente com a classificação solicitada.
4. Saída numérica coerente nos casos em que o problema exige cálculo de área.
5. Registro de execução ou evidência equivalente de funcionamento.
6. Justificativa breve sobre a lógica adotada na distinção dos casos.

### Contexto de Aquisição

1. **Curso:** Ciência da Computação.
2. **Componente curricular:** Introdução à Programação.
3. **Organização:** atividade individual.
4. **Ambiente:** sala de aula, lista de exercícios ou avaliação escrita/prática guiada.
5. **Forma de avaliação:** análise de resposta final com justificativa curta e verificável.

### Perfil do Público-Alvo

1. Estudantes de início de curso, em etapa introdutória de aprendizagem de programação imperativa.
2. Público com contato inicial com variáveis, fluxo sequencial e estruturas de repetição.
3. Necessita consolidar a leitura operacional de trechos de código antes de avançar para implementação de soluções mais extensas.
4. Requer apoio na articulação entre rastreio de execução e explicação técnica do resultado.

## Nível de Proficiência (critérios e dimensões)

| Nível de proficiência | Representação dos dados | Organização do fluxo | Controle por condições | Processamento numérico | Verificabilidade do artefato |
|---|---|---|---|---|---|
| **N1 - Inicial** | Identifica parcialmente os dados, mas com escolhas imprecisas de variáveis ou tipos | Monta sequência incompleta ou com rupturas entre entrada, processamento e saída | Reconhece a necessidade de decisão, mas cobre casos de forma parcial | Realiza cálculo com erros de expressão ou acionamento | Entrega pouco testável ou sem justificativa |
| **N2 - Intermediário** | Representa corretamente os dados principais, com pequenas inconsistências operacionais | Organiza fluxo funcional, mas com pouca clareza ou integração limitada | Implementa a decisão com cobertura principal dos casos previstos | Realiza cálculo funcional, mas com fragilidade de integração ao fluxo | Entrega verificável, porém com justificativa limitada |
| **N3 - Proficiente** | Representa dados e saídas com consistência funcional | Estrutura entrada, processamento e saída de modo verificável | Implementa decisão correta e coerente com as regras do enunciado | Integra cálculo e saída corretamente nos casos exigidos | Entrega verificável com justificativa coerente |
| **N4 - Avançado** | Representa os dados de modo consistente e explicita escolhas com clareza técnica | Estrutura o fluxo com alta clareza, justificando decisões de modelagem | Implementa e justifica a decisão com forte consistência lógica | Integra cálculo, decisão e apresentação com robustez e clareza | Entrega verificável, clara e tecnicamente bem argumentada |

# 2. Seleção e Enumeração de Conhecimentos

## K01 — Modelo de execução e noção de estado (paradigma imperativo)

Descrição  
• compreensão operacional de que um programa evolui por mudanças de estado durante a execução  
• relação entre atribuição, sequência de comandos e efeito produzido no resultado  
• leitura do encadeamento entre entrada, processamento e saída

Justificativa de mobilização na tarefa  
A tarefa exige compreender como os valores lidos compõem o estado do programa e como esse estado conduz decisões e resultados.

## K02 — Variáveis, constantes e tipos primitivos

Descrição  
• representação de dados simples por meio de identificadores  
• uso coerente de tipos numéricos e valores constantes  
• compatibilidade entre dados lidos, cálculos realizados e saídas produzidas

Justificativa de mobilização na tarefa  
O problema depende da leitura e do armazenamento de quantidade de lados e medida do lado em variáveis compatíveis com seus papéis computacionais.

## K03 — Expressões aritméticas e avaliação

Descrição  
• construção e avaliação de expressões aritméticas  
• uso coerente de operadores e composição de cálculos  
• relação entre expressão formulada e resultado numérico produzido

Justificativa de mobilização na tarefa  
Nos casos em que a área deve ser apresentada, a solução precisa implementar um cálculo numérico coerente e integrá-lo ao fluxo do programa.

## K04 — Expressões lógicas e condições

Descrição  
• formulação de condições booleanas a partir de comparações  
• interpretação de verdade e falsidade para controle de fluxo  
• correspondência entre regra do problema e expressão condicional

Justificativa de mobilização na tarefa  
A distinção entre os casos depende de condições explícitas sobre o número de lados e da correta associação entre regra e saída.

## K05 — Estrutura sequencial e E/S básica

Descrição  
• organização do programa como sequência verificável de comandos  
• leitura de entradas e apresentação de saídas compatíveis com o problema  
• encadeamento entre dados recebidos, processamento e resultados mostrados

Justificativa de mobilização na tarefa  
A atividade exige um fluxo básico completo de leitura, processamento e impressão, tornando esse conhecimento central para a execução da solução.

## K06 — Estruturas de seleção

Descrição  
• escolha entre caminhos alternativos de execução  
• cobertura de casos distintos por seleção simples ou encadeada  
• implementação de regras de classificação em programas introdutórios

Justificativa de mobilização na tarefa  
O problema é essencialmente condicional, pois a saída depende do valor lido para o número de lados e requer tratamento diferenciado entre casos.

# 3. Identificação de Objetivos de Aprendizagem

## LO1
Representar dados de entrada e saída com variáveis e tipos primitivos compatíveis ao papel que desempenham na solução.  
**K associados:** (K01, K02, K05)

## LO2
Construir expressões aritméticas simples para produzir resultados numéricos coerentes a partir dos dados lidos.  
**K associados:** (K02, K03)

## LO3
Organizar programas introdutórios segundo um fluxo verificável de entrada, processamento e saída.  
**K associados:** (K01, K05)

## LO4
Formular condições corretas para distinguir casos mutuamente exclusivos em problemas de classificação computacional.  
**K associados:** (K04, K06)

## LO5
Implementar uma solução básica que integre leitura, decisão condicional e cálculo simples de forma coerente.  
**K associados:** (K01, K03, K05, K06)

# 4. Definição de Competências

## 4.1 Competência Geral

Desenvolver programas introdutórios capazes de transformar entradas numéricas em saídas verificáveis por meio de organização sequencial, manipulação de dados, cálculo simples e seleção condicional coerente com regras explícitas do problema.


## 4.2 Especificações de Competências

### CT11.1

**Título da Competência**  
Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais

**Descrição Textual (reutilizável; não específica do enunciado)**  
Implementar programas introdutórios que articulem declarações, atribuições, entrada e saída e estruturas básicas de controle, mantendo coerência entre o comportamento esperado e a semântica da execução.

**Cobertura e rastreabilidade**  
LOs cobertos: (LO1, LO3, LO5)  
K mobilizados (Núcleo): (K01, K02, K05, K06)

**Especificação de Conhecimentos**

**K01**  
Descrição curta: compreensão do programa como sequência de estados ao longo da execução.  
Justificativa de evidência: a solução depende de acompanhar como leitura, decisão e saída modificam o estado do programa.

**K02**  
Descrição curta: uso de variáveis, constantes e tipos primitivos coerentes.  
Justificativa de evidência: os dados do problema precisam ser armazenados em representações compatíveis.

**K05**  
Descrição curta: organização sequencial com entrada, processamento e saída.  
Justificativa de evidência: o artefato final evidencia diretamente o encadeamento funcional do programa.

**K06**  
Descrição curta: seleção entre caminhos alternativos de execução.  
Justificativa de evidência: a implementação deve escolher corretamente o comportamento correspondente a cada caso.

**Alinhamento com a Taxonomia de Bloom**  
Predomina o nível **Aplicar**, pois a tarefa exige implementação funcional de uma solução computacional básica.

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → estruturar a execução do programa como uma sequência coerente de estados observáveis.  
Verbos de Bloom: implementar, executar, programar

K02 / Aplicar → declarar e utilizar variáveis compatíveis com os dados e resultados do problema.  
Verbos de Bloom: implementar, manipular, usar

K05 / Aplicar → organizar entrada, processamento e saída de modo verificável no programa.  
Verbos de Bloom: executar, operar, realizar

K06 / Aplicar → selecionar o caminho de execução adequado às regras explícitas do problema.  
Verbos de Bloom: implementar, programar, resolver


**Especificação de Disposições**  
1. Precisão na implementação.  
2. Atenção à coerência entre regra e comportamento.  
3. Cuidado com a verificabilidade do artefato.

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão, atenção, cuidado | K01 | estruturar a execução do programa como uma sequência coerente de estados observáveis |
| CT11.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão, atenção, cuidado | K02 | declarar e utilizar variáveis compatíveis com os dados e resultados do problema |
| CT11.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão, atenção, cuidado | K05 | organizar entrada, processamento e saída de modo verificável no programa |
| CT11.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão, atenção, cuidado | K06 | selecionar o caminho de execução adequado às regras explícitas do problema |

**Definição de Ativação**  
Restrição de ativação: obrigatória  
Modo de ativação: construtiva  
Função de ativação: núcleo  
Justificativa curta baseada na tarefa: a atividade exige a produção de um programa funcional. Por isso, a implementação básica em linguagem imperativa é condição necessária para que todas as demais evidências apareçam.

### CT11.2

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples

**Descrição Textual**  
Manipular dados elementares em programas introdutórios, escolhendo representações compatíveis, utilizando variáveis e constantes de forma coerente e avaliando expressões aritméticas simples com correção operacional.

**Cobertura e rastreabilidade**  
LOs cobertos: (LO1, LO2)  
K mobilizados (Núcleo): (K02, K03)

**Especificação de Conhecimentos**

**K02**  
Descrição curta: representação de dados com variáveis, constantes e tipos primitivos.  
Justificativa de evidência: a tarefa exige armazenar e utilizar corretamente valores numéricos com papéis distintos.

**K03**  
Descrição curta: construção e avaliação de expressões aritméticas.  
Justificativa de evidência: a solução precisa produzir cálculo coerente nos casos em que a área é solicitada.

**Alinhamento com a Taxonomia de Bloom**  
Predomina o nível **Aplicar**, pois o estudante precisa usar tipos e expressões em uma situação concreta de programação.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → representar dados numéricos com tipos primitivos e variáveis compatíveis com seu papel funcional.  
Verbos de Bloom: implementar, manipular, usar

K03 / Aplicar → construir e avaliar expressões aritméticas simples de forma coerente com o resultado esperado.  
Verbos de Bloom: calcular, computar, resolver



**Especificação de Disposições**  
1. Exatidão no tratamento dos dados.  
2. Atenção à coerência entre representação e cálculo.  
3. Rigor na produção de resultados numéricos.

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.2 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples | exatidão, atenção, rigor | K02 | representar dados numéricos com tipos primitivos e variáveis compatíveis com seu papel funcional |
| CT11.2 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples | exatidão, atenção, rigor | K03 | construir e avaliar expressões aritméticas simples de forma coerente com o resultado esperado |

**Definição de Ativação**  
Restrição de ativação: obrigatória  
Modo de ativação: construtiva  
Função de ativação: núcleo  
Justificativa curta baseada na tarefa: a leitura de dados numéricos e o cálculo condicionado da área exigem manipulação correta de tipos primitivos, variáveis e expressões aritméticas.

### CT11.3

**Título da Competência**  
Realizar entrada e saída de dados com consistência mínima e formatação apropriada

**Descrição Textual**  
Realizar leitura e apresentação de dados em programas introdutórios, preservando consistência entre os valores processados, a ordem do fluxo e a forma de exibição dos resultados.

**Cobertura e rastreabilidade**  
LOs cobertos: (LO1, LO3)  
K mobilizados (Núcleo): (K02, K05)

**Especificação de Conhecimentos**

**K02**  
Descrição curta: uso de variáveis e tipos adequados aos dados manipulados.  
Justificativa de evidência: as entradas e saídas do problema dependem de representações coerentes.

**K05**  
Descrição curta: estrutura sequencial e entrada e saída básica.  
Justificativa de evidência: o artefato final deve evidenciar claramente o fluxo entrada, processamento e saída.

**Alinhamento com a Taxonomia de Bloom**  
Predomina o nível **Aplicar**, pois a tarefa exige leitura e apresentação funcional de dados em um programa.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → armazenar os dados lidos em variáveis compatíveis com o papel que desempenham na solução.  
Verbos de Bloom: implementar, manipular, usar

K05 / Aplicar → realizar entrada e saída de dados em sequência verificável e com apresentação apropriada dos resultados.  
Verbos de Bloom: executar, operar, realizar


**Especificação de Disposições**  
1. Clareza na organização do fluxo.  
2. Atenção à consistência entre entrada e saída.  
3. Compromisso com a verificabilidade do programa.

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.3 | Realizar entrada e saída de dados com consistência mínima e formatação apropriada | clareza, atenção, compromisso | K02 | armazenar os dados lidos em variáveis compatíveis com o papel que desempenham na solução |
| CT11.3 | Realizar entrada e saída de dados com consistência mínima e formatação apropriada | clareza, atenção, compromisso | K05 | realizar entrada e saída de dados em sequência verificável e com apresentação apropriada dos resultados |

**Definição de Ativação**  
Restrição de ativação: obrigatória  
Modo de ativação: construtiva  
Função de ativação: núcleo  
Justificativa curta baseada na tarefa: a tarefa só produz evidência observável se os dados forem lidos corretamente e os resultados forem apresentados de maneira compatível com as exigências do enunciado.

### CT11.4

**Título da Competência**  
Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas

**Descrição Textual**  
Controlar o fluxo de programas introdutórios por meio de decisões baseadas em condições logicamente corretas, distinguindo casos mutuamente exclusivos e associando cada caso ao comportamento computacional apropriado.

**Cobertura e rastreabilidade**  
LOs cobertos: (LO4, LO5)  
K mobilizados (Núcleo): (K04, K05, K06)

**Especificação de Conhecimentos**

**K04**  
Descrição curta: formulação de expressões lógicas e condições.  
Justificativa de evidência: a classificação depende da comparação correta do número de lados com os casos previstos.

**K05**  
Descrição curta: organização sequencial do fluxo com entrada, processamento e saída.  
Justificativa de evidência: a decisão precisa estar integrada ao fluxo geral do programa sem comprometer a verificabilidade.

**K06**  
Descrição curta: uso de estruturas de seleção para cobrir caminhos alternativos.  
Justificativa de evidência: a tarefa exige tratar corretamente saídas diferentes para cada caso previsto.

**Alinhamento com a Taxonomia de Bloom**  
Predomina o nível **Aplicar**, com componente de **Analisar** na correspondência entre condição formulada e caminho executado.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → formular expressões lógicas corretas para distinguir os casos previstos pelo problema.  
Verbos de Bloom: implementar, operar, usar

K05 / Aplicar → integrar a decisão condicional ao fluxo geral da solução de forma verificável.  
Verbos de Bloom: executar, operar, realizar

K06 / Aplicar → implementar estruturas de seleção que associem cada condição ao comportamento adequado do programa.  
Verbos de Bloom: implementar, programar, resolver


**Especificação de Disposições**  
1. Rigor lógico na formulação das condições.  
2. Atenção à cobertura dos casos.  
3. Cuidado com a coerência entre condição e saída.

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.4 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | rigor, atenção, cuidado | K04 | formular expressões lógicas corretas para distinguir os casos previstos pelo problema |
| CT11.4 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | rigor, atenção, cuidado | K05 | integrar a decisão condicional ao fluxo geral da solução de forma verificável |
| CT11.4 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | rigor, atenção, cuidado | K06 | implementar estruturas de seleção que associem cada condição ao comportamento adequado do programa |

**Definição de Ativação**  
Restrição de ativação: obrigatória  
Modo de ativação: construtiva  
Função de ativação: núcleo  
Justificativa curta baseada na tarefa: a classificação pedida no enunciado depende diretamente da formulação correta das condições e da escolha do ramo adequado de execução.