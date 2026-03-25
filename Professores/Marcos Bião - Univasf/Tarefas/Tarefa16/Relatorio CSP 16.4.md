# RELATÓRIO CSP — TASK16.4

## Introdução

Este relatório situa a tarefa 16.4 na fase de **Autoria de Competências** do Competency Specification Process. A tarefa solicita a construção de um programa em C que opere sobre um vetor de 30 posições, realizando seu preenchimento e, em seguida, a exibição dos elementos pares em ordem reversa. No contexto da atividade mais ampla, trata-se de um problema típico de programação introdutória, resolvido em ambiente de laboratório, com submissão em juiz automático, ênfase em correção funcional e consistência entre entrada, processamento e saída.

A tarefa elicita evidências observáveis porque exige um artefato executável em que se pode verificar, de forma direta, a declaração de estruturas de dados, o controle de laços, a seleção por critério aritmético e a conformidade da saída. Ela também suporta o modelo K–S–D com baixa redundância, pois mobiliza um conjunto compacto de conhecimentos centrais da disciplina e permite derivar objetivos e competências reutilizáveis em outras tarefas de vetores e processamento sequencial.

---

## 1. Análise da Entidade Instrucional

### Título

**TASK16.4 — Preenchimento e varredura reversa de vetor com filtragem de pares**

### Descrição

A tarefa propõe a implementação, em linguagem C, de uma solução que manipula um vetor de tamanho fixo, preenchendo suas posições com valores no intervalo especificado pelo enunciado e exibindo, ao final, apenas os elementos pares, de trás para frente. No contexto da maratona, trata-se de um problema de processamento de dados com forte verificabilidade por testes automáticos.

### Processo de Desenvolvimento da Solução (em etapas)

1. Interpretar o enunciado, identificando estrutura de dados, tamanho do vetor, domínio dos valores e regra de saída.
2. Declarar o vetor e as variáveis auxiliares com tipos coerentes.
3. Preencher o vetor por meio de laço controlado, mantendo consistência entre índice e valor atribuído.
4. Realizar um segundo percurso, agora em ordem reversa, cobrindo corretamente os limites do vetor.
5. Aplicar um teste de paridade para decidir quais elementos devem ser exibidos.
6. Produzir a saída final em conformidade com a ordem e o critério solicitados.

### Resultados Esperados

- Programa em C compilável e executável.
- Vetor corretamente preenchido segundo a regra implementada a partir do enunciado.
- Varredura reversa sem erro de índice.
- Exibição exclusiva dos elementos pares.
- Saída verificável e compatível com a correção automática.

### Contexto de Aquisição

- **Curso/Nível:** disciplina introdutória de programação no ensino superior.
- **Componente curricular:** Introdução à Programação.
- **Organização da atividade:** maratona prática em equipes de até três estudantes.
- **Ambiente:** laboratório, um computador por equipe, tempo limitado e sem acesso à internet.
- **Avaliação:** correção funcional, aderência ao enunciado, consistência entre processamento e saída e submissão válida em juiz automático.

### Perfil do Público-Alvo

- Estudantes iniciantes em programação imperativa.
- Com familiaridade básica com sintaxe de C, variáveis, laços e saída padrão.
- Com necessidade de consolidar indexação, percursos em vetores e controle de fluxo simples.
- Beneficiados por tarefas curtas, objetivas e verificáveis automaticamente.

### Nível de Proficiência (critérios e dimensões)

| Nível | Interpretação do enunciado | Preenchimento e indexação do vetor | Percurso reverso e filtragem | Consistência da saída |
|---|---|---|---|---|
| **N1 - Inicial** | Identifica apenas parte da solicitação e omite regra de ordem ou filtragem. | Declara ou acessa o vetor com erros de tipo ou índice. | Não realiza percurso reverso correto ou falha no teste de paridade. | A saída não corresponde ao processamento realizado. |
| **N2 - Intermediário** | Reconhece vetor, preenchimento e saída, mas com lacunas na regra de processamento. | Preenche parte do vetor corretamente, mas com inconsistências pontuais. | Realiza parte do percurso reverso ou filtra pares com erros ocasionais. | A saída se aproxima do esperado, mas apresenta falhas de ordem ou seleção. |
| **N3 - Proficiente** | Interpreta corretamente estrutura, ordem reversa e critério de paridade. | Preenche as 30 posições com controle adequado de índice e valor. | Percorre o vetor de trás para frente e exibe corretamente apenas os pares. | A saída é coerente com o processamento e com o critério solicitado. |
| **N4 - Avançado** | Além de interpretar corretamente, antecipa casos de borda e verifica coerência da implementação. | Implementa o preenchimento com regularidade, clareza e forte controle de limites. | Mantém percurso reverso, filtragem e estabilidade da lógica sem erros de fronteira. | A saída é precisa, estável e plenamente aderente ao formato e à lógica exigidos. |




## 2. Seleção e Enumeração de Conhecimentos 

### **K02 — Variáveis, constantes e tipos primitivos**
- Representação de dados simples por identificadores e tipos coerentes.
- Uso de inteiros para índices, elementos do vetor e verificações numéricas.
- Atribuição consistente durante o preenchimento e o processamento.
- **Justificativa de mobilização na tarefa:** a tarefa depende da declaração correta do vetor e das variáveis de controle, bem como da coerência de tipo em atribuições e testes.

### **K03 — Expressões aritméticas e avaliação**
- Construção de expressões para cálculo de valores e controle de iteração.
- Uso de operadores aritméticos em incrementos, decrementos e paridade.
- Avaliação correta de expressões ao longo do processamento.
- **Justificativa de mobilização na tarefa:** a identificação de números pares e o controle do percurso reverso exigem expressões aritméticas corretas.

### **K04 — Expressões lógicas e condições**
- Formulação de condições booleanas simples para tomada de decisão.
- Interpretação correta de verdade e falsidade em critérios de seleção.
- Relação entre regra do problema e condição implementada.
- **Justificativa de mobilização na tarefa:** a exibição apenas dos pares requer uma condição lógica que discrimine quais elementos serão mostrados.

### **K05 — Estrutura sequencial e E/S básica**
- Organização do programa no fluxo entrada/processamento/saída.
- Uso coerente de comandos sequenciais e saída verificável.
- Relação entre o que foi processado e o que é exibido.
- **Justificativa de mobilização na tarefa:** o resultado só é evidenciado quando a saída é produzida de forma consistente com o processamento realizado.

### **K06 — Estruturas de seleção**
- Escolha de caminhos alternativos com base em condição simples.
- Uso de `if` para discriminar casos que devem ou não gerar saída.
- Relação entre critério do problema e ramo executado.
- **Justificativa de mobilização na tarefa:** a exibição apenas dos elementos pares requer uma decisão condicional simples para cada posição examinada.

### **K07 — Estruturas de repetição**
- Emprego de laços com contagem definida.
- Controle de inicialização, atualização e parada.
- Uso de percursos progressivos e regressivos.
- **Justificativa de mobilização na tarefa:** o problema exige ao menos dois percursos controlados, um para preenchimento e outro para leitura reversa.

### **K08 — Vetores e matrizes em C**
- Representação de coleções homogêneas indexadas em C.
- Acesso posicional a elementos e controle de limites.
- Percorrimento e processamento de vetor de tamanho fixo.
- **Justificativa de mobilização na tarefa:** o núcleo do problema é a manipulação de um vetor de 30 posições, com preenchimento e consulta reversa.

## 3. Identificação de Objetivos de Aprendizagem

### LO1
**Declarar e preencher vetores de tamanho fixo com dados numéricos, mantendo coerência entre tipo, índice e valor atribuído.**  
**K associados:** K02, K05, K07, K08

### LO2
**Controlar percursos progressivos e regressivos sobre vetores, preservando os limites válidos de acesso.**  
**K associados:** K03, K07, K08

### LO3
**Aplicar critérios aritméticos simples para selecionar elementos de uma coleção durante o processamento.**  
**K associados:** K03, K04, K06, K08

### LO4
**Produzir saída verificável e aderente ao enunciado, respeitando a ordem de exibição e o subconjunto solicitado.**  
**K associados:** K05, K06, K07, K08

---

## 4. Definição de Competências

### 4.1 Competência Geral

Construir e analisar soluções computacionais para problemas de programação introdutória, representando dados em coleções, descrevendo o processo de solução com precisão e implementando algoritmos que articulem sequências, repetições e critérios de seleção.

**Alinhamento geral defensável à BNCC:** EF69CO02, EF69CO03 e EF69CO05, com continuidade vertical possível para EM13CO02.

### 4.2 Especificações de Competências

## CT16.4.1

**Título da Competência**  
Traduzir problemas simples em algoritmos claros por decomposição e abstração

**Descrição Textual**  
Traduzir o enunciado em uma sequência algorítmica clara, decompondo o problema em etapas de preenchimento do vetor, percurso reverso, teste de paridade e exibição dos resultados.

**Cobertura e rastreabilidade**
- LOs cobertos: LO2, LO3, LO4
- K mobilizados (Núcleo): K03, K04, K05, K07

**Especificação de Conhecimentos**
- **K03:** sustenta as expressões aritméticas usadas no controle do percurso e na identificação da paridade.
- **K04:** sustenta a formulação da condição que decide quais elementos devem ser exibidos.
- **K05:** sustenta a organização do fluxo da solução em etapas coerentes de processamento e saída.
- **K07:** sustenta a implementação dos laços necessários ao preenchimento e à varredura do vetor.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Nível predominante:** Aplicar

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → usar expressões aritméticas coerentes para controlar o algoritmo e testar a paridade dos elementos.  
Verbos de Bloom: calcular, operar, usar

K04 / Aplicar → formular condições simples para selecionar os valores que devem compor a saída.  
Verbos de Bloom: implementar, operar, usar

K05 / Aplicar → organizar a solução em etapas consistentes de preenchimento, percurso, filtragem e exibição.  
Verbos de Bloom: estruturar, implementar, realizar

K07 / Aplicar → implementar laços que materializem a sequência algorítmica requerida pelo problema.  
Verbos de Bloom: executar, iterar, implementar


**Especificação de Disposições**
- clareza na organização do raciocínio
- atenção à sequência lógica do algoritmo
- precisão funcional na tradução do enunciado

**Competências Alinhadas à BNCC**
- EF69CO02
- EF69CO03

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.4.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza no raciocínio; atenção à sequência; precisão funcional | K03 | usar expressões aritméticas coerentes para controlar o algoritmo e testar a paridade dos elementos |
| CT16.4.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza no raciocínio; atenção à sequência; precisão funcional | K04 | formular condições simples para selecionar os valores que devem compor a saída |
| CT16.4.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza no raciocínio; atenção à sequência; precisão funcional | K05 | organizar a solução em etapas consistentes de preenchimento, percurso, filtragem e exibição |
| CT16.4.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza no raciocínio; atenção à sequência; precisão funcional | K07 | implementar laços que materializem a sequência algorítmica requerida pelo problema |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa exige que o estudante converta um enunciado breve em uma cadeia de operações bem ordenada. A competência é ativada quando a solução evidencia decomposição em etapas e correspondência entre regra do problema e algoritmo implementado.

## CT16.4.2

**Título da Competência**  
Representar e processar coleções homogêneas com vetores

**Descrição Textual**  
Representar dados homogêneos em vetor de tamanho fixo, preencher suas posições e processar seus elementos por índice válido, incluindo percursos direto e reverso.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1, LO2, LO3
- K mobilizados (Núcleo): K02, K07, K08

**Especificação de Conhecimentos**
- **K02:** sustenta a declaração coerente do vetor e das variáveis auxiliares.
- **K07:** sustenta os percursos necessários ao preenchimento e à leitura da coleção.
- **K08:** sustenta a representação, o acesso posicional e o processamento de vetor de tamanho fixo.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Nível predominante:** Aplicar

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar vetor e variáveis auxiliares com tipos compatíveis com o processamento numérico da tarefa.  
Verbos de Bloom: declarar, implementar, usar

K07 / Aplicar → executar percursos controlados para preencher e percorrer o vetor sem violar seus limites.  
Verbos de Bloom: executar, iterar, implementar

K08 / Aplicar → armazenar e acessar elementos por posição válida em uma coleção homogênea indexada.  
Verbos de Bloom: manipular, processar, usar

**Especificação de Disposições**
- atenção aos limites do vetor
- regularidade no preenchimento
- rigor no acesso posicional

**Competências Alinhadas à BNCC**
- EF69CO02
- EF69CO05

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.4.2 | Representar e processar coleções homogêneas com vetores | atenção aos limites; regularidade no preenchimento; rigor posicional | K02 | declarar vetor e variáveis auxiliares com tipos compatíveis com o processamento numérico da tarefa |
| CT16.4.2 | Representar e processar coleções homogêneas com vetores | atenção aos limites; regularidade no preenchimento; rigor posicional | K07 | executar percursos controlados para preencher e percorrer o vetor sem violar seus limites |
| CT16.4.2 | Representar e processar coleções homogêneas com vetores | atenção aos limites; regularidade no preenchimento; rigor posicional | K08 | armazenar e acessar elementos por posição válida em uma coleção homogênea indexada |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o núcleo observável da questão está na manipulação correta de um vetor de 30 posições. A competência é ativada quando o estudante representa a coleção, preenche suas posições e a percorre adequadamente.

## CT16.4.3

**Título da Competência**  
Produzir saída coerente com a ordem e o critério solicitados

**Descrição Textual**  
Exibir resultados de forma aderente ao enunciado, respeitando a ordem reversa de apresentação e o critério de seleção dos elementos pares.

**Cobertura e rastreabilidade**
- LOs cobertos: LO3, LO4
- K mobilizados (Núcleo): K03, K05, K06

**Especificação de Conhecimentos**
- **K03:** sustenta o cálculo da paridade dos valores processados.
- **K05:** sustenta a produção de saída verificável e coerente com o processamento realizado.
- **K06:** sustenta o uso de seleção simples para decidir quando um elemento deve ser exibido.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Nível predominante:** Aplicar

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → calcular a paridade dos elementos para determinar quais pertencem ao resultado.  
Verbos de Bloom: calcular, operar, usar

K05 / Aplicar → produzir saída coerente com a ordem de exibição e com o subconjunto solicitado.  
Verbos de Bloom: exibir, implementar, realizar

K06 / Aplicar → empregar seleção simples para mostrar apenas os elementos que atendem ao critério.  
Verbos de Bloom: implementar, selecionar, usar

**Especificação de Disposições**
- cuidado com a aderência da saída
- precisão na aplicação do critério
- compromisso com verificabilidade

**Competências Alinhadas à BNCC**
- EF69CO03
- EF69CO05

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.4.3 | Produzir saída coerente com a ordem e o critério solicitados | cuidado com a saída; precisão no critério; compromisso com verificabilidade | K03 | calcular a paridade dos elementos para determinar quais pertencem ao resultado |
| CT16.4.3 | Produzir saída coerente com a ordem e o critério solicitados | cuidado com a saída; precisão no critério; compromisso com verificabilidade | K05 | produzir saída coerente com a ordem de exibição e com o subconjunto solicitado |
| CT16.4.3 | Produzir saída coerente com a ordem e o critério solicitados | cuidado com a saída; precisão no critério; compromisso com verificabilidade | K06 | empregar seleção simples para mostrar apenas os elementos que atendem ao critério |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: como a correção da maratona depende da aderência exata da saída ao enunciado, esta competência é ativada quando o estudante exibe apenas os valores pares, na ordem reversa requerida e sem inconsistências observáveis.
