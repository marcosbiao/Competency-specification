# RELATÓRIO CSP: TASK12

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do Competency Specification Process (CSP) e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados pela TASK12. A tarefa solicita o desenvolvimento de um programa que exiba uma sequência finita de números pares, em ordem decrescente, sem entrada de dados pelo usuário.

A atividade elicita evidências observáveis porque o produto final permite verificar diretamente o uso de repetição, a atualização correta do valor controlado, a condição de parada e a saída exibida na tela. A justificativa breve também permite observar se o estudante compreende o critério usado para iniciar, atualizar e encerrar o processo iterativo.

A tarefa suporta o modelo **Conhecimento, Habilidade e Disposição (K-S-D)** porque mobiliza conhecimentos centrais de programação estruturada, exige habilidades técnicas avaliáveis no código e na saída produzida, e demanda disposições como precisão, consistência lógica e atenção aos limites da sequência.

## 1. Análise da Entidade Instrucional

### Título

**Exibição decrescente de números pares**

### Descrição

A entidade instrucional corresponde a uma atividade de programação introdutória em que o estudante deve implementar um programa capaz de gerar e exibir uma sequência numérica controlada. A sequência deve conter apenas números pares, seguir ordem decrescente e respeitar os limites definidos no enunciado. A evidência principal está no código, na saída apresentada e na justificativa do controle da repetição.

### Processo de Desenvolvimento da Solução

1. Identificar o padrão da sequência solicitada, considerando valor inicial, atualização e valor final.
2. Definir uma variável de controle compatível com a geração dos valores numéricos.
3. Selecionar uma estrutura de repetição adequada para produzir múltiplas saídas.
4. Formular a condição de continuidade ou de parada do laço.
5. Atualizar corretamente o valor controlado a cada iteração.
6. Exibir os valores produzidos em ordem decrescente, preservando a paridade e os limites do enunciado.
7. Conferir se a saída gerada é completa, finita e coerente com a sequência esperada.

### Resultados Esperados

* Código-fonte contendo uma estrutura de repetição responsável pela geração da sequência.
* Saída exibida na tela com números pares em ordem decrescente, respeitando os limites indicados.
* Ausência de valores ímpares, valores fora do intervalo, duplicações indevidas ou omissões.
* Término correto da execução, sem repetição infinita.
* Justificativa breve sobre início, atualização e condição de parada da repetição.

### Contexto de Aquisição

- **Curso:** graduação inicial em Computação
- **Organização:** atividade individual
- **Ambiente:** laboratório de programação ou avaliação prática introdutória
- **Avaliação:** análise do código, do comportamento final do programa e da justificativa breve apresentada

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em fase inicial de aprendizagem de programação estruturada. Espera-se que já tenham contato introdutório com algoritmos, variáveis, expressões simples, saída de dados e noção básica de repetição. A principal necessidade formativa é consolidar o uso de laços para gerar sequências finitas e verificáveis.

### Nível de Proficiência

| Nível | Organização do fluxo e da saída | Controle da repetição | Progressão numérica e paridade | Verificabilidade e justificativa |
|---|---|---|---|---|
| **N1 - Inicial** | Apresenta fluxo incompleto ou saída pouco verificável | Não utiliza repetição adequada ou produz laço incorreto | Inclui valores indevidos ou não preserva a ordem/paridade | Justificativa ausente ou incompatível com o código |
| **N2 - Intermediário** | Estrutura parte do fluxo, mas com fragilidades na apresentação da saída | Utiliza repetição, mas com erro em início, atualização ou parada | Preserva parte do padrão, mas com omissões ou limites imprecisos | Justificativa parcial, com pouca precisão técnica |
| **N3 - Proficiente** | Organiza o fluxo de execução e exibe a sequência de forma compreensível | Controla corretamente início, atualização e parada | Gera a sequência correta, com ordem decrescente e apenas pares | Justificativa coerente com o comportamento do programa |
| **N4 - Avançado** | Organiza o fluxo com clareza, estabilidade e saída tecnicamente verificável | Controla a repetição de modo preciso, simples e robusto | Gera a sequência correta com alta clareza algorítmica e sem redundâncias | Justificativa clara, objetiva e alinhada aos critérios de execução |

## 2. Seleção e Enumeração de Conhecimentos

### K02: Algoritmos e formas de representação

* Compreensão de algoritmo como sequência finita e ordenada de passos para resolver um problema.
* Tradução de um padrão numérico descrito em linguagem natural para uma solução computacional.
* Organização da solução de modo que o comportamento esperado seja reproduzível.

**Justificativa de mobilização na tarefa:** a atividade exige transformar a descrição da sequência em um procedimento finito, ordenado e executável.

### K03: Estrutura sequencial, entrada, processamento e saída

* Organização do programa em fluxo executável de comandos.
* Produção de saída observável na tela.
* Encadeamento coerente entre processamento iterativo e apresentação dos resultados.

**Justificativa de mobilização na tarefa:** embora não haja entrada de dados, a tarefa exige processamento e saída verificável, com exibição ordenada dos valores produzidos.

### K04: Variáveis, constantes, tipos de dados e atribuição

* Uso de variável ou valor controlado para representar o número corrente da sequência.
* Atribuição e atualização de valores ao longo da execução.
* Compatibilidade entre tipo de dado inteiro e sequência numérica solicitada.

**Justificativa de mobilização na tarefa:** a geração da sequência depende de um valor numérico controlado e atualizado a cada iteração.

### K05: Expressões aritméticas, relacionais e lógicas

* Uso de operação aritmética simples para alterar o valor da sequência.
* Uso de comparação relacional para controlar a continuidade ou parada.
* Formulação de expressões coerentes com ordem decrescente e paridade.

**Justificativa de mobilização na tarefa:** a progressão da sequência e o encerramento do laço dependem de expressões aritméticas e relacionais corretas.

### K07: Estruturas de repetição

* Uso de laço para executar repetidamente a exibição dos valores.
* Controle de inicialização, atualização e término da repetição.
* Garantia de execução finita e coerente com o intervalo solicitado.

**Justificativa de mobilização na tarefa:** a repetição é o mecanismo central para gerar todos os valores da sequência sem enumeração manual.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Identificar os elementos computacionais necessários para produzir uma sequência numérica finita e verificável.  
**K associados:** (K02, K03)

**LO2.** Utilizar variável de controle, valor inicial e atualização para conduzir uma repetição.  
**K associados:** (K04, K07)

**LO3.** Formular expressões aritméticas e relacionais simples para preservar a progressão e o término da sequência.  
**K associados:** (K05, K07)

**LO4.** Implementar estruturas de repetição que produzam saídas repetidas com término garantido.  
**K associados:** (K03, K04, K07)

**LO5.** Conferir a saída produzida quanto à ordem, paridade, completude e aderência aos limites definidos.  
**K associados:** (K03, K05, K07)

## 4. Definição de Competências

### 4.1 Competência Geral

**Implementar programas introdutórios com repetição finita, articulando algoritmo, variável de controle, expressões de atualização, condição de parada e saída verificável.**

### 4.2 Especificações de Competências

## Competência CT12.1

**Título da Competência**  
Realizar saída de dados com organização e formatação apropriada

**Descrição Textual**  
Capacidade de produzir saídas computacionais coerentes com o processamento realizado, apresentando resultados de forma organizada, completa e verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO5)
- K mobilizados (Núcleo): (K03, K05)

**Especificação de Conhecimentos**
- **K03:** estrutura sequencial, processamento e saída. **Justificativa de evidência:** a sequência exibida permite verificar se o fluxo de saída foi organizado de forma coerente com o processamento.
- **K05:** expressões aritméticas, relacionais e lógicas. **Justificativa de evidência:** a saída correta depende da preservação dos critérios de progressão, ordem e pertencimento numérico.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência exige empregar comandos de saída e expressões simples para apresentar resultados observáveis, organizados e verificáveis.

**Pareamento Conhecimento-Habilidade**

K03 / Aplicar → executar a apresentação de resultados no fluxo de saída de modo completo e verificável.  
Verbos de Bloom: executar, programar, usar

K05 / Aplicar → aplicar expressões numéricas para preservar critérios de progressão, ordem e pertencimento na saída.  
Verbos de Bloom: aplicar, calcular, resolver

**Especificação de Disposições**  
- atenção à clareza da saída;
- precisão na apresentação dos valores;
- cuidado com a verificabilidade do resultado.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.1 | Realizar saída de dados com organização e formatação apropriada | atenção à clareza da saída; precisão na apresentação dos valores; cuidado com a verificabilidade do resultado | K03 | executar a apresentação de resultados no fluxo de saída de modo completo e verificável |
| CT12.1 | Realizar saída de dados com organização e formatação apropriada | atenção à clareza da saída; precisão na apresentação dos valores; cuidado com a verificabilidade do resultado | K05 | aplicar expressões numéricas para preservar critérios de progressão, ordem e pertencimento na saída |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a tarefa exige que o programa apresente na tela uma sequência completa e verificável. A competência é ativada porque a evidência final do comportamento do programa está diretamente na saída produzida.

## Competência CT12.2

**Título da Competência**  
Controlar o fluxo com repetição utilizando variável de controle e paradas seguras

**Descrição Textual**  
Capacidade de utilizar estruturas de repetição para executar comandos de forma controlada, articulando inicialização, atualização do valor controlado e critério de término seguro.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO2, LO3, LO4)
- K mobilizados (Núcleo): (K04, K05, K07)

**Especificação de Conhecimentos**
- **K04:** variáveis, constantes, tipos de dados e atribuição. **Justificativa de evidência:** a geração da sequência depende de uma variável ou valor controlado que é atualizado a cada iteração.
- **K05:** expressões aritméticas, relacionais e lógicas. **Justificativa de evidência:** a progressão e o encerramento do laço dependem de expressões coerentes com os limites da sequência.
- **K07:** estruturas de repetição. **Justificativa de evidência:** o programa precisa repetir a exibição dos valores até alcançar o critério de parada definido.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência requer empregar laços, variável de controle e expressões de atualização em uma situação prática de programação introdutória.

**Pareamento Conhecimento-Habilidade**

K04 / Aplicar → manipular variável de controle compatível com o valor corrente da sequência.  
Verbos de Bloom: manipular, operar, usar

K05 / Aplicar → aplicar expressões aritméticas e relacionais para controlar progressão e parada do laço.  
Verbos de Bloom: aplicar, calcular, computar

K07 / Aplicar → implementar repetição finita com inicialização, atualização e término corretos.  
Verbos de Bloom: implementar, iterar, executar

**Especificação de Disposições**  
- consistência lógica;
- atenção aos limites da repetição;
- rigor no controle de término;
- precisão na atualização do valor.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.2 | Controlar o fluxo com repetição utilizando variável de controle e paradas seguras | consistência lógica; atenção aos limites da repetição; rigor no controle de término; precisão na atualização do valor | K04 | manipular variável de controle compatível com o valor corrente da sequência |
| CT12.2 | Controlar o fluxo com repetição utilizando variável de controle e paradas seguras | consistência lógica; atenção aos limites da repetição; rigor no controle de término; precisão na atualização do valor | K05 | aplicar expressões aritméticas e relacionais para controlar progressão e parada do laço |
| CT12.2 | Controlar o fluxo com repetição utilizando variável de controle e paradas seguras | consistência lógica; atenção aos limites da repetição; rigor no controle de término; precisão na atualização do valor | K07 | implementar repetição finita com inicialização, atualização e término corretos |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o núcleo da atividade é a geração de múltiplos valores por meio de repetição. A competência é ativada porque a correção depende diretamente da inicialização, atualização e condição de parada do laço.

## Competência CT12.3

**Título da Competência**  
Implementar algoritmos iterativos para geração de sequências numéricas simples

**Descrição Textual**  
Capacidade de construir programas introdutórios que representem padrões numéricos por meio de algoritmos iterativos, respeitando regras de progressão, restrições de pertencimento e apresentação ordenada dos resultados.

**Cobertura e rastreabilidade**
- LOs cobertos: (LO1, LO3, LO4, LO5)
- K mobilizados (Núcleo): (K02, K03, K05, K07)

**Especificação de Conhecimentos**
- **K02:** algoritmos e formas de representação. **Justificativa de evidência:** o código revela se o padrão da sequência foi convertido em procedimento finito e executável.
- **K03:** estrutura sequencial, processamento e saída. **Justificativa de evidência:** a tela exibida permite observar a coerência entre processamento iterativo e resultado produzido.
- **K05:** expressões aritméticas, relacionais e lógicas. **Justificativa de evidência:** a sequência correta depende de atualização numérica, preservação da paridade e limite de parada.
- **K07:** estruturas de repetição. **Justificativa de evidência:** a tarefa exige produção de vários valores por meio de um laço finito.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomina **Criar**, de forma controlada, porque a competência exige produzir um programa completo que integra algoritmo, repetição, expressões de controle e saída em um artefato funcional.

**Pareamento Conhecimento-Habilidade**

K02 / Criar → construir algoritmo iterativo finito para gerar sequência numérica definida por regra.  
Verbos de Bloom: construir, desenvolver, programar

K03 / Aplicar → executar fluxo de processamento e saída coerente com os valores gerados.  
Verbos de Bloom: executar, programar, usar

K05 / Aplicar → calcular atualizações e limites que preservem progressão decrescente e paridade.  
Verbos de Bloom: calcular, computar, resolver

K07 / Criar → desenvolver solução iterativa que gere todos os valores esperados com término garantido.  
Verbos de Bloom: desenvolver, produzir, programar

**Especificação de Disposições**  
- precisão algorítmica;
- atenção à completude da sequência;
- rigor no cumprimento das restrições do enunciado;
- cuidado com a verificabilidade da solução.


**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT12.3 | Implementar algoritmos iterativos para geração de sequências numéricas simples | precisão algorítmica; atenção à completude da sequência; rigor no cumprimento das restrições do enunciado; cuidado com a verificabilidade da solução | K02 | construir algoritmo iterativo finito para gerar sequência numérica definida por regra |
| CT12.3 | Implementar algoritmos iterativos para geração de sequências numéricas simples | precisão algorítmica; atenção à completude da sequência; rigor no cumprimento das restrições do enunciado; cuidado com a verificabilidade da solução | K03 | executar fluxo de processamento e saída coerente com os valores gerados |
| CT12.3 | Implementar algoritmos iterativos para geração de sequências numéricas simples | precisão algorítmica; atenção à completude da sequência; rigor no cumprimento das restrições do enunciado; cuidado com a verificabilidade da solução | K05 | calcular atualizações e limites que preservem progressão decrescente e paridade |
| CT12.3 | Implementar algoritmos iterativos para geração de sequências numéricas simples | precisão algorítmica; atenção à completude da sequência; rigor no cumprimento das restrições do enunciado; cuidado com a verificabilidade da solução | K07 | desenvolver solução iterativa que gere todos os valores esperados com término garantido |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a solução solicitada não se limita a reconhecer uma sequência, pois requer produzir um programa que gere todos os valores esperados. A competência é ativada pela integração entre algoritmo, laço, expressões de controle e saída final.