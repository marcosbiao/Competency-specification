# RELATÓRIO CSP: TASK16.7

## Introdução

Este relatório situa a TASK16.7 na fase de **Autoria de Competências** do Competency Specification Process, com base exclusiva na descrição pedagógica da atividade, no catálogo fixo de conhecimentos da disciplina e no alinhamento com a BNCC de Computação quando defensável. A tarefa solicita a leitura de um vetor `G(13)` correspondente ao gabarito de uma loteria esportiva, seguida da leitura do número do cartão de cada apostador e de um vetor `R(13)` com suas respostas. Em seguida, o algoritmo deve comparar as duas sequências, contabilizar os acertos, exibir o número do apostador e seu total de acertos e, no caso de treze acertos, acrescentar a mensagem **"GANHADOR, PARABÉNS"**.

A atividade produz evidências observáveis de interpretação de enunciado, organização algorítmica, uso de entrada e saída de dados, processamento de coleções homogêneas por índice, comparação posicional, repetição e seleção condicional. Por isso, sustenta uma modelagem K–S–D com boa rastreabilidade, baixa redundância e alta possibilidade de reuso em outras tarefas introdutórias de programação em C.

---

## 1. Análise da Entidade Instrucional

### 1.1 Título

**TASK16.7: Verificação de apostas em loteria esportiva com gabarito e respostas em vetor**

### 1.2 Descrição

A tarefa requer a implementação de um algoritmo em C que leia um gabarito com 13 números inteiros, todos no intervalo de 1 a 60, e, para cada apostador, leia o número do cartão e um vetor de 13 respostas. O programa deve comparar gabarito e respostas posição a posição, calcular a quantidade de acertos de cada apostador e exibir esse resultado. Quando o número de acertos for igual a 13, a saída deve incluir a mensagem **"GANHADOR, PARABÉNS"**.

Do ponto de vista instrucional, trata-se de uma tarefa típica de programação introdutória, adequada à prática de tradução de enunciado em algoritmo, organização de fluxo de leitura e escrita, uso de vetores e controle iterativo. A solução correta depende menos de complexidade algorítmica e mais de precisão na implementação.

### 1.3 Processo de Desenvolvimento da Solução

O desenvolvimento da solução requer interpretar o enunciado, identificar corretamente os dados de entrada e os resultados esperados, selecionar estruturas de dados compatíveis com o problema e organizar o fluxo geral de processamento. Do ponto de vista cognitivo, a tarefa mobiliza decomposição do problema, abstração dos elementos relevantes, definição de uma estratégia de comparação entre dados correspondentes e controle do processamento repetido de diferentes ocorrências. Também exige atenção ao tratamento de um caso especial previsto no enunciado, sem perder a consistência do formato de saída.

### 1.4 Resultados Esperados

1. Programa em C funcional e compatível com o enunciado.
2. Leitura correta do vetor gabarito.
3. Leitura correta do identificador do apostador e de seu vetor de respostas.
4. Comparação posicional correta entre os dois vetores.
5. Contagem correta do número de acertos.
6. Exibição do número do apostador e do total de acertos em formato apropriado.
7. Emissão correta da mensagem **"GANHADOR, PARABÉNS"** quando houver 13 acertos.

### 1.5 Contexto de Aquisição
- **Curso/organização:** disciplina de Introdução à Programação, em nível de graduação.
- **Ambiente:** laboratório, com computador compartilhado por equipe.
- **Forma de realização:** equipes de até três integrantes, com rodízio de operador a cada vinte minutos.
- **Restrições:** duas horas de duração, consulta apenas a material impresso e sem acesso à internet.
- **Avaliação:** correção funcional por juiz automático, com foco em aderência ao enunciado, consistência entre entrada, processamento e saída e submissão válida.

### 1.6 Perfil do Público-Alvo

A tarefa é voltada a estudantes iniciantes em programação que já tiveram contato com variáveis, entrada e saída de dados, estruturas de repetição, seleção condicional e vetores em C. O público necessita consolidar a passagem do enunciado para o algoritmo, com atenção especial à precisão de leitura, ao uso de índices e à correspondência entre regra do problema e comportamento do programa.

### 1.7 Nível de Proficiência

| Nível de Proficiência | Tradução do problema em algoritmo por decomposição e abstração | Entrada e saída de dados com formatação apropriada | Representação e processamento de coleções homogêneas com vetores | Qualidade global da solução |
|---|---|---|---|---|
| **N1 - Inicial** | Identifica parcialmente o problema, mas organiza a solução de modo incompleto ou confuso. | Lê ou escreve dados com erros de ordem, formato ou completude. | Usa vetores de forma incompleta ou com erros de índice, leitura ou comparação. | A solução é incompleta ou não produz resultados confiáveis. |
| **N2 - Intermediário** | Decompõe o problema em etapas básicas, mas ainda com fragilidades no encadeamento lógico. | Realiza entrada e saída parcialmente corretas, com pequenas inconsistências de formatação. | Representa os dados em vetores e executa parte do processamento, mas ainda com falhas na contagem ou no tratamento do caso especial. | A solução resolve parte do problema, mas apresenta inconsistências funcionais. |
| **N3 - Proficiente** | Traduz corretamente o enunciado em etapas algorítmicas claras e coerentes. | Realiza corretamente a leitura dos dados e a exibição dos resultados no formato esperado. | Representa gabarito e respostas em vetores, compara posição a posição e contabiliza corretamente os acertos. | A solução é correta, consistente e aderente ao enunciado. |
| **N4 - Avançado** | Decompõe o problema com clareza, economia e boa organização lógica, tornando a solução facilmente compreensível e verificável. | Mantém entrada e saída rigorosamente organizadas, estáveis e precisas em diferentes casos de teste. | Processa vetores com segurança, clareza e rastreabilidade, incluindo corretamente o tratamento do caso de 13 acertos. | A solução é correta, clara, robusta e facilmente depurável. |


## 2. Seleção e Enumeração de Conhecimentos

### K02: Variáveis, constantes e tipos primitivos

1. Uso de variáveis inteiras para armazenar cartão, índice e número de acertos.
2. Atribuição e atualização coerente de contadores e identificadores.
3. Compatibilidade entre o tipo de dado e o papel desempenhado na solução.

**Justificativa de mobilização:** a tarefa exige variáveis escalares para controlar leitura, percorrimento dos vetores e contagem dos acertos.

### K04: Expressões lógicas e condições

1. Formulação de condições booleanas por igualdade entre elementos.
2. Interpretação correta da correspondência entre gabarito e resposta.
3. Formulação da condição que caracteriza o caso vencedor.

**Justificativa de mobilização:** o programa depende de comparações posicionais e de uma condição explícita para identificar o caso de 13 acertos.

### K05: Estrutura sequencial e E/S básica

1. Organização do fluxo de leitura, processamento e saída.
2. Encadeamento adequado entre entrada do gabarito, leitura das respostas e emissão dos resultados.
3. Produção de saída verificável e aderente ao enunciado.

**Justificativa de mobilização:** a correção automática depende da consistência do fluxo entrada → processamento → saída.

### K06: Estruturas de seleção

1. Escolha de caminhos de execução a partir de condições.
2. Tratamento explícito do caso especial de pontuação máxima.
3. Integração da decisão condicional ao fluxo geral do programa.

**Justificativa de mobilização:** a mensagem de vencedor exige seleção condicional associada ao número de acertos.

### K07: Estruturas de repetição

1. Percorrimento controlado de vetores por índice.
2. Repetição de comparações ao longo das 13 posições.
3. Processamento iterativo de múltiplos dados de entrada.

**Justificativa de mobilização:** a contagem de acertos é produzida por repetição sistemática e controlada.

### K08: Vetores e matrizes em C

1. Representação de gabarito e respostas como coleções homogêneas indexadas.
2. Acesso posicional a elementos de vetores unidimensionais.
3. Processamento paralelo de duas sequências de mesmo tamanho.

**Justificativa de mobilização:** a estrutura central da tarefa é o vetor, tanto para o gabarito quanto para as respostas do apostador.



## 3. Identificação de Objetivos de Aprendizagem

### LO1

Traduzir um problema simples de processamento de dados em uma sequência algorítmica clara, distinguindo etapas de leitura, comparação, contagem e exibição de resultados.

**K associados:** K05, K07, K08

### LO2

Realizar entrada e saída de dados em linguagem C com ordem, formatação e correspondência adequadas ao enunciado.

**K associados:** K02, K05

### LO3

Representar e percorrer coleções homogêneas com vetores, utilizando índices válidos e acesso posicional consistente.

**K associados:** K07, K08

### LO4

Comparar elementos correspondentes de vetores, acumular ocorrências de acerto e aplicar uma condição explícita para destacar o resultado máximo.

**K associados:** K02, K04, K06, K07, K08


## 4. Definição de Competências

### 4.1 Competência Geral

Aplicar princípios da programação imperativa para traduzir problemas introdutórios em algoritmos claros, representar dados em coleções homogêneas e produzir saídas verificáveis por meio de estruturas de repetição, comparação e seleção.

**Alinhamento geral com a BNCC de Computação:** há aderência principalmente às habilidades **EF06CO02**, **EF06CO03** e **EF07CO01**, pois a tarefa envolve elaboração de algoritmo com instruções sequenciais, repetição e seleção, descrição precisa da solução em programa executável e uso de matrizes unidimensionais para representar informações em linguagem de programação.

### 4.2 Especificações de Competências

## CT16.7.1

**Título da Competência**  
Traduzir problemas simples em algoritmos claros por decomposição e abstração

**Descrição Textual**  
Organizar problemas introdutórios de programação em etapas lógicas bem definidas, identificando dados de entrada, estruturas de processamento, regras de comparação e resultados esperados, de modo a construir uma solução algorítmica clara, verificável e reutilizável.

**Cobertura e rastreabilidade**
1. **LOs cobertos:** LO1, LO4
2. **K mobilizados (Núcleo):** K05, K07, K08
3. **K mobilizados (Apoio):** K04, K02

**Especificação de Conhecimentos**
1. **K05:** sustenta a organização do fluxo do algoritmo em etapas sucessivas e observáveis. A evidência aparece na ordenação correta entre leitura, processamento e saída.
2. **K07:** sustenta a estruturação do processamento iterativo necessário para comparar respostas ao gabarito. A evidência aparece no uso coerente de laços.
3. **K08:** sustenta a modelagem do problema por meio de vetores indexados. A evidência aparece na representação do gabarito e das respostas como coleções homogêneas.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio em **Analisar**, pois a competência exige decompor o problema, relacionar suas partes e estruturar a solução antes da implementação detalhada.

**Pareamento Conhecimento–Habilidade**

K05 / Analisar → estruturar o fluxo geral do algoritmo em etapas coerentes de leitura, processamento e saída.  
Verbos de Bloom: decompor, estruturar, relacionar

K07 / Analisar → identificar onde e por que o problema exige repetição controlada ao longo do processamento.  
Verbos de Bloom: analisar, distinguir, estruturar

K08 / Analisar → modelar os dados do problema como vetores homogêneos e relacionar essa escolha à natureza das informações tratadas.  
Verbos de Bloom: modelar, relacionar, categorizar

K04 / Analisar → identificar as condições lógicas que controlam a comparação entre respostas e o destaque do resultado máximo.  
Verbos de Bloom: examinar, distinguir, relacionar

K02 / Analisar → selecionar variáveis compatíveis com índices, identificação do apostador e contagem de acertos.  
Verbos de Bloom: categorizar, estruturar, examinar


**Especificação de Disposições**  
clareza lógica  
precisão na interpretação do enunciado  
organização do raciocínio

**Competências Alinhadas à BNCC**  
EF06CO02  
EF06CO03

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.7.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza lógica, precisão na interpretação, organização do raciocínio | K05 | estruturar o fluxo geral do algoritmo |
| CT16.7.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza lógica, precisão na interpretação, organização do raciocínio | K07 | identificar o papel da repetição controlada |
| CT16.7.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza lógica, precisão na interpretação, organização do raciocínio | K08 | modelar os dados como vetores homogêneos |
| CT16.7.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza lógica, precisão na interpretação, organização do raciocínio | K04 | identificar as condições lógicas relevantes |
| CT16.7.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza lógica, precisão na interpretação, organização do raciocínio | K02 | selecionar variáveis coerentes com o problema |

**Definição de Ativação**
1. **Restrição de ativação:** obrigatória
2. **Modo de ativação:** analítica
3. **Função de ativação:** núcleo
4. **Justificativa:** a tarefa exige que o estudante compreenda a estrutura do problema antes de programar. A decomposição em etapas é condição para que a solução resulte em um algoritmo claro e funcional.

## CT16.7.2

**Título da Competência**  
Realizar entrada e saída de dados com formatação apropriada

**Descrição Textual**  
Ler dados de entrada e produzir saídas em linguagem C com ordem, consistência e formatação compatíveis com o problema, preservando a correspondência entre as informações processadas e os resultados exibidos.

**Cobertura e rastreabilidade**
1. **LOs cobertos:** LO2, LO4
2. **K mobilizados (Núcleo):** K05, K02
3. **K mobilizados (Apoio):** K07, K08, K06

**Especificação de Conhecimentos**
1. **K05:** sustenta o encadeamento correto entre leitura dos dados e exibição do resultado. A evidência aparece na organização verificável da entrada e da saída.
2. **K02:** sustenta o uso coerente de variáveis para armazenar cartão, respostas e total de acertos. A evidência aparece na consistência dos valores manipulados e exibidos.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio em **Aplicar**, pois a competência se manifesta na implementação correta da leitura e da escrita de dados em um programa executável.

**Pareamento Conhecimento–Habilidade**

K05 / Aplicar → organizar a leitura do gabarito, das respostas e a exibição dos resultados de modo verificável.  
Verbos de Bloom: organizar, executar, apresentar

K02 / Aplicar → utilizar variáveis coerentes para armazenar dados lidos e valores a serem exibidos.  
Verbos de Bloom: usar, implementar, operar

K07 / Aplicar → manter a leitura e a escrita consistentes ao longo do processamento iterativo.  
Verbos de Bloom: iterar, realizar, executar

K08 / Aplicar → acessar corretamente os elementos dos vetores durante a leitura e o processamento dos dados.  
Verbos de Bloom: manipular, implementar, operar

K06 / Aplicar → acionar a emissão da mensagem especial quando a condição de vencedor for satisfeita.  
Verbos de Bloom: aplicar, executar, resolver


**Especificação de Disposições**  
rigor no formato de saída  
atencão à ordem dos dados  
consistência operacional

**Competências Alinhadas à BNCC**  
EF06CO03

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.7.2 | Realizar entrada e saída de dados com formatação apropriada | rigor no formato, atenção à ordem, consistência operacional | K05 | organizar leitura e exibição dos dados |
| CT16.7.2 | Realizar entrada e saída de dados com formatação apropriada | rigor no formato, atenção à ordem, consistência operacional | K02 | utilizar variáveis coerentes |
| CT16.7.2 | Realizar entrada e saída de dados com formatação apropriada | rigor no formato, atenção à ordem, consistência operacional | K07 | manter consistência no processamento iterativo |
| CT16.7.2 | Realizar entrada e saída de dados com formatação apropriada | rigor no formato, atenção à ordem, consistência operacional | K08 | acessar corretamente os elementos dos vetores |
| CT16.7.2 | Realizar entrada e saída de dados com formatação apropriada | rigor no formato, atenção à ordem, consistência operacional | K06 | emitir a mensagem especial sob condição explícita |

**Definição de Ativação**
1. **Restrição de ativação:** obrigatória
2. **Modo de ativação:** construtiva
3. **Função de ativação:** núcleo
4. **Justificativa:** a tarefa é avaliada por correção automática e, portanto, depende de entrada e saída rigorosamente compatíveis com o enunciado. Sem essa competência, a solução pode estar logicamente próxima do correto, mas falhar na submissão.

## CT16.7.3

**Título da Competência**  
Representar e processar coleções homogêneas com vetores

**Descrição Textual**  
Modelar dados homogêneos em vetores, percorrê-los por índice e processá-los por comparação posicional, produzindo resultados quantitativos consistentes a partir do relacionamento entre duas sequências de mesmo tamanho.

**Cobertura e rastreabilidade**
1. **LOs cobertos:** LO3, LO4
2. **K mobilizados (Núcleo):** K08, K07, K04

**Especificação de Conhecimentos**
1. **K08:** sustenta a representação do gabarito e das respostas como vetores unidimensionais. A evidência aparece no acesso posicional e no tratamento coerente das 13 posições.
2. **K07:** sustenta o percorrimento integral dos vetores e a atualização do processamento a cada iteração. A evidência aparece na varredura completa das posições.
3. **K04:** sustenta a comparação entre elementos correspondentes e a decisão sobre ocorrência de acerto. A evidência aparece na verificação lógica entre gabarito e resposta.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio em **Aplicar**, pois a competência é evidenciada na implementação direta do processamento de vetores para resolver o problema proposto.

**Pareamento Conhecimento–Habilidade**

K08 / Aplicar → representar gabarito e respostas em vetores e acessar corretamente cada posição durante o processamento.  
Verbos de Bloom: manipular, implementar, usar

K07 / Aplicar → percorrer vetores com laços controlados, cobrindo todas as posições relevantes do problema.  
Verbos de Bloom: iterar, executar, operar

K04 / Aplicar → comparar elementos correspondentes e decidir quando uma posição configura acerto.  
Verbos de Bloom: aplicar, resolver, usar

**Especificação de Disposições**  
atenção aos índices  
consistência lógica  
precisão no processamento dos dados

**Competências Alinhadas à BNCC**  
EF06CO02  
EF07CO01

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.7.3 | Representar e processar coleções homogêneas com vetores | atenção aos índices, consistência lógica, precisão no processamento | K08 | representar gabarito e respostas em vetores |
| CT16.7.3 | Representar e processar coleções homogêneas com vetores | atenção aos índices, consistência lógica, precisão no processamento | K07 | percorrer vetores com laços controlados |
| CT16.7.3 | Representar e processar coleções homogêneas com vetores | atenção aos índices, consistência lógica, precisão no processamento | K04 | comparar elementos correspondentes |


**Definição de Ativação**
1. **Restrição de ativação:** obrigatória
2. **Modo de ativação:** construtiva
3. **Função de ativação:** núcleo
4. **Justificativa:** esta é a competência mais diretamente evidenciada pela tarefa, pois o núcleo do problema consiste em representar dados em vetores, percorrê-los e comparar suas posições para gerar a pontuação do apostador.

