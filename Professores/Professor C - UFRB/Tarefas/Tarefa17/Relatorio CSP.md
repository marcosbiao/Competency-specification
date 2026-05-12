# RELATÓRIO CSP - AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de Autoria de Competências do CSP e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados pela **TASK17**, uma atividade de programação introdutória em linguagem C voltada ao processamento de pedidos comerciais. A tarefa requer leitura de dados, cálculo de área, seleção de um único modelo de piso, composição de serviços adicionais, cálculo do valor final e repetição do atendimento para novos pedidos, além da produção de um resumo verificável do pedido.

A tarefa sustenta adequadamente o modelo K-S-D porque mobiliza conhecimentos centrais do catálogo da disciplina, exige habilidades técnicas avaliáveis e permite explicitar disposições compatíveis com rigor computacional, precisão e consistência lógica. O relatório foi construído sem criar novos conhecimentos fora do catálogo da disciplina e preserva reuso, rastreabilidade e controle de granularidade.

## 1. Análise da Entidade Instrucional

### Título

**Desafio Sustainable Floor: processamento de pedidos de piso com serviços complementares**

### Descrição

A task solicita o desenvolvimento de um programa em C para processar pedidos de piso a partir das dimensões de um cômodo, da escolha de um único modelo de piso e da contratação de zero a vários serviços complementares. A solução deve calcular a área, compor o valor final do pedido, exibir um resumo verificável e permitir o reinício do atendimento para um novo pedido. Além do programa, a atividade também requer a produção de um relatório técnico.

### Processo de Desenvolvimento da Solução

1. Identificar os dados relevantes do problema, incluindo dimensões do cômodo, área total, modelo de piso, serviços adicionais e valor final.
2. Representar esses dados com variáveis e tipos compatíveis com medidas reais e valores monetários.
3. Organizar o fluxo geral do programa em entrada, processamento e saída.
4. Implementar a escolha de um único modelo de piso por pedido.
5. Tratar a inclusão de nenhum, um ou vários serviços complementares, respeitando as regras do enunciado.
6. Calcular os valores derivados necessários à composição do preço total.
7. Exibir o resumo final do pedido com formatação verificável.
8. Controlar a repetição do atendimento quando houver solicitação de novo pedido.

### Resultados Esperados

- programa funcional em linguagem C;
- resumo do pedido contendo modelo, serviços, área total e valor total;
- repetição correta do fluxo para novos pedidos, quando solicitada;
- relatório técnico descrevendo o processo de desenvolvimento e os resultados obtidos.

### Contexto de Aquisição

- **Nível/Curso:** graduação, componente introdutório de computação/programação
- **Componente Curricular:** Programação de Computadores I
- **Contexto:** atividade avaliativa de programação estruturada em linguagem C
- **Ambiente:** laboratório de programação ou ambiente equivalente de desenvolvimento
- **Avaliação:** análise do código, da consistência do fluxo computacional, das saídas produzidas e do relatório técnico

### Perfil do Público-Alvo

O público-alvo é composto por estudantes iniciantes em programação estruturada, com contato formativo com leitura de dados, tipos básicos, expressões, estruturas condicionais, estruturas de repetição e organização de programas em linguagem C. Trata-se de um perfil que ainda está consolidando a tradução de regras textuais em comportamentos computacionais verificáveis, especialmente em problemas com múltiplas escolhas e composição de valores.

### Nível de Proficiência (critérios e dimensões)

| Nível | Representação de dados | Fluxo sequencial | Seleção condicional | Repetição do atendimento | Verificabilidade do artefato |
|---|---|---|---|---|---|
| **N1 - Inicial** | identifica apenas parte dos dados necessários | apresenta ordem de execução inconsistente | não cobre adequadamente as escolhas do problema | não controla o reinício do processo | saídas incompletas ou pouco legíveis |
| **N2 - Básico** | representa os dados principais com pequenas fragilidades | organiza parcialmente entrada, processamento e saída | cobre parte das regras com lacunas | repete o atendimento com falhas de controle | saídas compreensíveis, mas ainda frágeis |
| **N3 - Proficiente** | representa corretamente entradas, resultados intermediários e saídas | estrutura corretamente o fluxo completo do pedido | implementa corretamente as decisões exigidas | reinicia corretamente o fluxo quando solicitado | resumo final verificável e coerente |
| **N4 - Avançado** | organiza os dados com precisão e coerência ao longo de todo o programa | mantém fluxo claro, estável e facilmente verificável | articula decisões com alta consistência e sem ambiguidades | controla repetição com estabilidade e clareza de encerramento | programa e resultados com alto grau de clareza e rastreabilidade |

## 2. Seleção e Enumeração de Conhecimentos

Foram selecionados **5 conhecimentos** do catálogo da disciplina, respeitando o limite superior definido para Programação de Computadores I. A escolha prioriza os elementos diretamente mobilizados pela descrição pedagógica da task.

### K03 - Estrutura sequencial, entrada, processamento e saída

- organiza o programa como sequência ordenada de leitura, cálculo e exibição de resultados;
- estabelece encadeamento lógico entre os dados fornecidos e o resumo final do pedido;
- permite verificar o comportamento geral da solução.

**Justificativa de mobilização na tarefa:** o programa depende diretamente de um fluxo básico de entrada, processamento e saída para cada pedido realizado.

### K04 - Variáveis, constantes, tipos de dados e atribuição

- representa medidas, preços, área e totais por variáveis adequadas;
- sustenta atualizações de estado ao longo do processamento do pedido;
- exige compatibilidade entre tipos de dados e valores manipulados.

**Justificativa de mobilização na tarefa:** a solução depende de variáveis numéricas para armazenar dimensões, área, preços e total do pedido.

### K05 - Expressões aritméticas, relacionais e lógicas

- apoia a construção de cálculos necessários à composição do valor final;
- permite formular comparações e regras de inclusão de serviços;
- conecta operações numéricas a decisões computacionais.

**Justificativa de mobilização na tarefa:** a atividade envolve cálculo de área, composição de custos e uso de condições para tratar escolhas e combinações de serviços.

### K06 - Estruturas condicionais

- seleciona caminhos alternativos de execução conforme modelo e serviços escolhidos;
- permite tratar casos mutuamente exclusivos e combinações válidas do problema;
- sustenta a coerência entre regra do enunciado e comportamento do programa.

**Justificativa de mobilização na tarefa:** a task exige decidir computacionalmente entre modelos, serviços e cenários de processamento do pedido.

### K07 - Estruturas de repetição

- controla o reinício do ciclo de atendimento para novos pedidos;
- permite repetir blocos de instruções até critério explícito de parada;
- sustenta processamento iterativo coerente em programas interativos.

**Justificativa de mobilização na tarefa:** o enunciado exige que, após cada pedido, o programa pergunte se o atendente deseja processar um novo pedido e reinicie o fluxo quando necessário.

## 3. Identificação de Objetivos de Aprendizagem

### LO1
**Representar dados de entrada, processamento e saída em programas introdutórios de forma coerente com o problema.**  
**K associados:** (K03, K04)

### LO2
**Organizar programas em fluxo verificável de entrada, processamento e saída para resolver problemas de pedidos simples.**  
**K associados:** (K03, K04)

### LO3
**Formular e aplicar condições para selecionar alternativas de processamento e composição de saídas em problemas com múltiplas escolhas.**  
**K associados:** (K05, K06, K04)

### LO4
**Realizar processamento numérico simples para calcular resultados derivados e consolidar valores finais em programas introdutórios.**  
**K associados:** (K03, K04, K05)

### LO5
**Controlar a repetição de um ciclo completo de atendimento com critério explícito de continuação ou encerramento.**  
**K associados:** (K07, K03, K06)

## 4. Definição de Competências

### 4.1 Competência Geral

**Desenvolver programas estruturados em linguagem introdutória, articulando representação de dados, fluxo sequencial, cálculo, decisão condicional e repetição controlada para resolver problemas computacionais verificáveis.**

### 4.2 Especificações de Competências

## CT17.1

**Título da Competência**  
**Estruturar programas introdutórios com fluxo verificável de entrada, processamento e saída**

**Descrição Textual**  
Capacidade de organizar programas introdutórios em linguagem C a partir de entradas definidas, processamento coerente e saídas observáveis, preservando consistência entre dados, estado do programa e resultados exibidos.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO2)
- K mobilizados (Núcleo): (K03, K04)

**Especificação de Conhecimentos**
- **K03:** organiza a solução em sequência de leitura, processamento e exibição. **Justificativa de evidência:** o fluxo do programa é diretamente observável no artefato executável.
- **K04:** representa e atualiza os dados necessários ao processamento do pedido. **Justificativa de evidência:** as variáveis e atribuições aparecem de forma direta no código e nos resultados.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência exige implementação operacional de fluxo sequencial e uso funcional de variáveis em um programa executável.

**Pareamento Conhecimento-Habilidade**

K03 / Aplicar → executar o fluxo de leitura, processamento e exibição de resultados de forma verificável.  
Verbos de Bloom: executar, programar, usar

K04 / Aplicar → implementar variáveis e atribuições compatíveis com o papel computacional de cada dado.  
Verbos de Bloom: implementar, manipular, operar

**Especificação de Disposições**  
- precisão na representação dos dados  
- atenção à ordem de execução  
- rigor na consistência das saídas  

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT17.1 | Estruturar programas introdutórios com fluxo verificável de entrada, processamento e saída | precisão na representação dos dados; atenção à ordem de execução; rigor na consistência das saídas | K03 | executar o fluxo de leitura, processamento e exibição de resultados de forma verificável |
| CT17.1 | Estruturar programas introdutórios com fluxo verificável de entrada, processamento e saída | precisão na representação dos dados; atenção à ordem de execução; rigor na consistência das saídas | K04 | implementar variáveis e atribuições compatíveis com o papel computacional de cada dado |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a task exige a construção efetiva de um programa funcional que organize entradas, processamento e saídas. Essa competência é central porque a evidência principal está no comportamento executável do artefato.

## CT17.2

**Título da Competência**  
**Controlar o processamento de programas por meio de decisões condicionais coerentes**

**Descrição Textual**  
Capacidade de traduzir regras expressas em linguagem natural para condições computacionais e utilizá-las para selecionar comportamentos alternativos de execução em programas estruturados.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3)
- K mobilizados (Núcleo): (K05, K06, K04)

**Especificação de Conhecimentos**
- **K05:** estrutura comparações e expressões lógicas que sustentam decisões do programa. **Justificativa de evidência:** as regras de escolha do modelo e dos serviços se materializam em condições explicitamente programadas.
- **K06:** seleciona caminhos de execução distintos conforme as regras do problema. **Justificativa de evidência:** a correção das saídas depende diretamente dos ramos condicionais implementados.
- **K04:** sustenta o uso consistente das variáveis envolvidas nas escolhas e nos resultados derivados. **Justificativa de evidência:** os valores manipulados em cada caso podem ser verificados no código e nas saídas.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Analisar**, pois a competência exige relacionar regras do problema a condições computacionais e distinguir cenários de processamento com cobertura coerente.

**Pareamento Conhecimento-Habilidade**

K05 / Analisar → estruturar comparações e expressões lógicas coerentes com as regras de decisão do problema.  
Verbos de Bloom: analisar, estruturar, relacionar

K06 / Analisar → distinguir e organizar caminhos alternativos de execução sem lacunas de cobertura.  
Verbos de Bloom: discriminar, distinguir, articular

K04 / Aplicar → manipular variáveis de controle e de resultado de acordo com o ramo selecionado.  
Verbos de Bloom: manipular, implementar, operar

**Especificação de Disposições**  
- consistência lógica  
- atenção às regras do problema  
- rigor na cobertura dos casos  


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT17.2 | Controlar o processamento de programas por meio de decisões condicionais coerentes | consistência lógica; atenção às regras do problema; rigor na cobertura dos casos | K05 | estruturar comparações e expressões lógicas coerentes com as regras de decisão do problema |
| CT17.2 | Controlar o processamento de programas por meio de decisões condicionais coerentes | consistência lógica; atenção às regras do problema; rigor na cobertura dos casos | K06 | distinguir e organizar caminhos alternativos de execução sem lacunas de cobertura |
| CT17.2 | Controlar o processamento de programas por meio de decisões condicionais coerentes | consistência lógica; atenção às regras do problema; rigor na cobertura dos casos | K04 | manipular variáveis de controle e de resultado de acordo com o ramo selecionado |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a composição do pedido depende de decisões explícitas sobre modelo de piso e serviços adicionais. A competência é ativada porque o estudante precisa converter regras do enunciado em condições computacionais consistentes.

## CT17.3

**Título da Competência**  
**Realizar processamento numérico simples para consolidar resultados derivados em programas de pedidos**

**Descrição Textual**  
Capacidade de combinar leitura de dados, cálculos derivados e atualização de resultados para produzir saídas numéricas consistentes em programas estruturados.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO4)
- K mobilizados (Núcleo): (K03, K04, K05)

**Especificação de Conhecimentos**
- **K03:** encadeia leitura, cálculo e produção do resultado final. **Justificativa de evidência:** o cálculo do pedido só é verificável quando integrado ao fluxo completo do programa.
- **K04:** sustenta armazenamento de medidas, custos e totais. **Justificativa de evidência:** os resultados intermediários e finais dependem de variáveis corretamente utilizadas.
- **K05:** apoia cálculos de área e composição de custos. **Justificativa de evidência:** a correção do valor final depende diretamente das expressões implementadas.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência envolve uso operacional de cálculos, tipos e atualização de estado para produzir um resultado final verificável.

**Pareamento Conhecimento-Habilidade**

K03 / Aplicar → executar a sequência de cálculos e exibição de resultados de forma consistente.  
Verbos de Bloom: executar, realizar, usar

K04 / Aplicar → implementar variáveis numéricas adequadas ao armazenamento de medidas, subtotais e total final.  
Verbos de Bloom: implementar, armazenar, operar

K05 / Aplicar → calcular resultados derivados por meio de expressões aritméticas e lógicas coerentes.  
Verbos de Bloom: calcular, computar, resolver

**Especificação de Disposições**  
- precisão algorítmica  
- rigor computacional  
- atenção à consistência numérica  

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT17.3 | Realizar processamento numérico simples para consolidar resultados derivados em programas de pedidos | precisão algorítmica; rigor computacional; atenção à consistência numérica | K03 | executar a sequência de cálculos e exibição de resultados de forma consistente |
| CT17.3 | Realizar processamento numérico simples para consolidar resultados derivados em programas de pedidos | precisão algorítmica; rigor computacional; atenção à consistência numérica | K04 | implementar variáveis numéricas adequadas ao armazenamento de medidas, subtotais e total final |
| CT17.3 | Realizar processamento numérico simples para consolidar resultados derivados em programas de pedidos | precisão algorítmica; rigor computacional; atenção à consistência numérica | K05 | calcular resultados derivados por meio de expressões aritméticas e lógicas coerentes |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o objetivo operacional da task é compor o preço final do pedido a partir de dados de entrada e regras de cálculo. A competência é central porque a correção do artefato depende diretamente da consolidação numérica produzida.

## CT17.4

**Título da Competência**  
**Gerenciar repetição controlada de ciclos completos de atendimento em programas interativos**

**Descrição Textual**  
Capacidade de estruturar laços de repetição para executar novamente um fluxo completo de processamento, preservando reinicialização adequada de dados e critério explícito de continuação ou encerramento.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO5)
- K mobilizados (Núcleo): (K07, K03, K06)

**Especificação de Conhecimentos**
- **K07:** controla a repetição do ciclo de atendimento. **Justificativa de evidência:** o enunciado exige explicitamente a possibilidade de processar um novo pedido após o término do atual.
- **K03:** reexecuta o fluxo completo de entrada, processamento e saída em cada iteração. **Justificativa de evidência:** cada novo pedido demanda um novo ciclo computacional completo.
- **K06:** define a continuidade ou o encerramento do atendimento a partir de condição explícita. **Justificativa de evidência:** a repetição depende de decisão de continuar ou interromper o processo.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência requer implementar laço funcional com critério de parada e reinício coerente do processamento.

**Pareamento Conhecimento-Habilidade**

K07 / Aplicar → implementar laço de repetição que permita reprocessar pedidos com critério explícito de parada.  
Verbos de Bloom: implementar, iterar, usar

K03 / Aplicar → executar novamente o fluxo completo de entrada, processamento e saída em cada ciclo de atendimento.  
Verbos de Bloom: executar, realizar, usar

K06 / Aplicar → aplicar condição de continuação ou encerramento ao controle do atendimento.  
Verbos de Bloom: aplicar, implementar, usar

**Especificação de Disposições**  
- atenção à estabilidade do fluxo  
- cuidado com reinicialização de dados  
- disciplina no controle do encerramento  

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT17.4 | Gerenciar repetição controlada de ciclos completos de atendimento em programas interativos | atenção à estabilidade do fluxo; cuidado com reinicialização de dados; disciplina no controle do encerramento | K07 | implementar laço de repetição que permita reprocessar pedidos com critério explícito de parada |
| CT17.4 | Gerenciar repetição controlada de ciclos completos de atendimento em programas interativos | atenção à estabilidade do fluxo; cuidado com reinicialização de dados; disciplina no controle do encerramento | K03 | executar novamente o fluxo completo de entrada, processamento e saída em cada ciclo de atendimento |
| CT17.4 | Gerenciar repetição controlada de ciclos completos de atendimento em programas interativos | atenção à estabilidade do fluxo; cuidado com reinicialização de dados; disciplina no controle do encerramento | K06 | aplicar condição de continuação ou encerramento ao controle do atendimento |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o problema exige explicitamente o reprocessamento de novos pedidos após a conclusão do atendimento anterior. Essa competência é ativada porque o laço integra o comportamento esperado do programa.