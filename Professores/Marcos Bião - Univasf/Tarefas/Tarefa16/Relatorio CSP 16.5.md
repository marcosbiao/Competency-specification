# RELATÓRIO CSP — TASK16.5

## Introdução

Este relatório situa a tarefa 16.5 na fase de **Autoria de Competências** do CSP. A atividade integra uma maratona prática em C voltada a problemas introdutórios de processamento de dados, com submissão em juiz automático, ênfase em consistência entre entrada, processamento e saída, e evidências observáveis no código-fonte e no comportamento do programa.

A tarefa “verificar se uma matriz de ordem 3 é simétrica” elicita evidências diretas de representação matricial, percorrimento estruturado, formulação de condições lógicas e emissão de resultado verificável. Por isso, ela sustenta o modelo K–S–D sem redundância: o conhecimento disciplinar pode ser delimitado a um subconjunto do catálogo, os objetivos de aprendizagem são observáveis no artefato produzido, e as competências podem ser especificadas como capacidades reutilizáveis da disciplina. O catálogo de conhecimentos da disciplina estabelece precisamente esse limite superior de seleção.

## 1. Análise da Entidade Instrucional

### 1.1 Título

**Verificar se uma matriz de ordem 3 é simétrica**

### 1.2 Descrição

A tarefa requer a leitura de uma matriz 3×3 e a verificação de sua simetria por comparação entre elementos em posições refletidas em relação à diagonal principal. Em termos computacionais, o estudante deve representar a matriz em C, percorrê-la de modo sistemático, formular a condição lógica de simetria e emitir uma saída compatível com o enunciado e com a correção automática.

### 1.3 Processo de Desenvolvimento da Solução

1. Ler os 9 elementos da matriz 3×3 e armazená-los corretamente.
2. Definir uma estratégia de percorrimento das posições relevantes da matriz.
3. Comparar pares correspondentes `mat[i][j]` e `mat[j][i]`.
4. Atualizar o estado da verificação sempre que houver violação da simetria.
5. Encerrar o processamento emitindo a classificação final da matriz.

### 1.4 Resultados Esperados

1. Programa em C compilável e executável.
2. Leitura correta dos elementos da matriz.
3. Processamento consistente da propriedade de simetria.
4. Saída textual correta, distinguindo matriz simétrica de não simétrica.
5. Submissão válida em ambiente de juiz automático, quando aplicável ao contexto da atividade.

### 1.5 Contexto de Aquisição

A tarefa se insere em uma atividade prática de programação introdutória, realizada em equipes de até três estudantes, em laboratório, com apenas um computador por equipe, tempo total de duas horas, consulta apenas a material impresso e correção por testes desconhecidos em juiz automático. O conjunto da atividade trabalha vetores, matrizes e funções, e toma como evidência principal a correção funcional do programa submetido. 

### 1.6 Perfil do Público-Alvo

Estudantes de uma disciplina introdutória de programação que já tenham contato inicial com:

1. leitura e escrita básica em C;
2. estruturas sequenciais;
3. estruturas de repetição;
4. estruturas de seleção;
5. arranjos bidimensionais.

A necessidade principal do público, nesta tarefa, é consolidar a passagem da manipulação elementar de matrizes para a verificação de propriedades estruturais simples.

### 1.7 Nível de Proficiência (critérios e dimensões)

| Nível | Representação da matriz | Percorrimento e comparação | Formulação lógica da verificação | Saída e verificabilidade |
|---|---|---|---|---|
| **N1 - Inicial** | Declara a matriz com inconsistências de leitura ou indexação. | Percorre posições de forma incompleta ou redundante sem controle claro. | Não expressa adequadamente a condição de simetria. | A saída não corresponde ao processamento realizado. |
| **N2 - Intermediário** | Armazena a matriz corretamente, com pequenas fragilidades de organização. | Percorre a matriz e compara pares relevantes com alguma inconsistência pontual. | Expressa a condição, mas com fragilidade em casos de violação. | A saída corresponde parcialmente ao resultado computado. |
| **N3 - Proficiente** | Representa e preenche a matriz de modo correto e estável. | Percorre e compara posições simétricas com controle correto do fluxo. | Formula corretamente a regra lógica de decisão para a simetria. | A saída informa corretamente o resultado final da verificação. |
| **N4 - Avançado** | Representa a matriz com clareza e organiza o código para facilitar reúso e inspeção. | Além da corretude, reduz redundâncias e evidencia estratégia clara de verificação. | Formula a regra com clareza, robustez e boa legibilidade computacional. | A saída é correta, consistente e claramente alinhada ao estado final do programa. |

## 2. Seleção e Enumeração de Conhecimentos

A seleção abaixo utiliza exclusivamente o catálogo da disciplina como limite superior e privilegia os conhecimentos diretamente mobilizados pela tarefa.

### **K04 — Expressões lógicas e condições**

1. Permite formular relações de igualdade e desigualdade entre posições correlatas da matriz.
2. Sustenta a interpretação computacional de verdadeiro ou falso na verificação da propriedade.
3. É observável na construção da condição que decide se a matriz permanece ou não simétrica.

**Justificativa de mobilização:** a tarefa depende da expressão correta da condição `mat[i][j] == mat[j][i]` e da interpretação de sua violação como evidência de não simetria.

### **K05 — Estrutura sequencial e E/S básica**

1. Organiza o fluxo de leitura, processamento e exibição do resultado.
2. Garante a correspondência entre os dados lidos e o resultado apresentado.
3. É observável na sequência global do programa.

**Justificativa de mobilização:** sem um fluxo coerente de entrada, processamento e saída, a verificação não se torna testável no juiz automático.

### **K06 — Estruturas de seleção**

1. Permite decidir entre continuidade da verificação e marcação de falha na propriedade.
2. Sustenta a classificação final entre matriz simétrica e não simétrica.
3. É observável nos ramos condicionais do programa.

**Justificativa de mobilização:** a decisão computacional depende de estruturas condicionais para consolidar o resultado da verificação.

### **K07 — Estruturas de repetição**

1. Viabiliza o percorrimento sistemático das linhas e colunas da matriz.
2. Permite controlar a abrangência da inspeção das posições relevantes.
3. É observável no uso de laços para varredura bidimensional.

**Justificativa de mobilização:** a tarefa exige repetição controlada para comparar os elementos sem depender de enumeração manual.

### **K08 — Vetores e matrizes em C**

1. Representa a estrutura bidimensional central do problema.
2. Envolve acesso por índice, leitura e comparação de posições específicas.
3. É observável no armazenamento e na consulta de `mat[i][j]`.

**Justificativa de mobilização:** a propriedade a ser verificada é inerente à organização matricial dos dados.

## 3. Identificação de Objetivos de Aprendizagem

### **LO1**
Representar e preencher corretamente uma matriz bidimensional fixa em C, preservando a correspondência entre entrada e armazenamento.

**K associados:** K05, K08

### **LO2**
Percorrer sistematicamente uma matriz bidimensional para inspecionar elementos distribuídos por linhas e colunas.

**K associados:** K07, K08

### **LO3**
Aplicar condições lógicas e estruturas de decisão para verificar propriedades estruturais em matrizes.

**K associados:** K04, K06, K08

### **LO4**
Produzir saída verificável e coerente com o estado final do processamento.

**K associados:** K05, K06

## 4. Definição de Competências

### 4.1 Competência Geral

**Competência geral do domínio:** aplicar princípios de programação para modelar estruturas matriciais, analisar propriedades simples dos dados e implementar soluções corretas e verificáveis em linguagem C.

**Alinhamento geral com a BNCC:** há aderência defensável às habilidades **EF06CO02** (elaborar algoritmos com sequência, repetição e seleção em linguagem de programação), **EF06CO03** (descrever com precisão a solução e construir o programa correspondente), **EF06CO05** (definir o problema como relação entre entrada e saída), **EF07CO01** (usar registros e matrizes em programação) e, em uma progressão mais ampla, **EM13CO02** (refinar a solução desde a especificação até a implementação).

### 4.2 Especificações de Competências

Nesta tarefa, as competências propostas pelo usuário foram reavaliadas à luz das evidências realmente produzidas pelo artefato. Duas delas se mostram mais adequadas como competências nucleares: **Traduzir problemas simples em algoritmos claros por decomposição e abstração** e **Representar e processar coleções homogêneas com vetores e matrizes**. Já **Realizar entrada e saída de dados com validação mínima e formatação apropriada** é pertinente, mas não ocupa o núcleo da tarefa, porque o problema não exige validação substantiva de dados nem formatação elaborada; sua função aqui é instrumental.

## **CT16.5.1 — Traduzir problemas simples em algoritmos claros por decomposição e abstração**

**Descrição Textual**  
Traduzir problemas introdutórios em algoritmos claros, decompondo a solução em etapas coerentes e abstraindo relações essenciais entre os dados para decidir corretamente o resultado.

**Cobertura e rastreabilidade**
1. **LOs cobertos:** LO2, LO3  
2. **K mobilizados (Núcleo):** K04, K07, K08

**Especificação de Conhecimentos**
1. **K04:** expressões lógicas permitem explicitar a relação entre posições correlatas da matriz; a evidência aparece na condição que define a simetria.
2. **K07:** estruturas de repetição organizam a decomposição operacional da solução em um percurso sistemático da matriz.
3. **K08:** matrizes em C tornam observável a abstração do problema como comparação entre elementos `mat[i][j]` e `mat[j][i]`.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Analisar**

**Pareamento Conhecimento–Habilidade**

K04 / Analisar → formular a condição lógica que expressa a propriedade a ser verificada na matriz.  
Verbos de Bloom: analisar, relacionar, distinguir

K07 / Analisar → decompor o algoritmo em passos de leitura, percorrimento, comparação e decisão final.  
Verbos de Bloom: organizar, estruturar, examinar

K08 / Analisar → abstrair o problema em termos de posições relacionadas de uma estrutura bidimensional.  
Verbos de Bloom: correlacionar, examinar, modelar

**Especificação de Disposições**  
1. clareza algorítmica;  
2. precisão na decomposição;  
3. atenção às relações estruturais.

**Competências Alinhadas à BNCC**  
EF06CO02; EF06CO03; EM13CO02

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.5.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza algorítmica; precisão na decomposição; atenção às relações estruturais | K04 | formular a condição lógica que expressa a propriedade a ser verificada na matriz |
| CT16.5.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza algorítmica; precisão na decomposição; atenção às relações estruturais | K07 | decompor o algoritmo em passos de leitura, percorrimento, comparação e decisão final |
| CT16.5.1 | Traduzir problemas simples em algoritmos claros por decomposição e abstração | clareza algorítmica; precisão na decomposição; atenção às relações estruturais | K08 | abstrair o problema em termos de posições relacionadas de uma estrutura bidimensional |

**Definição de Ativação**
1. **Restrição de ativação:** obrigatória
2. **Modo de ativação:** analítica
3. **Função de ativação:** núcleo
4. **Justificativa curta:** a tarefa exige que o estudante reconheça a propriedade de simetria como uma relação entre posições da matriz e a traduza em um algoritmo claro, com passos logicamente organizados.

## **CT16.5.2 — Representar e processar coleções homogêneas com vetores e matrizes**

**Descrição Textual**  
Representar e processar coleções homogêneas em estruturas indexadas, utilizando vetores e matrizes de modo correto para armazenamento, acesso e inspeção de dados.

**Cobertura e rastreabilidade**
1. **LOs cobertos:** LO1, LO2  
2. **K mobilizados (Núcleo):** K07, K08

**Especificação de Conhecimentos**
1. **K07:** laços de repetição viabilizam o processamento ordenado de estruturas indexadas.
2. **K08:** vetores e matrizes em C fornecem a estrutura de representação exigida pelo problema.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Aplicar**

**Pareamento Conhecimento–Habilidade**

K07 / Aplicar → percorrer a matriz de forma sistemática para acessar as posições necessárias à verificação.  
Verbos de Bloom: executar, iterar, operar

K08 / Aplicar → representar uma matriz 3×3 e acessar corretamente seus elementos por índices válidos.  
Verbos de Bloom: implementar, manipular, usar

**Especificação de Disposições**  
1. atenção à indexação;  
2. organização do percorrimento;  
3. rigor operacional.

**Competências Alinhadas à BNCC**  
EF07CO01; EF06CO02

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.5.2 | Representar e processar coleções homogêneas com vetores e matrizes | atenção à indexação; organização do percorrimento; rigor operacional | K07 | percorrer a matriz de forma sistemática para acessar as posições necessárias à verificação |
| CT16.5.2 | Representar e processar coleções homogêneas com vetores e matrizes | atenção à indexação; organização do percorrimento; rigor operacional | K08 | representar uma matriz 3×3 e acessar corretamente seus elementos por índices válidos |

**Definição de Ativação**
1. **Restrição de ativação:** obrigatória
2. **Modo de ativação:** construtiva
3. **Função de ativação:** núcleo
4. **Justificativa curta:** a solução depende diretamente da representação da matriz e do processamento correto de seus elementos por índices e laços de repetição.

## **CT16.5.3 — Realizar entrada e saída de dados com validação mínima e formatação apropriada**

**Descrição Textual**  
Realizar entrada e saída de dados de modo consistente, preservando a correspondência entre o que é lido, o que é processado e o que é apresentado como resultado do programa.

**Cobertura e rastreabilidade**
1. **LOs cobertos:** LO1, LO4  
2. **K mobilizados (Núcleo):** K05, K06

**Especificação de Conhecimentos**
1. **K05:** a estrutura sequencial organiza a leitura dos dados e a emissão da resposta.
2. **K06:** a seleção define a saída apropriada de acordo com o estado final do processamento.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
**Aplicar**

**Pareamento Conhecimento–Habilidade**

K05 / Aplicar → ler os valores da matriz e organizar a saída de modo coerente com o enunciado.  
Verbos de Bloom: executar, implementar, usar

K06 / Aplicar → apresentar a classificação correta conforme o resultado da verificação realizada.  
Verbos de Bloom: aplicar, selecionar, resolver

**Especificação de Disposições**  
1. cuidado com a correspondência entre entrada e saída;  
2. compromisso com a corretude funcional;  
3. clareza na apresentação do resultado.

**Competências Alinhadas à BNCC**  
EF06CO05; EF06CO03

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.5.3 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | cuidado com a correspondência entre entrada e saída; compromisso com a corretude funcional; clareza na apresentação do resultado | K05 | ler os valores da matriz e organizar a saída de modo coerente com o enunciado |
| CT16.5.3 | Realizar entrada e saída de dados com validação mínima e formatação apropriada | cuidado com a correspondência entre entrada e saída; compromisso com a corretude funcional; clareza na apresentação do resultado | K06 | apresentar a classificação correta conforme o resultado da verificação realizada |

**Definição de Ativação**
1. **Restrição de ativação:** obrigatória
2. **Modo de ativação:** construtiva
3. **Função de ativação:** suporte
4. **Justificativa curta:** embora não seja o núcleo conceitual da tarefa, a competência é necessária para que a solução seja executável, testável e compatível com a avaliação automática.
