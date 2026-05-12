from pathlib import Path

content = r"""# RELATÓRIO CSP — AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do Competency Specification Process (CSP) e tem por finalidade explicitar, com alta rastreabilidade, os conhecimentos, objetivos de aprendizagem e competências mobilizados pela **TASK05**, referente ao cálculo da área e da potência de iluminação de um cômodo retangular.

A tarefa solicita que o estudante leia duas dimensões em metros, determine a área do ambiente e calcule a potência de iluminação correspondente com base em uma taxa fixa fornecida no enunciado. As evidências são diretamente observáveis no artefato produzido, especialmente na representação dos dados, na organização do fluxo sequencial, na correção do processamento aritmético e na clareza da saída final.

A atividade sustenta adequadamente o modelo **Conhecimento–Habilidade–Disposição (K–S–D)** porque mobiliza conhecimentos centrais da programação introdutória, requer habilidades técnicas objetivamente verificáveis e permite associar disposições compatíveis com rigor computacional, precisão e consistência lógica. O relatório foi estruturado para maximizar reuso e evitar redundâncias, utilizando exclusivamente conhecimentos já existentes no catálogo da disciplina.

---

## 1. Análise da Entidade Instrucional

### Título

**TASK05 — Cálculo da área e da potência de iluminação de um cômodo**

### Descrição

Trata-se de uma tarefa introdutória de programação voltada à tradução de um enunciado quantitativo simples em uma solução executável. O estudante deve ler duas medidas correspondentes às dimensões de um cômodo retangular, calcular sua área e, em seguida, obter a potência de iluminação necessária segundo um critério proporcional explícito no problema. O foco instrucional está na articulação entre leitura de dados, processamento aritmético e apresentação de resultados verificáveis.

### Processo de Desenvolvimento da Solução

1. Identificar no enunciado os dados de entrada e os resultados esperados.
2. Representar as dimensões e os resultados por variáveis numéricas adequadas.
3. Organizar a solução em fluxo sequencial de entrada, processamento e saída.
4. Construir o cálculo da área do cômodo retangular.
5. Aplicar a relação de proporcionalidade fornecida para determinar a potência.
6. Exibir de forma explícita a área calculada e a potência correspondente.

### Resultados Esperados

- código-fonte contendo leitura de dados, processamento e saída;
- representação coerente das dimensões do cômodo;
- cálculo correto da área;
- cálculo correto da potência de iluminação;
- saída final verificável, contendo os dois resultados solicitados;
- justificativa breve coerente com a lógica empregada.

### Contexto de Aquisição

- **Curso:** Ciência da Computação
- **Nível/Curso:** graduação, disciplina introdutória
- **Componente Curricular:** Programação de Computadores I
- **Organização:** atividade individual
- **Ambiente:** laboratório de programação ou avaliação prática introdutória
- **Avaliação:** análise do código, da coerência do processamento e da verificabilidade da saída produzida

### Perfil do Público-Alvo

O público-alvo é composto por estudantes ingressantes em disciplinas introdutórias de programação, em fase de consolidação dos fundamentos de variáveis, tipos primitivos, expressões aritméticas e organização sequencial de programas. São estudantes que ainda necessitam fortalecer a capacidade de converter descrições textuais de problemas em soluções computacionais corretas, simples e verificáveis.

### Nível de Proficiência (critérios e dimensões)

| Nível | Representação de dados | Fluxo sequencial | Processamento aritmético | Saída e verificabilidade |
|---|---|---|---|---|
| **N1 — Inicial** | identifica parcialmente as variáveis necessárias | organiza a solução com lacunas na sequência de execução | realiza cálculos incorretos ou incompletos | apresenta saída ausente, imprecisa ou pouco verificável |
| **N2 — Intermediario** | representa os dados principais com pequenas inconsistências | estrutura a sequência geral, mas com fragilidades operacionais | calcula parte dos resultados corretamente | apresenta saída compreensível, porém com baixa precisão técnica |
| **N3 — Proficiente** | utiliza variáveis e tipos de modo coerente | organiza corretamente entrada, processamento e saída | calcula área e potência com consistência | apresenta saída clara e verificável |
| **N4 — Avançado** | representa os dados com precisão e clareza | organiza o fluxo com alta consistência e legibilidade | integra cálculos e atualização de resultados de modo estável | apresenta saída tecnicamente clara, consistente e plenamente verificável |

---

## 2. Seleção e Enumeração de Conhecimentos

### K01 — Conceitos básicos de computação e resolução de problemas
- compreensão do problema como relação entre dados de entrada, processamento e resultados;
- noção de programa como solução executável para um problema bem definido;
- identificação de elementos essenciais do problema antes da implementação.

**Justificativa de mobilização na tarefa:** a tarefa exige que o estudante compreenda a situação proposta e a reorganize como problema computacional simples, com entradas explícitas e resultados determinados.

### K02 — Algoritmos e formas de representação
- compreensão de algoritmo como sequência ordenada e finita de passos;
- leitura e elaboração de solução procedural em nível introdutório;
- organização lógica da resolução antes ou durante a codificação.

**Justificativa de mobilização na tarefa:** a solução depende da tradução do enunciado em um procedimento executável, ainda que simples, com etapas bem ordenadas.

### K03 — Estrutura sequencial, entrada, processamento e saída
- organização do programa em leitura de dados, processamento e apresentação de resultados;
- encadeamento coerente de instruções em ordem de execução;
- explicitação dos resultados finais em forma observável.

**Justificativa de mobilização na tarefa:** a estrutura da atividade é integralmente sequencial e o comportamento esperado pode ser verificado diretamente nesse fluxo.

### K04 — Variáveis, constantes, tipos de dados e atribuição
- representação de dados e resultados por variáveis adequadas;
- uso de tipos numéricos compatíveis com o problema;
- atualização consistente de valores ao longo da execução.

**Justificativa de mobilização na tarefa:** a solução requer armazenar dimensões, área e potência em variáveis numéricas coerentes com seus papéis computacionais.

### K05 — Expressões aritméticas, relacionais e lógicas
- construção de expressões aritméticas para obtenção de resultados derivados;
- avaliação correta de operadores e resultados numéricos;
- uso de cálculo como mecanismo central de transformação dos dados de entrada.

**Justificativa de mobilização na tarefa:** a tarefa depende diretamente da formulação e aplicação correta de expressões aritméticas para calcular área e potência.

## 3. Identificação de Objetivos de Aprendizagem

### LO1
**Representar dados numéricos de entrada e saída em variáveis compatíveis com o papel computacional de cada informação.**  
**K associados:** (K04)

### LO2
**Organizar soluções introdutórias segundo um fluxo verificável de entrada, processamento e saída.**  
**K associados:** (K02, K03)

### LO3
**Aplicar expressões aritméticas para gerar resultados derivados a partir de dados fornecidos pelo usuário.**  
**K associados:** (K04, K05)

### LO4
**Apresentar resultados de forma explícita, verificável e coerente com o processamento realizado.**  
**K associados:** (K03, K05)

### LO5
**Traduzir um enunciado quantitativo simples em um algoritmo executável orientado à resolução do problema.**  
**K associados:** (K01, K02, K03)

## 4. Definição de Competências

### 4.1 Competência Geral

**Implementar soluções computacionais introdutórias para problemas quantitativos simples, articulando modelagem do problema, representação de dados, fluxo sequencial e processamento aritmético de forma verificável.**

### 4.2 Especificações de Competências

## CT05.1

**Título da Competência**  
**Estruturar programas introdutórios com fluxo sequencial e representação consistente de dados numéricos**

**Descrição Textual**  
Capacidade de construir programas simples em linguagem de programação estruturada, organizando dados numéricos e o fluxo de entrada, processamento e saída de modo tecnicamente coerente e verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO2)
- K mobilizados (Núcleo): (K03, K04)

**Especificação de Conhecimentos**
- **K03:** estrutura sequencial, entrada, processamento e saída. **Justificativa de evidência:** a competência é evidenciada diretamente pela ordem funcional do programa e pela presença explícita das três etapas.
- **K04:** variáveis, constantes, tipos de dados e atribuição. **Justificativa de evidência:** a competência é evidenciada pela representação correta das medidas e dos resultados em variáveis numéricas coerentes.


**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência requer uso operacional de variáveis, atribuições e fluxo sequencial em um artefato executável.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → estruturar o programa em uma sequência verificável de entrada, processamento e saída.  
Verbos de Bloom: executar, programar, resolver

K04 / Aplicar → declarar e utilizar variáveis numéricas compatíveis com o papel computacional de cada dado.  
Verbos de Bloom: implementar, manipular, usar


**Especificação de Disposições**
- precisão na representação dos dados;
- atenção à ordem das instruções;
- rigor na organização do fluxo computacional.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT05.1 | Estruturar programas introdutórios com fluxo sequencial e representação consistente de dados numéricos | precisão na representação dos dados; atenção à ordem das instruções; rigor na organização do fluxo computacional | K03 | estruturar o programa em uma sequência verificável de entrada, processamento e saída |
| CT05.1 | Estruturar programas introdutórios com fluxo sequencial e representação consistente de dados numéricos | precisão na representação dos dados; atenção à ordem das instruções; rigor na organização do fluxo computacional | K04 | declarar e utilizar variáveis numéricas compatíveis com o papel computacional de cada dado |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa exige a construção efetiva de um programa funcional. A evidência central desta competência aparece na organização do artefato produzido e na consistência entre variáveis, sequência de execução e resultados apresentados.


## CT05.2

**Título da Competência**  
**Implementar processamento aritmético simples para produzir resultados derivados em programas introdutórios**

**Descrição Textual**  
Capacidade de aplicar expressões aritméticas e atribuições em programas introdutórios para transformar dados de entrada em resultados numéricos derivados, de forma correta e tecnicamente verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO3, LO4)
- K mobilizados (Núcleo): (K04, K05)

**Especificação de Conhecimentos**
- **K04:** variáveis, constantes, tipos de dados e atribuição. **Justificativa de evidência:** a competência é evidenciada pela atualização correta das variáveis que armazenam os resultados do processamento.
- **K05:** expressões aritméticas, relacionais e lógicas. **Justificativa de evidência:** a competência é evidenciada diretamente pela formulação correta dos cálculos necessários para gerar os resultados.


**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência envolve operacionalizar cálculos e registrar resultados em um contexto computacional simples.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → armazenar e atualizar resultados numéricos em variáveis coerentes com o processamento realizado.  
Verbos de Bloom: implementar, operar, usar

K05 / Aplicar → calcular valores derivados por meio de expressões aritméticas corretas e verificáveis.  
Verbos de Bloom: calcular, computar, resolver


**Especificação de Disposições**
- precisão algorítmica;
- cuidado com a consistência numérica;
- rigor na atualização dos resultados.


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT05.2 | Implementar processamento aritmético simples para produzir resultados derivados em programas introdutórios | precisão algorítmica; cuidado com a consistência numérica; rigor na atualização dos resultados | K04 | armazenar e atualizar resultados numéricos em variáveis coerentes com o processamento realizado |
| CT05.2 | Implementar processamento aritmético simples para produzir resultados derivados em programas introdutórios | precisão algorítmica; cuidado com a consistência numérica; rigor na atualização dos resultados | K05 | calcular valores derivados por meio de expressões aritméticas corretas e verificáveis |
| CT05.2 | Implementar processamento aritmético simples para produzir resultados derivados em programas introdutórios | precisão algorítmica; cuidado com a consistência numérica; rigor na atualização dos resultados | K03 | inserir o processamento no ponto adequado do fluxo de execução do programa |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa depende diretamente do cálculo de valores derivados a partir das dimensões fornecidas. A evidência desta competência aparece no processamento correto e na coerência entre os dados de entrada e os resultados numéricos obtidos.


## CT05.3

**Título da Competência**  
**Traduzir problemas quantitativos simples em algoritmos executáveis e verificáveis**

**Descrição Textual**  
Capacidade de interpretar um enunciado quantitativo simples, identificar seus elementos essenciais e convertê-lo em um algoritmo executável, com comportamento coerente e resultados tecnicamente verificáveis.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO4, LO5)
- K mobilizados (Núcleo): (K01, K02, K03)

**Especificação de Conhecimentos**
- **K01:** conceitos básicos de computação e resolução de problemas. **Justificativa de evidência:** a competência é evidenciada pela correta interpretação do problema como relação entre entradas, processamento e saídas.
- **K02:** algoritmos e formas de representação. **Justificativa de evidência:** a competência é evidenciada pela organização da solução em um procedimento finito, ordenado e executável.
- **K03:** estrutura sequencial, entrada, processamento e saída. **Justificativa de evidência:** a competência é evidenciada pela transformação do enunciado em fluxo computacional verificável.


**Alinhamento com a Taxonomia de Bloom**  
Predomina **Analisar**, pois a competência requer decompor o enunciado em elementos computacionais e relacionar problema, procedimento e resultado esperado.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → identificar no problema os elementos essenciais de entrada, processamento e saída.  
Verbos de Bloom: analisar, distinguir, relacionar

K02 / Analisar → converter a descrição textual do problema em uma sequência ordenada de ações computacionais.  
Verbos de Bloom: estruturar, decompor, examinar

K03 / Aplicar → materializar a solução algorítmica em fluxo sequencial observável no programa.  
Verbos de Bloom: executar, programar, operar

**Especificação de Disposições**
- atenção ao enunciado;
- consistência lógica na modelagem do problema;
- compromisso com a verificabilidade da solução.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT05.3 | Traduzir problemas quantitativos simples em algoritmos executáveis e verificáveis | atenção ao enunciado; consistência lógica na modelagem do problema; compromisso com a verificabilidade da solução | K01 | identificar no problema os elementos essenciais de entrada, processamento e saída |
| CT05.3 | Traduzir problemas quantitativos simples em algoritmos executáveis e verificáveis | atenção ao enunciado; consistência lógica na modelagem do problema; compromisso com a verificabilidade da solução | K02 | converter a descrição textual do problema em uma sequência ordenada de ações computacionais |
| CT05.3 | Traduzir problemas quantitativos simples em algoritmos executáveis e verificáveis | atenção ao enunciado; consistência lógica na modelagem do problema; compromisso com a verificabilidade da solução | K03 | materializar a solução algorítmica em fluxo sequencial observável no programa |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: antes de calcular, o estudante precisa interpretar o enunciado como problema computacional e estruturar uma solução coerente. A competência é ativada porque a tarefa exige converter uma descrição verbal simples em algoritmo executável e verificável.
