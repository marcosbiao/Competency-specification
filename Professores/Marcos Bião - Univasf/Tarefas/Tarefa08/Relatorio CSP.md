# RELATÓRIO CSP — Fase de Autoria de Competências

## Introdução

Este relatório situa a task **TASK08** na fase de **Autoria de Competências** do CSP, com foco na especificação rastreável de conhecimentos, objetivos de aprendizagem e competências mobilizados pela atividade. A tarefa solicita a construção de um programa que receba dois números positivos `a` e `b` e calcule o produto, o quociente e o resto da divisão de `a` por `b`, sob a restrição de uso exclusivo de operações de soma e subtração.

A atividade elicita evidências observáveis porque exige um artefato executável, saídas verificáveis e justificativa breve sobre a estratégia utilizada. Isso permite explicitar conhecimentos diretamente mobilizados pela solução, habilidades operacionais de programação e disposições relacionadas à precisão, controle iterativo e respeito às restrições do problema, sem redundância entre os níveis K, LO e CT.

## 1. Análise da Entidade Instrucional

### Título

**TASK08 — Cálculo de produto, quociente e resto com operações elementares**

### Descrição

A tarefa propõe a implementação de uma solução numérica em programação introdutória na qual o estudante deve obter três resultados a partir de duas entradas positivas: produto, quociente e resto. A característica central do enunciado está na restrição operacional, pois a solução não pode recorrer diretamente a multiplicação, divisão ou operador de resto, exigindo a reformulação do problema com base em iteração, atualização de estado e controle de parada.

### Processo de Desenvolvimento da Solução (em etapas)

1. Interpretar o enunciado, as entradas e a restrição de uso apenas de soma e subtração.
2. Organizar a estrutura básica do programa com leitura dos valores e definição dos resultados esperados.
3. Planejar uma estratégia iterativa para calcular o produto por acumulação sucessiva.
4. Planejar uma estratégia iterativa para obter quociente e resto por subtrações sucessivas com condição de parada consistente.
5. Integrar os resultados em uma saída verificável e apresentar justificativa breve sobre a lógica da solução.

### Resultados Esperados

* Programa que receba dois valores positivos e produza produto, quociente e resto.
* Saídas compatíveis com os dados de entrada informados.
* Justificativa breve e tecnicamente coerente sobre a estratégia adotada.
* Evidências de que a solução respeita a restrição operacional do problema.

### Contexto de Aquisição (curso, organização, ambiente, avaliação)

* **Curso/Nível:** Ciência da Computação, disciplina introdutória de 1º semestre.
* **Componente curricular:** Introdução à Programação.
* **Organização:** realização individual.
* **Ambiente:** laboratório de programação ou avaliação prática/escrita com foco em algoritmo e implementação.
* **Avaliação:** observação do artefato produzido, verificação das saídas e análise da justificativa apresentada.

### Perfil do Público-Alvo (nível, pré-requisitos, necessidades)

* Estudantes iniciantes em programação imperativa.
* Pré-requisitos esperados: noções de variáveis, tipos primitivos, entrada e saída básica e estruturas de repetição em nível introdutório.
* Necessidades formativas: consolidar a relação entre estado do programa, repetição, condição de parada e transformação de entradas em saídas numéricas verificáveis.

### Nível de Proficiência (critérios e dimensões)

| Nível | Compreensão da restrição operacional | Estruturação do programa | Controle iterativo e condição de parada | Correção dos resultados e justificativa |
|---|---|---|---|---|
| **N1 - Inicial** | Reconhece a restrição, mas ainda depende de decisões inconsistentes na formulação da solução. | Organiza parcialmente entrada, processamento e saída. | Usa repetição com falhas de atualização ou de término. | Apresenta resultados incompletos ou justificativa insuficiente. |
| **N2 - Intermediário** | Respeita parcialmente a restrição, com pequenas inconsistências de modelagem. | Estrutura o fluxo principal, mas com fragilidades de integração entre etapas. | Implementa repetição funcional, mas com justificativa limitada sobre parada e estado. | Obtém parte dos resultados corretamente e justifica de forma parcial. |
| **N3 - Proficiente** | Respeita integralmente a restrição e modela a solução com coerência. | Organiza corretamente entrada, processamento iterativo e saída verificável. | Controla corretamente a atualização do estado e a condição de parada. | Obtém produto, quociente e resto de forma correta e justifica de modo coerente. |
| **N4 - Avançado** | Além de respeitar a restrição, justifica com clareza por que a estratégia escolhida é válida. | Estrutura o programa com clareza, coesão e boa legibilidade lógica. | Demonstra domínio do comportamento iterativo e consegue explicar sua correção operacional. | Além da correção, explicita com precisão a relação entre entradas, iteração e resultados. |

## 2. Seleção e Enumeração de Conhecimentos

**K01 — Modelo de execução e noção de estado (paradigma imperativo)**
* Compreensão de que o programa evolui por mudanças sucessivas de estado durante a execução.
* Reconhecimento de que atribuições e iterações alteram acumuladores, contadores e resultados parciais.
* Leitura do fluxo de execução como sequência de transições observáveis.

**Justificativa de mobilização na tarefa:** a solução depende de acompanhar atualizações sucessivas de variáveis para produzir produto, quociente e resto sem operadores diretos.

**K02 — Variáveis, constantes e tipos primitivos**
* Representação de dados numéricos simples por meio de variáveis compatíveis com o papel de cada valor.
* Uso coerente de identificadores para entradas, acumuladores e resultados.
* Distinção entre dados de entrada e valores atualizados ao longo da execução.

**Justificativa de mobilização na tarefa:** o problema exige manipulação explícita de entradas e resultados numéricos, com coerência entre os papéis assumidos pelas variáveis.

**K03 — Expressões aritméticas e avaliação**
* Construção de cálculos numéricos por meio de operações aritméticas básicas disponíveis.
* Atualização de valores por expressões aritméticas compatíveis com a estratégia adotada.
* Avaliação consistente de resultados parciais ao longo do processamento.

**Justificativa de mobilização na tarefa:** a atividade exige reformular operações derivadas em termos de soma e subtração, mantendo consistência nos cálculos intermediários.

**K04 — Expressões lógicas e condições**
* Construção de condições para controlar continuidade e término de processos iterativos.
* Uso de comparações coerentes para verificar quando interromper a repetição.
* Interpretação lógica de estados que autorizam ou impedem nova iteração.

**Justificativa de mobilização na tarefa:** o cálculo de quociente e resto por subtrações sucessivas depende de condição de parada logicamente correta.

**K05 — Estrutura sequencial e E/S básica**
* Organização do programa no fluxo entrada → processamento → saída.
* Leitura de dados e apresentação de resultados de forma verificável.
* Encadeamento coerente das etapas da solução.

**Justificativa de mobilização na tarefa:** a solução precisa transformar duas entradas em três resultados observáveis dentro de uma sequência operacional clara.

**K07 — Estruturas de repetição**
* Execução repetida de comandos com controle por condição ou contagem.
* Uso de laços para acumulação e decomposição sucessiva de valores.
* Garantia de término do processo iterativo em situações válidas.

**Justificativa de mobilização na tarefa:** a estratégia exigida pelo enunciado depende diretamente de repetição para substituir multiplicação e divisão.

## 3. Identificação de Objetivos de Aprendizagem

### LO1
**Estruturar um programa introdutório que receba entradas numéricas e apresente resultados verificáveis de processamento.**

**K associados:** (K02, K05)

### LO2
**Implementar estratégias iterativas de acumulação numérica para obter resultados sem recorrer diretamente a operadores não permitidos.**

**K associados:** (K01, K03, K07)

### LO3
**Controlar processos iterativos por meio de condições lógicas consistentes, garantindo término e correção dos resultados intermediários e finais.**

**K associados:** (K01, K03, K04, K07)

### LO4
**Justificar o comportamento da solução com base na atualização do estado do programa, nas condições de parada e na verificabilidade das saídas.**

**K associados:** (K01, K03, K04, K05, K07)

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver soluções algorítmicas em programação imperativa para transformar entradas numéricas em saídas verificáveis, organizando fluxo de execução, iteração, controle lógico e justificativa do comportamento do programa.

**BNCC:** não aplicável como referencial específico para esta task, por se tratar de contexto de ensino superior em disciplina introdutória de Computação.

### 4.2 Especificações de Competências

#### CT08.1

**Título da Competência**  
Estruturar programas numéricos introdutórios com fluxo verificável de entrada, processamento e saída.

**Descrição Textual**  
Capacidade de organizar programas imperativos simples que recebam dados, mantenham coerência entre variáveis e resultados e apresentem saídas verificáveis em sequência operacional clara.

**Cobertura e rastreabilidade**
* LOs cobertos: (LO1)
* K mobilizados (Núcleo): (K02, K05)

**Especificação de Conhecimentos**
* **K02:** representação de dados por variáveis e tipos primitivos.  
  **Justificativa de evidência:** a tarefa evidencia diretamente a definição de entradas e resultados numéricos com papéis distintos.
* **K05:** organização sequencial com leitura, processamento e saída.  
  **Justificativa de evidência:** o artefato produzido precisa exibir claramente o fluxo completo da solução.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Aplicar**

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar e utilizar variáveis numéricas compatíveis com o papel de entradas, acumuladores e resultados.  
Verbos de Bloom: aplicar, usar, operar

K05 / Aplicar → estruturar o fluxo de entrada, processamento e saída de modo verificável.  
Verbos de Bloom: organizar, executar, apresentar



**Especificação de Disposições**
* precisão na identificação do papel de cada variável;
* cuidado com a consistência entre entrada, processamento e saída;
* atenção à legibilidade lógica da solução.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto desta task.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT08.1 | Estruturar programas numéricos introdutórios com fluxo verificável de entrada, processamento e saída | precisão, consistência, legibilidade lógica | K02 | declarar e utilizar variáveis numéricas compatíveis com o papel de entradas, acumuladores e resultados |
| CT08.1 | Estruturar programas numéricos introdutórios com fluxo verificável de entrada, processamento e saída | precisão, consistência, legibilidade lógica | K05 | estruturar o fluxo de entrada, processamento e saída de modo verificável |


**Definição de Ativação**
* Restrição de ativação: obrigatória
* Modo de ativação: construtiva
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: a task exige a produção de um programa completo e verificável. Sem a organização do fluxo básico e sem coerência entre variáveis e resultados, não há como materializar a solução nem observar evidências confiáveis do desempenho do estudante.



#### CT08.2

**Título da Competência**  
Construir algoritmos iterativos para derivar operações numéricas a partir de operações elementares.

**Descrição Textual**  
Capacidade de desenvolver soluções algorítmicas que reformulem operações numéricas derivadas em processos iterativos baseados em atualização de estado e operações elementares permitidas pelo problema.

**Cobertura e rastreabilidade**
* LOs cobertos: (LO2, LO3)
* K mobilizados (Núcleo): (K01, K03, K07)

**Especificação de Conhecimentos**
* **K01:** noção de estado e transição em programas imperativos.  
  **Justificativa de evidência:** a competência se evidencia pelo controle de acumuladores, contadores e resultados parciais durante a iteração.
* **K03:** avaliação de expressões aritméticas em atualizações sucessivas.  
  **Justificativa de evidência:** a solução exige compor atualizações por soma e subtração sem recorrer a operadores diretos.
* **K07:** repetição com término garantido.  
  **Justificativa de evidência:** a tarefa depende de laços que produzam o resultado esperado por acumulação ou subtração sucessiva.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Criar**

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → rastrear a atualização do estado do programa em ciclos iterativos numéricos.  
Verbos de Bloom: rastrear, atualizar, estruturar

K03 / Aplicar → operar expressões aritméticas elementares para produzir resultados por acumulação ou redução sucessiva.  
Verbos de Bloom: calcular, manipular, executar

K07 / Criar → construir laços iterativos que realizem processamento numérico com parada garantida.  
Verbos de Bloom: construir, desenvolver, programar


**Especificação de Disposições**
* disciplina no respeito às restrições operacionais do problema;
* precisão na atualização de valores intermediários;
* atenção à condição de parada e ao término do laço;
* persistência na decomposição do problema em passos executáveis.

**Competências Alinhadas à BNCC (quando aplicável)**  
Não aplicável ao contexto desta task.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT08.2 | Construir algoritmos iterativos para derivar operações numéricas a partir de operações elementares | disciplina, precisão, atenção à parada, persistência | K01 | rastrear a atualização do estado do programa em ciclos iterativos numéricos |
| CT08.2 | Construir algoritmos iterativos para derivar operações numéricas a partir de operações elementares | disciplina, precisão, atenção à parada, persistência | K03 | operar expressões aritméticas elementares para produzir resultados por acumulação ou redução sucessiva |
| CT08.2 | Construir algoritmos iterativos para derivar operações numéricas a partir de operações elementares | disciplina, precisão, atenção à parada, persistência | K07 | construir laços iterativos que realizem processamento numérico com parada garantida |


**Definição de Ativação**
* Restrição de ativação: obrigatória
* Modo de ativação: construtiva
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: a competência é central porque o enunciado exige que o estudante conceba e implemente uma solução iterativa sob restrição explícita de operadores. O produto e a divisão inteira não podem ser obtidos por aplicação direta de operadores prontos, o que torna a construção algorítmica o núcleo da evidência.



#### CT08.3

**Título da Competência**  
Justificar a correção operacional de programas iterativos com base em estado, condição de parada e resultados observáveis.

**Descrição Textual**  
Capacidade de analisar e defender a correção de programas imperativos simples, relacionando atualização de estado, condições lógicas de controle e consistência entre processamento realizado e saídas produzidas.

**Cobertura e rastreabilidade**
* LOs cobertos: (LO3, LO4)
* K mobilizados (Núcleo): (K01, K04, K07)

**Especificação de Conhecimentos**
* **K01:** evolução do estado do programa durante a execução.  
  **Justificativa de evidência:** a justificativa depende de explicar como valores intermediários mudam ao longo do processamento.
* **K04:** condições lógicas e interpretação de parada.  
  **Justificativa de evidência:** a correção da solução depende de demonstrar por que o laço continua ou termina adequadamente.
* **K07:** repetição e término do processo.  
  **Justificativa de evidência:** a competência se manifesta quando o estudante mostra que o mecanismo iterativo produz o resultado esperado sem inconsistências de controle.

**Alinhamento com a Taxonomia de Bloom**  
**Avaliar**

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → relacionar mudanças de estado às etapas do processamento executado.  
Verbos de Bloom: analisar, rastrear, relacionar

K04 / Avaliar → justificar a adequação das condições lógicas usadas para manter ou encerrar a repetição.  
Verbos de Bloom: justificar, verificar, validar

K07 / Analisar → examinar o comportamento do laço quanto a atualização, término e produção dos resultados esperados.  
Verbos de Bloom: examinar, analisar, monitorar

**Especificação de Disposições**
* rigor na justificativa do comportamento do programa;
* atenção à verificabilidade dos resultados;
* cuidado com a coerência entre execução e explicação;
* responsabilidade intelectual ao defender a solução produzida.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto desta task.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT08.3 | Justificar a correção operacional de programas iterativos com base em estado, condição de parada e resultados observáveis | rigor, verificabilidade, coerência, responsabilidade intelectual | K01 | relacionar mudanças de estado às etapas do processamento executado |
| CT08.3 | Justificar a correção operacional de programas iterativos com base em estado, condição de parada e resultados observáveis | rigor, verificabilidade, coerência, responsabilidade intelectual | K04 | justificar a adequação das condições lógicas usadas para manter ou encerrar a repetição |
| CT08.3 | Justificar a correção operacional de programas iterativos com base em estado, condição de parada e resultados observáveis | rigor, verificabilidade, coerência, responsabilidade intelectual | K07 | examinar o comportamento do laço quanto a atualização, término e produção dos resultados esperados |


**Definição de Ativação**
* Restrição de ativação: obrigatória
* Modo de ativação: justificatória
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: além de programar, o estudante deve demonstrar que compreende o comportamento da solução produzida. A presença de justificativa breve no enunciado pedagógico torna indispensável a ativação analítica e justificatória dessa competência para validar a correção da resposta.
