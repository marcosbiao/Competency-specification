# RELATÓRIO CSP - TASK10

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do Competency Specification Process, com foco na especificação de conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa introdutória de programação. A tarefa solicita a implementação de uma solução para armazenamento e consulta de preços de automóveis em uma estrutura indexada por múltiplas dimensões, incluindo código, modelo, cor, ano e combustível.

Trata-se de uma entidade instrucional que produz evidências observáveis e verificáveis, porque o estudante precisa construir um artefato executável capaz de preencher a estrutura, recuperar valores a partir de uma chave composta e controlar o término das consultas. Essas evidências podem ser inspecionadas diretamente no comportamento do programa, nas entradas e saídas apresentadas e na justificativa da organização adotada.

A tarefa suporta o modelo **Conhecimento-Habilidade-Disposição (K-S-D)** sem redundância, pois mobiliza um subconjunto coeso do catálogo da disciplina: representação de dados, entrada e saída, repetição, condições, arranjos indexados e enumerações. O recorte permite distinguir com clareza quais conhecimentos são diretamente evidenciados pelos produtos da tarefa e quais capacidades estáveis da disciplina são efetivamente elicitadas.

## 1. Análise da Entidade Instrucional

### Título

Consulta de preços em arranjo multidimensional de automóveis

### Descrição

A tarefa requer a implementação de um programa que armazene preços de automóveis em uma estrutura multidimensional indexada por múltiplos atributos e, posteriormente, responda a consultas sucessivas a partir da leitura dos identificadores de cada automóvel. Além do armazenamento e da recuperação do preço, o enunciado exige um mecanismo explícito de controle para encerramento das consultas.

### Processo de Desenvolvimento da Solução

1. Interpretar as dimensões da estrutura e a função de cada índice no problema.
2. Definir uma representação compatível para o preço e para os identificadores numéricos e categóricos.
3. Organizar o preenchimento completo da estrutura a partir de leituras do teclado.
4. Implementar o percurso sistemático necessário para registrar todos os valores requeridos.
5. Implementar a rotina de consulta por chave composta, recuperando o preço associado.
6. Definir e integrar uma condição de parada verificável para encerrar o ciclo de consultas.
7. Verificar a coerência entre dados lidos, índices utilizados e valor devolvido ao usuário.

### Resultados Esperados

1. Programa funcional capaz de preencher a estrutura de dados integralmente.
2. Programa funcional capaz de responder a consultas sucessivas sobre o preço de um automóvel identificado por múltiplos atributos.
3. Controle explícito de término das consultas.
4. Evidências verificáveis por meio de entradas, saídas e justificativa breve sobre a organização da solução.

### Contexto de Aquisição (curso, organização, ambiente, avaliação)

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### Perfil do Público-Alvo (nível, pré-requisitos, necessidades)

O público-alvo é composto por estudantes em fase introdutória da programação imperativa em C, com contato prévio com tipos primitivos, entrada e saída básica, estruturas de repetição, estruturas condicionais e arranjos indexados. A principal necessidade formativa da tarefa é consolidar a relação entre modelagem de dados, percorrimento de estruturas, recuperação de informação e controle do fluxo de interação.

### Nível de Proficiência (critérios e dimensões)


| Nível | Modelagem da estrutura | Preenchimento da estrutura | Consulta por chave composta | Controle de encerramento | Clareza e rastreabilidade |
|---|---|---|---|---|---|
| **N1 - Inicial** | Reconhece parcialmente os atributos, mas não estabelece correspondência consistente entre índices e dados. | Realiza leituras incompletas ou sem cobertura sistemática das combinações. | Recupera valores de modo inconsistente ou incompleto. | Não implementa condição de parada confiável. | Artefato pouco legível e de difícil verificação. |
| **N2 - Intermediário** | Representa parte das dimensões corretamente, com lacunas ou simplificações relevantes. | Preenche a estrutura com cobertura parcial ou com inconsistências de percorrimento. | Recupera parte das consultas corretamente, com fragilidade na correspondência entre índices. | Implementa parada parcial ou dependente de comportamento não verificável. | Artefato parcialmente verificável, com justificativa limitada. |
| **N3 - Proficiente** | Representa de forma consistente os identificadores e categorias necessários para armazenamento e consulta. | Preenche integralmente a estrutura com percurso sistemático e coerente. | Recupera corretamente o preço a partir da combinação de identificadores informada. | Implementa controle explícito e verificável para término das consultas. | Artefato verificável, com justificativa coerente sobre estrutura e fluxo. |
| **N4 - Avançado** | Reorganiza a modelagem com abstração adicional, justificando alternativas estruturais com clareza técnica. | Otimiza a organização do preenchimento e melhora a clareza estrutural da solução sem comprometer a corretude. | Além de recuperar corretamente, explica e valida a correspondência entre consulta, índices e resultado. | Torna o fluxo de interação mais robusto e claramente justificável, com organização superior do controle. | Artefato altamente rastreável, com justificativa técnica precisa e bem articulada. |

## 2. Seleção e Enumeração de Conhecimentos

### K02 - Variáveis, constantes e tipos primitivos

1. Representação de dados simples necessários ao problema, como identificadores numéricos e preços.
2. Escolha de tipos coerentes para armazenar entradas e controlar leituras.
3. Uso consistente de identificadores para manter o estado da solução durante preenchimento e consulta.

**Justificativa de mobilização na tarefa:** o problema exige declarar e manipular dados primitivos compatíveis com código de identificação, variáveis de controle e valor monetário armazenado na estrutura.

### K04 - Expressões lógicas e condições

1. Formulação de condições para manutenção e encerramento do ciclo de consultas.
2. Interpretação de estados de continuidade, parada e eventuais checagens de coerência no fluxo.
3. Relação entre condição avaliada e comportamento do programa.

**Justificativa de mobilização na tarefa:** a tarefa exige um controle explícito de término das consultas, o que depende da formulação de condições lógicas coerentes com o fluxo interativo.

### K05 - Estrutura sequencial e E/S básica

1. Organização do programa em fluxo verificável de leitura, processamento, armazenamento e saída.
2. Leitura sucessiva de dados pelo teclado para preenchimento e consulta.
3. Apresentação do preço correspondente de forma observável na saída.

**Justificativa de mobilização na tarefa:** toda a solução depende de um encadeamento claro de entradas, atualização da estrutura e apresentação do resultado consultado.

### K07 - Estruturas de repetição

1. Uso de laços para percorrer sistematicamente as combinações necessárias ao preenchimento.
2. Uso de repetição para atendimento sucessivo de consultas.
3. Garantia de parada por contagem ou condição de continuidade.

**Justificativa de mobilização na tarefa:** o preenchimento integral da estrutura e o atendimento de múltiplas consultas requerem repetição controlada e verificável.

### K08 - Vetores e matrizes em C

1. Representação de coleções homogêneas indexadas para armazenamento de preços.
2. Acesso a posições da estrutura por combinação de índices.
3. Atualização e consulta de dados em estrutura de múltiplas dimensões.

**Justificativa de mobilização na tarefa:** o enunciado explicita o uso de um arranjo multidimensional como mecanismo central de armazenamento e recuperação de dados.

### K10 - Enumerações e uniões em C

1. Representação de categorias simbólicas, como modelo, cor, ano e combustível.
2. Associação estável entre nomes de categorias e posições utilizadas na estrutura.
3. Uso de tipos enumerados para tornar a modelagem dos índices categóricos mais consistente e legível.

**Justificativa de mobilização na tarefa:** as dimensões categóricas do problema são apresentadas explicitamente como enumerações, o que torna esse conhecimento diretamente pertinente à modelagem da solução.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Representar dados de domínio em estruturas indexadas por múltiplas dimensões, mantendo coerência entre identificadores, categorias e valor armazenado.  
**K associados:** (K02, K08, K10)

### LO2

Implementar o preenchimento integral de uma estrutura indexada por meio de leitura sistemática e percorrimento controlado.  
**K associados:** (K05, K07, K08, K10)

### LO3

Realizar consultas por chave composta, localizando e recuperando o valor correspondente em uma estrutura de armazenamento indexada.  
**K associados:** (K02, K05, K08, K10)

### LO4

Controlar ciclos interativos de consulta com condição explícita de continuidade e término verificável.  
**K associados:** (K04, K05, K07)

### LO5

Integrar modelagem de dados, preenchimento, consulta e controle de fluxo para desenvolver um programa introdutório de pequeno porte, com comportamento verificável.  
**K associados:** (K02, K04, K05, K07, K08, K10)


## 4. Definição de Competências

### 4.1 Competência Geral

Construir soluções computacionais introdutórias para armazenamento, organização e consulta de dados estruturados, articulando modelagem de informações, controle de fluxo e recuperação verificável de resultados.

**Observação sobre BNCC:** não aplicável como referência normativa neste relatório, por se tratar de contexto de ensino superior. Assim, não são utilizados códigos.

### 4.2 Especificações de Competências

As competências sugeridas pelo usuário são, de fato, mais adequadas ao perfil desta tarefa. Elas são mais reutilizáveis, menos dependentes do enunciado específico e organizam melhor o eixo central da atividade: decisão, repetição e integração para construção de um programa pequeno e verificável. Com base nisso, o conjunto de competências foi revisado abaixo.

#### CT10.1

**Título da Competência**  
Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas.

**Descrição Textual**

Aplicar estruturas de decisão para governar comportamentos do programa, selecionando caminhos de execução coerentes com condições lógicas bem formuladas e verificáveis.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO4, LO5)
- K mobilizados (Núcleo): (K04, K05)

**Especificação de Conhecimentos**
- **K04 - Expressões lógicas e condições:** conhecimento central para formular condições corretas de continuidade, parada e seleção de caminhos de execução; a evidência aparece na coerência do controle decisório do programa.
- **K05 - Estrutura sequencial e E/S básica:** conhecimento central para integrar leitura, decisão e resposta em fluxo observável; a evidência aparece na relação entre entrada recebida, condição avaliada e saída produzida.

**Alinhamento com a Taxonomia de Bloom (revisada)**
Predominância em **Aplicar**.

**Pareamento Conhecimento-Habilidade**

K04 / Aplicar → formular condições lógicas corretas para selecionar comportamentos e controlar o encerramento das consultas.  
Verbos de Bloom: implementar, usar, operar

K05 / Aplicar → integrar a avaliação das condições ao fluxo de leitura e resposta do programa de modo verificável.  
Verbos de Bloom: executar, implementar, apresentar


**Especificação de Disposições**
1. Precisão na formulação de condições.
2. Atenção à coerência entre decisão e comportamento produzido.
3. Rigor na verificabilidade do fluxo do programa.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto deste relatório.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.1 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | precisão, atenção, rigor | K04 | formular condições lógicas corretas para selecionar comportamentos e controlar o encerramento das consultas |
| CT10.1 | Controlar o fluxo com decisões (if/else) e seleção múltipla, formulando expressões lógicas corretas | precisão, atenção, rigor | K05 | integrar a avaliação das condições ao fluxo de leitura e resposta do programa de modo verificável |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa exige decisão explícita para sustentar e encerrar o ciclo de consultas, o que torna indispensável a formulação correta de condições lógicas no fluxo do programa.

#### CT10.2

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras.

**Descrição Textual**

Aplicar estruturas de repetição para percorrer dados, sustentar ciclos de interação e garantir término seguro da execução, preservando coerência entre iteração, estado do programa e condição de parada.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO4, LO5)
- K mobilizados (Núcleo): (K05, K07)

**Especificação de Conhecimentos**
- **K05 - Estrutura sequencial e E/S básica:** conhecimento central para articular leitura, iteração e resposta ao usuário em um fluxo verificável; a evidência aparece no encadeamento das operações durante preenchimento e consulta.
- **K07 - Estruturas de repetição:** conhecimento central para garantir o percurso sistemático da estrutura e a manutenção do ciclo de consultas com parada segura; a evidência aparece na cobertura das iterações e na finalização controlada.

**Alinhamento com a Taxonomia de Bloom (revisada)**
Predominância em **Aplicar**.

**Pareamento Conhecimento-Habilidade**

K05 / Aplicar → organizar leitura, processamento e saída em ciclos verificáveis durante o preenchimento e as consultas.  
Verbos de Bloom: executar, implementar, apresentar

K07 / Aplicar → controlar repetições com paradas seguras para preencher a estrutura e atender consultas sucessivas.  
Verbos de Bloom: iterar, executar, implementar


**Especificação de Disposições**
1. Sistematicidade no percorrimento da estrutura.
2. Cuidado com a garantia de parada.
3. Consistência no controle do fluxo iterativo.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto deste relatório.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.2 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | sistematicidade, cuidado, consistência | K05 | organizar leitura, processamento e saída em ciclos verificáveis durante o preenchimento e as consultas |
| CT10.2 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | sistematicidade, cuidado, consistência | K07 | controlar repetições com paradas seguras para preencher a estrutura e atender consultas sucessivas |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o preenchimento integral da estrutura e o atendimento de múltiplas consultas dependem diretamente de repetição controlada, com condição de parada observável e confiável.

#### CT10.3

**Título da Competência**  
Integrar os conceitos para desenvolver um programa de pequeno porte que resolva um problema do domínio.

**Descrição Textual**

Integrar modelagem de dados, estruturas de armazenamento, entrada e saída, decisão e repetição para implementar um programa introdutório de pequeno porte, com comportamento correto, verificável e adequado ao problema proposto.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO2, LO3, LO4, LO5)
- K mobilizados (Núcleo): (K02, K05, K07, K08, K10)

**Especificação de Conhecimentos**
- **K02 - Variáveis, constantes e tipos primitivos:** conhecimento central para representar identificadores, preços e variáveis de controle; a evidência aparece na coerência entre tipos e papéis dos dados.
- **K05 - Estrutura sequencial e E/S básica:** conhecimento central para organizar o fluxo observável de leitura, processamento e saída; a evidência aparece na execução verificável do programa.
- **K07 - Estruturas de repetição:** conhecimento central para percorrer a estrutura e sustentar o ciclo de consultas; a evidência aparece na cobertura do preenchimento e na repetição controlada.
- **K08 - Vetores e matrizes em C:** conhecimento central para armazenar e recuperar preços por combinação de índices; a evidência aparece na organização e no acesso correto à estrutura.
- **K10 - Enumerações e uniões em C:** conhecimento central para representar os atributos categóricos do domínio; a evidência aparece na correspondência entre categorias e indexação da estrutura.

**Alinhamento com a Taxonomia de Bloom**
Predominância em **Criar**, pois a tarefa exige implementação de uma solução funcional de pequeno porte.

**Pareamento Conhecimento-Habilidade**

K02 / Aplicar → declarar e utilizar variáveis e tipos primitivos compatíveis com identificadores, preços e controle do programa.  
Verbos de Bloom: representar, selecionar, usar

K05 / Aplicar → estruturar o fluxo de entrada, processamento e saída de modo verificável ao longo da execução.  
Verbos de Bloom: organizar, executar, apresentar

K07 / Aplicar → controlar a repetição necessária ao preenchimento da estrutura e ao atendimento das consultas.  
Verbos de Bloom: iterar, executar, implementar

K08 / Criar → implementar uma estrutura indexada que armazene e recupere preços a partir de múltiplos identificadores.  
Verbos de Bloom: estruturar, construir, integrar

K10 / Aplicar → representar categorias enumeradas de forma coerente com a modelagem e o acesso aos dados.  
Verbos de Bloom: mapear, usar, implementar


**Especificação de Disposições**
1. Organização na integração dos componentes da solução.
2. Precisão técnica na modelagem e no acesso aos dados.
3. Persistência na verificação do comportamento do programa.
4. Clareza na justificativa da solução implementada.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto deste relatório.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.3 | Integrar os conceitos para desenvolver um programa de pequeno porte que resolva um problema do domínio | organização, precisão técnica, persistência, clareza | K02 | declarar e utilizar variáveis e tipos primitivos compatíveis com identificadores, preços e controle do programa |
| CT10.3 | Integrar os conceitos para desenvolver um programa de pequeno porte que resolva um problema do domínio | organização, precisão técnica, persistência, clareza | K05 | estruturar o fluxo de entrada, processamento e saída de modo verificável ao longo da execução |
| CT10.3 | Integrar os conceitos para desenvolver um programa de pequeno porte que resolva um problema do domínio | organização, precisão técnica, persistência, clareza | K07 | controlar a repetição necessária ao preenchimento da estrutura e ao atendimento das consultas |
| CT10.3 | Integrar os conceitos para desenvolver um programa de pequeno porte que resolva um problema do domínio | organização, precisão técnica, persistência, clareza | K08 | implementar uma estrutura indexada que armazene e recupere preços a partir de múltiplos identificadores |
| CT10.3 | Integrar os conceitos para desenvolver um programa de pequeno porte que resolva um problema do domínio | organização, precisão técnica, persistência, clareza | K10 | representar categorias enumeradas de forma coerente com a modelagem e o acesso aos dados |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade não se limita a um único aspecto isolado. Ela exige que o estudante integre modelagem, armazenamento, consulta e controle de fluxo para produzir um programa funcional, o que justifica uma competência integradora de pequeno porte.