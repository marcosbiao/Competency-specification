# RELATÓRIO CSP — AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de Autoria de Competências do Competency Specification Process e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa introdutória de programação voltada à verificação de vogal em um caractere digitado. A atividade solicita leitura de entrada simples, comparação lógica, decisão condicional e apresentação de um resultado verificável, o que produz evidências observáveis no código, na saída e na justificativa breve do estudante.

A tarefa sustenta o modelo Conhecimento–Habilidade–Disposição porque mobiliza conhecimentos centrais do núcleo inicial da disciplina, exige habilidades tecnicamente observáveis e convoca disposições compatíveis com precisão, consistência lógica e clareza computacional. A modelagem a seguir prioriza rastreabilidade explícita, controle de granularidade e reuso em tarefas semelhantes da disciplina, sem criar conhecimentos fora do catálogo.

## 1. Análise da Entidade Instrucional

### Título

**Verificação de vogal em caractere digitado**

### Descrição

Trata-se de uma tarefa introdutória de programação em que o estudante deve ler um único caractere e classificá-lo como vogal ou não vogal, considerando letras maiúsculas e minúsculas. A evidência principal está na coerência entre entrada, regra de comparação, decisão computacional, saída produzida e justificativa breve do comportamento do programa.

### Processo de Desenvolvimento da Solução

1. Identificar o dado de entrada e o resultado esperado da classificação.
2. Representar computacionalmente o caractere lido e a resposta a ser produzida.
3. Organizar a solução segundo o fluxo de entrada, processamento e saída.
4. Formular a condição lógica que distingue vogais de demais caracteres.
5. Implementar a decisão condicional considerando maiúsculas e minúsculas.
6. Exibir o resultado final e justificá-lo de forma breve e coerente.

### Resultados Esperados

- código-fonte funcional com leitura, decisão condicional e saída;
- classificação explícita do caractere como vogal ou não vogal;
- coerência entre a regra implementada e o comportamento observado;
- justificativa breve explicando o critério de classificação adotado.

### Contexto de Aquisição

- **Título da Task:** Verificação de vogal em caractere digitado
- **Nível/Curso:** nível introdutório, Programação de Computadores I
- **Componente Curricular:** Programação de Computadores I
- **Contexto:** atividade individual, adequada a laboratório de programação ou avaliação prática inicial
- **Avaliação:** análise do código, da consistência da condição implementada, da saída produzida e da justificativa breve

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de aprendizagem de programação estruturada, com contato introdutório com entrada e saída, variáveis, comparações lógicas e estruturas condicionais. São estudantes que ainda consolidam a tradução de enunciados curtos em programas simples, verificáveis e tecnicamente coerentes.

### Nível de Proficiência (critérios e dimensões)

| Nível | Representação da entrada e da saída | Estrutura do fluxo computacional | Formulação da condição | Resultado e justificativa |
|---|---|---|---|---|
| **N1 — Inicial** | identifica parcialmente o dado de entrada ou o resultado esperado | organiza a solução de forma incompleta | não distingue corretamente os casos | apresenta saída inconsistente ou sem justificativa |
| **N2 — Intermediário** | representa entrada e saída com pequenas imprecisões | organiza parcialmente a sequência de leitura, processamento e saída | distingue os casos com fragilidades de comparação | apresenta resultado compreensível, mas justificativa limitada |
| **N3 — Proficiente** | representa entrada e saída de modo coerente com a tarefa | organiza corretamente o fluxo verificável do programa | formula corretamente a condição para classificar a entrada | apresenta resultado correto com justificativa breve adequada |
| **N4 — Avançado** | representa os dados com clareza técnica e sem ambiguidades | organiza o fluxo com precisão e alta legibilidade lógica | formula a decisão com precisão, estabilidade e cobertura completa | apresenta resultado correto com justificativa tecnicamente sólida e verificável |

## 2. Seleção e Enumeração de Conhecimentos 

### K01 — Conceitos básicos de computação e resolução de problemas

- compreensão da relação entre problema, dado de entrada, processamento e saída;
- identificação do programa como solução executável para uma regra simples de classificação;
- leitura da tarefa como transformação de uma entrada em um resultado observável.

**Justificativa de mobilização na tarefa:** a atividade exige reconhecer o problema computacional, delimitar a entrada e compreender que a solução deve produzir uma classificação verificável.

### K03 — Estrutura sequencial, entrada, processamento e saída

- organização do programa em uma sequência básica de leitura, processamento e exibição de resultado;
- encadeamento lógico entre o caractere recebido e a mensagem final produzida;
- compreensão do fluxo mínimo de execução em programas introdutórios.

**Justificativa de mobilização na tarefa:** a tarefa depende diretamente do fluxo de entrada do caractere, processamento da regra e apresentação do resultado ao usuário.

### K04 — Variáveis, constantes, tipos de dados e atribuição

- representação de dados simples por meio de variáveis adequadas ao problema;
- uso de identificadores para armazenar o valor lido e apoiar o processamento;
- coerência entre o papel do dado e seu uso ao longo da execução.

**Justificativa de mobilização na tarefa:** o estudante precisa manipular corretamente o dado de entrada e sustentar a decisão computacional a partir desse valor.

### K05 — Expressões aritméticas, relacionais e lógicas

- formulação de comparações que apoiam a tomada de decisão;
- interpretação de expressões relacionais e lógicas em problemas de classificação simples;
- composição de condições coerentes com a regra expressa no enunciado.

**Justificativa de mobilização na tarefa:** a classificação de um caractere como vogal ou não vogal depende de comparações e da formulação correta da condição lógica.

### K06 — Estruturas condicionais

- seleção entre caminhos alternativos de execução a partir de uma condição;
- tratamento de casos mutuamente excludentes em tarefas de classificação;
- produção de saídas distintas conforme o resultado da verificação.

**Justificativa de mobilização na tarefa:** a atividade solicita explicitamente uma verificação e, portanto, demanda decisão condicional para distinguir os dois resultados possíveis.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Representar computacionalmente dados simples de entrada e de saída de modo coerente com um problema introdutório de classificação.  
**K associados:** (K01, K04)

**LO2.** Organizar programas introdutórios segundo um fluxo verificável de entrada, processamento e saída.  
**K associados:** (K03, K04)

**LO3.** Formular condições relacionais e lógicas para distinguir categorias simples de dados em problemas de decisão.  
**K associados:** (K05, K06)

**LO4.** Implementar classificações condicionais considerando variações explicitamente previstas no enunciado.  
**K associados:** (K04, K05, K06)

**LO5.** Produzir saídas verificáveis e justificativas breves coerentes com a regra computacional implementada.  
**K associados:** (K01, K03, K06)

## 4. Definição de Competências

### 4.1 Competência Geral

**Desenvolver soluções introdutórias em programação estruturada para classificar entradas simples por meio de representação de dados, fluxo sequencial e decisão condicional verificável.**

### 4.2 Especificações de Competências

## Competência CT09.1

**Título da Competência**  
Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais

**Descrição Textual**  
Capacidade de construir programas introdutórios corretos em uma linguagem de programação, articulando representação de dados, sequência básica de execução e correspondência entre o que foi solicitado e o comportamento efetivamente produzido.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO5)
- K mobilizados (Núcleo): (K03, K04)

**Especificação de Conhecimentos**
- **K03:** organiza a solução em sequência verificável de leitura, processamento e saída. **Justificativa de evidência:** o fluxo pode ser observado diretamente no artefato executável e na ordem lógica da solução.
- **K04:** representa e manipula o dado simples de entrada de forma compatível com a tarefa. **Justificativa de evidência:** o uso do dado lido é diretamente observável nas atribuições e no processamento subsequente.

**Alinhamento com a Taxonomia de Bloom**

Predomina **Aplicar**, pois a competência requer uso operacional de estrutura sequencial e representação de dados em um programa executável simples.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → estruturar o fluxo de entrada, processamento e saída de modo verificável em programas introdutórios.  
Verbos de Bloom: organizar, executar, programar

K04 / Aplicar → representar e utilizar dados simples em variáveis coerentes com o papel computacional de cada elemento.  
Verbos de Bloom: implementar, manipular, usar


**Especificação de Disposições**  
- precisão na representação dos dados;
- atenção à sintaxe e ao comportamento do programa;
- clareza na apresentação do resultado.


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT09.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão na representação dos dados; atenção à sintaxe e ao comportamento do programa; clareza na apresentação do resultado | K03 | estruturar o fluxo de entrada, processamento e saída de modo verificável em programas introdutórios |
| CT09.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão na representação dos dados; atenção à sintaxe e ao comportamento do programa; clareza na apresentação do resultado | K04 | representar e utilizar dados simples em variáveis coerentes com o papel computacional de cada elemento |


**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade exige a construção de um programa elementar funcional. A competência é ativada porque o estudante precisa transformar uma regra simples em um artefato executável sintaticamente válido e semanticamente coerente.

## Competência CT09.2

**Título da Competência**  
Realizar entrada e saída de dados simples com correspondência entre leitura e resultado apresentado

**Descrição Textual**  
Capacidade de receber dados elementares do usuário e apresentar resultados de forma coerente, mantendo correspondência verificável entre a entrada processada e a saída produzida.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO5)
- K mobilizados (Núcleo): (K03, K04)

**Especificação de Conhecimentos**
- **K03:** estabelece o encadeamento funcional entre leitura, processamento e apresentação do resultado. **Justificativa de evidência:** a correção da solução depende da sequência observável entre entrada recebida e resposta produzida.
- **K04:** utiliza o dado armazenado de forma consistente ao longo da execução. **Justificativa de evidência:** o valor lido precisa ser mantido e empregado corretamente até a produção da saída.

**Alinhamento com a Taxonomia de Bloom**

Predomina **Aplicar**, pois a competência envolve executar corretamente operações introdutórias de entrada e saída em um programa simples.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → realizar leitura, processamento e exibição de resultados em sequência funcional e verificável.  
Verbos de Bloom: executar, realizar, programar

K04 / Aplicar → utilizar o dado lido de forma consistente até a geração da resposta final.  
Verbos de Bloom: manipular, operar, usar

**Especificação de Disposições**  
- atenção à leitura correta do dado;
- clareza na comunicação do resultado;
- consistência entre entrada e saída.


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT09.2 | Realizar entrada e saída de dados simples com correspondência entre leitura e resultado apresentado | atenção à leitura correta do dado; clareza na comunicação do resultado; consistência entre entrada e saída | K03 | realizar leitura, processamento e exibição de resultados em sequência funcional e verificável |
| CT09.2 | Realizar entrada e saída de dados simples com correspondência entre leitura e resultado apresentado | atenção à leitura correta do dado; clareza na comunicação do resultado; consistência entre entrada e saída | K04 | utilizar o dado lido de forma consistente até a geração da resposta final |


**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade demanda leitura de um único caractere e apresentação explícita da classificação final. A competência é ativada porque a evidência observável depende da correspondência entre o dado lido e a resposta exibida.

## Competência CT09.3

**Título da Competência**  
Controlar o fluxo com decisões simples (if/else), formulando expressões lógicas corretas

**Descrição Textual (reutilizável; não específica do enunciado)**  
Capacidade de traduzir regras expressas em linguagem natural para expressões lógicas corretas e empregá-las em decisões condicionais simples, distinguindo caminhos alternativos de execução em programas introdutórios.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3, LO4, LO5)
- K mobilizados (Núcleo): (K05, K06)

**Especificação de Conhecimentos**
- **K05:** formula comparações e relações lógicas coerentes com a regra do problema. **Justificativa de evidência:** a correção da condição pode ser verificada diretamente no comportamento de classificação do programa.
- **K06:** seleciona caminhos alternativos de execução de forma consistente. **Justificativa de evidência:** a saída distinta para cada caso revela se a estrutura condicional foi implementada adequadamente.

**Alinhamento com a Taxonomia de Bloom (revisada)**

Predomina **Aplicar**, pois a competência exige converter uma regra explícita em condição lógica operável e utilizá-la corretamente em uma decisão computacional simples.

**Pareamento Conhecimento–Habilidade**

K05 / Aplicar → formular expressões relacionais e lógicas corretas para classificar entradas simples.  
Verbos de Bloom: aplicar, construir, operar

K06 / Aplicar → implementar decisões condicionais simples que conduzam a saídas distintas e verificáveis.  
Verbos de Bloom: implementar, programar, resolver


**Especificação de Disposições**  
- consistência lógica;
- atenção às regras do problema;
- rigor na distinção entre casos.


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT09.3 | Controlar o fluxo com decisões simples (if/else), formulando expressões lógicas corretas | consistência lógica; atenção às regras do problema; rigor na distinção entre casos | K05 | formular expressões relacionais e lógicas corretas para classificar entradas simples |
| CT09.3 | Controlar o fluxo com decisões simples (if/else), formulando expressões lógicas corretas | consistência lógica; atenção às regras do problema; rigor na distinção entre casos | K06 | implementar decisões condicionais simples que conduzam a saídas distintas e verificáveis |


**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o núcleo lógico da atividade está na classificação do caractere com base em uma condição explícita. A competência é ativada porque o estudante precisa formular corretamente a expressão lógica e vinculá-la ao desvio condicional adequado.
