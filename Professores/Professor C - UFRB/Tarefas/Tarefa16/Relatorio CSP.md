# RELATÓRIO CSP - AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de Autoria de Competências do CSP e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados pela TASK16. A tarefa solicita a implementação, em linguagem C, de um programa capaz de processar pedidos de bubble tea, considerando escolha de base, seleção de complementos, categoria do cliente, aplicação de desconto e possibilidade de reinício do atendimento. As evidências são diretamente observáveis no código-fonte, nas saídas produzidas, na coerência do fluxo de execução e na justificativa breve associada ao funcionamento implementado.

A tarefa sustenta adequadamente o modelo Conhecimento-Habilidade-Disposição porque mobiliza conhecimentos centrais da programação estruturada, exige habilidades técnicas avaliáveis em artefatos concretos e envolve disposições relacionadas a rigor, consistência e verificabilidade. A modelagem apresentada prioriza rastreabilidade explícita entre K, LO e CT, evita redundância desnecessária e busca formular elementos reutilizáveis em outras tarefas introdutórias da mesma disciplina.

## 1. Análise da Entidade Instrucional

### Título

**Processamento de pedidos de bubble tea com cálculo de valor final**

### Descrição

A tarefa requer a construção de um programa em C para processar um pedido por vez, com exatamente uma base, nenhum ou vários complementos, aplicação de desconto conforme o perfil do cliente e exibição do valor final formatado. Além do processamento de um pedido, a solução deve permitir reiniciar o fluxo completo quando houver solicitação de novo atendimento. As evidências principais estão na correção do processamento, na integridade das saídas e na coerência entre as regras do enunciado e o comportamento do programa.

### Processo de Desenvolvimento da Solução

1. Interpretar as regras do pedido, identificando entradas, alternativas de escolha, descontos e saídas esperadas.
2. Representar computacionalmente os dados do problema com variáveis e tipos compatíveis.
3. Organizar a solução em um fluxo básico de entrada, processamento e saída.
4. Implementar decisões para tratar base, complementos e categoria do cliente de forma consistente.
5. Controlar a repetição do atendimento para permitir novo pedido sem perda da lógica do processo.
6. Validar a saída final, incluindo resumo textual do pedido e valor formatado, e registrar tecnicamente os resultados obtidos.

### Resultados Esperados

- programa em C funcional para processamento do pedido;
- saída contendo resumo textual das escolhas realizadas e valor final formatado;
- tratamento correto das regras de desconto previstas;
- reexecução do atendimento quando solicitado;
- relatório técnico descrevendo o desenvolvimento e os resultados observados;
- justificativa breve coerente com o funcionamento implementado.

### Contexto de Aquisição

- **Curso:** componente introdutório de programação em cursos de Computação
- **Organização:** preferencialmente individual
- **Ambiente:** laboratório de programação ou contexto de avaliação prática supervisionada
- **Avaliação:** análise do código, das saídas produzidas, da cobertura dos casos previstos e da coerência da documentação técnica

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de formação em programação estruturada, com contato prévio ou simultâneo com entrada e saída, variáveis, expressões, condicionais e laços. Trata-se de um perfil que necessita consolidar a tradução de enunciados textuais em soluções computacionais executáveis, bem como a organização do fluxo lógico de programas simples com múltiplas regras operacionais.

### Nível de Proficiência

| Nível | Representação de dados | Controle condicional | Controle de repetição | Saída e verificabilidade |
|---|---|---|---|---|
| **N1 - Inicial** | identifica apenas parte dos dados necessários ou usa tipos de forma inconsistente | implementa decisões incompletas ou incorretas | não controla adequadamente o reinício do atendimento | apresenta saídas incompletas ou pouco legíveis |
| **N2 - Intermediário** | representa os dados principais, com pequenas fragilidades de organização | trata parte das alternativas, mas com lacunas de cobertura | implementa repetição com funcionamento parcial | apresenta saídas compreensíveis, porém com baixa verificabilidade |
| **N3 - Proficiente** | representa dados e estados do pedido de forma coerente e funcional | trata corretamente as regras de escolha e desconto previstas | reinicia corretamente o processo completo quando solicitado | apresenta resumo e valor final de modo verificável e coerente |
| **N4 - Avançado** | representa dados com clareza técnica, consistência e boa organização estrutural | organiza decisões com precisão, clareza e estabilidade lógica | controla repetição com clareza, previsibilidade e sem inconsistências de estado | apresenta saídas tecnicamente consistentes, claras e bem organizadas |

## 2. Seleção e Enumeração de Conhecimentos

**K02 - Algoritmos e formas de representação**

- compreender o problema como sequência ordenada de etapas computacionais.
- organizar regras e decisões em uma lógica de processamento verificável.
- traduzir um enunciado operacional para uma estrutura algorítmica executável.

**Justificativa de mobilização na tarefa:** a atividade exige converter regras textuais de pedido, desconto e reinício do atendimento em uma solução algorítmica organizada.

**K03 - Estrutura sequencial, entrada, processamento e saída**

- organizar programas segundo um fluxo de leitura, processamento e apresentação de resultados.
- manter ordem lógica entre recebimento de dados, cálculo e exibição da saída.
- produzir resultados compatíveis com o estado final do processamento.

**Justificativa de mobilização na tarefa:** o problema depende diretamente de uma sequência clara de entrada dos dados do pedido, processamento das escolhas e saída formatada.

**K04 - Variáveis, constantes, tipos de dados e atribuição**

- representar dados do problema por identificadores e tipos compatíveis.
- armazenar estados intermediários e finais do processamento.
- atualizar valores de forma coerente ao longo da execução.

**Justificativa de mobilização na tarefa:** a solução precisa representar base, complementos, descontos e total do pedido por meio de variáveis e atribuições consistentes.

**K05 - Expressões aritméticas, relacionais e lógicas**

- construir expressões para totalização de valores e comparação de condições.
- formular regras relacionais e lógicas para distinção entre cenários de execução.
- utilizar operadores de modo coerente com cálculos e decisões do problema.

**Justificativa de mobilização na tarefa:** o programa requer acumular preços, comparar categorias e aplicar regras condicionadas para produzir o valor final correto.

**K06 - Estruturas condicionais**

- selecionar caminhos alternativos de execução com base em regras explícitas do problema.
- distinguir casos mutuamente excludentes ou complementares no processamento.
- controlar ações específicas para cada escolha relevante do pedido.

**Justificativa de mobilização na tarefa:** a tarefa exige decisões para base, complementos, categoria do cliente e aplicação de descontos, todas dependentes de seleção condicional.

**K07 - Estruturas de repetição**

- repetir blocos de processamento conforme um critério de continuidade.
- reiniciar etapas do programa quando necessário.
- manter coerência entre inicialização, repetição e encerramento do fluxo.

**Justificativa de mobilização na tarefa:** o enunciado exige explicitamente a possibilidade de processar um novo pedido e impõe o uso de pelo menos uma estrutura de repetição.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Organizar soluções introdutórias em uma sequência verificável de entrada, processamento e saída para problemas de atendimento simples.

**K associados:** (K02, K03)

### LO2

Representar dados e estados do processamento com variáveis, tipos e atribuições coerentes com o comportamento esperado do programa.

**K associados:** (K03, K04)

### LO3

Construir expressões aritméticas, relacionais e lógicas para totalizar valores e sustentar regras operacionais de decisão.

**K associados:** (K04, K05)

### LO4

Aplicar estruturas condicionais para selecionar comportamentos alternativos em função de escolhas e categorias previstas no problema.

**K associados:** (K05, K06)

### LO5

Utilizar estruturas de repetição para reexecutar fluxos completos de processamento quando houver continuidade da interação.

**K associados:** (K03, K07)

### LO6

Produzir saídas textuais verificáveis e tecnicamente coerentes com os dados processados e com as regras implementadas.

**K associados:** (K03, K04, K05)

## 4. Definição de Competências

### 4.1 Competência Geral

Implementar programas introdutórios em linguagem estruturada para processar entradas, aplicar regras de decisão, controlar repetições e produzir saídas verificáveis em problemas operacionais simples.


### 4.2 Especificações de Competências

## CT16.1

**Título da Competência**  
Estruturar programas introdutórios com fluxo verificável de entrada, processamento e saída

**Descrição Textual**  
Capacidade de organizar programas simples de forma sequencial, representando adequadamente os dados necessários ao processamento e produzindo saídas coerentes com o estado final da execução.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO2, LO6)
- K mobilizados (Núcleo): (K03, K04)

**Especificação de Conhecimentos**
- **K03:** organiza a sequência de leitura, processamento e apresentação de resultados. **Justificativa de evidência:** o fluxo do programa é diretamente observável no código e na ordem das saídas.
- **K04:** representa e atualiza dados do pedido ao longo da execução. **Justificativa de evidência:** a consistência das variáveis pode ser verificada pelo funcionamento do programa e pelos resultados apresentados.

**Alinhamento com a Taxonomia de Bloom**

Predomina **Aplicar**, porque a competência requer uso operacional de estruturas sequenciais, variáveis e saídas em um programa executável e verificável.

**Pareamento Conhecimento-Habilidade**

K03 / Aplicar → estruturar o fluxo de entrada, processamento e saída de modo verificável no programa.  
Verbos de Bloom: executar, organizar, apresentar

K04 / Aplicar → declarar, atribuir e atualizar dados do processamento de forma coerente com o comportamento esperado.  
Verbos de Bloom: implementar, manipular, usar

**Especificação de Disposições**  
- organização do fluxo lógico
- precisão na representação dos dados
- cuidado com a verificabilidade da saída

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.1 | Estruturar programas introdutórios com fluxo verificável de entrada, processamento e saída | organização do fluxo lógico; precisão na representação dos dados; cuidado com a verificabilidade da saída | K03 | estruturar o fluxo de entrada, processamento e saída de modo verificável no programa |
| CT16.1 | Estruturar programas introdutórios com fluxo verificável de entrada, processamento e saída | organização do fluxo lógico; precisão na representação dos dados; cuidado com a verificabilidade da saída | K04 | declarar, atribuir e atualizar dados do processamento de forma coerente com o comportamento esperado |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade exige a construção efetiva de um programa funcional, com dados de entrada, processamento e saída observáveis. Sem essa competência, não é possível materializar o comportamento mínimo esperado do artefato computacional.

## CT16.2

**Título da Competência**  
Controlar o fluxo de execução por regras condicionais em programas introdutórios

**Descrição Textual**  
Capacidade de traduzir regras explícitas de um problema em decisões computacionais coerentes, selecionando caminhos alternativos de execução conforme condições previamente definidas.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3, LO4, LO6)
- K mobilizados (Núcleo): (K05, K06)

**Especificação de Conhecimentos**
- **K05:** formula expressões aritméticas, relacionais e lógicas associadas ao comportamento do programa. **Justificativa de evidência:** as regras de totalização e desconto dependem diretamente da correção dessas expressões.
- **K06:** seleciona caminhos alternativos de execução segundo as condições do problema. **Justificativa de evidência:** a solução exige escolhas condicionadas para tratar casos distintos previstos no enunciado.

**Alinhamento com a Taxonomia de Bloom**

Predomina **Aplicar**, pois a competência requer transformar regras explicitadas no problema em estruturas condicionais operacionais dentro de um programa funcional.

**Pareamento Conhecimento-Habilidade**

K05 / Aplicar → construir expressões numéricas e lógicas coerentes com as regras de totalização e desconto do processamento.  
Verbos de Bloom: calcular, computar, operar

K06 / Aplicar → implementar decisões condicionais que distingam corretamente os cenários previstos no problema.  
Verbos de Bloom: aplicar, executar, programar

**Especificação de Disposições**  
- consistência lógica
- atenção às regras do problema
- rigor na cobertura de casos

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.2 | Controlar o fluxo de execução por regras condicionais em programas introdutórios | consistência lógica; atenção às regras do problema; rigor na cobertura de casos | K05 | construir expressões numéricas e lógicas coerentes com as regras de totalização e desconto do processamento |
| CT16.2 | Controlar o fluxo de execução por regras condicionais em programas introdutórios | consistência lógica; atenção às regras do problema; rigor na cobertura de casos | K06 | implementar decisões condicionais que distingam corretamente os cenários previstos no problema |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a lógica do pedido depende de seleção entre alternativas e aplicação de regras específicas para desconto e composição da saída. A competência é central porque os casos do problema só se tornam executáveis quando traduzidos em decisão condicional correta.

## CT16.3

**Título da Competência**  
Gerenciar repetição de processamento em programas interativos simples

**Descrição Textual**  
Capacidade de utilizar estruturas de repetição para controlar a continuidade da interação, reiniciando fluxos completos de processamento de forma estável e verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO5, LO6)
- K mobilizados (Núcleo): (K07, K03)

**Especificação de Conhecimentos**
- **K07:** controla a reexecução de blocos do programa conforme critério de continuidade. **Justificativa de evidência:** o enunciado exige explicitamente novo processamento de pedido por meio de repetição.
- **K03:** reorganiza o fluxo completo a cada iteração, preservando entrada, processamento e saída. **Justificativa de evidência:** a repetição só é adequada quando o ciclo completo de atendimento é reiniciado com consistência.

**Alinhamento com a Taxonomia de Bloom**

Predomina **Aplicar**, porque a competência exige uso funcional de laços para reprocessar interações dentro de um programa estruturado.

**Pareamento Conhecimento-Habilidade**

K07 / Aplicar → implementar laços que permitam reiniciar o atendimento completo quando houver continuidade da interação.  
Verbos de Bloom: executar, iterar, programar

K03 / Aplicar → reorganizar o ciclo de entrada, processamento e saída a cada nova execução do pedido.  
Verbos de Bloom: executar, organizar, usar

**Especificação de Disposições**  
- persistência na validação do fluxo
- atenção ao controle de estado
- cuidado com consistência entre iterações

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.3 | Gerenciar repetição de processamento em programas interativos simples | persistência na validação do fluxo; atenção ao controle de estado; cuidado com consistência entre iterações | K07 | implementar laços que permitam reiniciar o atendimento completo quando houver continuidade da interação |
| CT16.3 | Gerenciar repetição de processamento em programas interativos simples | persistência na validação do fluxo; atenção ao controle de estado; cuidado com consistência entre iterações | K03 | reorganizar o ciclo de entrada, processamento e saída a cada nova execução do pedido |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o enunciado exige a possibilidade de novo pedido após cada processamento, o que torna a repetição uma condição estrutural da solução. A competência é ativada diretamente pelo artefato programado e pelo comportamento observado em múltiplas execuções.

## CT16.4

**Título da Competência**  
Implementar soluções estruturadas que integrem seleção, totalização e reexecução de tarefas

**Descrição Textual**  
Capacidade de conceber e implementar soluções introdutórias completas em linguagem estruturada, articulando organização algorítmica, regras condicionais, cálculo e repetição em um artefato funcional e verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO3, LO4, LO5, LO6)
- K mobilizados (Núcleo): (K02, K05, K06, K07)

**Especificação de Conhecimentos**
- **K02:** organiza a solução como algoritmo executável e coerente com as regras do problema. **Justificativa de evidência:** a estrutura global do programa mostra se o estudante foi capaz de transformar o enunciado em procedimento computacional funcional.
- **K05:** articula expressões de cálculo e de controle lógico no mesmo processamento. **Justificativa de evidência:** a correção do total final e das condições de operação depende do uso integrado dessas expressões.
- **K06:** viabiliza a seleção entre comportamentos alternativos no decorrer da solução. **Justificativa de evidência:** diferentes escolhas do pedido exigem caminhos distintos de execução dentro do mesmo artefato.
- **K07:** sustenta a reexecução completa do processo quando houver novo atendimento. **Justificativa de evidência:** o programa só atende plenamente ao enunciado quando integra repetição ao restante da lógica de processamento.

**Alinhamento com a Taxonomia de Bloom**

Predomina **Criar**, de modo defensável, porque a tarefa requer a implementação de uma solução completa em C que combine, em um único artefato funcional, organização algorítmica, cálculo, decisão e repetição.

**Pareamento Conhecimento-Habilidade**

K02 / Criar → conceber a organização algorítmica global da solução de modo compatível com as regras e os resultados esperados.  
Verbos de Bloom: construir, desenvolver, planejar

K05 / Aplicar → combinar expressões numéricas e lógicas para sustentar o processamento integrado do programa.  
Verbos de Bloom: calcular, computar, operar

K06 / Aplicar → implementar decisões coerentes com alternativas de processamento presentes no fluxo completo da solução.  
Verbos de Bloom: aplicar, executar, programar

K07 / Aplicar → integrar a repetição ao programa de modo a permitir reexecução estável do atendimento.  
Verbos de Bloom: executar, iterar, programar

**Especificação de Disposições**  
- rigor computacional
- integração consistente entre partes da solução
- atenção à verificabilidade do artefato final
- cuidado com estabilidade do comportamento executável

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.4 | Implementar soluções estruturadas que integrem seleção, totalização e reexecução de tarefas | rigor computacional; integração consistente entre partes da solução; atenção à verificabilidade do artefato final; cuidado com estabilidade do comportamento executável | K02 | conceber a organização algorítmica global da solução de modo compatível com as regras e os resultados esperados |
| CT16.4 | Implementar soluções estruturadas que integrem seleção, totalização e reexecução de tarefas | rigor computacional; integração consistente entre partes da solução; atenção à verificabilidade do artefato final; cuidado com estabilidade do comportamento executável | K05 | combinar expressões numéricas e lógicas para sustentar o processamento integrado do programa |
| CT16.4 | Implementar soluções estruturadas que integrem seleção, totalização e reexecução de tarefas | rigor computacional; integração consistente entre partes da solução; atenção à verificabilidade do artefato final; cuidado com estabilidade do comportamento executável | K06 | implementar decisões coerentes com alternativas de processamento presentes no fluxo completo da solução |
| CT16.4 | Implementar soluções estruturadas que integrem seleção, totalização e reexecução de tarefas | rigor computacional; integração consistente entre partes da solução; atenção à verificabilidade do artefato final; cuidado com estabilidade do comportamento executável | K07 | integrar a repetição ao programa de modo a permitir reexecução estável do atendimento |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a task não pede apenas partes isoladas de programação, mas uma solução completa e executável. Por isso, a competência integradora é ativada pelo artefato final, que precisa reunir algoritmo, cálculo, decisão, repetição e saída verificável em um único programa funcional.
