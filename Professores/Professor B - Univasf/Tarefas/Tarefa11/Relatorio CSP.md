# Relatório CSP Revisado  
## TASK11: Cálculo iterativo do cosseno por série em subprograma

## Introdução

Este relatório enquadra a tarefa na fase de **Autoria de Competências** do **Competency Specification Process (CSP)**, com foco na explicitação rastreável de conhecimentos, objetivos de aprendizagem e competências mobilizados por uma atividade introdutória de programação. A tarefa solicita a implementação de um programa que percorra uma faixa de valores reais, calcule o cosseno por aproximação em série e apresente os resultados correspondentes.

A tarefa produz evidências observáveis porque exige um artefato executável com laço de varredura, cálculo numérico iterativo, uso consistente de variáveis e organização do cálculo em subprograma, conforme explicitado no enunciado. Esses elementos permitem verificar diretamente a coerência entre especificação, implementação e saída produzida.

A estrutura K–S–D é sustentada sem redundância porque o relatório seleciona apenas os conhecimentos do catálogo que são diretamente mobilizados pela atividade, formula objetivos de aprendizagem reutilizáveis e consolida competências estáveis do domínio de programação introdutória. Nesta versão revisada, os **Ks de apoio foram removidos**, mantendo apenas os conhecimentos diretamente mobilizados em cada competência.

## 1. Análise da Entidade Instrucional

### Título
**TASK11: Cálculo iterativo do cosseno por série em subprograma**

### Descrição
Atividade prática de programação introdutória, de natureza individual, centrada na implementação de um programa numérico que percorre uma faixa de valores reais, calcula resultados por aproximação iterativa e apresenta saída tabulada. A especificação exige repetição, cálculo acumulativo, uso de expressões aritméticas e organização do cálculo em subprograma.

### Processo de Desenvolvimento da Solução
1. Interpretar a faixa de valores a ser percorrida e a forma esperada de saída.
2. Definir o fluxo principal responsável pela varredura dos valores de entrada.
3. Estruturar o cálculo iterativo do cosseno com quantidade fixa de parcelas.
4. Organizar esse cálculo em um subprograma, conforme exigido no enunciado.
5. Integrar a chamada ao subprograma à impressão dos resultados.
6. Verificar a cobertura do intervalo, a consistência do cálculo e a legibilidade da saída.

### Resultados Esperados
* Código-fonte completo do programa.
* Subprograma responsável pelo cálculo do cosseno.
* Saída tabulada contendo, para cada valor processado, o valor correspondente calculado.
* Evidências de coerência entre repetição, cálculo iterativo e organização do programa.

### Contexto de Aquisição
- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### Perfil do Público-Alvo
* Estudantes em etapa inicial da formação em programação.
* Pré-requisitos plausíveis: noção de variáveis, tipos primitivos, expressões aritméticas, estrutura sequencial, repetição e subprogramas introdutórios.
* Necessidades formativas centrais: controlar laços com segurança, manter coerência do cálculo iterativo e organizar o programa de modo verificável.

### Nível de Proficiência (critérios e dimensões)

| Nível | Organização do fluxo do programa | Controle de repetição | Cálculo numérico iterativo | Organização do cálculo em subprograma | Verificabilidade da saída |
|---|---|---|---|---|---|
| **N1 - Inicial** | Constrói sequência simples com forte dependência de exemplos. | Usa laços simples com apoio intenso. | Aplica expressões isoladas sem controle consistente da acumulação. | Reconhece a existência de subprogramas, mas não os utiliza com autonomia. | Produz saída incompleta ou pouco rastreável. |
| **N2 - Intermediário** | Organiza fluxo principal com alguma autonomia, mas ainda com lacunas de consistência. | Controla repetição por contagem ou faixa, mas com risco de inconsistência na parada. | Implementa cálculos iterativos básicos com apoio. | Implementa subprograma simples com orientação parcial. | Produz saída parcialmente verificável. |
| **N3 - Proficiente** | Estrutura fluxo principal coerente, legível e verificável. | Implementa laços com critério de término consistente e cobertura adequada do domínio. | Mantém coerência entre termos, acumuladores e atualizações sucessivas. | Organiza o cálculo exigido em subprograma com parâmetros e retorno compatíveis. | Produz saída organizada, comparável e adequada à inspeção. |
| **N4 - Avançado** | Refina a arquitetura do programa com alto controle estrutural. | Generaliza estratégias iterativas com maior robustez. | Otimiza ou compara estratégias de cálculo com maior sofisticação. | Reorganiza o cálculo em estruturas mais gerais e reutilizáveis. | Produz saída com refinamentos adicionais de rastreabilidade. |


## 2. Seleção e Enumeração de Conhecimentos

Foram selecionados **6 conhecimentos** do catálogo, número suficiente para cobrir a tarefa com rastreabilidade e sem inflar a granularidade.

### K01 — Modelo de execução e noção de estado (paradigma imperativo)
* Compreende que o programa evolui por atualizações sucessivas de estado durante a execução.
* Sustenta o acompanhamento de variáveis de controle, acumuladores e resultados parciais.
* Permite explicar a relação entre cada iteração e a transformação do estado do programa.

**Justificativa de mobilização na tarefa:** o cálculo por série e a varredura do intervalo dependem de atualizações sucessivas de variáveis, o que torna o estado do programa diretamente observável.

### K02 — Variáveis, constantes e tipos primitivos
* Representa dados numéricos por meio de variáveis e constantes adequadas ao problema.
* Exige coerência entre papéis de dados, parâmetros, retorno e resultados intermediários.
* Sustenta o uso apropriado de tipos primitivos em cálculos e saídas numéricas.

**Justificativa de mobilização na tarefa:** a solução envolve valores reais, contadores, termos intermediários e retorno de subprograma, exigindo tipagem e uso coerente de variáveis.

### K03 — Expressões aritméticas e avaliação
* Organiza expressões numéricas compostas, respeitando estrutura operacional coerente.
* Sustenta cálculos iterativos com múltiplos termos e atualizações sucessivas.
* Permite verificar a consistência de resultados intermediários e finais.

**Justificativa de mobilização na tarefa:** o problema exige implementação computacional de uma série numérica, tornando centrais as expressões aritméticas e sua avaliação iterativa.

### K05 — Estrutura sequencial e E/S básica
* Organiza o fluxo principal do programa em sequência verificável.
* Sustenta a produção de saídas legíveis e comparáveis.
* Articula processamento e apresentação dos resultados.

**Justificativa de mobilização na tarefa:** a atividade exige organização sequencial clara e saída tabulada observável.

### K07 — Estruturas de repetição
* Controla execuções repetidas com base em contagem ou progressão de valores.
* Exige critérios de parada coerentes e cobertura adequada do domínio processado.
* Sustenta tanto laços do fluxo principal quanto laços internos de cálculo iterativo.

**Justificativa de mobilização na tarefa:** a atividade depende diretamente de repetição para percorrer os valores de entrada e para computar a quantidade fixa de parcelas da série.

### K11 — Subprogramas: procedimentos e funções
* Decompõe o problema em subprogramas coesos com parâmetros e retorno compatíveis.
* Permite separar a rotina de cálculo do fluxo principal do programa.
* Sustenta organização modular e verificabilidade localizada do comportamento.

**Justificativa de mobilização na tarefa:** o enunciado exige explicitamente que o cálculo do cosseno seja implementado em subprograma.

## 3. Identificação de Objetivos de Aprendizagem

### LO1
**Organizar o fluxo principal de um programa numérico de modo sequencial e verificável, produzindo saída legível e rastreável.**  
**K associados:** K05, K02

### LO2
**Controlar varreduras numéricas por repetição, assegurando cobertura do domínio solicitado e parada consistente.**  
**K associados:** K07, K05, K02

### LO3
**Implementar cálculo iterativo com atualização coerente de variáveis e uso consistente de expressões aritméticas.**  
**K associados:** K01, K03, K02

### LO4
**Organizar um cálculo específico em subprograma com parâmetros e retorno compatíveis com o problema.**  
**K associados:** K11, K02, K05

### LO5
**Integrar fluxo principal, repetição, cálculo numérico e subprograma em uma solução completa e verificável.**  
**K associados:** K05, K07, K11, K01

## 4. Definição de Competências

### 4.1 Competência Geral

**Competência geral do domínio de Computação:** desenvolver programas introdutórios que integrem fluxo sequencial, repetição, cálculo numérico e organização funcional da solução para produzir resultados verificáveis.

**BNCC:** não aplicada neste relatório.

### 4.2 Especificações de Competências

## CT11.1

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras

**Descrição Textual**  
Estruturar programas que utilizem repetição para percorrer domínios numéricos e atualizar valores intermediários de modo controlado, preservando cobertura adequada dos casos processados e término consistente da execução.

**Cobertura e rastreabilidade**
* LOs cobertos: LO2, LO5
* K mobilizados: K07, K01, K02

**Especificação de Conhecimentos**
* **K07:** sustenta a construção de laços com progressão e parada coerentes; é diretamente evidenciado pela varredura correta do intervalo e pelo número fixo de iterações do cálculo.
* **K01:** explicita a evolução do estado do programa durante a repetição; é evidenciado pelas atualizações sucessivas de contadores, acumuladores e resultados parciais.
* **K02:** garante coerência entre variáveis de controle, acumuladores e valores numéricos processados; é evidenciado pelo uso adequado de tipos e papéis de dados.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, com apoio de **Analisar** no rastreamento do estado computacional.

**Pareamento Conhecimento–Habilidade**

K07 / Aplicar → implementar laços que percorram um domínio numérico com passo, cobertura e término consistentes.  
Verbos de Bloom: implementar, iterar, executar

K01 / Analisar → rastrear a evolução do estado do programa durante atualizações sucessivas de contadores e acumuladores.  
Verbos de Bloom: rastrear, relacionar, estruturar

K02 / Aplicar → usar variáveis e tipos numéricos compatíveis com o controle iterativo e a acumulação de resultados.  
Verbos de Bloom: usar, manipular, implementar

**Especificação de Disposições**  
* Atenção ao critério de término dos laços.
* Cuidado com a atualização consistente do estado do programa.
* Disciplina na conferência da cobertura do domínio processado.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.1 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | Atenção ao término; cuidado com atualizações; disciplina na conferência | K07 | Implementar laços que percorram um domínio numérico com passo, cobertura e término consistentes |
| CT11.1 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | Atenção ao término; cuidado com atualizações; disciplina na conferência | K01 | Rastrear a evolução do estado do programa durante atualizações sucessivas de contadores e acumuladores |
| CT11.1 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | Atenção ao término; cuidado com atualizações; disciplina na conferência | K02 | Usar variáveis e tipos numéricos compatíveis com o controle iterativo e a acumulação de resultados |

**Definição de Ativação**
* Restrição de ativação: obrigatória
* Modo de ativação: construtiva e analítica
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: a tarefa exige varredura do intervalo solicitado e cálculo por quantidade fixa de parcelas. Por isso, repetição, acumulação e parada segura são elementos centrais e diretamente observáveis no código e na saída produzida.

## CT11.2

**Título da Competência**  
Implementar cálculo numérico iterativo por série finita com expressões aritméticas coerentes

**Descrição Textual**  
Construir rotinas de cálculo numérico iterativo em que expressões aritméticas, termos intermediários e resultados acumulados sejam organizados de forma coerente, permitindo a obtenção de resultados verificáveis em problemas de aproximação.

**Cobertura e rastreabilidade**
* LOs cobertos: LO3, LO5
* K mobilizados: K03, K01, K02

**Especificação de Conhecimentos**
* **K03:** sustenta a construção e avaliação de expressões aritméticas compostas; é diretamente evidenciado pela coerência operacional dos termos da série.
* **K01:** torna observável a evolução do cálculo ao longo das parcelas sucessivas; é evidenciado pelas atualizações do resultado parcial durante a execução.
* **K02:** assegura compatibilidade entre variáveis, constantes e resultados intermediários; é evidenciado pelo uso correto de dados numéricos no cálculo.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, com apoio de **Analisar** na interpretação do comportamento do cálculo.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → computar termos sucessivos de uma expressão numérica composta com coerência operacional.  
Verbos de Bloom: calcular, computar, implementar

K01 / Analisar → explicitar a evolução do resultado parcial ao longo do cálculo iterativo.  
Verbos de Bloom: analisar, relacionar, rastrear
(reutilizável; não específica do enunciado)
K02 / Aplicar → manter variáveis e constantes coerentes com o papel numérico de termos intermediários e acumuladores.  
Verbos de Bloom: usar, manipular, aplicar


**Especificação de Disposições**  
* Rigor na organização do cálculo.
* Atenção à coerência entre termos intermediários e resultado acumulado.
* Persistência na verificação da consistência numérica.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.2 | Implementar cálculo numérico iterativo por série finita com expressões aritméticas coerentes | Rigor; atenção à coerência; persistência na verificação | K03 | Computar termos sucessivos de uma expressão numérica composta com coerência operacional |
| CT11.2 | Implementar cálculo numérico iterativo por série finita com expressões aritméticas coerentes | Rigor; atenção à coerência; persistência na verificação | K01 | Explicitar a evolução do resultado parcial ao longo do cálculo iterativo |
| CT11.2 | Implementar cálculo numérico iterativo por série finita com expressões aritméticas coerentes | Rigor; atenção à coerência; persistência na verificação | K02 | Manter variáveis e constantes coerentes com o papel numérico de termos intermediários e acumuladores |

**Definição de Ativação**
* Restrição de ativação: obrigatória
* Modo de ativação: construtiva e analítica
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: a aproximação do cosseno pela série é o centro matemático-computacional da atividade. Assim, a qualidade do cálculo iterativo e das expressões aritméticas constitui evidência direta do desempenho do estudante.

## CT11.3

**Título da Competência**  
Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados

**Descrição Textual**  
Estruturar soluções em que partes específicas do processamento sejam organizadas em funções ou procedimentos com responsabilidade bem definida, assinaturas coerentes e tipos compatíveis com os dados manipulados e os resultados produzidos.

**Cobertura e rastreabilidade**
* LOs cobertos: LO1, LO4, LO5
* K mobilizados: K11, K05, K02

**Especificação de Conhecimentos**
* **K11:** sustenta a decomposição da solução em função ou procedimento com papel computacional específico; é diretamente evidenciado pela existência e uso coerente do subprograma exigido.
* **K05:** organiza o fluxo principal e a apresentação dos resultados; é diretamente evidenciado pela integração entre a chamada ao subprograma e a saída tabulada.
* **K02:** garante coerência entre parâmetros, retorno e valores manipulados; é evidenciado pela compatibilidade entre assinatura, processamento e resultado apresentado.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, com apoio de **Criar** na organização funcional da solução em unidade própria de processamento.

**Pareamento Conhecimento–Habilidade**

K11 / Aplicar → organizar parte do processamento em função ou procedimento com assinatura coerente com a especificação do problema.  
Verbos de Bloom: organizar, implementar, utilizar

K05 / Aplicar → estruturar o fluxo principal e a apresentação dos resultados em sequência verificável.  
Verbos de Bloom: organizar, implementar, executar

K02 / Aplicar → definir e usar tipos numéricos compatíveis entre parâmetros, retorno e resultados produzidos.  
Verbos de Bloom: usar, aplicar, manipular


**Especificação de Disposições**  
* Clareza na decomposição da solução.
* Cuidado com a coerência entre assinatura e processamento.
* Compromisso com a verificabilidade do comportamento final.

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT11.3 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | Clareza; cuidado com coerência; compromisso com verificabilidade | K11 | Organizar parte do processamento em função ou procedimento com assinatura coerente com a especificação do problema |
| CT11.3 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | Clareza; cuidado com coerência; compromisso com verificabilidade | K05 | Estruturar o fluxo principal e a apresentação dos resultados em sequência verificável |
| CT11.3 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | Clareza; cuidado com coerência; compromisso com verificabilidade | K02 | Definir e usar tipos numéricos compatíveis entre parâmetros, retorno e resultados produzidos |

**Definição de Ativação**
* Restrição de ativação: obrigatória
* Modo de ativação: construtiva
* Função de ativação: núcleo
* Justificativa curta baseada na tarefa: o enunciado exige explicitamente que o cálculo seja implementado em subprograma. Por isso, a modularização funcional com assinatura e tipos adequados constitui evidência direta e pertinente nesta atividade.
