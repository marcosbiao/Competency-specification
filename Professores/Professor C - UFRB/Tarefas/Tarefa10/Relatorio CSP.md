# RELATÓRIO CSP: AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de Autoria de Competências do Competency Specification Process e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa introdutória de programação estruturada. A atividade requer a leitura de dados financeiros, o processamento de múltiplos débitos, o cálculo do saldo final e a classificação do resultado em três estados possíveis, com exibição verificável do valor e da mensagem correspondente.

A tarefa elicita evidências observáveis porque o artefato produzido permite inspecionar diretamente a representação dos dados, a lógica de acumulação, a decisão condicional e a coerência entre processamento e saída. Ela sustenta o modelo Conhecimento-Habilidade-Disposição sem redundância, pois mobiliza um subconjunto delimitado do catálogo da disciplina, exige habilidades técnicas avaliáveis no programa e permite associar disposições compatíveis com precisão, consistência lógica e verificabilidade.

## 1. Análise da Entidade Instrucional

### Título

**Cálculo de saldo mensal com verificação de situação financeira**

### Descrição

Trata-se de uma tarefa introdutória de programação em que o estudante deve construir um programa capaz de receber um valor de salário, uma quantidade de contas do mês e os valores dessas contas, acumulando os débitos para, ao final, calcular o saldo e classificá-lo como positivo, negativo ou nulo. A atividade requer um artefato executável com saída verificável e uma justificativa breve coerente com o comportamento observado.

### Processo de Desenvolvimento da Solução 

1. Identificar as entradas do problema e o resultado esperado.
2. Definir variáveis adequadas para salário, quantidade de contas, valores lidos, total de débitos e saldo.
3. Organizar a solução em fluxo de entrada, processamento e saída.
4. Ler o salário e a quantidade de contas.
5. Ler iterativamente os valores das contas e acumular o total de débitos.
6. Calcular o saldo final a partir do salário e do total acumulado.
7. Verificar, por condição explícita, se o saldo é positivo, negativo ou igual a zero.
8. Exibir o valor do saldo e a mensagem compatível com o caso identificado.

### Resultados Esperados

1. Programa executável com leitura, acumulação, cálculo e decisão condicional.
2. Cálculo verificável do total de débitos do mês.
3. Exibição do saldo final em formato observável.
4. Exibição de mensagem compatível com um dos três casos previstos.
5. Justificativa breve explicando a classificação produzida.

### Contexto de Aquisição

- **Nível/Curso:** nível introdutório, Programação de Computadores I
- **Componente Curricular:** Programação de Computadores I
- **Contexto:** atividade individual, adequada a laboratório de programação ou avaliação prática inicial
- **Avaliação:** análise do código, da consistência da condição implementada, da saída produzida e da justificativa breve

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de formação em programação, com contato introdutório com variáveis, entrada e saída, expressões, estruturas condicionais e laços. Como necessidade principal, esse perfil demanda consolidar a passagem do enunciado textual para uma solução computacional verificável, especialmente em situações que combinam acumulação de valores e classificação do resultado.

### Nível de Proficiência (critérios e dimensões)

| Nível | Representação dos dados | Organização algorítmica | Processamento iterativo | Decisão condicional | Saída e justificativa |
|---|---|---|---|---|---|
| **N1 - Inicial** | identifica parcialmente as entradas e saídas, com variáveis insuficientes ou incoerentes | estrutura a solução de forma incompleta ou desordenada | não controla adequadamente a repetição ou a acumulação | trata os casos de modo ausente ou incorreto | apresenta saída incompleta ou não verificável |
| **N2 - Intermediário** | representa os dados principais, mas com pequenas fragilidades de tipo ou atribuição | organiza a sequência principal, mas com lacunas de execução | realiza repetição com pequenas inconsistências no acumulador | distingue parte dos casos, mas com cobertura incompleta | apresenta resultado compreensível, mas com justificativa frágil |
| **N3 - Proficiente** | representa salário, quantidade, acumulador e saldo de forma coerente | organiza corretamente leitura, acumulação, cálculo e saída | acumula corretamente os débitos a partir da quantidade informada | cobre corretamente saldo positivo, negativo e nulo | apresenta saldo e mensagem corretos com justificativa adequada |
| **N4 - Avançado** | organiza os dados com clareza técnica e boa rastreabilidade entre entrada, processamento e saída | organiza a solução com clareza, precisão e estabilidade de execução | integra repetição e acumulação com alta consistência e boa legibilidade lógica | expressa a decisão com precisão, sem ambiguidade e com total coerência lógica | apresenta saída clara, verificável e justificativa tecnicamente sólida |

## 2. Seleção e Enumeração de Conhecimentos

**K02 - Algoritmos e formas de representação**
- compreensão de algoritmo como sequência finita, ordenada e não ambígua de passos;
- organização da solução em etapas logicamente encadeadas;
- tradução do enunciado para uma sequência computacional executável.

Justificativa de mobilização na tarefa: a solução depende da formulação de um procedimento algorítmico estável que una leitura, repetição, cálculo e decisão.

**K03 - Estrutura sequencial, entrada, processamento e saída**
- organização do programa em fluxo de leitura, processamento e apresentação de resultados;
- encadeamento correto entre dados lidos, operações realizadas e saída produzida;
- produção de resultados coerentes com os valores fornecidos.

Justificativa de mobilização na tarefa: a atividade exige um programa executável com ordem de instruções verificável e com saída diretamente relacionada ao processamento realizado.

**K04 - Variáveis, constantes, tipos de dados e atribuição**
- representação de salário, quantidade, débitos parciais, total acumulado e saldo por variáveis adequadas;
- atualização consistente de valores durante a execução;
- compatibilidade elementar entre tipo de dado e uso computacional.

Justificativa de mobilização na tarefa: o problema requer armazenamento de entradas, manutenção de acumulador e registro do saldo final por meio de atribuições coerentes.

**K05 - Expressões aritméticas, relacionais e lógicas**
- construção de expressões para acumular débitos e calcular o saldo final;
- formulação de comparações que permitam distinguir os estados do saldo;
- uso coerente de operações numéricas e relacionais no mesmo problema.

Justificativa de mobilização na tarefa: o cálculo do saldo e a verificação de seus três estados dependem diretamente do uso correto de expressões aritméticas e relacionais.

**K06 - Estruturas condicionais**
- seleção de caminhos alternativos conforme o resultado da avaliação de uma condição;
- cobertura de casos mutuamente exclusivos e complementares;
- associação entre cada caso do problema e a saída textual correspondente.

Justificativa de mobilização na tarefa: a classificação do saldo em positivo, negativo ou nulo constitui o núcleo decisório da atividade.

**K07 - Estruturas de repetição**
- execução iterativa de leituras e acumulações controladas por quantidade informada;
- uso de laço para tratar múltiplos valores do mesmo tipo;
- atualização progressiva de acumulador ao longo da execução.

Justificativa de mobilização na tarefa: a descrição pedagógica exige leitura e soma dos valores das contas do mês, o que torna a repetição parte central do processamento.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Implementar programas básicos em linguagem de programação, articulando sequência lógica, variáveis e fluxo verificável de execução.  
**K associados:** (K02, K03, K04)

**LO2.** Realizar entrada e saída de dados numéricos de forma organizada e verificável no programa.  
**K associados:** (K03, K04)

**LO3.** Processar múltiplos valores por repetição controlada e acumulação coerente.  
**K associados:** (K04, K05, K07)

**LO4.** Classificar resultados numéricos por decisões condicionais mutuamente exclusivas, associando cada caso à saída correspondente.  
**K associados:** (K03, K05, K06)

## 4. Definição de Competências

### 4.1 Competência Geral

**Implementar soluções introdutórias de programação estruturada que integrem representação de dados, fluxo algorítmico, processamento iterativo e decisão condicional para produzir saídas verificáveis.**

### 4.2 Especificações de Competências

## CT10.1

**Título da Competência**  
Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais

**Descrição Textual**  
Capacidade de construir programas introdutórios em uma linguagem de programação, articulando estrutura algorítmica, variáveis e fluxo básico de execução de modo tecnicamente coerente.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1)
- K mobilizados (Núcleo): (K02, K03, K04)

**Especificação de Conhecimentos**
- **K02:** compreensão da solução como sequência ordenada e não ambígua de passos. Justificativa de evidência: o artefato permite verificar se a lógica global do programa foi estruturada de forma executável.
- **K03:** organização do fluxo de entrada, processamento e saída. Justificativa de evidência: a ordem operacional do programa é diretamente observável no código e no comportamento final.
- **K04:** uso de variáveis e atribuições coerentes com o papel dos dados. Justificativa de evidência: a tarefa evidencia a necessidade de armazenar entradas, acumulador e resultado final com consistência.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Criar**, pois a competência requer a implementação de um programa funcional, ainda que em nível introdutório.

**Pareamento Conhecimento-Habilidade**

K02 / Aplicar → implementar uma solução algorítmica em sequência finita e coerente com os dados e resultados do problema.  
Verbos de Bloom: implementar, programar, executar

K03 / Aplicar → estruturar o fluxo de entrada, processamento e saída de modo verificável no programa.  
Verbos de Bloom: executar, realizar, usar

K04 / Aplicar → declarar e utilizar variáveis numéricas compatíveis com o papel computacional de cada dado.  
Verbos de Bloom: manipular, operar, usar


**Especificação de Disposições**  
precisão na representação dos dados; atenção à ordem das instruções; rigor na consistência do programa


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão na representação dos dados; atenção à ordem das instruções; rigor na consistência do programa | K02 | implementar uma solução algorítmica em sequência finita e coerente com os dados e resultados do problema |
| CT10.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão na representação dos dados; atenção à ordem das instruções; rigor na consistência do programa | K03 | estruturar o fluxo de entrada, processamento e saída de modo verificável no programa |
| CT10.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão na representação dos dados; atenção à ordem das instruções; rigor na consistência do programa | K04 | declarar e utilizar variáveis numéricas compatíveis com o papel computacional de cada dado |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a task exige a produção de um programa funcional desde a organização algorítmica até a manutenção do estado das variáveis. Sem essa competência, a solução não se estabiliza como artefato executável.

## CT10.2

**Título da Competência**  
Realizar entrada e saída de dados com formatação apropriada

**Descrição Textual**  
Capacidade de receber dados de entrada e apresentar resultados de saída de maneira organizada, coerente com o processamento realizado e verificável no comportamento do programa.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2)
- K mobilizados (Núcleo): (K03, K04)

**Especificação de Conhecimentos**
- **K03:** organização do programa em leitura, processamento e apresentação de resultados. Justificativa de evidência: o código permite verificar a relação entre valores lidos e resultados exibidos.
- **K04:** uso de variáveis para armazenamento de dados de entrada e resultados. Justificativa de evidência: as entradas e saídas precisam estar representadas de forma consistente ao longo da execução.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência envolve uso operacional de rotinas básicas de entrada e saída.

**Pareamento Conhecimento-Habilidade**

K03 / Aplicar → realizar leitura e apresentação de dados em um fluxo de execução coerente e observável.  
Verbos de Bloom: executar, realizar, usar

K04 / Aplicar → armazenar entradas e resultados em variáveis compatíveis com o processamento e a saída do programa.  
Verbos de Bloom: armazenar, manipular, operar

**Especificação de Disposições**  
clareza na apresentação dos resultados; atenção aos dados lidos; rigor na verificabilidade da saída

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.2 | Realizar entrada e saída de dados com formatação apropriada | clareza na apresentação dos resultados; atenção aos dados lidos; rigor na verificabilidade da saída | K03 | realizar leitura e apresentação de dados em um fluxo de execução coerente e observável |
| CT10.2 | Realizar entrada e saída de dados com formatação apropriada | clareza na apresentação dos resultados; atenção aos dados lidos; rigor na verificabilidade da saída | K04 | armazenar entradas e resultados em variáveis compatíveis com o processamento e a saída do programa |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade exige leitura explícita do salário, da quantidade de contas e dos valores correspondentes, além da exibição do saldo e da mensagem final. Essas evidências tornam a competência diretamente observável.

## CT10.3

**Título da Competência**  
Processar múltiplos valores por repetição e acumulação controladas

**Descrição Textual**  
Capacidade de implementar processamento iterativo de conjuntos simples de valores, controlando a repetição e atualizando acumuladores de modo consistente ao longo da execução.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3)
- K mobilizados (Núcleo): (K04, K05, K07)

**Especificação de Conhecimentos**
- **K04:** uso de variáveis de leitura e acumuladores. Justificativa de evidência: a tarefa exige manter estado atualizado ao longo do laço.
- **K05:** construção de expressões aritméticas para atualização progressiva do total. Justificativa de evidência: o total de débitos depende do cálculo sucessivo implementado.
- **K07:** uso de repetição controlada por quantidade informada. Justificativa de evidência: a leitura das contas do mês e sua soma dependem de iteração observável no programa.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência envolve uso operacional de laço e acumulação em problema introdutório.

**Pareamento Conhecimento-Habilidade**

K04 / Aplicar → manter variáveis de leitura e acumuladores com atribuições coerentes durante o processamento iterativo.  
Verbos de Bloom: manipular, operar, usar

K05 / Aplicar → calcular atualizações sucessivas de um acumulador a partir de valores lidos iterativamente.  
Verbos de Bloom: calcular, computar, operar

K07 / Aplicar → iterar a leitura e o processamento de múltiplas entradas de modo controlado e com término garantido.  
Verbos de Bloom: iterar, executar, usar

**Especificação de Disposições**  
consistência operacional; atenção ao controle de repetição; rigor na atualização do acumulador


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.3 | Processar múltiplos valores por repetição e acumulação controladas | consistência operacional; atenção ao controle de repetição; rigor na atualização do acumulador | K04 | manter variáveis de leitura e acumuladores com atribuições coerentes durante o processamento iterativo |
| CT10.3 | Processar múltiplos valores por repetição e acumulação controladas | consistência operacional; atenção ao controle de repetição; rigor na atualização do acumulador | K05 | calcular atualizações sucessivas de um acumulador a partir de valores lidos iterativamente |
| CT10.3 | Processar múltiplos valores por repetição e acumulação controladas | consistência operacional; atenção ao controle de repetição; rigor na atualização do acumulador | K07 | iterar a leitura e o processamento de múltiplas entradas de modo controlado e com término garantido |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a descrição pedagógica exige soma dos valores das contas do mês, o que torna a repetição controlada e a acumulação parte diretamente evidenciável do artefato produzido.

## CT10.4

**Título da Competência**  
Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas

**Descrição Textual**  
Capacidade de formular comparações e organizar estruturas condicionais para selecionar saídas distintas em função de resultados numéricos mutuamente exclusivos.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO4)
- K mobilizados (Núcleo): (K03, K05, K06)

**Especificação de Conhecimentos**
- **K03:** inserção da decisão no fluxo global de entrada, processamento e saída. Justificativa de evidência: a mensagem final precisa estar articulada ao resultado calculado.
- **K05:** formulação de comparações coerentes com os estados do resultado. Justificativa de evidência: a distinção entre positivo, negativo e nulo depende diretamente das expressões relacionais implementadas.
- **K06:** organização de caminhos alternativos mutuamente exclusivos. Justificativa de evidência: a tarefa exige cobertura explícita dos três casos e associação correta entre cada caso e sua mensagem.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Analisar**, pois a competência requer discriminar cenários, relacionar comparações e estruturar decisões mutuamente exclusivas a partir de um resultado numérico.

**Pareamento Conhecimento-Habilidade**

K03 / Aplicar → integrar a decisão condicional ao fluxo de saída do programa de modo verificável.  
Verbos de Bloom: executar, realizar, usar

K05 / Analisar → analisar o valor calculado do resultado por meio de comparações explícitas e coerentes com os casos do problema.  
Verbos de Bloom: analisar, examinar, relacionar

K06 / Analisar → distinguir e estruturar caminhos alternativos de execução para casos mutuamente exclusivos.  
Verbos de Bloom: distinguir, estruturar, discriminar

**Especificação de Disposições**  
consistência lógica; atenção à cobertura dos casos; precisão na correspondência entre condição e saída

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.4 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | consistência lógica; atenção à cobertura dos casos; precisão na correspondência entre condição e saída | K03 | integrar a decisão condicional ao fluxo de saída do programa de modo verificável |
| CT10.4 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | consistência lógica; atenção à cobertura dos casos; precisão na correspondência entre condição e saída | K05 | analisar o valor calculado do resultado por meio de comparações explícitas e coerentes com os casos do problema |
| CT10.4 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | consistência lógica; atenção à cobertura dos casos; precisão na correspondência entre condição e saída | K06 | distinguir e estruturar caminhos alternativos de execução para casos mutuamente exclusivos |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o centro avaliativo da classificação financeira está na distinção correta entre três estados do saldo. A competência é ativada porque a tarefa torna a decisão condicional diretamente inspecionável.

