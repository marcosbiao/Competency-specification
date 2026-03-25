# RELATÓRIO CSP — TASK16.2

## Identificação da Task
- **Código da Task:** TASK16.2
- **Título:** Maratona de Programação em C com Vetores, Matrizes e Funções
- **Nível/Curso:** Graduação, em disciplina introdutória de programação
- **Componente Curricular:** Introdução à Programação
- **Contexto:** atividade prática em laboratório, em equipes de até três estudantes, com um computador por equipe, tempo limitado e submissão em juiz automático
- **Nível de proficiência:** Intermediário

## Introdução
Este relatório situa a TASK16.2 na fase de **Autoria de Competências** do **Competency Specification Process (CSP)**. A tarefa consiste em uma maratona de programação em linguagem C, realizada em laboratório e organizada em torno de problemas introdutórios que exigem leitura de entrada, processamento correto de dados, manipulação de vetores e matrizes e uso de função com retorno. As evidências são diretamente observáveis no código-fonte produzido, nas saídas geradas e na aceitação das submissões em juiz automático.

A atividade sustenta o modelo **K–S–D** porque mobiliza conhecimentos computacionais claramente delimitados do catálogo da disciplina, exige habilidades observáveis de implementação e demanda disposições compatíveis com precisão, persistência, colaboração e respeito às restrições operacionais. A seleção abaixo evita redundância e mantém foco em capacidades reutilizáveis da disciplina.

---

## 1. Análise da Entidade Instrucional

### 1.1 Título
**Maratona de Programação em C com Vetores, Matrizes e Funções**

### 1.2 Descrição
Atividade prática de programação introdutória em linguagem C, desenvolvida em equipes, com resolução de múltiplos problemas sob tempo limitado. Os enunciados demandam leitura e escrita de dados, processamento sequencial, uso de estruturas de repetição e seleção, manipulação de vetores e matrizes e definição de função simples com retorno. O contexto de correção por juiz automático reforça a necessidade de precisão funcional e aderência estrita ao formato de saída.

### 1.3 Processo de Desenvolvimento da Solução
1. Ler e interpretar cada enunciado, identificando entradas, processamento e saídas esperadas.
2. Escolher os tipos de dados e as estruturas adequadas para representar as informações.
3. Estruturar o algoritmo com sequência, seleção e repetição conforme o problema.
4. Implementar percursos, verificações e transformações sobre vetores e matrizes quando necessário.
5. Definir função simples com parâmetros e retorno quando o problema exigir decomposição funcional.
6. Compilar, revisar a consistência da saída e submeter a solução ao juiz automático.

### 1.4 Resultados Esperados
- Programas em C correspondentes aos problemas resolvidos.
- Submissões válidas no sistema de correção.
- Saídas compatíveis com os formatos exigidos.
- Soluções funcionalmente corretas para testes previstos e não previstos.
- Evidências de manipulação adequada de vetores, matrizes e funções simples.

### 1.5 Contexto de Aquisição
- **Curso/organização:** disciplina de Introdução à Programação, em nível de graduação.
- **Ambiente:** laboratório, com computador compartilhado por equipe.
- **Forma de realização:** equipes de até três integrantes, com rodízio de operador a cada vinte minutos.
- **Restrições:** duas horas de duração, consulta apenas a material impresso e sem acesso à internet.
- **Avaliação:** correção funcional por juiz automático, com foco em aderência ao enunciado, consistência entre entrada, processamento e saída e submissão válida.

### 1.6 Perfil do Público-Alvo
- **Nível:** estudantes em etapa introdutória de programação.
- **Pré-requisitos:** noções básicas de linguagem C, tipos primitivos, entrada e saída, estruturas de controle e organização elementar de algoritmos.
- **Necessidades:** consolidar precisão sintática e semântica, fortalecer raciocínio de processamento de coleções homogêneas e desenvolver segurança na implementação sob restrição de tempo.

### 1.7 Nível de Proficiência (critérios e dimensões)

| Nível | Compreensão do problema | Estruturação do algoritmo | Uso de estruturas da linguagem C | Consistência entre entrada, processamento e saída | Desempenho na submissão |
|---|---|---|---|---|---|
| **N1 - Inicial** | Identifica apenas partes do enunciado e omite requisitos relevantes. | Organiza passos de modo incompleto ou inconsistente. | Emprega tipos e estruturas com erros recorrentes. | Produz incompatibilidades frequentes com o enunciado. | Requer muitas correções para obter submissão válida. |
| **N2 - Intermediário** | Reconhece entradas, saídas e regras principais, com pequenas lacunas. | Estrutura solução funcional para casos mais diretos. | Usa tipos, repetições e seleções de modo funcional, ainda com ajustes pontuais. | Mantém consistência parcial, com falhas de formatação ou cobertura de casos. | Obtém submissões válidas em parte dos problemas. |
| **N3 - Proficiente** | Interpreta corretamente o enunciado e preserva os requisitos essenciais. | Organiza fluxo lógico coerente, com controle adequado de casos e percursos. | Usa adequadamente tipos, vetores, matrizes e funções simples. | Garante consistência funcional e aderência ao formato solicitado. | Obtém submissões válidas e corretas em problemas representativos. |
| **N4 - Avançado** | Antecipa casos limite e traduz o enunciado em estratégia de solução robusta. | Estrutura solução de forma estável, clara e facilmente verificável. | Integra estruturas com precisão e economia de construção. | Mantém comportamento robusto inclusive em casos menos evidentes. | Sustenta taxa elevada de correção e ajuste eficiente durante a maratona. |


## 2. Seleção e Enumeração de Conhecimentos

**K02 — Variáveis, constantes e tipos primitivos**
- Representação de dados simples por identificadores e tipos coerentes.
- Uso de inteiros, caracteres e ponto flutuante em operações básicas.
- Atribuição e manutenção de coerência de tipos durante o processamento.
- **Justificativa de mobilização na tarefa:** os problemas exigem declaração e uso consistente de variáveis e tipos para ler, processar e exibir resultados.

**K03 — Expressões aritméticas e avaliação**
- Construção de cálculos com operadores e precedência adequados.
- Composição de expressões para contagem, soma e transformação de valores.
- Produção de resultados numéricos coerentes com o enunciado.
- **Justificativa de mobilização na tarefa:** a maratona inclui problemas de soma, contagem e processamento quantitativo que dependem de avaliação correta de expressões.

**K04 — Expressões lógicas e condições**
- Construção de sentenças relacionais e lógicas para verificação de casos.
- Interpretação de verdade e falsidade em regras do problema.
- Formulação de condições compatíveis com decisões e validações.
- **Justificativa de mobilização na tarefa:** a verificação de propriedades em matrizes e a análise de acertos requerem condições corretas e rastreáveis.

**K05 — Estrutura sequencial e E/S básica**
- Organização do fluxo entrada → processamento → saída.
- Leitura e exibição de dados em formato verificável.
- Encadeamento coerente de comandos em programas introdutórios.
- **Justificativa de mobilização na tarefa:** todas as soluções dependem de leitura correta, processamento ordenado e saída aderente ao formato exigido pelo juiz automático.

**K06 — Estruturas de seleção**
- Escolha entre caminhos alternativos de execução com base em condições.
- Cobertura de casos por if/else e encadeamentos simples.
- Implementação de regras distintas conforme valores ou propriedades observadas.
- **Justificativa de mobilização na tarefa:** parte dos problemas exige classificar, verificar ou decidir comportamentos a partir de critérios explícitos.

**K07 — Estruturas de repetição**
- Percurso iterativo controlado por contagem ou condição.
- Uso de laços para varrer dados e acumular resultados.
- Garantia de parada e cobertura adequada de elementos.
- **Justificativa de mobilização na tarefa:** a leitura e o processamento de vetores e matrizes exigem laços corretos e sistemáticos.

**K08 — Vetores e matrizes em C**
- Representação de coleções homogêneas indexadas em uma ou duas dimensões.
- Acesso posicional, leitura, atualização e análise de elementos.
- Percorrimento de linhas, colunas e sequências com controle por índice.
- **Justificativa de mobilização na tarefa:** o núcleo temático da maratona envolve manipulação de vetores e matrizes em problemas introdutórios.

**K11 — Subprogramas: procedimentos e funções**
- Definição e invocação de funções com parâmetros e retorno.
- Organização modular de partes da solução.
- Encapsulamento de comportamento simples e reutilizável.
- **Justificativa de mobilização na tarefa:** a atividade inclui construção de função simples com retorno, mobilizando decomposição funcional elementar.


## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Implementar programas introdutórios em C com declaração coerente de variáveis, uso adequado de tipos primitivos e organização correta de entrada, processamento e saída.  
**K associados:** K02, K05

**LO2.** Construir soluções com expressões aritméticas, lógicas e estruturas de seleção para verificar condições e produzir resultados corretos.  
**K associados:** K03, K04, K06

**LO3.** Percorrer e processar vetores e matrizes por meio de laços adequados, realizando leitura, contagem, soma, verificação e transformação de dados.  
**K associados:** K07, K08, K05

**LO4.** Definir e utilizar funções simples com parâmetros e retorno coerentes para decompor partes da solução.  
**K associados:** K11, K02, K05

**LO5.** Garantir consistência funcional entre entradas, processamento interno e saídas observáveis em problemas introdutórios submetidos a correção automática.  
**K associados:** K02, K03, K04, K05

## 4. Definição de Competências

### 4.1 Competência Geral
Mobilizar princípios de programação imperativa para construir soluções computacionais corretas, verificáveis e reutilizáveis em problemas introdutórios de processamento de dados.

**Alinhamento geral com BNCC:** embora a tarefa pertença ao ensino superior, ela converge de modo amplo com a competência de aplicar princípios e técnicas da Computação para identificar problemas e criar soluções computacionais. Não se propõe uso de códigos BNCC nesta especificação por não se tratar de contexto da educação básica.

### 4.2 Especificações de Competências

#### CT16.2.1
**Título da Competência**  
Manipular coleções homogêneas com vetores e matrizes em C

**Descrição Textual**  
Representar, percorrer e processar coleções homogêneas indexadas em uma ou duas dimensões, utilizando laços e operações compatíveis com a estrutura dos dados.

**Cobertura e rastreabilidade**
- LOs cobertos: LO3, LO5
- K mobilizados (Núcleo): K05, K07, K08

**Especificação de Conhecimentos**
- **K05:** organiza a sequência de leitura, processamento e saída exigida para operar coleções de forma verificável.
- **K07:** sustenta os percursos iterativos necessários para varrer posições e acumular resultados.
- **K08:** fornece a estrutura de representação e acesso posicional a vetores e matrizes evidenciada diretamente nos programas.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**
K05 / Aplicar → estruturar o fluxo de entrada, processamento e saída para operar coleções de dados de forma verificável.  
Verbos de Bloom: executar, implementar, operar

K07 / Aplicar → percorrer vetores e matrizes com laços corretos, garantindo cobertura e parada adequadas.  
Verbos de Bloom: iterar, implementar, usar

K08 / Aplicar → representar e manipular vetores e matrizes por índice para leitura, verificação e transformação de dados.  
Verbos de Bloom: manipular, implementar, operar


**Especificação de Disposições**  
- Precisão no acesso posicional aos dados.
- Atenção a limites e dimensões das estruturas.
- Persistência na revisão de inconsistências de processamento.
- Disciplina na observância do formato de saída.

**Competências Alinhadas à BNCC**  
Alinhamento amplo, sem código: construir soluções computacionais com uso de estruturas de dados adequadas.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.2.1 | Manipular coleções homogêneas com vetores e matrizes em C | Precisão, atenção a limites, persistência | K05 | Estruturar o fluxo de E/S para operar coleções de forma verificável |
| CT16.2.1 | Manipular coleções homogêneas com vetores e matrizes em C | Precisão, atenção a limites, persistência | K07 | Percorrer vetores e matrizes com laços corretos |
| CT16.2.1 | Manipular coleções homogêneas com vetores e matrizes em C | Precisão, atenção a limites, persistência | K08 | Representar e manipular coleções indexadas em uma ou duas dimensões |

**Definição de Ativação**
- **Restrição de ativação:** obrigatória
- **Modo de ativação:** construtiva
- **Função de ativação:** núcleo
- **Justificativa curta baseada na tarefa:** a maratona explicita problemas centrados em vetores e matrizes. A competência é ativada diretamente na implementação, pois as evidências aparecem no código, no percurso dos dados e na correção das saídas produzidas.


#### CT16.2.2
**Título da Competência**  
Controlar o fluxo de processamento com condições e repetições

**Descrição Textual**  
Organizar o comportamento de programas introdutórios por meio de expressões lógicas, seleção e repetição, assegurando coerência entre regras do problema e execução do algoritmo.

**Cobertura e rastreabilidade**
- LOs cobertos: LO2, LO3, LO5
- K mobilizados (Núcleo): K04, K06, K07

**Especificação de Conhecimentos**
- **K04:** permite formular as condições que expressam corretamente as regras de verificação do problema.
- **K06:** materializa decisões computacionais em ramos de execução observáveis no programa.
- **K07:** garante iteração controlada para processar sequências e estruturas bidimensionais.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**
K04 / Aplicar → formular expressões lógicas coerentes com critérios de verificação e classificação do problema.  
Verbos de Bloom: aplicar, usar, implementar

K06 / Aplicar → selecionar caminhos de execução adequados a partir de condições explicitadas no algoritmo.  
Verbos de Bloom: implementar, operar, resolver

K07 / Aplicar → repetir operações de processamento de dados com controle correto de início, continuidade e parada.  
Verbos de Bloom: iterar, executar, usar


**Especificação de Disposições**  
- Rigor lógico na formulação de condições.
- Cuidado com cobertura de casos.
- Atenção à parada segura dos laços.
- Responsabilidade na validação do comportamento esperado.

**Competências Alinhadas à BNCC**  
Alinhamento amplo, sem código: construir algoritmos com sequências, seleções condicionais e repetições.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.2.2 | Controlar o fluxo de processamento com condições e repetições | Rigor lógico, cobertura de casos, atenção à parada | K04 | Formular expressões lógicas coerentes com os critérios do problema |
| CT16.2.2 | Controlar o fluxo de processamento com condições e repetições | Rigor lógico, cobertura de casos, atenção à parada | K06 | Selecionar caminhos de execução adequados |
| CT16.2.2 | Controlar o fluxo de processamento com condições e repetições | Rigor lógico, cobertura de casos, atenção à parada | K07 | Repetir operações com controle correto de laço |

**Definição de Ativação**
- **Restrição de ativação:** obrigatória
- **Modo de ativação:** construtiva
- **Função de ativação:** núcleo
- **Justificativa curta baseada na tarefa:** os problemas demandam verificações, classificações e percursos. A competência se ativa na tradução das regras do enunciado em condições e iterações corretas, diretamente observáveis no comportamento do programa.


#### CT16.2.3
**Título da Competência**  
Modularizar soluções introdutórias com funções simples

**Descrição Textual**  
Decompor partes de um problema em funções simples, com parâmetros e retorno compatíveis, preservando a coerência entre dados recebidos, processamento interno e resultado produzido.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1, LO4
- K mobilizados (Núcleo): K02, K05, K11

**Especificação de Conhecimentos**
- **K02:** assegura escolha e uso coerente dos tipos envolvidos em parâmetros, variáveis locais e valores de retorno.
- **K05:** sustenta a organização funcional do fluxo de dados entre chamada, processamento e resultado.
- **K11:** explicita a decomposição da solução em funções com responsabilidade delimitada.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**
K02 / Aplicar → declarar variáveis, parâmetros e retornos com tipos coerentes ao papel de cada dado.  
Verbos de Bloom: implementar, usar, operar

K05 / Aplicar → organizar a interação entre função e programa principal de modo verificável.  
Verbos de Bloom: executar, implementar, operar

K11 / Aplicar → definir e invocar funções simples com responsabilidade clara e retorno compatível com o problema.  
Verbos de Bloom: implementar, programar, usar


**Especificação de Disposições**  
- Clareza na delimitação de responsabilidades.
- Precisão na passagem de dados e interpretação de retorno.
- Organização do código com foco em verificabilidade.
- Persistência na correção de inconsistências entre partes da solução.

**Competências Alinhadas à BNCC**  
Alinhamento amplo, sem código: decompor soluções e automatizá-las por meio de linguagem de programação.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.2.3 | Modularizar soluções introdutórias com funções simples | Clareza, precisão, organização | K02 | Declarar variáveis, parâmetros e retornos com tipos coerentes |
| CT16.2.3 | Modularizar soluções introdutórias com funções simples | Clareza, precisão, organização | K05 | Organizar a interação entre função e programa principal |
| CT16.2.3 | Modularizar soluções introdutórias com funções simples | Clareza, precisão, organização | K11 | Definir e invocar funções simples com responsabilidade clara |

**Definição de Ativação**
- **Restrição de ativação:** obrigatória
- **Modo de ativação:** construtiva
- **Função de ativação:** núcleo
- **Justificativa curta baseada na tarefa:** a descrição pedagógica explicita a construção de função simples com retorno. Assim, a competência é ativada na própria implementação e pode ser diagnosticada por meio da assinatura, chamada e comportamento funcional da solução.

#### CT16.2.4
**Título da Competência**  
Produzir soluções corretas de entrada, processamento e saída em C

**Descrição Textual**  
Implementar soluções introdutórias em linguagem C com consistência funcional entre dados de entrada, cálculos realizados e saídas observáveis, atendendo a especificações formais de correção.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1, LO2, LO5
- K mobilizados (Núcleo): K02, K03, K05

**Especificação de Conhecimentos**
- **K02:** permite representar corretamente os dados tratados na solução.
- **K03:** sustenta cálculos, acumulações e transformações numéricas requeridas pelos problemas.
- **K05:** garante o encadeamento verificável entre leitura, processamento e exibição de resultados.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**
K02 / Aplicar → utilizar variáveis e tipos primitivos coerentes para representar dados de entrada e resultados.  
Verbos de Bloom: implementar, usar, operar

K03 / Aplicar → calcular expressões aritméticas corretamente para gerar resultados compatíveis com a especificação.  
Verbos de Bloom: calcular, computar, resolver

K05 / Aplicar → organizar programas com fluxo verificável de leitura, processamento e saída aderente ao enunciado.  
Verbos de Bloom: executar, implementar, operar


**Especificação de Disposições**  
- Exatidão na implementação.
- Atenção à aderência formal ao enunciado.
- Compromisso com verificabilidade da solução.
- Persistência diante de testes não previstos.

**Competências Alinhadas à BNCC**  
Alinhamento amplo, sem código: criar soluções computacionais corretas para problemas formulados.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.2.4 | Produzir soluções corretas de entrada, processamento e saída em C | Exatidão, aderência formal, verificabilidade | K02 | Utilizar variáveis e tipos coerentes para representar dados |
| CT16.2.4 | Produzir soluções corretas de entrada, processamento e saída em C | Exatidão, aderência formal, verificabilidade | K03 | Calcular expressões aritméticas corretamente |
| CT16.2.4 | Produzir soluções corretas de entrada, processamento e saída em C | Exatidão, aderência formal, verificabilidade | K05 | Organizar fluxo verificável de leitura, processamento e saída |

**Definição de Ativação**
- **Restrição de ativação:** obrigatória
- **Modo de ativação:** construtiva
- **Função de ativação:** núcleo
- **Justificativa curta baseada na tarefa:** a correção por juiz automático torna diretamente observável a competência de produzir soluções funcionalmente corretas. Ela é ativada na implementação integral de cada programa e evidenciada pelas submissões válidas e aceitas.
