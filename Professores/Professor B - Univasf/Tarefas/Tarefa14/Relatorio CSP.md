# Relatório CSP — TASK14

## Introdução

Este relatório situa a tarefa na fase de **Autoria de Competências** do Competency Specification Process. A atividade solicita a implementação de um programa capaz de ler valores inteiros positivos em laço, interromper a execução por sentinela negativa, manter uma janela móvel de cinco observações em vetor e calcular, a cada atualização válida, a média correspondente. Além disso, o enunciado exige modularização explícita por subprogramas para atualização do vetor e cálculo da média.

A tarefa elicita evidências observáveis porque produz artefatos diretamente verificáveis: código-fonte funcional, atualização consistente da estrutura de dados, saídas associadas às iterações válidas e organização modular da solução. Esses elementos permitem observar conhecimentos da disciplina, habilidades operacionais e disposições ligadas à precisão, consistência e organização do raciocínio computacional.

O modelo K–S–D é adequado a esta tarefa porque há mobilização articulada de conhecimentos, objetivos observáveis de desempenho e disposições profissionais elementares de programação. O recorte adotado busca evitar redundância e preservar reuso, selecionando apenas os conhecimentos estritamente necessários para caracterizar a competência mobilizada pela atividade.

## 1. Análise da Entidade Instrucional

### Título

Média móvel com vetor e subprogramas

### Descrição

A tarefa requer a construção de um programa imperativo que receba uma sequência de entradas inteiras positivas, use um valor negativo como sentinela de encerramento, mantenha uma janela fixa de cinco observações e calcule a média móvel a cada atualização válida. O problema exige o uso coordenado de laço de repetição, vetor, cálculo numérico e decomposição funcional em subprogramas.

### Processo de Desenvolvimento da Solução

1. Interpretar as regras de entrada, término e processamento da atividade.
2. Definir a estrutura de armazenamento para manter cinco observações correntes.
3. Organizar o laço de leitura com término por valor negativo.
4. Atualizar a janela de dados a cada nova entrada válida, preservando a lógica de descarte do valor mais antigo.
5. Calcular a média da janela corrente por meio de subprograma próprio.
6. Emitir a saída correspondente a cada atualização válida.
7. Integrar os subprogramas ao fluxo principal e verificar a consistência do comportamento global.

### Resultados Esperados

- programa funcional em C
- vetor de cinco posições atualizado de forma consistente
- laço de leitura com parada controlada por sentinela
- cálculo correto da média móvel
- saídas verificáveis associadas às iterações válidas
- uso obrigatório de subprogramas para atualização do vetor e cálculo da média
- justificativa breve ou comentários objetivos sobre a responsabilidade de cada subprograma

### Contexto de Aquisição 

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### Perfil do Público-Alvo

Trata-se de estudantes em fase inicial de formação em programação imperativa. Pressupõem-se conhecimentos prévios de leitura e escrita básicas, variáveis, tipos primitivos, expressões aritméticas, estruturas condicionais simples, laços introdutórios e noções iniciais de vetor e função. A principal necessidade pedagógica é integrar esses conhecimentos em uma solução única, com evidência de estado, repetição, processamento de coleção e modularização.

### Nível de Proficiência (critérios e dimensões)

| Nível | Leitura iterativa e sentinela | Manipulação de vetor e janela móvel | Cálculo e representação da média | Modularização por subprogramas |
|---|---|---|---|---|
| **N1 — Inicial** | Identifica parcialmente a regra de término, mas não mantém laço confiável. | Armazena dados sem preservar corretamente a janela de cinco valores. | Realiza cálculo incompleto ou incompatível com os dados armazenados. | Separa trechos de código sem responsabilidade clara. |
| **N2 — Intermediário** | Implementa laço com término, porém com fragilidade em casos válidos e inválidos. | Atualiza a coleção com inconsistências ocasionais na ordem ou no descarte. | Calcula a média em parte dos casos, com limitações de representação ou integração ao fluxo. | Usa subprogramas, mas com interfaces pouco coesas ou integração incompleta. |
| **N3 — Proficiente** | Organiza laço estável com sentinela negativa e processamento consistente das entradas válidas. | Mantém a janela fixa com descarte consistente do valor mais antigo e inserção correta do novo valor. | Calcula e apresenta a média móvel de modo correto e coerente com a janela corrente. | Distribui responsabilidades entre subprogramas coerentes para atualização e cálculo. |
| **N4 — Avançado** | Generaliza o padrão de leitura com robustez, clareza e justificativa técnica do controle de fluxo. | Otimiza ou abstrai a atualização de forma clara, mantendo total rastreabilidade do estado. | Justifica escolhas de representação e encapsula o cálculo com elevado grau de clareza e reuso. | Projeta decomposição modular com alta coesão, baixo acoplamento e justificativa consistente. |

## 2. Seleção e Enumeração de Conhecimentos

### K02 — Variáveis, constantes e tipos primitivos

- representar valores inteiros de entrada e resultado numérico da média com tipos compatíveis
- utilizar variáveis de armazenamento e apoio ao cálculo de forma coerente
- preservar consistência entre papel do dado e representação adotada

Justificativa de mobilização na tarefa: a entrada é composta por inteiros positivos, enquanto a média pode exigir representação não inteira, o que mobiliza escolha e uso coerente de tipos primitivos.

### K03 — Expressões aritméticas e avaliação

- compor e avaliar expressões numéricas para agregação dos valores da janela
- empregar operadores e atribuições de modo coerente com o cálculo requerido
- assegurar correspondência entre soma acumulada, divisão e resultado produzido

Justificativa de mobilização na tarefa: a tarefa exige cálculo de média móvel, o que depende de expressão aritmética correta e de avaliação consistente sobre os cinco valores correntes.

### K04 — Expressões lógicas e condições

- formular a condição de término associada ao valor negativo sentinela
- distinguir valores válidos de processamento e valor de encerramento
- relacionar regra do enunciado com a condição booleana usada no controle do fluxo

Justificativa de mobilização na tarefa: o encerramento do programa depende de uma condição explícita sobre o valor lido, tornando indispensável a formulação correta de expressões lógicas.

### K05 — Estrutura sequencial e E/S básica

- organizar o fluxo de leitura, processamento e escrita em sequência verificável
- produzir saídas compatíveis com cada atualização válida da janela
- integrar chamadas de subprogramas ao fluxo principal do programa

Justificativa de mobilização na tarefa: a atividade é observada por meio do comportamento de entrada e saída do programa, de modo que a organização sequencial do processamento é evidência central.

### K07 — Estruturas de repetição

- controlar repetição de leitura orientada por condição de parada
- percorrer ou atualizar coleção de dados de forma iterativa
- manter coerência entre iteração, processamento e término do laço

Justificativa de mobilização na tarefa: a leitura contínua até sentinela e a atualização recorrente da janela de cinco observações exigem uso efetivo de laços de repetição.

### K08 — Vetores e matrizes em C

- representar uma série de observações correntes em estrutura homogênea indexada
- acessar, atualizar e percorrer posições de vetor com consistência
- usar o vetor como suporte para armazenamento e cálculo sobre coleção finita

Justificativa de mobilização na tarefa: o enunciado determina explicitamente o armazenamento dos valores em vetor e exige atualização da coleção corrente de cinco observações.

### K11 — Subprogramas: procedimentos e funções

- decompor a solução em unidades coesas de responsabilidade
- definir subprogramas para atualização de estrutura e cálculo numérico
- integrar parâmetros, efeitos e retornos ao programa principal

Justificativa de mobilização na tarefa: o uso de subprogramas não é opcional nesta atividade, sendo parte explícita do comportamento esperado e da evidência de organização modular.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Implementar leitura iterativa de dados com término controlado por sentinela e distinção entre entradas válidas e condição de encerramento.

**K associados:** K04, K05, K07

### LO2

Manipular vetores em processamento iterativo, preservando a coleção corrente de dados conforme as regras do problema.

**K associados:** K07, K08

### LO3

Processar resultados numéricos sobre dados armazenados, utilizando expressão aritmética e representação compatíveis com o resultado produzido.

**K associados:** K02, K03, K08

### LO4

Produzir saídas verificáveis em programas que integram leitura, atualização de dados e processamento numérico.

**K associados:** K05, K07, K08

### LO5

Modularizar programas introdutórios em subprogramas com responsabilidades bem definidas para atualização de dados e cálculo.

**K associados:** K05, K08, K11

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver soluções introdutórias de programação imperativa que integrem entrada e saída, controle de fluxo, estruturas indexadas, processamento numérico e modularização por subprogramas para produzir comportamento verificável e tecnicamente coerente.

**Alinhamento com BNCC:** não aplicável ao contexto informado.

### 4.2 Especificações de Competências

### CT14.1

**Título da Competência**  
Controlar fluxo iterativo de leitura e processamento com condição explícita de término

**Descrição Textual**  
Organizar programas que realizam leitura contínua de dados e processam entradas válidas até uma condição de término claramente definida, preservando consistência entre controle do laço, regras de validação e emissão de resultados.

**Cobertura e rastreabilidade**
- LOs cobertos: LO1, LO4
- K mobilizados: K04, K05, K07

**Especificação de Conhecimentos**
- K04: expressões lógicas e condições para formular sentinela e validar o fluxo de leitura. Evidência direta na condição de término e no tratamento do valor negativo.
- K05: estrutura sequencial e E/S básica para conectar leitura, processamento e saída. Evidência direta no comportamento observável do programa a cada iteração válida.
- K07: estruturas de repetição para sustentar laço com parada garantida. Evidência direta na leitura contínua e no processamento iterativo.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomina o nível **Aplicar**, com componente de **Analisar** limitado à formulação correta da condição de término no fluxo iterativo.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → formular a condição de término e de aceitação das entradas conforme as regras do problema.  
Verbos de Bloom: aplicar, implementar, operar

K05 / Aplicar → organizar a sequência de leitura, processamento e saída de modo verificável em cada iteração válida.  
Verbos de Bloom: implementar, executar, operar

K07 / Aplicar → manter um laço de leitura com parada garantida e processamento associado a cada nova entrada válida.  
Verbos de Bloom: iterar, implementar, executar

**Especificação de Disposições**
- atenção às regras de término e validade dos dados
- disciplina na manutenção da consistência do fluxo
- cuidado com resultados observáveis e verificáveis

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT14.1 | Controlar fluxo iterativo de leitura e processamento com condição explícita de término | atenção às regras de término; disciplina na consistência do fluxo; cuidado com verificabilidade | K04 | formular a condição de término e de aceitação das entradas conforme as regras do problema |
| CT14.1 | Controlar fluxo iterativo de leitura e processamento com condição explícita de término | atenção às regras de término; disciplina na consistência do fluxo; cuidado com verificabilidade | K05 | organizar a sequência de leitura, processamento e saída de modo verificável em cada iteração válida |
| CT14.1 | Controlar fluxo iterativo de leitura e processamento com condição explícita de término | atenção às regras de término; disciplina na consistência do fluxo; cuidado com verificabilidade | K07 | manter um laço de leitura com parada garantida e processamento associado a cada nova entrada válida |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade depende diretamente de um laço que lê valores sucessivos e interrompe o processamento por sentinela negativa. Sem essa ativação, não há produção válida das saídas nem integração correta entre entrada e processamento.

### CT14.2

**Título da Competência**  
Manipular dados em vetores e processamentos iterativos para produzir resultados numéricos verificáveis

**Descrição Textual**  
Organizar programas que armazenam, atualizam e percorrem coleções lineares em contexto iterativo, articulando estrutura de dados, cálculo numérico e representação compatível para gerar resultados corretos e observáveis.

**Cobertura e rastreabilidade**
- LOs cobertos: LO2, LO3, LO4
- K mobilizados: K02, K03, K07, K08

**Especificação de Conhecimentos**
- K02: variáveis, constantes e tipos primitivos para representar entrada, armazenamento intermediário e resultado numérico. Evidência direta na compatibilidade entre dados inteiros e média produzida.
- K03: expressões aritméticas e avaliação para compor o cálculo solicitado sobre o conjunto corrente de dados. Evidência direta no processamento do resultado numérico.
- K07: estruturas de repetição para sustentar atualização e percorrimento da coleção no fluxo do programa. Evidência direta na dinâmica iterativa de processamento.
- K08: vetores em C para representar e manipular a coleção linear de observações. Evidência direta na estrutura de dados exigida e no processamento sobre seus elementos.

**Alinhamento com a Taxonomia de Bloom (revisada)**  
Predomina o nível **Aplicar**, pois a competência exige implementar manipulação de dados e processamento numérico corretos sobre estruturas indexadas em contexto iterativo.

**Pareamento Conhecimento–Habilidade**

K02 / Aplicar → representar dados de entrada, armazenamento e resultado com tipos compatíveis ao processamento realizado.  
Verbos de Bloom: usar, manipular, implementar

K03 / Aplicar → computar resultados numéricos sobre os dados armazenados por meio de expressões aritméticas coerentes.  
Verbos de Bloom: calcular, computar, operar

K07 / Aplicar → coordenar o processamento iterativo necessário à atualização e ao uso consistente da coleção de dados.  
Verbos de Bloom: iterar, implementar, operar

K08 / Aplicar → armazenar, atualizar e percorrer vetores de forma coerente com o resultado esperado do programa.  
Verbos de Bloom: manipular, armazenar, implementar

**Especificação de Disposições**
- rigor no tratamento dos dados
- atenção à consistência entre armazenamento e processamento
- cuidado com a verificabilidade do resultado

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT14.2 | Manipular dados em vetores e processamentos iterativos para produzir resultados numéricos verificáveis | rigor no tratamento dos dados; atenção à consistência; cuidado com verificabilidade | K02 | representar dados de entrada, armazenamento e resultado com tipos compatíveis ao processamento realizado |
| CT14.2 | Manipular dados em vetores e processamentos iterativos para produzir resultados numéricos verificáveis | rigor no tratamento dos dados; atenção à consistência; cuidado com verificabilidade | K03 | computar resultados numéricos sobre os dados armazenados por meio de expressões aritméticas coerentes |
| CT14.2 | Manipular dados em vetores e processamentos iterativos para produzir resultados numéricos verificáveis | rigor no tratamento dos dados; atenção à consistência; cuidado com verificabilidade | K07 | coordenar o processamento iterativo necessário à atualização e ao uso consistente da coleção de dados |
| CT14.2 | Manipular dados em vetores e processamentos iterativos para produzir resultados numéricos verificáveis | rigor no tratamento dos dados; atenção à consistência; cuidado com verificabilidade | K08 | armazenar, atualizar e percorrer vetores de forma coerente com o resultado esperado do programa |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a atividade exige que a coleção de dados seja atualizada continuamente e utilizada no cálculo de um resultado numérico observável. Por isso, o processamento iterativo sobre vetor constitui evidência central e não apenas operacional da tarefa.

### CT14.3

**Título da Competência**  
Modularizar soluções introdutórias em subprogramas coesos e integrados ao fluxo principal

**Descrição Textual**  
Projetar soluções de programação elementar com decomposição em procedimentos e funções que distribuam responsabilidades de armazenamento, processamento e retorno de resultados de maneira clara, coesa e verificável.

**Cobertura e rastreabilidade**
- LOs cobertos: LO5
- K mobilizados: K05, K08, K11

**Especificação de Conhecimentos**
- K05: estrutura sequencial e E/S básica para integrar chamadas e resultados ao fluxo principal. Evidência direta na composição verificável do programa completo.
- K08: vetores em C para definir os dados manipulados pelos subprogramas da solução. Evidência direta na estrutura compartilhada entre as partes modulares.
- K11: subprogramas para decompor a solução em unidades de responsabilidade clara. Evidência direta na exigência explícita do enunciado.

**Alinhamento com a Taxonomia de Bloom**  
Predomina o nível **Criar**, pois a tarefa exige conceber e implementar uma organização modular da solução, articulando subprogramas distintos para armazenamento e cálculo.

**Pareamento Conhecimento–Habilidade**

K11 / Criar → decompor a solução em subprogramas coesos com responsabilidade explícita de atualização e cálculo.  
Verbos de Bloom: projetar, desenvolver, programar

K08 / Aplicar → definir o uso da estrutura indexada nos subprogramas de forma coerente com o fluxo da solução.  
Verbos de Bloom: manipular, armazenar, implementar

K05 / Aplicar → integrar chamadas de subprogramas e emissão de saídas ao fluxo principal do programa de modo verificável.  
Verbos de Bloom: executar, implementar, operar

**Especificação de Disposições**
- organização modular do raciocínio
- cuidado com coesão das responsabilidades
- disciplina na integração entre partes da solução
- atenção à clareza estrutural do código

**Competências Alinhadas à BNCC**  
Não aplicável.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT14.3 | Modularizar soluções introdutórias em subprogramas coesos e integrados ao fluxo principal | organização modular; cuidado com coesão; disciplina de integração; atenção à clareza estrutural | K11 | decompor a solução em subprogramas coesos com responsabilidade explícita de atualização e cálculo |
| CT14.3 | Modularizar soluções introdutórias em subprogramas coesos e integrados ao fluxo principal | organização modular; cuidado com coesão; disciplina de integração; atenção à clareza estrutural | K08 | definir o uso da estrutura indexada nos subprogramas de forma coerente com o fluxo da solução |
| CT14.3 | Modularizar soluções introdutórias em subprogramas coesos e integrados ao fluxo principal | organização modular; cuidado com coesão; disciplina de integração; atenção à clareza estrutural | K05 | integrar chamadas de subprogramas e emissão de saídas ao fluxo principal do programa de modo verificável |

**Definição de Ativação**
- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: o enunciado impõe explicitamente o uso de subprogramas para armazenamento e cálculo. A competência de modularização, portanto, não é periférica, mas critério obrigatório de realização adequada da atividade.
