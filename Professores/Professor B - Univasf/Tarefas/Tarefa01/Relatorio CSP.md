# Relatório CSP — Autoria de Competências


## Introdução

Este relatório situa a task na fase de **Autoria de Competências** do CSP, com foco na identificação de conhecimentos, objetivos de aprendizagem e competências diretamente mobilizados por uma atividade de programação introdutória. A tarefa solicita a implementação de um programa que opere sobre quatro valores numéricos previamente armazenados, produzindo quatro resultados distintos e apresentando-os de forma identificável e verificável.

A entidade instrucional gera evidências observáveis porque exige um artefato executável, saídas passíveis de conferência e uma justificativa breve sobre a correção do processamento realizado. Essas evidências permitem rastrear, com boa precisão, conhecimentos relativos a estado do programa, tipos primitivos, expressões aritméticas e organização sequencial de entrada, processamento e saída.

A tarefa também suporta o modelo **K–S–D** sem redundância. Os **conhecimentos** concentram-se no catálogo da disciplina, as **habilidades** são observáveis no código e na apresentação dos resultados, e as **disposições** aparecem como atitudes operacionais de precisão, conferência e consistência técnica durante a implementação.

## 1. Análise da Entidade Instrucional

### Título

Cálculo e impressão de médias aritmética, geométrica, harmônica e ponderada

### Descrição

Trata-se de uma atividade introdutória de programação cujo foco é a construção de um programa sequencial que receba como base quatro valores numéricos já associados a variáveis e produza quatro saídas distintas. A tarefa demanda organização adequada do estado do programa, formulação de expressões aritméticas coerentes, uso consistente de variáveis numéricas e apresentação verificável dos resultados.

### Processo de Desenvolvimento da Solução (em etapas)

1. Identificar os dados de entrada já definidos no enunciado e os resultados que devem ser produzidos.
2. Representar os valores em variáveis compatíveis com o processamento numérico esperado.
3. Organizar a sequência de processamento necessária para gerar os quatro resultados solicitados.
4. Implementar as expressões aritméticas correspondentes, preservando coerência entre dados, processamento e resultado.
5. Exibir os resultados de forma identificável e registrar justificativa breve sobre a correção da solução.

### Resultados Esperados

1. Código-fonte completo do programa.
2. Saída do programa contendo as quatro médias solicitadas, identificadas de modo claro.
3. Evidência de uso coerente das variáveis `x`, `y`, `w` e `z`.
4. Justificativa breve, tecnicamente consistente, relacionando o enunciado ao processamento implementado.

### Contexto de Aquisição (curso, organização, ambiente, avaliação)

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### Perfil do Público-Alvo (nível, pré-requisitos, necessidades)

O público-alvo corresponde a estudantes em fase inicial de aprendizagem de programação imperativa. Pressupõe-se familiaridade introdutória com variáveis, atribuição, tipos primitivos, expressões aritméticas e estrutura sequencial. A principal necessidade formativa é consolidar a passagem de um enunciado matemático simples para uma implementação computacional verificável.

### Nível de Proficiência

| Nível | Formulação algorítmica | Representação de dados | Processamento aritmético | Fluxo do programa | Comunicação e verificabilidade |
|---|---|---|---|---|---|
| **N1 - Inicial** | Reconhece parcialmente os dados e resultados do problema, mas organiza a solução com lacunas | Usa variáveis ou tipos com inadequações que comprometem parte da solução | Implementa cálculos com erros de formulação ou de avaliação | Apresenta sequência incompleta ou pouco verificável entre dados, processamento e saída | Exibe resultados sem identificação suficiente ou sem justificativa coerente |
| **N2 - Intermediário**| Decompõe o problema em etapas básicas, com pequenas inconsistências | Usa variáveis e tipos majoritariamente adequados, com pequenas inconsistências | Implementa cálculos essenciais, mas com inconsistências pontuais | Organiza um fluxo básico, ainda com fragilidades de apresentação ou rastreabilidade | Exibe resultados identificáveis, mas com justificativa limitada |
| **N3 - Proficiente** | Estrutura a solução em etapas claras e coerentes com o enunciado | Representa dados e resultados com variáveis e tipos compatíveis | Implementa corretamente as expressões necessárias e produz resultados coerentes | Mantém fluxo verificável de entrada ou preparação dos dados, processamento e saída | Exibe resultados claros e apresenta justificativa breve coerente |
| **N4 - Avançado** | Estrutura a solução com clareza, economia e alta rastreabilidade entre problema e algoritmo | Representa dados e resultados com precisão e demonstra controle rigoroso sobre coerência de tipos e papéis | Implementa os cálculos com correção, clareza estrutural e justificativa técnica consistente | Mantém fluxo altamente claro, verificável e bem articulado entre todas as partes do programa | Exibe resultados claros, consistentes e apresenta justificativa precisa, técnica e facilmente auditável |"""


## 2. Seleção e Enumeração de Conhecimentos

**K01 — Modelo de execução e noção de estado (paradigma imperativo)**

* Compreensão de que o programa evolui por mudanças de estado ao longo da execução.
* Leitura operacional das atribuições e da ordem em que os comandos produzem resultados.
* Relação entre sequência de processamento e efeito observável nas saídas.

**Justificativa de mobilização na tarefa:** a atividade exige que o estudante organize o programa como uma sequência coerente de estados, preservando a correspondência entre valores iniciais, processamento e resultados exibidos.

**K02 — Variáveis, constantes e tipos primitivos**

* Representação de dados simples por meio de variáveis numéricas.
* Uso coerente de tipos primitivos em cálculos básicos.
* Associação correta entre identificadores, valores e resultados produzidos.

**Justificativa de mobilização na tarefa:** a solução depende do uso consistente das variáveis `x`, `y`, `w` e `z`, bem como da escolha de representação numérica compatível com resultados possivelmente não inteiros.

**K03 — Expressões aritméticas e avaliação**

* Construção de expressões aritméticas compostas com operadores e agrupamentos.
* Avaliação coerente de cálculos numéricos em programas introdutórios.
* Controle da precedência e da composição de operações no processamento.

**Justificativa de mobilização na tarefa:** a task exige a implementação de múltiplos cálculos a partir do mesmo conjunto de dados, o que torna central a formulação correta de expressões aritméticas.

**K05 — Estrutura sequencial e E/S básica**

* Organização do programa como sequência de comandos orientada ao problema.
* Encadeamento verificável entre preparação de dados, processamento e saída.
* Produção de saídas claras e conferíveis em contexto introdutório.

**Justificativa de mobilização na tarefa:** a atividade requer um fluxo sequencial simples, no qual os dados são processados e os resultados são exibidos de maneira identificável.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Representar e manipular dados numéricos em variáveis compatíveis com problemas de cálculo sequencial.  
**K associados:** (K02, K05)

**LO2.** Organizar o estado do programa em uma sequência coerente de atribuições e atualizações voltada à produção de múltiplos resultados.  
**K associados:** (K01, K02, K05)

**LO3.** Implementar expressões aritméticas compostas de modo correto e verificável em problemas introdutórios de programação.  
**K associados:** (K03, K02, K01)

**LO4.** Produzir saídas identificáveis e justificativas breves que permitam conferir a consistência entre processamento e resultado.  
**K associados:** (K05, K01, K03)

## 4. Definição de Competências

### 4.1 Competência Geral

Modelar e implementar programas sequenciais simples que representem dados numéricos, realizem processamento aritmético coerente e produzam saídas verificáveis.

**BNCC:** não aplicável ao contexto desta task, por se tratar de atividade situada no ensino superior.

### 4.2 Especificações de Competências

## CT01.1

**Título da Competência**  
Traduzir problemas simples em algoritmos claros por decomposição e abstração

**Descrição Textual**  
Analisar problemas introdutórios de programação e estruturá-los como algoritmos sequenciais claros, distinguindo dados, processamento e resultados de forma verificável e reutilizável em diferentes contextos elementares da disciplina.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO2)
2. K mobilizados: (K01, K03, K05)

**Especificação de Conhecimentos**

**K01:** compreensão do programa como sucessão de estados observáveis.  
**Justificativa de evidência:** a competência é evidenciada quando o estudante organiza a solução como sequência coerente de ações e resultados.

**K03:** construção e avaliação de expressões aritméticas compatíveis com o problema.  
**Justificativa de evidência:** a decomposição do problema exige identificar quais cálculos compõem o processamento solicitado.

**K05:** estruturação sequencial do artefato com articulação verificável entre processamento e saída.  
**Justificativa de evidência:** a clareza algorítmica se manifesta na organização ordenada das etapas do programa.

**Alinhamento com a Taxonomia de Bloom**  
Predominância em **Analisar**.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → decompor o problema em estados sucessivos do programa, preservando a coerência entre cada etapa da solução.  
Verbos de Bloom: decompor, estruturar, rastrear

K03 / Analisar → relacionar os cálculos requeridos pelo problema às expressões aritméticas que compõem o algoritmo.  
Verbos de Bloom: analisar, relacionar, modelar

K05 / Analisar → estruturar a solução em uma sequência clara de preparação dos dados, processamento e apresentação dos resultados.  
Verbos de Bloom: estruturar, contextualizar, decompor


**Especificação de Disposições**
1. Clareza na organização do raciocínio algorítmico.
2. Atenção à decomposição adequada do problema.
3. Compromisso com a verificabilidade da solução.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT01.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza; atenção; verificabilidade | K01 | decompor o problema em estados sucessivos do programa, preservando a coerência entre cada etapa da solução |
| CT01.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza; atenção; verificabilidade | K03 | relacionar os cálculos requeridos pelo problema às expressões aritméticas que compõem o algoritmo |
| CT01.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza; atenção; verificabilidade | K05 | estruturar a solução em uma sequência clara de preparação dos dados, processamento e apresentação dos resultados |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: analítica
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a competência é ativada porque a tarefa exige decompor um problema numérico simples em uma solução sequencial inteligível, antes da implementação efetiva do programa.

## CT01.2

**Título da Competência**  
Implementar programas introdutórios com fluxo verificável de entrada, processamento e saída

**Descrição Textual**  
Construir programas introdutórios em que dados, processamento e saída permaneçam articulados de forma clara, verificável e tecnicamente consistente, mesmo em problemas de baixa complexidade estrutural.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO2, LO4)
2. K mobilizados: (K01, K03, K05)

**Especificação de Conhecimentos**

**K01:** relação entre ordem de execução e efeitos observáveis no programa.  
**Justificativa de evidência:** a verificabilidade do fluxo depende de compreender como o programa avança até produzir as saídas finais.

**K03:** composição correta de cálculos no interior do fluxo implementado.  
**Justificativa de evidência:** o processamento do programa só é verificável se os cálculos realizados forem coerentes com o problema.

**K05:** organização sequencial e produção de saídas identificáveis.  
**Justificativa de evidência:** a tarefa evidencia diretamente a necessidade de apresentar um fluxo completo e conferível.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predominância em **Aplicar**.

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → manter coerência entre a ordem de execução do programa e os resultados que devem ser produzidos ao final do processamento.  
Verbos de Bloom: implementar, operar, usar

K03 / Aplicar → implementar os cálculos requeridos no fluxo do programa, preservando correção e verificabilidade.  
Verbos de Bloom: calcular, implementar, resolver

K05 / Aplicar → organizar entrada ou preparação dos dados, processamento e saída de modo identificável e conferível.  
Verbos de Bloom: executar, implementar, apresentar


**Especificação de Disposições**
1. Cuidado com a integridade do fluxo do programa.
2. Precisão na apresentação das saídas.
3. Responsabilidade na conferência do comportamento implementado.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT01.2 | Implementar programas introdutórios com fluxo verificável de entrada, processamento e saída | cuidado; precisão; responsabilidade | K01 | manter coerência entre a ordem de execução do programa e os resultados que devem ser produzidos ao final do processamento |
| CT01.2 | Implementar programas introdutórios com fluxo verificável de entrada, processamento e saída | cuidado; precisão; responsabilidade | K03 | implementar os cálculos requeridos no fluxo do programa, preservando correção e verificabilidade |
| CT01.2 | Implementar programas introdutórios com fluxo verificável de entrada, processamento e saída | cuidado; precisão; responsabilidade | K05 | organizar entrada ou preparação dos dados, processamento e saída de modo identificável e conferível |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a competência é ativada porque a atividade requer a construção efetiva de um programa sequencial cuja execução possa ser conferida por meio do código e da saída produzida.

## CT01.3

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e expressões simples, preservando a coerência do estado do programa

**Descrição Textual**  
Empregar tipos primitivos, variáveis e expressões aritméticas simples em programas introdutórios, mantendo consistência entre representação dos dados, transformações realizadas e estado resultante do programa.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO3, LO4)
2. K mobilizados: (K01, K02, K03)

**Especificação de Conhecimentos**

**K01:** compreensão das mudanças de estado decorrentes das atribuições e cálculos executados.  
**Justificativa de evidência:** a competência é visível quando o estudante preserva coerência entre dados iniciais, processamento e resultados finais.

**K02:** uso de variáveis e tipos primitivos compatíveis com o papel de cada dado no programa.  
**Justificativa de evidência:** a task depende diretamente da correta representação numérica dos valores e resultados.

**K03:** formulação e avaliação de expressões aritméticas corretas.  
**Justificativa de evidência:** a produção das médias solicitadas exige uso consistente e verificável de expressões numéricas.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predominância em **Aplicar**.

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → preservar a coerência do estado do programa à medida que valores são utilizados para gerar novos resultados.  
Verbos de Bloom: operar, usar, implementar

K02 / Aplicar → representar dados e resultados com variáveis e tipos primitivos compatíveis com o processamento realizado.  
Verbos de Bloom: manipular, implementar, usar

K03 / Aplicar → construir expressões aritméticas simples e corretas para transformar dados em resultados verificáveis.  
Verbos de Bloom: calcular, implementar, resolver


**Especificação de Disposições**
1. Precisão no uso de dados numéricos.
2. Atenção à coerência entre representação e processamento.
3. Rigor técnico na formulação dos cálculos.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT01.3 | Manipular dados com tipos primitivos, variáveis e expressões simples, preservando a coerência do estado do programa | precisão; atenção; rigor técnico | K01 | preservar a coerência do estado do programa à medida que valores são utilizados para gerar novos resultados |
| CT01.3 | Manipular dados com tipos primitivos, variáveis e expressões simples, preservando a coerência do estado do programa | precisão; atenção; rigor técnico | K02 | representar dados e resultados com variáveis e tipos primitivos compatíveis com o processamento realizado |
| CT01.3 | Manipular dados com tipos primitivos, variáveis e expressões simples, preservando a coerência do estado do programa | precisão; atenção; rigor técnico | K03 | construir expressões aritméticas simples e corretas para transformar dados em resultados verificáveis |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a competência é ativada porque o problema exige manipulação consistente de dados numéricos e formulação correta de expressões aritméticas no interior do programa.
