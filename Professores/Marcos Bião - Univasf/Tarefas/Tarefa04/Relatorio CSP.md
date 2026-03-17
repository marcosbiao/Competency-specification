# RELATÓRIO CSP: Autoria de Competências

## Introdução

Este relatório situa a **TASK04** na fase de **Autoria de Competências** do Competency Specification Process, com foco na identificação e especificação de conhecimentos, objetivos de aprendizagem e competências mobilizados pela atividade. A tarefa é conceitual, de resposta objetiva com justificativa breve, e solicita ao estudante analisar afirmativas sobre o uso de `if ... else` em comparação com dois `if`, selecionando a alternativa correta e sustentando sua escolha com base em argumentos técnicos verificáveis.

A atividade elicita evidências observáveis porque exige dois produtos claros: a **seleção de uma alternativa** e a **apresentação de uma justificativa breve**. Esses produtos permitem avaliar compreensão conceitual, análise do fluxo de execução e julgamento técnico sobre estruturas de seleção. O modelo **K–S–D** é adequado porque a tarefa mobiliza conhecimentos de lógica condicional e controle de fluxo, habilidades de análise e avaliação, e disposições ligadas a rigor conceitual, precisão e clareza argumentativa, sem redundância e com potencial de reuso em outras tarefas introdutórias da disciplina.

---

# 1. Análise da Entidade Instrucional

## Título

**TASK04: Justificativa do uso de `if ... else` em comparação com dois `if`**

## Descrição

Trata-se de uma tarefa conceitual de múltipla escolha, aplicada em contexto de avaliação individual, cujo foco é examinar a compreensão do estudante sobre o emprego de estruturas de seleção em cenários com duas possibilidades de resposta. A atividade não exige implementação de código, mas demanda leitura analítica do enunciado, comparação entre afirmativas e elaboração de justificativa curta, tecnicamente coerente, acerca do comportamento esperado do fluxo condicional.

## Processo de Desenvolvimento da Solução (em etapas)

1. Ler integralmente o enunciado e identificar o problema conceitual central.
2. Interpretar cada afirmativa à luz do funcionamento de estruturas condicionais em programação imperativa introdutória.
3. Comparar as afirmativas quanto à correção técnica, especialmente no que se refere a exclusividade de casos, quantidade de testes e adequação estrutural.
4. Selecionar a alternativa considerada correta.
5. Redigir justificativa breve, verificável e coerente com o comportamento do fluxo de execução.

## Resultados Esperados

1. Marcação de uma única alternativa entre as opções apresentadas.
2. Justificativa breve explicando por que a alternativa selecionada é tecnicamente adequada.
3. Evidência de compreensão sobre:
   1. o papel da estrutura `if ... else` em decisões binárias;
   2. a diferença entre alternativas condicionalmente equivalentes;
   3. a relação entre forma estrutural, fluxo de execução e economia de testes em nível introdutório.

## Contexto de Aquisição

- **Curso:** Ciência da Computação
- **Nível:** Graduação, 1º semestre
- **Componente Curricular:** Introdução à Programação
- **Organização da atividade:** individual
- **Ambiente provável:** laboratório de programação ou atividade prática equivalente
- **Forma de avaliação:** análise do código, da saída produzida e da justificativa breve

## Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de formação em programação, tipicamente no primeiro semestre, com contato introdutório com estruturas de seleção. Pressupõe-se familiaridade básica com:

1. leitura de enunciados técnicos;
2. noção elementar de condição lógica;
3. entendimento introdutório de fluxo de controle;
4. distinção entre alternativas de execução em programas imperativos.

## Nível de Proficiência (critérios e dimensões)

| Nível | Reconhecimento conceitual | Análise do fluxo condicional | Justificativa técnica |
|---|---|---|---|
| **N1 - Inicial** | Reconhece parcialmente o papel do `if ... else`, mas com confusão entre clareza e eficiência | Identifica a existência de alternativas, sem explicar adequadamente a dinâmica dos testes | Justificativa incompleta, genérica ou pouco verificável |
| **N2 - Intermediário** | Distingue o uso de `if ... else` em cenários binários simples | Analisa de forma satisfatória a diferença entre uma e outra organização condicional | Justificativa correta, porém breve e ainda pouco precisa em alguns termos |
| **N3 - Proficiente** | Relaciona corretamente exclusividade de casos, fluxo de execução e adequação estrutural | Explica com clareza a redução de verificações em nível introdutório | Justificativa consistente, objetiva e tecnicamente bem fundamentada |
| **N4 - Avançado** | Articula com precisão conceitual o papel da estrutura de seleção no comportamento do programa | Analisa criticamente as afirmativas, distinguindo argumentos válidos e inválidos | Justificativa rigorosa, clara, concisa e inteiramente verificável |


# 2. Seleção e Enumeração de Conhecimentos

## Conhecimentos selecionados

### **K01 — Modelo de execução e noção de estado (paradigma imperativo)**

1. Compreensão de que o programa segue um fluxo de execução observável, no qual decisões alteram o caminho percorrido.
2. Entendimento de que a escolha de um ramo condicional afeta quais comandos são efetivamente considerados na execução.
3. Leitura operacional do comportamento do programa em estruturas simples de controle.

**Justificativa de mobilização na tarefa:**  
A atividade exige que o estudante interprete o comportamento do fluxo condicional e raciocine sobre o efeito da estrutura escolhida no número de verificações realizadas.

### **K04 — Expressões lógicas e condições**

1. Compreensão de condições booleanas como base para tomada de decisão.
2. Interpretação da relação entre verdade, falsidade e abertura de caminhos alternativos de execução.
3. Reconhecimento de que decisões binárias exigem formulação lógica coerente com os casos previstos.

**Justificativa de mobilização na tarefa:**  
A comparação entre `if ... else` e dois `if` depende de entender como condições sustentam escolhas mutuamente exclusivas e organizam a decisão computacional.

### **K05 — Estrutura sequencial e E/S básica**

1. Compreensão da execução como sequência ordenada de verificações e comandos.
2. Leitura do encadeamento mínimo entre avaliação da condição e passagem ao próximo passo do programa.
3. Organização observável do comportamento elementar do programa, mesmo em tarefa sem implementação.

**Justificativa de mobilização na tarefa:**  
Embora a tarefa não peça código, a justificativa técnica depende de entender a sequência básica de testes e desvios no fluxo de execução.

### **K06 — Estruturas de seleção**

1. Conhecimento da função de estruturas condicionais na escolha de caminhos alternativos.
2. Reconhecimento do papel de `if ... else` em cenários com duas respostas possíveis.
3. Compreensão introdutória de cobertura de casos e adequação estrutural na seleção.

**Justificativa de mobilização na tarefa:**  
Este é o conhecimento central da task, pois o problema solicita avaliar a adequação de uma estrutura de seleção frente a outra em um cenário binário.

---

# 3. Identificação de Objetivos de Aprendizagem

## LO1

**Diferenciar situações de decisão mutuamente exclusiva e reconhecer quando a estrutura `if ... else` é adequada em relação a alternativas condicionais equivalentes.**

**K associados:** (K04, K06)

## LO2

**Analisar o impacto elementar do fluxo de execução sobre a quantidade de testes realizados em estruturas condicionais simples.**

**K associados:** (K01, K05, K06)

## LO3

**Avaliar afirmativas técnicas sobre estruturas de seleção e justificar a escolha de uma alternativa com base em evidências conceituais verificáveis.**

**K associados:** (K01, K04, K05, K06)


# 4. Definição de Competências

## 4.1 Competência Geral

**Competência Geral do domínio de Computação**

Interpretar, comparar e justificar o uso de estruturas de seleção em programas imperativos introdutórios, articulando condições lógicas, fluxo de execução e critérios técnicos de adequação.

**BNCC:** não aplicável como alinhamento específico, por se tratar de tarefa situada no contexto de educação superior.

---

## 4.2 Especificações de Competências

### Competência CT04.1

**Título da Competência**  
Selecionar estruturas condicionais coerentes com cenários binários.

**Descrição Textual (reutilizável; não específica do enunciado)**  
Trata-se de reconhecer situações em que duas possibilidades de resposta são mutuamente exclusivas e de selecionar a estrutura de seleção mais coerente com a cobertura dos casos, evitando redundâncias desnecessárias no controle do fluxo.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1)
2. K mobilizados (Núcleo): (K04, K06)

**Especificação de Conhecimentos**

**K04**  
Condições lógicas sustentam a distinção entre casos possíveis e a abertura correta dos ramos alternativos.  
**Justificativa de evidência:** a tarefa exige interpretar a relação entre condição e possibilidade de escolha exclusiva.

**K06**  
Estruturas de seleção organizam caminhos alternativos de execução conforme a regra do problema.  
**Justificativa de evidência:** o enunciado pede decidir qual forma estrutural é mais adequada em um cenário com duas respostas possíveis.


**Pareamento Conhecimento–Habilidade**

K04 / Analisar → distinguir condições mutuamente exclusivas e relacioná-las à abertura correta de ramos alternativos.  
Verbos de Bloom: distinguir, relacionar, decompor

K06 / Analisar → estruturar a escolha da estrutura condicional conforme a cobertura completa e não redundante dos casos.  
Verbos de Bloom: estruturar, categorizar, analisar



**Especificação de Disposições (2–4)**  
1. Precisão conceitual  
2. Atenção à consistência lógica  
3. Clareza analítica

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável ao contexto desta task.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT04.1 | Selecionar estruturas condicionais coerentes com cenários binários | Precisão conceitual; Atenção à consistência lógica; Clareza analítica | K04 | Distinguir condições mutuamente exclusivas e relacioná-las à abertura correta de ramos alternativos |
| CT04.1 | Selecionar estruturas condicionais coerentes com cenários binários | Precisão conceitual; Atenção à consistência lógica; Clareza analítica | K06 | Estruturar a escolha da estrutura condicional conforme a cobertura completa e não redundante dos casos |


**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: analítica
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a task exige que o estudante compare estruturalmente alternativas condicionais e reconheça qual delas é adequada a um cenário com duas possibilidades de resposta. A ativação desta competência é direta e central para a resolução.

---

### Competência CT04.2

**Título da Competência**  
Analisar efeitos operacionais elementares do fluxo condicional.

**Descrição Textual (reutilizável; não específica do enunciado)**  
Trata-se de examinar, em nível introdutório, como a organização do controle condicional afeta o percurso de execução do programa, especialmente no que se refere à quantidade de verificações realizadas em cenários simples.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO2, LO3)
2. K mobilizados (Núcleo): (K01, K06)

**Especificação de Conhecimentos**

**K01**  
O modelo de execução permite interpretar quais testes podem ou não ocorrer conforme o ramo selecionado.  
**Justificativa de evidência:** a questão exige comparar o efeito operacional de uma estrutura sobre o número de avaliações condicionais.

**K06**  
Estruturas de seleção definem como as alternativas são percorridas durante a execução.  
**Justificativa de evidência:** a escolha correta depende de compreender o comportamento operacional de `if ... else` frente a dois `if`.


**Pareamento Conhecimento–Habilidade**

K01 / Avaliar → julgar o efeito do fluxo de execução sobre a quantidade potencial de avaliações condicionais.  
Verbos de Bloom: julgar, verificar, justificar

K06 / Avaliar → decidir se a estrutura de seleção adotada é tecnicamente adequada ao cenário de duas respostas possíveis.  
Verbos de Bloom: decidir, escolher, validar


**Especificação de Disposições**  
1. Rigor argumentativo  
2. Precisão na análise  
3. Atenção a evidências operacionais

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável ao contexto desta task.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT04.2 | Analisar efeitos operacionais elementares do fluxo condicional | Rigor argumentativo; Precisão na análise; Atenção a evidências operacionais | K01 | Julgar o efeito do fluxo de execução sobre a quantidade potencial de avaliações condicionais |
| CT04.2 | Analisar efeitos operacionais elementares do fluxo condicional | Rigor argumentativo; Precisão na análise; Atenção a evidências operacionais | K06 | Decidir se a estrutura de seleção adotada é tecnicamente adequada ao cenário de duas respostas possíveis |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: analítica
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a atividade solicita avaliar se determinada justificativa técnica sobre o uso do `if ... else` é válida. Isso ativa diretamente a análise do comportamento operacional elementar do fluxo condicional.

---

### Competência CT04.3

**Título da Competência**  
Justificar escolhas de controle de fluxo com argumentação técnica verificável.

**Descrição Textual (reutilizável; não específica do enunciado)**  
Trata-se de sustentar uma decisão sobre o uso de estruturas condicionais por meio de justificativa breve, clara e tecnicamente coerente, articulando lógica das condições e comportamento esperado da execução.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO3)
2. K mobilizados (Núcleo): (K01, K04)

**Especificação de Conhecimentos**

**K01**  
A justificativa técnica depende de compreender o comportamento do fluxo de execução e seus efeitos observáveis.  
**Justificativa de evidência:** o estudante deve explicar por que uma alternativa é correta com base na dinâmica do programa.

**K04**  
A defesa da alternativa selecionada exige coerência entre formulação lógica e organização do desvio condicional.  
**Justificativa de evidência:** a tarefa demanda avaliar afirmativas que tratam da adequação conceitual da decisão binária.


**Pareamento Conhecimento–Habilidade**

K01 / Avaliar → justificar o comportamento observado de uma decisão condicional com base na lógica de execução do programa.  
Verbos de Bloom: justificar, defender, verificar

K04 / Avaliar → verificar se as afirmativas sobre condições e exclusividade de casos são tecnicamente sustentáveis.  
Verbos de Bloom: verificar, argumentar, escolher


**Especificação de Disposições**  
1. Clareza comunicativa  
2. Rigor conceitual  
3. Objetividade técnica

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável ao contexto desta task.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT04.3 | Justificar escolhas de controle de fluxo com argumentação técnica verificável | Clareza comunicativa; Rigor conceitual; Objetividade técnica | K01 | Justificar o comportamento observado de uma decisão condicional com base na lógica de execução do programa |
| CT04.3 | Justificar escolhas de controle de fluxo com argumentação técnica verificável | Clareza comunicativa; Rigor conceitual; Objetividade técnica | K04 | Verificar se as afirmativas sobre condições e exclusividade de casos são tecnicamente sustentáveis |


**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: justificatória
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a resolução não se encerra com a escolha da alternativa. A task exige justificativa breve, o que ativa explicitamente a competência de defender tecnicamente a decisão adotada com base em evidências conceituais.

