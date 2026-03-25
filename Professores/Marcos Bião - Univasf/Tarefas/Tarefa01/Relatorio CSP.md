# RELATÓRIO CSP — AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do CSP e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados por uma tarefa introdutória de programação em C. A atividade solicita a leitura de um valor numérico, a verificação de uma condição relacional, o cálculo de resultados derivados e a apresentação de saídas verificáveis. Por isso, ela elicita evidências observáveis no código, no comportamento final do programa e na coerência da justificativa breve.

A tarefa sustenta adequadamente o modelo **K–S–D** porque mobiliza conhecimentos centrais da programação imperativa, exige habilidades técnicas observáveis e permite associar disposições compatíveis com rigor computacional, precisão e consistência lógica. A modelagem a seguir prioriza rastreabilidade explícita, reuso e controle de granularidade, sem criar conhecimentos fora do catálogo da disciplina.

## 1. Análise da Entidade Instrucional

### Título

**Controle de excesso de pescado e cálculo de multa**

### Descrição

A tarefa requer a implementação, em linguagem C, de um programa capaz de ler o peso de peixes informado, verificar se esse valor ultrapassa um limite fixado no enunciado e registrar, conforme o caso, o excesso e o valor da multa. Quando não houver excesso, o programa deve manter as variáveis de saída com valor zero. A evidência principal está na coerência entre leitura, decisão, cálculo, atualização de variáveis e saída produzida.

### Processo de Desenvolvimento da Solução

1. Identificar os dados explicitamente envolvidos no problema: peso informado, excesso e multa.
2. Representar esses dados por variáveis numéricas compatíveis com seus papéis.
3. Organizar a solução segundo um fluxo básico de entrada, processamento e saída.
4. Formular a condição que distingue a situação com excesso da situação sem excesso.
5. Implementar a atualização das variáveis de saída em cada cenário.
6. Exibir os resultados finais de modo verificável e coerente com o enunciado.

### Resultados Esperados

- código-fonte em C com leitura, processamento condicional e saída;
- valores finais de `E` e `M` apresentados de forma explícita;
- tratamento coerente do caso com excesso e do caso sem excesso;
- justificativa breve explicando o comportamento adotado pela solução.

### Contexto de Aquisição 

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### Perfil do Público-Alvo 
O público-alvo é composto por estudantes ingressantes em disciplinas introdutórias de programação, com contato inicial com variáveis, tipos primitivos, expressões, entrada e saída e estruturas de decisão. Trata-se de um perfil que necessita consolidar a tradução de enunciados textuais em soluções computacionais simples, corretas e verificáveis.


### Nível de Proficiência (critérios e dimensões)

| Nível | Representação de dados | Lógica condicional | Processamento e atualização de estado | Saída e justificativa |
|---|---|---|---|---|
| **N1 — Inicial** | identifica parcialmente as variáveis, com incoerências de uso | condição ausente ou incorreta | atualização inconsistente de `E` e `M` | saída incompleta ou sem justificativa coerente |
| **N2 — Básico** | representa os dados principais, com pequenas fragilidades | distingue os casos, mas com imprecisões de implementação | calcula ou atualiza apenas parte do comportamento esperado | saída compreensível, porém pouco verificável |
| **N3 — Proficiente** | utiliza variáveis e tipos de modo coerente | implementa corretamente a verificação dos casos | atualiza `E` e `M` com consistência nos dois cenários | saída verificável e justificativa breve adequada |
| **N4 — Avançado** | organiza os dados com clareza e precisão técnica | expressa a decisão de forma estável e sem ambiguidades | integra cálculo, decisão e estado com alta consistência | saída clara, verificável e justificativa tecnicamente sólida |


## 2. Seleção e Enumeração de Conhecimentos

**K01 — Modelo de execução e noção de estado (paradigma imperativo)**
- compreensão operacional de que o programa evolui por mudanças de estado durante a execução;
- relação entre atribuição, sequência de comandos e estado final observável;
- leitura do comportamento do programa a partir das atualizações realizadas.
- **Justificativa de mobilização na tarefa:** a tarefa evidencia diretamente a mudança de estado das variáveis `E` e `M` conforme o ramo executado.

**K02 — Variáveis, constantes e tipos primitivos**
- representação de dados simples por identificadores e tipos primitivos;
- uso de variáveis para entrada, processamento e saída;
- coerência de tipos em operações numéricas básicas.
- **Justificativa de mobilização na tarefa:** o programa depende da representação consistente do peso, do excesso e da multa em variáveis numéricas.

**K03 — Expressões aritméticas e avaliação**
- construção de expressões aritméticas para gerar valores derivados;
- avaliação coerente de operadores e resultados numéricos;
- atualização de variáveis por atribuição.
- **Justificativa de mobilização na tarefa:** o cálculo do excesso e da multa depende de processamento aritmético simples, diretamente observável no código.

**K04 — Expressões lógicas e condições**
- formulação de condições booleanas a partir de comparações numéricas;
- interpretação de verdade e falsidade em regras de decisão;
- correspondência entre regra do problema e condição implementada.
- **Justificativa de mobilização na tarefa:** a verificação da ultrapassagem do limite é o critério lógico central do problema.

**K05 — Estrutura sequencial e E/S básica**
- organização do programa como sequência de leitura, processamento e saída;
- encadeamento verificável de comandos em solução introdutória;
- apresentação de resultados observáveis ao final da execução.
- **Justificativa de mobilização na tarefa:** a atividade exige um fluxo básico de entrada do peso, processamento da regra e exibição das variáveis finais.

**K06 — Estruturas de seleção**
- escolha de caminhos alternativos de execução com base em uma condição;
- tratamento explícito de dois cenários mutuamente exclusivos;
- cobertura coerente dos casos previstos no enunciado.
- **Justificativa de mobilização na tarefa:** a solução precisa distinguir computacionalmente o caso com excesso do caso sem excesso.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Representar dados numéricos de entrada, processamento e saída em programas introdutórios de forma coerente com o problema.  
**K associados:** (K02, K05)

**LO2.** Organizar soluções simples segundo um fluxo verificável de entrada, processamento e saída.  
**K associados:** (K05, K01)

**LO3.** Formular e aplicar condições relacionais para distinguir cenários alternativos de execução.  
**K associados:** (K04, K06)

**LO4.** Construir processamento aritmético simples para gerar resultados derivados e atualizar o estado do programa.  
**K associados:** (K03, K01, K02)

**LO5.** Produzir saídas verificáveis e tecnicamente coerentes com o comportamento implementado.  
**K associados:** (K05, K01, K06)

## 4. Definição de Competências

### 4.1 Competência Geral

**Implementar soluções computacionais introdutórias em programação imperativa, articulando representação de dados, fluxo sequencial, decisão condicional e atualização de resultados de forma verificável.**

**BNCC:** não aplicável diretamente ao contexto desta task.

### 4.2 Especificações de Competências

---

## Competência CT01.1

**Título da Competência**  
Estruturar programas introdutórios com variáveis numéricas e fluxo básico de entrada e saída

**Descrição Textual**  
Capacidade de organizar um programa simples em linguagem C para receber dados numéricos, armazená-los em variáveis coerentes e apresentar resultados verificáveis ao final de uma sequência básica de execução.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO2, LO5)
- K mobilizados (Núcleo): (K01, K02, K05)

**Especificação de Conhecimentos**
- **K01:** compreensão do estado do programa como resultado das atribuições executadas. **Justificativa de evidência:** o estado final das variáveis pode ser observado diretamente na saída produzida.
- **K02:** uso de variáveis e tipos primitivos para representar dados numéricos. **Justificativa de evidência:** a tarefa exige representar corretamente peso, excesso e multa.
- **K05:** organização sequencial de leitura, processamento e saída. **Justificativa de evidência:** o artefato permite verificar se o fluxo básico foi montado de forma funcional.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomina **Aplicar**, pois a competência requer uso operacional de variáveis, tipos e fluxo sequencial em um programa executável.

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → explicitar o estado final do programa por meio de atribuições coerentes entre leitura, processamento e saída.  
Verbos de Bloom: aplicar, executar, usar

K02 / Aplicar → declarar e utilizar variáveis numéricas compatíveis com o papel computacional de cada dado.  
Verbos de Bloom: implementar, manipular, operar

K05 / Aplicar → estruturar o fluxo de entrada, processamento e saída de modo verificável no programa final.  
Verbos de Bloom: executar, programar, resolver

**Especificação de Disposições**  
- precisão na representação dos dados;
- atenção à ordem dos comandos;
- rigor na apresentação dos resultados.

**Competências Alinhadas à BNCC (quando aplicável)**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT01.1 | Estruturar programas introdutórios com variáveis numéricas e fluxo básico de entrada e saída | precisão na representação dos dados; atenção à ordem dos comandos; rigor na apresentação dos resultados | K01 | explicitar o estado final do programa por meio de atribuições coerentes entre leitura, processamento e saída |
| CT01.1 | Estruturar programas introdutórios com variáveis numéricas e fluxo básico de entrada e saída | precisão na representação dos dados; atenção à ordem dos comandos; rigor na apresentação dos resultados | K02 | declarar e utilizar variáveis numéricas compatíveis com o papel computacional de cada dado |
| CT01.1 | Estruturar programas introdutórios com variáveis numéricas e fluxo básico de entrada e saída | precisão na representação dos dados; atenção à ordem dos comandos; rigor na apresentação dos resultados | K05 | estruturar o fluxo de entrada, processamento e saída de modo verificável no programa final |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a task exige a construção efetiva de um programa funcional com leitura, processamento e saída. As evidências centrais estão diretamente no artefato produzido e no comportamento final observado.

---

## Competência CT01.2

**Título da Competência**  
Controlar o fluxo de execução por meio de decisão condicional simples

**Descrição Textual**  
Capacidade de traduzir uma regra expressa em linguagem natural para uma condição lógica e utilizá-la para selecionar, de forma correta, entre dois comportamentos alternativos de execução.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO3, LO5)
- K mobilizados (Núcleo): (K01, K04, K06)

**Especificação de Conhecimentos**
- **K01:** compreensão da relação entre ramo executado e estado final do programa. **Justificativa de evidência:** os valores finais de `E` e `M` dependem diretamente do caminho de execução escolhido.
- **K04:** formulação de condições lógicas a partir de comparações numéricas. **Justificativa de evidência:** a verificação do limite regulamentar é observável diretamente na condição implementada.
- **K06:** uso de seleção para tratar casos alternativos de execução. **Justificativa de evidência:** a tarefa requer distinguir explicitamente o cenário com excesso do cenário sem excesso.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomina **Analisar**, pois a competência exige discriminar cenários, relacionar regra do problema e condição computacional e estruturar caminhos alternativos coerentes.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → relacionar o caminho de execução escolhido ao estado final assumido pelas variáveis de saída.  
Verbos de Bloom: distinguir, relacionar, rastrear

K04 / Analisar → formular condição lógica coerente com a regra numérica que separa os cenários do problema.  
Verbos de Bloom: analisar, examinar, estruturar

K06 / Analisar → organizar a seleção entre dois comportamentos alternativos sem lacunas de cobertura.  
Verbos de Bloom: discriminar, distinguir, articular


**Especificação de Disposições**  
- consistência lógica;
- atenção às regras do problema;
- rigor na cobertura dos casos.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT01.2 | Controlar o fluxo de execução por meio de decisão condicional simples | consistência lógica; atenção às regras do problema; rigor na cobertura dos casos | K01 | relacionar o caminho de execução escolhido ao estado final assumido pelas variáveis de saída |
| CT01.2 | Controlar o fluxo de execução por meio de decisão condicional simples | consistência lógica; atenção às regras do problema; rigor na cobertura dos casos | K04 | formular condição lógica coerente com a regra numérica que separa os cenários do problema |
| CT01.2 | Controlar o fluxo de execução por meio de decisão condicional simples | consistência lógica; atenção às regras do problema; rigor na cobertura dos casos | K06 | organizar a seleção entre dois comportamentos alternativos sem lacunas de cobertura |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: analítica
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a distinção entre ocorrência e não ocorrência de excesso constitui o núcleo lógico do problema. A competência é ativada porque o estudante precisa analisar a regra do enunciado e convertê-la em decisão computacional verificável.

---

## Competência CT01.3

**Título da Competência**  
Implementar processamento numérico simples para gerar e registrar resultados derivados

**Descrição Textual**  
Capacidade de integrar cálculo aritmético, atualização de variáveis e controle condicional para produzir resultados derivados corretos em programas introdutórios.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO4, LO5)
- K mobilizados (Núcleo): (K01, K02, K03, K06)

**Especificação de Conhecimentos**
- **K01:** compreensão do programa como sequência de atualizações de estado. **Justificativa de evidência:** a consistência do estado final é diretamente verificável nas variáveis resultantes.
- **K02:** uso de variáveis e tipos numéricos adequados ao cálculo. **Justificativa de evidência:** o processamento depende de variáveis compatíveis com peso, excesso e multa.
- **K03:** construção e avaliação de expressões aritméticas. **Justificativa de evidência:** a obtenção dos resultados derivados depende diretamente do cálculo implementado.
- **K06:** articulação do cálculo com o ramo correto da seleção. **Justificativa de evidência:** o processamento só é válido se ocorrer no cenário apropriado e se o caso alternativo for tratado corretamente.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomina **Criar**, de forma defensável, porque a tarefa exige a implementação de uma solução completa em C que combine cálculo, decisão e atualização de resultados em um único artefato funcional.

**Pareamento Conhecimento–Habilidade**

K01 / Aplicar → atualizar o estado do programa de modo coerente com o resultado produzido em cada cenário de execução.  
Verbos de Bloom: aplicar, manipular, operar

K02 / Aplicar → utilizar variáveis numéricas compatíveis com a produção e o armazenamento dos resultados calculados.  
Verbos de Bloom: implementar, programar, usar

K03 / Aplicar → calcular valores derivados a partir do dado de entrada por meio de expressões aritméticas corretas.  
Verbos de Bloom: calcular, computar, resolver

K06 / Criar → construir o processamento condicional de forma integrada ao cálculo e ao registro dos resultados finais.  
Verbos de Bloom: construir, desenvolver, programar


**Especificação de Disposições**  
- rigor computacional;
- precisão algorítmica;
- consistência na atualização dos resultados.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT01.3 | Implementar processamento numérico simples para gerar e registrar resultados derivados | rigor computacional; precisão algorítmica; consistência na atualização dos resultados | K01 | atualizar o estado do programa de modo coerente com o resultado produzido em cada cenário de execução |
| CT01.3 | Implementar processamento numérico simples para gerar e registrar resultados derivados | rigor computacional; precisão algorítmica; consistência na atualização dos resultados | K02 | utilizar variáveis numéricas compatíveis com a produção e o armazenamento dos resultados calculados |
| CT01.3 | Implementar processamento numérico simples para gerar e registrar resultados derivados | rigor computacional; precisão algorítmica; consistência na atualização dos resultados | K03 | calcular valores derivados a partir do dado de entrada por meio de expressões aritméticas corretas |
| CT01.3 | Implementar processamento numérico simples para gerar e registrar resultados derivados | rigor computacional; precisão algorítmica; consistência na atualização dos resultados | K06 | construir o processamento condicional de forma integrada ao cálculo e ao registro dos resultados finais |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a solução solicitada não se limita a reconhecer casos; ela exige programar o cálculo e registrar computacionalmente os resultados. A evidência é direta no código e nos valores produzidos ao final da execução.
