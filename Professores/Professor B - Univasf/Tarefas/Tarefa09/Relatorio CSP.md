# RELATÓRIO CSP, AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa a TASK09 na fase de **Autoria de Competências** do Competency Specification Process, com foco na explicitação rastreável dos conhecimentos, objetivos de aprendizagem e competências mobilizados pela atividade. A tarefa exige que o estudante processe uma matriz bidimensional, localize a cabeça de uma cobra e reconstrua a trajetória completa até a extremidade final do corpo, produzindo uma sequência ordenada de coordenadas.

A task elicita evidências observáveis porque requer um artefato executável ou formalizável, uma saída em formato verificável e uma justificativa breve sobre a coerência do percurso. Isso permite observar de forma direta leitura matricial, formulação de condições, uso de repetição com parada segura e organização da saída.

No modelo **K–S–D**, a atividade mobiliza um conjunto compacto e reutilizável de conhecimentos da disciplina, habilidades observáveis e disposições cognitivas ligadas a precisão algorítmica, verificabilidade e coerência entre estrutura do problema, processamento e resultado.

## 1. Análise da Entidade Instrucional

### Título

Desafio I, Encontrando a Cobra no Grid

### Descrição

A tarefa solicita a implementação de um algoritmo capaz de percorrer uma matriz bidimensional que representa um grid, localizar a cabeça da cobra e reconstruir a sequência ordenada de coordenadas correspondente ao corpo conectado até a extremidade final. O produto esperado é uma solução verificável que respeite a convenção de saída `[coluna, linha]`, funcione para matrizes `M x N` e mantenha a ordem correta do percurso.

### Processo de Desenvolvimento da Solução

1. Localizar, na matriz, a posição correspondente à cabeça da cobra.
2. Definir a convenção de leitura da matriz e da saída, distinguindo índice de linha, índice de coluna e formato de coordenadas.
3. Examinar posições adjacentes válidas para reconhecer continuidade do corpo sem introduzir ramificações, repetições indevidas ou saltos.
4. Controlar o avanço do percurso até a extremidade final, preservando ordem, completude e parada segura.
5. Emitir a sequência ordenada de coordenadas em formato verificável, acompanhada de justificativa breve sobre o critério de percurso adotado.

### Resultados Esperados

- algoritmo ou código-fonte capaz de processar uma matriz bidimensional arbitrária;
- identificação correta da cabeça e das posições pertencentes à cobra;
- sequência ordenada de pares `[coluna, linha]`, da cabeça até a cauda;
- evidência de que o percurso não inclui células vazias nem repete posições indevidamente;
- justificativa breve e tecnicamente coerente sobre a ordem do percurso.

### Contexto de Aquisição

- **Curso/componente:** Introdução à Programação.
- **Organização:** preferencialmente individual.
- **Ambiente:** laboratório de programação, lista de exercícios ou avaliação prática escrita/computacional.
- **Avaliação:** centrada no artefato produzido, na correção da saída e na justificativa breve.

### Perfil do Público-Alvo

- estudantes em etapa inicial de formação em Computação;
- com familiaridade prévia com variáveis, tipos primitivos, seleção, repetição e matrizes;
- que necessitam consolidar leitura posicional em grade, rastreamento de estado e produção de saídas verificáveis;
- que se beneficiam de tarefas com forte relação entre estrutura de dados, controle de fluxo e correção observável.

### Nível de Proficiência (critérios e dimensões)

| Nível | Representação matricial e indexação | Controle de fluxo e adjacência | Reconstrução ordenada do percurso | Saída e verificabilidade |
|---|---|---|---|---|
| **N1 - Inicial** | Reconhece a existência de linhas e colunas, mas ainda confunde posição lógica e coordenada solicitada. | Identifica parcialmente a necessidade de verificar vizinhos, mas sem consistência nas decisões. | Registra partes da cobra, mas sem garantir ordem completa. | Produz saída incompleta ou em formato inconsistente. |
| **N2 - Intermediário** | Localiza a cabeça e acessa posições da matriz com apoio, cometendo poucos erros de índice. | Aplica condições simples para testar continuidade local, ainda com fragilidade em casos de borda. | Reconstrói parte significativa da trajetória, ainda com risco de omissão ou repetição. | Produz saída compreensível, mas com pequenas inconsistências de formatação ou justificativa. |
| **N3 - Proficiente** | Percorre a matriz com indexação consistente e distingue corretamente linha, coluna e formato de saída. | Decide corretamente a continuidade do percurso com seleção e testes consistentes de vizinhança. | Reconstrói toda a trajetória da cabeça à cauda, sem saltos e sem repetições indevidas. | Produz saída completa, ordenada e no formato exigido, com justificativa verificável. |
| **N4 - Avançado** | Generaliza a solução para diferentes dimensões, explicita convenções e previne ambiguidades de indexação. | Estrutura decisões robustas, com boa cobertura de bordas, continuidade e parada segura. | Mantém a trajetória ordenada com controle explícito do estado e justificativa técnica consistente. | Produz saída rigorosa, claramente justificável e facilmente auditável por teste ou inspeção. |

## 2. Seleção e Enumeração de Conhecimentos

**K01 — Modelo de execução e noção de estado (paradigma imperativo)**
- Compreende o programa como sequência de transições de estado ao longo da execução.
- Sustenta o acompanhamento de posição corrente, histórico do percurso e progresso da solução.
- Permite explicar operacionalmente como o algoritmo avança no grid.
- **Justificativa de mobilização na tarefa:** a task exige manter coerência entre posição atual, próxima posição válida e sequência já produzida.

**K02 — Variáveis, constantes e tipos primitivos**
- Permite representar índices, coordenadas, marcadores de controle e caracteres da matriz com tipos coerentes.
- Sustenta a distinção entre dados inteiros de posição e dados do tipo caractere que codificam a cobra.
- Favorece atribuições consistentes em uma solução iterativa introdutória.
- **Justificativa de mobilização na tarefa:** a implementação depende de variáveis para linha, coluna, estado de percurso e leitura de símbolos do grid.

**K04 — Expressões lógicas e condições**
- Viabiliza a formulação de testes booleanos sobre células válidas, limites do grid e continuidade do percurso.
- Sustenta a combinação de operadores relacionais e lógicos em decisões locais.
- Permite distinguir células da cobra, células vazias e situações de parada.
- **Justificativa de mobilização na tarefa:** a task depende de condições corretas para reconhecer adjacência válida, evitar células indevidas e determinar quando o percurso termina.

**K05 — Estrutura sequencial e E/S básica**
- Organiza a solução em fluxo verificável de leitura, processamento e emissão de resultados.
- Sustenta a geração de saídas no formato exigido pela atividade.
- Favorece a observabilidade do artefato por meio de entradas e saídas consistentes.
- **Justificativa de mobilização na tarefa:** a atividade cobra uma sequência ordenada de coordenadas em formato específico, tornando a E/S parte diretamente observável da solução.

**K06 — Estruturas de seleção**
- Permite escolher entre alternativas de continuidade do percurso com base em condições locais.
- Sustenta o tratamento de casos distintos durante a navegação pela matriz.
- Viabiliza decisões de avanço, rejeição de caminhos inválidos e encerramento do percurso.
- **Justificativa de mobilização na tarefa:** a solução precisa selecionar a próxima célula compatível com a trajetória da cobra e rejeitar alternativas incompatíveis.

**K07 — Estruturas de repetição**
- Permite realizar varreduras na matriz e repetir verificações até completar o percurso.
- Sustenta laços com condição de parada segura em problemas de processamento iterativo.
- Viabiliza percursos sistemáticos em estruturas bidimensionais.
- **Justificativa de mobilização na tarefa:** a solução precisa tanto percorrer a matriz quanto avançar iterativamente ao longo da cobra até a extremidade final.

**K08 — Vetores e matrizes em C**
- Permite representar, acessar e percorrer arranjos bidimensionais indexados.
- Sustenta leitura posicional, inspeção de vizinhança e processamento de elementos por índice.
- Viabiliza o tratamento da matriz como grid de símbolos com coordenadas observáveis.
- **Justificativa de mobilização na tarefa:** o núcleo do problema está na interpretação e no processamento correto de uma matriz bidimensional arbitrária.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Representar posições, símbolos e coordenadas de uma matriz bidimensional com variáveis e tipos coerentes ao problema.  
**K associados:** (K01, K02, K08)

**LO2.** Formular condições que permitam reconhecer adjacência válida, limites do grid e continuidade do percurso.  
**K associados:** (K04, K06, K08)

**LO3.** Controlar iterações com parada segura ao percorrer a matriz e reconstruir uma trajetória conectada.  
**K associados:** (K01, K07, K08)

**LO4.** Organizar o fluxo de processamento e a apresentação da saída em formato ordenado e verificável.  
**K associados:** (K02, K05, K08)

**LO5.** Justificar a escolha de estruturas de dados e de controle compatíveis com a natureza espacial e iterativa do problema.  
**K associados:** (K05, K06, K07, K08)

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver soluções introdutórias de programação para problemas que exigem representação estruturada de dados, controle de fluxo, processamento iterativo e produção de saídas verificáveis.

### 4.2 Especificações de Competências

#### CT09.1

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e constantes para representar posições, símbolos e estado do percurso.

**Descrição Textual**

Capacidade de representar dados elementares de um problema computacional por meio de variáveis, constantes e tipos coerentes, preservando a consistência entre estrutura de dados, estado do algoritmo e formato de saída.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO4)
- K mobilizados (Núcleo): (K01, K02, K05, K08)

**Especificação de Conhecimentos**
- **K01:** noção de estado ao longo da execução; evidenciado pela atualização coerente da posição corrente e da sequência produzida.
- **K02:** uso de tipos e variáveis coerentes; evidenciado pela representação de índices, coordenadas e caracteres do grid.
- **K05:** organização sequencial da entrada, processamento e saída; evidenciado pelo formato verificável da resposta.
- **K08:** manipulação de matriz bidimensional; evidenciado pelo acesso posicional e pela leitura correta do grid.

**Alinhamento com a Taxonomia de Bloom**
- Predominância: **Aplicar**
- Apoio complementar: **Compreender**
- Justificativa: a competência requer uso operacional de variáveis, tipos, estado e matriz em uma implementação verificável, sem demandar concepção estrutural mais ampla do que a exigida pela task.

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → manter o estado do percurso coerente ao longo das atualizações de posição.  
Verbos de Bloom: implementar, manipular, usar

K02 / Aplicar → representar índices, coordenadas e símbolos com tipos primitivos coerentes ao problema.  
Verbos de Bloom: usar, manipular, implementar

K05 / Aplicar → organizar entrada, processamento e saída para produzir uma resposta verificável no formato exigido.  
Verbos de Bloom: implementar, documentar, executar

K08 / Aplicar → acessar e percorrer posições de uma matriz bidimensional por índices válidos.  
Verbos de Bloom: mapear, iterar, usar


**Especificação de Disposições**
- atenção à consistência entre tipo e dado representado;
- cuidado com indexação e convenção de coordenadas;
- rigor na organização da saída;
- compromisso com verificabilidade do artefato.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT09.1 | Manipular dados com tipos primitivos, variáveis e constantes para representar posições, símbolos e estado do percurso | atenção, cuidado, rigor, compromisso | K01 | manter o estado do percurso coerente ao longo das atualizações de posição |
| CT09.1 | Manipular dados com tipos primitivos, variáveis e constantes para representar posições, símbolos e estado do percurso | atenção, cuidado, rigor, compromisso | K02 | representar índices, coordenadas e símbolos com tipos primitivos coerentes ao problema |
| CT09.1 | Manipular dados com tipos primitivos, variáveis e constantes para representar posições, símbolos e estado do percurso | atenção, cuidado, rigor, compromisso | K05 | organizar entrada, processamento e saída para produzir uma resposta verificável no formato exigido |
| CT09.1 | Manipular dados com tipos primitivos, variáveis e constantes para representar posições, símbolos e estado do percurso | atenção, cuidado, rigor, compromisso | K08 | acessar e percorrer posições de uma matriz bidimensional por índices válidos |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a solução depende de representação correta de índices, caracteres, coordenadas e estado de avanço. Sem essa ativação, o algoritmo não produz uma trajetória rastreável nem uma saída consistente.

#### CT09.2

**Título da Competência**  
Controlar o fluxo com decisões, formulando expressões lógicas corretas.

**Descrição Textual**

Capacidade de formular condições corretas e empregar estruturas de seleção para tomar decisões locais consistentes em problemas que exigem tratamento de casos, verificação de vizinhança e exclusão de alternativas inválidas.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2)
- K mobilizados (Núcleo): (K04, K06, K08)

**Especificação de Conhecimentos**
- **K04:** construção de condições lógicas; evidenciado pela distinção entre células válidas, limites e situações de parada.
- **K06:** uso de seleção para escolha de caminhos; evidenciado pela decisão sobre continuidade ou rejeição de alternativas locais.
- **K08:** leitura de vizinhança em matriz; evidenciado pela análise de posições adjacentes no grid.

**Alinhamento com a Taxonomia de Bloom**
- Predominância: **Analisar**
- Apoio complementar: **Aplicar**
- Justificativa: a competência exige examinar a relação entre regras do problema, conteúdo das células e posição no grid para fundamentar decisões condicionais corretas.

**Pareamento Conhecimento–Habilidade**

K04 / Analisar → examinar condições lógicas que distingam adjacência válida, borda e término do percurso.  
Verbos de Bloom: analisar, discriminar, relacionar

K06 / Aplicar → implementar decisões condicionais coerentes com as regras de continuidade do percurso.  
Verbos de Bloom: implementar, operar, usar

K08 / Analisar → relacionar posições vizinhas da matriz para sustentar decisões de continuidade sem saltos nem ramificações.  
Verbos de Bloom: rastrear, estruturar, relacionar

**Especificação de Disposições**
- rigor na formulação de condições;
- cautela no tratamento de bordas;
- atenção à exclusão de caminhos inválidos;
- compromisso com a coerência lógica da decisão.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT09.2 | Controlar o fluxo com decisões, formulando expressões lógicas corretas | rigor, cautela, atenção, compromisso | K04 | examinar condições lógicas que distingam adjacência válida, borda e término do percurso |
| CT09.2 | Controlar o fluxo com decisões, formulando expressões lógicas corretas | rigor, cautela, atenção, compromisso | K06 | implementar decisões condicionais coerentes com as regras de continuidade do percurso |
| CT09.2 | Controlar o fluxo com decisões, formulando expressões lógicas corretas | rigor, cautela, atenção, compromisso | K08 | relacionar posições vizinhas da matriz para sustentar decisões de continuidade sem saltos nem ramificações |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica e justificatória
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o percurso correto depende de decisões locais consistentes sobre adjacência, borda e continuidade. Essas decisões precisam ser tecnicamente justificáveis a partir das regras do grid.

#### CT09.3

**Título da Competência**  
Controlar o fluxo com repetição utilizando varredura, iteração e paradas seguras.

**Descrição Textual**

Capacidade de estruturar percursos iterativos em problemas introdutórios de programação, usando repetição de modo sistemático e seguro para localizar elementos, atualizar estado e completar uma tarefa sem perda de controle operacional.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3)
- K mobilizados (Núcleo): (K01, K07, K08)

**Especificação de Conhecimentos**
- **K01:** atualização de estado ao longo do laço; evidenciado pela manutenção da posição corrente e do avanço da trajetória.
- **K07:** uso de repetição com parada segura; evidenciado pela varredura da matriz e pelo avanço iterativo até a cauda.
- **K08:** percorrimento de matriz; evidenciado pela exploração sistemática de posições e pela reconstrução do trajeto no grid.

**Alinhamento com a Taxonomia de Bloom**
- Predominância: **Aplicar**
- Apoio complementar: **Analisar**
- Justificativa: a competência exige implementar laços corretos e monitorar seu comportamento durante a execução, com atenção à progressão do estado e à condição de parada.

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → atualizar a posição corrente e o histórico do percurso durante a iteração.  
Verbos de Bloom: implementar, manipular, operar

K07 / Aplicar → estruturar laços com parada segura para percorrer a matriz e seguir a trajetória conectada.  
Verbos de Bloom: iterar, implementar, usar

K08 / Aplicar → percorrer o grid de forma sistemática para localizar a cabeça e avançar pelas células conectadas.  
Verbos de Bloom: mapear, iterar, operar


**Especificação de Disposições**
- persistência na depuração de laços;
- cuidado com condição de parada;
- atenção à progressão do estado;
- compromisso com completude do percurso.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT09.3 | Controlar o fluxo com repetição utilizando varredura, iteração e paradas seguras | persistência, cuidado, atenção, compromisso | K01 | atualizar a posição corrente e o histórico do percurso durante a iteração |
| CT09.3 | Controlar o fluxo com repetição utilizando varredura, iteração e paradas seguras | persistência, cuidado, atenção, compromisso | K07 | estruturar laços com parada segura para percorrer a matriz e seguir a trajetória conectada |
| CT09.3 | Controlar o fluxo com repetição utilizando varredura, iteração e paradas seguras | persistência, cuidado, atenção, compromisso | K08 | percorrer o grid de forma sistemática para localizar a cabeça e avançar pelas células conectadas |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa só se completa quando o estudante controla a varredura e o avanço iterativo até o fim da trajetória. O desempenho observável depende diretamente de laços consistentes e de parada segura.

#### CT09.4

**Título da Competência**  
Selecionar estruturas adequadas ao problema e justificar as escolhas.

**Descrição Textual**

Capacidade de escolher, em nível introdutório, estruturas de dados e de controle compatíveis com a natureza do problema computacional, justificando tecnicamente a adequação dessas escolhas em função da representação, do processamento e da verificabilidade do resultado.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO5)
- K mobilizados (Núcleo): (K05, K06, K07, K08)

**Especificação de Conhecimentos**
- **K05:** organização sequencial da solução; evidenciado pela necessidade de estruturar um fluxo auditável de processamento e saída.
- **K06:** seleção como mecanismo de decisão local; evidenciado pela escolha entre alternativas de continuidade do percurso.
- **K07:** repetição como mecanismo de varredura e avanço; evidenciado pelo percurso iterativo até a extremidade final.
- **K08:** matriz como estrutura de representação espacial; evidenciado pela adequação do grid ao problema de rastreamento.

**Alinhamento com a Taxonomia de Bloom**
- Predominância: **Avaliar**
- Apoio complementar: **Analisar**
- Justificativa: a competência não se limita a usar estruturas prontas. Ela exige defender por que matriz, seleção, repetição e organização sequencial são escolhas adequadas para esse tipo de problema.

**Pareamento Conhecimento–Habilidade**

K05 / Avaliar → justificar a organização sequencial da solução para manter a verificabilidade da saída.  
Verbos de Bloom: argumentar, justificar, validar

K06 / Avaliar → justificar o uso de decisões condicionais para escolher o próximo passo do percurso.  
Verbos de Bloom: escolher, justificar, validar

K07 / Avaliar → justificar o uso de repetição para realizar varredura e avanço controlado até a cauda.  
Verbos de Bloom: decidir, avaliar, justificar

K08 / Avaliar → justificar a escolha da matriz como estrutura compatível com a representação espacial do problema.  
Verbos de Bloom: argumentar, defender, justificar


**Especificação de Disposições**
- reflexão sobre adequação estrutural;
- precisão na justificativa técnica;
- cuidado com coerência entre problema e solução;
- compromisso com explicitação de escolhas.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT09.4 | Selecionar estruturas adequadas ao problema e justificar as escolhas | reflexão, precisão, cuidado, compromisso | K05 | justificar a organização sequencial da solução para manter a verificabilidade da saída |
| CT09.4 | Selecionar estruturas adequadas ao problema e justificar as escolhas | reflexão, precisão, cuidado, compromisso | K06 | justificar o uso de decisões condicionais para escolher o próximo passo do percurso |
| CT09.4 | Selecionar estruturas adequadas ao problema e justificar as escolhas | reflexão, precisão, cuidado, compromisso | K07 | justificar o uso de repetição para realizar varredura e avanço controlado até a cauda |
| CT09.4 | Selecionar estruturas adequadas ao problema e justificar as escolhas | reflexão, precisão, cuidado, compromisso | K08 | justificar a escolha da matriz como estrutura compatível com a representação espacial do problema |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: justificatória
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade solicita não apenas um resultado funcional, mas também uma justificativa breve sobre a correção do percurso. Isso torna observável a adequação entre problema, estrutura escolhida e estratégia de solução.

