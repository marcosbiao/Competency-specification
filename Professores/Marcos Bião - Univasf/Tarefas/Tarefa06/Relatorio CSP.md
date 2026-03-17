# RELATÓRIO CSP — Autoria de Competências

## Introdução

Este relatório situa a **TASK06** na fase de **Autoria de Competências** do Competency Specification Process, com foco na explicitação dos conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa de análise de código em programação introdutória.

A tarefa solicita que o estudante examine um trecho com **estruturas de repetição aninhadas**, acompanhe a atualização de uma variável acumuladora e determine a saída exibida ao final da execução, apresentando também uma justificativa breve. Trata-se, portanto, de uma entidade instrucional que produz evidências observáveis de interpretação do fluxo, rastreio de estado e explicação técnica do comportamento do programa.

A atividade sustenta o modelo **Conhecimento–Habilidade–Disposição** porque mobiliza conhecimentos conceituais da disciplina, exige habilidades analíticas e justificatórias verificáveis e demanda disposições compatíveis com o trabalho em programação, como precisão, atenção ao detalhe e rigor no registro da resposta. A especificação foi construída com controle de granularidade, sem redundância e com foco em reuso dentro da disciplina.

---

## 1. Análise da Entidade Instrucional

### Título

**TASK06 — Análise de Saída em Estruturas de Repetição Aninhadas**

### Descrição

Atividade de leitura e interpretação de um trecho de código já fornecido, centrada na previsão da saída produzida ao final da execução. O estudante não precisa implementar uma solução nova, mas deve analisar o comportamento do programa a partir da interação entre laços aninhados, atualização de variável e comando de saída.

### Processo de Desenvolvimento da Solução (em etapas)

1. Identificar as variáveis relevantes para a análise do comportamento do trecho.
2. Reconhecer a organização do fluxo de controle, com destaque para os laços aninhados.
3. Acompanhar a evolução do estado da variável que sofre atualização repetida.
4. Relacionar a quantidade de execuções do comando interno ao resultado final exibido.
5. Registrar a resposta final com justificativa breve, tecnicamente consistente e verificável.

### Resultados Esperados

1. Indicação do valor final exibido pelo programa.
2. Justificativa breve baseada no comportamento das repetições e na atualização da variável.
3. Coerência entre a resposta apresentada e a explicação registrada.
4. Evidência de leitura correta do fluxo iterativo e da saída produzida.

### Contexto de Aquisição

1. **Curso:** Ciência da Computação.
2. **Componente curricular:** Introdução à Programação.
3. **Organização:** atividade individual.
4. **Ambiente:** sala de aula, lista de exercícios ou avaliação escrita/prática guiada.
5. **Forma de avaliação:** análise de resposta final com justificativa curta e verificável.

### Perfil do Público-Alvo

1. Estudantes de início de curso, em etapa introdutória de aprendizagem de programação imperativa.
2. Público com contato inicial com variáveis, fluxo sequencial e estruturas de repetição.
3. Necessita consolidar a leitura operacional de trechos de código antes de avançar para implementação de soluções mais extensas.
4. Requer apoio na articulação entre rastreio de execução e explicação técnica do resultado.

### Nível de Proficiência (critérios e dimensões)

| Nível | Interpretação do fluxo | Rastreio do estado | Justificativa técnica | Verificabilidade da resposta |
|---|---|---|---|---|
| **N1 - Inicial** | Reconhece que há repetição no trecho, mas interpreta de forma parcial a organização do fluxo. | Identifica a variável principal, porém acompanha sua evolução com imprecisão ou lacunas. | Apresenta justificativa breve, ainda genérica ou pouco articulada ao comportamento do programa. | Registra uma resposta com baixa sustentação analítica, dificultando a conferência do raciocínio. |
| **N2 - Intermediário** | Identifica corretamente a presença de laços aninhados e compreende, em termos gerais, seu funcionamento. | Acompanha a atualização da variável com razoável consistência, embora possa cometer pequenas falhas de rastreio. | Produz justificativa coerente, mas ainda com detalhamento técnico limitado. | A resposta é verificável em parte, com evidências suficientes para compreender o raciocínio geral. |
| **N3 - Proficiente** | Interpreta corretamente a estrutura do fluxo, distinguindo o papel do laço externo e do laço interno. | Rastreia de forma consistente a evolução da variável ao longo da execução. | Justifica a resposta com clareza, articulando repetição, atualização de estado e saída final. | A resposta é plenamente verificável e coerente com o comportamento do programa. |
| **N4 - Avançado** | Analisa o fluxo com precisão e demonstra domínio da lógica iterativa presente no trecho. | Explicita com rigor a progressão do estado e sua relação com o resultado final. | Apresenta justificativa sintética, precisa e tecnicamente bem fundamentada. | A resposta é altamente verificável, clara e sustentada por argumentação consistente e objetiva. |

## 2. Seleção e Enumeração de Conhecimentos

### **K01 — Modelo de execução e noção de estado (paradigma imperativo)**

1. Compreensão de que o programa evolui por mudanças sucessivas de estado.
2. Interpretação de atribuições e atualizações como transições observáveis durante a execução.
3. Leitura operacional da sequência de comandos e do fluxo de controle.

**Justificativa de mobilização na tarefa:**  
A tarefa exige acompanhar como o estado da variável acumuladora se modifica ao longo da execução e como essas mudanças sustentam a resposta final.

### **K02 — Variáveis, constantes e tipos primitivos**

1. Identificação de variáveis como elementos que armazenam e atualizam valores.
2. Compreensão do papel funcional de identificadores em contextos introdutórios.
3. Relação entre variável de controle, variável acumuladora e resultado produzido.

**Justificativa de mobilização na tarefa:**  
O estudante precisa distinguir o papel da variável que acumula resultado e das variáveis associadas ao controle das repetições.

### **K03 — Expressões aritméticas e avaliação**

1. Compreensão de atualizações aritméticas elementares aplicadas por atribuição.
2. Interpretação do efeito cumulativo de operações simples repetidas.
3. Relação entre operação local e resultado global após várias execuções.

**Justificativa de mobilização na tarefa:**  
O comportamento do programa depende de uma atualização aritmética recorrente, cujo efeito total precisa ser interpretado corretamente.

### **K05 — Estrutura sequencial e E/S básica**

1. Organização do programa como sequência de comandos articulados.
2. Relação entre processamento realizado e saída observável.
3. Leitura do comando de saída como evidência do estado final do programa.

**Justificativa de mobilização na tarefa:**  
A resposta depende da correta interpretação do que é exibido ao final da sequência de processamento.

### **K07 — Estruturas de repetição**

1. Compreensão de laços por contagem e de sua função no controle da execução.
2. Leitura de repetição aninhada como composição de ciclos iterativos.
3. Relação entre número de iterações e processamento acumulativo.

**Justificativa de mobilização na tarefa:**  
Este é o conhecimento central da atividade, pois a saída final decorre diretamente da interação entre dois laços por contagem.


## 3. Identificação de Objetivos de Aprendizagem

### **LO1**
Identificar o papel funcional das variáveis e da saída em um trecho de programa com repetição por contagem.

**K associados:** (K01, K02, K05)

### **LO2**
Rastrear a evolução do estado de uma variável ao longo da execução de estruturas de repetição.

**K associados:** (K01, K07)

### **LO3**
Analisar o efeito combinado de laços aninhados sobre a quantidade de atualizações realizadas em uma variável.

**K associados:** (K01, K03, K07)

### **LO4**
Justificar tecnicamente um resultado de execução, articulando fluxo iterativo, atualização de variável e saída exibida.

**K associados:** (K01, K05, K07, K03)

---

## 4. Definição de Competências

### 4.1 Competência Geral 
**Competência geral do domínio de Computação:**  
Interpretar e explicar o comportamento de programas imperativos introdutórios, relacionando estado, fluxo de repetição, atualização de variáveis e resultado produzido.

**Observação sobre BNCC:**  
Não aplicável neste relatório, por se tratar de contexto de ensino superior em disciplina de Introdução à Programação.

### 4.2 Especificações de Competências

#### CT06.1

**Título da Competência**  
Controlar o fluxo com repetição, interpretando contadores, acumuladores e limites de iteração

**Descrição Textual**  
Capacidade de analisar trechos de programas com estruturas de repetição, reconhecendo o papel de contadores, acumuladores e limites de iteração na determinação do comportamento do fluxo e do resultado produzido.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO2, LO3)
2. K mobilizados (Núcleo): (K07, K01, K03)

**Especificação de Conhecimentos**

**K07 — Estruturas de repetição**  
Descrição curta: compreensão de laços por contagem e da composição de repetições aninhadas.  
Justificativa de evidência: a tarefa exige interpretar diretamente o funcionamento de dois laços encadeados e seu efeito no processamento.

**K01 — Modelo de execução e noção de estado (paradigma imperativo)**  
Descrição curta: leitura do programa como sequência de mudanças de estado ao longo da execução.  
Justificativa de evidência: o estudante precisa acompanhar como o estado da variável se modifica a cada iteração.

**K03 — Expressões aritméticas e avaliação**  
Descrição curta: interpretação do efeito cumulativo de atualizações aritméticas simples.  
Justificativa de evidência: a saída final depende da atualização repetida da variável acumuladora.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predominância de **Analisar**, pois a competência exige decompor o fluxo iterativo e relacioná-lo ao efeito acumulado da execução.

**Pareamento Conhecimento–Habilidade**

K07 / Analisar → decompor o comportamento de estruturas de repetição por contagem, distinguindo o papel de laços externos e internos.  
Verbos de Bloom: decompor, discriminar, estruturar

K01 / Analisar → rastrear as mudanças de estado produzidas sucessivamente durante a execução iterativa do programa.  
Verbos de Bloom: rastrear, relacionar, examinar

K03 / Analisar → relacionar atualizações aritméticas sucessivas ao valor acumulado ao longo das iterações.  
Verbos de Bloom: relacionar, examinar, atualizar


**Especificação de Disposições**  
1. Atenção ao detalhe na leitura do fluxo iterativo.  
2. Precisão no acompanhamento das mudanças de estado.  
3. Rigor lógico na interpretação do efeito das repetições.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT06.1 | Controlar o fluxo com repetição, interpretando contadores, acumuladores e limites de iteração | Atenção ao detalhe; precisão; rigor lógico | K07 | Decompor o comportamento de estruturas de repetição por contagem |
| CT06.1 | Controlar o fluxo com repetição, interpretando contadores, acumuladores e limites de iteração | Atenção ao detalhe; precisão; rigor lógico | K01 | Rastrear as mudanças de estado durante a execução iterativa |
| CT06.1 | Controlar o fluxo com repetição, interpretando contadores, acumuladores e limites de iteração | Atenção ao detalhe; precisão; rigor lógico | K03 | Relacionar atualizações sucessivas ao valor acumulado |


**Definição de Ativação**
1. Restrição de ativação: obrigatória  
2. Modo de ativação: analítica  
3. Função de ativação: núcleo  
4. Justificativa curta baseada na tarefa: a tarefa é centrada na interpretação de laços aninhados e no efeito de contadores e acumuladores sobre a saída. Sem essa ativação analítica, não é possível sustentar a resposta de forma consistente.


#### CT06.2

**Título da Competência**  
Manipular dados com variáveis e expressões simples para analisar o estado do programa

**Descrição Textual**  
Capacidade de interpretar o papel de variáveis em programas introdutórios e de relacionar expressões simples às mudanças de estado observadas durante a execução.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO2)
2. K mobilizados (Núcleo): (K02, K03, K01)

**Especificação de Conhecimentos**

**K02 — Variáveis, constantes e tipos primitivos**  
Descrição curta: identificação de variáveis como elementos que armazenam, controlam e acumulam valores.  
Justificativa de evidência: a tarefa exige distinguir variáveis de controle e variável acumuladora para interpretar corretamente o trecho.

**K03 — Expressões aritméticas e avaliação**  
Descrição curta: compreensão do efeito de operações aritméticas elementares aplicadas por atualização.  
Justificativa de evidência: o programa depende de uma atualização simples cujo efeito precisa ser interpretado no contexto iterativo.

**K01 — Modelo de execução e noção de estado (paradigma imperativo)**  
Descrição curta: relação entre execução de comandos e transformação do estado do programa.  
Justificativa de evidência: a análise do trecho requer acompanhar a evolução do valor armazenado ao longo da execução.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predominância de **Aplicar**, com apoio de **Analisar**, pois a competência mobiliza o uso interpretativo de variáveis e expressões simples para explicar o estado do programa.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → identificar e utilizar o papel funcional de variáveis de controle e de acumulação na interpretação de trechos de programa.  
Verbos de Bloom: identificar, selecionar, representar

K03 / Aplicar → operar com atualizações aritméticas simples para explicar a evolução do valor armazenado em uma variável.  
Verbos de Bloom: operar, usar, calcular

K01 / Analisar → explicitar o estado do programa a partir da sequência de execuções que afetam a variável observada.  
Verbos de Bloom: explicitar, examinar, relacionar


**Especificação de Disposições**  
1. Cuidado na leitura dos identificadores e de suas funções.  
2. Consistência na interpretação do valor armazenado ao longo da execução.  
3. Objetividade na relação entre atualização local e resultado global.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT06.2 | Manipular dados com variáveis e expressões simples para analisar o estado do programa | Cuidado; consistência; objetividade | K02 | Identificar e utilizar o papel funcional de variáveis de controle e de acumulação |
| CT06.2 | Manipular dados com variáveis e expressões simples para analisar o estado do programa | Cuidado; consistência; objetividade | K03 | Operar com atualizações aritméticas simples para explicar a evolução do valor |
| CT06.2 | Manipular dados com variáveis e expressões simples para analisar o estado do programa | Cuidado; consistência; objetividade | K01 | Explicitar o estado do programa a partir da sequência de execuções |


**Definição de Ativação**
1. Restrição de ativação: obrigatória  
2. Modo de ativação: analítica  
3. Função de ativação: núcleo  
4. Justificativa curta baseada na tarefa: embora o foco principal esteja nas repetições, a resposta depende também da leitura correta das variáveis e da atualização simples que altera seu valor. Essa competência sustenta a interpretação do estado do programa.

---

#### CT06.3

**Título da Competência**  
Comunicar o resultado da análise de execução com justificativa técnica breve e verificável

**Descrição Textual**  
Capacidade de registrar o resultado de análise de um trecho de programa de forma clara, objetiva e tecnicamente verificável, articulando fluxo, estado e saída observada.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO4)
2. K mobilizados (Núcleo): (K05, K01, K07)

**Especificação de Conhecimentos**

**K05 — Estrutura sequencial e E/S básica**  
Descrição curta: compreensão da relação entre processamento executado e saída apresentada.  
Justificativa de evidência: a atividade solicita explicitamente o valor exibido ao final da execução.

**K01 — Modelo de execução e noção de estado (paradigma imperativo)**  
Descrição curta: explicação do estado final alcançado após a sequência de comandos.  
Justificativa de evidência: a justificativa precisa relacionar a resposta final à evolução do estado do programa.

**K07 — Estruturas de repetição**  
Descrição curta: interpretação do papel da repetição no resultado final comunicado.  
Justificativa de evidência: a justificativa técnica precisa mencionar como o fluxo iterativo interfere na saída.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predominância de **Avaliar**, pois a competência exige validar a resposta registrada com base em evidências extraídas da execução do programa.

**Pareamento Conhecimento–Habilidade**

K05 / Avaliar → validar a coerência entre o processamento descrito e a saída registrada como resposta final.  
Verbos de Bloom: validar, verificar, justificar

K01 / Avaliar → argumentar sobre a consistência do estado final do programa a partir da sequência de execuções observada.  
Verbos de Bloom: argumentar, justificar, verificar

K07 / Analisar → relacionar o comportamento das repetições ao resultado que precisa ser comunicado.  
Verbos de Bloom: relacionar, estruturar, rastrear


**Especificação de Disposições**  
1. Clareza na comunicação técnica.  
2. Compromisso com a verificabilidade da resposta.  
3. Síntese argumentativa sem perda de rigor.  
4. Consistência entre resultado e justificativa.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT06.3 | Comunicar o resultado da análise de execução com justificativa técnica breve e verificável | Clareza; verificabilidade; síntese argumentativa; consistência | K05 | Validar a coerência entre processamento e saída final |
| CT06.3 | Comunicar o resultado da análise de execução com justificativa técnica breve e verificável | Clareza; verificabilidade; síntese argumentativa; consistência | K01 | Argumentar sobre a consistência do estado final do programa |
| CT06.3 | Comunicar o resultado da análise de execução com justificativa técnica breve e verificável | Clareza; verificabilidade; síntese argumentativa; consistência | K07 | Relacionar o comportamento das repetições ao resultado comunicado |


**Definição de Ativação**
1. Restrição de ativação: obrigatória  
2. Modo de ativação: justificatória  
3. Função de ativação: núcleo  
4. Justificativa curta baseada na tarefa: a entidade instrucional não exige apenas indicar uma resposta, mas registrar uma justificativa breve e coerente. Essa competência torna a evidência observável, comunicável e avaliável de forma técnica.