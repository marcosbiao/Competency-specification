# RELATÓRIO CSP

## Introdução

Este relatório situa a tarefa TASK13 na fase de Autoria de Competências do Competency Specification Process, com foco na explicitação rastreável de conhecimentos, objetivos de aprendizagem e competências mobilizados por uma atividade introdutória de programação. A tarefa solicita a leitura de coordenadas de dois pontos, a organização do processamento em programa principal e subprograma, e a produção de uma saída numérica verificável.

A atividade elicita evidências observáveis porque exige artefatos concretos, como definição de dados, fluxo de entrada e saída, cálculo numérico e organização modular. Esses elementos permitem identificar, com baixo grau de inferência, quais conhecimentos do catálogo são diretamente acionados e quais capacidades podem ser especificadas de forma reutilizável.

O modelo K–S–D é suportado sem redundância porque os conhecimentos selecionados permanecem no limite do catálogo da disciplina, os objetivos de aprendizagem são formulados com verbos observáveis e as competências consolidam capacidades estáveis do domínio. Parte do enunciado, contudo, recai sobre conteúdo não contemplado pelo catálogo atual e, por isso, é registrada separadamente em EXT, sem gerar novos K, LO ou CT.

## 1. Análise da Entidade Instrucional

### Título

**TASK13: Cálculo da Distância entre Dois Pontos com Registro e Subprograma**

### Descrição

Atividade de implementação voltada à construção de uma solução numérica simples, com leitura de dados no programa principal, uso de subprograma e apresentação de resultado verificável. O enunciado exige organização modular e coerência entre os papéis do programa principal e do subprograma, além de uma justificativa breve para a opção adotada quando houver ambiguidade na exibição do resultado.

### Processo de Desenvolvimento da Solução

1. Interpretar o enunciado e identificar os dados de entrada, o processamento requerido e a saída esperada.
2. Organizar a estrutura geral da solução, distinguindo responsabilidades do programa principal e do subprograma.
3. Declarar os dados numéricos necessários para representar as coordenadas e sustentar o processamento.
4. Implementar o cálculo solicitado com expressões aritméticas coerentes.
5. Integrar leitura, processamento e saída em fluxo verificável.
6. Registrar a decisão adotada para a apresentação do resultado, em razão da ambiguidade presente no enunciado.

### Resultados Esperados

- Código-fonte funcional.
- Leitura das coordenadas no programa principal.
- Subprograma invocado com os dados requeridos.
- Resultado numérico apresentado de forma observável.
- Justificativa breve sobre a organização entre programa principal e subprograma.

### Contexto de Aquisição

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### Perfil do Público-Alvo

- Estudantes em etapa inicial de formação em programação imperativa.
- Pré-requisitos esperados: noções básicas de tipos primitivos, atribuição, entrada e saída, e cálculo aritmético simples.
- Necessidades formativas centrais: consolidar fluxo sequencial, coerência de tipos, decomposição em subprogramas e verificabilidade do comportamento do programa.

### Nível de Proficiência (critérios e dimensões)

| Nível de Proficiência | Fluxo de entrada, processamento e saída | Coerência de dados numéricos e estruturados | Organização modular | Verificabilidade do artefato |
|---|---|---|---|---|
| **N1 - Inicial** | Organiza apenas partes isoladas do fluxo, com lacunas de integração. | Representa dados com inconsistências frequentes entre declaração, uso e resultado. | Utiliza subprograma ou estrutura de dados de modo parcial ou confuso. | Apresenta solução pouco observável ou sem justificativa coerente. |
| **N2 - Intermediário** | Implementa fluxo básico verificável, ainda com pequenas inconsistências. | Usa dados coerentes na maior parte da solução, mas com fragilidades pontuais. | Define e invoca subprograma com responsabilidade básica adequada. | Apresenta resultado observável com justificativa sucinta. |
| **N3 - Proficiente** | Integra leitura, processamento e saída de modo coerente e observável. | Mantém consistência entre dados, processamento e resultado ao longo da solução. | Separa responsabilidades com clareza entre programa principal e subprograma. | Apresenta solução verificável, legível e justificativa coerente. |
| **N4 - Avançado** | Estrutura fluxo robusto, claro e reutilizável. | Articula representação de dados e processamento com alta precisão técnica. | Organiza interfaces e responsabilidades com elevado grau de clareza e generalização. | Produz solução verificável, clara e tecnicamente bem defendida. |

## 2. Seleção e Enumeração de Conhecimentos

**Nota de escopo:** a tarefa exige modelagem por registro `struct`, mas o catálogo atual não possui item específico para registros/estruturas compostas em C. Esse aspecto será tratado em EXT. O subconjunto abaixo contempla apenas os conhecimentos efetivamente existentes no catálogo.

### K01: Modelo de execução e noção de estado (paradigma imperativo)

- Compreender que a execução progride por mudanças de estado ao longo da sequência de comandos.
- Rastrear a transição entre leitura, processamento e apresentação do resultado.
- Relacionar atualização de dados e comportamento observável do programa.

**Justificativa de mobilização na tarefa:** a atividade exige coerência entre o que é lido, processado e exibido, além de justificar a distribuição de responsabilidades entre partes da solução.

### K02: Variáveis, constantes e tipos primitivos

- Declarar e utilizar dados simples, com destaque para valores reais.
- Manter coerência entre tipos e papel dos dados no processamento.
- Sustentar atribuições e operações numéricas introdutórias.

**Justificativa de mobilização na tarefa:** as coordenadas são tratadas como valores reais e precisam ser utilizadas de forma consistente no programa principal e na interface do processamento.

### K03: Expressões aritméticas e avaliação

- Construir expressões numéricas coerentes com o cálculo solicitado.
- Respeitar ordem de avaliação e composição de operações.
- Produzir resultados compatíveis com o problema proposto.

**Justificativa de mobilização na tarefa:** o cálculo da distância depende de expressão aritmética corretamente formulada e avaliada.

### K05: Estrutura sequencial e E/S básica

- Organizar programas como sequência verificável de leitura, processamento e saída.
- Produzir saídas observáveis e compatíveis com a execução.
- Manter encadeamento coerente entre comandos principais.

**Justificativa de mobilização na tarefa:** o enunciado exige leitura no programa principal, acionamento do processamento e comunicação do resultado ao final da execução.

### K11: Subprogramas: procedimentos e funções

- Decompor soluções em subprogramas com responsabilidade definida.
- Estabelecer parâmetros coerentes com os dados de entrada.
- Integrar definição, invocação e retorno ao fluxo do programa.

**Justificativa de mobilização na tarefa:** a tarefa exige explicitamente um subprograma, com passagem de dados e organização modular da solução.

## 3. Identificação de Objetivos de Aprendizagem

### LO1
Declarar e utilizar dados numéricos simples coerentes com o papel das entradas e do resultado em uma solução introdutória.

**K associados:** K02, K05

### LO2
Organizar o fluxo de execução de modo que leitura, processamento e saída sejam observáveis e verificáveis.

**K associados:** K05, K01

### LO3
Construir o processamento numérico requerido por meio de expressões aritméticas consistentes com o problema.

**K associados:** K03, K02

### LO4
Modularizar uma solução introdutória em subprograma com parâmetros coerentes e responsabilidade claramente delimitada.

**K associados:** K11, K05, K02

### LO5
Justificar a distribuição de responsabilidades entre programa principal e subprograma com base no comportamento esperado da solução.

**K associados:** K01, K11

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver programas introdutórios que representem dados numéricos simples, organizem o fluxo de entrada, processamento e saída e utilizem subprogramas para estruturar o comportamento da solução de forma verificável.

**BNCC:** não aplicável ao contexto informado.

### 4.2 Especificações de Competências

## CT13.1

**Título da Competência**  
Modelar e organizar dados compostos em programas introdutórios

**Descrição Textual**  
Representar entidades simples do problema por meio de `structs`, articulando campos, passagem de dados e uso coerente dessas estruturas em subprogramas introdutórios.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1
- K mobilizados: K02, K11

**Especificação de Conhecimentos**
- **K02:** sustenta a declaração coerente dos campos primitivos que compõem a estrutura utilizada na solução.
- **K11:** sustenta o uso da estrutura na interface do subprograma e sua integração ao programa principal.

**Alinhamento com a Taxonomia de Bloom**  
Predominância em **Aplicar**.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar campos primitivos coerentes com a representação dos dados manipulados pela estrutura.  
Verbos de Bloom: construir, implementar, usar

K11 / Aplicar → utilizar estruturas compostas na interface de subprogramas de modo coerente com a responsabilidade do processamento.  
Verbos de Bloom: implementar, programar, usar


**Especificação de Disposições**  
- Precisão na representação dos dados.
- Clareza na organização entre estrutura e processamento.
- Cuidado com a coerência entre definição e uso.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto informado.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT13.1 | Modelar e organizar dados compostos em programas introdutórios | precisão; clareza; coerência | K02 | declarar campos primitivos coerentes com a representação dos dados manipulados pela estrutura |
| CT13.1 | Modelar e organizar dados compostos em programas introdutórios | precisão; clareza; coerência | K11 | utilizar estruturas compostas na interface de subprogramas de modo coerente com a responsabilidade do processamento |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta: a tarefa exige que os dados dos pontos sejam organizados em uma estrutura e passados ao subprograma. A competência é ativada diretamente na definição da representação dos dados e em seu uso na interface do processamento.

**Nota de escopo:** o catálogo atual não possui um K específico para registros ou `structs`. Nesta tarefa, a competência foi formulada a partir da articulação entre K02 e K11, mantendo a lacuna específica registrada em EXT.

## CT13.2

**Título da Competência**  
Modularizar processamento por subprogramas com interface coerente

**Descrição Textual**  
Decompor soluções introdutórias em subprogramas com responsabilidade definida, parâmetros coerentes e integração clara ao fluxo do programa principal.

**Cobertura e rastreabilidade**
- LOs cobertos: LO2, LO3
- K mobilizados: K11, K05, K03

**Especificação de Conhecimentos**
- **K11:** evidencia a definição, a invocação e a responsabilidade do subprograma no processamento da solução.
- **K05:** assegura a integração do subprograma ao fluxo global do programa, com leitura e apresentação observáveis.
- **K03:** sustenta o processamento numérico encapsulado no subprograma, mantendo coerência com o cálculo requerido.

**Alinhamento com a Taxonomia de Bloom**  
Predominância em **Aplicar**, com exigência localizada de **Analisar** na delimitação das responsabilidades entre unidades do programa.

**Pareamento Conhecimento–Habilidade**

K11 / Aplicar → definir e invocar subprograma com parâmetros coerentes com a responsabilidade do processamento.  
Verbos de Bloom: implementar, programar, usar

K05 / Aplicar → integrar a chamada do subprograma ao fluxo principal mantendo a solução observável.  
Verbos de Bloom: executar, implementar, usar

K03 / Aplicar → estruturar o cálculo solicitado em expressão aritmética coerente com o processamento modularizado.  
Verbos de Bloom: calcular, implementar, resolver

**Especificação de Disposições**  
- Organização modular da solução.
- Clareza na separação de responsabilidades.
- Disciplina na integração entre partes do programa.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto informado.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT13.2 | Modularizar processamento por subprogramas com interface coerente | organização modular; clareza; disciplina | K11 | definir e invocar subprograma com parâmetros coerentes com a responsabilidade do processamento |
| CT13.2 | Modularizar processamento por subprogramas com interface coerente | organização modular; clareza; disciplina | K05 | integrar a chamada do subprograma ao fluxo principal mantendo a solução observável |
| CT13.2 | Modularizar processamento por subprogramas com interface coerente | organização modular; clareza; disciplina | K03 | estruturar o cálculo solicitado em expressão aritmética coerente com o processamento modularizado |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva e justificatória
- Função de ativação: núcleo
- Justificativa curta: o enunciado exige explicitamente o uso de subprograma e a distinção entre o que cabe ao programa principal e ao processamento encapsulado. A competência é ativada na implementação e na justificativa da organização adotada.

## CT13.3

**Título da Competência**  
Realizar entrada e saída de dados com validação mínima e formatação apropriada

**Descrição Textual**  
Realizar leitura de dados e apresentação de resultados em programas introdutórios de forma consistente, verificável e adequada ao comportamento esperado da solução, preservando formatação apropriada e controle mínimo de consistência dos dados manipulados.

**Cobertura e rastreabilidade**
- LOs cobertos: LO4
- K mobilizados: K05, K02

**Especificação de Conhecimentos**
- **K05:** organiza o fluxo de leitura e saída, tornando a execução observável e verificável.
- **K02:** assegura coerência entre os dados lidos, o tipo utilizado e o resultado apresentado.

**Alinhamento com a Taxonomia de Bloom**  
Predominância em **Aplicar**.

**Pareamento Conhecimento–Habilidade**

K05 / Aplicar → realizar leitura e apresentação de resultados em sequência verificável e compatível com a solução proposta.  
Verbos de Bloom: executar, implementar, usar

K02 / Aplicar → utilizar tipos e variáveis coerentes com os dados lidos e com o resultado informado pelo programa.  
Verbos de Bloom: manipular, operar, usar

**Especificação de Disposições**  
- Atenção à consistência da entrada e da saída.
- Clareza na apresentação dos resultados.
- Cuidado com a verificabilidade do artefato.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto informado.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT13.3 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | consistência; clareza; verificabilidade | K05 | realizar leitura e apresentação de resultados em sequência verificável e compatível com a solução proposta |
| CT13.3 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | consistência; clareza; verificabilidade | K02 | utilizar tipos e variáveis coerentes com os dados lidos e com o resultado informado pelo programa |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta: a tarefa depende da leitura correta das coordenadas e da apresentação observável do resultado. A competência é ativada na organização da entrada e da saída do programa de forma consistente com a execução esperada.

## 5. Fora do Escopo/Extensão (EXT)

- Uso explícito de registros em C por meio de `struct`, incluindo definição do tipo e acesso a campos nomeados.
- Passagem de parâmetros do tipo `struct` entre programa principal e subprograma.

**Observação:** os itens acima são exigidos pelo enunciado, mas não possuem correspondência explícita no catálogo K atual. Por essa razão, foram mantidos como extensão registrada, sem criação de novo conhecimento no catálogo.
