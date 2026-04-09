# Relatório CSP — Autoria de Competências

## Introdução

Este relatório situa a tarefa na fase de **Autoria de Competências** do Competency Specification Process, com foco na especificação rastreável de conhecimentos, objetivos de aprendizagem e competências mobilizados pela atividade. A tarefa solicita a leitura de uma matriz esparsa, a identificação de seus elementos não nulos e a construção de uma matriz condensada com três colunas, preservando valor, linha e coluna de ocorrência.

A atividade elicita evidências observáveis porque exige um artefato executável, duas saídas matriciais verificáveis e consistência entre posições da matriz original e registros da matriz condensada. O problema também favorece o modelo K–S–D sem redundância, pois mobiliza um subconjunto enxuto e estável de conhecimentos de Introdução à Programação, traduzidos em objetivos reutilizáveis e em competências exclusivas do domínio de Computação.

## 1. Análise da Entidade Instrucional

### 1.1 Título

Condensação de Matriz Esparsa em Estrutura de Três Colunas

### 1.2 Descrição

A tarefa requer a implementação de um programa que leia uma matriz esparsa de dimensões `M x N`, percorra todos os seus elementos, identifique os valores não nulos e os registre em uma segunda estrutura bidimensional com três colunas. Essa estrutura condensada deve preservar, para cada ocorrência relevante, o valor encontrado e seus índices de linha e coluna. Ao final, o programa deve imprimir a matriz original e a matriz condensada em formato matricial.

### 1.3 Processo de Desenvolvimento da Solução

1. Definir as estruturas de dados necessárias para representar a matriz original e a matriz condensada.
2. Ler e armazenar os elementos da matriz original, preservando a organização bidimensional.
3. Percorrer sistematicamente a matriz original por linhas e colunas.
4. Testar cada elemento para verificar se ele é não nulo e, quando pertinente, registrar valor e coordenadas na matriz condensada.
5. Imprimir a matriz original e a matriz condensada em formato matricial, de modo verificável.

### 1.4 Resultados Esperados

1. Código-fonte funcional para leitura, processamento e impressão das estruturas.
2. Matriz original impressa em formato matricial.
3. Matriz condensada impressa em formato matricial.
4. Correspondência verificável entre cada valor não nulo e os índices registrados.
5. Justificativa breve sobre a lógica adotada para formar a estrutura condensada.

### 1.5 Contexto de Aquisição

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### 1.6 Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de formação em Computação, com contato prévio com variáveis, tipos primitivos, entrada e saída, estruturas condicionais simples, laços e manipulação básica de matrizes. A principal necessidade formativa da tarefa é consolidar a integração entre percorrimento bidimensional, filtragem por condição simples e preservação de rastreabilidade posicional em estruturas derivadas.

### 1.7 Nível de Proficiência

A tarefa se posiciona predominantemente em **N3 — Proficiente**, por exigir integração consistente entre matrizes, laços, condição simples e transformação de representação. A tabela a seguir apresenta as dimensões com linhas e colunas invertidas.

| Nível | Representação de dados | Percorrimento bidimensional | Condição e filtragem | Rastreabilidade posicional | Verificabilidade da saída |
|---|---|---|---|---|---|
| **N1 — Inicial** | Reconhece a existência de matriz e acessa posições isoladas com apoio. | Percorre parcialmente linhas ou colunas, com erros de cobertura. | Aplica teste simples com inconsistências ocasionais. | Registra valor sem preservar com segurança os índices correspondentes. | Produz saída incompleta ou pouco legível. |
| **N2 — Intermediário** | Lê e armazena elementos em matriz simples, com pequenos ajustes. | Percorre a matriz completa, mas com fragilidade em limites e organização. | Identifica casos não nulos, mas ainda com falhas de registro. | Registra parte das coordenadas, com pequenas inconsistências. | Produz saída legível, mas ainda com inconsistências de organização. |
| **N3 — Proficiente** | Organiza matriz original e matriz derivada com coerência estrutural. | Percorre sistematicamente todas as posições, preservando cobertura e ordem. | Filtra corretamente os elementos relevantes e relaciona valor e posição. | Preserva valor, linha e coluna de cada ocorrência relevante de forma verificável. | Imprime as duas matrizes de modo matricial e verificável. |
| **N4 — Avançado** | Generaliza a representação para variações mais abstratas ou modularizadas. | Otimiza ou abstrai o percorrimento em rotinas reutilizáveis. | Expande a lógica para múltiplos critérios ou políticas de condensação. | Mantém rastreabilidade completa em transformações mais complexas. | Acrescenta validação estrutural, modularização ou testes adicionais. |

## 2. Seleção e Enumeração de Conhecimentos

Foram selecionados seis conhecimentos do catálogo, mantendo o recorte necessário para a tarefa e evitando expansão indevida de escopo.

### K01 — Modelo de execução e noção de estado (paradigma imperativo)

Descrição
1. Compreensão de que o programa evolui por atualizações sucessivas de estado ao longo da execução.
2. Leitura da relação entre atribuições, ordem de execução e efeito produzido na memória.
3. Entendimento operacional do preenchimento progressivo de estruturas durante o processamento.

Justificativa de mobilização na tarefa

A construção da matriz condensada depende de atualizações sucessivas do estado do programa, especialmente na progressão do preenchimento e na preservação da correspondência entre leitura e registro.

### K02 — Variáveis, constantes e tipos primitivos

Descrição
1. Uso de variáveis para armazenar valores, índices e marcadores de processamento.
2. Escolha coerente de tipos primitivos para dados numéricos e posições.
3. Manutenção de consistência entre papel do dado e forma de armazenamento.

Justificativa de mobilização na tarefa

A tarefa demanda variáveis para dimensões, índices, elementos da matriz e controle do preenchimento da estrutura condensada, todos com função observável na solução.

### K04 — Expressões lógicas e condições

Descrição
1. Construção de condições booleanas simples para tomada de decisão.
2. Interpretação de relações de verdade e falsidade no controle de fluxo.
3. Aplicação de testes condicionais diretamente ligados à regra do problema.

Justificativa de mobilização na tarefa

A seleção dos elementos a serem condensados depende de uma condição simples e central do enunciado: verificar se o elemento da matriz é diferente de zero.

### K05 — Estrutura sequencial e E/S básica

Descrição
1. Organização do fluxo de leitura, processamento e saída em sequência verificável.
2. Integração entre comandos de entrada, transformação de dados e impressão.
3. Produção de saídas formatadas de modo compatível com a inspeção do resultado.

Justificativa de mobilização na tarefa

A atividade exige leitura da matriz original, processamento da condensação e impressão de duas estruturas em formato matricial, o que torna esse conhecimento diretamente observável.

### K07 — Estruturas de repetição

Descrição
1. Uso de laços para percorrer conjuntos de dados indexados.
2. Controle de cobertura, avanço e parada em percorrimentos sistemáticos.
3. Coordenação entre repetição e processamento acumulativo ou seletivo.

Justificativa de mobilização na tarefa

A matriz precisa ser percorrida integralmente por linhas e colunas, e isso depende de estruturas de repetição corretamente organizadas.

### K08 — Vetores e matrizes em C

Descrição
1. Representação de coleções homogêneas em uma e duas dimensões.
2. Acesso por índice e manutenção de coerência posicional entre leitura e escrita.
3. Processamento de dados em estrutura bidimensional, inclusive com estrutura derivada.

Justificativa de mobilização na tarefa

A tarefa é centrada em leitura, percorrimento, consulta e escrita em matrizes, tanto na estrutura original quanto na forma condensada de três colunas.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Organizar a leitura, o armazenamento e a impressão de estruturas bidimensionais de modo verificável.

**K associados:** K02, K05, K08  
**Cobertura prevista:** CT07.1, CT07.3

### LO2

Percorrer matrizes bidimensionais com laços e indexação consistentes, garantindo cobertura completa das posições relevantes.

**K associados:** K01, K07, K08  
**Cobertura prevista:** CT07.1, CT07.2

### LO3

Identificar elementos que satisfazem uma condição simples e registrar, de forma coerente, valor e posição em estrutura derivada.

**K associados:** K04, K07, K08  
**Cobertura prevista:** CT07.2, CT07.3

### LO4

Implementar transformação de representação de dados preservando rastreabilidade entre estrutura original e estrutura condensada.

**K associados:** K01, K02, K05, K08  
**Cobertura prevista:** CT07.3

## 4. Definição de Competências

### 4.1 Competência Geral

Modelar, implementar e verificar soluções imperativas que transformem dados estruturados em representações computacionais equivalentes e rastreáveis, com controle de fluxo consistente e saída verificável.

Como a tarefa pertence a um contexto de graduação em Introdução à Programação, **não há alinhamento por códigos da BNCC**. Mantém-se apenas uma formulação geral do domínio de Computação.

### 4.2 Especificações de Competências

## CT07.1

**Título da Competência**  
Manipular matrizes bidimensionais com indexação consistente e organização estrutural

**Descrição Textual**  
Representar, acessar e organizar dados em matrizes bidimensionais, preservando coerência entre posições, elementos e estrutura de armazenamento ao longo do processamento.

**Cobertura e rastreabilidade**


LOs cobertos: LO1, LO2  
K mobilizados (Núcleo): K02, K08

**Especificação de Conhecimentos**

| Código K | Descrição curta | Justificativa de evidência |
|---|---|---|
| K02 | Variáveis, índices e tipos coerentes para armazenar dimensões, posições e valores. | Evidenciado pela necessidade de declarar e utilizar dados compatíveis com leitura e registro matricial. |
| K08 | Representação e acesso posicional em matrizes bidimensionais. | Evidenciado pela leitura, armazenamento e acesso consistente aos elementos da matriz original e da matriz derivada. |

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, pois a competência exige uso operacional de variáveis, índices e matrizes para manter a estrutura correta do artefato produzido.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → declarar e utilizar variáveis e índices compatíveis com o papel estrutural de cada dado.
Verbos de Bloom: representar, selecionar, operar

K08 / Aplicar → ler, armazenar e acessar elementos de matrizes bidimensionais com indexação consistente.
Verbos de Bloom: manipular, usar, implementar


**Especificação de Disposições**  
Precisão no uso de índices; cuidado com a coerência estrutural dos dados; atenção à organização matricial da solução.

**Competências Alinhadas à BNCC**  
Não aplicável neste contexto.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT07.1 | Manipular matrizes bidimensionais com indexação consistente e organização estrutural | Precisão no uso de índices; cuidado com a coerência estrutural dos dados; atenção à organização matricial da solução | K02 | Declarar e utilizar variáveis e índices compatíveis com o papel estrutural de cada dado |
| CT07.1 | Manipular matrizes bidimensionais com indexação consistente e organização estrutural | Precisão no uso de índices; cuidado com a coerência estrutural dos dados; atenção à organização matricial da solução | K08 | Ler, armazenar e acessar elementos de matrizes bidimensionais com indexação consistente |

**Definição de Ativação**


Restrição de ativação: Obrigatória  
Modo de ativação: Construtiva   
Função de ativação: Núcleo  
Justificativa: A tarefa depende diretamente da correta representação da matriz original e da matriz condensada. Sem organização estrutural coerente, o restante do processamento perde verificabilidade.

## CT07.2

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores e paradas seguras

**Descrição Textual**  
Estruturar percorrimentos iterativos sobre dados indexados, com controle consistente de avanço, cobertura e limites, assegurando parada correta do processamento.

**Cobertura e rastreabilidade**

LOs cobertos: LO2, LO3  
K mobilizados (Núcleo): K07, K08

**Especificação de Conhecimentos**

| Código K | Descrição curta | Justificativa de evidência |
|---|---|---|
| K07 | Estruturas de repetição para percorrimento completo e controlado de dados indexados. | Evidenciado pela necessidade de varrer todas as posições da matriz original sem perda de cobertura. |
| K08 | Organização bidimensional que impõe controle por linhas e colunas. | Evidenciado pelo uso de índices coordenados no percorrimento da matriz. |

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, pois a competência exige implementação correta de laços, contadores e limites para produzir o comportamento esperado.

**Pareamento Conhecimento–Habilidade**

K07 / Aplicar → estruturar laços com contadores e condições de parada compatíveis com o percorrimento completo da matriz.
Verbos de Bloom: iterar, executar, implementar

K08 / Aplicar → articular linhas e colunas como eixos de controle do percorrimento bidimensional.
Verbos de Bloom: organizar, usar, operar


**Especificação de Disposições**  
Disciplina no controle do fluxo; atenção aos limites do percorrimento; rigor na cobertura completa das posições.

**Competências Alinhadas à BNCC**  
Não aplicável neste contexto.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT07.2 | Controlar o fluxo com repetição utilizando contadores e paradas seguras | Disciplina no controle do fluxo; atenção aos limites do percorrimento; rigor na cobertura completa das posições | K07 | Estruturar laços com contadores e condições de parada compatíveis com o percorrimento completo da matriz |
| CT07.2 | Controlar o fluxo com repetição utilizando contadores e paradas seguras | Disciplina no controle do fluxo; atenção aos limites do percorrimento; rigor na cobertura completa das posições | K08 | Articular linhas e colunas como eixos de controle do percorrimento bidimensional |

**Definição de Ativação**

Restrição de ativação: Obrigatória  
Modo de ativação: Construtiva   
Função de ativação: Núcleo  
Justificativa: A tarefa exige varredura integral da matriz original. Por isso, a repetição com controle seguro de avanço e parada é evidência direta e indispensável do desempenho esperado. 

## CT07.3

**Título da Competência**  
Transformar representações matriciais por filtragem condicional simples e rastreabilidade posicional

**Descrição Textual**  
Selecionar elementos relevantes em estruturas matriciais a partir de condição simples e registrá-los em representação derivada, preservando valor, posição e verificabilidade da saída.

**Cobertura e rastreabilidade**

LOs cobertos: LO1, LO3, LO4     
K mobilizados (Núcleo): K04, K05, K08 

**Especificação de Conhecimentos**

| Código K | Descrição curta | Justificativa de evidência |
|---|---|---|
| K04 | Expressões lógicas simples para decidir o registro de um elemento. | Evidenciado pelo critério de não nulidade aplicado a cada posição da matriz. |
| K05 | Fluxo verificável de leitura, transformação e impressão. | Evidenciado pela necessidade de produzir duas saídas matriciais observáveis e coerentes. |
| K08 | Estruturas bidimensionais como origem e destino da transformação. | Evidenciado pela passagem da matriz original para a matriz condensada de três colunas. |

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio de **Criar**, apoiado por **Aplicar**, pois a competência requer implementar uma transformação completa de representação com critério de seleção explícito e produto verificável.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → formular e aplicar condição simples para decidir quais elementos devem ser registrados.
Verbos de Bloom: aplicar, selecionar, usar

K05 / Aplicar → organizar o fluxo de leitura, transformação e impressão de modo verificável.
Verbos de Bloom: implementar, executar, apresentar

K08 / Criar → construir uma representação matricial condensada preservando valor e coordenadas dos elementos relevantes.
Verbos de Bloom: construir, desenvolver, produzir



**Especificação de Disposições**  
Compromisso com a rastreabilidade; cuidado com a consistência entre critério e registro; atenção à verificabilidade da saída produzida.

**Competências Alinhadas à BNCC**  
Não aplicável neste contexto.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT07.3 | Transformar representações matriciais por filtragem condicional simples e rastreabilidade posicional | Compromisso com a rastreabilidade; cuidado com a consistência entre critério e registro; atenção à verificabilidade da saída produzida | K04 | Formular e aplicar condição simples para decidir quais elementos devem ser registrados |
| CT07.3 | Transformar representações matriciais por filtragem condicional simples e rastreabilidade posicional | Compromisso com a rastreabilidade; cuidado com a consistência entre critério e registro; atenção à verificabilidade da saída produzida | K05 | Organizar o fluxo de leitura, transformação e impressão de modo verificável |
| CT07.3 | Transformar representações matriciais por filtragem condicional simples e rastreabilidade posicional | Compromisso com a rastreabilidade; cuidado com a consistência entre critério e registro; atenção à verificabilidade da saída produzida | K08 | Construir uma representação matricial condensada preservando valor e coordenadas dos elementos relevantes |

**Definição de Ativação**

Restrição de ativação: Obrigatória  
Modo de ativação: Construtiva   
Função de ativação: Núcleo  
Justificativa: O produto final da tarefa é uma transformação de representação baseada em filtragem por condição simples. O que se avalia diretamente é a coerência entre seleção, registro posicional e saída matricial. 
