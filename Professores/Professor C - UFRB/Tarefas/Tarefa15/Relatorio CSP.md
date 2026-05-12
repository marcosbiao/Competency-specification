# RELATÓRIO CSP - AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do Competency Specification Process e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa introdutória de programação voltada ao cálculo do salário de um veterinário a partir dos serviços realizados no mês. A atividade exige registro de múltiplos atendimentos, aplicação de regras distintas de comissão, processamento iterativo e emissão de um relatório final verificável. Por isso, produz evidências observáveis no código, na organização dos dados, no comportamento computacional e na saída consolidada.

A tarefa sustenta adequadamente o modelo **Conhecimento-Habilidade-Disposição (K-S-D)** porque mobiliza conhecimentos centrais da disciplina, requer habilidades técnicas diretamente avaliáveis e permite explicitar disposições compatíveis com precisão, consistência lógica e rigor computacional. A modelagem abaixo prioriza reuso, rastreabilidade explícita e controle de granularidade, sem criar conhecimentos fora do catálogo da disciplina.

## 1. Análise da Entidade Instrucional

### Título

**Sistema de cálculo de salário de veterinário com relatório mensal de serviços**

### Descrição

A tarefa requer a implementação de um programa capaz de registrar até 20 serviços realizados por um veterinário em um período mensal, armazenar dados essenciais de cada atendimento, aplicar a comissão correspondente ao tipo de serviço e produzir um relatório final contendo a listagem dos procedimentos e o salário do profissional. As evidências principais estão na correção do processamento, na consistência do armazenamento e na verificabilidade do relatório produzido.

### Processo de Desenvolvimento da Solução

1. Identificar os dados exigidos pelo problema e o limite máximo de atendimentos.
2. Definir como representar e armazenar, ao longo da execução, os dados de cada serviço.
3. Organizar a solução em fluxo de entrada, processamento e saída.
4. Processar cada atendimento informado, associando o código do serviço à regra de comissão correspondente.
5. Atualizar os valores parciais e o acumulado final do salário.
6. Exibir um relatório consolidado com os dados processados e o resultado final.

### Resultados Esperados

- programa executável ou código-fonte funcional;
- registro consistente de até 20 atendimentos;
- cálculo correto do valor devido ao veterinário em cada serviço;
- soma final coerente das comissões;
- relatório final com identificação do profissional, quantidade de atendimentos, listagem dos serviços e salário final;
- justificativa breve e tecnicamente coerente sobre o processamento adotado.

### Contexto de Aquisição

- **Título da Task:** Sistema de cálculo de salário de veterinário com relatório mensal de serviços
- **Nível/Curso:** nível introdutório em curso da área de Computação
- **Componente Curricular:** Programação de Computadores I
- **Contexto:** atividade prática individual, adequada a laboratório de programação ou avaliação prática escrita e computacional
- **Avaliação:** análise do código, do tratamento dos dados, da coerência do cálculo, da organização do relatório e da justificativa breve

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em etapa inicial de formação em programação, já familiarizados com noções introdutórias de algoritmo, variáveis, entrada e saída e estruturas condicionais simples. A tarefa é adequada para estudantes que necessitam consolidar o processamento de múltiplas ocorrências, o uso de coleções indexadas, a aplicação de regras por seleção condicional e a geração de saídas verificáveis.

### Nível de Proficiência (critérios e dimensões)

| Nível | Representação dos dados | Processamento iterativo | Aplicação das regras de comissão | Consolidação e relatório |
|---|---|---|---|---|
| **N1 - Inicial** | identifica apenas parte dos dados necessários ou os representa de modo inconsistente | não controla adequadamente a repetição ou ignora o limite de ocorrências | não associa corretamente códigos e comissões | apresenta saída incompleta ou pouco verificável |
| **N2 - Intermediário** | representa os dados principais, mas com fragilidades de tipo, organização ou armazenamento | percorre as ocorrências com inconsistências pontuais de controle | distingue parte dos casos, mas ainda com falhas de decisão ou cálculo | apresenta saída compreensível, mas com lacunas de organização |
| **N3 - Proficiente** | representa corretamente os dados necessários ao processamento e à saída | processa corretamente as ocorrências previstas e respeita o limite da tarefa | aplica corretamente as regras de decisão e cálculo em todos os casos previstos | produz relatório completo, coerente e verificável |
| **N4 - Avançado** | representa os dados com clareza, precisão e organização estável para reutilização | organiza o processamento iterativo de forma clara, consistente e verificável | integra decisão e cálculo com alta consistência e sem ambiguidades | produz relatório claro, consistente e tecnicamente bem estruturado |

## 2. Seleção e Enumeração de Conhecimentos

**K02: Algoritmos e formas de representação**
- compreensão de algoritmo como sequência ordenada e não ambígua de passos;
- organização do problema em etapas computacionais estáveis;
- representação da solução de forma logicamente estruturada.
- **Justificativa de mobilização na tarefa:** a atividade exige transformar uma descrição textual de regras de negócio em uma solução computacional organizada e verificável.

**K03: Estrutura sequencial, entrada, processamento e saída**
- organização do programa em leitura de dados, processamento e exibição de resultados;
- encadeamento coerente entre dados de entrada, cálculos intermediários e saída final;
- produção de resultados observáveis ao término da execução.
- **Justificativa de mobilização na tarefa:** a solução depende de fluxo sequencial claro para ler dados, processar atendimentos e emitir o relatório mensal.

**K04: Variáveis, constantes, tipos de dados e atribuição**
- uso de variáveis para representar dados de entrada, resultados parciais e acumulados;
- seleção de tipos de dados compatíveis com quantidades, códigos e valores monetários;
- atualização consistente de valores ao longo da execução.
- **Justificativa de mobilização na tarefa:** o problema exige armazenar e atualizar dados numéricos e simbólicos durante o processamento dos serviços.

**K05: Expressões aritméticas, relacionais e lógicas**
- construção de expressões para cálculo de valores derivados;
- formulação de comparações e condições associadas às regras do problema;
- combinação coerente de operações numéricas e critérios lógicos.
- **Justificativa de mobilização na tarefa:** a tarefa exige calcular comissão e salário final, além de relacionar códigos de serviço às regras correspondentes.

**K06: Estruturas condicionais**
- seleção de caminhos de execução a partir de condições;
- tratamento de casos alternativos associados às regras do domínio;
- cobertura coerente de cenários mutuamente excludentes.
- **Justificativa de mobilização na tarefa:** o programa precisa distinguir tipos de serviço e aplicar a comissão correta em cada caso.

**K07: Estruturas de repetição**
- processamento iterativo de múltiplas ocorrências;
- controle do número de iterações e do critério de parada;
- uso de contagem e acumulação em tarefas com vários dados.
- **Justificativa de mobilização na tarefa:** a atividade envolve registrar e processar vários serviços realizados ao longo do mês, até o limite estabelecido.

**K08: Vetores e matrizes**
- armazenamento de coleções homogêneas em posições indexadas;
- leitura, atualização e recuperação de dados associados a várias ocorrências;
- percorrimento sequencial de coleções para processamento e listagem.
- **Justificativa de mobilização na tarefa:** a listagem final dos atendimentos pressupõe armazenamento recuperável dos dados de cada ocorrência ao longo do processamento.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Estruturar soluções introdutórias como sequência verificável de entrada, processamento e saída para problemas com múltiplas ocorrências.  
**K associados:** (K02, K03, K07)

**LO2.** Representar e armazenar dados necessários ao processamento de várias ocorrências de um problema por meio de variáveis e coleções indexadas.  
**K associados:** (K04, K07, K08)

**LO3.** Aplicar regras de decisão em programas introdutórios a partir de condições formuladas com base nos dados do problema.  
**K associados:** (K05, K06, K04)

**LO4.** Calcular valores derivados e acumulados a partir de dados de entrada, atualizando o estado do programa de modo consistente.  
**K associados:** (K03, K04, K05, K07)

**LO5.** Produzir saídas consolidadas e verificáveis a partir dos dados processados e armazenados durante a execução.  
**K associados:** (K03, K08, K04)

## 4. Definição de Competências

### 4.1 Competência Geral 

**Implementar soluções computacionais introdutórias que integrem representação de dados, processamento iterativo, decisão condicional, cálculo e apresentação verificável de resultados.**

### 4.2 Especificações de Competências

## CT15.1

**Título da Competência**  
**Estruturar soluções algorítmicas para processar múltiplas ocorrências com fluxo verificável**

**Descrição Textual**  
Capacidade de organizar programas introdutórios que tratem múltiplas ocorrências de dados por meio de um fluxo coerente de entrada, processamento iterativo e saída final verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1)
- K mobilizados (Núcleo): (K03, K07)

**Especificação de Conhecimentos**
- **K03:** organização do programa como sequência de leitura, processamento e saída. **Justificativa de evidência:** a competência é observada diretamente na estrutura funcional do artefato produzido.
- **K07:** uso de repetição para tratar várias ocorrências de dados. **Justificativa de evidência:** a tarefa exige processar diversos serviços ao longo do mês, respeitando um limite de ocorrências.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência requer implementação operacional de fluxo sequencial e processamento iterativo em um programa funcional.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → organizar o programa em uma sequência funcional de entrada, processamento e saída para múltiplas ocorrências.  
Verbos de Bloom: executar, programar, organizar

K07 / Aplicar → processar iterativamente um conjunto limitado de ocorrências com controle coerente do ciclo de execução.  
Verbos de Bloom: iterar, executar, operar

**Especificação de Disposições**  
- atenção à ordem lógica do processamento;
- rigor no controle das iterações;
- consistência na execução do fluxo do programa.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.1 | Estruturar soluções algorítmicas para processar múltiplas ocorrências com fluxo verificável | atenção à ordem lógica do processamento; rigor no controle das iterações; consistência na execução do fluxo do programa | K03 | organizar o programa em uma sequência funcional de entrada, processamento e saída para múltiplas ocorrências |
| CT15.1 | Estruturar soluções algorítmicas para processar múltiplas ocorrências com fluxo verificável | atenção à ordem lógica do processamento; rigor no controle das iterações; consistência na execução do fluxo do programa | K07 | processar iterativamente um conjunto limitado de ocorrências com controle coerente do ciclo de execução |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa exige a construção efetiva de um programa que leia vários dados, processe cada ocorrência e produza um resultado final verificável. O fluxo sequencial e o uso de repetição são centrais na evidência observável do artefato.

## CT15.2

**Título da Competência**  
**Representar e manter coleções de dados para processamento e recuperação posterior**

**Descrição Textual**  
Capacidade de selecionar e utilizar estruturas de armazenamento indexado para manter dados de múltiplas ocorrências disponíveis para processamento e apresentação posterior.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2)
- K mobilizados (Núcleo): (K04, K08)

**Especificação de Conhecimentos**
- **K04:** representação de dados por variáveis, tipos e atribuições coerentes. **Justificativa de evidência:** a competência é observada na forma como os dados de cada ocorrência são armazenados e mantidos ao longo da execução.
- **K08:** uso de coleções indexadas para armazenar várias ocorrências. **Justificativa de evidência:** a listagem final dos serviços requer recuperação dos dados armazenados durante o processamento.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência exige selecionar e usar estruturas básicas de armazenamento adequadas ao comportamento esperado da solução.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → representar dados de entrada e resultados parciais em variáveis compatíveis com seu papel computacional.  
Verbos de Bloom: implementar, manipular, usar

K08 / Aplicar → armazenar e recuperar dados de múltiplas ocorrências por meio de coleções indexadas adequadas ao processamento.  
Verbos de Bloom: armazenar, operar, recuperar

**Especificação de Disposições**  
- precisão na representação dos dados;
- cuidado com consistência entre armazenamento e recuperação;
- organização no tratamento das ocorrências.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.2 | Representar e manter coleções de dados para processamento e recuperação posterior | precisão na representação dos dados; cuidado com consistência entre armazenamento e recuperação; organização no tratamento das ocorrências | K04 | representar dados de entrada e resultados parciais em variáveis compatíveis com seu papel computacional |
| CT15.2 | Representar e manter coleções de dados para processamento e recuperação posterior | precisão na representação dos dados; cuidado com consistência entre armazenamento e recuperação; organização no tratamento das ocorrências | K08 | armazenar e recuperar dados de múltiplas ocorrências por meio de coleções indexadas adequadas ao processamento |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a produção do relatório final exige que os dados de cada atendimento permaneçam disponíveis para recuperação posterior. Por isso, a representação e manutenção de coleções de dados são ativadas como parte central da solução.


## CT15.3

**Título da Competência**  
**Aplicar regras condicionais e cálculo para produzir valores derivados em programas introdutórios**

**Descrição Textual**  
Capacidade de transformar regras do problema em condições computacionais e combiná-las com expressões numéricas para gerar resultados derivados corretos.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3, LO4)
- K mobilizados (Núcleo): (K04, K05, K06)

**Especificação de Conhecimentos**
- **K04:** representação de dados por variáveis, tipos e atribuições coerentes. **Justificativa de evidência:** a competência é observada na atualização consistente dos valores parciais e acumulados produzidos durante o processamento.
- **K05:** formulação de expressões aritméticas, relacionais e lógicas para cálculo e decisão. **Justificativa de evidência:** a tarefa evidencia diretamente a associação entre código de serviço, cálculo da comissão e formação do salário.
- **K06:** seleção de caminhos alternativos de execução. **Justificativa de evidência:** o valor devido ao profissional depende da escolha correta do caminho condicional associado a cada tipo de serviço.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência exige converter regras do domínio em condições e cálculos implementáveis e consistentes.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → atualizar variáveis de resultado de modo consistente durante o processamento de cada ocorrência e no acumulado final.  
Verbos de Bloom: manipular, operar, usar

K05 / Aplicar → formular expressões numéricas e condições coerentes com as regras de transformação dos dados de entrada.  
Verbos de Bloom: calcular, computar, resolver

K06 / Aplicar → selecionar corretamente o comportamento de processamento associado a cada caso previsto no problema.  
Verbos de Bloom: aplicar, executar, programar

**Especificação de Disposições**  
- consistência lógica;
- precisão aritmética;
- atenção às regras explícitas do problema.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.3 | Aplicar regras condicionais e cálculo para produzir valores derivados em programas introdutórios | consistência lógica; precisão aritmética; atenção às regras explícitas do problema | K04 | atualizar variáveis de resultado de modo consistente durante o processamento de cada ocorrência e no acumulado final |
| CT15.3 | Aplicar regras condicionais e cálculo para produzir valores derivados em programas introdutórios | consistência lógica; precisão aritmética; atenção às regras explícitas do problema | K05 | formular expressões numéricas e condições coerentes com as regras de transformação dos dados de entrada |
| CT15.3 | Aplicar regras condicionais e cálculo para produzir valores derivados em programas introdutórios | consistência lógica; precisão aritmética; atenção às regras explícitas do problema | K06 | selecionar corretamente o comportamento de processamento associado a cada caso previsto no problema |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica/construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o núcleo funcional da atividade está em relacionar tipos de serviço a regras diferentes de comissão e traduzir essa regra em cálculo executável. A competência é ativada pela necessidade de decidir e calcular corretamente em cada ocorrência.

## CT15.4

**Título da Competência**  
**Consolidar e apresentar resultados computacionais em formato de relatório verificável**

**Descrição Textual**  
Capacidade de organizar a saída de programas introdutórios de modo a apresentar dados processados, resultados intermediários relevantes e síntese final de forma clara e verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO5)
- K mobilizados (Núcleo): (K03, K08)

**Especificação de Conhecimentos**
- **K03:** articulação entre processamento e exibição de resultados. **Justificativa de evidência:** a competência se manifesta na apresentação do relatório final e na verificabilidade da saída produzida.
- **K08:** recuperação de dados armazenados para listagem final. **Justificativa de evidência:** a saída exige percorrer os dados das ocorrências já registradas e apresentá-los de forma consolidada.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência requer uso operacional da estrutura do programa e das coleções de dados para produzir uma saída organizada.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → apresentar resultados processados em uma saída final coerente com o fluxo de execução do programa.  
Verbos de Bloom: executar, apresentar, usar

K08 / Aplicar → recuperar dados armazenados em coleções indexadas para compor uma listagem final verificável.  
Verbos de Bloom: recuperar, armazenar, operar

**Especificação de Disposições**  
- clareza na apresentação da informação;
- rigor na verificabilidade da saída;
- organização na consolidação dos resultados.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.4 | Consolidar e apresentar resultados computacionais em formato de relatório verificável | clareza na apresentação da informação; rigor na verificabilidade da saída; organização na consolidação dos resultados | K03 | apresentar resultados processados em uma saída final coerente com o fluxo de execução do programa |
| CT15.4 | Consolidar e apresentar resultados computacionais em formato de relatório verificável | clareza na apresentação da informação; rigor na verificabilidade da saída; organização na consolidação dos resultados | K08 | recuperar dados armazenados em coleções indexadas para compor uma listagem final verificável |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: justificatória/construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade não se encerra no cálculo interno. Ela exige um relatório final que torne o processamento auditável e verificável, o que ativa a competência de consolidação e apresentação de resultados como parte central do desempenho esperado.
