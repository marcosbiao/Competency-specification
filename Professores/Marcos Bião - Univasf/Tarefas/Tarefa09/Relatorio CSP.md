# RELATÓRIO CSP — AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa a tarefa na fase de **Autoria de Competências** do CSP, com foco na identificação de conhecimentos, objetivos de aprendizagem e competências mobilizados por uma atividade introdutória de programação em C. A tarefa solicita a construção de um programa que leia um valor `N` e calcule a soma dos `N` primeiros termos de uma série numérica definida no enunciado.

A atividade produz evidências observáveis e verificáveis porque exige um artefato computacional executável, com entrada, processamento e saída explícitos. Do ponto de vista do modelo **Conhecimento–Habilidade–Disposição**, a tarefa mobiliza conhecimentos centrais de Computação ligados à representação de dados, expressões aritméticas, estrutura sequencial e repetição. O recorte adotado privilegia reuso, rastreabilidade e baixa redundância, concentrando a especificação apenas nos conhecimentos efetivamente sustentados pelo catálogo da disciplina.

## 1. Análise da Entidade Instrucional

### Título

Soma dos N primeiros termos de uma série em C

### Descrição

A tarefa propõe a implementação de um programa em linguagem C que receba um valor inteiro `N` e calcule a soma dos `N` primeiros termos de uma série numérica apresentada no enunciado. A evidência principal é a produção de um programa funcional capaz de organizar leitura de entrada, processamento iterativo e exibição do resultado final. Trata-se de uma atividade típica de programação introdutória, centrada na tradução de um padrão numérico em comportamento computacional verificável.

### Processo de Desenvolvimento da Solução

1. Identificar a entrada requerida e o resultado esperado.
2. Definir os dados que precisam ser representados durante a execução.
3. Organizar a sequência de leitura, processamento e saída.
4. Implementar um mecanismo de repetição compatível com a quantidade de termos solicitada.
5. Atualizar o valor acumulado ao longo do processamento.
6. Exibir o resultado final de forma verificável.

### Resultados Esperados

1. Programa em C com leitura do valor `N`.
2. Processamento da soma dos `N` primeiros termos da série.
3. Exibição do resultado final calculado.
4. Justificativa breve e coerente sobre a aderência da solução ao enunciado.

## Contexto de Aquisição

- **Curso:** Ciência da Computação
- **Nível:** Graduação, 1º semestre
- **Componente Curricular:** Introdução à Programação
- **Organização da atividade:** individual
- **Ambiente provável:** laboratório de programação ou atividade prática equivalente
- **Forma de avaliação:** análise do código, da saída produzida e da justificativa breve

## Perfil do Público-Alvo

Estudantes iniciantes em programação, em fase de consolidação de noções de entrada e saída, variáveis, tipos primitivos, expressões lógicas e estruturas de seleção. Pressupõe-se familiaridade inicial com sintaxe básica em C e com problemas que exigem transformar regras verbais em comportamento observável do programa. As necessidades centrais do público incluem apoio à leitura técnica do enunciado, organização de casos e implementação consistente de decisões condicionais.

### Nível de Proficiência (critérios e dimensões)

| Nível de proficiência | Representação dos dados | Controle iterativo | Cálculo e atualização | Estrutura do programa | Verificabilidade |
|---|---|---|---|---|---|
| **N1 - Inicial** | Identifica apenas parte dos dados necessários e ainda apresenta instabilidade na escolha de tipos | Usa repetição com falhas de contagem ou de parada | Realiza apenas parte do processamento esperado | Organiza o fluxo de forma incompleta | Apresenta resultado pouco interpretável ou sem justificativa coerente |
| **N2 - Intermediário** | Representa os dados principais, mas com pequenas inconsistências | Usa repetição funcional, embora com controle pouco robusto | Atualiza valores com coerência parcial | Organiza um fluxo funcional, porém pouco claro | Apresenta resultado visível com justificativa mínima |
| **N3 - Proficiente** | Representa corretamente entrada, acumulador e variáveis auxiliares | Implementa repetição compatível com `N` e com parada segura | Calcula e acumula os termos de forma correta ao longo das iterações | Organiza fluxo completo e coerente de entrada, processamento e saída | Produz resultado verificável com justificativa coerente |
| **N4 - Avançado** | Representa os dados com clareza, consistência e sem redundâncias | Implementa repetição consistente, clara e facilmente verificável | Mantém cálculo e acumulação corretos com processamento estável | Estrutura o programa de forma tecnicamente clara e bem organizada | Produz artefato facilmente inspecionável, com justificativa técnica consistente |

## 2. Seleção e Enumeração de Conhecimentos 

### K01 — Modelo de execução e noção de estado (paradigma imperativo)

1. Compreensão de que o programa evolui por mudanças sucessivas de estado durante a execução.
2. Relação entre atribuição, atualização de variáveis e efeito da ordem de execução.
3. Leitura operacional do comportamento do programa em processamento iterativo.

**Justificativa de mobilização na tarefa:** a soma parcial da série exige acompanhar o estado do programa ao longo das iterações, especialmente no uso de contador e acumulador.

### K02 — Variáveis, constantes e tipos primitivos

1. Representação de dados simples por identificadores e tipos adequados.
2. Uso coerente de variáveis, constantes e atribuições em cálculos básicos.
3. Escolha de tipos numéricos compatíveis com o papel de cada dado.

**Justificativa de mobilização na tarefa:** a entrada, os valores intermediários e o resultado final precisam ser representados com tipos numéricos coerentes.

### K03 — Expressões aritméticas e avaliação

1. Construção de expressões aritméticas com operadores e precedência.
2. Avaliação correta de cálculos parciais.
3. Atualização de resultados por expressões consistentes.

**Justificativa de mobilização na tarefa:** o cálculo dos termos da série e da soma acumulada depende diretamente de expressões aritméticas corretas.

### K05 — Estrutura sequencial e E/S básica

1. Organização do programa como sequência de comandos.
2. Encadeamento entre leitura, processamento e exibição de resultados.
3. Produção de saídas observáveis e verificáveis.

**Justificativa de mobilização na tarefa:** o enunciado exige leitura de `N`, processamento da soma e apresentação do resultado final.

### K07 — Estruturas de repetição

1. Execução repetida de comandos controlada por contador ou condição.
2. Definição de parada compatível com a finalidade do problema.
3. Processamento acumulativo e iterativo coerente.

**Justificativa de mobilização na tarefa:** a tarefa requer considerar exatamente os `N` primeiros termos da série, o que torna a repetição central na solução.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Representar os dados necessários ao problema em variáveis e tipos primitivos compatíveis com o cálculo solicitado.

**K associados:** K02, K05

### LO2

Avaliar expressões aritméticas coerentes com o padrão da série para calcular termos e atualizar a soma parcial.

**K associados:** K02, K03

### LO3

Controlar o processamento iterativo por contagem, acompanhando o estado do programa ao longo das atualizações sucessivas.

**K associados:** K01, K07

### LO4

Implementar um programa em C com fluxo verificável de entrada, processamento e saída para produzir o resultado final.

**K associados:** K02, K05, K07

## 4. Definição de Competências

### 4.1 Competência Geral

Construir soluções computacionais introdutórias em linguagem C para problemas numéricos bem definidos, articulando representação de dados, processamento iterativo e produção de resultados verificáveis.

**BNCC:** não aplicável nesta tarefa.

### 4.2 Especificações de Competências

## CT04.1

**Título da Competência**  
Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais

**Descrição Textual**  
Implementar programas introdutórios em C com fluxo coerente de entrada, processamento e saída, compreendendo a função semântica das instruções básicas e sua organização no comportamento do programa.

**Cobertura e rastreabilidade**  
LOs cobertos: LO1, LO4  
K mobilizados (Núcleo): K02, K05

**Especificação de Conhecimentos**

K02  
Descrição curta: representação de dados simples por variáveis, constantes e tipos primitivos adequados.  
Justificativa de evidência: a tarefa evidencia diretamente a declaração e o uso de dados numéricos coerentes com entrada e resultado.

K05  
Descrição curta: organização do programa em fluxo de entrada, processamento e saída.  
Justificativa de evidência: a tarefa exige explicitamente leitura de `N`, cálculo da soma e exibição do resultado.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Criar

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar e utilizar variáveis numéricas compatíveis com a entrada e com o resultado do programa.  
Verbos de Bloom: aplicar, usar, manipular

K05 / Criar → construir um fluxo verificável de entrada, processamento e saída em um programa básico em C.  
Verbos de Bloom: construir, programar, desenvolver


**Especificação de Disposições**

1. Organização lógica da solução.
2. Clareza na relação entre entrada e saída.
3. Atenção à consistência estrutural do programa.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT04.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | organização lógica; clareza; consistência estrutural | K02 | declarar e utilizar variáveis numéricas compatíveis com a entrada e com o resultado do programa |
| CT04.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | organização lógica; clareza; consistência estrutural | K05 | construir um fluxo verificável de entrada, processamento e saída em um programa básico em C |

**Definição de Ativação**

Restrição de ativação: obrigatória  
Modo de ativação: construtiva  
Função de ativação: núcleo  
Justificativa: a tarefa exige a implementação completa de um programa em C. Por isso, a organização estrutural do artefato e o uso funcional de variáveis e E/S são evidências centrais da competência.

## CT04.2

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples

**Descrição Textual**  
Manipular dados numéricos em programas introdutórios, selecionando tipos primitivos adequados e avaliando expressões aritméticas coerentes com o comportamento esperado do problema.

**Cobertura e rastreabilidade**  
LOs cobertos: LO1, LO2  
K mobilizados (Núcleo): K02, K03

**Especificação de Conhecimentos**

K02  
Descrição curta: uso de identificadores e tipos simples para armazenar e processar dados.  
Justificativa de evidência: o problema requer representação numérica adequada para a quantidade de termos e para a soma parcial.

K03  
Descrição curta: construção e avaliação de expressões aritméticas com operadores e precedência.  
Justificativa de evidência: a tarefa evidencia diretamente o cálculo dos termos e a atualização da soma.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → manipular variáveis e constantes numéricas compatíveis com o cálculo da soma parcial.  
Verbos de Bloom: aplicar, manipular, usar

K03 / Aplicar → calcular termos e atualizar resultados parciais por meio de expressões aritméticas consistentes.  
Verbos de Bloom: calcular, computar, resolver


**Especificação de Disposições**

1. Precisão no tratamento de dados numéricos.
2. Atenção à coerência entre tipos e operações.
3. Cuidado com a consistência dos resultados parciais.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT04.2 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples | precisão; coerência; consistência numérica | K02 | manipular variáveis e constantes numéricas compatíveis com o cálculo da soma parcial |
| CT04.2 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples | precisão; coerência; consistência numérica | K03 | calcular termos e atualizar resultados parciais por meio de expressões aritméticas consistentes |

**Definição de Ativação**

Restrição de ativação: obrigatória  
Modo de ativação: construtiva  
Função de ativação: núcleo  
Justificativa: a tarefa depende diretamente da representação correta dos dados e do cálculo dos termos da série. Essas evidências aparecem de forma explícita no processamento numérico implementado.

## CT04.3

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras

**Descrição Textual**  
Controlar processamento iterativo em programas introdutórios, utilizando repetição por contagem, atualização progressiva de estado e mecanismos de parada compatíveis com a finalidade do problema.

**Cobertura e rastreabilidade**  
LOs cobertos: LO2, LO3, LO4  
K mobilizados (Núcleo): K01, K03, K07

**Especificação de Conhecimentos**

K01  
Descrição curta: compreensão de que o programa evolui por atualizações sucessivas de estado.  
Justificativa de evidência: a tarefa exige acompanhar contador, termo corrente e acumulador ao longo das iterações.

K03  
Descrição curta: composição de cálculos necessários para atualização iterativa.  
Justificativa de evidência: cada repetição exige recalcular valores e atualizar a soma.

K07  
Descrição curta: execução repetida de comandos com controle por contagem e parada.  
Justificativa de evidência: o problema requer considerar exatamente os `N` primeiros termos da série.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → explicitar o estado do programa por meio do acompanhamento coerente de contador, termo e acumulador durante a execução.  
Verbos de Bloom: analisar, relacionar, rastrear

K03 / Aplicar → computar as atualizações aritméticas necessárias ao processamento de cada iteração.  
Verbos de Bloom: calcular, computar, operar

K07 / Aplicar → implementar repetição por contagem com parada segura e acumulação consistente dos resultados parciais.  
Verbos de Bloom: implementar, iterar, executar


**Especificação de Disposições**

1. Rigor no controle de contagem.
2. Atenção à atualização progressiva do estado.
3. Cuidado com a condição de parada e com a estabilidade do processamento.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT04.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | rigor; atenção; cuidado com estabilidade | K01 | explicitar o estado do programa por meio do acompanhamento coerente de contador, termo e acumulador durante a execução |
| CT04.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | rigor; atenção; cuidado com estabilidade | K03 | computar as atualizações aritméticas necessárias ao processamento de cada iteração |
| CT04.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | rigor; atenção; cuidado com estabilidade | K07 | implementar repetição por contagem com parada segura e acumulação consistente dos resultados parciais |

**Definição de Ativação**

Restrição de ativação: obrigatória  
Modo de ativação: construtiva  
Função de ativação: núcleo  
Justificativa: o cálculo solicitado depende diretamente de repetição controlada por quantidade de termos, com atualização iterativa do acumulador. A evidência dessa competência aparece no comportamento funcional do programa.
