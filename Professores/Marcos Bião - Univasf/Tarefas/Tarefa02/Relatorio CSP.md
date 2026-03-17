# RELATÓRIO CSP — Autoria de Competências  
## Emissão de notificação por índice de poluição

## Introdução

Este relatório situa a **TASK02** na fase de **Autoria de Competências** do **Competency Specification Process (CSP)**, com foco na explicitação rastreável de **Conhecimentos (K)**, **Objetivos de Aprendizagem (LO)** e **Competências (CT)** mobilizados pela tarefa. A atividade consiste em desenvolver, em linguagem C, um programa que leia um índice de poluição e emita a notificação correspondente aos grupos de indústrias, conforme regras condicionais explícitas no enunciado.

A tarefa elicita evidências observáveis porque exige um artefato verificável e uma saída textual coerente com as condições avaliadas. Além disso, a justificativa breve da decisão permite observar não apenas o produto final, mas também a correspondência entre regra do problema, condição lógica e comportamento do programa.

O modelo **K–S–D** é adequado a esta tarefa porque o desempenho depende da mobilização articulada de conhecimentos introdutórios de programação, da habilidade de implementar e estruturar decisões condicionais e de disposições como precisão, sistematicidade e atenção a casos. O relatório evita redundância ao selecionar apenas o subconjunto de conhecimentos diretamente pertinente à tarefa e ao formular competências reutilizáveis no escopo da disciplina.



# 1. Análise da Entidade Instrucional

## Título

**Emissão de notificação por índice de poluição**

## Descrição

Trata-se de uma tarefa introdutória de programação em C na qual o estudante deve ler um valor numérico correspondente ao índice de poluição e determinar qual notificação deve ser emitida aos grupos de indústrias, segundo limiares e regras de decisão definidos no enunciado. O foco instrucional recai sobre a tradução de regras textuais em condições computacionais verificáveis e na produção de uma saída textual compatível com a decisão tomada.

## Processo de Desenvolvimento da Solução (em etapas)

1. Identificar o dado de entrada relevante no enunciado.
2. Representar esse dado em variável numérica adequada no programa.
3. Interpretar as regras do problema como condições comparáveis.
4. Estruturar a seleção entre casos possíveis com coerência lógica.
5. Emitir a notificação correspondente ao caso identificado.
6. Verificar se a saída produzida é consistente com a regra acionada.

## Resultados Esperados

- Programa em C capaz de ler o índice de poluição.
- Implementação de lógica de decisão coerente com os limiares descritos.
- Emissão de notificação textual verificável.
- Justificativa breve sobre a regra que fundamenta a saída.
- Evidência de cobertura dos casos explicitamente previstos pela tarefa.

## Contexto de Aquisição

- **Curso:** Ciência da Computação
- **Nível:** Graduação, 1º semestre
- **Componente Curricular:** Introdução à Programação
- **Organização da atividade:** individual
- **Ambiente provável:** laboratório de programação ou atividade prática equivalente
- **Forma de avaliação:** análise do código, da saída produzida e da justificativa breve

## Perfil do Público-Alvo

Estudantes iniciantes em programação, em fase de consolidação de noções de entrada e saída, variáveis, tipos primitivos, expressões lógicas e estruturas de seleção. Pressupõe-se familiaridade inicial com sintaxe básica em C e com problemas que exigem transformar regras verbais em comportamento observável do programa. As necessidades centrais do público incluem apoio à leitura técnica do enunciado, organização de casos e implementação consistente de decisões condicionais.

## Nível de Proficiência (critérios e dimensões)

| Nível | Representação da entrada | Estruturação das condições | Implementação da seleção | Saída e justificativa |
|---|---|---|---|---|
| **N1 - Inicial** | Lê o dado com apoio e usa variável numérica simples | Identifica parte dos limiares, mas com ambiguidades | Implementa seleção incompleta ou com cobertura parcial | Produz saída parcialmente coerente e justificativa limitada |
| **N3 - Intermediário** | Lê e representa corretamente o índice | Formula condições adequadas para os casos principais | Implementa seleção funcional, com pequenas fragilidades de organização | Produz saída coerente e justificativa breve compreensível |
| **N3 - Proficiente** | Representa o dado de forma consistente e verificável | Organiza as condições com boa distinção entre os casos explicitados | Implementa seleção clara, sem sobreposição indevida entre casos | Produz saída correta e justificativa tecnicamente coerente |
| **N4 - Avançado** | Representa a entrada com clareza e consistência total | Modela os limiares com alto rigor lógico e boa legibilidade | Estrutura a seleção de forma robusta, clara e facilmente verificável | Produz saída precisa, justificativa concisa e forte rastreabilidade entre regra e comportamento |



# 2. Seleção e Enumeração de Conhecimentos

## Conhecimentos selecionados

### **K01 — Modelo de execução e noção de estado (paradigma imperativo)**
- Compreensão de que o programa evolui por mudanças de estado ao longo da execução.
- Relação entre sequência de instruções, atualização de variáveis e comportamento observado.
- Noção introdutória de fluxo de controle em programas imperativos.

**Justificativa de mobilização na tarefa:**  
A tarefa exige compreender que a leitura do índice, a avaliação das condições e a emissão da notificação compõem um encadeamento de estados observável no programa.

### **K02 — Variáveis, constantes e tipos primitivos**
- Uso de identificadores para armazenar dados simples.
- Escolha de tipos numéricos compatíveis com o papel do dado.
- Coerência entre valor lido e representação adotada no programa.

**Justificativa de mobilização na tarefa:**  
O índice de poluição é um dado numérico decimal e precisa ser representado de forma compatível para permitir leitura e comparação.

### **K04 — Expressões lógicas e condições**
- Construção de condições booleanas a partir de operadores relacionais.
- Interpretação de verdade e falsidade em regras de decisão.
- Relação entre condição formulada e caso do problema.

**Justificativa de mobilização na tarefa:**  
A distinção entre faixa aceitável e limiares de notificação depende diretamente da formulação de condições lógicas coerentes.

### **K05 — Estrutura sequencial e E/S básica**
- Organização de programas como sequência de leitura, processamento e saída.
- Uso de entrada e saída em tarefas introdutórias.
- Produção de resultados verificáveis a partir de um dado lido.

**Justificativa de mobilização na tarefa:**  
A atividade requer ler o índice informado, processá-lo e emitir uma notificação textual observável.

### **K06 — Estruturas de seleção**
- Escolha entre caminhos alternativos com base em condições.
- Encadeamento de decisões para cobertura de casos.
- Implementação de regras de negócio simples por meio de seleção.

**Justificativa de mobilização na tarefa:**  
A lógica principal da tarefa é decisória: o programa deve escolher a notificação adequada conforme o valor do índice.

---

# 3. Identificação de Objetivos de Aprendizagem

### **LO1**
Representar e ler, em um programa introdutório em C, um dado numérico necessário para o processamento da tarefa.

**K associados:** K02, K05

### **LO2**
Formular condições lógicas que expressem, de modo verificável, os limiares e distinções de casos presentes em um enunciado.

**K associados:** K04, K02

### **LO3**
Implementar estruturas de seleção capazes de associar regras condicionais a saídas observáveis sem ambiguidade operacional.

**K associados:** K06, K04, K01

### **LO4**
Produzir uma saída textual coerente com a condição identificada e justificá-la com base no comportamento do programa.

**K associados:** K05, K06, K01



# 4. Definição de Competências

## 4.1 Competência Geral 

**Competência geral do domínio de Computação:**  
Desenvolver programas introdutórios em linguagem C que transformem entradas numéricas em saídas verificáveis por meio de representação adequada de dados, formulação de condições e uso consistente de estruturas de seleção.

**BNCC:** não aplicável operacionalmente a esta tarefa, por se tratar de componente curricular de graduação.



## 4.2 Especificações de Competências

### Competência CT02.1

**Título da Competência**  
Representar entradas numéricas e organizar o fluxo básico de entrada, processamento e saída em programas introdutórios.

**Descrição Textual**  
Trata-se de estruturar programas simples que recebam dados numéricos, preservem coerência de representação e organizem um fluxo verificável de entrada, processamento inicial e emissão de resultados observáveis.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1, LO4
- K mobilizados (Núcleo): K02, K05

**Especificação de Conhecimentos**
- **K02 — Variáveis, constantes e tipos primitivos:** sustenta a representação correta do dado de entrada, diretamente evidenciada pela leitura e uso do índice numérico.
- **K05 — Estrutura sequencial e E/S básica:** sustenta a organização verificável do fluxo entrada→processamento→saída, diretamente observável no programa.


**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar e utilizar uma variável numérica compatível com a leitura do dado de entrada.  
Verbos de Bloom: implementar, usar, operar

K05 / Aplicar → organizar o fluxo de entrada, processamento inicial e saída de modo verificável.  
Verbos de Bloom: executar, implementar, realizar


**Especificação de Disposições**  
- Precisão no tratamento do dado de entrada  
- Sistematicidade na organização do programa  
- Atenção à verificabilidade da saída

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto desta tarefa.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT02.1 | Representar entradas numéricas e organizar o fluxo básico de entrada, processamento e saída em programas introdutórios | Precisão; sistematicidade; atenção à verificabilidade | K02 | Declarar e utilizar uma variável numérica compatível com a leitura do dado de entrada |
| CT02.1 | Representar entradas numéricas e organizar o fluxo básico de entrada, processamento e saída em programas introdutórios | Precisão; sistematicidade; atenção à verificabilidade | K05 | Organizar o fluxo de entrada, processamento inicial e saída de modo verificável |
| CT02.1 | Representar entradas numéricas e organizar o fluxo básico de entrada, processamento e saída em programas introdutórios | Precisão; sistematicidade; atenção à verificabilidade | K01 | Rastrear o efeito da leitura e do processamento inicial sobre o estado do programa |

**Definição de Ativação**
- Restrição de ativação: **obrigatória**
- Modo de ativação: **construtiva**
- Função de ativação: **núcleo**
- Justificativa curta baseada na tarefa: esta competência é ativada desde o início da resolução, pois o estudante precisa ler o índice, representá-lo adequadamente e estruturar um fluxo mínimo de execução que permita observar o comportamento do programa.


### Competência CT02.2

**Título da Competência**  
Modelar regras condicionais por limiares e estruturar cobertura de casos em decisões computacionais.

**Descrição Textual**  
Trata-se de transformar regras expressas em linguagem natural em condições lógicas implementáveis, distinguindo casos, limiares e precedências de decisão de forma coerente e verificável em programas introdutórios.

**Cobertura e rastreabilidade**
- LOs cobertos: LO2, LO3
- K mobilizados (Núcleo): K04, K06

**Especificação de Conhecimentos**
- **K04 — Expressões lógicas e condições:** é diretamente evidenciado pela formulação das comparações e distinções entre casos do problema.
- **K06 — Estruturas de seleção:** é diretamente evidenciado pela implementação dos ramos decisórios correspondentes às condições formuladas.


**Pareamento Conhecimento–Habilidade**

K04 / Analisar → decompor a regra do problema em condições lógicas coerentes para discriminar os casos previstos.  
Verbos de Bloom: analisar, discriminar, relacionar

K06 / Analisar → estruturar o encadeamento de decisões preservando cobertura e precedência entre casos.  
Verbos de Bloom: estruturar, distinguir, examinar


**Especificação de Disposições**  
- Rigor lógico  
- Atenção a fronteiras e distinção de casos  
- Clareza na correspondência entre regra e condição

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto desta tarefa.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT02.2 | Modelar regras condicionais por limiares e estruturar cobertura de casos em decisões computacionais | Rigor lógico; atenção a fronteiras; clareza de correspondência | K04 | Decompor a regra do problema em condições lógicas coerentes para discriminar os casos previstos |
| CT02.2 | Modelar regras condicionais por limiares e estruturar cobertura de casos em decisões computacionais | Rigor lógico; atenção a fronteiras; clareza de correspondência | K06 | Estruturar o encadeamento de decisões preservando cobertura e precedência entre casos |
| CT02.2 | Modelar regras condicionais por limiares e estruturar cobertura de casos em decisões computacionais | Rigor lógico; atenção a fronteiras; clareza de correspondência | K02 | Utilizar representação numérica compatível com as comparações exigidas pelas condições |

**Definição de Ativação**
- Restrição de ativação: **obrigatória**
- Modo de ativação: **analítica**
- Função de ativação: **núcleo**
- Justificativa curta baseada na tarefa: a tarefa depende diretamente da análise das regras do enunciado e de sua tradução em condições e ramos de decisão; sem essa competência, não há correspondência confiável entre índice lido e notificação emitida.



### Competência CT02.3

**Título da Competência**  
Construir programas condicionais verificáveis que emitam respostas coerentes com regras explicitadas.

**Descrição Textual**  
Trata-se de integrar leitura de dados, estruturação de decisões e emissão de mensagens em programas introdutórios, de modo que o comportamento final seja coerente, justificável e observável a partir das regras implementadas.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1, LO3, LO4
- K mobilizados (Núcleo): K01, K05, K06

**Especificação de Conhecimentos**
- **K01 — Modelo de execução e noção de estado:** é diretamente evidenciado quando o estudante consegue articular leitura, decisão e saída como um encadeamento de estados do programa.
- **K05 — Estrutura sequencial e E/S básica:** é diretamente evidenciado pela organização do fluxo executável e pela produção de uma saída observável.
- **K06 — Estruturas de seleção:** é diretamente evidenciado pela materialização da lógica decisória no comportamento final do programa.



**Pareamento Conhecimento–Habilidade**

K01 / Analisar → explicitar o encadeamento de estados do programa ao longo da decisão e da emissão da saída.  
Verbos de Bloom: rastrear, modelar, estruturar

K05 / Aplicar → materializar uma sequência verificável de leitura, processamento e emissão de mensagem.  
Verbos de Bloom: implementar, executar, operar

K06 / Criar → conceber a estrutura condicional do programa de forma coesa para produzir a notificação adequada.  
Verbos de Bloom: conceber, desenvolver, programar


**Especificação de Disposições**  
- Coerência técnica  
- Atenção à consistência entre regra e saída  
- Disciplina na verificação do comportamento  
- Clareza na justificativa

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto desta tarefa.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT02.3 | Construir programas condicionais verificáveis que emitam respostas coerentes com regras explicitadas | Coerência técnica; atenção à consistência; disciplina na verificação; clareza na justificativa | K01 | Explicitar o encadeamento de estados do programa ao longo da decisão e da emissão da saída |
| CT02.3 | Construir programas condicionais verificáveis que emitam respostas coerentes com regras explicitadas | Coerência técnica; atenção à consistência; disciplina na verificação; clareza na justificativa | K05 | Materializar uma sequência verificável de leitura, processamento e emissão de mensagem |
| CT02.3 | Construir programas condicionais verificáveis que emitam respostas coerentes com regras explicitadas | Coerência técnica; atenção à consistência; disciplina na verificação; clareza na justificativa | K06 | Conceber a estrutura condicional do programa de forma coesa para produzir a notificação adequada |
| CT02.3 | Construir programas condicionais verificáveis que emitam respostas coerentes com regras explicitadas | Coerência técnica; atenção à consistência; disciplina na verificação; clareza na justificativa | K04 | Verificar a correspondência entre a condição avaliada e a mensagem emitida pelo programa |

**Definição de Ativação**
- Restrição de ativação: **obrigatória**
- Modo de ativação: **construtiva e justificatória**
- Função de ativação: **núcleo**
- Justificativa curta baseada na tarefa: a solução final só se completa quando o estudante integra leitura, seleção e saída em um programa funcional e consegue justificar por que a mensagem emitida decorre da regra implementada.
