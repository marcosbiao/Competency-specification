# RELATÓRIO CSP

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do Competency Specification Process (CSP) e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados pela **TASK07**, centrada na verificação computacional de aptidão para doação de sangue. A tarefa requer leitura de múltiplos dados do usuário, tradução de regras textuais em critérios lógicos, uso de decisão condicional e apresentação de uma resposta final verificável. Por isso, produz evidências observáveis no programa, nas condições implementadas, na cobertura dos casos e na coerência da saída.

A tarefa sustenta o modelo **Conhecimento–Habilidade–Disposição (K–S–D)** porque mobiliza conhecimentos estáveis do núcleo de programação introdutória, exige habilidades técnicas avaliáveis no artefato construído e permite associar disposições ligadas a precisão, consistência lógica e rigor computacional. A modelagem abaixo prioriza rastreabilidade explícita, reuso e controle de granularidade, sem criar conhecimentos fora do catálogo da disciplina.

## 1. Análise da Entidade Instrucional

### Título

**TASK07: Verificação de aptidão para doação de sangue**

### Descrição

A tarefa solicita a implementação de um programa que colete informações do usuário e determine se ele está apto ou não a doar sangue com base em um conjunto de critérios simultâneos. A solução integra entrada de dados, representação adequada das informações, formulação de expressões relacionais e lógicas, uso de estruturas condicionais e emissão de uma decisão final clara. A evidência principal está no artefato executável e na coerência entre regras do enunciado, comportamento computacional e justificativa breve.

### Processo de Desenvolvimento da Solução

1. Identificar as informações de entrada exigidas pelo problema.
2. Representar essas informações por variáveis compatíveis com seus papéis computacionais.
3. Organizar o fluxo básico de entrada, processamento e saída.
4. Traduzir cada requisito do enunciado em condições verificáveis.
5. Integrar os critérios parciais em uma decisão final de aptidão ou inaptidão.
6. Exibir o resultado de forma verificável e coerente com as condições avaliadas.

### Resultados Esperados

1. Código-fonte contendo leitura de dados, processamento lógico e saída final.
2. Decisão explícita sobre a aptidão ou inaptidão para doação.
3. Cobertura de todos os critérios exigidos no enunciado.
4. Justificativa breve coerente com as condições efetivamente avaliadas.
5. Saída final clara, verificável e tecnicamente consistente.

### Contexto de Aquisição

1. **Curso/Nível:** disciplina introdutória de programação em curso superior da área de Computação.
2. **Componente Curricular:** Programação de Computadores I.
3. **Organização:** atividade individual.
4. **Ambiente:** laboratório de programação ou avaliação prática escrita/computacional.
5. **Avaliação:** análise do código, da consistência lógica das condições, da cobertura dos critérios do problema e da verificabilidade da saída.

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de formação em programação estruturada, com repertório introdutório sobre algoritmo, variáveis, tipos de dados, expressões e estruturas condicionais. São estudantes que ainda consolidam a tradução de enunciados textuais em regras computacionais explícitas e necessitam de tarefas que evidenciem a relação entre entrada, processamento, decisão e saída. A tarefa é adequada a esse perfil porque exige múltiplas verificações, mas permanece dentro do escopo nuclear da disciplina.

### Nível de Proficiência (critérios e dimensões)

| Nível | Representação dos dados | Formulação das condições | Decisão computacional | Saída e justificativa |
|---|---|---|---|---|
| **N1 - Inicial** | identifica apenas parte das entradas ou usa variáveis de forma inconsistente | constrói condições incorretas ou incompletas | a decisão final não corresponde aos critérios avaliados | apresenta saída pouco verificável ou incoerente |
| **N2 - Intermediario** | representa as entradas principais, com pequenas fragilidades de tipo ou organização | traduz parcialmente os critérios do enunciado | a decisão cobre parte dos casos, mas com lacunas | apresenta saída compreensível, porém insuficientemente fundamentada |
| **N3 - Proficiente** | representa adequadamente todas as entradas e saídas necessárias | traduz corretamente os critérios e combina as verificações necessárias | a decisão final é coerente com os critérios implementados | apresenta saída clara e justificativa breve adequada |
| **N4 - Avançado** | representa os dados com clareza, consistência e boa organização algorítmica | formula condições robustas, sem ambiguidades e com boa legibilidade lógica | a decisão final é coerente, completa e tecnicamente bem estruturada | apresenta saída clara, verificável e justificativa tecnicamente sólida |

## 2. Seleção e Enumeração de Conhecimentos 

### K02: Algoritmos e formas de representação

1. Compreensão de algoritmo como sequência finita, ordenada e não ambígua de passos para resolver um problema.
2. Organização de soluções em etapas logicamente articuladas.
3. Tradução de regras do problema para uma representação algorítmica executável.

**Justificativa de mobilização na tarefa:** a atividade exige estruturar uma solução que transforme regras textuais em passos computacionais coerentes e verificáveis.

### K03: Estrutura sequencial, entrada, processamento e saída

1. Organização do programa como fluxo de leitura, processamento e apresentação de resultados.
2. Encadeamento correto entre dados de entrada, decisão e saída produzida.
3. Produção de resultados observáveis ao final da execução.

**Justificativa de mobilização na tarefa:** a solução depende diretamente da leitura de dados do usuário, do processamento das regras e da emissão de uma resposta final verificável.

### K04: Variáveis, constantes, tipos de dados e atribuição

1. Representação de dados por variáveis adequadas ao problema.
2. Uso coerente de tipos de dados básicos em contexto introdutório.
3. Atualização de valores por atribuição ao longo do processamento.

**Justificativa de mobilização na tarefa:** o programa precisa armazenar entradas heterogêneas e manter coerência entre variáveis de controle, critérios e resposta final.

### K05: Expressões aritméticas, relacionais e lógicas

1. Construção de comparações numéricas e avaliações lógicas a partir das regras do problema.
2. Combinação de critérios por meio de operadores relacionais e lógicos.
3. Uso de expressões para apoiar a tomada de decisão computacional.

**Justificativa de mobilização na tarefa:** a verificação de idade, peso, horas de sono, intervalo entre doações e demais critérios depende da formulação correta de expressões relacionais e lógicas.

### K06: Estruturas condicionais

1. Seleção de caminhos alternativos de execução com base em condições.
2. Tratamento explícito de situações que satisfazem ou não satisfazem um conjunto de regras.
3. Cobertura coerente de casos complementares em problemas de classificação e validação.

**Justificativa de mobilização na tarefa:** a tarefa requer decidir entre aptidão e inaptidão a partir da avaliação conjunta de múltiplos critérios.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Implementar programas introdutórios que representem adequadamente dados de entrada e de saída conforme as exigências do problema.

**K associados:** (K03, K04)

### LO2

Organizar programas básicos segundo um fluxo verificável de entrada, processamento e saída.

**K associados:** (K02, K03)

### LO3

Construir expressões relacionais e lógicas para verificar critérios múltiplos de validação em problemas introdutórios.

**K associados:** (K05, K06)

### LO4

Implementar decisões condicionais que classifiquem situações a partir da combinação de requisitos explicitados em linguagem natural.

**K associados:** (K02, K05, K06)

### LO5

Produzir saídas finais claras e justificáveis, coerentes com as condições efetivamente avaliadas pelo programa.

**K associados:** (K03, K04, K06)

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver soluções computacionais introdutórias que convertam regras textuais em verificações programáveis, articulando representação de dados, fluxo de processamento, expressões lógicas e decisão condicional de forma verificável.

### 4.2 Especificações de Competências

## CT07.1

**Título da Competência**  
Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais

**Descrição Textual**  
Capacidade de construir programas introdutórios funcionalmente coerentes, articulando representação de dados, fluxo sequencial e instruções fundamentais da linguagem, de modo que o comportamento do programa seja compreensível, verificável e semanticamente consistente.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO2)
2. K mobilizados (Núcleo): (K02, K03, K04)

**Especificação de Conhecimentos**
1. **K02:** organiza a solução como sequência algorítmica coerente. **Justificativa de evidência:** a tarefa permite observar se as regras do problema foram convertidas em etapas computacionais ordenadas.
2. **K03:** estrutura o programa segundo entrada, processamento e saída. **Justificativa de evidência:** o artefato final evidencia diretamente o fluxo operacional da solução.
3. **K04:** representa e atualiza dados por meio de variáveis adequadas. **Justificativa de evidência:** as entradas e a resposta final precisam ser armazenadas e manipuladas com consistência.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência exige implementação operacional de um programa introdutório com comportamento observável.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → organizar a solução em passos computacionais coerentes com a lógica global do problema.  
Verbos de Bloom: construir, implementar, resolver

K03 / Aplicar → estruturar o fluxo de leitura, processamento e saída de modo verificável no programa final.  
Verbos de Bloom: executar, programar, realizar

K04 / Aplicar → declarar, armazenar e atualizar variáveis compatíveis com os dados mobilizados pela solução.  
Verbos de Bloom: implementar, manipular, usar


**Especificação de Disposições**  
1. precisão na representação dos dados
2. atenção à coerência entre instruções e comportamento
3. rigor na construção do artefato executável

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT07.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão na representação dos dados; atenção à coerência entre instruções e comportamento; rigor na construção do artefato executável | K02 | organizar a solução em passos computacionais coerentes com a lógica global do problema |
| CT07.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão na representação dos dados; atenção à coerência entre instruções e comportamento; rigor na construção do artefato executável | K03 | estruturar o fluxo de leitura, processamento e saída de modo verificável no programa final |
| CT07.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão na representação dos dados; atenção à coerência entre instruções e comportamento; rigor na construção do artefato executável | K04 | declarar, armazenar e atualizar variáveis compatíveis com os dados mobilizados pela solução |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a atividade exige a construção efetiva de um programa funcional. As evidências aparecem no artefato executável, na organização do fluxo e na coerência semântica entre dados, processamento e resposta final.

## CT07.2

**Título da Competência**  
Realizar entrada e saída de dados com validação mínima e formatação apropriada

**Descrição Textual**  
Capacidade de receber, representar e apresentar dados em programas introdutórios, garantindo consistência mínima entre o que é lido, o que é processado e o que é devolvido como resultado observável ao usuário.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO2, LO5)
2. K mobilizados (Núcleo): (K03, K04, K06)

**Especificação de Conhecimentos**
1. **K03:** organiza a leitura e a apresentação de resultados no fluxo do programa. **Justificativa de evidência:** a tarefa evidencia se os dados são solicitados e se a decisão final é apresentada de forma verificável.
2. **K04:** utiliza variáveis compatíveis com entradas e saídas da solução. **Justificativa de evidência:** o problema mobiliza diferentes informações que precisam ser armazenadas com consistência.
3. **K06:** sustenta a validação mínima necessária para determinar a resposta final. **Justificativa de evidência:** a saída correta depende de a classificação final resultar das verificações condicionais implementadas.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência exige operacionalizar leitura, organização de dados e apresentação do resultado em um programa funcional.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → realizar a leitura dos dados e apresentar a resposta final de forma verificável no fluxo do programa.  
Verbos de Bloom: executar, programar, apresentar

K04 / Aplicar → representar entradas e saídas com variáveis compatíveis com o papel computacional de cada dado.  
Verbos de Bloom: implementar, manipular, usar

K06 / Aplicar → produzir a saída final a partir da validação mínima exigida pelas condições implementadas.  
Verbos de Bloom: aplicar, operar, realizar


**Especificação de Disposições**  
1. atenção à consistência entre entrada e saída
2. clareza na apresentação do resultado
3. rigor no tratamento dos dados fornecidos

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT07.2 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | atenção à consistência entre entrada e saída; clareza na apresentação do resultado; rigor no tratamento dos dados fornecidos | K03 | realizar a leitura dos dados e apresentar a resposta final de forma verificável no fluxo do programa |
| CT07.2 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | atenção à consistência entre entrada e saída; clareza na apresentação do resultado; rigor no tratamento dos dados fornecidos | K04 | representar entradas e saídas com variáveis compatíveis com o papel computacional de cada dado |
| CT07.2 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | atenção à consistência entre entrada e saída; clareza na apresentação do resultado; rigor no tratamento dos dados fornecidos | K06 | produzir a saída final a partir da validação mínima exigida pelas condições implementadas |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a task depende da coleta de múltiplas informações e da devolução de uma resposta final explícita. Sem essa competência, a solução não se torna verificável do ponto de vista do usuário nem da avaliação.

## CT07.3

**Título da Competência**  
Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas

**Descrição Textual**  
Capacidade de formular expressões relacionais e lógicas corretas e utilizá-las no controle do fluxo de programas introdutórios, implementando decisões condicionais que classifiquem situações com base em múltiplos critérios.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO3, LO4, LO5)
2. K mobilizados (Núcleo): (K02, K05, K06)

**Especificação de Conhecimentos**
1. **K02:** organiza a solução como procedimento algorítmico que integra regras e decisão. **Justificativa de evidência:** a integração dos critérios exige uma estrutura algorítmica coerente.
2. **K05:** formula comparações e combinações lógicas a partir das regras do problema. **Justificativa de evidência:** a tarefa permite observar diretamente se os critérios foram convertidos em expressões corretas.
3. **K06:** implementa o bloco decisório responsável pela classificação final. **Justificativa de evidência:** a resposta final depende da cobertura coerente dos casos de aptidão e inaptidão.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Analisar**, pois a competência exige decompor critérios, relacioná-los e estruturar a lógica que sustenta a decisão computacional.

**Pareamento Conhecimento–Habilidade**

K02 / Analisar → organizar a solução algorítmica que consolide critérios múltiplos em uma decisão computacional coerente.  
Verbos de Bloom: analisar, estruturar, relacionar

K05 / Analisar → compor expressões relacionais e lógicas coerentes com critérios múltiplos de validação.  
Verbos de Bloom: analisar, examinar, estruturar

K06 / Analisar → organizar decisões condicionais que cubram corretamente os casos previstos pelo problema.  
Verbos de Bloom: discriminar, distinguir, estruturar


**Especificação de Disposições**  
1. consistência lógica
2. atenção às regras explicitadas no enunciado
3. rigor na cobertura dos casos
4. clareza na decisão final


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT07.3 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | consistência lógica; atenção às regras explicitadas no enunciado; rigor na cobertura dos casos; clareza na decisão final | K02 | organizar a solução algorítmica que consolide critérios múltiplos em uma decisão computacional coerente |
| CT07.3 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | consistência lógica; atenção às regras explicitadas no enunciado; rigor na cobertura dos casos; clareza na decisão final | K05 | compor expressões relacionais e lógicas coerentes com critérios múltiplos de validação |
| CT07.3 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | consistência lógica; atenção às regras explicitadas no enunciado; rigor na cobertura dos casos; clareza na decisão final | K06 | organizar decisões condicionais que cubram corretamente os casos previstos pelo problema |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: analítica
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: o centro da task está na conversão de critérios de elegibilidade em verificações programáveis. A decisão final só é válida se as expressões lógicas e o controle do fluxo estiverem corretamente estruturados.
