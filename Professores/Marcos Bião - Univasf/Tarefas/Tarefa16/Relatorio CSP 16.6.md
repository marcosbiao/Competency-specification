# RELATÓRIO CSP — TASK16.6


## Introdução

Este relatório situa a TASK16.6 na fase de **Autoria de Competências** do CSP. A tarefa solicita a leitura de uma matriz bidimensional, a exibição de seu estado inicial, a identificação do menor elemento, a transformação dos dados por divisão escalar e a reapresentação da matriz resultante. Trata-se de uma tarefa com evidências observáveis no código e na saída produzida, pois o estudante precisa articular entrada, processamento e saída de forma coerente.

A tarefa suporta o modelo **Conhecimento–Habilidade–Disposição (K–S–D)** porque mobiliza conhecimentos de representação de dados, controle de fluxo, expressões, processamento de coleções homogêneas e comunicação de resultados computacionais. O relatório busca manter alta rastreabilidade, reuso das competências e controle de granularidade.

## 1. Análise da Entidade Instrucional

### Título

**Divisão de uma matriz pelo menor elemento**

### Descrição

A tarefa requer a implementação de um programa em C que leia uma matriz `5x7`, exiba seus elementos, identifique o menor valor armazenado, divida todos os elementos da matriz por esse valor e exiba a matriz atualizada. O problema insere-se no conjunto de questões da maratona prática da disciplina, com foco em correção funcional, consistência entre entrada, processamento e saída e aderência estrita ao enunciado.

### Processo de Desenvolvimento da Solução

1. Organizar uma solução que articule representação bidimensional, análise de valores e transformação de dados.
2. Mobilizar percorrimento sistemático da estrutura para garantir cobertura integral da matriz.
3. Relacionar leitura, processamento e saída de modo coerente com o enunciado.
4. Empregar comparação e atualização de estado em contexto de processamento matricial.
5. Preservar consistência entre a estrutura de dados utilizada, a operação realizada e a reapresentação dos resultados.

### Resultados Esperados

1. Solução em C sintaticamente válida e aderente ao problema proposto.
2. Manipulação consistente de dados organizados em matriz bidimensional.
3. Uso correto de percorrimento, comparação e atualização sobre coleção homogênea.
4. Coerência entre estado inicial dos dados, processamento realizado e estado final produzido.
5. Saída clara, verificável e compatível com o contexto de correção automática.
6. Evidências suficientes para avaliação do desempenho do estudante na tarefa.

### Contexto de Aquisição

A tarefa é desenvolvida em disciplina introdutória de programação, em ambiente de laboratório, com tempo restrito, consulta apenas a material impresso e validação por juiz automático. Esse contexto valoriza precisão de implementação, clareza algorítmica, consistência de saída e aderência estrita ao problema proposto.

### Perfil do Público-Alvo

**Público:** estudantes de graduação em fase inicial de formação em programação.  
**Pré-requisitos:** variáveis, tipos primitivos, expressões, estruturas de seleção, estruturas de repetição, entrada e saída de dados e noções de vetores e matrizes em C.  
**Necessidades formativas:** consolidar a passagem do enunciado para o algoritmo, fortalecer o processamento de coleções homogêneas e manter coerência entre leitura, transformação e exibição dos dados.

### Nível de Proficiência

| Nível | Tradução do problema em algoritmo | Entrada e saída de dados | Representação e processamento da matriz |
|---|---|---|---|
| **N1 - Inicial** | Identifica apenas parte das exigências do problema ou organiza a solução de forma incompleta. | Lê ou exibe dados com inconsistências observáveis. | Declara ou percorre a matriz com erros de indexação ou cobertura. |
| **N2 - Intermediário** | Estrutura as etapas principais, mas ainda com fragilidades na decomposição do problema. | Realiza leitura e exibição com pequenas falhas de organização ou formatação. | Representa e percorre a matriz com pequenas inconsistências. |
| **N3 - Proficiente** | Traduz o enunciado em um algoritmo claro, completo e coerente. | Realiza entrada e saída de forma correta e verificável. | Representa, percorre, analisa e transforma a matriz corretamente. |
| **N4 - Avançado** | Além de correto, organiza a solução com alta clareza, economia e rastreabilidade. | Produz entrada e saída corretas, legíveis e bem organizadas para validação. | Executa o processamento com precisão, estabilidade e boa organização do código. |

## 2. Seleção e Enumeração de Conhecimentos

### K01 — Modelo de execução e noção de estado

1. Compreende que o programa evolui por mudanças sucessivas de estado.
2. Permite distinguir a matriz antes e depois do processamento.
3. Sustenta a atualização de variáveis auxiliares e da própria matriz.

**Justificativa de mobilização:** a tarefa exige acompanhar o estado inicial da matriz, o estado intermediário da busca do menor valor e o estado final após a transformação.

### K02 — Variáveis, constantes e tipos primitivos

1. Abrange declaração e uso de variáveis escalares e escolha coerente de tipos.
2. Sustenta o armazenamento do menor elemento e o controle dos percorrimentos.
3. Apoia a representação numérica necessária à divisão escalar.

**Justificativa de mobilização:** a tarefa requer variáveis compatíveis com os dados lidos e com o processamento numérico realizado.

### K03 — Expressões aritméticas e avaliação

1. Envolve construção e avaliação de expressões numéricas.
2. Sustenta a divisão de cada elemento da matriz por um valor de referência.
3. Requer coerência no cálculo e na atualização dos elementos.

**Justificativa de mobilização:** a transformação central do problema é aritmética e depende de avaliação correta de expressões.

### K04 — Expressões lógicas e condições

1. Abrange comparações entre valores e construção de condições booleanas.
2. Sustenta a identificação do menor elemento da matriz.
3. Relaciona-se à decisão de atualizar a referência do mínimo.

**Justificativa de mobilização:** a busca pelo menor elemento depende de comparação lógica consistente.

### K05 — Estrutura sequencial e E/S básica

1. Organiza o fluxo entrada → processamento → saída.
2. Sustenta a leitura dos dados e as duas exibições solicitadas.
3. Requer consistência entre o que é lido, processado e apresentado.

**Justificativa de mobilização:** a tarefa depende de um encadeamento correto entre leitura da matriz, processamento e reapresentação dos resultados.

### K06 — Estruturas de seleção

1. Permite escolher quando atualizar a variável que registra o menor valor.
2. Materializa decisões condicionais no algoritmo.
3. Relaciona-se ao uso apropriado de `if` durante a varredura da matriz.

**Justificativa de mobilização:** a identificação do menor elemento exige seleção condicional baseada em comparação.

### K07 — Estruturas de repetição

1. Sustenta a leitura integral da matriz.
2. Viabiliza a busca do menor elemento e a atualização de todos os valores.
3. Permite percorrimento controlado de linhas e colunas.

**Justificativa de mobilização:** a tarefa só se completa por repetição estruturada sobre todos os elementos da matriz.

### K08 — Vetores e matrizes em C

1. Abrange representação, acesso indexado, leitura, atualização e processamento de matrizes bidimensionais.
2. Sustenta a organização dos dados como coleção homogênea bidimensional.
3. Permite percorrimento e transformação da estrutura.

**Justificativa de mobilização:** o objeto central da tarefa é uma matriz `5x7`, que deve ser lida, analisada, transformada e exibida.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Traduzir enunciados de processamento matricial em algoritmos claros, decompondo o problema em etapas coerentes de leitura, análise, transformação e exibição.  
**K associados:** K01, K05, K07, K08

### LO2

Realizar entrada e saída de dados de uma matriz bidimensional de forma consistente, com organização compatível com a verificação do problema.  
**K associados:** K02, K05, K07, K08

### LO3

Representar e percorrer coleções homogêneas em duas dimensões para localizar informações relevantes e aplicar transformações aos seus elementos.  
**K associados:** K03, K04, K06, K07, K08

### LO4

Aplicar operações aritméticas e condicionais sobre dados matriciais, preservando coerência entre o estado inicial e o estado final da estrutura.  
**K associados:** K01, K02, K03, K04, K06, K08

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver soluções em programação que representem, organizem e processem dados estruturados, articulando decomposição do problema, controle de fluxo e consistência entre entrada, processamento e saída.

### 4.2 Especificações de Competências

## CT16.6.1

**Título da Competência**  
Traduzir problemas simples em algoritmos claros por decomposição e abstração

**Descrição Textual**  
Converter enunciados introdutórios de programação em sequências algorítmicas coerentes, decompondo o problema em etapas e abstraindo operações essenciais para produzir uma solução executável e verificável.

**LOs cobertos:** LO1, LO4  
**Conhecimentos mobilizados:** K01, K04, K05, K06, K07, K08

**Pareamento Conhecimento–Habilidade**

1. **K01 / Analisar / decompor** → distinguir estados relevantes do programa ao longo da solução.
2. **K05 / Aplicar / organizar** → estruturar a sequência de leitura, processamento e saída.
3. **K07 / Aplicar / implementar** → distribuir as etapas da solução em percorrimentos coerentes.
4. **K08 / Aplicar / representar** → modelar o problema por meio de uma matriz bidimensional.

**Disposições**

1. Clareza na organização da solução.
2. Rigor na interpretação do enunciado.
3. Atenção à completude do algoritmo.

**Definição de Ativação**  
**Restrição de ativação:** obrigatória  
**Modo de ativação:** construtiva  
**Função de ativação:** núcleo  
**Justificativa:** a tarefa exige decompor o problema em etapas articuladas e produzir um algoritmo completo. Sem essa ativação, não há solução coerente para leitura, análise e transformação da matriz.

**Tabela-resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.6.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza, rigor, completude | K01 | distinguir estados relevantes do programa |
| CT16.6.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza, rigor, completude | K05 | estruturar a sequência de leitura, processamento e saída |
| CT16.6.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza, rigor, completude | K07 | distribuir as etapas da solução em percorrimentos coerentes |
| CT16.6.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza, rigor, completude | K08 | modelar o problema por meio de matriz bidimensional |

## CT16.6.2

**Título da Competência**  
Realizar entrada e saída de dados com validação mínima e formatação apropriada

**Descrição Textual**  
Ler e apresentar dados em programas introdutórios, mantendo consistência entre o formato esperado pelo problema, a organização interna dos dados e a exibição dos resultados produzidos.

**LOs cobertos:** LO2  
**Conhecimentos mobilizados:** K02, K05, K07, K08

**Pareamento Conhecimento–Habilidade**

1. **K02 / Aplicar / usar** → declarar variáveis e tipos coerentes com a leitura e a exibição dos dados.
2. **K05 / Aplicar / apresentar** → organizar entrada e saída em fluxo verificável.
3. **K07 / Aplicar / iterar** → percorrer integralmente a matriz para leitura e exibição.
4. **K08 / Aplicar / manipular** → acessar corretamente os elementos da coleção homogênea bidimensional.

**Disposições**

1. Precisão na leitura dos dados.
2. Atenção ao formato da saída.
3. Compromisso com a verificabilidade do resultado.

**Definição de Ativação**  
**Restrição de ativação:** obrigatória  
**Modo de ativação:** construtiva  
**Função de ativação:** núcleo  
**Justificativa:** a tarefa exige ler uma matriz completa e exibi-la em dois momentos distintos. A evidência da competência aparece diretamente na consistência entre dados recebidos, organização da estrutura e saída apresentada.

**Tabela-resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.6.2 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | precisão, atenção ao formato, verificabilidade | K02 | declarar variáveis e tipos coerentes |
| CT16.6.2 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | precisão, atenção ao formato, verificabilidade | K05 | organizar entrada e saída em fluxo verificável |
| CT16.6.2 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | precisão, atenção ao formato, verificabilidade | K07 | percorrer integralmente a matriz para leitura e exibição |
| CT16.6.2 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | precisão, atenção ao formato, verificabilidade | K08 | acessar corretamente os elementos da matriz |

## CT16.6.3

**Título da Competência**  
Representar e processar coleções homogêneas com vetores e matrizes

**Descrição Textual**  
Representar dados em estruturas indexadas homogêneas e processar seus elementos por percorrimento, análise e transformação, mantendo coerência entre a estrutura utilizada e o objetivo computacional da tarefa.

**LOs cobertos:** LO3, LO4  
**Conhecimentos mobilizados:** K03, K04, K06, K07, K08

**Pareamento Conhecimento–Habilidade**

1. **K03 / Aplicar / calcular** → aplicar transformação aritmética sobre todos os elementos da matriz.
2. **K04 / Analisar / distinguir** → comparar valores para identificar o menor elemento.
3. **K06 / Aplicar / decidir** → atualizar a referência do mínimo quando a condição for satisfeita.
4. **K07 / Aplicar / percorrer** → varrer integralmente a matriz para análise e transformação.
5. **K08 / Aplicar / processar** → representar e manipular a coleção homogênea bidimensional de forma correta.

**Disposições**

1. Precisão no processamento dos dados.
2. Rigor lógico na análise da matriz.
3. Atenção à consistência entre estrutura e operação aplicada.

**Definição de Ativação**  
**Restrição de ativação:** obrigatória  
**Modo de ativação:** analítica e construtiva  
**Função de ativação:** núcleo  
**Justificativa:** o núcleo da tarefa está em representar a matriz, localizar um valor relevante e transformar todos os seus elementos. A competência é diretamente evidenciada pelo uso correto da estrutura e pelo processamento integral da coleção homogênea.

**Tabela-resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.6.3 | Representar e processar coleções homogêneas com vetores e matrizes | precisão, rigor lógico, consistência | K03 | aplicar transformação aritmética aos elementos |
| CT16.6.3 | Representar e processar coleções homogêneas com vetores e matrizes | precisão, rigor lógico, consistência | K04 | comparar valores para identificar o menor elemento |
| CT16.6.3 | Representar e processar coleções homogêneas com vetores e matrizes | precisão, rigor lógico, consistência | K06 | atualizar a referência do mínimo por decisão condicional |
| CT16.6.3 | Representar e processar coleções homogêneas com vetores e matrizes | precisão, rigor lógico, consistência | K07 | varrer integralmente a matriz |
| CT16.6.3 | Representar e processar coleções homogêneas com vetores e matrizes | precisão, rigor lógico, consistência | K08 | representar e manipular a estrutura bidimensional |

