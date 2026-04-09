# Relatório CSP — Autoria de Competências

## Introdução

Este relatório situa a tarefa na fase de **Autoria de Competências** do Competency Specification Process, com foco na explicitação rastreável de conhecimentos, objetivos de aprendizagem e competências mobilizados por uma atividade introdutória de programação. A tarefa solicita a implementação de um programa que processe registros sucessivos de entrevistados, classifique preferências clubísticas, consolide contagens, calcule médias salariais condicionadas e informe o total de participantes.

A atividade elicita evidências observáveis porque o estudante precisa produzir um artefato executável, manter estado coerente ao longo do processamento, aplicar regras de decisão derivadas do enunciado e apresentar resultados verificáveis. Isso permite distinguir com clareza os conhecimentos efetivamente mobilizados, as habilidades observáveis associadas à resolução e as disposições necessárias para executar a tarefa com consistência técnica.

O modelo K–S–D é suportado sem redundância porque a tarefa articula um conjunto enxuto de conhecimentos centrais da disciplina, convertidos em objetivos reutilizáveis e consolidados em competências estáveis de Computação, evitando microfragmentação excessiva e preservando reuso em tarefas semelhantes de processamento de dados.

# 1. Análise da Entidade Instrucional

## 1.1 Título

Processamento de dados de uma pesquisa sobre preferência clubística e perfil dos entrevistados

## 1.2 Descrição

A tarefa consiste em desenvolver um programa que leia, para cada entrevistado, um código de clube de preferência, um valor salarial e um indicador de cidade natal. O conjunto de entrevistados é indeterminado, exigindo processamento iterativo de registros. Ao final, o programa deve consolidar contagens por clube, médias salariais para dois grupos específicos, uma contagem condicionada por cidade natal e clube, além do total de pessoas processadas.

## 1.3 Processo de Desenvolvimento da Solução

1. Identificar as entradas categóricas e numéricas fornecidas pelo problema e as saídas solicitadas.
2. Definir variáveis adequadas para leitura, contagem, acumulação salarial e totalização.
3. Organizar um fluxo repetitivo para leitura sucessiva dos registros, preservando um critério consistente de encerramento.
4. Aplicar condições para classificar cada registro e atualizar apenas os acumuladores pertinentes.
5. Consolidar os dados acumulados em indicadores finais, incluindo médias condicionadas e contagens específicas.
6. Apresentar os resultados de forma verificável e coerente com as regras do enunciado.

## 1.4 Resultados Esperados

1. Código-fonte executável.
2. Saída final contendo o número de torcedores por clube.
3. Saída final contendo as médias salariais dos torcedores de Grêmio e Internacional.
4. Saída final contendo a quantidade de pessoas nascidas em Porto Alegre que não torcem por nenhum dos dois principais clubes.
5. Saída final contendo o total de entrevistados.
6. Justificativa breve que permita compreender a lógica geral de processamento adotada.
7. Registros de teste ou demonstração compatíveis com a verificabilidade dos resultados.

## 1.5 Contexto de Aquisição

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

## 1.6 Perfil do Público-Alvo

O público-alvo é composto por estudantes em etapa inicial de formação em Computação, após contato prévio com variáveis, tipos primitivos, entrada e saída, expressões, estruturas de decisão e estruturas de repetição. Como necessidade principal, a tarefa exige coordenação entre múltiplos acumuladores, classificação de casos e consolidação de indicadores, o que demanda atenção ao controle de estado e à verificabilidade dos resultados.

## 1.7 Nível de Proficiência (critérios e dimensões)

| Nível | Organização do fluxo entrada–processamento–saída | Controle de repetição e manutenção de estado | Classificação condicional e cobertura de casos | Cálculo de indicadores agregados | Verificabilidade e clareza do artefato |
|---|---|---|---|---|---|
| **N1 — Inicial** | Estrutura apenas partes do fluxo, com lacunas de integração. | Processa poucos registros ou perde consistência no estado. | Trata apenas casos básicos ou deixa lacunas. | Apresenta cálculos incompletos ou inconsistentes. | Saída pouco interpretável e justificativa insuficiente. |
| **N2 — Intermediário** | Organiza o fluxo principal, mas com inconsistências pontuais. | Mantém parte dos acumuladores corretamente, mas com falhas ocasionais. | Cobre os casos principais, mas com fragilidade em condições compostas. | Calcula parte dos indicadores com pequenas falhas. | Saída parcialmente verificável. |
| **N3 — Proficiente** | Organiza integralmente o fluxo com coerência entre entradas, processamento e saídas. | Controla laço, parada e atualização de estado de modo consistente. | Cobre adequadamente os casos previstos e atualiza os indicadores corretos. | Consolida contagens e médias solicitadas com coerência aritmética. | Saída verificável e justificativa breve coerente. |
| **N4 — Avançado** | Estrutura o fluxo com clareza superior, prevendo variações e refinando a comunicação dos resultados. | Generaliza o controle iterativo com maior robustez e melhor abstração operacional. | Refina as decisões com alto rigor lógico e excelente legibilidade. | Consolida indicadores com maior refinamento, incluindo comunicação mais precisa de convenções. | Saída altamente clara, bem organizada e acompanhada de justificativa tecnicamente sólida. |


# 2. Seleção e Enumeração de Conhecimentos 

## K01 — Modelo de execução e noção de estado (paradigma imperativo)

Descrição:
1. Compreensão de que o programa modifica seu estado ao longo da execução por meio de atribuições sucessivas.
2. Entendimento do papel de contadores, acumuladores e totalizadores como representações do estado corrente.
3. Capacidade de relacionar cada atualização de variável ao efeito esperado no processamento global.

Justificativa de mobilização na tarefa:  
A tarefa depende de atualização sucessiva de contagens, somas e total geral a cada entrevistado processado, tornando o controle de estado diretamente relevante.

## K02 — Variáveis, constantes e tipos primitivos

Descrição:
1. Representação de dados categóricos e numéricos com identificadores apropriados.
2. Uso coerente de tipos primitivos para salário, códigos de clube, cidade natal, contagens e médias.
3. Manutenção de consistência entre o papel lógico da variável e sua utilização no programa.

Justificativa de mobilização na tarefa:  
A solução exige variáveis distintas para entrada, contagem, soma salarial, médias e totalização, com compatibilidade entre natureza do dado e uso computacional.

## K03 — Expressões aritméticas e avaliação

Descrição:
1. Construção de expressões aritméticas para atualização de somas e cálculo de médias.
2. Avaliação coerente de operações envolvendo salários, contagens e resultados numéricos.
3. Relação entre expressão aritmética, atribuição e resultado final apresentado.

Justificativa de mobilização na tarefa:  
As médias salariais e a acumulação de salários requerem composição aritmética correta e avaliação consistente das expressões utilizadas.

## K04 — Expressões lógicas e condições

Descrição:
1. Construção de condições booleanas para identificar casos relevantes do enunciado.
2. Interpretação de verdade e falsidade para seleção de caminhos de execução.
3. Uso de condições simples e compostas para decidir quando atualizar cada indicador.

Justificativa de mobilização na tarefa:  
O programa precisa verificar clube de preferência, cidade natal e combinações específicas dessas informações para decidir corretamente o que será acumulado.

## K05 — Estrutura sequencial e E/S básica

Descrição:
1. Organização do fluxo de leitura, processamento e apresentação dos resultados.
2. Relação entre dados de entrada, transformação interna e comunicação das saídas.
3. Produção de saídas verificáveis compatíveis com os indicadores solicitados.

Justificativa de mobilização na tarefa:  
O problema solicita um programa com entradas bem definidas e múltiplas saídas consolidadas, o que demanda estrutura sequencial clara e observável.

## K06 — Estruturas de seleção

Descrição:
1. Escolha de caminhos alternativos de execução com base em condições.
2. Cobertura de casos de classificação por clube e por condição combinada.
3. Encadeamento coerente de decisões para evitar omissões e atualizações indevidas.

Justificativa de mobilização na tarefa:  
A classificação dos entrevistados e a atualização seletiva de contadores e somas exigem estruturas condicionais diretamente observáveis no artefato.

## K07 — Estruturas de repetição

Descrição:
1. Processamento sucessivo de registros em quantidade desconhecida.
2. Controle de laço por critério consistente de continuidade e encerramento.
3. Integração entre repetição e atualização de acumuladores ao longo da execução.

Justificativa de mobilização na tarefa:  
O enunciado explicita uma pesquisa com número desconhecido de pessoas, o que torna indispensável o uso de repetição para processar os registros.

# 3. Identificação de Objetivos de Aprendizagem

## LO1

Realizar entrada e saída de dados de forma consistente, organizando o fluxo de leitura e apresentação dos resultados solicitados.

**K associados:** K02, K05

## LO2

Calcular indicadores agregados a partir de dados acumulados, preservando coerência aritmética entre somas, contagens e médias.

**K associados:** K03, K02, K05

## LO3

Controlar o fluxo do programa com decisões condicionais, formulando expressões lógicas corretas para classificar registros segundo as regras do problema.

**K associados:** K04, K06

## LO4

Controlar o fluxo do programa com repetição, utilizando contadores, acumuladores e critério consistente de parada para processar quantidade indeterminada de registros.

**K associados:** K01, K07

# 4. Definição de Competências

## 4.1 Competência Geral

Desenvolver programas estruturados capazes de receber registros sucessivos, classificá-los por regras explícitas, consolidar indicadores quantitativos e comunicar resultados verificáveis por meio de variáveis, decisões, repetição e cálculo aritmético.

**Observação sobre BNCC:** não aplicável neste relatório, pois não há base segura para alinhamento específico com códigos em um contexto de disciplina introdutória de programação fora da educação básica.

## 4.2 Especificações de Competências

### CT05.1

**Título da Competência**  
Realizar entrada e saída de dados com consistência e formatação apropriada

**Descrição Textual**  
Organizar o fluxo de leitura de dados e a apresentação de resultados em programas introdutórios, garantindo coerência entre as entradas recebidas, os indicadores produzidos e a forma verificável de comunicação das saídas.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO1, LO2
2. K mobilizados: K02, K03, K05

**Especificação de Conhecimentos**
1. K02: sustenta a declaração e o uso coerente de variáveis para entradas, contagens, somas e médias.
2. K03: fundamenta o cálculo dos indicadores numéricos derivados do processamento acumulado.
3. K05: organiza a sequência de leitura, processamento e apresentação dos resultados solicitados.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio em **Aplicar**, pois a competência demanda implementar leitura, cálculos numéricos e apresentação verificável dos resultados em um programa funcional.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar e utilizar variáveis compatíveis com dados categóricos, valores salariais e indicadores consolidados.  
Verbos de Bloom: usar, manipular, implementar

K03 / Aplicar → calcular contagens derivadas, somas e médias com expressões aritméticas coerentes ao processamento realizado.  
Verbos de Bloom: calcular, computar, resolver

K05 / Aplicar → estruturar a entrada e a saída do programa de modo verificável, com apresentação apropriada dos resultados finais.  
Verbos de Bloom: executar, implementar, documentar


**Especificação de Disposições**
1. Clareza na organização do fluxo de interação com dados.
2. Cuidado com a consistência entre variáveis e resultados exibidos.
3. Zelo com a legibilidade e verificabilidade das saídas.

**Competências Alinhadas à BNCC**  
Não aplicável neste relatório.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT05.1 | Realizar entrada e saída de dados com consistência e formatação apropriada | clareza, consistência, zelo com verificabilidade | K02 | declarar e utilizar variáveis compatíveis com dados categóricos, valores salariais e indicadores consolidados |
| CT05.1 | Realizar entrada e saída de dados com consistência e formatação apropriada | clareza, consistência, zelo com verificabilidade | K03 | calcular contagens derivadas, somas e médias com expressões aritméticas coerentes ao processamento realizado |
| CT05.1 | Realizar entrada e saída de dados com consistência e formatação apropriada | clareza, consistência, zelo com verificabilidade | K05 | estruturar a entrada e a saída do programa de modo verificável, com apresentação apropriada dos resultados finais |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a tarefa exige leitura de dados categóricos e numéricos, cálculo de indicadores e comunicação dos resultados finais. Essa competência é diretamente ativada pelo produto principal da atividade, que é o programa executável com saídas observáveis.

### CT05.2

**Título da Competência**  
Controlar o fluxo com decisões condicionais, formulando expressões lógicas corretas

**Descrição Textual**  
Aplicar estruturas de decisão para classificar registros, distinguir casos relevantes do problema e garantir que cada atualização de contadores e acumuladores ocorra apenas nas situações logicamente pertinentes.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO3
2. K mobilizados: K04, K06

**Especificação de Conhecimentos**
1. K04: explicita as condições simples e compostas que determinam quando um registro pertence a determinada categoria do problema.
2. K06: sustenta a escolha correta de caminhos alternativos de execução para classificar registros sem lacunas nem sobreposição indevida.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio em **Aplicar**, com componente de **Analisar** na distinção entre casos condicionais e seus efeitos sobre o processamento.

**Pareamento Conhecimento–Habilidade**

K04 / Analisar → distinguir e relacionar condições necessárias à classificação correta de cada registro.  
Verbos de Bloom: distinguir, relacionar, examinar

K06 / Aplicar → implementar estruturas de seleção para cobrir os casos previstos pelo problema sem lacunas de classificação.  
Verbos de Bloom: implementar, executar, usar


**Especificação de Disposições**
1. Rigor lógico na formulação das condições.
2. Atenção à cobertura completa dos casos previstos.
3. Coerência entre regra do problema e atualização dos indicadores.

**Competências Alinhadas à BNCC**  
Não aplicável neste relatório.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT05.2 | Controlar o fluxo com decisões condicionais, formulando expressões lógicas corretas | rigor lógico, atenção à cobertura, coerência | K04 | distinguir e relacionar condições necessárias à classificação correta de cada registro |
| CT05.2 | Controlar o fluxo com decisões condicionais, formulando expressões lógicas corretas | rigor lógico, atenção à cobertura, coerência | K06 | implementar estruturas de seleção para cobrir os casos previstos pelo problema sem lacunas de classificação |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: as saídas dependem diretamente da correta classificação de cada entrevistado segundo clube de preferência e cidade natal. A competência é central porque erros nas decisões comprometem simultaneamente contagens, somas e médias.

### CT05.3

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras

**Descrição Textual**  
Implementar processamento iterativo de conjuntos indeterminados de registros, preservando a atualização coerente do estado do programa por meio de contadores, acumuladores e um critério consistente de encerramento.

**Cobertura e rastreabilidade**
1. LOs cobertos: LO4
2. K mobilizados: K01, K07

**Especificação de Conhecimentos**
1. K01: modela o estado do programa e evidencia a necessidade de atualização coerente de contadores, acumuladores e totalizadores durante a execução.
2. K07: sustenta a leitura repetida de registros em quantidade desconhecida e o controle de laço com parada consistente.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio em **Aplicar**, com componente de **Analisar** no rastreamento do estado durante a execução iterativa.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → rastrear e atualizar o estado do programa durante o processamento iterativo de registros.  
Verbos de Bloom: rastrear, atualizar, modelar

K07 / Aplicar → implementar laços para processar quantidade indeterminada de registros com parada consistente e atualização segura dos acumuladores.  
Verbos de Bloom: iterar, executar, implementar


**Especificação de Disposições**
1. Precisão na atualização do estado do programa.
2. Atenção ao critério de continuidade e encerramento do processamento.
3. Disciplina na manutenção consistente dos acumuladores.

**Competências Alinhadas à BNCC**  
Não aplicável neste relatório.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT05.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | precisão, atenção à parada, disciplina | K01 | rastrear e atualizar o estado do programa durante o processamento iterativo de registros |
| CT05.3 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | precisão, atenção à parada, disciplina | K07 | implementar laços para processar quantidade indeterminada de registros com parada consistente e atualização segura dos acumuladores |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a pesquisa envolve quantidade desconhecida de entrevistados, o que exige processamento iterativo com contadores, acumuladores e um critério claro de parada. Sem essa competência, a solução não consegue consolidar o conjunto completo de dados da pesquisa.