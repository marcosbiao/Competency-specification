# RELATÓRIO CSP: TASK16.1

## Introdução

Este relatório situa a TASK16.1 na fase de **Autoria de Competências** do Competency Specification Process. A tarefa consiste em uma maratona prática de programação em C, realizada em laboratório, com resolução de problemas sobre vetores, matrizes e funções, submissão em juiz automático e restrição de tempo. As evidências são observáveis porque o desempenho se materializa em programas executáveis, saídas compatíveis com o enunciado e submissões válidas no ambiente de correção.

A tarefa sustenta o modelo **Conhecimento–Habilidade–Disposição** porque mobiliza um conjunto delimitado de conhecimentos da disciplina de Introdução à Programação, exige habilidades técnicas verificáveis na implementação e depende de disposições como precisão, disciplina de verificação e cuidado com a conformidade da solução. A seleção de K, LO e CT foi feita com base exclusiva na descrição pedagógica e no catálogo fixo da disciplina, preservando reuso e rastreabilidade.

---

## 1. Análise da Entidade Instrucional

### Título

**TASK16.1**  
**Maratona de Programação em C com Vetores, Matrizes e Funções**

### Descrição

Atividade prática de programação introdutória, em equipes de até três estudantes, realizada em laboratório com um computador por equipe e tempo total de duas horas. Cada equipe deve resolver o maior número possível de problemas em C, envolvendo processamento de dados, vetores, matrizes e função simples com retorno, com submissão em juiz automático e validação por testes não conhecidos previamente.

### Processo de Desenvolvimento da Solução

1. Ler e interpretar cada enunciado, identificando entradas, saídas e restrições.
2. Organizar a solução em etapas de leitura, processamento e saída.
3. Selecionar estruturas de controle e de dados adequadas ao problema.
4. Implementar a solução em C, utilizando variáveis, expressões, decisões, repetições, vetores, matrizes e, quando necessário, funções.
5. Conferir a consistência entre entrada, processamento e saída antes da submissão.
6. Submeter a solução no juiz automático e revisar quando necessário, dentro do tempo disponível.

### Resultados Esperados

1. Arquivos fonte em linguagem C para os problemas resolvidos.
2. Submissões registradas no sistema de correção.
3. Soluções aceitas quando corretas nos testes do juiz.
4. Saídas compatíveis com o enunciado, sem inconsistências observáveis entre dados processados e resultados exibidos.

### Contexto de Aquisição

**Curso:** Introdução à Programação  
**Organização:** atividade individual  
**Ambiente:** laboratório de informática ou avaliação prática escrita  
**Avaliação:** observação direta do artefato produzido, das saídas obtidas e da justificativa breve associada à solução

### Perfil do Público-Alvo

Estudantes de uma disciplina inicial de programação que já tiveram contato com sintaxe básica em C, variáveis, entrada e saída, estruturas de controle e noções iniciais de dados estruturados. A tarefa demanda leitura cuidadosa de enunciados, implementação sob restrição temporal e capacidade de manter precisão sintática e semântica em ambiente de correção automática.

### Nível de Proficiência (critérios e dimensões)

**Nível alvo inferido da tarefa:** intermediário.

| Nível | Interpretação do problema | Estruturação do programa | Manipulação de dados estruturados | Conformidade da saída |
|---|---|---|---|---|
| **N1 - Inicial** | Identifica apenas parte das entradas e saídas. | Organiza comandos sem clareza de fluxo. | Usa vetores ou matrizes com erros de índice ou percorrimento. | Produz resultados parciais ou formato inadequado. |
| **N2 - Intermediário** | Reconhece entradas, saídas e parte das regras. | Estrutura leitura, processamento e saída de modo funcional. | Percorre e atualiza estruturas simples com apoio. | Atende parte do formato exigido. |
| **N3 - Proficiente** | Traduz corretamente regras e restrições em estrutura de solução. | Mantém fluxo coerente e verificável em todo o programa. | Manipula vetores e matrizes com correção e consistência. | Atende integralmente ao formato e à lógica esperada. |
| **N4 - Avançado** | Antecipa casos limite e ajusta a solução com baixo retrabalho. | Estrutura a solução com alta coesão e mínima redundância. | Integra estruturas e subprogramas com segurança e generalidade. | Mantém robustez frente a casos variados e restrições implícitas. |


## 2. Seleção e Enumeração de Conhecimentos

### **K01 — Modelo de execução e noção de estado (paradigma imperativo)**

* Compreensão operacional de que o programa evolui por mudanças de estado durante a execução.
* Relação entre atribuição, ordem dos comandos e efeito produzido.
* Base para justificar o fluxo da solução e a atualização de valores.

**Justificativa de mobilização na tarefa:** a maratona exige interpretar o comportamento do programa, organizar etapas de execução e manter coerência entre estados intermediários e resultado final.

### **K02 — Variáveis, constantes e tipos primitivos**

* Representação de dados simples por meio de identificadores e tipos coerentes.
* Uso de atribuição, armazenamento e manipulação de valores numéricos e caracteres.
* Coerência básica entre o papel do dado e seu tipo.

**Justificativa de mobilização na tarefa:** os problemas exigem declarar e usar variáveis compatíveis com leituras, estados intermediários, contagens, somas e resultados finais.

### **K03 — Expressões aritméticas e avaliação**

* Construção de expressões com operadores aritméticos e precedência adequada.
* Avaliação correta de cálculos e atualizações por atribuição.
* Controle de resultados coerentes em operações de processamento.

**Justificativa de mobilização na tarefa:** a atividade inclui contagem, soma e processamento numérico, o que exige cálculo correto e avaliação consistente de expressões.

### **K04 — Expressões lógicas e condições**

* Construção de condições booleanas a partir de operadores relacionais e lógicos.
* Interpretação de verdade e falsidade em regras computacionais.
* Formulação de testes coerentes para verificação de propriedades.

**Justificativa de mobilização na tarefa:** parte dos problemas envolve verificação e análise de dados, exigindo condições bem formuladas para distinguir casos válidos e resultados esperados.

### **K05 — Estrutura sequencial e E/S básica**

* Organização do programa como sequência verificável de leitura, processamento e saída.
* Uso de entrada e saída básica na linguagem adotada.
* Produção de resultados compatíveis com o formato requerido.

**Justificativa de mobilização na tarefa:** a evidência principal da atividade é a transformação correta de entradas em saídas aceitas pelo juiz automático.

### **K06 — Estruturas de seleção**

* Escolha de caminhos alternativos com base em condições.
* Cobertura de casos e tratamento de regras distintas.
* Encadeamento de decisões simples em programas introdutórios.

**Justificativa de mobilização na tarefa:** problemas de classificação, verificação e transformação de matrizes exigem decisões explícitas e tratamento de casos.

### **K07 — Estruturas de repetição**

* Execução iterativa controlada por contador ou condição.
* Varredura e processamento acumulativo de conjuntos de dados.
* Garantia de parada e coerência do laço.

**Justificativa de mobilização na tarefa:** vetores, matrizes e sequências de respostas exigem percorrimento, contagem, soma e análise iterativa.

### **K08 — Vetores e matrizes em C**

* Representação de coleções homogêneas indexadas em uma ou duas dimensões.
* Acesso, atualização e percorrimento de elementos.
* Leitura e processamento posicional de dados estruturados.

**Justificativa de mobilização na tarefa:** o núcleo temático da atividade recai diretamente sobre problemas com vetores e matrizes.

### **K11 — Subprogramas: procedimentos e funções**

* Definição e invocação de funções com parâmetros e retorno.
* Organização modular do programa por responsabilidades locais.
* Integração entre subprogramas e fluxo principal.

**Justificativa de mobilização na tarefa:** a atividade inclui explicitamente a construção de função simples com retorno.


## 3. Identificação de Objetivos de Aprendizagem

### LO1

Traduzir problemas simples em algoritmos claros, organizando a solução em etapas coerentes de leitura, processamento e saída.

**K associados:** K01, K05, K06, K07

### LO2

Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples em programas introdutórios.

**K associados:** K02, K03

### LO3

Realizar entrada e saída de dados com formatação apropriada e verificações mínimas compatíveis com o enunciado.

**K associados:** K02, K04, K05, K06

### LO4

Modularizar soluções por funções ou procedimentos com assinaturas, parâmetros e tipos adequados.

**K associados:** K02, K05, K11

### LO5

Representar e processar coleções homogêneas com vetores e matrizes, utilizando percursos e verificações compatíveis com o problema.

**K associados:** K04, K06, K07, K08



## 4. Definição de Competências

### 4.1 Competência Geral

Como se trata de atividade de ensino superior, **não há aplicação normativa direta da BNCC**. Ainda assim, a tarefa se alinha, em nível geral, à competência de construir soluções computacionais corretas, estruturadas e verificáveis por meio de programação, com ênfase em interpretação de problemas, processamento de dados e precisão de implementação.

### 4.2 Especificações de Competências

#### CT16.1.1

**Título da Competência**  
Traduzir problemas simples em algoritmos claros por decomposição e organização do fluxo da solução.

**Descrição Textual**  
Interpretar enunciados introdutórios e estruturar algoritmos claros, decompondo o problema em etapas operacionais e organizando a lógica de sequência, decisão e repetição de forma verificável.

**Cobertura e rastreabilidade**

* LOs cobertos: LO1
* K mobilizados (Núcleo): K01, K05, K06, K07

**Especificação de Conhecimentos**

* **K01:** compreensão do estado do programa; evidenciada pela organização coerente das atualizações ao longo da solução.
* **K05:** estruturação sequencial de leitura, processamento e saída; evidenciada pela clareza operacional do algoritmo.
* **K06:** seleção de caminhos alternativos; evidenciada no tratamento de casos e regras do problema.
* **K07:** repetição controlada; evidenciada na formulação de percursos e iterações necessárias.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Analisar.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → rastrear o estado do programa e justificar a ordem das operações na solução.  
Verbos de Bloom: analisar, rastrear, estruturar

K05 / Analisar → decompor o problema em etapas coerentes de entrada, processamento e saída.  
Verbos de Bloom: decompor, estruturar, modelar

K06 / Analisar → distinguir casos do problema e relacioná-los a decisões adequadas no algoritmo.  
Verbos de Bloom: distinguir, relacionar, analisar

K07 / Analisar → examinar a necessidade de iteração e estruturar laços compatíveis com o objetivo do processamento.  
Verbos de Bloom: examinar, estruturar, decompor


**Especificação de Disposições**

* clareza na leitura do problema
* rigor na decomposição da solução
* atenção à coerência do fluxo lógico

**Competências Alinhadas à BNCC**  
Alinhamento geral ao eixo de algoritmos e resolução computacional de problemas.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.1.1 | Traduzir problemas simples em algoritmos claros | clareza, rigor, atenção ao fluxo | K01 | rastrear o estado do programa e justificar a ordem das operações |
| CT16.1.1 | Traduzir problemas simples em algoritmos claros | clareza, rigor, atenção ao fluxo | K05 | decompor o problema em etapas coerentes de entrada, processamento e saída |
| CT16.1.1 | Traduzir problemas simples em algoritmos claros | clareza, rigor, atenção ao fluxo | K06 | distinguir casos do problema e relacioná-los a decisões adequadas |
| CT16.1.1 | Traduzir problemas simples em algoritmos claros | clareza, rigor, atenção ao fluxo | K07 | examinar a necessidade de iteração e estruturar laços compatíveis |

**Definição de Ativação**

* Restrição de ativação: obrigatória
* Modo de ativação: analítica
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: a atividade exige interpretar enunciados, produzir algoritmos em C e resolver problemas sob tempo limitado. Isso torna central a capacidade de decompor o problema e organizar o fluxo lógico da solução.


#### CT16.1.2

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples.

**Descrição Textual**  
Representar e processar dados simples com tipos adequados, realizando cálculos e atualizações coerentes em programas introdutórios.

**Cobertura e rastreabilidade**

* LOs cobertos: LO2
* K mobilizados (Núcleo): K02, K03

**Especificação de Conhecimentos**

* **K02:** uso coerente de variáveis, constantes e tipos primitivos; evidenciado nas declarações e atualizações do programa.
* **K03:** avaliação correta de expressões aritméticas; evidenciada em contagens, somas e cálculos intermediários.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar e utilizar variáveis e tipos primitivos compatíveis com o papel de cada dado.  
Verbos de Bloom: implementar, usar, operar

K03 / Aplicar → calcular expressões e atualizar valores de forma coerente durante o processamento.  
Verbos de Bloom: calcular, computar, resolver


**Especificação de Disposições**

* precisão no uso de tipos
* cuidado com valores intermediários
* atenção à consistência dos cálculos

**Competências Alinhadas à BNCC**  
Alinhamento geral à representação e manipulação de dados em programação.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.1.2 | Manipular dados com tipos primitivos | precisão, cuidado, atenção à consistência | K02 | declarar e utilizar variáveis e tipos primitivos compatíveis |
| CT16.1.2 | Manipular dados com tipos primitivos | precisão, cuidado, atenção à consistência | K03 | calcular expressões e atualizar valores de forma coerente |

**Definição de Ativação**

* Restrição de ativação: obrigatória
* Modo de ativação: construtiva
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: os problemas envolvem leitura de valores, armazenamento em variáveis, contagem, soma e atualização de resultados. Sem esse domínio, a solução não produz comportamento funcional adequado.

#### CT16.1.3

**Título da Competência**  
Realizar entrada e saída de dados com validação mínima e formatação apropriada.

**Descrição Textual**  
Ler dados, produzir saídas no formato exigido e realizar verificações mínimas compatíveis com as regras do problema, preservando consistência entre entrada, processamento e exibição.

**Cobertura e rastreabilidade**

* LOs cobertos: LO3
* K mobilizados (Núcleo): K02, K04, K05, K06

**Especificação de Conhecimentos**

* **K02:** escolha de tipos compatíveis com os dados lidos e exibidos; evidenciada pela coerência entre entrada e saída.
* **K04:** formulação de condições simples de verificação; evidenciada em checagens mínimas exigidas pelo problema.
* **K05:** organização de leitura e saída; evidenciada pela conformidade com o formato requerido.
* **K06:** tratamento de casos alternativos; evidenciado quando diferentes situações exigem respostas distintas.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → escolher tipos adequados para ler, armazenar e exibir os dados do problema.  
Verbos de Bloom: implementar, usar, operar

K04 / Aplicar → formular verificações mínimas coerentes com as regras de leitura e exibição.  
Verbos de Bloom: implementar, resolver, usar

K05 / Aplicar → estruturar a entrada e a saída de modo compatível com o formato exigido.  
Verbos de Bloom: executar, implementar, apresentar

K06 / Aplicar → selecionar respostas ou formatos distintos quando o problema exigir tratamento de casos.  
Verbos de Bloom: implementar, operar, resolver


**Especificação de Disposições**

* atenção ao formato da saída
* disciplina na conferência das leituras
* cuidado com a coerência entre dados e resposta

**Competências Alinhadas à BNCC**  
Alinhamento geral à produção de artefatos computacionais corretos e verificáveis.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.1.3 | Realizar entrada e saída de dados | atenção ao formato, disciplina, cuidado com coerência | K02 | escolher tipos adequados para ler, armazenar e exibir dados |
| CT16.1.3 | Realizar entrada e saída de dados | atenção ao formato, disciplina, cuidado com coerência | K04 | formular verificações mínimas coerentes com as regras do problema |
| CT16.1.3 | Realizar entrada e saída de dados | atenção ao formato, disciplina, cuidado com coerência | K05 | estruturar a entrada e a saída conforme o formato exigido |
| CT16.1.3 | Realizar entrada e saída de dados | atenção ao formato, disciplina, cuidado com coerência | K06 | selecionar respostas ou formatos distintos quando necessário |

**Definição de Ativação**

* Restrição de ativação: obrigatória
* Modo de ativação: construtiva
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: o juiz automático exige submissões com comportamento compatível com o enunciado e saídas corretamente formatadas. A conformidade entre leitura, processamento e exibição é evidência direta da tarefa.


#### CT16.1.4

**Título da Competência**  
Modularizar soluções por funções ou procedimentos com assinaturas e tipos adequados.

**Descrição Textual**  
Organizar partes da solução em subprogramas coesos, definindo interfaces simples com parâmetros e retorno adequados ao problema.

**Cobertura e rastreabilidade**

* LOs cobertos: LO4
* K mobilizados (Núcleo): K02, K05, K11

**Especificação de Conhecimentos**

* **K02:** definição de parâmetros e retorno com tipos coerentes; evidenciada na interface dos subprogramas.
* **K05:** integração entre chamada, processamento e uso do resultado; evidenciada no fluxo do programa principal.
* **K11:** definição e invocação de funções; evidenciadas na decomposição funcional da solução.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Criar.

**Pareamento Conhecimento–Habilidade**

K02 / Criar → definir parâmetros e retornos com tipos adequados à função implementada.  
Verbos de Bloom: construir, formular, desenvolver

K05 / Criar → integrar subprogramas ao fluxo geral da solução sem comprometer a coerência operacional.  
Verbos de Bloom: planejar, produzir, construir

K11 / Criar → desenvolver funções ou procedimentos com responsabilidade clara e uso correto no programa.  
Verbos de Bloom: desenvolver, programar, construir


**Especificação de Disposições**

* organização modular
* atenção às interfaces dos subprogramas
* clareza na divisão de responsabilidades

**Competências Alinhadas à BNCC**  
Alinhamento geral à decomposição funcional de soluções computacionais.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.1.4 | Modularizar soluções por funções ou procedimentos | organização modular, atenção às interfaces, clareza | K02 | definir parâmetros e retornos com tipos adequados |
| CT16.1.4 | Modularizar soluções por funções ou procedimentos | organização modular, atenção às interfaces, clareza | K05 | integrar subprogramas ao fluxo geral da solução |
| CT16.1.4 | Modularizar soluções por funções ou procedimentos | organização modular, atenção às interfaces, clareza | K11 | desenvolver funções ou procedimentos com responsabilidade clara |

**Definição de Ativação**

* Restrição de ativação: obrigatória
* Modo de ativação: construtiva
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: a descrição pedagógica explicita a construção de função simples com retorno. Assim, a modularização não é apenas acessória, mas componente diretamente ativado na tarefa.


#### CT16.1.5

**Título da Competência**  
Representar e processar coleções homogêneas com vetores e matrizes.

**Descrição Textual**  
Utilizar vetores e matrizes como estruturas adequadas para organizar, percorrer, consultar e transformar dados em problemas introdutórios de programação.

**Cobertura e rastreabilidade**

* LOs cobertos: LO5
* K mobilizados (Núcleo): K04, K06, K07, K08

**Especificação de Conhecimentos**

* **K04:** formulação de verificações sobre elementos e propriedades; evidenciada na análise de conteúdos das coleções.
* **K06:** tratamento de casos durante o processamento; evidenciado na classificação ou transformação de elementos.
* **K07:** percorrimento iterativo de coleções; evidenciado pelos laços usados para varrer posições.
* **K08:** representação e acesso posicional a vetores e matrizes; evidenciados pela indexação correta e pelo processamento dos elementos.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → verificar propriedades de elementos e formular condições coerentes no processamento da coleção.  
Verbos de Bloom: implementar, resolver, usar

K06 / Aplicar → selecionar ações distintas conforme o conteúdo ou a posição dos elementos processados.  
Verbos de Bloom: implementar, operar, resolver

K07 / Aplicar → percorrer vetores e matrizes com laços compatíveis com a dimensão e o objetivo do problema.  
Verbos de Bloom: iterar, manipular, usar

K08 / Aplicar → acessar, consultar e atualizar posições de vetores e matrizes com indexação correta.  
Verbos de Bloom: implementar, manipular, operar


**Especificação de Disposições**

* cuidado com índices e limites
* atenção à consistência das estruturas
* rigor no percorrimento dos dados

**Competências Alinhadas à BNCC**  
Alinhamento geral à representação e manipulação estruturada da informação.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.1.5 | Representar e processar coleções homogêneas | cuidado com índices, atenção à consistência, rigor | K04 | verificar propriedades de elementos e formular condições coerentes |
| CT16.1.5 | Representar e processar coleções homogêneas | cuidado com índices, atenção à consistência, rigor | K06 | selecionar ações distintas conforme o conteúdo ou a posição |
| CT16.1.5 | Representar e processar coleções homogêneas | cuidado com índices, atenção à consistência, rigor | K07 | percorrer vetores e matrizes com laços compatíveis |
| CT16.1.5 | Representar e processar coleções homogêneas | cuidado com índices, atenção à consistência, rigor | K08 | acessar, consultar e atualizar posições com indexação correta |

**Definição de Ativação**

* Restrição de ativação: obrigatória
* Modo de ativação: construtiva
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: vetores e matrizes constituem o núcleo temático da maratona. Os artefatos produzidos evidenciam diretamente a capacidade de representar, percorrer e transformar coleções homogêneas em C.

