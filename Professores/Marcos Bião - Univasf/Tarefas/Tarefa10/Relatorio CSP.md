# RELATÓRIO CSP
## Fase de Autoria de Competências


## Introdução

Este relatório situa a TASK10 na fase de Autoria de Competências do CSP, com foco na explicitação rastreável dos conhecimentos mobilizados, dos objetivos de aprendizagem envolvidos e das competências observáveis associadas à tarefa. A atividade solicita que o estudante analise um trecho curto de programa com repetição aninhada, acompanhe a atualização de uma variável e selecione a saída correta entre alternativas, apresentando justificativa breve.

A tarefa produz evidências observáveis porque exige interpretação do fluxo de execução, rastreamento de estado, relação entre número de iterações e efeito acumulado, além de defesa técnica da alternativa escolhida. Trata-se, portanto, de uma situação adequada para o modelo Conhecimento–Habilidade–Disposição, pois articula conhecimentos conceituais da programação imperativa, habilidades analíticas de leitura de código e disposições de rigor, atenção e justificativa baseada em evidências, sem redundância nem fragmentação excessiva.


# 1. Análise da Entidade Instrucional

## Título

Previsão de saída em laços aninhados com incremento acumulado

## Descrição

A tarefa consiste em analisar um trecho de programa em linguagem C que contém variável acumuladora, laços de repetição aninhados e comando de saída. O estudante deve interpretar o comportamento do programa durante a execução, identificar o valor efetivamente produzido ao final e selecionar a alternativa correta, acompanhada de justificativa breve. A exigência central não é implementar uma solução nova, mas rastrear e explicar o comportamento de uma solução já escrita.

## Processo de Desenvolvimento da Solução

1. Ler o trecho de programa e identificar os elementos centrais da execução.
2. Reconhecer o papel da variável cujo valor final será exibido.
3. Examinar a organização dos laços de repetição e a relação entre laço externo e laço interno.
4. Relacionar a atualização repetida da variável ao total de execuções do bloco iterativo.
5. Confrontar o valor inferido com as alternativas apresentadas.
6. Registrar a alternativa escolhida com justificativa breve e tecnicamente consistente.

## Resultados Esperados

1. Seleção de uma única alternativa.
2. Justificativa curta baseada no fluxo de execução observado.
3. Evidência de compreensão do efeito dos laços aninhados sobre a variável acumuladora.
4. Coerência entre a interpretação do programa e a resposta assinalada.

### Contexto de Aquisição

1. **Curso:** Ciência da Computação.
2. **Componente curricular:** Introdução à Programação.
3. **Organização:** atividade individual.
4. **Ambiente:** sala de aula, lista de exercícios ou avaliação escrita/prática guiada.
5. **Forma de avaliação:** análise de resposta final com justificativa curta e verificável.

### Perfil do Público-Alvo

1. Estudantes de início de curso, em etapa introdutória de aprendizagem de programação imperativa.
2. Público com contato inicial com variáveis, fluxo sequencial e estruturas de repetição.
3. Necessita consolidar a leitura operacional de trechos de código antes de avançar para implementação de soluções mais extensas.
4. Requer apoio na articulação entre rastreio de execução e explicação técnica do resultado.

## Nível de Proficiência (critérios e dimensões)

| Nível | Leitura do fluxo do programa | Rastreamento do estado das variáveis | Interpretação de laços aninhados | Justificativa da resposta |
|---|---|---|---|---|
| **N1 - Inicial** | Reconhece partes isoladas do código, mas compreende apenas parcialmente o encadeamento da execução. | Acompanha parcialmente as atualizações, com omissões ou confusões no estado das variáveis. | Reconhece a existência de repetição, mas não articula adequadamente os dois níveis do laço. | Responde com justificativa ausente, vaga ou pouco verificável. |
| **N2 - Intermediário** | Identifica a sequência geral de execução, ainda com pequenas lacunas interpretativas. | Acompanha as principais atualizações, mas apresenta justificativa incompleta. | Compreende a repetição aninhada em termos gerais, com pequenas imprecisões. | Apresenta justificativa breve, mas ainda limitada em clareza ou verificabilidade. |
| **N3 - Proficiente** | Interpreta corretamente o fluxo completo, incluindo a relação entre os blocos do programa. | Rastreia corretamente as mudanças de estado durante toda a execução. | Relaciona corretamente laço externo, laço interno e total de execuções. | Justifica a resposta com base no fluxo de execução e na atualização da variável. |
| **N4 - Avançado** | Interpreta o fluxo com precisão e explicita relações estruturais de forma autônoma e consistente. | Rastreia o estado com precisão, sintetiza o comportamento e explica regularidades do processo. | Explica com clareza o efeito combinado dos laços e sua implicação quantitativa. | Justifica de modo técnico, claro e rigoroso, com elevada verificabilidade. |



# 2. Seleção e Enumeração de Conhecimentos

Foram selecionados 6 conhecimentos do catálogo da disciplina, número suficiente para cobrir a tarefa com rastreabilidade e sem explosão de granularidade.

## K01 — Modelo de execução e noção de estado (paradigma imperativo)

1. Compreensão operacional de que a execução do programa produz mudanças sucessivas de estado.
2. Interpretação de atribuições e atualizações como transições observáveis durante a execução.
3. Leitura do comportamento do programa ao longo do tempo.

Justificativa de mobilização na tarefa: a questão exige acompanhar como o estado da variável muda ao longo das iterações até a produção da saída final.

## K02 — Variáveis, constantes e tipos primitivos

1. Reconhecimento do papel de variáveis em armazenamento e atualização de valores.
2. Compreensão do uso de variáveis inteiras em contagem e acumulação.
3. Coerência entre identificadores, valores e função desempenhada no programa.

Justificativa de mobilização na tarefa: o estudante precisa reconhecer a variável exibida, seu valor inicial e o efeito das atualizações sucessivas.

## K03 — Expressões aritméticas e avaliação

1. Interpretação de atualizações numéricas simples associadas à execução de comandos.
2. Compreensão do efeito acumulativo de operações aritméticas repetidas.
3. Relação entre atualização por comando e valor final obtido.

Justificativa de mobilização na tarefa: a resposta depende de relacionar incremento repetido com acumulação numérica ao longo das iterações.

## K04 — Expressões lógicas e condições

1. Interpretação de condições que controlam continuidade e parada de laços.
2. Compreensão da relação entre comparação e permanência na repetição.
3. Leitura de condições como mecanismos de controle do fluxo.

Justificativa de mobilização na tarefa: embora não seja o foco principal, a repetição depende da interpretação correta das condições de controle dos laços.

## K05 — Estrutura sequencial e E/S básica

1. Compreensão de que o programa organiza processamento e saída observável.
2. Interpretação do comando de saída como evidência final do estado computado.
3. Relação entre processamento executado e valor apresentado ao usuário.

Justificativa de mobilização na tarefa: a atividade pede a previsão da saída exibida, o que requer compreender o papel do comando de impressão no fluxo do programa.

## K07 — Estruturas de repetição

1. Compreensão de laços controlados por contagem.
2. Interpretação de repetição aninhada e do efeito de múltiplas iterações.
3. Relação entre quantidade de repetições e processamento acumulado.

Justificativa de mobilização na tarefa: este é o eixo central do problema, pois a saída depende diretamente do comportamento de dois laços aninhados.


# 3. Identificação de Objetivos de Aprendizagem

## LO1
Interpretar mudanças de estado de variáveis durante a execução de trechos de programas imperativos introdutórios.  
**K associados:** (K01, K02)

## LO2
Analisar laços de repetição por contagem, inclusive quando organizados de forma aninhada.  
**K associados:** (K07, K04, K01)

## LO3
Relacionar atualizações aritméticas iterativas ao valor acumulado produzido ao final da execução.  
**K associados:** (K03, K07, K02)

## LO4
Justificar a saída de um trecho de programa com base no fluxo de execução e no comando de saída.  
**K associados:** (K05, K01, K07)



# 4. Definição de Competências

## 4.1 Competência Geral

No contexto desta task, situada no ensino superior, não se aplica alinhamento à BNCC. Em termos amplos do domínio de Computação, a tarefa contribui para a seguinte competência geral:

**Interpretar e explicar o comportamento de programas imperativos introdutórios a partir da análise do fluxo de execução, do estado das variáveis e dos mecanismos de repetição e saída.**

## 4.2 Especificações de Competências

### CT10.1

**Título da Competência**  
Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões simples

**Descrição Textual**  
Interpretar e manipular dados em programas introdutórios, reconhecendo o papel de variáveis e constantes e avaliando expressões simples que produzem alterações observáveis no estado do programa.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO3)
2. K mobilizados (Núcleo): (K01, K02, K03)

**Especificação de Conhecimentos**

K01 — Modelo de execução e noção de estado (paradigma imperativo)  
Descrição curta: compreensão de que a execução produz mudanças sucessivas no estado das variáveis.  
Justificativa de evidência: a tarefa exige acompanhar o estado da variável ao longo do processamento.

K02 — Variáveis, constantes e tipos primitivos  
Descrição curta: reconhecimento do papel funcional de variáveis e constantes no programa.  
Justificativa de evidência: o estudante precisa reconhecer a variável acumuladora, seu valor inicial e sua atualização.

K03 — Expressões aritméticas e avaliação  
Descrição curta: interpretação do efeito numérico de expressões simples e atualizações sucessivas.  
Justificativa de evidência: a resposta depende de compreender o efeito acumulado do incremento.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Analisar

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → rastrear as mudanças de estado das variáveis ao longo da execução do programa.  
Verbos de Bloom: rastrear, examinar, relacionar

K02 / Aplicar → manipular variáveis e constantes de tipos primitivos conforme seu papel no processamento.  
Verbos de Bloom: manipular, usar, operar

K03 / Analisar → relacionar expressões simples e atualizações sucessivas ao valor final produzido.  
Verbos de Bloom: analisar, relacionar, deduzir


**Especificação de Disposições**  
1. Atenção ao estado das variáveis.
2. Precisão no acompanhamento de atualizações.
3. Rigor na interpretação de expressões simples.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.1 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões simples | atenção, precisão, rigor | K01 | rastrear as mudanças de estado das variáveis ao longo da execução do programa |
| CT10.1 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões simples | atenção, precisão, rigor | K02 | manipular variáveis e constantes de tipos primitivos conforme seu papel no processamento |
| CT10.1 | Manipular dados com tipos primitivos, variáveis e constantes, avaliando expressões simples | atenção, precisão, rigor | K03 | relacionar expressões simples e atualizações sucessivas ao valor final produzido |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: analítica
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a atividade exige que o estudante interprete o papel das variáveis e das expressões simples para compreender como o valor final é produzido.



### CT10.2

**Título da Competência**  
Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras

**Descrição Textual**  
Interpretar estruturas de repetição em programas introdutórios, distinguindo mecanismos de controle, contagem, acumulação e parada, inclusive em contextos com laços aninhados.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO2, LO3)
2. K mobilizados (Núcleo): (K04, K07, K03)

**Especificação de Conhecimentos**

K04 — Expressões lógicas e condições  
Descrição curta: compreensão das condições que controlam permanência e término de laços.  
Justificativa de evidência: a interpretação correta da repetição depende da leitura das condições de controle.

K07 — Estruturas de repetição  
Descrição curta: compreensão de laços por contagem e de repetição aninhada.  
Justificativa de evidência: este é o eixo central da tarefa, pois o resultado depende do comportamento dos laços.

K03 — Expressões aritméticas e avaliação  
Descrição curta: interpretação do efeito acumulativo das atualizações realizadas em cada iteração.  
Justificativa de evidência: a repetição só pode ser explicada adequadamente quando associada ao efeito numérico reiterado.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Analisar

**Pareamento Conhecimento–Habilidade**

K04 / Compreender → explicar como as condições controlam a continuidade e a parada dos laços de repetição.  
Verbos de Bloom: explicar, comentar, inferir

K07 / Analisar → decompor o comportamento de laços por contagem, incluindo sua organização aninhada.  
Verbos de Bloom: decompor, examinar, relacionar

K03 / Aplicar → operar a atualização aritmética repetida para interpretar o processo de acumulação no laço.  
Verbos de Bloom: operar, calcular, iterar


**Especificação de Disposições**  
1. Cuidado na leitura das condições de repetição.
2. Persistência no acompanhamento de processos iterativos.
3. Consistência na análise de estruturas aninhadas.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.2 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | cuidado, persistência, consistência | K04 | explicar como as condições controlam a continuidade e a parada dos laços de repetição |
| CT10.2 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | cuidado, persistência, consistência | K07 | decompor o comportamento de laços por contagem, incluindo sua organização aninhada |
| CT10.2 | Controlar o fluxo com repetição utilizando contadores, acumuladores e paradas seguras | cuidado, persistência, consistência | K03 | operar a atualização aritmética repetida para interpretar o processo de acumulação no laço |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: analítica
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a questão exige compreender como os laços se organizam, quantas vezes executam e como a acumulação ocorre sob controle das condições de parada.


### CT10.3

**Título da Competência**  
Justificar a saída de um programa por meio do rastreamento do fluxo e do estado das variáveis

**Descrição Textual**  
Selecionar e justificar a saída produzida por um programa introdutório, articulando fluxo de execução, estado final das variáveis e evidência observável no comando de saída.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO4)
2. K mobilizados (Núcleo): (K01, K05, K07)

**Especificação de Conhecimentos**

K01 — Modelo de execução e noção de estado (paradigma imperativo)  
Descrição curta: compreensão do estado final relevante produzido pela execução.  
Justificativa de evidência: a justificativa depende de associar o processamento ao estado final da variável.

K05 — Estrutura sequencial e E/S básica  
Descrição curta: compreensão da relação entre processamento e valor exibido ao final.  
Justificativa de evidência: a tarefa solicita a previsão da saída efetivamente mostrada pelo programa.

K07 — Estruturas de repetição  
Descrição curta: interpretação do papel da repetição na produção do resultado final.  
Justificativa de evidência: a saída só pode ser justificada corretamente quando a repetição é compreendida.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Avaliar

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → relacionar o estado final do programa ao valor que será apresentado na saída.  
Verbos de Bloom: relacionar, examinar, rastrear

K05 / Avaliar → justificar a saída exibida com base no processamento realizado pelo programa.  
Verbos de Bloom: justificar, verificar, defender

K07 / Analisar → examinar como a repetição interfere diretamente no resultado final observado.  
Verbos de Bloom: examinar, relacionar, deduzir


**Especificação de Disposições**  
1. Clareza na argumentação técnica.
2. Compromisso com evidências observáveis.
3. Prudência na escolha entre alternativas.

**Competências Alinhadas à BNCC**  
Não se aplica.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT10.3 | Justificar a saída de um programa por meio do rastreamento do fluxo e do estado das variáveis | clareza, evidência, prudência | K01 | relacionar o estado final do programa ao valor que será apresentado na saída |
| CT10.3 | Justificar a saída de um programa por meio do rastreamento do fluxo e do estado das variáveis | clareza, evidência, prudência | K05 | justificar a saída exibida com base no processamento realizado pelo programa |
| CT10.3 | Justificar a saída de um programa por meio do rastreamento do fluxo e do estado das variáveis | clareza, evidência, prudência | K07 | examinar como a repetição interfere diretamente no resultado final observado |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: justificatória
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: como a questão é de múltipla escolha com justificativa breve, o estudante precisa converter a análise do fluxo em defesa técnica verificável da alternativa selecionada.

