# Catálogo de Conhecimentos da Disciplina — Programação de Computadores I (UFRB)

**Objetivo:** estabelecer um conjunto fixo e reutilizável de conhecimentos (K) para a disciplina **Programação de Computadores I**, a ser usado como **limite superior** na geração de relatórios CSP das tarefas da disciplina.  
**Regra de uso no CSP:** em cada tarefa, o relatório CSP **seleciona um subconjunto** deste catálogo. Extensões só devem ser aceitas se a ementa ou o catálogo forem formalmente revisados.

## Fontes e âncoras

**Ementa da disciplina:** Conceitos básicos de computação. Algoritmos em Linguagens de Programação Estruturadas.

**Escopo operacional considerado para explicitação do catálogo:** considerando a ementa da disciplina muito aberta, esse catalogo foi desenvolvido a partir das atividades aplicadas na disciplina. Compreende-se que o componente abrangeu conteúdos introdutórios de programação, incluindo noção de algoritmo, variáveis, fluxograma, estruturas condicionais, estruturas de repetição, vetores e matrizes.

**Âncora externa de referência:** CS2023 (ACM/IEEE), especialmente a unidade **SDF-Fundamentals** e, quando pertinente, conteúdos relacionados a estruturas de dados elementares.

### Convenção de códigos CS2023
**SDF-n** = *SDF-Fundamentals*, tópico **n**

## Tabela-resumo do catálogo (K)

| Código | Conhecimento | Rastreio na ementa/escopo | Código CS2023 |
|---|---|---|---|
| K01 | Conceitos básicos de computação e resolução de problemas | Conceitos básicos de computação | Sem âncora específica explícita |
| K02 | Algoritmos e formas de representação | Algoritmos em Linguagens de Programação Estruturadas; noção de algoritmo; fluxograma | Sem âncora específica explícita |
| K03 | Estrutura sequencial, entrada, processamento e saída | Algoritmos em Linguagens de Programação Estruturadas; parte introdutória | SDF-3 |
| K04 | Variáveis, constantes, tipos de dados e atribuição | Parte introdutória; variáveis | SDF-1 |
| K05 | Expressões aritméticas, relacionais e lógicas | Parte introdutória; base para condicionais e laços | SDF-1 / SDF-3 |
| K06 | Estruturas condicionais | Estrutura condicional | SDF-3 |
| K07 | Estruturas de repetição | Laços | SDF-3 |
| K08 | Vetores e matrizes | Vetores e matrizes | SDF-6 |

## Definições detalhadas

### K01 — Conceitos básicos de computação e resolução de problemas
**Descrição:** compreensão introdutória do que é computação no contexto da disciplina, incluindo a noção de problema, dado, processamento, saída e programa como solução executável para um problema.

**Escopo mínimo:** noção de computador como sistema de processamento de dados; diferença entre problema e solução; ideia de programa como sequência organizada de instruções; compreensão introdutória do raciocínio necessário para formular soluções.

**Rastreio na ementa/escopo:** Conceitos básicos de computação.

**Código CS2023 curto:** sem âncora específica explícita.

**Evidências típicas (em tarefas):** explicar o que um algoritmo resolve; identificar entradas, processamento e saídas; distinguir descrição informal do problema e solução computacional.

**Observações de reuso:** base conceitual transversal para todas as tarefas da disciplina.

### K02 — Algoritmos e formas de representação
**Descrição:** compreensão de algoritmo como sequência finita, ordenada e não ambígua de passos para resolver um problema, incluindo sua representação por descrição textual estruturada, pseudocódigo e fluxograma.

**Escopo mínimo:** definição de algoritmo; propriedades de finitude, ordem e precisão; leitura e construção de fluxogramas simples; tradução entre diferentes formas introdutórias de representação algorítmica.

**Rastreio na ementa/escopo:** Algoritmos em Linguagens de Programação Estruturadas; noção de algoritmo; fluxograma.

**Código CS2023 curto:** sem âncora específica explícita.

**Evidências típicas:** elaborar algoritmos em linguagem descritiva ou pseudocódigo; interpretar fluxogramas; converter fluxograma em descrição sequencial ou vice-versa.

**Observações de reuso:** conhecimento nuclear da disciplina, anterior à codificação e fortemente mobilizado em tarefas introdutórias.

### K03 — Estrutura sequencial, entrada, processamento e saída
**Descrição:** organização de algoritmos e programas como sequência de instruções executadas em ordem, com leitura de dados, processamento e produção de resultados.

**Escopo mínimo:** fluxo sequencial de execução; comandos de entrada e saída em nível introdutório; encadeamento lógico entre leitura, processamento e exibição de resultados.

**Rastreio na ementa/escopo:** Algoritmos em Linguagens de Programação Estruturadas; parte introdutória.

**Código CS2023 curto:** SDF-3.

**Evidências típicas:** programas simples com entrada, processamento e saída; ordenação correta de instruções; produção de resultados coerentes com os dados fornecidos.

**Observações de reuso:** fundamento operacional para qualquer tarefa executável na disciplina.

### K04 — Variáveis, constantes, tipos de dados e atribuição
**Descrição:** representação e manipulação de dados por meio de identificadores, valores e tipos, em uma perspectiva introdutória de programação estruturada.

**Escopo mínimo:** noção de variável e constante; atribuição; atualização de valores; tipos de dados básicos; compatibilidade elementar entre tipo e uso do dado.

**Rastreio na ementa/escopo:** parte introdutória; variáveis.

**Código CS2023 curto:** SDF-1.

**Evidências típicas:** declarar ou utilizar variáveis adequadas ao problema; armazenar resultados intermediários; atualizar corretamente o valor de uma variável ao longo da execução.

**Observações de reuso:** conhecimento transversal, mobilizado em praticamente todas as tarefas de programação introdutória.

### K05 — Expressões aritméticas, relacionais e lógicas
**Descrição:** construção e avaliação de expressões utilizadas para cálculo, comparação e formulação de condições em algoritmos e programas.

**Escopo mínimo:** operadores aritméticos; operadores relacionais; operadores lógicos; precedência básica; composição de expressões para apoiar decisões e repetições.

**Rastreio na ementa/escopo:** parte introdutória; base para condicionais e laços.

**Código CS2023 curto:** SDF-1 / SDF-3.

**Evidências típicas:** cálculos corretos; formulação adequada de condições; uso coerente de comparações e conectivos lógicos em decisões e laços.

**Observações de reuso:** serve de base para tarefas numéricas, estruturas condicionais e estruturas de repetição.

### K06 — Estruturas condicionais
**Descrição:** seleção de caminhos alternativos de execução a partir da avaliação de condições.

**Escopo mínimo:** decisões simples e compostas; estruturas do tipo `se`, `se-senão` e encadeamentos introdutórios; cobertura de casos mutuamente excludentes ou complementares.

**Rastreio na ementa/escopo:** estrutura condicional.

**Código CS2023 curto:** SDF-3.

**Evidências típicas:** classificar valores, validar situações, escolher ações conforme regras do problema, implementar corretamente diferentes casos de saída.

**Observações de reuso:** central em problemas de decisão, classificação, validação e aplicação de regras.

### K07 — Estruturas de repetição
**Descrição:** execução iterativa de blocos de instruções controlada por contador, condição ou critério de parada.

**Escopo mínimo:** noção de laço; repetição por contagem e por condição; inicialização, atualização e parada; compreensão de iteração passo a passo.

**Rastreio na ementa/escopo:** laços.

**Código CS2023 curto:** SDF-3.

**Evidências típicas:** repetição controlada de leituras, contagens, acumulações e percorrimentos; laços com término garantido; processamento iterativo coerente.

**Observações de reuso:** indispensável para tarefas com múltiplos dados, contagem de ocorrências, somatórios e percorrimento de coleções.

### K08 — Vetores
**Descrição:** representação e manipulação de coleções homogêneas unidimensionais e bidimensionais em programação estruturada.

**Escopo mínimo:** noção de vetor como conjunto indexado de elementos do mesmo tipo; acesso por posição; preenchimento, leitura e processamento sequencial dos elementos.

**Rastreio na ementa/escopo:** vetores e matrizes.

**Código CS2023 curto:** SDF-6.

**Evidências típicas:** armazenar vários valores em uma mesma estrutura; percorrer posições com laços; consultar, atualizar e processar elementos do vetor.

**Observações de reuso:** conhecimento central para tarefas com listas de valores, notas, contagens, buscas simples e agregações.


## Itens explicitamente fora do escopo
Os tópicos abaixo **não devem ser considerados parte do catálogo-base**, salvo se houver evidência clara de que foram efetivamente trabalhados e a disciplina decidir incorporá-los formalmente:

1. Funções e procedimentos
2. Recursão
3. Strings como conteúdo específico
4. Arquivos
5. Ponteiros
6. Registros, structs, enumerações e uniões
7. Ordenação e busca como tópico formal autônomo
8. Teste, depuração e documentação como conhecimentos independentes do catálogo

Caso apareçam incidentalmente em alguma tarefa, recomenda-se tratá-los como **EXT (extensão)**, e não como parte do núcleo fixo do catálogo.

## Política de manutenção
Alterações neste catálogo devem ocorrer apenas quando houver revisão da ementa da disciplina ou decisão pedagógica explícita de ampliação do escopo.

Cada tarefa da disciplina deve declarar explicitamente quais conhecimentos **K** foram mobilizados, sempre como subconjunto deste catálogo, para garantir rastreabilidade, consistência e reuso nos relatórios CSP.