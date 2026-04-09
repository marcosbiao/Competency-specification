# Relatório CSP: TASK15

## Introdução

Este relatório situa a TASK15 na fase de Autoria de Competências do Competency Specification Process, com foco na explicitação de conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa de programação introdutória. A atividade solicita a implementação de uma solução recursiva para percorrer uma matriz bidimensional, localizar a cabeça de uma estrutura conectada e retornar uma sequência ordenada de coordenadas correspondente ao trajeto completo.

A tarefa produz evidências observáveis porque exige um artefato executável, saída verificável, justificativa breve e comportamento consistente diante de diferentes dimensões de matriz e diferentes configurações válidas do problema. Essas evidências permitem distinguir o que é diretamente demonstrado no produto final, o que sustenta a solução em nível conceitual e como a recursão é efetivamente empregada.

O modelo K–S–D é adequado neste caso porque a tarefa mobiliza, de forma articulada e sem redundância, conhecimentos sobre matrizes, condições, seleção, subprogramas e recursão; habilidades observáveis na construção e no percurso da solução; e disposições relacionadas a precisão, consistência e rigor técnico.

## 1. Análise da Entidade Instrucional

### 1.1 Título

Percurso recursivo de estrutura conectada em matriz bidimensional

### 1.2 Descrição

A tarefa propõe a construção de um algoritmo recursivo que recebe uma matriz representando um grid com células vazias e uma estrutura conectada iniciada por uma cabeça. A solução deve localizar o ponto inicial, seguir corretamente a conectividade da estrutura e produzir uma sequência ordenada de coordenadas no formato `[coluna, linha]`. O foco principal está na modelagem do percurso, no uso apropriado de recursão e na consistência entre especificação, processamento e saída.

### 1.3 Processo de Desenvolvimento da Solução

1. Interpretar a representação matricial do problema e identificar os símbolos relevantes.
2. Definir uma estratégia de localização da posição inicial da estrutura.
3. Estabelecer critérios de continuidade do percurso com base em vizinhança válida e conectividade.
4. Projetar o subprograma recursivo com caso base, passo recursivo e progresso para término.
5. Registrar as coordenadas na ordem correta ao longo do percurso.
6. Verificar a saída produzida em diferentes configurações válidas da matriz.

### 1.4 Resultados Esperados

1. Algoritmo ou programa com uso efetivo de recursão.
2. Identificação correta da cabeça da estrutura.
3. Percurso completo da estrutura conectada sem omissão de posições.
4. Saída ordenada no formato especificado.
5. Justificativa breve sobre a lógica geral do percurso recursivo.
6. Registros de teste que permitam verificar funcionamento e término.

### 1.5 Contexto de Aquisição

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### 1.6 Perfil do Público-Alvo

| Aspecto | Caracterização |
|---|---|
| Nível | Estudantes em fase introdutória da disciplina, já expostos a estruturas matriciais, seleção, subprogramas e recursão |
| Pré-requisitos | Leitura de matrizes, acesso por índices, formulação de condições, definição de funções e noção de caso base |
| Necessidades formativas | Consolidar a integração entre representação de dados, conectividade local, decomposição da solução e controle recursivo do percurso |

### 1.7 Nível de Proficiência

| Nível | Leitura da matriz e da conectividade | Estruturação da recursão | Correção do percurso e da saída | Verificabilidade do artefato |
|---|---|---|---|---|
| **N1 - Inicial** | Reconhece parcialmente símbolos e posições, com dificuldade para relacionar vizinhança e trajeto | Apresenta caso base incompleto ou passo recursivo sem progresso claro | Percorre apenas parte da estrutura ou produz ordenação inconsistente | Entrega pouco legível e com justificativa insuficiente |
| **N2 - Intermediário** | Identifica a maioria das posições relevantes e estabelece parte da conectividade | Define caso base e passo recursivo, mas com fragilidades no controle do término | Percorre a maior parte da estrutura, com pequenas falhas de ordenação ou cobertura | Entrega verificável, mas ainda com explicações limitadas |
| **N3 - Proficiente** | Interpreta corretamente a matriz e distingue a continuidade do percurso com segurança | Implementa caso base, avanço e término de modo consistente | Percorre toda a estrutura e produz a sequência correta de coordenadas | Entrega clara, justificável e testável |
| **N4 - Avançado** | Generaliza a leitura para diferentes configurações válidas e antecipa casos de borda compatíveis com a especificação | Organiza a recursão de forma clara, robusta e facilmente verificável | Mantém correção integral com clareza adicional na organização do resultado e na justificativa | Entrega altamente rastreável, com justificativa precisa e testes bem escolhidos |

## 2. Seleção e Enumeração de Conhecimentos

### K01: Modelo de execução e noção de estado (paradigma imperativo)

1. Compreensão de que a execução do programa evolui por mudanças de estado ao longo do processamento.
2. Leitura do efeito das atualizações de estado sobre o percurso e sobre o resultado acumulado.
3. Relação entre ordem de execução, transição de estado e artefato final observável.

Justificativa de mobilização na tarefa: o percurso correto depende de acompanhar a progressão do processamento e de manter coerência entre posição atual, histórico do percurso e saída gerada.

### K04: Expressões lógicas e condições

1. Construção de condições booleanas para verificar vizinhança válida e continuidade do percurso.
2. Interpretação de relações de adjacência e de critérios de término.
3. Formulação de checagens consistentes com a especificação do problema.

Justificativa de mobilização na tarefa: a solução precisa distinguir posições válidas, decidir continuidade e reconhecer quando o percurso deve encerrar.

### K06: Estruturas de seleção

1. Uso de decisões condicionais para escolher o próximo passo do processamento.
2. Cobertura coerente de caminhos alternativos de execução.
3. Organização de ramos que preservem a consistência do percurso.

Justificativa de mobilização na tarefa: a escolha do próximo movimento e o tratamento dos casos possíveis exigem seleção estruturada e verificável.

### K08: Vetores e matrizes em C

1. Representação de dados em arranjos bidimensionais com acesso posicional por índices.
2. Leitura, consulta e processamento de células em uma grade.
3. Relação entre posição, conteúdo da célula e interpretação computacional do problema.

Justificativa de mobilização na tarefa: a estrutura de entrada é explicitamente uma matriz bidimensional e toda a trajetória da solução é orientada por acesso indexado ao grid.

### K11: Subprogramas: procedimentos e funções

1. Decomposição do problema em unidades de processamento com responsabilidade delimitada.
2. Definição de parâmetros e retorno coerentes com o papel do subprograma.
3. Organização modular da solução para facilitar clareza, reuso e verificabilidade.

Justificativa de mobilização na tarefa: a solução recursiva pressupõe o uso de subprogramas para estruturar a lógica de localização, percurso e retorno do resultado.

### K12: Recursão em subprogramas

1. Formulação de caso base e caso recursivo em uma função ou procedimento.
2. Garantia de progresso para término do processamento.
3. Rastreamento conceitual das chamadas ao longo da resolução.

Justificativa de mobilização na tarefa: a recursão é uma exigência explícita do enunciado e constitui o eixo central da estratégia de solução.

## 3. Identificação de Objetivos de Aprendizagem

### LO15.1
Identificar e acessar posições relevantes em matrizes bidimensionais com base em critérios de conteúdo e vizinhança.

**K associados:** (K08, K04)

### LO15.2
Estruturar decisões de percurso por meio de condições verificáveis e seleção coerente entre alternativas de continuidade e término.

**K associados:** (K04, K06, K01)

### LO15.3
Implementar subprogramas recursivos com caso base, passo recursivo e progresso observável para término.

**K associados:** (K11, K12, K01)

### LO15.4
Produzir saídas ordenadas e verificáveis que representem o resultado do percurso conforme a especificação do problema.

**K associados:** (K08, K11, K01)

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver soluções algorítmicas para problemas estruturados por meio de representação adequada de dados, controle de fluxo e decomposição em subprogramas, produzindo resultados verificáveis e coerentes com a especificação.

BNCC: não aplicável nesta tarefa, por tratar-se de contexto de ensino superior e não haver necessidade de alinhamento curricular externo.

### 4.2 Especificações de Competências

#### CT15.1

**Título da Competência**  
Analisar e percorrer estruturas matriciais por conectividade local

**Descrição Textual**  
Identificar, em matrizes bidimensionais, elementos conectados e determinar a continuidade de um percurso com base em posição, vizinhança e critérios condicionais verificáveis.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO15.1, LO15.2)
2. K mobilizados: (K08, K04, K06)

**Especificação de Conhecimentos**
1. K08: acesso indexado a matrizes e interpretação posicional do conteúdo. Evidência direta na leitura do grid e na determinação das coordenadas percorridas.
2. K04: formulação de condições para reconhecer vizinhança válida e continuidade do trajeto. Evidência direta nas verificações que sustentam o avanço correto.
3. K06: organização de decisões entre alternativas de continuidade e encerramento. Evidência direta na escolha consistente do próximo passo.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Analisar**, pois a competência exige examinar a estrutura matricial, distinguir posições relevantes e relacionar critérios de conectividade para orientar o percurso.

**Pareamento Conhecimento–Habilidade**

K08 / Analisar → examinar posições de uma matriz bidimensional e relacionar conteúdo, índice e coordenada para sustentar um percurso verificável.  
Verbos de Bloom: examinar, estruturar, rastrear

K04 / Analisar → distinguir condições de adjacência e continuidade adequadas ao avanço do processamento em uma grade.  
Verbos de Bloom: distinguir, relacionar, decompor

K06 / Aplicar → selecionar ramos de execução coerentes com os casos possíveis de continuidade e término do percurso.  
Verbos de Bloom: aplicar, executar, usar

**Especificação de Disposições**
1. Precisão no uso de índices e coordenadas.
2. Atenção à conectividade local e à consistência das decisões.
3. Rigor na verificação das condições de percurso.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.1 | Analisar e percorrer estruturas matriciais por conectividade local | precisão; atenção; rigor | K08 | examinar posições de uma matriz bidimensional e relacionar conteúdo, índice e coordenada para sustentar um percurso verificável |
| CT15.1 | Analisar e percorrer estruturas matriciais por conectividade local | precisão; atenção; rigor | K04 | distinguir condições de adjacência e continuidade adequadas ao avanço do processamento em uma grade |
| CT15.1 | Analisar e percorrer estruturas matriciais por conectividade local | precisão; atenção; rigor | K06 | selecionar ramos de execução coerentes com os casos possíveis de continuidade e término do percurso |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: analítica
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a atividade exige que o estudante leia a matriz, reconheça a conectividade entre células e determine, com base em critérios observáveis, como o percurso deve prosseguir. Essa competência é diretamente visível na correção do trajeto produzido.

#### CT15.2

**Título da Competência**  
Construir subprogramas recursivos com progressão verificável

**Descrição Textual**  
Projetar e implementar subprogramas recursivos com parâmetros, caso base, passo recursivo e garantia de término, de modo coerente com a estrutura do problema.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO15.2, LO15.3)
2. K mobilizados: (K11, K12)

**Especificação de Conhecimentos**
1. K11: decomposição da solução em subprogramas com responsabilidade clara, parâmetros coerentes e retorno consistente. Evidência direta na organização modular da solução.
2. K12: definição da recursão com caso base, caso recursivo e progresso para término. Evidência direta na exigência de que a estratégia principal seja recursiva.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Criar**, pois a competência requer conceber e implementar uma solução recursiva funcional, articulando estrutura de subprograma e controle de chamadas.

**Pareamento Conhecimento–Habilidade**

K11 / Criar → projetar subprogramas coesos com parâmetros e retorno compatíveis com o papel de cada etapa do processamento.  
Verbos de Bloom: projetar, desenvolver, construir

K12 / Criar → formular uma estratégia recursiva com caso base, avanço consistente e término verificável.  
Verbos de Bloom: formular, criar, programar

**Especificação de Disposições**
1. Disciplina na definição do caso base.
2. Rigor no controle de progresso para término.
3. Organização modular da solução.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.2 | Construir subprogramas recursivos com progressão verificável | disciplina; rigor; organização | K11 | projetar subprogramas coesos com parâmetros e retorno compatíveis com o papel de cada etapa do processamento |
| CT15.2 | Construir subprogramas recursivos com progressão verificável | disciplina; rigor; organização | K12 | formular uma estratégia recursiva com caso base, avanço consistente e término verificável |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: o enunciado exige explicitamente um algoritmo recursivo. Assim, a competência é ativada na própria construção do artefato, na definição do caso base, no encadeamento das chamadas e na garantia de término.

#### CT15.3

**Título da Competência**  
Integrar representação de dados e geração ordenada de resultados em solução verificável

**Descrição Textual**  
Integrar representação estrutural dos dados, organização do processamento e produção de saída para devolver resultados ordenados e coerentes com uma especificação algorítmica.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO15.3, LO15.4)
2. K mobilizados: (K01, K08, K11)

**Especificação de Conhecimentos**
1. K01: acompanhamento do estado do processamento ao longo da construção do resultado. Evidência direta na manutenção da ordem do percurso e na consistência da saída.
2. K08: relação entre posição matricial e coordenada devolvida. Evidência direta na produção do resultado a partir do grid.
3. K11: organização do processamento em subprogramas que permitam construir e devolver o resultado de modo verificável. Evidência direta na estrutura funcional da solução.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Criar**, pois a competência exige integrar diferentes componentes da solução em um artefato funcional que produza um resultado ordenado conforme a especificação.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → rastrear a evolução do estado do programa para manter a ordem correta do resultado produzido.  
Verbos de Bloom: rastrear, contextualizar, relacionar

K08 / Aplicar → mapear posições matriciais para coordenadas consistentes com a especificação de saída.  
Verbos de Bloom: mapear, implementar, usar

K11 / Criar → desenvolver subprogramas articulados que organizem o processamento e devolvam resultados verificáveis.  
Verbos de Bloom: desenvolver, construir, programar

**Especificação de Disposições**
1. Consistência na organização da saída.
2. Cuidado com rastreabilidade entre processamento e resultado.
3. Clareza técnica na justificativa do artefato produzido.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT15.3 | Integrar representação de dados e geração ordenada de resultados em solução verificável | consistência; cuidado; clareza | K01 | rastrear a evolução do estado do programa para manter a ordem correta do resultado produzido |
| CT15.3 | Integrar representação de dados e geração ordenada de resultados em solução verificável | consistência; cuidado; clareza | K08 | mapear posições matriciais para coordenadas consistentes com a especificação de saída |
| CT15.3 | Integrar representação de dados e geração ordenada de resultados em solução verificável | consistência; cuidado; clareza | K11 | desenvolver subprogramas articulados que organizem o processamento e devolvam resultados verificáveis |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a atividade não se encerra na identificação local das células ou na escrita de uma função recursiva isolada. O estudante precisa integrar representação, percurso e geração ordenada do resultado, produzindo uma saída verificável e justificando seu funcionamento.
