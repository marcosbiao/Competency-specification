# RELATÓRIO CSP — AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do Competency Specification Process e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa introdutória de programação. A atividade requer a leitura sucessiva de números inteiros, com encerramento por sentinela, e a apresentação do maior e do menor valor efetivamente processados. As evidências observáveis concentram-se no código produzido, no controle correto da repetição, na atualização consistente do estado do programa e na saída final verificável.

A tarefa sustenta adequadamente o modelo **Conhecimento–Habilidade–Disposição (K–S–D)** porque combina conhecimentos centrais da disciplina, habilidades técnicas diretamente observáveis e disposições ligadas a rigor lógico, precisão operacional e consistência computacional. A especificação abaixo prioriza rastreabilidade explícita, reuso em outras tarefas da disciplina e controle de granularidade, sem criar conhecimentos fora do catálogo fixo.

## 1. Análise da Entidade Instrucional

### Título

**Determinação do maior e do menor valor em sequência numérica com parada por sentinela**

### Descrição

A tarefa solicita a implementação de um programa que leia números inteiros um a um, interrompa a entrada quando o valor 0 for informado e apresente, ao final, o maior e o menor número válidos processados. Trata-se de uma atividade típica de programação introdutória porque articula leitura sucessiva de dados, controle de repetição por critério de parada, comparação entre valores e produção de resultados finais observáveis.

### Processo de Desenvolvimento da Solução

1. Interpretar o problema como processamento de uma sequência numérica de tamanho indeterminado.
2. Identificar o valor 0 como critério de parada e distingui-lo dos valores efetivamente analisados.
3. Organizar o fluxo do programa com entrada, processamento iterativo e saída final.
4. Definir variáveis para leitura, controle e registro dos valores extremos.
5. Repetir a leitura e, a cada iteração válida, comparar e atualizar o maior e o menor valor.
6. Encerrar o processamento no momento adequado e exibir resultados coerentes com os dados considerados.
7. Tratar explicitamente o caso em que não haja número válido antes da parada, conforme orientação pedagógica definida.

### Resultados Esperados

- código-fonte em linguagem estruturada com leitura repetida, processamento iterativo e saída final;
- uso correto de sentinela para encerramento da entrada;
- atualização consistente do maior e do menor valor ao longo da execução;
- saída final verificável com os valores extremos obtidos;
- justificativa breve sobre o critério de parada e a coerência dos resultados apresentados.

### Contexto de Aquisição

- **Curso:** graduação inicial em Computação
- **Organização:** atividade individual
- **Ambiente:** laboratório de programação ou avaliação prática introdutória
- **Avaliação:** análise do código, do comportamento final do programa e da justificativa breve apresentada

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de aprendizagem de programação estruturada, com contato introdutório com algoritmo, variáveis, entrada e saída, expressões, estruturas condicionais e estruturas de repetição. Esses estudantes necessitam consolidar a tradução de enunciados textuais em soluções executáveis, com atenção especial ao controle de fluxo, ao estado do programa e à verificabilidade dos resultados.

### Nível de Proficiência (critérios e dimensões)

| Nível | Modelagem da solução | Controle de repetição | Atualização de estado | Saída e justificativa |
|---|---|---|---|---|
| **N1 — Inicial** | identifica parcialmente entradas, parada e resultados | laço ausente, incorreto ou sem término garantido | maior e menor são tratados de forma inconsistente | saída incompleta ou incompatível com o processamento |
| **N2 — Intermediario** | organiza a solução, mas com lacunas na representação do problema | repete leituras, mas com falhas no uso da sentinela | atualiza apenas parte do estado ou com comparações frágeis | saída compreensível, mas com pouca verificabilidade |
| **N3 — Proficiente** | modela corretamente a sequência de entrada, o critério de parada e as saídas | controla a repetição por sentinela de forma correta e estável | atualiza corretamente os valores extremos ao longo da execução | apresenta saída correta e justificativa breve coerente |
| **N4 — Avançado** | modela a solução com clareza, antecipando casos relevantes sem perder aderência ao enunciado | integra repetição e parada com alta consistência, inclusive em casos limítrofes | mantém estado interno claro, consistente e tecnicamente robusto | apresenta saída clara, verificável e justificativa tecnicamente precisa |

## 2. Seleção e Enumeração de Conhecimentos

### K02 — Algoritmos e formas de representação
- compreender algoritmo como sequência finita, ordenada e não ambígua de passos;
- representar a lógica da solução de modo estruturado antes ou durante a implementação;
- organizar o problema como procedimento computacional verificável.

**Justificativa de mobilização na tarefa:** a atividade exige estruturar uma solução algorítmica para processar entradas sucessivas, interromper a execução em condição específica e produzir resultados finais observáveis.

### K03 — Estrutura sequencial, entrada, processamento e saída
- organizar o programa em fluxo coerente de leitura, processamento e exibição de resultados;
- encadear instruções de forma verificável no comportamento final do programa;
- produzir saídas compatíveis com os dados efetivamente processados.

**Justificativa de mobilização na tarefa:** a tarefa depende de um fluxo básico de entrada de dados, processamento iterativo e saída final consistente.

### K04 — Variáveis, constantes, tipos de dados e atribuição
- representar valores de entrada, controle e resultado por variáveis adequadas;
- atualizar o estado do programa por atribuições coerentes ao longo da execução;
- manter compatibilidade entre tipo de dado e uso computacional.

**Justificativa de mobilização na tarefa:** a solução requer variáveis para leitura, comparação e registro do maior e do menor valor, além de possíveis controles de inicialização.

### K05 — Expressões aritméticas, relacionais e lógicas
- formular comparações entre valores numéricos para apoiar decisões e atualizações;
- interpretar condições lógicas associadas ao critério de parada e aos valores extremos;
- combinar expressões de maneira coerente com o comportamento esperado.

**Justificativa de mobilização na tarefa:** a identificação do maior, do menor e da sentinela depende diretamente do uso correto de expressões relacionais e lógicas.

### K06 — Estruturas condicionais
- selecionar ações distintas com base em condições avaliadas durante a execução;
- tratar cenários alternativos de atualização de estado;
- cobrir de forma consistente os casos previstos pela lógica do problema.

**Justificativa de mobilização na tarefa:** a solução exige decisões sucessivas para atualizar os valores extremos e tratar explicitamente situações específicas de processamento.

### K07 — Estruturas de repetição
- executar leituras e processamentos iterativos controlados por condição ou critério de parada;
- manter laço com término garantido e comportamento coerente;
- repetir ações sobre quantidade indeterminada de dados.

**Justificativa de mobilização na tarefa:** o núcleo operacional da atividade está no processamento iterativo de uma quantidade indeterminada de números até a ocorrência do valor sentinela.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Estruturar algoritmos introdutórios para processar sequências de dados com entrada, processamento e saída verificáveis.  
**K associados:** (K02, K03)

**LO2.** Representar e atualizar variáveis de leitura, controle e resultado de forma coerente ao longo da execução do programa.  
**K associados:** (K03, K04)

**LO3.** Formular comparações relacionais e decisões condicionais para distinguir critério de parada e atualização de resultados.  
**K associados:** (K05, K06)

**LO4.** Aplicar estruturas de repetição para tratar quantidade indeterminada de entradas com término garantido por sentinela.  
**K associados:** (K05, K07)

**LO5.** Produzir saídas finais coerentes com os valores efetivamente processados e justificá-las de forma tecnicamente consistente.  
**K associados:** (K03, K04, K05)

## 4. Definição de Competências

### 4.1 Competência Geral

**Implementar soluções computacionais introdutórias em programação estruturada, articulando organização algorítmica, controle de fluxo, atualização de estado e produção de saídas verificáveis.**

### 4.2 Especificações de Competências

## CT11.1

**Título da Competência**  
**Implementar programas introdutórios com fluxo verificável de entrada, processamento e saída**

**Descrição Textual**  
Capacidade de estruturar programas simples em linguagem de programação estruturada, organizando a solução como algoritmo executável com leitura de dados, processamento coerente e apresentação de resultados verificáveis.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO2, LO5)
- K mobilizados (Núcleo): (K02, K03, K04)

**Especificação de Conhecimentos**
- **K02:** organização algorítmica da solução em etapas finitas e ordenadas. **Justificativa de evidência:** o artefato final evidencia se a lógica do programa foi estruturada como procedimento computacional coerente.
- **K03:** encadeamento entre leitura, processamento e saída. **Justificativa de evidência:** a tarefa permite verificar diretamente se o programa executa o fluxo solicitado até a exibição dos resultados finais.
- **K04:** representação e atualização de variáveis de leitura e de resultado. **Justificativa de evidência:** os valores extremos só podem ser produzidos se as variáveis forem usadas e atualizadas de forma consistente.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência exige uso operacional e verificável de organização algorítmica, fluxo básico de execução e manipulação de variáveis em um programa funcional.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → estruturar a solução como algoritmo finito e ordenado para processamento de dados em programa introdutório.  
Verbos de Bloom: implementar, organizar, programar

K03 / Aplicar → organizar o fluxo de entrada, processamento e saída de modo verificável no comportamento do programa.  
Verbos de Bloom: executar, implementar, apresentar

K04 / Aplicar → representar e atualizar variáveis compatíveis com leitura, controle e resultados do processamento.  
Verbos de Bloom: manipular, usar, armazenar

**Especificação de Disposições**
- rigor na organização do fluxo computacional;
- precisão na representação dos dados;
- atenção à coerência entre processamento e saída.


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.1 | Implementar programas introdutórios com fluxo verificável de entrada, processamento e saída | rigor na organização do fluxo computacional; precisão na representação dos dados; atenção à coerência entre processamento e saída | K02 | estruturar a solução como algoritmo finito e ordenado para processamento de dados em programa introdutório |
| CT11.1 | Implementar programas introdutórios com fluxo verificável de entrada, processamento e saída | rigor na organização do fluxo computacional; precisão na representação dos dados; atenção à coerência entre processamento e saída | K03 | organizar o fluxo de entrada, processamento e saída de modo verificável no comportamento do programa |
| CT11.1 | Implementar programas introdutórios com fluxo verificável de entrada, processamento e saída | rigor na organização do fluxo computacional; precisão na representação dos dados; atenção à coerência entre processamento e saída | K04 | representar e atualizar variáveis compatíveis com leitura, controle e resultados do processamento |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade requer a construção efetiva de um programa executável com comportamento observável. A competência é ativada desde o início da solução, pois o estudante precisa organizar a lógica do algoritmo, materializá-la em código e produzir uma saída final verificável.


## CT11.2

**Título da Competência**  
**Controlar o processamento iterativo de entradas por critério de parada explícito**

**Descrição Textual**  
Capacidade de processar quantidade indeterminada de dados em programas introdutórios, utilizando estruturas de repetição com critério de parada explícito e comportamento estável ao longo da execução.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO3, LO4)
- K mobilizados (Núcleo): (K05, K07)

**Especificação de Conhecimentos**
- **K05:** formulação de expressões relacionais e lógicas para controlar o fluxo iterativo. **Justificativa de evidência:** o critério de parada e a distinção entre valores válidos e valor sentinela dependem de comparações corretamente formuladas.
- **K07:** uso de repetição com término garantido em quantidade indeterminada de entradas. **Justificativa de evidência:** a própria estrutura central da tarefa exige laço funcional, estável e coerente com o valor de parada.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência demanda implementação operacional de laço com condição de término explícita, diretamente verificável no comportamento do programa.

**Pareamento Conhecimento–Habilidade**

K05 / Aplicar → formular condições relacionais e lógicas que controlem corretamente a continuidade e a interrupção do processamento.  
Verbos de Bloom: operar, implementar, resolver

K07 / Aplicar → implementar repetição com quantidade indeterminada de entradas e término garantido por critério explícito.  
Verbos de Bloom: iterar, executar, programar


**Especificação de Disposições**
- atenção ao critério de parada;
- consistência no controle do fluxo iterativo;
- disciplina lógica na repetição de processamento.


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.2 | Controlar o processamento iterativo de entradas por critério de parada explícito | atenção ao critério de parada; consistência no controle do fluxo iterativo; disciplina lógica na repetição de processamento | K05 | formular condições relacionais e lógicas que controlem corretamente a continuidade e a interrupção do processamento |
| CT11.2 | Controlar o processamento iterativo de entradas por critério de parada explícito | atenção ao critério de parada; consistência no controle do fluxo iterativo; disciplina lógica na repetição de processamento | K07 | implementar repetição com quantidade indeterminada de entradas e término garantido por critério explícito |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o processamento de quantidade indeterminada de números constitui o núcleo operacional do problema. A competência é ativada porque o estudante precisa manter a repetição funcional até a sentinela, sem incluir indevidamente o valor de parada no conjunto analisado.

## CT11.3

**Título da Competência**  
**Atualizar e comparar estados para produzir resultados extremos em sequências numéricas**

**Descrição Textual**  
Capacidade de manter e atualizar o estado de um programa ao longo do processamento de uma sequência de valores, utilizando comparações e decisões condicionais para produzir resultados agregados ou extremos de forma verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO3, LO5)
- K mobilizados (Núcleo): (K04, K05, K06)

**Especificação de Conhecimentos**
- **K04:** uso de variáveis e atribuições para registrar e atualizar resultados parciais. **Justificativa de evidência:** o maior e o menor valor somente emergem do processamento se o estado interno for mantido corretamente a cada leitura válida.
- **K05:** formulação de comparações numéricas que sustentam atualização de extremos. **Justificativa de evidência:** a correção do resultado final depende diretamente da comparação consistente entre valores lidos e valores armazenados.
- **K06:** seleção condicional para decidir quando atualizar ou preservar o estado do programa. **Justificativa de evidência:** a tarefa requer decisões reiteradas e observáveis entre atualizar o maior, o menor ou manter os valores correntes.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Analisar**, pois a competência requer discriminar situações de atualização de estado, relacionar comparações a decisões e rastrear o efeito dessas decisões no resultado final.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → atualizar variáveis de resultado de forma coerente com o estado corrente do processamento.  
Verbos de Bloom: manipular, armazenar, usar

K05 / Analisar → comparar valores para distinguir quando o estado do programa deve ser preservado ou atualizado.  
Verbos de Bloom: analisar, distinguir, relacionar

K06 / Analisar → decidir condicionalmente sobre a atualização dos resultados a partir das comparações realizadas.  
Verbos de Bloom: discriminar, estruturar, rastrear

**Especificação de Disposições**
- precisão na comparação entre valores;
- rigor na atualização do estado;
- atenção à consistência entre processamento e resultado final.


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.3 | Atualizar e comparar estados para produzir resultados extremos em sequências numéricas | precisão na comparação entre valores; rigor na atualização do estado; atenção à consistência entre processamento e resultado final | K04 | atualizar variáveis de resultado de forma coerente com o estado corrente do processamento |
| CT11.3 | Atualizar e comparar estados para produzir resultados extremos em sequências numéricas | precisão na comparação entre valores; rigor na atualização do estado; atenção à consistência entre processamento e resultado final | K05 | comparar valores para distinguir quando o estado do programa deve ser preservado ou atualizado |
| CT11.3 | Atualizar e comparar estados para produzir resultados extremos em sequências numéricas | precisão na comparação entre valores; rigor na atualização do estado; atenção à consistência entre processamento e resultado final | K06 | decidir condicionalmente sobre a atualização dos resultados a partir das comparações realizadas |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a produção do maior e do menor valor exige comparação contínua entre dados lidos e estado armazenado. A competência é ativada porque o estudante precisa analisar cada leitura válida, decidir sobre atualização e preservar a coerência do resultado final.

