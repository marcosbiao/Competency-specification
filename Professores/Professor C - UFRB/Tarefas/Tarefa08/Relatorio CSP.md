# RELATÓRIO CSP COMPLETO

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do **Competency Specification Process (CSP)** e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa introdutória de programação. A atividade requer que o estudante leia um ano, aplique uma regra lógica baseada em divisibilidade e informe se o valor deve ou não ser classificado como ano de Copa do Mundo. As evidências são observáveis no código-fonte, no comportamento final do programa e na justificativa breve associada ao resultado.

A tarefa sustenta adequadamente o modelo **Conhecimento–Habilidade–Disposição (K–S–D)** porque mobiliza conhecimentos centrais da programação estruturada, exige habilidades técnicas verificáveis e demanda disposições ligadas à precisão lógica, à consistência computacional e à clareza da saída produzida. A modelagem a seguir evita redundância, seleciona apenas conhecimentos do catálogo da disciplina e organiza competências reutilizáveis para outras tarefas introdutórias da mesma natureza.

## 1. Análise da Entidade Instrucional

### Título

**Verificação de ano de Copa do Mundo**

### Descrição

Atividade introdutória de programação em que o estudante deve implementar um programa capaz de solicitar um ano, avaliar uma regra composta por dois critérios de divisibilidade e exibir uma classificação textual coerente com o resultado do teste lógico. A evidência principal está na articulação correta entre entrada, processamento condicional e saída.

### Processo de Desenvolvimento da Solução

1. Identificar a entrada requerida pelo problema, correspondente a um ano informado pelo usuário.
2. Representar esse dado por variável numérica compatível com o tipo de informação solicitado.
3. Traduzir a regra textual do enunciado em expressões relacionais e lógicas verificáveis.
4. Organizar a decisão computacional para distinguir os dois resultados possíveis.
5. Produzir uma saída textual clara, coerente com a condição avaliada.
6. Registrar breve justificativa técnica que conecte a regra implementada ao resultado apresentado.

### Resultados Esperados

- código-fonte com leitura do ano, processamento condicional e saída;
- solicitação e leitura correta de um único valor de entrada;
- classificação do ano como pertencente ou não ao caso previsto no enunciado;
- mensagem final verificável e coerente com a regra aplicada;
- justificativa breve explicando a lógica empregada.

### Contexto de Aquisição

- **Código da Task:** TASK08
- **Título da Task:** Verificação de ano de Copa do Mundo
- **Nível/Curso:** nível introdutório em Programação
- **Componente Curricular:** Programação de Computadores I
- **Contexto:** atividade individual, adequada a laboratório de programação ou avaliação prática inicial
- **Avaliação:** análise do código, do comportamento da solução e da coerência da justificativa breve

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de aprendizagem de programação estruturada, com contato introdutório com variáveis, tipos de dados, expressões, entrada e saída e estruturas condicionais. Trata-se de um perfil que ainda está consolidando a tradução de regras descritas em linguagem natural para decisões computacionais simples e verificáveis.

### Nível de Proficiência (critérios e dimensões)

| Nível | Representação do dado de entrada | Formulação da regra lógica | Controle do fluxo condicional | Saída e justificativa |
|---|---|---|---|---|
| **N1 - Inicial** | identifica o dado principal com inconsistências de tipo ou uso | não traduz corretamente os critérios de divisibilidade | não distingue adequadamente os dois cenários | apresenta saída incompleta ou incoerente |
| **N2 - Intermediário** | representa o ano corretamente, mas com fragilidades operacionais | traduz parte da regra, mas com imprecisões na combinação lógica | distingue os cenários com pequenas falhas de cobertura | apresenta saída compreensível, mas pouco verificável |
| **N3 - Proficiente** | representa o ano de forma coerente e funcional | traduz integralmente a regra em condição correta | controla corretamente os dois resultados possíveis | apresenta saída clara com justificativa adequada |
| **N4 - Avançado** | representa o dado com precisão e organização técnica | formula a condição com clareza, precisão e estabilidade | organiza a decisão de forma precisa, legível e robusta | apresenta saída tecnicamente clara e justificativa consistente |

## 2. Seleção e Enumeração de Conhecimentos

**K03 — Estrutura sequencial, entrada, processamento e saída**
- organização do programa como sequência de leitura, processamento e apresentação de resultado;
- encadeamento lógico entre entrada de dados, avaliação da regra e exibição da classificação;
- produção de saídas observáveis e compatíveis com o enunciado.

**Justificativa de mobilização na tarefa:** a atividade depende diretamente do fluxo básico de entrada, processamento e saída para que o comportamento do programa possa ser verificado.

**K04 — Variáveis, constantes, tipos de dados e atribuição**
- representação de dados por identificadores e tipos adequados;
- uso de variável para armazenar o ano informado;
- atualização e uso consistente do valor lido ao longo da execução.

**Justificativa de mobilização na tarefa:** o problema exige que o ano seja lido, armazenado e utilizado em testes de divisibilidade de forma coerente.

**K05 — Expressões aritméticas, relacionais e lógicas**
- formulação de comparações numéricas e condições compostas;
- uso de operadores relacionais e lógicos na construção da regra computacional;
- articulação entre operações numéricas e avaliação de verdadeiro ou falso.

**Justificativa de mobilização na tarefa:** a classificação solicitada decorre da avaliação de uma regra composta por critérios de divisibilidade e negação lógica.

**K06 — Estruturas condicionais**
- seleção entre caminhos alternativos de execução a partir de condição avaliada;
- cobertura de casos mutuamente excludentes;
- produção de resultados distintos conforme a regra do problema.

**Justificativa de mobilização na tarefa:** a solução precisa decidir entre dois resultados possíveis e exibir a mensagem correspondente ao caso identificado.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Organizar programas introdutórios com fluxo verificável de entrada, processamento e saída.  
**K associados:** (K03, K04)

**LO2.** Representar e utilizar dados inteiros de entrada de modo coerente com o problema computacional proposto.  
**K associados:** (K04, K03)

**LO3.** Formular condições compostas a partir de expressões relacionais e lógicas para classificar casos numéricos.  
**K associados:** (K05, K06)

**LO4.** Controlar a execução do programa por meio de decisão condicional simples, cobrindo os resultados alternativos previstos no enunciado.  
**K associados:** (K06, K05)

**LO5.** Produzir saídas textuais verificáveis e justificadas a partir do comportamento implementado.  
**K associados:** (K03, K06)

## 4. Definição de Competências

### 4.1 Competência Geral

**Implementar soluções computacionais introdutórias que articulem representação de dados, formulação de regras lógicas, decisão condicional e apresentação verificável de resultados.**


### 4.2 Especificações de Competências

## CT08.1

**Título da Competência**  
**Estruturar programas introdutórios com entrada única, processamento simples e saída verificável**

**Descrição Textual**  
Capacidade de organizar programas simples segundo um fluxo funcional de entrada, processamento e saída, utilizando variáveis adequadas e produzindo resultados observáveis ao final da execução.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO2, LO5)
- K mobilizados (Núcleo): (K03, K04)

**Especificação de Conhecimentos**
- **K03:** organiza a sequência básica de leitura, processamento e exibição. **Justificativa de evidência:** o fluxo completo do programa é diretamente observável no artefato produzido.
- **K04:** representa e utiliza o dado de entrada em variável compatível. **Justificativa de evidência:** a leitura e o uso do ano dependem de armazenamento e atribuição coerentes.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, porque a competência exige o uso operacional de estruturas básicas da programação em uma solução executável.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → estruturar o fluxo de entrada, processamento e saída de modo verificável no programa final.  
Verbos de Bloom: executar, programar, usar

K04 / Aplicar → declarar e utilizar variável numérica compatível com o papel do dado de entrada.  
Verbos de Bloom: implementar, manipular, operar

**Especificação de Disposições**  
- precisão na representação do dado;
- atenção à ordem dos comandos;
- rigor na apresentação do resultado.


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT08.1 | Estruturar programas introdutórios com entrada única, processamento simples e saída verificável | precisão na representação do dado; atenção à ordem dos comandos; rigor na apresentação do resultado | K03 | estruturar o fluxo de entrada, processamento e saída de modo verificável no programa final |
| CT08.1 | Estruturar programas introdutórios com entrada única, processamento simples e saída verificável | precisão na representação do dado; atenção à ordem dos comandos; rigor na apresentação do resultado | K04 | declarar e utilizar variável numérica compatível com o papel do dado de entrada |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa exige a construção efetiva de um programa funcional, com leitura de dado, processamento e exibição do resultado. A evidência está diretamente no artefato executável e na clareza da saída produzida.

## CT08.2

**Título da Competência**  
**Controlar o fluxo de execução por meio de expressões relacionais, lógicas e decisão condicional**

**Descrição Textual**  
Capacidade de traduzir regras descritas em linguagem natural para condições computacionais compostas e utilizá-las para selecionar comportamentos alternativos de execução em programas introdutórios.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3, LO4, LO5)
- K mobilizados (Núcleo): (K05, K06)

**Especificação de Conhecimentos**
- **K05:** permite formular comparações e combinações lógicas coerentes com a regra do problema. **Justificativa de evidência:** a condição composta implementada é observável diretamente no código.
- **K06:** permite selecionar corretamente entre dois resultados alternativos. **Justificativa de evidência:** a classificação final depende do ramo de execução acionado pela condição.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Analisar**, porque a competência exige decompor uma regra textual em critérios computacionais e organizar sua aplicação lógica no fluxo do programa.

**Pareamento Conhecimento–Habilidade**

K05 / Analisar → formular expressões relacionais e lógicas coerentes com critérios numéricos definidos no problema.  
Verbos de Bloom: analisar, examinar, estruturar

K06 / Analisar → distinguir e organizar caminhos alternativos de execução sem lacunas de cobertura.  
Verbos de Bloom: discriminar, distinguir, relacionar

**Especificação de Disposições**  
- consistência lógica;
- atenção às regras do problema;
- rigor na cobertura dos casos.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT08.2 | Controlar o fluxo de execução por meio de expressões relacionais, lógicas e decisão condicional | consistência lógica; atenção às regras do problema; rigor na cobertura dos casos | K05 | formular expressões relacionais e lógicas coerentes com critérios numéricos definidos no problema |
| CT08.2 | Controlar o fluxo de execução por meio de expressões relacionais, lógicas e decisão condicional | consistência lógica; atenção às regras do problema; rigor na cobertura dos casos | K06 | distinguir e organizar caminhos alternativos de execução sem lacunas de cobertura |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o núcleo lógico da atividade está na tradução da regra textual em uma condição composta e na escolha do resultado adequado. A evidência principal está na condição implementada e no ramo executado.

## CT08.3

**Título da Competência**  
**Implementar classificações binárias simples em programas introdutórios a partir de regras explícitas**

**Descrição Textual**  
Capacidade de integrar entrada de dados, avaliação lógica e decisão condicional para construir programas que classifiquem casos simples em duas saídas possíveis, com resultado verificável e justificativa coerente.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO3, LO4, LO5)
- K mobilizados (Núcleo): (K03, K05, K06)

**Especificação de Conhecimentos**
- **K03:** integra leitura, processamento e saída em um fluxo único de classificação. **Justificativa de evidência:** a execução completa do programa evidencia a coerência do processo classificatório.
- **K05:** sustenta a formulação da regra lógica que separa os dois resultados possíveis. **Justificativa de evidência:** a condição avaliada é o elemento central da classificação computacional.
- **K06:** organiza a decisão entre as duas respostas do programa. **Justificativa de evidência:** o resultado exibido depende diretamente da estrutura de seleção empregada.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Criar**, de modo defensável, porque a tarefa exige a implementação de uma solução completa e funcional em linguagem de programação, articulando múltiplos conhecimentos em um único artefato executável.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → integrar entrada, processamento e saída em um fluxo funcional de classificação computacional.  
Verbos de Bloom: aplicar, executar, usar

K05 / Analisar → relacionar critérios numéricos a uma regra lógica de classificação binária.  
Verbos de Bloom: analisar, relacionar, estruturar

K06 / Criar → construir a decisão computacional que produz uma entre duas saídas possíveis.  
Verbos de Bloom: construir, desenvolver, programar

**Especificação de Disposições**  
- rigor computacional;
- precisão lógica;
- consistência na classificação produzida.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT08.3 | Implementar classificações binárias simples em programas introdutórios a partir de regras explícitas | rigor computacional; precisão lógica; consistência na classificação produzida | K03 | integrar entrada, processamento e saída em um fluxo funcional de classificação computacional |
| CT08.3 | Implementar classificações binárias simples em programas introdutórios a partir de regras explícitas | rigor computacional; precisão lógica; consistência na classificação produzida | K05 | relacionar critérios numéricos a uma regra lógica de classificação binária |
| CT08.3 | Implementar classificações binárias simples em programas introdutórios a partir de regras explícitas | rigor computacional; precisão lógica; consistência na classificação produzida | K06 | construir a decisão computacional que produz uma entre duas saídas possíveis |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade não solicita apenas reconhecer uma regra. Ela exige construir um programa completo que leia um valor, avalie uma condição composta e produza uma classificação textual verificável.