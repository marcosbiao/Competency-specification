# RELATÓRIO CSP — Autoria de Competências


## Introdução

Este relatório situa a tarefa na fase de **Autoria de Competências** do Competency Specification Process (CSP), com foco na especificação rastreável de conhecimentos, objetivos de aprendizagem e competências mobilizados pela atividade. A tarefa solicita a implementação de um programa que leia uma matriz 5x5 e determine o elemento minimax, definido como o menor elemento da linha em que se encontra o maior elemento da matriz.

A atividade produz evidências observáveis porque exige um artefato executável, com entrada estruturada, varredura da matriz, atualização de referências durante o processamento e saída final verificável. Além do valor produzido, a tarefa também permite observar coerência de estado, uso de laços, manipulação de índices e justificativa para eventual ambiguidade de desempate.

No modelo K–S–D, a tarefa sustenta uma decomposição sem redundância porque mobiliza um conjunto delimitado de conhecimentos do catálogo da disciplina, articula objetivos de aprendizagem reutilizáveis em tarefas semelhantes de processamento matricial e elicita competências estáveis da área de programação imperativa introdutória.

## 1. Análise da Entidade Instrucional

### 1.1 Título

Determinação do elemento minimax em matriz 5x5

### 1.2 Descrição

A entidade instrucional propõe a construção de um programa que receba, por leitura, os 25 valores de uma matriz bidimensional e determine um resultado derivado por critério composto. A solução depende de percorrimento sistemático da matriz, identificação de um elemento de referência global, localização da linha associada e determinação de um novo valor nessa linha. O produto central é um programa com saída verificável e justificativa breve quando houver necessidade de explicitar critério de desempate.

### 1.3 Processo de Desenvolvimento da Solução

1. Organizar a estrutura de entrada para preenchimento completo da matriz 5x5.
2. Definir variáveis de controle compatíveis com valor, linha de referência e estado da busca.
3. Percorrer a matriz para localizar o maior elemento e registrar a linha correspondente.
4. Processar a linha de referência para identificar o menor elemento nela contido.
5. Exibir o resultado final e manter coerência da solução em cenários sem ambiguidade e em cenários com possível empate do maior valor.

### 1.4 Resultados Esperados

1. Código-fonte funcional.
2. Matriz preenchida por leitura.
3. Processamento consistente para localização do maior elemento e da linha associada.
4. Determinação do elemento minimax.
5. Saída do programa com resultado verificável.
6. Justificativa curta, quando necessária, para o tratamento de empate do maior elemento.

### 1.5 Contexto de Aquisição

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### 1.6 Perfil do Público-Alvo

Trata-se de estudantes em etapa inicial da formação em programação, com contato introdutório com linguagem C, estruturas sequenciais, estruturas de repetição, seleção e arranjos bidimensionais. Pressupõe-se familiaridade básica com leitura e escrita de dados, declaração de variáveis, noção de índice e organização de laços aninhados. A principal necessidade formativa é consolidar o processamento de matrizes com critério de busca composto, sem perder a coerência do estado do programa.

### 1.7 Nível de Proficiência (critérios e dimensões)

| Nível | Leitura e armazenamento da matriz | Percorrimento e controle de estado | Aplicação do critério minimax | Verificabilidade do artefato |
|---|---|---|---|---|
| **N1 — Inicial** | Preenche a matriz de forma parcial ou com inconsistências de índice. | Percorre a matriz com falhas de cobertura ou atualização. | Identifica apenas parte do critério ou produz resultado incorreto. | Entrega pouco legível ou sem evidência suficiente. |
| **N2 — Intermediário** | Preenche a matriz completa, mas com organização ainda frágil. | Percorre a matriz, mas com controle de estado pouco robusto. | Compreende o critério, mas com falhas em casos limítrofes. | Entrega funcional, mas com justificativa insuficiente. |
| **N3 — Proficiente** | Preenche a matriz corretamente com fluxo estável de leitura. | Percorre integralmente a matriz e mantém referências coerentes. | Determina corretamente o resultado para entradas regulares. | Entrega funcional e verificável, com saída coerente. |
| **N4 — Avançado** | Estrutura a leitura com clareza, consistência e boa verificabilidade. | Percorre a matriz com controle preciso, sem redundância e com rastreabilidade clara. | Determina corretamente o resultado e explicita de forma consistente a regra adotada em caso de empate. | Entrega funcional, verificável e com justificativa técnica clara e concisa. |

## 2. Seleção e Enumeração de Conhecimentos 

**K01 — Modelo de execução e noção de estado (paradigma imperativo)**

1. Descrição
   1. Compreensão de que o programa evolui por mudanças sucessivas de estado.
   2. Relação entre atribuições, atualização de variáveis e resultado produzido.
   3. Leitura operacional do fluxo de execução em problemas iterativos.

2. Justificativa de mobilização na tarefa  
A identificação do maior elemento, o registro da linha associada e a posterior determinação do menor elemento dependem de atualizações consistentes do estado do programa ao longo da execução.

**K02 — Variáveis, constantes e tipos primitivos**

1. Descrição
   1. Declaração e uso coerente de variáveis para dados numéricos e controle.
   2. Compatibilidade entre tipo da variável e papel desempenhado na solução.
   3. Uso de identificadores para armazenar valores e índices.

2. Justificativa de mobilização na tarefa  
A solução requer variáveis para armazenar elementos lidos, referências de busca, índices de linha e coluna e resultado final.

**K04 — Expressões lógicas e condições**

1. Descrição
   1. Construção de comparações entre valores.
   2. Interpretação correta de condições booleanas em decisões de busca.
   3. Relação entre regra do problema e condição implementada.

2. Justificativa de mobilização na tarefa  
A tarefa exige comparações para identificar máximos, mínimos e situações em que a referência de busca deve ser atualizada.

**K05 — Estrutura sequencial e E/S básica**

1. Descrição
   1. Organização do fluxo entrada, processamento e saída.
   2. Leitura e apresentação de dados de modo verificável.
   3. Encadeamento sequencial de comandos em solução executável.

2. Justificativa de mobilização na tarefa  
O programa precisa receber os 25 valores da matriz, processá-los e exibir um resultado numérico final de forma verificável.

**K06 — Estruturas de seleção**

1. Descrição
   1. Uso de decisões para alterar o caminho de execução.
   2. Atualização de referências quando critérios são satisfeitos.
   3. Cobertura consistente de casos de comparação.

2. Justificativa de mobilização na tarefa  
A busca pelo maior elemento e pelo menor elemento na linha selecionada depende de decisões condicionais implementadas durante a execução.

**K07 — Estruturas de repetição**

1. Descrição
   1. Uso de laços para percorrer coleções de dados.
   2. Controle de contagem e parada em varreduras completas.
   3. Organização de laços simples e aninhados.

2. Justificativa de mobilização na tarefa  
A leitura da matriz e sua inspeção sistemática requerem iteração controlada sobre linhas e colunas.

**K08 — Vetores e matrizes em C**

1. Descrição
   1. Representação de dados homogêneos em arranjos bidimensionais.
   2. Acesso por índices de linha e coluna.
   3. Percorrimento, leitura e processamento de elementos em matriz.

2. Justificativa de mobilização na tarefa  
O enunciado exige diretamente o preenchimento e o processamento de uma matriz 5x5, tornando esse conhecimento central e diretamente evidenciável.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Implementar a leitura e o armazenamento completo de dados em matriz bidimensional, preservando a correspondência entre posição e valor.

**K associados:** (K02, K05, K07, K08)

### LO2

Aplicar estruturas de repetição para percorrer integralmente uma matriz, mantendo controle consistente de índices e referências de busca.

**K associados:** (K01, K02, K07, K08)

### LO3

Aplicar decisões condicionais com expressões lógicas corretas para atualizar máximos, mínimos e linhas de referência durante o processamento.

**K associados:** (K01, K04, K06, K08)

### LO4

Produzir saída verificável para o valor minimax determinado, explicitando o critério adotado quando houver ambiguidade de interpretação.

**K associados:** (K01, K04, K05, K06)

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver programas introdutórios capazes de representar, percorrer e processar coleções bidimensionais, aplicando estruturas de decisão e repetição para produzir resultados verificáveis.

**BNCC:** não aplicável ao contexto deste relatório, por se tratar de atividade situada em componente curricular de graduação.

### 4.2 Especificações de Competências

## CT08.1

**Título da Competência**  
Manipular matrizes bidimensionais por leitura, indexação e acesso posicional consistente

**Descrição Textual**  
Implementar programas introdutórios que recebam dados em matrizes, preservem a correspondência entre índices e valores e organizem o acesso posicional necessário ao processamento.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO2)
2. K mobilizados: (K02, K05, K07, K08)

**Especificação de Conhecimentos**
1. **K02:** variáveis e índices devem ser compatíveis com o papel de armazenamento e controle, pois a leitura da matriz depende dessa coerência.
2. **K05:** a tarefa evidencia a organização sequencial da leitura, do processamento inicial e da saída verificável.
3. **K07:** a cobertura integral da matriz depende de laços com contagem e parada consistentes.
4. **K08:** a matriz bidimensional é o objeto central de representação e acesso posicional da atividade.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, pois a competência envolve implementação de leitura, armazenamento e acesso operacional a uma estrutura matricial.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar e utilizar variáveis e índices compatíveis com a leitura e o armazenamento dos dados da matriz.  
Verbos de Bloom: implementar, usar, operar

K05 / Aplicar → organizar o fluxo de entrada, preenchimento e saída de modo verificável.  
Verbos de Bloom: implementar, executar, operar

K07 / Aplicar → executar laços de preenchimento e percorrimento com parada garantida e cobertura integral da matriz.  
Verbos de Bloom: iterar, executar, operar

K08 / Aplicar → manipular posições de uma matriz bidimensional preservando a correspondência entre índice e valor.  
Verbos de Bloom: implementar, manipular, usar


**Especificação de Disposições**
1. Atenção à integridade posicional dos dados armazenados.
2. Rigor no controle da cobertura de leitura.
3. Cuidado com a verificabilidade do fluxo de execução.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT08.1 | Manipular matrizes bidimensionais por leitura, indexação e acesso posicional consistente | Atenção à integridade posicional dos dados armazenados | K02 | Declarar e utilizar variáveis e índices compatíveis com a leitura e o armazenamento dos dados da matriz |
| CT08.1 | Manipular matrizes bidimensionais por leitura, indexação e acesso posicional consistente | Rigor no controle da cobertura de leitura | K05 | Organizar o fluxo de entrada, preenchimento e saída de modo verificável |
| CT08.1 | Manipular matrizes bidimensionais por leitura, indexação e acesso posicional consistente | Rigor no controle da cobertura de leitura | K07 | Executar laços de preenchimento e percorrimento com parada garantida e cobertura integral da matriz |
| CT08.1 | Manipular matrizes bidimensionais por leitura, indexação e acesso posicional consistente | Atenção à integridade posicional dos dados armazenados | K08 | Manipular posições de uma matriz bidimensional preservando a correspondência entre índice e valor |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa  
Sem essa competência, a tarefa não alcança o processamento do critério minimax. A leitura integral da matriz e o acesso posicional consistente são condições estruturais da execução observável do programa.

## CT08.2

**Título da Competência**  
Controlar o fluxo com decisões (if/else), formulando expressões lógicas corretas

**Descrição Textual**  
Aplicar estruturas de seleção para comparar valores, atualizar referências de processamento e manter coerência entre a regra do problema e as condições implementadas.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO3, LO4)
2. K mobilizados: (K01, K04, K06, K08)

**Especificação de Conhecimentos**
1. **K01:** a competência evidencia o acompanhamento do estado da busca e a atualização coerente de referências durante o processamento.
2. **K04:** a tarefa exige formulação correta de expressões lógicas para comparar elementos e sustentar decisões.
3. **K06:** a atualização de máximos, mínimos e linhas de referência depende de decisões condicionais consistentes.
4. **K08:** as decisões são aplicadas sobre uma estrutura bidimensional, em que a posição do elemento influencia o resultado derivado.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, com componente de **Analisar**, pois a competência exige traduzir a regra do problema em condições corretas e usá-las para controlar o fluxo.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → rastrear atualizações de estado associadas à manutenção de valores e linhas de referência durante o processamento.  
Verbos de Bloom: rastrear, examinar, atualizar

K04 / Aplicar → formular expressões lógicas corretas para comparar valores e sustentar decisões de atualização.  
Verbos de Bloom: aplicar, implementar, usar

K06 / Aplicar → controlar o fluxo com decisões condicionais coerentes com o critério de busca definido pelo problema.  
Verbos de Bloom: implementar, resolver, operar

K08 / Aplicar → relacionar decisões condicionais ao acesso posicional de elementos em matriz bidimensional.  
Verbos de Bloom: usar, manipular, implementar


**Especificação de Disposições**
1. Precisão na formulação de condições.
2. Atenção à coerência entre regra formal e decisão executada.
3. Disciplina no rastreamento do estado do programa.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT08.2 | Controlar o fluxo com decisões (if/else), formulando expressões lógicas corretas | Disciplina no rastreamento do estado do programa | K01 | Rastrear atualizações de estado associadas à manutenção de valores e linhas de referência durante o processamento |
| CT08.2 | Controlar o fluxo com decisões (if/else), formulando expressões lógicas corretas | Precisão na formulação de condições | K04 | Formular expressões lógicas corretas para comparar valores e sustentar decisões de atualização |
| CT08.2 | Controlar o fluxo com decisões (if/else), formulando expressões lógicas corretas | Atenção à coerência entre regra formal e decisão executada | K06 | Controlar o fluxo com decisões condicionais coerentes com o critério de busca definido pelo problema |
| CT08.2 | Controlar o fluxo com decisões (if/else), formulando expressões lógicas corretas | Atenção à coerência entre regra formal e decisão executada | K08 | Relacionar decisões condicionais ao acesso posicional de elementos em matriz bidimensional |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: analítica
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa  
A determinação do minimax depende de comparações sucessivas e de atualização condicional de referências. Por isso, a competência de decisão é diretamente diagnóstica nesta atividade.

## CT08.3

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores, variáveis de referência e paradas seguras

**Descrição Textual**  
Aplicar estruturas de repetição para percorrer coleções bidimensionais, manter variáveis de controle e referência atualizadas e garantir cobertura completa da estrutura sem perda de coerência do estado.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO2, LO3)
2. K mobilizados: (K01, K02, K07, K08)

**Especificação de Conhecimentos**
1. **K01:** a competência evidencia o acompanhamento do estado iterativo da solução durante a varredura da matriz.
2. **K02:** variáveis de índice, referência e resultado precisam ser mantidas com tipos e papéis coerentes.
3. **K07:** a tarefa depende de laços controlados para percorrer linhas e colunas com parada garantida.
4. **K08:** o percorrimento repetitivo incide diretamente sobre uma matriz 5x5, exigindo acesso ordenado por índice.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio de **Aplicar**, pois a competência envolve organizar e executar laços que sustentam o processamento da matriz.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → examinar a evolução do estado do programa durante iterações sucessivas sobre a matriz.  
Verbos de Bloom: examinar, rastrear, atualizar

K02 / Aplicar → utilizar variáveis de controle e referência coerentes com os papéis de índice, valor corrente e resultado parcial.  
Verbos de Bloom: implementar, usar, operar

K07 / Aplicar → controlar o fluxo com repetição por meio de contadores e condições de parada seguras em varreduras matriciais.  
Verbos de Bloom: iterar, executar, operar

K08 / Aplicar → percorrer uma matriz bidimensional de modo sistemático para localizar elementos e linhas de referência.  
Verbos de Bloom: manipular, implementar, usar

**Especificação de Disposições**
1. Disciplina na cobertura integral da estrutura.
2. Cuidado com a consistência entre índices e posições.
3. Atenção à estabilidade do estado durante as iterações.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT08.3 | Controlar o fluxo com repetição utilizando contadores, variáveis de referência e paradas seguras | Atenção à estabilidade do estado durante as iterações | K01 | Examinar a evolução do estado do programa durante iterações sucessivas sobre a matriz |
| CT08.3 | Controlar o fluxo com repetição utilizando contadores, variáveis de referência e paradas seguras | Cuidado com a consistência entre índices e posições | K02 | Utilizar variáveis de controle e referência coerentes com os papéis de índice, valor corrente e resultado parcial |
| CT08.3 | Controlar o fluxo com repetição utilizando contadores, variáveis de referência e paradas seguras | Disciplina na cobertura integral da estrutura | K07 | Controlar o fluxo com repetição por meio de contadores e condições de parada seguras em varreduras matriciais |
| CT08.3 | Controlar o fluxo com repetição utilizando contadores, variáveis de referência e paradas seguras | Cuidado com a consistência entre índices e posições | K08 | Percorrer uma matriz bidimensional de modo sistemático para localizar elementos e linhas de referência |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa  
A matriz só pode ser processada por percorrimento sistemático de linhas e colunas. Assim, o controle do fluxo por repetição é central para a leitura, a busca do maior elemento e a determinação do menor elemento na linha correspondente.

