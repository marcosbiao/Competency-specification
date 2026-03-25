# RELATÓRIO CSP - Autoria de Competências

## Introdução

Este relatório situa a Tarefa 17 na fase de Autoria de Competências, com foco na explicitação de conhecimentos, objetivos de aprendizagem e competências mobilizados por uma atividade introdutória de programação. A tarefa solicita a implementação de um sistema de cadastro de funcionários com operações de inclusão, consulta, alteração, exclusão e relatório.

A atividade produz evidências observáveis em código, execução e saídas verificáveis. Do ponto de vista formativo, ela mobiliza representação de dados, controle de fluxo, manipulação de coleções homogêneas e escolha de estruturas adequadas ao problema.

## 1. Análise da Entidade Instrucional

### Título

Sistema de cadastro de funcionários

### Descrição

A tarefa propõe a construção de um programa capaz de armazenar e manipular dados cadastrais de funcionários, contemplando campos numéricos e textuais. O sistema deve oferecer operações de cadastro, busca por código ou nome, alteração, exclusão e emissão de relatório.

Trata-se de uma atividade de implementação que exige manter coerência entre representação dos dados, lógica de busca e atualização do estado do programa ao longo de múltiplas operações.

### Processo de Desenvolvimento da Solução

1. Interpretar os campos obrigatórios e as operações previstas.
2. Definir uma forma de representação dos registros em memória.
3. Organizar o fluxo principal do programa e o menu de opções.
4. Implementar inclusão e consulta de registros.
5. Implementar alteração e exclusão preservando a consistência dos dados.
6. Gerar relatório e verificar o comportamento com cenários de teste.

### Resultados Esperados

1. Programa executável com as operações solicitadas.
2. Armazenamento coerente de dados numéricos e textuais.
3. Consulta, alteração, exclusão e relatório com saídas verificáveis.
4. Evidências de teste mostrando o funcionamento das operações principais.

### Contexto de Aquisição

Curso de Introdução à Programação, em atividade individual, com realização em laboratório ou ambiente equivalente. A avaliação incide sobre o código, a execução do sistema e a coerência entre entradas, processamento e saídas.

### Perfil do Público-Alvo

Estudantes em etapa inicial de formação em programação, com domínio introdutório de variáveis, entrada e saída, estruturas de decisão, repetição e manipulação básica de vetores, matrizes e strings. A principal demanda pedagógica é integrar esses conhecimentos em uma solução mais extensa e coerente.

### Nível de Proficiência (critérios e dimensões)

| Nível | Representação dos dados | Operações do sistema | Controle de fluxo e consistência | Verificabilidade das saídas |
|---|---|---|---|---|
| **N1 - Inicial** | Representa apenas parte dos campos ou com inconsistências de tipo | Implementa poucas operações ou com falhas frequentes | Fluxo incompleto ou sujeito a estados incorretos | Saídas pouco informativas ou inconsistentes |
| **N2 - Intermediário** | Representa todos os campos, com organização funcional, mas ainda frágil | Implementa as operações principais, com cobertura parcial de casos | Fluxo funcional, mas com lacunas em atualização, exclusão ou repetição | Saídas suficientes para conferência básica |
| **N3 - Proficiente** | Representa todos os campos de modo coerente e acessível às operações | Implementa todas as operações previstas com comportamento consistente | Fluxo estável, preservando o estado do cadastro nas operações | Saídas claras para consulta e relatório |
| **N4 - Avançado** | Representa os dados com boa organização e favorece manutenção e legibilidade | Implementa todas as operações com boa robustez e clareza de uso | Fluxo estável, com tratamento cuidadoso de casos e melhor verificabilidade | Saídas claras, organizadas e favoráveis à validação do comportamento |

## 2. Seleção e Enumeração de Conhecimentos

### K01 - Modelo de execução e noção de estado (paradigma imperativo)

1. Compreensão de que o programa evolui por mudanças de estado durante a execução.
2. Leitura do efeito de atribuições, atualizações e ordem das operações.
3. Observação de como o cadastro muda após inclusão, alteração e exclusão.

**Justificativa de mobilização:** o sistema mantém registros ao longo do tempo de execução e exige controle explícito do estado do cadastro.

### K02 - Variáveis, constantes e tipos primitivos

1. Uso coerente de identificadores para armazenar dados simples.
2. Escolha de tipos adequados para código, salário, status e demais campos.
3. Manutenção de atribuições compatíveis com o papel de cada dado.

**Justificativa de mobilização:** a solução depende de campos numéricos e textuais representados de modo consistente.

### K04 - Expressões lógicas e condições

1. Construção de condições booleanas para decidir ações do sistema.
2. Formulação de critérios de busca, atualização e exclusão.
3. Interpretação correta de verdade e falsidade em regras operacionais.

**Justificativa de mobilização:** a consulta por código ou nome e a seleção de operações dependem de condições logicamente corretas.

### K05 - Estrutura sequencial e E/S básica

1. Organização do fluxo entrada → processamento → saída.
2. Leitura de dados cadastrais e apresentação de respostas verificáveis.
3. Encadeamento coerente de comandos em cada operação.

**Justificativa de mobilização:** todas as funcionalidades do sistema dependem de interação por entrada e saída e de sequência operacional clara.

### K06 - Estruturas de seleção

1. Escolha de ramos de execução conforme opções do sistema.
2. Tratamento de casos distintos para consulta, alteração, exclusão e relatório.
3. Cobertura dos caminhos necessários ao comportamento esperado.

**Justificativa de mobilização:** o programa precisa selecionar ações diferentes conforme a opção escolhida e o resultado das buscas.

### K07 - Estruturas de repetição

1. Repetição de operações enquanto o sistema estiver em uso.
2. Percorrimento de coleções para localizar e listar registros.
3. Controle de parada e iteração com comportamento previsível.

**Justificativa de mobilização:** o sistema pressupõe repetição tanto para navegação no menu quanto para busca e emissão de relatórios.

### K08 - Vetores e matrizes em C

1. Representação e acesso posicional a coleções indexadas.
2. Percorrimento, atualização e consulta de múltiplos registros.
3. Organização de dados em estruturas homogêneas manipuláveis por índice.

**Justificativa de mobilização:** o cadastro envolve múltiplos funcionários e requer armazenamento e acesso sistemático aos registros em memória.

### K09 - Strings em C

1. Declaração, leitura e escrita de dados textuais.
2. Comparação e manipulação básica de nomes, cargos, telefones e status.
3. Tratamento de campos textuais em consulta e apresentação.

**Justificativa de mobilização:** parte central do problema envolve nomes e outros campos textuais, além de consulta por nome e geração de relatórios legíveis.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Organizar dados cadastrais em estruturas homogêneas compatíveis com campos numéricos e textuais.  
**K associados:** K02, K08, K09

**LO2.** Implementar um fluxo interativo com menu, repetição controlada e encerramento seguro.  
**K associados:** K05, K06, K07

**LO3.** Localizar, alterar, excluir e listar registros preservando a consistência do cadastro.  
**K associados:** K01, K04, K06, K07, K08, K09

**LO4.** Justificar a escolha das estruturas de armazenamento e acesso em função das operações pedidas pela tarefa.  
**K associados:** K01, K02, K08, K09

## 4. Definição de Competências

### 4.1 Competência Geral

Implementar programas introdutórios que organizem dados em memória, controlem o fluxo de execução com segurança e escolham estruturas adequadas ao problema, produzindo comportamento verificável em operações de cadastro, consulta e manutenção.

### 4.2 Especificações de Competências

#### CT17.1

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras

**Descrição Textual**  
Organizar a execução de programas que dependem de repetição, controle de continuidade e encerramento seguro, garantindo que o fluxo principal e os percursos sobre dados ocorram de forma previsível e verificável.

**Cobertura e rastreabilidade**  
1. LOs cobertos: LO2, LO3  
2. K mobilizados: K05, K06, K07

**Pareamento Conhecimento-Habilidade**

- K05 / Aplicar / implementar → estruturar rotinas de entrada, processamento e saída em fluxo contínuo
- K06 / Aplicar / selecionar → direcionar a execução conforme a opção escolhida e o resultado das condições
- K07 / Aplicar / iterar → controlar laços, percursos e condições de parada de forma segura

**Descrição das habilidades associadas**
1. Manter o sistema em execução enquanto houver interação prevista.
2. Percorrer registros para consulta, alteração, exclusão e relatório.
3. Encerrar a repetição em condições coerentes, sem comprometer o estado do programa.

**Disposições**
1. Organização do fluxo de resolução.
2. Atenção à continuidade e ao encerramento da execução.
3. Disciplina na cobertura dos casos operacionais.

**Tabela-resumo**

| Código | Competência | Conhecimento | Nível de Bloom | Verbo | Habilidade |
|---|---|---|---|---|---|
| CT17.1 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | K05 | Aplicar | implementar | estruturar rotinas de entrada, processamento e saída em fluxo contínuo |
| CT17.1 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | K06 | Aplicar | selecionar | direcionar a execução conforme a opção escolhida e o resultado das condições |
| CT17.1 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | K07 | Aplicar | iterar | controlar laços, percursos e condições de parada de forma segura |

#### CT17.2

**Título da Competência**  
Representar e processar coleções homogêneas com vetores e matrizes

**Descrição Textual**  
Representar conjuntos de dados em coleções homogêneas e operar sobre eles por meio de acesso indexado, percorrimento, atualização e apresentação de resultados, preservando consistência entre posições e campos relacionados.

**Cobertura e rastreabilidade**  
1. LOs cobertos: LO1, LO3  
2. K mobilizados: K02, K08, K09

**Pareamento Conhecimento-Habilidade**

- K02 / Aplicar / definir → utilizar variáveis e tipos compatíveis com cada campo cadastral
- K08 / Aplicar / organizar → armazenar, acessar e atualizar registros em vetores e matrizes
- K09 / Aplicar / manipular → tratar campos textuais em operações de busca, alteração e exibição

**Descrição das habilidades associadas**
1. Armazenar múltiplos registros de forma coerente em memória.
2. Processar dados indexados para localizar, atualizar e listar informações.
3. Integrar campos textuais e numéricos no processamento do cadastro.

**Disposições**
1. Precisão na representação dos dados.
2. Atenção à correspondência entre índices e campos.
3. Cuidado com a consistência das informações armazenadas.

**Tabela-resumo**

| Código | Competência | Conhecimento | Nível de Bloom | Verbo | Habilidade |
|---|---|---|---|---|---|
| CT17.2 | Representar e processar coleções homogêneas com vetores e matrizes | K02 | Aplicar | definir | utilizar variáveis e tipos compatíveis com cada campo cadastral |
| CT17.2 | Representar e processar coleções homogêneas com vetores e matrizes | K08 | Aplicar | organizar | armazenar, acessar e atualizar registros em vetores e matrizes |
| CT17.2 | Representar e processar coleções homogêneas com vetores e matrizes | K09 | Aplicar | manipular | tratar campos textuais em operações de busca, alteração e exibição |

#### CT17.3

**Título da Competência**  
Selecionar estruturas adequadas ao problema e justificar as escolhas

**Descrição Textual**  
Analisar as demandas de um problema computacional e selecionar formas de representação compatíveis com os dados e operações requeridos, justificando a adequação das estruturas escolhidas em função do comportamento esperado do programa.

**Cobertura e rastreabilidade**  
1. LOs cobertos: LO1, LO4  
2. K mobilizados: K01, K02, K08, K09

**Pareamento Conhecimento-Habilidade**

- K01 / Analisar / relacionar → explicar como a estrutura escolhida sustenta o estado do cadastro ao longo da execução
- K02 / Analisar / compatibilizar → associar tipos e variáveis às características dos campos do problema
- K08 / Analisar / selecionar → escolher coleções indexadas compatíveis com armazenamento e acesso aos registros
- K09 / Analisar / justificar → defender a representação adotada para campos textuais e consultas por nome

**Descrição das habilidades associadas**
1. Relacionar operações solicitadas e forma de armazenamento dos dados.
2. Escolher estruturas coerentes com consulta, alteração, exclusão e relatório.
3. Justificar tecnicamente as decisões de representação adotadas na solução.

**Disposições**
1. Rigor na análise do problema.
2. Coerência nas decisões de modelagem.
3. Clareza ao justificar escolhas técnicas.

**Tabela-resumo**

| Código | Competência | Conhecimento | Nível de Bloom | Verbo | Habilidade |
|---|---|---|---|---|---|
| CT17.3 | Selecionar estruturas adequadas ao problema e justificar as escolhas | K01 | Analisar | relacionar | explicar como a estrutura escolhida sustenta o estado do cadastro ao longo da execução |
| CT17.3 | Selecionar estruturas adequadas ao problema e justificar as escolhas | K02 | Analisar | compatibilizar | associar tipos e variáveis às características dos campos do problema |
| CT17.3 | Selecionar estruturas adequadas ao problema e justificar as escolhas | K08 | Analisar | selecionar | escolher coleções indexadas compatíveis com armazenamento e acesso aos registros |
| CT17.3 | Selecionar estruturas adequadas ao problema e justificar as escolhas | K09 | Analisar | justificar | defender a representação adotada para campos textuais e consultas por nome |

