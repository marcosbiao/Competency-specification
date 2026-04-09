# RELATÓRIO CSP — Autoria de Competências

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do **Competency Specification Process (CSP)** e tem por finalidade explicitar, com rastreabilidade, os conhecimentos, objetivos de aprendizagem e competências mobilizados pela TASK04. A tarefa solicita a implementação de um programa capaz de ler três números inteiros e apresentá-los em ordem crescente, exigindo ainda duas formas distintas de implementação para o mesmo problema.

A atividade elicita evidências observáveis porque demanda artefatos verificáveis, como código-fonte, saídas produzidas, testes com diferentes entradas e justificativa breve sobre a distinção entre as implementações. Trata-se, portanto, de uma entidade instrucional adequada para análise no modelo K–S–D, pois mobiliza conhecimentos de dados, estado, fluxo sequencial, condições e seleção, sem exigir expansão indevida do escopo do catálogo da disciplina.

## 1. Análise da Entidade Instrucional

### Título

Ordenação crescente de três números inteiros em duas implementações

### Descrição

A tarefa requer que o estudante leia três valores inteiros, compare esses valores e produza uma saída ordenada do menor para o maior. Além da correção funcional, a proposta exige duas implementações distintas, o que amplia a evidência de domínio conceitual e reduz a chance de reprodução mecânica de um único padrão de solução.

### Processo de Desenvolvimento da Solução

1. Interpretar o problema e identificar entrada, processamento e saída.
2. Definir uma primeira estratégia de ordenação compatível com programação introdutória.
3. Definir uma segunda estratégia, distinta da primeira, preservando a mesma especificação funcional.
4. Implementar as duas versões com coerência de tipos, variáveis e fluxo de controle.
5. Testar casos representativos, incluindo valores repetidos e negativos.
6. Registrar brevemente o que diferencia as duas implementações.

### Resultados Esperados

1. Código-fonte contendo duas implementações corretas da ordenação.
2. Saídas verificáveis para entradas de teste.
3. Evidência de que ambas as implementações produzem o mesmo resultado para a mesma entrada.
4. Justificativa breve e tecnicamente coerente sobre a diferença entre as estratégias adotadas.

### Contexto de Aquisição (curso, organização, ambiente, avaliação)

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### Perfil do Público-Alvo (nível, pré-requisitos, necessidades)

Trata-se de público em fase inicial de formação em programação, já familiarizado com leitura e escrita de dados, tipos inteiros e organização sequencial básica de programas. A tarefa é adequada para estudantes em transição do uso de estruturas estritamente sequenciais para o emprego sistemático de condições e seleção. As necessidades formativas centrais concentram-se na cobertura de casos, na consistência do estado do programa e na equivalência funcional entre diferentes implementações.

### Nível de Proficiência (critérios e dimensões)

| Nível | Leitura da especificação | Uso de condições e seleção | Consistência do estado do programa | Verificabilidade da solução |
|---|---|---|---|---|
| **N1 – Inicial** | identifica parcialmente entrada e saída | constrói condições incompletas ou frágeis | atualizações incoerentes ou perda de valores | apresenta pouca evidência de teste |
| **N2 – Intermediário** | identifica corretamente a especificação e a ordem requerida | usa seleção para ordenar os valores com cobertura básica dos casos | mantém coerência das variáveis durante a ordenação | apresenta saídas compatíveis e algum teste representativo |
| **N3 – Proficiente** | interpreta também casos de repetição e equivalência entre versões | organiza a seleção com clareza e sem lacunas relevantes | preserva integralmente o estado e evita redundâncias | demonstra equivalência funcional entre as duas implementações |
| **N4 – Avançado** | antecipa restrições, compara estratégias e justifica decisões com precisão | otimiza a estrutura decisória e explicita critérios de projeto | produz solução robusta, clara e tecnicamente econômica | justifica comparativamente as implementações com elevada clareza técnica |

## 2. Seleção e Enumeração de Conhecimentos

### K01 — Modelo de execução e noção de estado (paradigma imperativo)

1. Compreensão de que o programa evolui por mudanças de estado ao longo da execução.
2. Interpretação de atribuições e atualizações de variáveis como transições de estado.
3. Leitura operacional do fluxo de comandos em uma solução imperativa introdutória.

**Justificativa de mobilização na tarefa:** a ordenação exige preservar e reorganizar valores sem perda de informação, o que depende de controle do estado do programa durante comparações e possíveis reatribuições.

### K02 — Variáveis, constantes e tipos primitivos

1. Representação de dados simples por variáveis tipadas.
2. Uso coerente de inteiros e identificadores para armazenar e manipular valores.
3. Consistência entre papel do dado e sua utilização no programa.

**Justificativa de mobilização na tarefa:** a tarefa trabalha explicitamente com três números inteiros lidos do teclado, exigindo declaração, armazenamento e manipulação coerente desses valores.

### K04 — Expressões lógicas e condições

1. Construção de comparações relacionais entre valores.
2. Composição de condições para tomada de decisão.
3. Interpretação correta de verdade e falsidade no controle do fluxo.

**Justificativa de mobilização na tarefa:** ordenar valores requer estabelecer relações de ordem e decidir, com base em condições, qual valor deve aparecer antes ou depois na saída.

### K05 — Estrutura sequencial e E/S básica

1. Organização do fluxo entrada, processamento e saída.
2. Leitura de dados e apresentação de resultados de forma verificável.
3. Encadeamento coerente de comandos em programa simples.

**Justificativa de mobilização na tarefa:** a atividade exige leitura via teclado e saída ordenada clara, de modo que a estrutura sequencial e a E/S básica são evidências centrais do artefato.

### K06 — Estruturas de seleção

1. Emprego de caminhos alternativos de execução com base em condições.
2. Cobertura de casos por encadeamento ou aninhamento de decisões.
3. Relação entre regra do problema e ramo executado.

**Justificativa de mobilização na tarefa:** a ordenação de três valores em programação introdutória é diretamente apoiada por estruturas de seleção para distinguir e tratar os diferentes arranjos possíveis.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Manipular dados inteiros em programas introdutórios, preservando coerência entre variáveis, estado do programa e resultado produzido.

**K associados:** K01, K02

### LO2

Controlar o fluxo de execução com condições e estruturas de seleção adequadas ao problema.

**K associados:** K04, K06

### LO3

Estruturar programas simples com leitura, processamento e saída verificáveis.

**K associados:** K02, K05

### LO4

Comparar implementações distintas para uma mesma especificação e justificar a adequação da estratégia adotada.

**K associados:** K01, K05, K06

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver soluções computacionais introdutórias que transformem dados de entrada em saídas verificáveis, com uso coerente de variáveis, condições, seleção e controle do estado do programa.

**BNCC:** não aplicável neste relatório, pois a tarefa está situada em componente curricular de ensino superior.

### 4.2 Especificações de Competências

## CT04.1

**Título da Competência**  
Controlar o fluxo com decisões, formulando expressões lógicas corretas

**Descrição Textual**  
Controlar a execução de programas introdutórios por meio de condições logicamente corretas e estruturas de seleção coerentes com as relações de ordem e com os casos previstos no problema.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO2, LO3
2. K mobilizados (Núcleo): K04, K06, K05

**Especificação de Conhecimentos**
1. **K04:** formulação de comparações e condições coerentes; a evidência aparece na correção lógica dos testes que orientam a ordenação.
2. **K06:** uso de decisões encadeadas ou aninhadas para tratar os casos relevantes; a evidência aparece na seleção correta dos ramos de execução.
3. **K05:** organização do fluxo de entrada, processamento e saída; a evidência aparece na apresentação verificável do resultado após a decisão.

**Alinhamento com a Taxonomia de Bloom**  
Predomina o nível **Aplicar**, pois o estudante precisa empregar expressões lógicas e estruturas de seleção para construir uma solução funcional que satisfaça a especificação do problema.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → formular expressões lógicas corretas para comparar valores e definir a ordem de apresentação.  
Verbos de Bloom: aplicar, implementar, usar

K06 / Aplicar → controlar o fluxo do programa com estruturas de seleção coerentes com os casos previstos.  
Verbos de Bloom: construir, executar, programar

K05 / Aplicar → organizar a sequência de entrada, processamento e saída de forma verificável.  
Verbos de Bloom: implementar, operar, resolver


**Especificação de Disposições**  
1. Precisão na formulação das condições.
2. Atenção à cobertura dos casos relevantes.
3. Compromisso com a verificabilidade do comportamento do programa.

**Competências Alinhadas à BNCC**  
Não aplicável neste contexto.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT04.1 | Controlar o fluxo com decisões, formulando expressões lógicas corretas | precisão; cobertura de casos; verificabilidade | K04 | formular expressões lógicas corretas para comparar valores e definir a ordem de apresentação |
| CT04.1 | Controlar o fluxo com decisões, formulando expressões lógicas corretas | precisão; cobertura de casos; verificabilidade | K06 | controlar o fluxo do programa com estruturas de seleção coerentes com os casos previstos |
| CT04.1 | Controlar o fluxo com decisões, formulando expressões lógicas corretas | precisão; cobertura de casos; verificabilidade | K05 | organizar a sequência de entrada, processamento e saída de forma verificável |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a tarefa exige que o estudante produza uma ordenação correta com base em comparações entre valores. Isso torna indispensável o uso de condições corretas e de uma seleção consistente para gerar a saída esperada.

## CT04.2

**Título da Competência**  
Selecionar estruturas adequadas ao problema e justificar as escolhas

**Descrição Textual**  
Selecionar, entre diferentes possibilidades de organização da solução, estruturas computacionais adequadas ao problema e justificar sua escolha com base no comportamento observado da implementação.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO2, LO4
2. K mobilizados (Núcleo): K06, K01, K05

**Especificação de Conhecimentos**
1. **K06:** seleção de estruturas decisórias adequadas ao tratamento dos casos; a evidência aparece na distinção funcional entre as duas implementações.
2. **K01:** compreensão do estado do programa ao longo da execução; a evidência aparece na explicação de como cada estratégia conduz ao mesmo resultado.
3. **K05:** verificabilidade do comportamento da solução; a evidência aparece na comparação entre entradas e saídas produzidas pelas implementações.

**Alinhamento com a Taxonomia de Bloom**  
Predomina o nível **Avaliar**, pois a tarefa não exige apenas implementar, mas também justificar a adequação de duas estratégias distintas para a mesma especificação.

**Pareamento Conhecimento–Habilidade**

K06 / Avaliar → escolher estruturas de seleção adequadas ao problema e justificar sua pertinência em relação aos casos tratados.  
Verbos de Bloom: escolher, justificar, validar

K01 / Analisar → relacionar o comportamento das implementações ao estado do programa para explicar sua equivalência funcional.  
Verbos de Bloom: analisar, examinar, rastrear

K05 / Analisar → verificar entradas e saídas das implementações para sustentar a justificativa da escolha realizada.  
Verbos de Bloom: examinar, estruturar, distinguir

**Especificação de Disposições**  
1. Critério técnico na escolha da estrutura.
2. Clareza ao justificar a solução adotada.
3. Atenção a evidências observáveis do comportamento do programa.

**Competências Alinhadas à BNCC**  
Não aplicável neste contexto.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT04.2 | Selecionar estruturas adequadas ao problema e justificar as escolhas | critério técnico; clareza; evidência observável | K06 | escolher estruturas de seleção adequadas ao problema e justificar sua pertinência em relação aos casos tratados |
| CT04.2 | Selecionar estruturas adequadas ao problema e justificar as escolhas | critério técnico; clareza; evidência observável | K01 | relacionar o comportamento das implementações ao estado do programa para explicar sua equivalência funcional |
| CT04.2 | Selecionar estruturas adequadas ao problema e justificar as escolhas | critério técnico; clareza; evidência observável | K05 | verificar entradas e saídas das implementações para sustentar a justificativa da escolha realizada |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: justificatória
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: como a atividade exige duas implementações diferentes, não basta produzir código correto. O estudante também precisa justificar a adequação da organização escolhida e demonstrar equivalência funcional entre as soluções.

## CT04.3

**Título da Competência**  
Manipular dados com tipos primitivos e variáveis, preservando a coerência do estado do programa

**Descrição Textual**  
Manipular dados simples em programas imperativos introdutórios, mantendo coerência entre tipos, variáveis, atualizações de estado e resultado final produzido.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO1, LO3
2. K mobilizados (Núcleo): K02, K01, K05

**Especificação de Conhecimentos**
1. **K02:** representação dos dados por variáveis inteiras coerentes com o problema; a evidência aparece na declaração e no uso correto dos valores lidos.
2. **K01:** manutenção do estado do programa durante o processamento; a evidência aparece na preservação dos dados ao longo da ordenação.
3. **K05:** fluxo observável entre leitura, processamento e saída; a evidência aparece na consistência entre os dados recebidos e o resultado exibido.

**Alinhamento com a Taxonomia de Bloom**  
Predomina o nível **Aplicar**, pois o estudante precisa utilizar tipos primitivos, variáveis e atualizações de estado para construir uma solução funcional e verificável.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → manipular variáveis inteiras compatíveis com o papel de cada dado na solução.  
Verbos de Bloom: aplicar, implementar, manipular

K01 / Aplicar → preservar a coerência do estado do programa durante comparações e reatribuições.  
Verbos de Bloom: executar, operar, resolver

K05 / Aplicar → produzir uma saída verificável consistente com os dados lidos e o processamento realizado.  
Verbos de Bloom: implementar, operar, programar


**Especificação de Disposições**  
1. Cuidado com a preservação dos dados.
2. Atenção à consistência do processamento.
3. Rigor na conferência do resultado final.

**Competências Alinhadas à BNCC**  
Não aplicável neste contexto.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT04.3 | Manipular dados com tipos primitivos e variáveis, preservando a coerência do estado do programa | preservação de dados; consistência; rigor | K02 | manipular variáveis inteiras compatíveis com o papel de cada dado na solução |
| CT04.3 | Manipular dados com tipos primitivos e variáveis, preservando a coerência do estado do programa | preservação de dados; consistência; rigor | K01 | preservar a coerência do estado do programa durante comparações e reatribuições |
| CT04.3 | Manipular dados com tipos primitivos e variáveis, preservando a coerência do estado do programa | preservação de dados; consistência; rigor | K05 | produzir uma saída verificável consistente com os dados lidos e o processamento realizado |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a atividade depende da leitura, armazenamento e reorganização correta de três valores inteiros. Qualquer incoerência de tipo, variável ou estado compromete diretamente a ordenação produzida.
