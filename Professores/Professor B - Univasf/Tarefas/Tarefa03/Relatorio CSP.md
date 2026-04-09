# Relatório CSP - Autoria de Competências

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do Competency Specification Process (CSP) e tem como finalidade explicitar, com rastreabilidade, os conhecimentos, objetivos de aprendizagem e competências mobilizados pela TASK03. A tarefa solicita a implementação de um programa que receba largura e comprimento de um aposento, utilize constantes fornecidas no enunciado e produza a quantidade de latas de tinta necessária para pintar apenas as paredes, com desconto da área da porta.

A tarefa elicita evidências observáveis porque exige um artefato executável, com fluxo identificável de entrada, processamento e saída, além de uma justificativa breve sobre a coerência do resultado. Isso permite verificar a representação dos dados, a organização sequencial do programa, a construção de expressões aritméticas e a manutenção de consistência entre restrições do problema e resultado final.

O modelo K-S-D é suportado sem redundância porque a tarefa mobiliza um conjunto reduzido e estável de conhecimentos nucleares da disciplina. O foco recai sobre representação de dados numéricos, processamento aritmético e estrutura sequencial de programas, enquanto as disposições associadas dizem respeito ao rigor, à verificabilidade e à consistência técnica da solução.

## 1. Análise da Entidade Instrucional

### 1.1 Título

Cálculo de latas de tinta para pintura de um aposento

### 1.2 Descrição

Trata-se de uma tarefa introdutória de programação em que o estudante deve construir um programa para resolver um problema prático de cálculo. A atividade exige leitura de duas entradas numéricas, uso de constantes já definidas no enunciado e produção de um resultado inteiro suficiente para atender à situação proposta. O foco instrucional está na tradução de uma descrição verbal para uma solução computacional verificável.

### 1.3 Processo de Desenvolvimento da Solução

1. Identificar os dados de entrada, as constantes fornecidas e o resultado esperado.
2. Representar, no programa, as dimensões do aposento, as constantes do problema e os valores intermediários necessários ao processamento.
3. Organizar o fluxo sequencial para leitura das entradas, cálculo da área pintável, determinação do consumo de tinta e definição da quantidade final de latas.
4. Produzir uma saída verificável e registrar justificativa breve coerente com as restrições do enunciado.

### 1.4 Resultados Esperados

- Programa funcional para o problema proposto.
- Código-fonte com leitura correta das entradas.
- Saída que apresente a quantidade de latas necessária.
- Justificativa breve sobre a coerência do cálculo final.
- Evidência de que a área da porta foi descontada e de que apenas as paredes foram consideradas.

### 1.5 Contexto de Aquisição 

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### 1.6 Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de formação em programação imperativa. Como pré-requisitos, espera-se familiaridade elementar com variáveis, leitura e escrita de dados e operações aritméticas básicas. A principal necessidade formativa está em transformar um enunciado cotidiano em uma sequência computacional precisa, sem perda das restrições do problema.

### 1.7 Nível de Proficiência (critérios e dimensões)

| Nível | Representação dos dados | Processamento aritmético | Fluxo de entrada, processamento e saída | Justificativa e verificabilidade |
|---|---|---|---|---|
| **N1 - Inicial** | Identifica parte das entradas e constantes, mas com inconsistências de tipo ou papel. | Monta cálculos incompletos ou incorretos. | O fluxo é incompleto ou pouco verificável. | A justificativa é ausente ou desconexa. |
| **N2 - Intermediário** | Representa entradas e constantes principais, com pequenas imprecisões. | Realiza parte do processamento corretamente, mas com lacunas na composição global. | O fluxo existe, mas apresenta inconsistências pontuais. | A justificativa existe, mas cobre apenas parte das restrições. |
| **N3 - Proficiente** | Representa corretamente entradas, constantes e valores intermediários. | Estrutura cálculos coerentes com o problema e obtém resultado compatível. | O fluxo é organizado, legível e verificável. | A justificativa é coerente com o processamento e com o resultado. |
| **N4 - Avançado** | Representa os dados com precisão e explicita de modo claro a função de cada elemento no programa. | Integra os cálculos com clareza, precisão e forte rastreabilidade entre etapas. | O fluxo é tecnicamente consistente e favorece leitura, teste e conferência do resultado. | A justificativa articula restrições, processamento e resultado final com precisão técnica. |

## 2. Seleção e Enumeração de Conhecimentos

**K01 - Modelo de execução e noção de estado (paradigma imperativo)**
- Compreensão de que a execução do programa altera o estado por meio de atribuições e atualizações sucessivas.
- Relação entre sequência de comandos, valores intermediários e resultado final.
- Leitura do programa como processo de transformação de estados observáveis.

Justificativa de mobilização na tarefa: a atividade exige acompanhar a evolução dos valores desde a leitura das dimensões até a produção da quantidade final de latas, o que evidencia a noção de estado durante a execução.

**K02 - Variáveis, constantes e tipos primitivos**
- Representação de entradas numéricas, constantes do problema e valores intermediários por identificadores adequados.
- Escolha coerente de tipos numéricos para dimensões, áreas, consumo e quantidade final.
- Uso disciplinado de constantes já fornecidas no enunciado.

Justificativa de mobilização na tarefa: a solução depende de declarar e utilizar, com coerência, dados de entrada e constantes fixas do problema, preservando o papel de cada valor no processamento.

**K03 - Expressões aritméticas e avaliação**
- Construção de expressões para combinar medidas, áreas e consumo de material.
- Respeito à composição dos cálculos e à coerência entre valores intermediários.
- Avaliação correta de expressões numéricas em sequência de processamento.

Justificativa de mobilização na tarefa: o núcleo da atividade consiste em transformar medidas do aposento em área pintável, consumo de tinta e quantidade final de latas por meio de expressões aritméticas corretas.

**K05 - Estrutura sequencial e E/S básica**
- Organização do programa no fluxo leitura, processamento e saída.
- Entrada das dimensões do aposento e apresentação do resultado em formato verificável.
- Encadeamento sequencial dos comandos de modo compatível com o problema.

Justificativa de mobilização na tarefa: a tarefa requer um programa introdutório típico de transformação de entradas numéricas em saída única, com fluxo sequencial claramente verificável.

## 3. Identificação de Objetivos de Aprendizagem

**LO1. Implementar programas sequenciais básicos que transformem entradas numéricas em saídas verificáveis.**

**K associados:** (K02, K05)

**LO2. Manipular variáveis, constantes e tipos primitivos de modo coerente com o papel dos dados no programa.**

**K associados:** (K01, K02)

**LO3. Construir e avaliar expressões aritméticas compatíveis com relações quantitativas simples do problema.**

**K associados:** (K02, K03)

**LO4. Registrar a entrada, apresentar a saída e justificar tecnicamente o resultado produzido com base no processamento realizado.**

**K associados:** (K01, K03, K05)

## 4. Definição de Competências

### 4.1 Competência Geral

Implementar programas básicos que organizem entrada, processamento e saída de forma verificável, manipulem dados numéricos com coerência e produzam resultados consistentes com as restrições explícitas de um problema.

**Alinhamento BNCC:** não aplicável ao contexto desta tarefa.

### 4.2 Especificações de Competências

#### CT03.1

**Título da Competência**  
Implementar programas básicos em linguagem imperativa, organizando entrada, processamento e saída de forma verificável

**Descrição Textual**  
Construir programas introdutórios que recebam dados numéricos, organizem um fluxo sequencial estável de processamento e apresentem uma saída verificável, preservando a função computacional de cada etapa.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO4)
- K mobilizados (Núcleo): (K02, K05)

**Especificação de Conhecimentos**
- K02: permite declarar e utilizar entradas, constantes e resultados parciais de modo compatível com o papel de cada dado.
- K05: evidencia a capacidade de estruturar o programa como sequência verificável de leitura, processamento e saída.

**Alinhamento com a Taxonomia de Bloom (revisada)**

Predomínio de **Criar**, pois a competência exige implementar uma solução computacional básica que articule leitura de dados, processamento e apresentação do resultado em um programa funcional.

**Pareamento Conhecimento-Habilidade**

K02 / Aplicar → declarar e utilizar dados numéricos e constantes compatíveis com o papel de cada elemento no programa.  
Verbos de Bloom: aplicar, implementar, usar

K05 / Criar → produzir um programa sequencial que integre entrada, processamento e saída em fluxo verificável.  
Verbos de Bloom: construir, desenvolver, produzir


**Especificação de Disposições**
- Atenção à função de cada dado no programa.
- Rigor na organização sequencial da solução.
- Compromisso com a verificabilidade da saída produzida.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT03.1 | Implementar programas básicos em linguagem imperativa, organizando entrada, processamento e saída de forma verificável | atenção à função de cada dado; rigor sequencial; verificabilidade da saída | K02 | declarar e utilizar dados numéricos e constantes compatíveis com o papel de cada elemento no programa |
| CT03.1 | Implementar programas básicos em linguagem imperativa, organizando entrada, processamento e saída de forma verificável | atenção à função de cada dado; rigor sequencial; verificabilidade da saída | K05 | produzir um programa sequencial que integre entrada, processamento e saída em fluxo verificável |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade exige a implementação de um programa executável. Sem a organização mínima do fluxo de entrada, processamento e saída, não há artefato funcional nem evidência observável da solução.

#### CT03.2

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples

**Descrição Textual**  
Selecionar e manipular representações numéricas básicas em programas introdutórios, combinando variáveis, constantes e expressões aritméticas de modo coerente com o comportamento esperado da solução.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO3)
- K mobilizados (Núcleo): (K02, K03)

**Especificação de Conhecimentos**
- K02: sustenta a escolha e o uso coerente de tipos primitivos, variáveis e constantes no processamento numérico.
- K03: fundamenta a construção e a avaliação das expressões aritméticas necessárias ao problema.

**Alinhamento com a Taxonomia de Bloom**

Predomínio de **Aplicar**, pois a competência requer utilizar tipos primitivos, variáveis, constantes e expressões aritméticas em um contexto de implementação introdutória, sem exigir modelagem conceitual mais complexa.

**Pareamento Conhecimento-Habilidade**

K02 / Aplicar → selecionar e manipular tipos primitivos, variáveis e constantes coerentes com o processamento numérico do programa.  
Verbos de Bloom: aplicar, manipular, usar

K03 / Aplicar → construir e avaliar expressões aritméticas compatíveis com as relações quantitativas do problema.  
Verbos de Bloom: calcular, computar, resolver


**Especificação de Disposições**
- Precisão no tratamento de valores numéricos.
- Disciplina na associação entre dado, tipo e operação.
- Cuidado com a consistência dos resultados intermediários.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT03.2 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples | precisão numérica; disciplina entre dado, tipo e operação; consistência dos resultados intermediários | K02 | selecionar e manipular tipos primitivos, variáveis e constantes coerentes com o processamento numérico do programa |
| CT03.2 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples | precisão numérica; disciplina entre dado, tipo e operação; consistência dos resultados intermediários | K03 | construir e avaliar expressões aritméticas compatíveis com as relações quantitativas do problema |


**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o centro computacional da atividade está na manipulação coerente dos dados numéricos e na avaliação das expressões usadas para transformar medidas em quantidade final de latas.

#### CT03.3

**Título da Competência**  
Realizar entrada e saída de dados com consistência, apresentando resultados numéricos de forma verificável

**Descrição Textual (reutilizável; não específica do enunciado)**  
Registrar entradas numéricas, apresentar resultados de maneira conferível e justificar a coerência do valor produzido com base no processamento efetuado e nas restrições explícitas do problema.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO4)
- K mobilizados (Núcleo): (K05, K03)

**Especificação de Conhecimentos**
- K05: torna observável a organização da leitura das entradas e da apresentação do resultado em formato verificável.
- K03: sustenta a conferência técnica da coerência numérica do valor exibido.

**Alinhamento com a Taxonomia de Bloom (revisada)**

Predomínio de **Avaliar**, pois a competência exige conferir o resultado apresentado, relacioná-lo ao processamento realizado e justificá-lo tecnicamente a partir das restrições do problema.

**Pareamento Conhecimento-Habilidade**

K05 / Aplicar → organizar leitura das entradas e apresentação do resultado em formato verificável.  
Verbos de Bloom: executar, implementar, usar

K03 / Avaliar → verificar a coerência numérica do resultado apresentado em relação ao processamento realizado.  
Verbos de Bloom: verificar, justificar, validar


**Especificação de Disposições**
- Responsabilidade na conferência do resultado final.
- Clareza na apresentação da saída.
- Consistência técnica na justificativa do valor produzido.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT03.3 | Realizar entrada e saída de dados com consistência, apresentando resultados numéricos de forma verificável | responsabilidade na conferência; clareza na saída; consistência técnica da justificativa | K05 | organizar leitura das entradas e apresentação do resultado em formato verificável |
| CT03.3 | Realizar entrada e saída de dados com consistência, apresentando resultados numéricos de forma verificável | responsabilidade na conferência; clareza na saída; consistência técnica da justificativa | K03 | verificar a coerência numérica do resultado apresentado em relação ao processamento realizado |


**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: justificatória
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: além do código executável, a tarefa exige uma saída conferível e uma justificativa breve do resultado. Por isso, a competência é ativada quando o estudante apresenta e sustenta tecnicamente o valor produzido.
