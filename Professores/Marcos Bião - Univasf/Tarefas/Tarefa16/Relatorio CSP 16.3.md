# RELATÓRIO CSP
## TASK16.3 | Autoria de Competências

## Introdução

Este relatório situa a **TASK16.3** na fase de **Autoria de Competências** do Competency Specification Process. A tarefa consiste em uma maratona prática de programação em C, com resolução de problemas envolvendo vetores, matrizes, contagens, somas, verificações e construção de função simples com retorno, em ambiente de laboratório e sob correção por juiz automático. Essas características tornam as evidências observáveis, pois o desempenho se materializa em programas fonte, submissões válidas e saídas compatíveis com especificações formais.

A tarefa suporta o modelo **K–S–D** sem redundância porque mobiliza um subconjunto bem delimitado de conhecimentos do catálogo da disciplina, os converte em objetivos de aprendizagem reutilizáveis e os organiza em competências de Computação que permanecem válidas em outras tarefas introdutórias da mesma disciplina. O foco avaliativo recai sobre a correção funcional, a consistência entre entrada, processamento e saída e a adequação estrutural da implementação em C.

# 1. Análise da Entidade Instrucional

## 1.1 Título

**Maratona de Programação em C com Vetores, Matrizes e Funções**

## 1.2 Descrição

Trata se de uma atividade prática de programação introdutória, realizada em equipes, em que os estudantes devem resolver o maior número possível de problemas no tempo estipulado. Os problemas exigem implementação em C e cobrem processamento de dados com vetores, matrizes e funções, sempre com validação por juiz automático e testes não conhecidos previamente.

## 1.3 Processo de Desenvolvimento da Solução

1. Ler e interpretar cada enunciado, identificando entradas, processamento e saídas.
2. Selecionar estruturas adequadas para representar os dados do problema.
3. Planejar a lógica da solução, com laços, condições e cálculos necessários.
4. Implementar o programa em C, preservando coerência entre dados lidos, transformação realizada e saída exigida.
5. Quando pertinente, modularizar partes da solução com função simples e retorno.
6. Submeter a solução ao sistema e verificar aceitação ou inconsistências observáveis.

## 1.4 Resultados Esperados

* Programas em C corretos para os problemas resolvidos.
* Arquivos fonte organizados por problema.
* Submissões válidas registradas no sistema.
* Saídas compatíveis com o enunciado.
* Aceitação no juiz automático, quando a solução estiver correta.

### 1.5 Contexto de Aquisição
- **Curso/organização:** disciplina de Introdução à Programação, em nível de graduação.
- **Ambiente:** laboratório, com computador compartilhado por equipe.
- **Forma de realização:** equipes de até três integrantes, com rodízio de operador a cada vinte minutos.
- **Restrições:** duas horas de duração, consulta apenas a material impresso e sem acesso à internet.
- **Avaliação:** correção funcional por juiz automático, com foco em aderência ao enunciado, consistência entre entrada, processamento e saída e submissão válida.

## 1.6 Perfil do Público Alvo

| Dimensão | Caracterização |
|---|---|
| Nível | Estudantes de disciplina introdutória de programação |
| Pré requisitos | Sintaxe básica em C, variáveis, expressões, entrada e saída, estruturas de controle |
| Necessidades | Consolidar processamento de coleções homogêneas, decisões, iterações e modularização simples |
| Exigência cognitiva | Traduzir enunciados em algoritmos verificáveis sob restrição de tempo |

## 1.7 Nível de Proficiência (critérios e dimensões)

| Nível | Interpretação do problema | Representação dos dados | Controle de fluxo | Modularização | Correção e verificabilidade |
|---|---|---|---|---|---|
| **N1 - Inicial** | Identifica apenas partes isoladas do enunciado | Escolhe estruturas de forma pouco consistente | Usa laços e condições com erros frequentes | Não decompõe a solução | Produz saídas inconsistentes |
| **N2 - Intermediário** | Reconhece entradas, saídas e regra principal | Usa vetores, matrizes e variáveis de modo funcional | Implementa fluxo básico correto | Usa função simples quando solicitado | Resolve casos principais com pequenas falhas |
| **N3 - Proficiente** | Organiza casos e restrições com precisão | Seleciona e articula estruturas com adequação | Combina decisões e iterações com estabilidade | Define funções coesas com parâmetros e retorno corretos | Atende integralmente à especificação |
| **N4 - Avançado** | Antecipa casos limite e inconsistências | Otimiza a representação conforme o problema | Estrutura fluxos robustos e claros | Reorganiza a solução com alto reuso | Mantém correção inclusive em casos limite e sob validação automatizada |

# 2. Seleção e Enumeração de Conhecimentos

Foi selecionado um subconjunto de **8 conhecimentos** do catálogo fixo da disciplina, compatível com o escopo da tarefa e suficiente para cobrir as evidências observáveis centrais.

## K02 — Variáveis, constantes e tipos primitivos

* Representação de dados simples em variáveis e constantes.
* Escolha coerente de tipos numéricos e caracteres.
* Uso consistente de atribuição e armazenamento de valores.

**Justificativa de mobilização na tarefa:** a atividade exige leitura e manipulação de dados em C, com coerência entre papel do dado e tipo utilizado.

## K03 — Expressões aritméticas e avaliação

* Construção de cálculos com operadores aritméticos.
* Avaliação correta de expressões.
* Atualização de resultados por atribuição.

**Justificativa de mobilização na tarefa:** contagens, somas e processamento de valores dependem de cálculo correto e composição aritmética estável.

## K04 — Expressões lógicas e condições

* Construção de condições booleanas.
* Interpretação de verdade e falsidade.
* Formulação de verificações compatíveis com regras do problema.

**Justificativa de mobilização na tarefa:** a tarefa envolve verificação de propriedades em matrizes, comparação de respostas e checagens que exigem condições corretas.

## K05 — Estrutura sequencial e E/S básica

* Organização do fluxo entrada → processamento → saída.
* Leitura e exibição de dados em formato verificável.
* Encadeamento coerente de comandos.

**Justificativa de mobilização na tarefa:** todas as soluções precisam ler dados, processá los e produzir saídas estritamente compatíveis com o enunciado e com o juiz automático.

## K06 — Estruturas de seleção

* Escolha de caminhos alternativos com base em condições.
* Cobertura de casos distintos.
* Implementação de regras de decisão.

**Justificativa de mobilização na tarefa:** vários problemas pedem verificação, classificação ou transformação condicionada de dados.

## K07 — Estruturas de repetição

* Percorrimento iterativo de dados.
* Controle de laços por contagem ou condição.
* Acumulação e processamento repetido.

**Justificativa de mobilização na tarefa:** vetores e matrizes demandam varredura, contagem, soma e análise iterativa.

## K08 — Vetores e matrizes em C

* Representação de coleções homogêneas unidimensionais e bidimensionais.
* Acesso por índice e percorrimento.
* Leitura, atualização e processamento posicional.

**Justificativa de mobilização na tarefa:** o núcleo explícito da atividade envolve manipulação de vetores e matrizes em linguagem C.

## K11 — Subprogramas: procedimentos e funções

* Definição e chamada de funções.
* Uso de parâmetros e retorno.
* Organização modular introdutória da solução.

**Justificativa de mobilização na tarefa:** a descrição pedagógica inclui explicitamente construção de função simples com retorno.

# 3. Identificação de Objetivos de Aprendizagem

## LO1
Implementar programas em C com fluxo verificável de entrada, processamento e saída, respeitando o formato exigido.

**K associados:** K02, K05

## LO2
Processar vetores e matrizes por meio de percorrimento, indexação e atualização coerente dos elementos.

**K associados:** K07, K08

## LO3
Realizar contagens, somas e agregações simples sobre dados numéricos em problemas introdutórios.

**K associados:** K02, K03, K07, K08

## LO4
Formular condições e decisões corretas para verificar propriedades, comparar valores e tratar casos distintos.

**K associados:** K04, K06, K07, K08

## LO5
Definir e utilizar funções simples com parâmetros e retorno compatíveis com a parte do problema que se deseja modularizar.

**K associados:** K02, K05, K11

Os objetivos acima foram formulados para reuso em outras tarefas da disciplina, evitando dependência excessiva do enunciado específico desta maratona.

# 4. Definição de Competências

## 4.1 Competência Geral

**Construir soluções corretas em linguagem C para problemas introdutórios de processamento de dados, articulando estruturas de entrada e saída, controle de fluxo, coleções homogêneas e modularização simples, com verificabilidade por testes.**

## 4.2 Especificações de Competências

As competências abaixo foram derivadas das evidências da tarefa, do catálogo fixo de conhecimentos da disciplina e dos verbos da taxonomia de Bloom fornecida.

### CT16.3.1

**Título da Competência**  
Representar e processar coleções homogêneas com vetores e matrizes em C

**Descrição Textual**  
Manipular dados organizados em vetores e matrizes, realizando leitura, percorrimento, atualização e processamento posicional de forma correta e verificável em linguagem C.

**Cobertura e rastreabilidade**  
* LOs cobertos: LO2, LO3  
* K mobilizados (Núcleo): K07, K08

**Especificação de Conhecimentos**  
* **K07:** estruturas de repetição permitem varrer coleções e realizar processamento acumulativo; a evidência aparece no percorrimento correto de vetores e matrizes.
* **K08:** vetores e matrizes definem a estrutura central dos dados da tarefa; a evidência aparece na indexação, leitura e transformação das posições.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio de **Aplicar**, com traços de **Analisar** quando a solução exige organizar o percorrimento adequado para diferentes dimensões.

**Pareamento Conhecimento–Habilidade**

K07 / Aplicar / executar → percorrer coleções homogêneas com laços compatíveis com a dimensão e o objetivo do processamento.  
K08 / Aplicar / implementar → ler, indexar e atualizar vetores e matrizes de modo consistente com a estrutura do problema.


**Especificação de Disposições**  
* precisão no acesso posicional
* atenção à consistência estrutural
* persistência na validação da solução

**Competências Alinhadas à BNCC**  
Não aplicável diretamente.

**Tabela Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.3.1 | Representar e processar coleções homogêneas com vetores e matrizes em C | precisão, consistência estrutural, persistência | K07 | percorrer coleções com laços compatíveis |
| CT16.3.1 | Representar e processar coleções homogêneas com vetores e matrizes em C | precisão, consistência estrutural, persistência | K08 | ler, indexar e atualizar vetores e matrizes |

**Definição de Ativação**  
* Restrição de ativação: obrigatória  
* Modo de ativação: construtiva  
* Função de ativação: núcleo  
* Justificativa: a atividade declara explicitamente problemas com vetores e matrizes. O desempenho correto depende da implementação efetiva dessas estruturas no código submetido.

### CT16.3.2

**Título da Competência**  
Controlar decisões e verificações lógicas em problemas de processamento de dados

**Descrição Textual**  
Formular condições e estruturas de decisão para verificar propriedades, comparar valores e conduzir transformações ou classificações coerentes durante o processamento de dados em C.

**Cobertura e rastreabilidade**  
* LOs cobertos: LO4  
* K mobilizados (Núcleo): K04, K06, K08

**Especificação de Conhecimentos**  
* **K04:** expressões lógicas sustentam as verificações de propriedades e comparações; a evidência aparece na formulação correta das condições.
* **K06:** estruturas de seleção organizam o tratamento de casos distintos; a evidência aparece em desvios coerentes no programa.
* **K08:** vetores e matrizes são o contexto sobre o qual muitas decisões incidem; a evidência aparece quando condições dependem de posições e valores da coleção.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio de **Analisar**, pois o estudante precisa distinguir estados e regras do problema antes de selecionar o caminho de execução adequado.

**Pareamento Conhecimento–Habilidade**

K04 / Analisar / analisar → formular condições lógicas corretas para verificar propriedades de dados e estados do processamento.  
K06 / Aplicar / implementar → implementar decisões coerentes para tratar casos distintos previstos na especificação.  
K08 / Aplicar / manipular → vincular verificações e decisões aos elementos e posições de vetores ou matrizes.

**Especificação de Disposições**  
* rigor na formulação de condições
* atenção a casos distintos
* cautela com erros de lógica

**Competências Alinhadas à BNCC**  
Não aplicável diretamente.

**Tabela Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.3.2 | Controlar decisões e verificações lógicas em problemas de processamento de dados | rigor, atenção a casos, cautela | K04 | formular condições lógicas corretas |
| CT16.3.2 | Controlar decisões e verificações lógicas em problemas de processamento de dados | rigor, atenção a casos, cautela | K06 | implementar decisões coerentes |
| CT16.3.2 | Controlar decisões e verificações lógicas em problemas de processamento de dados | rigor, atenção a casos, cautela | K08 | vincular decisões às estruturas de dados |

**Definição de Ativação**  
* Restrição de ativação: obrigatória  
* Modo de ativação: analítica  
* Função de ativação: núcleo  
* Justificativa: a tarefa envolve verificação e transformação de matrizes, além de comparação de respostas e checagens de valores, o que exige análise lógica explícita no código.

### CT16.3.3

**Título da Competência**  
Implementar soluções verificáveis em C com consistência entre entrada, processamento e saída

**Descrição Textual**  
Desenvolver programas em C que mantenham coerência entre leitura de dados, transformação computacional e apresentação dos resultados, produzindo comportamento compatível com especificações formais e validação automatizada.

**Cobertura e rastreabilidade**  
* LOs cobertos: LO1, LO3  
* K mobilizados (Núcleo): K02, K03, K05, K07

**Especificação de Conhecimentos**  
* **K02:** tipos e variáveis sustentam a representação correta dos dados de entrada e dos resultados intermediários.
* **K03:** expressões aritméticas viabilizam somas, contagens e cálculos exigidos nos problemas.
* **K05:** a estrutura sequencial organiza o fluxo completo de entrada, processamento e saída.
* **K07:** laços garantem o processamento repetido e acumulativo necessário em vários enunciados.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio de **Aplicar**, pois a competência se evidencia na implementação funcional correta e na aderência ao formato exigido.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar / implementar → declarar e utilizar variáveis e tipos compatíveis com o papel computacional de cada dado.  
K03 / Aplicar / calcular → realizar cálculos e atualizações aritméticas coerentes com o resultado esperado.  
K05 / Aplicar / executar → estruturar o fluxo de entrada, processamento e saída de modo verificável.  
K07 / Aplicar / iterar → controlar repetições necessárias para leitura, contagem e agregação de dados.


**Especificação de Disposições**  
* precisão sintático semântica
* disciplina na validação
* atenção ao formato de saída
* responsabilidade técnica na submissão

**Competências Alinhadas à BNCC**  
Não aplicável diretamente.

**Tabela Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.3.3 | Implementar soluções verificáveis em C com consistência entre entrada, processamento e saída | precisão, disciplina, atenção, responsabilidade | K02 | declarar e utilizar tipos coerentes |
| CT16.3.3 | Implementar soluções verificáveis em C com consistência entre entrada, processamento e saída | precisão, disciplina, atenção, responsabilidade | K03 | realizar cálculos e atualizações corretas |
| CT16.3.3 | Implementar soluções verificáveis em C com consistência entre entrada, processamento e saída | precisão, disciplina, atenção, responsabilidade | K05 | estruturar fluxo verificável de E/S |
| CT16.3.3 | Implementar soluções verificáveis em C com consistência entre entrada, processamento e saída | precisão, disciplina, atenção, responsabilidade | K07 | controlar repetições de processamento |

**Definição de Ativação**  
* Restrição de ativação: obrigatória  
* Modo de ativação: construtiva  
* Função de ativação: núcleo  
* Justificativa: a correção funcional e a aceitação no juiz automático dependem diretamente da coerência entre entrada, processamento e saída, que constitui critério explícito de avaliação da tarefa.

### CT16.3.4

**Título da Competência**  
Modularizar soluções introdutórias por meio de funções simples com retorno

**Descrição Textual**  
Organizar partes delimitadas da solução em funções simples, com parâmetros e retorno coerentes, de modo a tornar o programa mais claro, verificável e compatível com a lógica do problema.

**Cobertura e rastreabilidade**  
* LOs cobertos: LO5  
* K mobilizados (Núcleo): K05, K11, K02

**Especificação de Conhecimentos**  
* **K05:** a estrutura sequencial sustenta o encadeamento entre chamadas e resultados.
* **K11:** funções materializam a decomposição modular exigida na tarefa.
* **K02:** tipos e variáveis garantem compatibilidade entre parâmetros, retorno e uso no programa principal.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomínio de **Aplicar**, com aproximação de **Criar** em grau controlado, pois há implementação de subprograma simples, mas não projeto avançado de arquitetura.

**Pareamento Conhecimento–Habilidade**

K05 / Aplicar / executar → integrar chamadas de função ao fluxo principal do programa sem comprometer a verificabilidade da solução.  
K11 / Aplicar / implementar → definir e invocar funções simples com responsabilidade delimitada e retorno coerente.  
K02 / Aplicar / configurar → tipar parâmetros, variáveis locais e retorno de modo compatível com a operação realizada.


**Especificação de Disposições**  
* organização modular
* clareza técnica
* atenção à coerência entre partes
* zelo pela legibilidade funcional

**Competências Alinhadas à BNCC**  
Não aplicável diretamente.

**Tabela Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.3.4 | Modularizar soluções introdutórias por meio de funções simples com retorno | organização, clareza, coerência, zelo | K05 | integrar chamadas ao fluxo principal |
| CT16.3.4 | Modularizar soluções introdutórias por meio de funções simples com retorno | organização, clareza, coerência, zelo | K11 | definir e invocar funções simples |
| CT16.3.4 | Modularizar soluções introdutórias por meio de funções simples com retorno | organização, clareza, coerência, zelo | K02 | tipar parâmetros e retorno corretamente |

**Definição de Ativação**  
* Restrição de ativação: obrigatória  
* Modo de ativação: construtiva  
* Função de ativação: núcleo  
* Justificativa: a descrição pedagógica inclui explicitamente construção de função simples com retorno, de modo que a modularização não é acessória, mas evidência direta da tarefa.

