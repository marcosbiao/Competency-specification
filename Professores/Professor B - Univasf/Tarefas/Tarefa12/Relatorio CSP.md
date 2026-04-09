# Relatório CSP — Autoria de Competências  

## Introdução

Este relatório enquadra a atividade 12 na fase de Autoria de Competências do CSP, tomando como base a descrição pedagógica da tarefa de construção de um subprograma que recebe quatro números inteiros e devolve a soma dos três maiores, bem como de um programa principal que processa múltiplos conjuntos de entrada conforme a decisão do usuário. A tarefa elicita evidências observáveis porque exige artefatos verificáveis, como definição correta do subprograma, repetição controlada, leitura sucessiva de dados e apresentação do resultado a cada execução.

A especificação foi construída com foco em rastreabilidade entre conhecimentos, objetivos de aprendizagem e competências, preservando reuso e evitando redundância. Nesta versão, os conhecimentos foram mantidos apenas como conhecimentos mobilizados, sem separação em K Apoio.

## 1. Análise da Entidade Instrucional

### Título

Subprograma para soma dos três maiores valores em conjuntos sucessivos de quatro inteiros

### Descrição

A atividade solicita a construção de uma solução modular em programação imperativa. O estudante deve implementar um subprograma com quatro parâmetros inteiros e retorno numérico, responsável por produzir a soma dos três maiores valores entre os quatro recebidos. Em seguida, deve integrá-lo a um programa principal que leia sucessivos conjuntos de quatro valores, enquanto o usuário desejar, e apresente a soma calculada para cada conjunto.

### Processo de Desenvolvimento da Solução

1. Identificar as entradas, a saída e a responsabilidade funcional do subprograma.
2. Definir a assinatura do subprograma com parâmetros e tipo de retorno compatíveis.
3. Estruturar a lógica necessária para determinar quais três valores devem compor a soma.
4. Implementar o programa principal com leitura dos dados, chamada do subprograma e exibição do resultado.
5. Organizar a repetição do processamento para múltiplos conjuntos, com condição de parada explícita.

### Resultados Esperados

1. Código-fonte do programa principal.
2. Código-fonte do subprograma.
3. Execução com mais de um conjunto de entrada.
4. Saídas correspondentes ao resultado de cada chamada.
5. Justificativa breve sobre a função do subprograma e sobre o controle de repetição adotado.

### Contexto de Aquisição

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### Perfil do Público-Alvo

Estudantes em fase inicial de formação em programação imperativa, com conhecimentos prévios esperados sobre variáveis, tipos primitivos, expressões, estruturas condicionais, estruturas de repetição e noções introdutórias de funções ou procedimentos.

### Nível de Proficiência (critérios e dimensões)

| Nível | Modularização | Repetição com parada segura | Entrada, saída e verificabilidade |
|---|---|---|---|
| **N1 - Inicial** | Define subprograma incompleto ou incompatível com a tarefa. | Implementa repetição sem controle claro de continuidade ou encerramento. | Lê ou exibe dados com inconsistências que dificultam a verificação. |
| **N2 - Intermediário** | Define subprograma funcional, mas com assinatura ou integração parcialmente inadequadas. | Processa múltiplos casos com repetição básica, porém com fragilidade na condição de parada. | Lê e exibe resultados de forma compreensível, mas com organização limitada. |
| **N3 - Proficiente** | Implementa subprograma coeso, com parâmetros e retorno adequados. | Controla adequadamente a repetição de múltiplos conjuntos com parada consistente. | Realiza leitura e apresentação dos resultados de modo claro e verificável. |
| **N4 - Avançado** | Modulariza a solução com clareza e boa separação de responsabilidades. | Organiza repetição estável, semanticamente precisa e robusta. | Produz artefato bem estruturado, claro e tecnicamente consistente. |

## 2. Seleção e Enumeração de Conhecimentos 

### K02 — Variáveis, constantes e tipos primitivos

1. Representação de dados simples por identificadores com tipo coerente.
2. Uso de inteiros, atribuições e coerência de tipos em operações básicas.
3. Definição de parâmetros e retorno compatíveis com o processamento solicitado.

Justificativa de mobilização na tarefa: a atividade exige leitura e manipulação de números inteiros, além de interface coerente entre o módulo principal e o subprograma.

### K03 — Expressões aritméticas e avaliação

1. Construção de expressões numéricas para composição do resultado.
2. Avaliação correta de operações aritméticas em contexto de atribuição.
3. Produção de uma soma coerente a partir dos valores selecionados.

Justificativa de mobilização na tarefa: o resultado devolvido pelo subprograma depende de avaliação aritmética correta.

### K04 — Expressões lógicas e condições

1. Formulação de relações entre valores para comparação.
2. Composição de condições booleanas que sustentam o controle de fluxo.
3. Interpretação correta de verdade e falsidade em decisões.

Justificativa de mobilização na tarefa: a identificação dos três maiores valores exige comparações corretas entre os dados de entrada.

### K05 — Estrutura sequencial e E/S básica

1. Organização do fluxo de entrada, processamento e saída.
2. Leitura de dados e apresentação de resultados em cada iteração.
3. Encadeamento consistente entre leitura, chamada e exibição.

Justificativa de mobilização na tarefa: o programa principal deve organizar leitura, chamada do subprograma e exibição do resultado a cada conjunto processado.

### K07 — Estruturas de repetição

1. Execução repetida de leitura e processamento.
2. Uso de condição de parada explícita controlada pelo usuário.
3. Organização iterativa de múltiplos casos de entrada.

Justificativa de mobilização na tarefa: o enunciado exige o processamento de tantos conjuntos quantos o usuário desejar.

### K11 — Subprogramas: procedimentos e funções

1. Decomposição do problema em unidade funcional coesa.
2. Definição e invocação correta de subprograma com parâmetros e retorno.
3. Organização modular entre programa principal e processamento especializado.

Justificativa de mobilização na tarefa: o uso de subprograma é exigência central do enunciado.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Implementar funções ou procedimentos com assinatura e tipos compatíveis com a responsabilidade de processamento atribuída.

**K associados:** K02, K11

### LO2

Organizar repetição controlada por condição explícita para processar múltiplos conjuntos de dados com parada consistente.

**K associados:** K07, K05, K04

### LO3

Realizar entrada e saída de dados de forma coerente, verificável e apropriada ao fluxo de execução do programa.

**K associados:** K05, K02

### LO4

Aplicar comparações e operações aritméticas de modo consistente para produzir o resultado numérico esperado no subprograma.

**K associados:** K04, K03, K02

## 4. Definição de Competências

### 4.1 Competência Geral 

Não aplicável em termos de BNCC, pois a atividade está situada em contexto de ensino superior. Em termos gerais, a tarefa mobiliza a construção de soluções computacionais modulares, iterativas e verificáveis em programação imperativa introdutória.

### 4.2 Especificações de Competências

## CT12.1

**Título da Competência**  
Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados

**Descrição Textual**

Definir e integrar funções ou procedimentos com responsabilidade funcional clara, utilizando assinaturas, parâmetros, tipos e retorno coerentes com o processamento solicitado em problemas introdutórios de programação.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1, LO4
- K mobilizados (Núcleo): K11, K02, K04, K03

**Especificação de Conhecimentos**
- K11: definição e invocação correta de subprogramas; evidenciado diretamente pela implementação e pela chamada do módulo de cálculo.
- K02: uso coerente de parâmetros, variáveis e tipo de retorno; evidenciado pela compatibilidade entre dados de entrada e resultado devolvido.
- K04: formulação de comparações entre valores; evidenciado pela lógica usada no interior do subprograma.
- K03: composição aritmética do resultado; evidenciado pela soma produzida a partir dos valores selecionados.

**Alinhamento com a Taxonomia de Bloom (revisada)**

Criar

**Pareamento Conhecimento–Habilidade**

K11 / Criar → desenvolver função ou procedimento com responsabilidade bem definida e interface compatível com o problema proposto.  
Verbos de Bloom: desenvolver, projetar, construir

K02 / Aplicar → utilizar parâmetros, variáveis e tipos primitivos de modo coerente com a assinatura e com o retorno do subprograma.  
Verbos de Bloom: implementar, usar, operar

K04 / Analisar → estruturar comparações lógicas que permitam distinguir corretamente os valores relevantes para o resultado.  
Verbos de Bloom: analisar, estruturar, rastrear

K03 / Aplicar → compor a expressão aritmética do retorno a partir dos valores corretamente identificados no processamento.  
Verbos de Bloom: calcular, computar, resolver


**Especificação de Disposições**  
1. Precisão na definição da interface entre módulos.  
2. Clareza na separação de responsabilidades.  
3. Cuidado com coerência entre parâmetros, processamento e retorno.  
4. Rigor na formulação da lógica interna do subprograma.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.1 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | precisão de interface; separação de responsabilidades; rigor lógico | K11 | desenvolver função ou procedimento com interface compatível |
| CT12.1 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | precisão de interface; separação de responsabilidades; rigor lógico | K02 | utilizar parâmetros, variáveis e tipos de modo coerente |
| CT12.1 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | precisão de interface; separação de responsabilidades; rigor lógico | K04 | estruturar comparações lógicas corretas no processamento |
| CT12.1 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | precisão de interface; separação de responsabilidades; rigor lógico | K03 | compor a expressão aritmética do retorno |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta: a atividade exige explicitamente a definição de um subprograma que processe os dados recebidos e devolva um resultado ao módulo chamador.

## CT12.2

**Título da Competência**  
Controlar o fluxo com repetição e paradas seguras em processamento iterativo de casos

**Descrição Textual**

Organizar estruturas de repetição para processar múltiplos casos de entrada, mantendo condição de continuidade explícita, parada segura e comportamento verificável em programas introdutórios.

**Cobertura e rastreabilidade**
- LOs cobertos: LO2, LO3
- K mobilizados (Núcleo): K07, K05, K04

**Especificação de Conhecimentos**
- K07: repetição com continuidade e encerramento; evidenciado diretamente pelo processamento de múltiplos conjuntos de entrada.
- K05: organização sequencial do ciclo de execução; evidenciado pela leitura, chamada e exibição em cada iteração.
- K04: condição lógica de continuidade; evidenciado pelo controle de parada adotado pelo programa.

**Alinhamento com a Taxonomia de Bloom**

Aplicar

**Pareamento Conhecimento–Habilidade**

K07 / Aplicar → implementar estrutura de repetição que processe sucessivos conjuntos de entrada com encerramento consistente.  
Verbos de Bloom: implementar, iterar, executar

K05 / Aplicar → organizar o ciclo de leitura, processamento e saída de forma estável em cada repetição.  
Verbos de Bloom: executar, implementar, usar

K04 / Aplicar → utilizar condição lógica explícita para controlar continuidade e encerramento do programa.  
Verbos de Bloom: usar, operar, realizar

**Especificação de Disposições**  
1. Atenção à condição de parada.  
2. Disciplina na estabilidade do fluxo iterativo.  
3. Clareza na organização de ciclos sucessivos.  
4. Cuidado com encerramento consistente da execução.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.2 | Controlar o fluxo com repetição e paradas seguras em processamento iterativo de casos | atenção à parada; estabilidade iterativa; consistência de fluxo | K07 | implementar estrutura de repetição com encerramento consistente |
| CT12.2 | Controlar o fluxo com repetição e paradas seguras em processamento iterativo de casos | atenção à parada; estabilidade iterativa; consistência de fluxo | K05 | organizar o ciclo de leitura, processamento e saída |
| CT12.2 | Controlar o fluxo com repetição e paradas seguras em processamento iterativo de casos | atenção à parada; estabilidade iterativa; consistência de fluxo | K04 | utilizar condição lógica explícita para continuidade e encerramento |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta: a atividade exige processar tantos conjuntos quanto o usuário desejar, o que torna a repetição controlada parte observável e indispensável da solução.

## CT12.3

**Título da Competência**  
Realizar entrada e saída de dados com consistência e formatação apropriada

**Descrição Textual**

Organizar operações de entrada e saída de dados em programas introdutórios, preservando consistência entre leitura, processamento e apresentação dos resultados de modo verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: LO2, LO3
- K mobilizados (Núcleo): K05, K02

**Especificação de Conhecimentos**
- K05: fluxo de entrada, processamento e saída; evidenciado diretamente pela leitura dos conjuntos e apresentação do resultado em cada iteração.
- K02: coerência entre dados lidos e dados apresentados; evidenciado pelo uso correto das variáveis que participam do fluxo do programa.

**Alinhamento com a Taxonomia de Bloom (revisada)**

Aplicar

**Pareamento Conhecimento–Habilidade**

K05 / Aplicar → estruturar a entrada dos dados e a apresentação do resultado de modo claro, sequencial e verificável.  
Verbos de Bloom: executar, implementar, usar

K02 / Aplicar → manter coerência entre os dados lidos, armazenados e apresentados ao longo da execução.  
Verbos de Bloom: usar, operar, manipular


**Especificação de Disposições**  
1. Clareza na apresentação dos resultados.  
2. Cuidado com coerência entre leitura e exibição.  
3. Organização do fluxo observável do programa.  
4. Atenção à verificabilidade da execução.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.3 | Realizar entrada e saída de dados com consistência e formatação apropriada | clareza de apresentação; coerência de fluxo; verificabilidade | K05 | estruturar a entrada e a apresentação do resultado de modo verificável |
| CT12.3 | Realizar entrada e saída de dados com consistência e formatação apropriada | clareza de apresentação; coerência de fluxo; verificabilidade | K02 | manter coerência entre dados lidos, armazenados e apresentados |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: justificatória
- Função de ativação: núcleo
- Justificativa curta: a solução precisa ler sucessivos conjuntos de valores e exibir a soma correspondente a cada caso, o que torna a entrada e a saída parte verificável do desempenho na tarefa.

