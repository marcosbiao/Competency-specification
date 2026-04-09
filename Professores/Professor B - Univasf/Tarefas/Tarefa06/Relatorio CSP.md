# RELATÓRIO CSP

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do Competency Specification Process (CSP) e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados pela TASK06. A tarefa solicita a implementação de duas transformações sucessivas sobre um arranjo unidimensional: um deslocamento para a posição seguinte e, em seguida, um deslocamento para a posição anterior, ambos com tratamento explícito das extremidades.

A tarefa elicita evidências observáveis porque o estudante precisa produzir um programa funcional, manipular corretamente índices e posições, controlar a atualização do estado do arranjo ao longo da execução e apresentar resultados verificáveis após cada etapa relevante. O artefato produzido permite observar diretamente a consistência da lógica empregada, o comportamento do programa e a justificativa breve associada ao processamento.

No modelo K–S–D, a tarefa mobiliza conhecimentos estruturais da disciplina, especialmente estado de programa, variáveis, estrutura sequencial, repetição e arranjos. As habilidades associadas são observáveis no código e nas saídas. As disposições, por sua vez, relacionam-se à precisão, à atenção às extremidades e ao compromisso com a verificabilidade. A especificação a seguir procura manter alta rastreabilidade e reuso, sem fragmentação excessiva.


## 1. Análise da Entidade Instrucional

### Título
**Deslocamento sequencial de elementos em arranjo unidimensional**

### Descrição
Atividade de programação introdutória voltada à manipulação de arranjos unidimensionais por meio de atualizações posicionais sucessivas. A tarefa exige que o estudante transforme o estado de um arranjo em duas etapas, preservando a coerência dos dados durante cada deslocamento, tratando perdas controladas de valores nas extremidades e registrando estados intermediários e finais de forma verificável.

### Processo de Desenvolvimento da Solução
1. Identificar o arranjo, o número de posições e as extremidades relevantes para a transformação.
2. Planejar o primeiro deslocamento, garantindo que os valores ainda necessários não sejam comprometidos durante a atualização.
3. Registrar o estado resultante da primeira transformação.
4. Aplicar a segunda transformação sobre o arranjo já modificado pela etapa anterior.
5. Produzir saídas que permitam verificar o estado inicial, o estado intermediário e o estado final.
6. Apresentar justificativa breve coerente com o comportamento observado.

### Resultados Esperados
- Programa funcional que implemente as duas transformações solicitadas.
- Evidência do estado inicial do arranjo.
- Evidência do estado após o deslocamento para a posição seguinte.
- Evidência do estado após o deslocamento para a posição anterior.
- Justificativa breve sobre a coerência das transformações e do tratamento das extremidades.

### Contexto de Aquisição
- **Curso/componente:** Introdução à Programação
- **Organização:** resolução individual
- **Ambiente:** laboratório de programação ou avaliação prática escrita/computacional
- **Avaliação:** baseada em código executável, saídas observáveis e justificativa breve
- **Natureza da evidência:** construtiva e verificável

### Perfil do Público-Alvo
- Estudantes em etapa inicial da formação em Computação.
- Com domínio prévio esperado de variáveis, atribuição, estrutura sequencial e laços introdutórios.
- Em processo de consolidação de acesso posicional, atualização de estado e manipulação de arranjos.
- Com necessidade formativa de maior precisão no tratamento de índices, fronteiras do arranjo e efeitos de atualização sucessiva.

### Nível de Proficiência (critérios e dimensões)

| Nível | Compreensão do arranjo e das posições | Controle da iteração | Consistência das atualizações de estado | Verificabilidade da solução |
|---|---|---|---|---|
| **N1 - Inicial** | Reconhece que o arranjo possui posições, mas ainda comete erros frequentes de indexação. | Usa laços com apoio, sem garantir coerência completa do percurso. | Atualiza posições, mas perde valores indevidamente ou mistura estados. | Apresenta pouca evidência do comportamento do programa. |
| **N2 - Intermediário** | Identifica corretamente posições e extremidades na maior parte dos casos. | Estrutura percursos válidos para processar o arranjo. | Realiza a transformação principal com pequenas fragilidades. | Mostra saídas suficientes para inspeção básica. |
| **N3 - Proficiente** | Manipula índices e fronteiras com consistência em toda a tarefa. | Seleciona e controla percursos adequados, preservando a integridade da transformação. | Mantém coerência entre estados inicial, intermediário e final, inclusive nas extremidades. | Registra e apresenta evidências completas e coerentes das duas etapas. |
| **N4 - Avançado** | Generaliza a lógica para variações estruturais com autonomia e precisão. | Reorganiza a lógica iterativa com alto grau de robustez e justificativa técnica. | Explicita invariantes e antecipa riscos de atualização com rigor superior ao esperado. | Documenta, compara e justifica os estados com elevado grau de precisão analítica. |

## 2. Seleção e Enumeração de Conhecimentos 

### K01 — Modelo de execução e noção de estado (paradigma imperativo)
- Compreensão de que o programa evolui por atualizações sucessivas de estado.
- Relação entre atribuição, ordem de execução e efeito sobre os dados armazenados.
- Leitura do comportamento do programa a partir das mudanças produzidas ao longo da execução.

**Justificativa de mobilização na tarefa:** a atividade depende da compreensão de que o arranjo sofre transformações sucessivas e de que cada etapa altera o estado que servirá de base para a etapa seguinte.

### K02 — Variáveis, constantes e tipos primitivos
- Uso de identificadores para armazenar dados e controlar a execução.
- Coerência entre o papel de cada variável e o valor manipulado.
- Emprego de valores primitivos em atualizações, controle e preenchimento.

**Justificativa de mobilização na tarefa:** a implementação exige variáveis coerentes para representar índices, tamanho do arranjo e valor de preenchimento nas extremidades.

### K05 — Estrutura sequencial e E/S básica
- Organização do programa em sequência verificável de ações.
- Leitura, processamento e apresentação de resultados em fluxo coerente.
- Produção de saídas que permitam inspecionar o comportamento do programa.

**Justificativa de mobilização na tarefa:** o estudante precisa estruturar a execução de modo que os estados relevantes do arranjo possam ser observados antes e após cada transformação.

### K07 — Estruturas de repetição
- Percorrimento iterativo de coleções homogêneas.
- Controle de laços por contagem e por condição de parada.
- Processamento repetido de posições com consistência operacional.

**Justificativa de mobilização na tarefa:** o deslocamento dos elementos requer varredura sistemática do arranjo e controle correto da repetição durante as atualizações.

### K08 — Vetores e matrizes em C
- Representação de coleções homogêneas indexadas.
- Acesso, leitura e atualização de elementos por posição.
- Percorrimento e processamento de arranjos com base em índices válidos.

**Justificativa de mobilização na tarefa:** o núcleo do problema é a manipulação de um arranjo unidimensional, com deslocamento posicional e tratamento explícito das extremidades.


## 3. Identificação de Objetivos de Aprendizagem

### LO1
Manipular arranjos unidimensionais por índice, preservando a correspondência entre posição lógica e posição armazenada.

**K associados:** (K02, K08)

### LO2
Implementar percursos iterativos que realizem transformações posicionais sobre arranjos sem comprometer a coerência do processamento.

**K associados:** (K01, K07, K08)

### LO3
Organizar o programa em fluxo verificável de entrada ou inicialização, processamento e saída dos estados relevantes do arranjo.

**K associados:** (K05, K08)

### LO4
Tratar corretamente as extremidades do arranjo em operações de deslocamento, com descarte controlado de valores e preenchimento coerente.

**K associados:** (K01, K02, K08)

### LO5
Justificar o comportamento da solução com base no estado intermediário e no estado final observados.

**K associados:** (K01, K05, K08)


## 4. Definição de Competências

### 4.1 Competência Geral

**Competência geral do domínio de Computação:** desenvolver programas introdutórios que transformem coleções homogêneas por meio de acesso posicional, controle iterativo e atualização consistente do estado do programa, produzindo evidências verificáveis do processamento realizado.

**Alinhamento à BNCC:** não se aplica neste contexto, por se tratar de componente curricular de nível superior em Introdução à Programação.



### 4.2 Especificações de Competências

## CT06.1

**Título da Competência**  
Implementar programas básicos em linguagem imperativa, organizando variáveis, atribuições e fluxo sequencial verificável.

**Descrição Textual**  
Construir programas introdutórios com estrutura sequencial coerente, utilizando variáveis e atualizações de estado de modo consistente, com resultados observáveis e tecnicamente verificáveis.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3, LO5)
- K mobilizados (Núcleo): (K01, K02, K05)

**Especificação de Conhecimentos**
- **K01:** noção de estado do programa e efeito das atribuições ao longo da execução.  
  **Justificativa de evidência:** a tarefa exige acompanhar transformações sucessivas do arranjo e interpretar seus estados.
- **K02:** uso coerente de variáveis, constantes e tipos primitivos no controle e na atualização de dados.  
  **Justificativa de evidência:** a solução depende de variáveis compatíveis com índices, tamanho do arranjo e valor de preenchimento.
- **K05:** organização sequencial da solução e produção de saídas verificáveis.  
  **Justificativa de evidência:** os estados do arranjo devem ser apresentados de forma consistente antes e após as transformações.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio de **Aplicar**.

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → explicitar o estado do programa por meio de atribuições coerentes durante a transformação do arranjo.  
Verbos de Bloom: implementar, operar, realizar

K02 / Aplicar → utilizar variáveis e valores primitivos compatíveis com o controle do processamento e com o preenchimento das extremidades.  
Verbos de Bloom: usar, configurar, implementar

K05 / Aplicar → organizar o fluxo de entrada ou inicialização, processamento e saída de modo verificável.  
Verbos de Bloom: organizar, executar, apresentar


**Especificação de Disposições**  
- precisão operacional  
- atenção à consistência do estado  
- compromisso com verificabilidade

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT06.1 | Implementar programas básicos em linguagem imperativa, organizando variáveis, atribuições e fluxo sequencial verificável | precisão operacional; consistência do estado; verificabilidade | K01 | explicitar o estado do programa por meio de atribuições coerentes durante a transformação do arranjo |
| CT06.1 | Implementar programas básicos em linguagem imperativa, organizando variáveis, atribuições e fluxo sequencial verificável | precisão operacional; consistência do estado; verificabilidade | K02 | utilizar variáveis e valores primitivos compatíveis com o controle do processamento e com o preenchimento das extremidades |
| CT06.1 | Implementar programas básicos em linguagem imperativa, organizando variáveis, atribuições e fluxo sequencial verificável | precisão operacional; consistência do estado; verificabilidade | K05 | organizar o fluxo de entrada ou inicialização, processamento e saída de modo verificável |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade exige implementação efetiva de um programa introdutório com variáveis, atribuições e saídas observáveis. Sem essa ativação, não há artefato executável nem evidência verificável do processamento.


## CT06.2

**Título da Competência**  
Controlar o fluxo com repetição para percorrer e transformar coleções homogêneas com parada segura.

**Descrição Textual**  
Empregar estruturas de repetição para percorrer coleções homogêneas e aplicar transformações sucessivas, preservando a ordem do processamento e garantindo término correto do laço.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO4)
- K mobilizados (Núcleo): (K01, K07, K08)

**Especificação de Conhecimentos**
- **K01:** compreensão do estado do programa durante transformações sucessivas.  
  **Justificativa de evidência:** o deslocamento depende da leitura correta do efeito de cada atualização sobre o arranjo.
- **K07:** estruturas de repetição com controle de percurso e parada.  
  **Justificativa de evidência:** o problema exige varredura sistemática do arranjo por laço.
- **K08:** acesso e atualização de posições em coleções homogêneas indexadas.  
  **Justificativa de evidência:** a transformação solicitada é realizada diretamente sobre os elementos do vetor.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, com apoio de **Analisar**.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → rastrear o efeito de cada atualização sobre o estado intermediário e final do arranjo.  
Verbos de Bloom: rastrear, examinar, estruturar

K07 / Aplicar → controlar laços de repetição para percorrer o arranjo com término correto e sem perda indevida de posições relevantes.  
Verbos de Bloom: iterar, implementar, operar

K08 / Aplicar → processar coleções homogêneas indexadas por meio de percursos adequados às transformações requeridas.  
Verbos de Bloom: manipular, implementar, resolver


**Especificação de Disposições**  
- disciplina na ordem de atualização  
- atenção ao término do laço  
- cautela com as extremidades do arranjo

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT06.2 | Controlar o fluxo com repetição para percorrer e transformar coleções homogêneas com parada segura | disciplina na ordem; atenção ao término; cautela com extremidades | K01 | rastrear o efeito de cada atualização sobre o estado intermediário e final do arranjo |
| CT06.2 | Controlar o fluxo com repetição para percorrer e transformar coleções homogêneas com parada segura | disciplina na ordem; atenção ao término; cautela com extremidades | K07 | controlar laços de repetição para percorrer o arranjo com término correto e sem perda indevida de posições relevantes |
| CT06.2 | Controlar o fluxo com repetição para percorrer e transformar coleções homogêneas com parada segura | disciplina na ordem; atenção ao término; cautela com extremidades | K08 | processar coleções homogêneas indexadas por meio de percursos adequados às transformações requeridas |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a lógica central do problema depende de repetição para percorrer o arranjo e aplicar deslocamentos sucessivos. A correção da solução depende diretamente do controle adequado do laço e das fronteiras de percurso.


## CT06.3

**Título da Competência**  
Representar e processar coleções homogêneas com vetores e matrizes.

**Descrição Textual**  
Selecionar e manipular estruturas homogêneas indexadas para armazenar, acessar e transformar dados por posição, preservando coerência entre índices, valores e efeito global do processamento.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO2, LO4)
- K mobilizados (Núcleo): (K02, K07, K08)

**Especificação de Conhecimentos**
- **K02:** variáveis e valores associados ao controle e à atualização de dados na estrutura.  
  **Justificativa de evidência:** a solução requer uso consistente de índices, tamanho e valor de preenchimento.
- **K07:** repetição como mecanismo de percorrimento e transformação da coleção.  
  **Justificativa de evidência:** o vetor precisa ser percorrido integralmente para realizar o deslocamento.
- **K08:** vetores e matrizes como estruturas homogêneas indexadas.  
  **Justificativa de evidência:** o problema incide diretamente sobre acesso posicional, deslocamento e atualização de elementos.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → utilizar variáveis compatíveis com a representação do tamanho, das posições e do valor de preenchimento da coleção.  
Verbos de Bloom: usar, configurar, realizar

K07 / Aplicar → percorrer a coleção homogênea com laços adequados ao processamento completo de seus elementos.  
Verbos de Bloom: iterar, implementar, operar

K08 / Aplicar → representar e transformar coleções homogêneas indexadas por meio de acesso posicional e atualização consistente de elementos.  
Verbos de Bloom: manipular, implementar, resolver


**Especificação de Disposições**  
- precisão na indexação  
- atenção à integridade da coleção  
- rigor no tratamento das fronteiras

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT06.3 | Representar e processar coleções homogêneas com vetores e matrizes | precisão na indexação; integridade da coleção; rigor nas fronteiras | K02 | utilizar variáveis compatíveis com a representação do tamanho, das posições e do valor de preenchimento da coleção |
| CT06.3 | Representar e processar coleções homogêneas com vetores e matrizes | precisão na indexação; integridade da coleção; rigor nas fronteiras | K07 | percorrer a coleção homogênea com laços adequados ao processamento completo de seus elementos |
| CT06.3 | Representar e processar coleções homogêneas com vetores e matrizes | precisão na indexação; integridade da coleção; rigor nas fronteiras | K08 | representar e transformar coleções homogêneas indexadas por meio de acesso posicional e atualização consistente de elementos |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica/construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o enunciado exige diretamente a manipulação de um arranjo unidimensional, com deslocamento de elementos e tratamento das extremidades. Esta é a competência mais diretamente diagnosticada pelos produtos da tarefa.