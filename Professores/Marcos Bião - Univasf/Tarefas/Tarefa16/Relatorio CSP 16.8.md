# RELATÓRIO CSP — Autoria de Competências

## Introdução
Este relatório situa a TASK08 na fase de Autoria de Competências do CSP. A tarefa solicita a criação de uma função que receba três valores do tipo `float` e retorne o quadrado do primeiro somado aos outros dois, além da construção de um `main()` que execute essa função. Trata-se de uma atividade curta, mas com evidências observáveis de modelagem funcional, uso correto de tipos primitivos, composição de expressão aritmética e organização do fluxo entre entrada, processamento e saída.

A tarefa produz evidências diretas porque o artefato final precisa compilar, receber valores, invocar a função e exibir um resultado compatível com o enunciado. No modelo K–S–D, os conhecimentos concentram-se em tipos, expressões, estrutura sequencial e subprogramas; as habilidades são observáveis no código executável; e as disposições aparecem na precisão sintática, na disciplina de implementação e na atenção ao contrato da função. A seleção foi mantida enxuta e sem redundância, conforme as regras do catálogo e do template fornecido.

## 1. Análise da Entidade Instrucional

### Título
Função com três valores `float` e retorno de cálculo composto.

### Descrição
O estudante deve implementar, em C, uma função com três parâmetros `float`, responsável por calcular o quadrado do primeiro valor somado aos outros dois. Em seguida, deve construir um programa principal que leia os valores necessários, chame a função e apresente o resultado produzido.

### Processo de Desenvolvimento da Solução
1. Ler e interpretar o enunciado, identificando entradas, processamento e saída.
2. Definir o tipo de retorno e os parâmetros da função.
3. Declarar variáveis `float` coerentes com os dados numéricos do problema.
4. Implementar a expressão aritmética correspondente ao cálculo solicitado.
5. Construir o `main()` para leitura dos dados, chamada da função e exibição do resultado.
6. Verificar se o fluxo completo produz resposta compatível com o enunciado.

### Resultados Esperados
- Código-fonte em C com função corretamente definida.
- Uso correto de parâmetros e valor de retorno.
- `main()` com leitura, invocação da função e exibição do resultado.
- Saída numericamente coerente com o cálculo solicitado.
- Solução apta à submissão e validação em juiz automático.

### Contexto de Aquisição
A tarefa integra uma atividade prática de Introdução à Programação em ambiente de laboratório, com desenvolvimento em linguagem C, restrição de tempo, uso de um único computador por equipe e validação por juiz automático. O foco da atividade é correção funcional, aderência ao enunciado e consistência entre entrada, processamento e saída.

### Perfil do Público-Alvo
- Estudantes de início de curso em Computação ou áreas afins.
- Público com contato inicial com programação estruturada em C.
- Pré-requisitos: variáveis, tipos primitivos, expressões aritméticas, estrutura sequencial e noção introdutória de função.
- Necessidades: consolidar modularização elementar e precisão na implementação de pequenos cálculos.

### Nível de Proficiência (critérios e dimensões)

| Nível | Compreensão do enunciado | Implementação da função | Uso de tipos e variáveis | Fluxo no `main()` | Correção do resultado |
|---|---|---|---|---|---|
| **N1 - Inicial** | Identifica parcialmente entradas e saída, mas com lacunas no processamento | Define a função com erros de assinatura ou retorno | Usa tipos ou variáveis de modo inconsistente | Organiza leitura e chamada com falhas | Resultado incorreto ou instável |
| **N2 - Intermediário** | Reconhece entradas, processamento e saída com pequena imprecisão | Define função válida, mas com fragilidade na expressão ou no retorno | Usa `float` adequadamente na maior parte do código | Constrói `main()` funcional com pequenas limitações | Resultado geralmente correto, com risco de erro pontual |
| **N3 - Proficiente** | Interpreta corretamente o enunciado e o contrato da função | Implementa função com parâmetros, retorno e cálculo corretos | Emprega variáveis e tipos coerentes com o problema | Organiza bem leitura, chamada e saída | Resultado correto e verificável |
| **N4 - Avançado** | Explicita com clareza a relação entre dados, função e saída | Implementa função de forma clara, enxuta e reutilizável | Usa tipos com precisão e nomeação consistente | Estrutura `main()` de modo limpo e facilmente auditável | Resultado correto, com boa legibilidade e rastreabilidade |

## 2. Seleção e Enumeração de Conhecimentos

**K01 — Modelo de execução e noção de estado (paradigma imperativo)**
- Compreender que o programa evolui por atualizações sucessivas de estado.
- Relacionar atribuições e chamadas de função à mudança controlada do estado do programa.
- Reconhecer a ordem de execução entre leitura, processamento e exibição.
- **Justificativa de mobilização na tarefa:** a solução depende da sequência correta entre entrada de valores, chamada da função e apresentação do resultado.

**K02 — Variáveis, constantes e tipos primitivos**
- Declarar identificadores compatíveis com dados numéricos em ponto flutuante.
- Diferenciar papel de parâmetro, variável local e valor retornado.
- Preservar coerência de tipos ao longo do programa.
- **Justificativa de mobilização na tarefa:** os três valores de entrada são `float`, o que exige uso consistente de variáveis e tipos primitivos.

**K03 — Expressões aritméticas e avaliação**
- Construir expressões com operadores aritméticos e precedência adequada.
- Representar o quadrado de um valor e a soma de parcelas numéricas.
- Verificar a coerência do cálculo implementado.
- **Justificativa de mobilização na tarefa:** o núcleo operacional da tarefa é a expressão que calcula o quadrado do primeiro valor somado aos outros dois.

**K05 — Estrutura sequencial e E/S básica**
- Organizar programas no fluxo entrada → processamento → saída.
- Ler valores e apresentar resultados em formato verificável.
- Encadear comandos de modo consistente.
- **Justificativa de mobilização na tarefa:** o `main()` deve operacionalizar leitura, chamada da função e exibição do resultado sem desvios de fluxo.

**K11 — Subprogramas: procedimentos e funções**
- Definir funções com parâmetros e valor de retorno.
- Invocar subprogramas de forma coerente com sua assinatura.
- Utilizar decomposição simples para isolar uma responsabilidade computacional.
- **Justificativa de mobilização na tarefa:** a evidência principal da TASK08 é a criação e uso correto de uma função com retorno numérico.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Definir e invocar funções simples com parâmetros e retorno em linguagem C.  
**K associados:** (K11, K02)

**LO2.** Representar entradas e saídas numéricas com tipos primitivos coerentes ao problema.  
**K associados:** (K02, K05)

**LO3.** Implementar expressões aritméticas compatíveis com uma especificação algorítmica simples.  
**K associados:** (K03, K02)

**LO4.** Organizar programas sequenciais que integrem leitura de dados, processamento funcional e exibição de resultados.  
**K associados:** (K05, K11, K01)

## 4. Definição de Competências

### 4.1 Competência Geral
Construir soluções computacionais simples em linguagem C, mobilizando tipos primitivos, expressões aritméticas, fluxo sequencial e subprogramas para produzir resultados verificáveis em problemas introdutórios de programação.

## 4.2 Especificações de Competências

### CT16.8.1
**Título da Competência**  
Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais.

**Descrição Textual**  
Construir programas introdutórios corretos e verificáveis, utilizando tipos primitivos, expressões aritméticas, estrutura sequencial e convenções sintáticas da linguagem de forma coerente com o problema.

**Cobertura e rastreabilidade**  
- LOs cobertos: (LO2, LO3, LO4)  
- K mobilizados: (K02, K03, K05, K01)

**Especificação de Conhecimentos**  
- **K02:** sustenta a declaração e o uso coerente de variáveis e parâmetros numéricos do tipo `float`.  
- **K03:** viabiliza a construção correta da expressão aritmética pedida no enunciado.  
- **K05:** organiza o fluxo sequencial de leitura, processamento e saída no `main()`.  
- **K01:** dá suporte à compreensão da ordem de execução e da evolução do estado do programa.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, pois o estudante implementa uma solução funcional mobilizando elementos sintáticos e semânticos já introduzidos.

**Pareamento Conhecimento–Habilidade**  
K02 / Aplicar / representar → declarar e usar variáveis `float` coerentes com as entradas e a saída.  
K03 / Aplicar / calcular → implementar a expressão aritmética correspondente ao quadrado do primeiro valor somado aos outros dois.  
K05 / Aplicar / organizar → estruturar o `main()` com leitura, processamento e exibição do resultado.  
K01 / Aplicar / executar → manter a ordem de execução do programa de forma consistente e verificável.

**Especificação de Disposições**  
- precisão sintática  
- atenção à semântica das instruções  
- rigor na verificação do resultado

**Competências alinhadas à BNCC quando aplicável**  
Há convergência geral com o eixo de Programação da BNCC Computação, especialmente na implementação de algoritmos em linguagem de programação.

**Tabela-resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.8.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão sintática, atenção semântica, rigor | K02 | declarar e usar variáveis `float` coerentes |
| CT16.8.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão sintática, atenção semântica, rigor | K03 | implementar corretamente a expressão aritmética |
| CT16.8.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão sintática, atenção semântica, rigor | K05 | organizar leitura, processamento e saída |
| CT16.8.1 | Implementar programas básicos em uma linguagem, compreendendo sintaxe e semântica essenciais | precisão sintática, atenção semântica, rigor | K01 | preservar a ordem de execução do programa |

**Definição de Ativação**  
- Restrição de ativação: obrigatória  
- Modo de ativação: construtiva  
- Função de ativação: núcleo  
- Justificativa curta baseada na tarefa: a solução precisa compilar, ler valores, processar o cálculo e apresentar a resposta correta em linguagem C.


### CT16.8.2
**Título da Competência**  
Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados.

**Descrição Textual**  
Decompor problemas simples em subprogramas coesos, definindo parâmetros, tipo de retorno e chamada de forma compatível com o contrato computacional da solução.

**Cobertura e rastreabilidade**  
- LOs cobertos: (LO1, LO4)  
- K mobilizados: (K11, K02, K05)

**Especificação de Conhecimentos**  
- **K11:** estrutura a definição da função, sua assinatura, seu retorno e sua invocação no programa principal.  
- **K02:** assegura a compatibilidade entre os tipos dos parâmetros, das variáveis e do valor retornado.  
- **K05:** integra a função ao fluxo do `main()`, articulando entrada, chamada e saída.

**Alinhamento com a Taxonomia de Bloom**  
Predomínio de **Aplicar**, pois o estudante utiliza a abstração de função para construir uma solução modular simples e correta.

**Pareamento Conhecimento–Habilidade**  
K11 / Aplicar / implementar → definir e invocar uma função com três parâmetros e retorno compatível com o problema.  
K02 / Aplicar / usar → empregar tipos adequados na assinatura da função e nas variáveis associadas.  
K05 / Aplicar / integrar → articular a chamada da função ao fluxo principal do programa.

**Anotação de Verbos**  
implementar, usar, integrar

**Especificação de Disposições**  
- atenção ao contrato da função  
- clareza na decomposição da solução  
- disciplina na organização modular do código

**Competências alinhadas à BNCC quando aplicável**  
Há convergência geral com o eixo de Programação da BNCC Computação, especialmente na construção de soluções algorítmicas estruturadas e implementadas por módulos simples.

**Tabela-resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.8.2 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | atenção ao contrato, clareza, disciplina | K11 | definir e invocar função com parâmetros e retorno |
| CT16.8.2 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | atenção ao contrato, clareza, disciplina | K02 | empregar tipos adequados na assinatura e no retorno |
| CT16.8.2 | Modularizar soluções por funções/procedimentos com assinaturas e tipos adequados | atenção ao contrato, clareza, disciplina | K05 | integrar a função ao fluxo do `main()` |

**Definição de Ativação**  
- Restrição de ativação: obrigatória  
- Modo de ativação: construtiva  
- Função de ativação: núcleo  
- Justificativa curta baseada na tarefa: a evidência central do enunciado é a criação de uma função com parâmetros `float`, retorno numérico e execução correta a partir do `main()`.