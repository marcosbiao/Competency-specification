# RELATÓRIO CSP: TASK12

## Introdução

Este relatório situa a **TASK12** na fase de **Autoria de Competências**, explicitando os conhecimentos, objetivos de aprendizagem e competências mobilizados pela atividade. A tarefa solicita que o estudante analise um programa em C, determine o valor final de uma variável e justifique o resultado com base no comportamento do laço, nas condições avaliadas e nos desvios de fluxo presentes na execução.

A atividade produz evidências observáveis porque a resposta pode ser verificada em três planos: correção do resultado final, coerência do rastreamento da execução e qualidade da justificativa técnica. Também sustenta o modelo **K–S–D** sem redundância, pois articula conhecimentos centrais de programação imperativa introdutória, habilidades de análise do fluxo de execução e disposições relacionadas a rigor interpretativo, precisão e consistência argumentativa.

# 1. Análise da Entidade Instrucional

## Título

**TASK12: Análise de execução de programa com repetição, seleção e desvio de fluxo**

## Descrição

A atividade propõe a leitura analítica de um programa já fornecido no enunciado. O estudante deve interpretar a evolução do estado do programa ao longo da execução, identificar como o laço de repetição e as condições interferem no valor acumulado de uma variável e apresentar uma resposta final acompanhada de justificativa breve e tecnicamente consistente. O foco não está na implementação de uma solução nova, mas na compreensão precisa do comportamento de um programa existente.

## Processo de Desenvolvimento da Solução (em etapas)

1. Identificar a variável cujo valor final deve ser determinado e reconhecer seu estado inicial.
2. Examinar o funcionamento do laço de repetição, incluindo faixa de iteração e condição geral de continuidade.
3. Verificar, nas iterações relevantes, o efeito das condições lógicas sobre a execução das instruções seguintes.
4. Distinguir quais iterações contribuem para a atualização da variável e quais deixam de contribuir.
5. Consolidar o resultado final com justificativa coerente com a ordem real de execução do programa.

## Resultados Esperados

1. Indicação do valor final da variável solicitada.
2. Justificativa breve e tecnicamente consistente sobre os fatores que levam a esse resultado.
3. Evidência de leitura correta do fluxo de execução, incluindo inicialização, repetição, exclusão de iterações e interrupção do laço.

## Contexto de Aquisição

**Curso:** Bacharelado em Ciência da Computação  
**Organização da atividade:** individual  
**Ambiente provável:** avaliação escrita, lista de exercícios ou atividade dirigida em laboratório  
**Forma de avaliação:** resposta final acompanhada de justificativa breve e verificável  
**Natureza da evidência:** análise de código, rastreamento de execução e explicação técnica

## Perfil do Público-Alvo

A atividade é dirigida a estudantes iniciantes em programação que já tiveram contato introdutório com variáveis, expressões aritméticas e lógicas, estruturas de seleção e estruturas de repetição em C. Pressupõe familiaridade básica com leitura de código e acompanhamento do estado de variáveis ao longo da execução. Atende a necessidades formativas típicas do início da disciplina, especialmente no desenvolvimento de precisão interpretativa e justificativas baseadas no comportamento real do programa.

## Nível de Proficiência (critérios e dimensões)

| Nível | Leitura do fluxo do programa | Controle de estado da variável | Interpretação de condições | Qualidade da justificativa |
|---|---|---|---|---|
| **N1 - Inicial** | Reconhece a existência do laço e das condições, mas interpreta apenas parte da execução. | Identifica a variável principal, mas não acompanha corretamente todas as atualizações. | Reconhece condições simples, porém não explica adequadamente seu efeito no fluxo. | Apresenta resposta com justificativa insuficiente ou incompleta. |
| **N2 - Intermediário** | Acompanha a maior parte das iterações, com pequenas lacunas. | Rastreia atualizações principais, mas omite algumas contribuições ou exclusões relevantes. | Explica parcialmente o papel das condições no comportamento do programa. | Justifica o resultado com coerência parcial e verificabilidade limitada. |
| **N3 - Proficiente** | Reconstrói corretamente a ordem de execução e os desvios relevantes. | Rastreia corretamente as contribuições e não contribuições para o valor final. | Relaciona corretamente condições, desvios e resultado observado. | Justifica de modo claro, verificável e consistente. |
| **N4 - Avançado** | Explica a execução com precisão, economia textual e robustez técnica. | Articula com clareza a relação entre inicialização, atualização, exclusão de iterações e interrupção do laço. | Discute com precisão o efeito combinado das condições sobre a execução global. | Produz justificativa sintética, rigorosa e semanticamente precisa. |

# 2. Seleção e Enumeração de Conhecimentos

## K01 — Modelo de execução e noção de estado (paradigma imperativo)

1. Compreensão operacional de que programas imperativos evoluem por mudanças sucessivas de estado.
2. Interpretação de atribuições como transições de estado ao longo da execução.
3. Leitura do comportamento sequencial e iterativo em nível introdutório.

**Justificativa de mobilização na tarefa:** a atividade exige rastrear a evolução do estado de uma variável ao longo da execução e justificar por que o resultado final é produzido.

## K02 — Variáveis, constantes e tipos primitivos

1. Reconhecimento do papel de variáveis e constantes na armazenagem e atualização de valores.
2. Interpretação de identificadores e valores inteiros em programas introdutórios.
3. Compreensão do efeito operacional da inicialização e da atualização de variáveis.

**Justificativa de mobilização na tarefa:** o estudante precisa interpretar corretamente a variável acumuladora, o contador do laço e seus respectivos papéis no processamento.

## K03 — Expressões aritméticas e avaliação

1. Compreensão de expressões de atualização numérica em atribuições.
2. Interpretação de operações aritméticas associadas ao acúmulo de valores.
3. Relação entre expressão avaliada e novo estado produzido na variável.

**Justificativa de mobilização na tarefa:** o valor final decorre de atualizações aritméticas sucessivas, cuja leitura correta é indispensável para explicar o resultado.

## K04 — Expressões lógicas e condições

1. Leitura de condições booleanas com operadores relacionais e lógicos.
2. Interpretação de verdade e falsidade em decisões de fluxo.
3. Compreensão do papel de condições compostas sobre a continuidade da execução.

**Justificativa de mobilização na tarefa:** a execução depende de condições que filtram iterações e determinam quando certas instruções deixam de produzir efeito no acúmulo.

## K06 — Estruturas de seleção

1. Compreensão de desvios condicionais como escolha entre caminhos de execução.
2. Interpretação do impacto de instruções condicionais sobre o comportamento do programa.
3. Relação entre condição satisfeita e efeito imediato no fluxo.

**Justificativa de mobilização na tarefa:** a atividade envolve decisões condicionais que alteram diretamente o processamento de determinadas iterações.

## K07 — Estruturas de repetição

1. Compreensão de laços controlados por contagem e condição de continuidade.
2. Interpretação do processamento iterativo e da noção de parada do laço.
3. Relação entre iteração, atualização e término da repetição.

**Justificativa de mobilização na tarefa:** o núcleo da atividade está no acompanhamento de um laço iterativo e na análise de como sua execução parcial produz o resultado final.

# 3. Identificação de Objetivos de Aprendizagem

## LO1
**Interpretar o estado de variáveis em programas imperativos simples ao longo da execução.**  
**K associados:** K01, K02, K03

## LO2
**Analisar condições lógicas e decisões condicionais que alteram o caminho de execução de um programa.**  
**K associados:** K04, K06, K01

## LO3
**Examinar o comportamento de laços com contador, acumulador, exclusão de iterações e parada antecipada.**  
**K associados:** K07, K02, K03, K04

## LO4
**Comunicar a análise da execução com justificativa técnica breve, coerente e verificável.**  
**K associados:** K01, K04, K07

# 4. Definição de Competências

## 4.1 Competência Geral 

No domínio da Computação, a tarefa contribui para a capacidade de **analisar o comportamento de programas imperativos introdutórios, interpretando o efeito de variáveis, expressões, condições e estruturas de repetição sobre os resultados produzidos**.

**BNCC:** não aplicável como eixo formal de alinhamento nesta tarefa.

## 4.2 Especificações de Competências

### CT12.1

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples

**Descrição Textual**  
Interpretar e operar com variáveis, constantes e valores primitivos em programas introdutórios, reconhecendo inicialização, atualização e avaliação de expressões que afetam o estado do programa.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO1
2. K mobilizados (Núcleo): K01, K02, K03

**Especificação de Conhecimentos**
1. **K01:** modelo de execução e noção de estado.  
   **Justificativa de evidência:** a tarefa exige acompanhar como o estado da variável evolui ao longo da execução.
2. **K02:** variáveis, constantes e tipos primitivos.  
   **Justificativa de evidência:** a análise depende da interpretação correta da variável acumuladora, do contador e dos valores utilizados.
3. **K03:** expressões aritméticas e avaliação.  
   **Justificativa de evidência:** o resultado final depende da leitura correta das expressões que atualizam a variável.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Nível predominante:** Aplicar

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → explicitar o estado do programa a partir da sequência de atualizações realizadas sobre a variável.  
Verbos de Bloom: executar, operar, aplicar

K02 / Aplicar → identificar e utilizar corretamente variáveis, constantes e valores primitivos segundo seu papel no processamento.  
Verbos de Bloom: usar, manipular, selecionar

K03 / Aplicar → avaliar expressões aritméticas simples que alteram o valor de uma variável ao longo da execução.  
Verbos de Bloom: calcular, computar, aplicar


**Especificação de Disposições**  
1. Atenção ao valor corrente das variáveis.  
2. Precisão na leitura de expressões.  
3. Rigor na interpretação do estado do programa.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.1 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples | Atenção ao valor corrente das variáveis | K01 | explicitar o estado do programa a partir das atualizações |
| CT12.1 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples | Precisão na leitura de expressões | K02 | identificar e utilizar corretamente variáveis e constantes |
| CT12.1 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões e conversões simples | Rigor interpretativo | K03 | avaliar expressões aritméticas simples de atualização |

**Definição de Ativação**
1. Restrição de ativação: obrigatória  
2. Modo de ativação: analítica  
3. Função de ativação: núcleo  
4. Justificativa curta baseada na tarefa: a resolução depende de interpretar corretamente o papel das variáveis e das expressões que modificam seu valor. Sem isso, o estudante não consegue justificar o resultado final de forma consistente.

### CT12.2

**Título da Competência**  
Controlar o fluxo com decisões condicionais, formulando expressões lógicas corretas

**Descrição Textual**  
Interpretar estruturas de decisão em programas introdutórios, analisando como condições simples e compostas alteram o caminho de execução e interferem no processamento.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO2
2. K mobilizados (Núcleo): K04, K06, K01

**Especificação de Conhecimentos**
1. **K04:** expressões lógicas e condições.  
   **Justificativa de evidência:** a questão exige interpretar corretamente as condições que determinam desvios no fluxo.
2. **K06:** estruturas de seleção.  
   **Justificativa de evidência:** o comportamento do programa depende diretamente de instruções condicionais.
3. **K01:** modelo de execução e noção de estado.  
   **Justificativa de evidência:** os desvios condicionais alteram a sequência de estados observada na execução.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Nível predominante:** Analisar

**Pareamento Conhecimento–Habilidade**

K04 / Analisar → interpretar condições lógicas simples e compostas para explicar sua interferência no processamento.  
Verbos de Bloom: analisar, discriminar, relacionar

K06 / Analisar → distinguir caminhos alternativos de execução produzidos por decisões condicionais.  
Verbos de Bloom: distinguir, examinar, estruturar

K01 / Analisar → relacionar mudanças de fluxo a alterações sucessivas no estado do programa.  
Verbos de Bloom: relacionar, decompor, rastrear


**Especificação de Disposições**  
1. Atenção ao efeito das condições compostas.  
2. Cuidado na distinção entre executar, ignorar e interromper.  
3. Clareza na justificativa do fluxo.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.2 | Controlar o fluxo com decisões condicionais, formulando expressões lógicas corretas | Atenção ao efeito das condições compostas | K04 | interpretar condições lógicas para explicar o processamento |
| CT12.2 | Controlar o fluxo com decisões condicionais, formulando expressões lógicas corretas | Cuidado com desvios de fluxo | K06 | distinguir caminhos alternativos de execução |
| CT12.2 | Controlar o fluxo com decisões condicionais, formulando expressões lógicas corretas | Clareza justificativa | K01 | relacionar mudanças de fluxo a estados do programa |

**Definição de Ativação**
1. Restrição de ativação: obrigatória  
2. Modo de ativação: analítica  
3. Função de ativação: núcleo  
4. Justificativa curta baseada na tarefa: o enunciado depende de decisões condicionais que modificam diretamente o que ocorre em cada iteração. A interpretação correta dessas condições é central para sustentar o resultado final.

### CT12.3

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras

**Descrição Textual**  
Analisar e controlar o comportamento de laços em programas introdutórios, reconhecendo o papel de contadores, acumuladores, exclusões de iteração e condições de interrupção segura.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO3
2. K mobilizados (Núcleo): K07, K02, K03, K04

**Especificação de Conhecimentos**
1. **K07:** estruturas de repetição.  
   **Justificativa de evidência:** a tarefa está centrada na interpretação de um laço com controle por contador.
2. **K02:** variáveis, constantes e tipos primitivos.  
   **Justificativa de evidência:** a análise exige reconhecer o papel do contador e do acumulador.
3. **K03:** expressões aritméticas e avaliação.  
   **Justificativa de evidência:** o acumulador é atualizado por expressão aritmética ao longo das iterações válidas.
4. **K04:** expressões lógicas e condições.  
   **Justificativa de evidência:** a parada e a exclusão de iterações dependem da avaliação de condições.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Nível predominante:** Analisar

**Pareamento Conhecimento–Habilidade**

K07 / Analisar → explicar o comportamento de laços com base no contador, nas iterações efetivamente executadas e na condição de parada.  
Verbos de Bloom: examinar, decompor, analisar

K02 / Aplicar → identificar corretamente o papel funcional de contador e acumulador no processamento iterativo.  
Verbos de Bloom: usar, manipular, aplicar

K03 / Aplicar → avaliar atualizações acumulativas simples realizadas durante as iterações válidas do laço.  
Verbos de Bloom: calcular, computar, executar

K04 / Analisar → interpretar condições que excluem iterações ou interrompem a repetição antes do limite previsto.  
Verbos de Bloom: analisar, relacionar, discriminar


**Especificação de Disposições**  
1. Disciplina no acompanhamento das iterações.  
2. Precisão no tratamento de exclusões e interrupções.  
3. Consistência na leitura do comportamento iterativo.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | Disciplina no acompanhamento das iterações | K07 | explicar o comportamento de laços com base no contador e na parada |
| CT12.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | Precisão funcional | K02 | identificar o papel de contador e acumulador |
| CT12.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | Consistência numérica | K03 | avaliar atualizações acumulativas simples |
| CT12.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | Atenção às condições | K04 | interpretar exclusões e interrupções da repetição |

**Definição de Ativação**
1. Restrição de ativação: obrigatória  
2. Modo de ativação: analítica  
3. Função de ativação: núcleo  
4. Justificativa curta baseada na tarefa: a questão solicita explicar o valor final de uma variável em contexto iterativo. Isso exige interpretar contador, acumulador, iterações ignoradas e interrupção do laço como evidências centrais do comportamento do programa.

### CT12.4

**Título da Competência**  
Comunicar a análise da execução descrevendo o comportamento do programa e as evidências do resultado final

**Descrição Textual**  
Apresentar justificativas técnicas curtas e verificáveis sobre o comportamento de programas introdutórios, articulando sequência de execução, mudanças de estado e fatores que sustentam o resultado produzido.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO4
2. K mobilizados (Núcleo): K01, K04, K07

**Especificação de Conhecimentos**
1. **K01:** modelo de execução e noção de estado.  
   **Justificativa de evidência:** a justificativa depende de reconstruir o estado do programa ao longo da execução.
2. **K04:** expressões lógicas e condições.  
   **Justificativa de evidência:** a explicação deve considerar os desvios provocados pelas condições avaliadas.
3. **K07:** estruturas de repetição.  
   **Justificativa de evidência:** a argumentação precisa respeitar a progressão iterativa efetivamente executada.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Nível predominante:** Avaliar

**Pareamento Conhecimento–Habilidade**

K01 / Avaliar → sustentar a resposta final com base em evidências do estado assumido pelo programa ao longo da execução.  
Verbos de Bloom: justificar, defender, validar

K04 / Analisar → explicitar o papel das condições na produção do resultado observado.  
Verbos de Bloom: analisar, relacionar, examinar

K07 / Analisar → organizar a justificativa segundo a ordem das iterações efetivamente processadas.  
Verbos de Bloom: estruturar, decompor, rastrear


**Especificação de Disposições**  
1. Clareza na comunicação técnica.  
2. Coerência entre resultado e justificativa.  
3. Compromisso com evidências observáveis.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.4 | Comunicar a análise da execução descrevendo o comportamento do programa e as evidências do resultado final | Clareza na comunicação técnica | K01 | sustentar a resposta com base no estado do programa |
| CT12.4 | Comunicar a análise da execução descrevendo o comportamento do programa e as evidências do resultado final | Coerência justificativa | K04 | explicitar o papel das condições no resultado |
| CT12.4 | Comunicar a análise da execução descrevendo o comportamento do programa e as evidências do resultado final | Compromisso com evidências | K07 | organizar a justificativa segundo as iterações processadas |

**Definição de Ativação**
1. Restrição de ativação: obrigatória  
2. Modo de ativação: justificatória  
3. Função de ativação: núcleo  
4. Justificativa curta baseada na tarefa: o enunciado não pede apenas um valor final, mas uma explicação dos fatores que o produzem. Por isso, a comunicação da análise é parte constitutiva da evidência e não apenas um complemento textual.
