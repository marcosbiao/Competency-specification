# RELATÓRIO CSP — FASE DE AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório enquadra a TASK07 na fase de **Autoria de Competências** do CSP, com base exclusiva na descrição pedagógica da atividade e no catálogo fixo de conhecimentos da disciplina. A tarefa consiste em analisar afirmativas sobre estruturas de repetição e selecionar a alternativa correta, acompanhando a resposta de justificativa breve e tecnicamente coerente.

A atividade elicita evidências observáveis porque exige que o estudante interprete o funcionamento de `for`, `while` e `do while`, relacione o ponto de teste da condição ao comportamento do laço e julgue a correção de afirmações conceituais. O recorte abaixo preserva rastreabilidade entre **K**, **LO** e **CT**, evita redundância e prioriza competências reutilizáveis dentro da disciplina de Introdução à Programação.

## 1. Análise da Entidade Instrucional

### Título

**Análise conceitual de estruturas de repetição**

### Descrição

Atividade individual, de natureza avaliativa, centrada na leitura e análise de quatro afirmativas sobre estruturas de repetição em programação. O estudante deve distinguir descrições corretas e incorretas sobre `for`, `while` e `do while`, selecionar uma alternativa de múltipla escolha e justificar brevemente sua decisão com base em evidências conceituais.

### Processo de Desenvolvimento da Solução

1. Ler o enunciado e identificar o foco conceitual da questão.
2. Examinar cada afirmativa separadamente.
3. Relacionar cada afirmativa ao comportamento esperado das estruturas `for`, `while` e `do while`.
4. Verificar, em cada caso, o papel da condição lógica e a posição do teste.
5. Determinar quais afirmativas se sustentam conceitualmente.
6. Selecionar a alternativa correspondente e registrar justificativa breve.

### Resultados Esperados

1. Marcação de uma única alternativa.
2. Justificativa breve, conceitualmente correta.
3. Distinção adequada entre teste no início e teste no final do laço.
4. Reconhecimento da possibilidade de não execução ou de execução mínima, conforme o tipo de laço.
5. Uso de terminologia técnica coerente ao justificar a escolha.

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

| Nível | Compreensão das estruturas de repetição | Interpretação da condição lógica | Julgamento das afirmativas | Clareza e verificabilidade da resposta |
|---|---|---|---|---|
| **N1 - Inicial** | Reconhece parcialmente os tipos de laço, mas ainda confunde seus comportamentos | Identifica a existência de condição, mas explica seu efeito de forma imprecisa | Escolhe alternativa com justificativa insuficiente ou inconsistente | Resposta pouco clara ou sem coerência interna |
| **N2 - Intermediário** | Distingue os laços mais comuns, embora com insegurança em casos específicos | Explica o papel da condição em situações usuais | Justifica parcialmente a escolha, mas com lacunas conceituais | Resposta compreensível, mas com justificativa parcial |
| **N3 - Proficiente** | Diferencia corretamente `for`, `while` e `do while` quanto ao controle e à execução | Relaciona corretamente condição, ponto de teste e continuidade do laço | Sustenta a escolha com justificativa breve, correta e verificável | Resposta clara, coerente e tecnicamente adequada |
| **N4 - Avançado** | Analisa com segurança nuances conceituais e antecipa implicações semânticas de cada forma de laço | Examina implicações do teste lógico com precisão terminológica e argumentativa | Valida e refuta afirmativas com argumentação técnica precisa e completa | Resposta sintética, rigorosa e terminologicamente precisa |

## 2. Seleção e Enumeração de Conhecimentos


**K01 — Modelo de execução e noção de estado (paradigma imperativo)**  
1. Compreensão de que a execução de um programa evolui por mudanças de estado ao longo do fluxo de controle.  
2. Interpretação de transições de estado produzidas por repetição e reavaliação de condições.  
3. Leitura operacional do comportamento do programa em nível introdutório.  

**Justificativa de mobilização na tarefa:** a análise das afirmativas exige interpretar o efeito do controle iterativo sobre a evolução da execução do programa.

**K04 — Expressões lógicas e condições**  
1. Construção e interpretação de condições booleanas para controle de fluxo.  
2. Relação entre valor lógico da condição e continuidade da execução.  
3. Compreensão do papel dos operadores relacionais e lógicos em contextos introdutórios.  

**Justificativa de mobilização na tarefa:** a tarefa exige distinguir como a condição controla o laço e em que ponto esse controle é verificado.

**K05 — Estrutura sequencial e E/S básica**  
1. Organização de ações em sequência operacional coerente.  
2. Leitura da ordem entre verificação, execução do corpo e continuidade do fluxo.  
3. Compreensão do encadeamento básico entre etapas de processamento.  

**Justificativa de mobilização na tarefa:** embora secundário, este conhecimento apoia a interpretação da ordem de execução presente nas afirmativas sobre início e final do laço.

**K07 — Estruturas de repetição**  
1. Compreensão de `for`, `while` e `do while` como mecanismos de repetição controlada.  
2. Distinção entre laços por contagem e por condição.  
3. Reconhecimento de condições de parada, execução nula e execução mínima.  

**Justificativa de mobilização na tarefa:** este é o conhecimento central diretamente evidenciado, pois o enunciado inteiro incide sobre o comportamento conceitual das estruturas de repetição.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Identificar o mecanismo de controle e o ponto de teste em estruturas de repetição `for`, `while` e `do while`.  
**K associados:** (K04, K07)

**LO2.** Relacionar a posição do teste lógico à possibilidade de não execução ou de execução mínima do laço.  
**K associados:** (K01, K04, K07)

**LO3.** Distinguir descrições corretas e incorretas sobre comportamento de estruturas de repetição em programação imperativa introdutória.  
**K associados:** (K01, K07)

**LO4.** Justificar tecnicamente a escolha de uma alternativa em questão conceitual sobre repetição, com terminologia adequada e evidência verificável.  
**K associados:** (K01, K04, K05, K07)


## 4. Definição de Competências

### 4.1 Competência Geral 

Analisar e justificar o comportamento de estruturas de controle iterativo em programação imperativa introdutória, distinguindo mecanismos de repetição, posição do teste lógico e implicações para a execução do programa.

**BNCC:** não aplicável ao contexto desta tarefa.

### 4.2 Especificações de Competências

#### CT07.1

**Título da Competência**  
**Controlar o fluxo com repetição, distinguindo o comportamento de `for`, `while` e `do while` quanto ao teste da condição e à execução do laço**

**Descrição Textual **  
Compreender e analisar, em tarefas introdutórias de programação, como diferentes estruturas de repetição controlam o fluxo de execução, distinguindo a posição do teste lógico, a continuidade do laço e seus efeitos sobre a execução do programa.

**Cobertura e rastreabilidade**  
1. LOs cobertos: (LO1, LO2)  
2. K mobilizados (Núcleo): (K04, K07)  

**Especificação de Conhecimentos**

**K04**  
Descrição curta: expressões lógicas e condições usadas no controle do fluxo.  
Justificativa de evidência: o estudante precisa interpretar como a condição lógica regula a repetição.

**K07**  
Descrição curta: estruturas de repetição e seus mecanismos de controle.  
Justificativa de evidência: a tarefa exige distinguir conceitualmente `for`, `while` e `do while`.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Nível predominante: **Analisar**

**Pareamento Conhecimento–Habilidade**

K04 / Analisar → distinguir como a condição lógica regula a continuidade ou a interrupção do laço.  
Verbos de Bloom: discriminar, examinar, relacionar

K07 / Analisar → diferenciar o comportamento de `for`, `while` e `do while` quanto ao controle da repetição e à posição do teste.  
Verbos de Bloom: analisar, distinguir, estruturar


**Especificação de Disposições**  
1. Atenção à coerência entre condição e comportamento do laço.  
2. Rigor conceitual ao diferenciar mecanismos de repetição.  
3. Cautela diante de generalizações incorretas sobre laços.  

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT07.1 | Controlar o fluxo com repetição, distinguindo o comportamento de `for`, `while` e `do while` quanto ao teste da condição e à execução do laço | Atenção à coerência lógica | K04 | Distinguir como a condição lógica regula a continuidade ou a interrupção do laço |
| CT07.1 | Controlar o fluxo com repetição, distinguindo o comportamento de `for`, `while` e `do while` quanto ao teste da condição e à execução do laço | Rigor conceitual | K07 | Diferenciar o comportamento de `for`, `while` e `do while` quanto ao controle da repetição e à posição do teste |


**Definição de Ativação**  
Restrição de ativação: obrigatória  
Modo de ativação: analítica  
Função de ativação: núcleo  
Justificativa curta baseada na tarefa: a questão exige análise direta do funcionamento dos laços e da posição do teste lógico. Esta competência é ativada de forma central na validação das afirmativas.



#### CT07.2

**Título da Competência**  
**Diferenciar cenários de execução em laços iterativos, relacionando a posição do teste lógico à possibilidade de não execução ou execução mínima**

**Descrição Textual (reutilizável; não específica do enunciado)**  
Analisar cenários de execução em estruturas de repetição introdutórias, relacionando o local em que a condição é verificada à possibilidade de o laço não executar, executar uma vez ou prosseguir iterativamente.

**Cobertura e rastreabilidade**  
1. LOs cobertos: (LO2, LO3)  
2. K mobilizados (Núcleo): (K01, K04, K07)

**Especificação de Conhecimentos**

**K01**  
Descrição curta: noção de estado e progressão da execução em programas imperativos.  
Justificativa de evidência: a competência exige interpretar as transições de execução que explicam se o laço entra ou não em funcionamento.

**K04**  
Descrição curta: condições booleanas aplicadas ao controle do fluxo.  
Justificativa de evidência: a possibilidade de execução depende da avaliação lógica da condição no ponto de teste.

**K07**  
Descrição curta: laços de repetição por condição e por contagem.  
Justificativa de evidência: a tarefa incide diretamente sobre diferenças semânticas entre os tipos de laço.

**Alinhamento com a Taxonomia de Bloom**  
Nível predominante: **Analisar**

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → interpretar as transições de estado que explicam a ocorrência de zero, uma ou várias iterações.  
Verbos de Bloom: rastrear, examinar, deduzir

K04 / Analisar → relacionar o valor lógico da condição ao momento em que o teste é realizado no laço.  
Verbos de Bloom: relacionar, decompor, examinar

K07 / Analisar → distinguir cenários de execução nula, mínima ou repetida conforme a estrutura de repetição utilizada.  
Verbos de Bloom: distinguir, detectar, analisar


**Especificação de Disposições**  
1. Precisão ao lidar com casos limite de execução.  
2. Disciplina conceitual na leitura do enunciado.  
3. Compromisso com inferências logicamente sustentadas.  

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT07.2 | Diferenciar cenários de execução em laços iterativos, relacionando a posição do teste lógico à possibilidade de não execução ou execução mínima | Precisão em casos limite | K01 | Interpretar as transições de estado que explicam a ocorrência de zero, uma ou várias iterações |
| CT07.2 | Diferenciar cenários de execução em laços iterativos, relacionando a posição do teste lógico à possibilidade de não execução ou execução mínima | Disciplina conceitual | K04 | Relacionar o valor lógico da condição ao momento em que o teste é realizado no laço |
| CT07.2 | Diferenciar cenários de execução em laços iterativos, relacionando a posição do teste lógico à possibilidade de não execução ou execução mínima | Compromisso com inferências sustentadas | K07 | Distinguir cenários de execução nula, mínima ou repetida conforme a estrutura de repetição utilizada |

**Definição de Ativação**  
Restrição de ativação: obrigatória  
Modo de ativação: analítica  
Função de ativação: núcleo  
Justificativa curta baseada na tarefa: a distinção entre laços que podem não executar e laços que executam ao menos uma vez compõe uma evidência central da questão. Esta competência sustenta o julgamento correto das afirmativas.

#### CT07.3

**Título da Competência**  
**Justificar tecnicamente julgamentos sobre estruturas de repetição**

**Descrição Textual (reutilizável; não específica do enunciado)**  
Julgar e justificar, em tarefas conceituais de programação introdutória, a correção de afirmações sobre estruturas de repetição, articulando terminologia técnica, regras de execução e evidências observáveis do comportamento do laço.

**Cobertura e rastreabilidade**  
1. LOs cobertos: (LO3, LO4)  
2. K mobilizados (Núcleo): (K01, K04, K07)  

**Especificação de Conhecimentos**

**K01**  
Descrição curta: execução como evolução de estado em programas imperativos.  
Justificativa de evidência: a justificativa da resposta depende de relacionar afirmações textuais ao comportamento esperado da execução.

**K04**  
Descrição curta: interpretação de condições lógicas no controle de fluxo.  
Justificativa de evidência: o julgamento das afirmativas depende da leitura correta do papel da condição no laço.

**K07**  
Descrição curta: conhecimento conceitual de estruturas de repetição.  
Justificativa de evidência: a escolha correta da alternativa exige domínio das regras de funcionamento de `for`, `while` e `do while`.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Nível predominante: **Avaliar**

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → correlacionar afirmações textuais com o comportamento esperado do fluxo iterativo.  
Verbos de Bloom: correlacionar, examinar, questionar

K04 / Avaliar → julgar a adequação conceitual de descrições sobre testes lógicos em estruturas de repetição.  
Verbos de Bloom: justificar, verificar, decidir

K07 / Avaliar → validar a correção de assertivas sobre `for`, `while` e `do while` com base em suas regras de execução.  
Verbos de Bloom: validar, argumentar, escolher


**Especificação de Disposições**  
1. Precisão terminológica na justificativa.  
2. Responsabilidade intelectual ao validar ou rejeitar afirmações.  
3. Preferência por evidência conceitual em vez de resposta intuitiva.  
4. Clareza argumentativa compatível com verificação.  

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT07.3 | Justificar tecnicamente julgamentos sobre estruturas de repetição | Precisão terminológica | K01 | Correlacionar afirmações textuais com o comportamento esperado do fluxo iterativo |
| CT07.3 | Justificar tecnicamente julgamentos sobre estruturas de repetição | Responsabilidade intelectual | K04 | Julgar a adequação conceitual de descrições sobre testes lógicos em estruturas de repetição |
| CT07.3 | Justificar tecnicamente julgamentos sobre estruturas de repetição | Preferência por evidência conceitual | K07 | Validar a correção de assertivas sobre `for`, `while` e `do while` com base em suas regras de execução |


**Definição de Ativação**  
Restrição de ativação: obrigatória  
Modo de ativação: justificatória  
Função de ativação: núcleo  
Justificativa curta baseada na tarefa: o produto da atividade inclui não apenas a marcação da alternativa, mas também uma justificativa breve e coerente. A competência é ativada de forma explícita na defesa técnica da resposta.

