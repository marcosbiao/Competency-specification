# RELATÓRIO CSP — Autoria de Competências

## Introdução

Este relatório situa a TASK15 na fase de **Autoria de Competências** do CSP, com foco na explicitação rastreável de conhecimentos, objetivos de aprendizagem e competências mobilizados pela tarefa. A atividade solicita a construção de um algoritmo que leia uma quantidade inicial de entradas, processe sucessivamente valores numéricos e delegue o cálculo do fatorial a uma função específica.

A tarefa produz evidências observáveis porque exige um artefato executável ou pseudocódigo verificável, no qual se pode inspecionar a leitura dos dados, o controle de repetição, a organização do fluxo principal e a modularização do cálculo em subprograma. Além disso, a breve justificativa esperada permite observar se o estudante compreende o papel da função na estrutura da solução.

A tarefa sustenta o modelo **K–S–D** sem redundância porque mobiliza um conjunto limitado, porém articulado, de conhecimentos da disciplina. O núcleo de evidência está na combinação entre leitura e saída, repetição por contagem, atualização de estado em cálculo iterativo e uso de função com parâmetros e retorno.


## 1. Análise da Entidade Instrucional

### Título

Cálculo de fatoriais por função com múltiplas entradas

### Descrição

A entidade instrucional propõe a construção de uma solução algorítmica que processe uma sequência finita de valores numéricos a partir de uma quantidade inicial `n`. Para cada valor lido, o estudante deve obter o respectivo fatorial, obrigatoriamente por meio de uma função. A tarefa mobiliza organização sequencial, repetição controlada, cálculo aritmético e decomposição funcional.

### Processo de Desenvolvimento da Solução (em etapas)

1. Ler o valor inicial que representa a quantidade de entradas a serem processadas.  
2. Organizar o fluxo principal para executar a leitura dos valores subsequentes em quantidade compatível com `n`.  
3. Encapsular o cálculo do fatorial em uma função com responsabilidade específica.  
4. Invocar a função para cada valor lido e associar cada entrada ao respectivo resultado.  
5. Exibir as saídas de forma consistente e verificável, preservando correspondência entre entradas e resultados.

### Resultados Esperados

1. Algoritmo, pseudocódigo ou programa funcional que resolva a tarefa.  
2. Função explicitamente responsável pelo cálculo do fatorial.  
3. Processamento repetitivo compatível com a quantidade de valores informada.  
4. Saídas coerentes com as entradas lidas.  
5. Justificativa breve sobre a organização da solução e o papel da função.

### Contexto de Aquisição

**Curso:** Introdução à Programação  
**Organização:** atividade individual  
**Ambiente:** laboratório de informática ou avaliação prática escrita  
**Avaliação:** observação direta do artefato produzido, das saídas obtidas e da justificativa breve associada à solução

### Perfil do Público-Alvo

Estudantes em fase inicial de aprendizagem em programação imperativa, com contato prévio ou em consolidação de noções de variáveis, expressões aritméticas, leitura e saída básicas. A tarefa é apropriada para aprendizes que já conseguem acompanhar fluxo sequencial simples e precisam avançar na integração entre repetição e subprogramas.

### Nível de Proficiência (critérios e dimensões)

| Nível | Estrutura do fluxo principal | Controle de repetição | Uso de função | Correção e verificabilidade |
|---|---|---|---|---|
| **N1 - Inicial** | organiza parcialmente a leitura e a saída, com inconsistências no encadeamento das etapas | utiliza repetição de modo incompleto ou com controle frágil da quantidade de entradas | ausente ou sem separação clara de responsabilidade | produz resultados parciais ou pouco verificáveis |
| **N2 - Intermediário** | estrutura leitura, processamento e saída com pequenas inconsistências | processa a quantidade indicada, mas com fragilidades de controle ou organização | utiliza função, porém com coesão limitada ou integração incompleta ao fluxo principal | produz resultados majoritariamente corretos, com justificativa ainda restrita |
| **N3 - Proficiente** | organiza corretamente o fluxo de entrada, processamento e saída | controla a repetição por contagem de forma consistente e segura | implementa função adequada ao cálculo solicitado, com parâmetros e retorno coerentes | produz saídas corretas e verificáveis para todas as entradas processadas |
| **N4 - Avançado** | apresenta fluxo claro, econômico e bem organizado | utiliza repetição com boa legibilidade e controle preciso do processamento seriado | modulariza a solução com função coesa, integrada de forma clara ao programa | além da correção, apresenta justificativa técnica objetiva e artefato de alta clareza |



## 2. Seleção e Enumeração de Conhecimentos

### K01 — Modelo de execução e noção de estado (paradigma imperativo)

1. Compreensão de que a execução do programa evolui por mudanças sucessivas de estado.  
2. Relação entre atribuições, atualização de variáveis e transformação do estado ao longo do processamento.  
3. Uso dessa noção para interpretar sequências de comandos e laços iterativos.  

**Justificativa de mobilização na tarefa:** o cálculo iterativo do fatorial exige acompanhar atualizações sucessivas de variáveis e compreender como o estado do programa muda a cada passo do processamento.

### K02 — Variáveis, constantes e tipos primitivos

1. Representação de dados simples por variáveis e constantes.  
2. Uso coerente de tipos primitivos em operações numéricas básicas.  
3. Associação entre identificadores e papéis funcionais no algoritmo.  

**Justificativa de mobilização na tarefa:** a solução requer armazenar a quantidade de entradas, os valores lidos e os resultados calculados, com coerência entre papel da variável e natureza do dado manipulado.

### K03 — Expressões aritméticas e avaliação

1. Construção de expressões aritméticas válidas em contexto imperativo.  
2. Avaliação correta de operações numéricas e atualização por atribuição.  
3. Uso coerente de operações em cálculos acumulativos.  

**Justificativa de mobilização na tarefa:** o fatorial é um cálculo numérico acumulativo, dependente de expressões aritméticas corretas ao longo do processamento.

### K05 — Estrutura sequencial e E/S básica

1. Organização do fluxo de execução em etapas de entrada, processamento e saída.  
2. Leitura e apresentação de dados de modo consistente com o problema.  
3. Encadeamento verificável entre valores recebidos e resultados produzidos.  

**Justificativa de mobilização na tarefa:** a atividade depende de leitura inicial de `n`, leituras subsequentes e apresentação dos resultados, o que torna a estrutura sequencial e a E/S parte central do artefato.

### K07 — Estruturas de repetição

1. Uso de laços controlados por contagem ou condição.  
2. Garantia de processamento repetido com parada definida.  
3. Aplicação de repetição para percorrer séries finitas de entradas ou cálculos iterativos.  

**Justificativa de mobilização na tarefa:** a tarefa exige processar múltiplos valores e também realizar cálculo repetitivo dentro do fatorial, tornando a repetição um conhecimento diretamente mobilizado.

### K11 — Subprogramas: procedimentos e funções

1. Decomposição do programa em unidades com responsabilidade definida.  
2. Uso de parâmetros e retorno para comunicação entre fluxo principal e subprograma.  
3. Organização modular que favorece clareza e reuso.  

**Justificativa de mobilização na tarefa:** o enunciado exige explicitamente que o cálculo do fatorial seja feito por uma função, tornando esse conhecimento indispensável e diretamente observável.


## 3. Identificação de Objetivos de Aprendizagem

### LO1
Organizar programas que leem uma quantidade inicial de dados e processam, de forma consistente, uma sequência finita de entradas.

**K associados:** K05, K07

### LO2
Representar e atualizar dados numéricos de modo coerente durante cálculos iterativos em programas imperativos.

**K associados:** K01, K02, K03

### LO3
Implementar funções com parâmetros e retorno para encapsular cálculos específicos em programas introdutórios.

**K associados:** K11, K02, K05

### LO4
Aplicar repetição controlada e expressões aritméticas para produzir resultados corretos e verificáveis em processamento seriado de valores.

**K associados:** K03, K07, K05, K01



## 4. Definição de Competências

### 4.1 Competência Geral 

Desenvolver soluções introdutórias de programação imperativa que organizem entrada, processamento e saída de dados, utilizem repetição de forma controlada e modularizem cálculos por meio de funções, produzindo resultados corretos e verificáveis.

**Alinhamento BNCC:** não aplicável nesta especificação.

### 4.2 Especificações de Competências

## CT15.1

**Título da Competência**  
Realizar entrada e saída de dados com controle de quantidade e consistência entre leituras e resultados

**Descrição Textual**  
Organizar programas introdutórios que recebam uma quantidade inicial de dados, executem leituras subsequentes em conformidade com esse controle e produzam saídas consistentes com o processamento realizado.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1, LO4
- K mobilizados (Núcleo): K05, K02

**Especificação de Conhecimentos**
- **K05**: estrutura sequencial e E/S básica para encadear entrada, processamento e saída.  
  **Justificativa de evidência:** o artefato precisa mostrar leitura inicial, leituras subsequentes e apresentação correspondente dos resultados.
- **K02**: uso de variáveis e tipos primitivos para armazenar quantidade, valores de entrada e resultados.  
  **Justificativa de evidência:** a solução só se mantém consistente se os dados forem representados e manipulados com coerência.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predominância em **Aplicar**, pois a competência exige implementar fluxo funcional de entrada e saída em um programa concreto.

**Pareamento Conhecimento–Habilidade**

K05 / Aplicar → estruturar o fluxo de leitura inicial, processamento subsequente e apresentação de resultados de forma verificável.  
Verbos de Bloom: executar, implementar, operar

K02 / Aplicar → utilizar variáveis numéricas coerentes com os papéis de quantidade, valor lido e resultado calculado.  
Verbos de Bloom: manipular, usar, realizar


**Especificação de Disposições**  
- precisão na correspondência entre entradas e saídas  
- disciplina na organização do fluxo do programa  
- atenção à consistência dos dados processados  

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.1 | Realizar entrada e saída de dados com controle de quantidade e consistência entre leituras e resultados | precisão; disciplina; atenção à consistência | K05 | estruturar o fluxo de leitura inicial, processamento subsequente e apresentação de resultados de forma verificável |
| CT15.1 | Realizar entrada e saída de dados com controle de quantidade e consistência entre leituras e resultados | precisão; disciplina; atenção à consistência | K02 | utilizar variáveis numéricas coerentes com os papéis de quantidade, valor lido e resultado calculado |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa exige implementação concreta de leitura, processamento seriado e saída. Sem essa competência, não há como materializar a estrutura mínima observável do artefato solicitado.

## CT15.2

**Título da Competência**  
Controlar o fluxo com repetição utilizando contagem e parada segura

**Descrição Textual**  
Empregar estruturas de repetição para processar quantidades finitas de dados e sustentar execuções iterativas com controle explícito do fluxo e da condição de término.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1, LO4
- K mobilizados (Núcleo): K07, K05, K01

**Especificação de Conhecimentos**
- **K07**: repetição por contagem e controle de término em laços finitos.  
  **Justificativa de evidência:** a tarefa exige processar `n` entradas e manter iteração coerente no cálculo.
- **K05**: encadeamento do fluxo iterativo ao restante do programa.  
  **Justificativa de evidência:** o laço precisa estar integrado ao fluxo geral de leitura e saída.
- **K01**: atualização de estado ao longo da execução repetida.  
  **Justificativa de evidência:** o comportamento do programa depende do acompanhamento consistente das mudanças de estado em cada iteração.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predominância em **Aplicar**, com componente analítico limitado, pois o estudante deve usar laços de modo funcional e controlado para resolver um problema concreto.

**Pareamento Conhecimento–Habilidade**

K07 / Aplicar → controlar a repetição por contagem para processar uma sequência finita de entradas com término garantido.  
Verbos de Bloom: iterar, executar, resolver

K05 / Aplicar → integrar o laço ao fluxo global do programa de forma coerente com entrada e saída.  
Verbos de Bloom: implementar, operar, realizar

K01 / Analisar → rastrear a atualização do estado do programa ao longo das iterações para manter consistência no processamento.  
Verbos de Bloom: rastrear, estruturar, examinar


**Especificação de Disposições**  
- rigor no controle da quantidade processada  
- cuidado com consistência do fluxo  
- atenção à parada segura e ao processamento completo  

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.2 | Controlar o fluxo com repetição utilizando contagem e parada segura | rigor; cuidado; atenção à parada segura | K07 | controlar a repetição por contagem para processar uma sequência finita de entradas com término garantido |
| CT15.2 | Controlar o fluxo com repetição utilizando contagem e parada segura | rigor; cuidado; atenção à parada segura | K05 | integrar o laço ao fluxo global do programa de forma coerente com entrada e saída |
| CT15.2 | Controlar o fluxo com repetição utilizando contagem e parada segura | rigor; cuidado; atenção à parada segura | K01 | rastrear a atualização do estado do programa ao longo das iterações para manter consistência no processamento |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a quantidade de valores é determinada por `n`, de modo que a competência de repetição é diretamente exigida tanto para o processamento das entradas quanto para a sustentação do cálculo iterativo.


## CT15.3

**Título da Competência**  
Decompor a solução em função com parâmetros e retorno coerentes

**Descrição Textual**  
Modularizar programas introdutórios por meio de funções com responsabilidade bem definida, articulando parâmetros, processamento interno e retorno de resultado ao fluxo principal.

**Cobertura e rastreabilidade**
- LOs cobertos: LO3
- K mobilizados (Núcleo): K11, K02

**Especificação de Conhecimentos**
- **K11**: definição e uso de função como unidade coesa de processamento.  
  **Justificativa de evidência:** o enunciado determina explicitamente que o cálculo do fatorial seja feito por função.
- **K02**: coerência entre tipo dos dados recebidos e valor retornado.  
  **Justificativa de evidência:** a função só cumpre seu papel quando há consistência entre entrada, processamento e retorno.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predominância em **Criar**, pois a tarefa requer conceber e implementar uma decomposição funcional efetiva, e não apenas reconhecer ou usar uma função já pronta.

**Pareamento Conhecimento–Habilidade**

K11 / Criar → projetar e implementar uma função coesa para encapsular um cálculo específico do programa.  
Verbos de Bloom: projetar, desenvolver, programar

K02 / Aplicar → definir parâmetros e retorno compatíveis com o tipo de dado manipulado na função.  
Verbos de Bloom: usar, manipular, aplicar


**Especificação de Disposições**  
- organização modular da solução  
- precisão na definição de responsabilidades  
- clareza na integração entre partes do programa  

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.3 | Decompor a solução em função com parâmetros e retorno coerentes | organização modular; precisão; clareza | K11 | projetar e implementar uma função coesa para encapsular um cálculo específico do programa |
| CT15.3 | Decompor a solução em função com parâmetros e retorno coerentes | organização modular; precisão; clareza | K02 | definir parâmetros e retorno compatíveis com o tipo de dado manipulado na função |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a modularização por função não é opcional neste problema. Ela constitui exigência explícita do enunciado e produz evidência direta sobre decomposição funcional e integração entre subprograma e fluxo principal.


## CT15.4

**Título da Competência**  
Aplicar expressões aritméticas e atualização de estado em cálculo iterativo verificável

**Descrição Textual**  
Executar cálculos numéricos iterativos em programas imperativos, articulando expressões aritméticas, atualização consistente de estado e controle de repetição para produzir resultados corretos.

**Cobertura e rastreabilidade**
- LOs cobertos: LO2, LO4
- K mobilizados (Núcleo): K03, K01, K07

**Especificação de Conhecimentos**
- **K03**: formulação e avaliação de expressões aritméticas em cálculo acumulativo.  
  **Justificativa de evidência:** o fatorial depende de operações aritméticas corretas ao longo da iteração.
- **K01**: compreensão do estado do programa durante sucessivas atualizações.  
  **Justificativa de evidência:** o resultado só emerge corretamente quando o estudante controla a evolução das variáveis durante o cálculo.
- **K07**: repetição estruturada para sustentar o processo acumulativo.  
  **Justificativa de evidência:** o cálculo iterativo do fatorial exige laço com progressão e término coerentes.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predominância em **Aplicar**, com apoio de **Analisar** em rastreamento de estado, pois a competência se manifesta na implementação correta do cálculo iterativo.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → construir expressões aritméticas coerentes para atualizar corretamente o resultado de um cálculo acumulativo.  
Verbos de Bloom: calcular, computar, implementar

K01 / Analisar → examinar a evolução do estado do programa durante as atualizações sucessivas do cálculo.  
Verbos de Bloom: examinar, rastrear, estruturar

K07 / Aplicar → utilizar repetição controlada para sustentar o processamento iterativo até a condição de término adequada.  
Verbos de Bloom: iterar, executar, resolver


**Especificação de Disposições**  
- precisão no cálculo acumulativo  
- persistência analítica na verificação do estado  
- consistência na atualização das variáveis  

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.4 | Aplicar expressões aritméticas e atualização de estado em cálculo iterativo verificável | precisão; persistência analítica; consistência | K03 | construir expressões aritméticas coerentes para atualizar corretamente o resultado de um cálculo acumulativo |
| CT15.4 | Aplicar expressões aritméticas e atualização de estado em cálculo iterativo verificável | precisão; persistência analítica; consistência | K01 | examinar a evolução do estado do programa durante as atualizações sucessivas do cálculo |
| CT15.4 | Aplicar expressões aritméticas e atualização de estado em cálculo iterativo verificável | precisão; persistência analítica; consistência | K07 | utilizar repetição controlada para sustentar o processamento iterativo até a condição de término adequada |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa não se reduz à leitura e modularização. Ela exige que o estudante implemente um cálculo iterativo correto, o que ativa diretamente conhecimento aritmético, repetição e acompanhamento do estado do programa.

