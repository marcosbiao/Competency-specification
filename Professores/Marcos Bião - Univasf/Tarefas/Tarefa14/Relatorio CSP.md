# RELATÓRIO CSP — Autoria de Competências

## Introdução

Este relatório situa a tarefa **TASK14 — Impressão de padrão textual com diagonal principal** na fase de **Autoria de Competências** do CSP. A tarefa solicita a leitura de um valor inteiro `n` e a geração de uma saída textual com `n` linhas, em que um símbolo de destaque ocupa progressivamente a diagonal principal, enquanto as demais posições seguem um símbolo de preenchimento. Trata-se de uma entidade instrucional com evidências diretamente observáveis, pois o desempenho do estudante se manifesta no código produzido, no comportamento da execução e na conformidade formal da saída exibida.

A tarefa elicita, de forma enxuta e sem redundância, conhecimentos centrais de **Introdução à Programação**, especialmente relacionados a entrada e saída, controle de estado, repetição e decisão posicional. O modelo **K–S–D** é suportado porque a atividade exige conhecimentos do catálogo, habilidades observáveis na implementação e disposições de precisão, consistência e conferência do artefato final.

---

## 1. Análise da Entidade Instrucional

### Título

**TASK14 — Impressão de padrão textual com diagonal principal**

### Descrição

Atividade de implementação introdutória em que o estudante deve construir um programa capaz de ler um número inteiro e imprimir um padrão textual quadrado, com quantidade de linhas e posições definida pelo valor de entrada. A organização do padrão exige repetição controlada, decisão local sobre o símbolo a ser impresso e preservação rigorosa do formato especificado.

### Processo de Desenvolvimento da Solução (em etapas)

1. Interpretar o padrão solicitado, identificando regularidade global e regra local de destaque.
2. Definir o parâmetro de entrada que controla a dimensão da saída.
3. Organizar o fluxo de geração da saída em linhas e posições por linha.
4. Aplicar uma decisão posicional para distinguir símbolo de destaque e símbolo de preenchimento.
5. Verificar a completude do padrão, o término das repetições e a conformidade do formato final.

### Resultados Esperados

* Programa que leia um valor inteiro e produza a saída textual no formato solicitado.
* Saída exibida de forma verificável, com quantidade correta de linhas e posições.
* Justificativa breve e coerente sobre o critério usado para posicionar o símbolo de destaque.
* Artefato final legível e consistente com o enunciado.

### Contexto de Aquisição 

* **Componente curricular:** Introdução à Programação.
* **Nível/curso inferido:** formação inicial em Computação ou curso correlato com disciplina introdutória de programação.
* **Organização:** atividade individual.
* **Ambiente:** laboratório de programação ou avaliação prática com execução em console.
* **Avaliação:** observação do código funcional, da saída produzida e da justificativa breve associada ao critério de construção do padrão.

### Perfil do Público-Alvo (nível, pré-requisitos, necessidades)

Trata-se de estudantes em fase inicial da disciplina, já expostos a variáveis, tipos primitivos, entrada e saída básica, condições e estruturas de repetição. O público-alvo necessita consolidar o uso integrado desses elementos em um problema pequeno, mas com exigência de precisão formal na saída e de coerência entre controle iterativo e regra posicional.

### Nível de Proficiência (critérios e dimensões)

| Nível | Compreensão da especificação | Controle do fluxo | Decisão local | Conformidade da saída | Verificabilidade e justificativa |
|---|---|---|---|---|---|
| **N1 - Inicial** | Reconhece parcialmente o padrão e a regra posicional. | Usa repetição com falhas de contagem ou término. | Tem dificuldade para formular a condição correta. | Apresenta erros relevantes de formato ou estrutura. | Justificativa ausente, vaga ou incoerente. |
| **N2 - Intermediário** | Entende a ideia geral do padrão, com algumas inconsistências. | Usa repetição de modo parcialmente correto. | Formula a condição, mas com erros em alguns casos. | Aproxima-se do formato esperado, com erros pontuais. | Justificativa breve, mas parcialmente coerente. |
| **N3 - Proficiente** | Compreende corretamente o padrão e sua regra de organização. | Controla adequadamente linhas, posições e término. | Aplica corretamente a condição lógica em toda a saída. | Produz saída correta e consistente com o enunciado. | Justificativa objetiva, coerente e verificável. |
| **N4 - Avançado** | Explica com clareza a regularidade do padrão e suas implicações. | Estrutura a repetição com precisão, clareza e estabilidade. | Formula e aplica a condição com pleno domínio. | Produz saída integralmente correta e formalmente precisa. | Justificativa clara, técnica e bem articulada. |



## 2. Seleção e Enumeração de Conhecimentos

### K01 — Modelo de execução e noção de estado (paradigma imperativo)

* Compreensão de que o programa evolui por mudanças de estado durante a execução.
* Acompanhamento de variáveis de controle ao longo das iterações.
* Relação entre estado corrente e comportamento observável da saída.

**Justificativa de mobilização na tarefa:** a atividade exige manter rastreável o estado associado à linha corrente, à posição corrente e ao efeito dessas variações sobre o símbolo impresso.

### K02 — Variáveis, constantes e tipos primitivos

* Representação de dados simples por meio de identificadores e tipos compatíveis.
* Uso de valores inteiros como parâmetros de controle da execução.
* Atribuições coerentes para armazenar entrada e controlar o processamento.

**Justificativa de mobilização na tarefa:** o valor `n` e os controladores da geração do padrão dependem de uso correto de variáveis primitivas e de atribuições consistentes.

### K04 — Expressões lógicas e condições

* Construção de condições booleanas a partir de comparações entre valores.
* Diferenciação entre casos de execução com base em uma regra posicional.
* Tradução de um critério do enunciado para uma decisão computacional observável.

**Justificativa de mobilização na tarefa:** a distinção entre símbolo de destaque e símbolo de preenchimento depende de uma condição relacional aplicada durante a impressão.

### K05 — Estrutura sequencial e E/S básica

* Organização do fluxo entrada, processamento e saída.
* Emissão de saídas textuais de forma verificável.
* Manutenção de consistência entre valor lido e produto exibido.

**Justificativa de mobilização na tarefa:** a evidência principal da atividade é a própria saída textual, produzida a partir de um fluxo básico de leitura e impressão.

### K07 — Estruturas de repetição

* Execução repetida de blocos de comandos controlada por contagem.
* Percorrimento sistemático de linhas e posições dentro de cada linha.
* Garantia de cobertura completa e término adequado do processo iterativo.

**Justificativa de mobilização na tarefa:** o enunciado exige impressão de múltiplas linhas e múltiplas posições por linha, o que torna a repetição o núcleo operacional da solução.


## 3. Identificação de Objetivos de Aprendizagem

### LO1
Organizar programas que leem um parâmetro inteiro e produzem saída textual formatada de modo verificável.

**K associados:** K02, K05

### LO2
Empregar estruturas de repetição contada para controlar a quantidade de linhas e de posições impressas em um padrão textual.

**K associados:** K07, K05, K01

### LO3
Aplicar condições relacionais entre variáveis de controle para diferenciar posições com comportamento especial em uma saída estruturada.

**K associados:** K04, K07, K01

### LO4
Verificar a consistência dimensional e posicional da saída gerada em relação à especificação do problema, justificando o critério adotado.

**K associados:** K05, K04, K07, K01



## 4. Definição de Competências

### 4.1 Competência Geral 

**Competência geral do domínio:** desenvolver programas introdutórios que transformem uma entrada simples em uma saída textual verificável, mobilizando controle de estado, sequência, repetição e decisão posicional.

**BNCC:** não aplicada neste relatório, pois o contexto explicitado é de disciplina introdutória de programação em nível superior, sem base segura para uso de códigos específicos.


#### 4.2 Especificações de Competências

## CT14.1

**Título da Competência**  
Traduzir problemas simples em algoritmos claros por decomposição e abstração

**Descrição Textual**  
Capacidade de interpretar um problema introdutório de programação, identificar sua estrutura essencial e organizá-lo em um algoritmo claro, com etapas de entrada, processamento e saída coerentemente articuladas.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO2, LO3, LO4)
2. K mobilizados (Núcleo): (K01, K05, K06, K07)

**Especificação de Conhecimentos**
1. **K01**: compreensão do estado do programa e de sua evolução durante a execução.  
Justificativa de evidência: a solução depende de acompanhar a progressão das linhas e posições ao longo da execução.
2. **K05**: organização sequencial da leitura, processamento e impressão.  
Justificativa de evidência: o problema exige fluxo básico de entrada e saída claramente estruturado.
3. **K06**: uso de seleção para distinguir comportamentos alternativos.  
Justificativa de evidência: em cada posição, o programa precisa decidir qual símbolo imprimir.
4. **K07**: uso de repetição para compor a estrutura completa da saída.  
Justificativa de evidência: a geração do padrão depende de laços que percorrem linhas e colunas.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Analisar

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → decompor a execução do problema em estados sucessivos que expliquem a construção do padrão.  
Verbos de Bloom: decompor, rastrear, estruturar

K05 / Analisar → organizar a sequência de entrada, processamento e saída de modo coerente com a especificação.  
Verbos de Bloom: estruturar, relacionar, examinar

K06 / Analisar → distinguir os casos de impressão a partir da regra posicional do problema.  
Verbos de Bloom: distinguir, relacionar, examinar

K07 / Analisar → estruturar o processo iterativo necessário para percorrer integralmente a saída solicitada.  
Verbos de Bloom: estruturar, decompor, rastrear



**Especificação de Disposições**  
1. clareza na organização da solução
2. precisão na leitura da especificação
3. cuidado com a coerência entre etapas
4. disciplina na conferência do algoritmo

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT14.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza, precisão, coerência, disciplina | K01 | decompor a execução do problema em estados sucessivos que expliquem a construção do padrão |
| CT14.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza, precisão, coerência, disciplina | K05 | organizar a sequência de entrada, processamento e saída de modo coerente com a especificação |
| CT14.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza, precisão, coerência, disciplina | K06 | distinguir os casos de impressão a partir da regra posicional do problema |
| CT14.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza, precisão, coerência, disciplina | K07 | estruturar o processo iterativo necessário para percorrer integralmente a saída solicitada |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: analítica
3. Função de ativação: núcleo
4. Justificativa curta: a tarefa exige interpretar o padrão solicitado e traduzi-lo em uma estrutura algorítmica verificável, o que ativa análise da organização global da solução.



## CT14.2

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e constantes

**Descrição Textual**  
Capacidade de utilizar variáveis e tipos primitivos de forma coerente para representar dados de entrada e estados de controle em programas introdutórios.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO2)
2. K mobilizados (Núcleo): (K01, K02, K05)

**Especificação de Conhecimentos**
1. **K01**: noção de estado e atualização de variáveis durante a execução.  
Justificativa de evidência: a construção do padrão depende de variáveis que evoluem a cada passo.
2. **K02**: uso de variáveis e tipo inteiro para entrada e controle.  
Justificativa de evidência: o valor lido e os contadores da solução são dados primitivos diretamente observáveis.
3. **K05**: integração entre variáveis, processamento e saída.  
Justificativa de evidência: o estado das variáveis precisa refletir-se corretamente no produto exibido.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → atualizar variáveis de controle de modo coerente com a evolução da execução.  
Verbos de Bloom: aplicar, manipular, iterar

K02 / Aplicar → declarar e utilizar dados primitivos compatíveis com a entrada e o controle do problema.  
Verbos de Bloom: aplicar, implementar, usar

K05 / Aplicar → integrar o uso das variáveis ao fluxo sequencial de geração da saída.  
Verbos de Bloom: executar, operar, implementar


**Especificação de Disposições**  
1. rigor na escolha e uso de variáveis
2. atenção à coerência dos tipos
3. cuidado com atualização de estado

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT14.2 | Manipular dados com tipos primitivos, variáveis e constantes | rigor, atenção, cuidado | K01 | atualizar variáveis de controle de modo coerente com a evolução da execução |
| CT14.2 | Manipular dados com tipos primitivos, variáveis e constantes | rigor, atenção, cuidado | K02 | declarar e utilizar dados primitivos compatíveis com a entrada e o controle do problema |
| CT14.2 | Manipular dados com tipos primitivos, variáveis e constantes | rigor, atenção, cuidado | K05 | integrar o uso das variáveis ao fluxo sequencial de geração da saída |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta: o problema depende diretamente do uso de variáveis primitivas para controlar dimensão, linha e posição, sem o que a solução não se sustenta.


## CT14.3

**Título da Competência**  
Realizar entrada e saída de dados com formatação apropriada

**Descrição Textual**  
Capacidade de ler dados simples e produzir saída textual com formato observável, preservando consistência entre o valor de entrada e o resultado exibido.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO4)
2. K mobilizados (Núcleo): (K02, K05)

**Especificação de Conhecimentos**
1. **K02**: uso do dado de entrada em tipo compatível.  
Justificativa de evidência: o parâmetro que controla a saída precisa ser lido e armazenado corretamente.
2. **K05**: produção de saída textual no formato exigido.  
Justificativa de evidência: a correção da tarefa é observada diretamente na forma da saída impressa.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → receber e representar o dado de entrada em tipo compatível com o controle da execução.  
Verbos de Bloom: usar, aplicar, implementar

K05 / Aplicar → produzir uma saída textual formatada de acordo com a especificação do problema.  
Verbos de Bloom: executar, implementar, operar


**Especificação de Disposições**  
1. atenção ao formato
2. precisão na leitura da entrada
3. cuidado com a verificabilidade da saída

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT14.3 | Realizar entrada e saída de dados com formatação apropriada | atenção, precisão, cuidado | K02 | receber e representar o dado de entrada em tipo compatível com o controle da execução |
| CT14.3 | Realizar entrada e saída de dados com formatação apropriada | atenção, precisão, cuidado | K05 | produzir uma saída textual formatada de acordo com a especificação do problema |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta: a tarefa tem como evidência principal a leitura de um parâmetro simples e a impressão correta do padrão, o que ativa diretamente a competência de E/S formatada.

## CT14.4

**Título da Competência**  
Controlar o fluxo com decisões (if/else), formulando expressões lógicas corretas

**Descrição Textual**  
Capacidade de formular condições booleanas corretas e utilizá-las em estruturas de decisão para selecionar comportamentos alternativos em programas introdutórios.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO3, LO4)
2. K mobilizados (Núcleo): (K04, K06, K01)

**Especificação de Conhecimentos**
1. **K04**: formulação de expressões lógicas e relacionais.  
Justificativa de evidência: a escolha do símbolo depende de uma condição posicional correta.
2. **K06**: uso de seleção para distinguir dois comportamentos de saída.  
Justificativa de evidência: o problema exige decisão entre símbolo de destaque e símbolo de preenchimento.
3. **K01**: acompanhamento do estado utilizado na decisão.  
Justificativa de evidência: a condição depende dos valores correntes de controle durante a execução.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → formular a condição lógica que diferencia a posição especial das demais posições do padrão.  
Verbos de Bloom: aplicar, implementar, usar

K06 / Aplicar → selecionar corretamente o comportamento de impressão por meio de decisão condicional simples.  
Verbos de Bloom: executar, implementar, operar

K01 / Aplicar → utilizar o estado corrente do programa como base para a decisão em cada passo da execução.  
Verbos de Bloom: usar, manipular, iterar


**Especificação de Disposições**  
1. precisão lógica
2. atenção a casos distintos
3. cuidado com coerência posicional

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT14.4 | Controlar o fluxo com decisões (if/else), formulando expressões lógicas corretas | precisão, atenção, cuidado | K04 | formular a condição lógica que diferencia a posição especial das demais posições do padrão |
| CT14.4 | Controlar o fluxo com decisões (if/else), formulando expressões lógicas corretas | precisão, atenção, cuidado | K06 | selecionar corretamente o comportamento de impressão por meio de decisão condicional simples |
| CT14.4 | Controlar o fluxo com decisões (if/else), formulando expressões lógicas corretas | precisão, atenção, cuidado | K01 | utilizar o estado corrente do programa como base para a decisão em cada passo da execução |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta: a diagonal destacada só é produzida corretamente quando o estudante formula uma condição lógica válida e a aplica em uma decisão simples de impressão.

## CT14.5

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores e paradas seguras

**Descrição Textual**  
Capacidade de empregar estruturas de repetição contada para percorrer quantidades definidas de elementos, garantindo cobertura completa e término correto da execução.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO2, LO4)
2. K mobilizados (Núcleo): (K07, K01, K05)

**Especificação de Conhecimentos**
1. **K07**: uso de laços por contagem.  
Justificativa de evidência: a tarefa exige percorrer linhas e posições de forma sistemática.
2. **K01**: atualização do estado iterativo.  
Justificativa de evidência: a progressão do padrão depende do avanço correto dos contadores.
3. **K05**: integração entre repetição e impressão sequencial.  
Justificativa de evidência: o resultado final decorre da emissão ordenada de símbolos em cada iteração.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Aplicar

**Pareamento Conhecimento–Habilidade**

K07 / Aplicar → implementar laços contados que percorrem integralmente as linhas e posições do padrão.  
Verbos de Bloom: implementar, iterar, executar

K01 / Aplicar → atualizar os contadores de execução de forma coerente com a progressão do algoritmo.  
Verbos de Bloom: manipular, usar, iterar

K05 / Aplicar → articular a repetição com a impressão sequencial da saída solicitada.  
Verbos de Bloom: executar, operar, implementar


**Especificação de Disposições**  
1. atenção à contagem
2. rigor na completude
3. cuidado com término da execução

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT14.5 | Controlar o fluxo com repetição utilizando contadores e paradas seguras | atenção, rigor, cuidado | K07 | implementar laços contados que percorrem integralmente as linhas e posições do padrão |
| CT14.5 | Controlar o fluxo com repetição utilizando contadores e paradas seguras | atenção, rigor, cuidado | K01 | atualizar os contadores de execução de forma coerente com a progressão do algoritmo |
| CT14.5 | Controlar o fluxo com repetição utilizando contadores e paradas seguras | atenção, rigor, cuidado | K05 | articular a repetição com a impressão sequencial da saída solicitada |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta: o padrão só é produzido corretamente com repetição controlada por contagem, cobrindo todas as linhas e posições com encerramento consistente.