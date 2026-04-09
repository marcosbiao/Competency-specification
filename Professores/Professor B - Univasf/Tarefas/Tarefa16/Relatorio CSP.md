# RELATÓRIO CSP - TASK16

## Introdução

Este relatório situa a tarefa na fase de Autoria de Competências do Competency Specification Process, com foco na explicitação rastreável de conhecimentos, objetivos de aprendizagem e competências mobilizados pela atividade. A tarefa propõe a implementação, em linguagem C, de um sistema simples de cadastro de alunos com persistência em arquivo binário, listagem de registros, busca por ID e exibição de arquivos do diretório de trabalho.

Trata-se de uma entidade instrucional adequada à elicitação de evidências observáveis porque exige um artefato executável, operações verificáveis por menu, persistência entre execuções e justificativa breve sobre decisões de implementação. O modelo K–S–D é suportado sem redundância porque a tarefa combina conhecimentos conceituais da programação imperativa, habilidades observáveis de implementação e disposições ligadas à precisão técnica, à organização funcional e à verificabilidade do comportamento do sistema.

## 1. Análise da Entidade Instrucional

### Título

Sistema de Cadastro de Alunos com Persistência em Arquivo Binário

### Descrição

A tarefa requer o desenvolvimento de um programa em C com interface textual por menu, capaz de cadastrar alunos em arquivo binário, listar registros armazenados, buscar registros por ID e exibir os arquivos do diretório de trabalho. A atividade mobiliza persistência simples, fluxo de controle, modularização por funções e acesso sequencial a dados persistidos.

### Processo de Desenvolvimento da Solução

1. Delimitar as funcionalidades do sistema e o fluxo geral das opções do menu.
2. Modelar o registro de aluno e definir a organização dos dados manipulados pelo programa.
3. Implementar rotinas funcionais para cadastro, listagem, busca e exibição do conteúdo do diretório.
4. Integrar as rotinas em um fluxo interativo consistente, com entradas e saídas verificáveis.
5. Validar o comportamento do sistema por meio da execução das operações e da persistência dos registros.
6. Registrar justificativa breve sobre as decisões adotadas para armazenamento, consulta e organização funcional.

### Resultados Esperados

1. Programa em C compilável e executável.
2. Menu textual funcional com as operações previstas.
3. Persistência de registros em arquivo binário.
4. Listagem consistente dos alunos armazenados.
5. Busca sequencial por ID com resultado verificável.
6. Exibição dos arquivos acessíveis no diretório de trabalho.
7. Justificativa breve sobre a organização da solução.

### Contexto de Aquisição

- **Curso:** Ciência da Computação  
- **Organização:** atividade individual  
- **Ambiente:** laboratório de programação ou avaliação prática introdutória  
- **Avaliação:** análise do código, da coerência do fluxo computacional, da consistência das variáveis de saída e da verificabilidade dos resultados

### Perfil do Público-Alvo

Estudantes em fase introdutória da programação imperativa em linguagem C, já familiarizados com tipos primitivos, entrada e saída básica, seleção, repetição e noções iniciais de funções. A tarefa atende especialmente a estudantes que precisam integrar conteúdos previamente estudados em uma miniaplicação com persistência e organização modular.

### Nível de Proficiência (critérios e dimensões)

| Nível | Persistência em arquivo | Organização modular | Fluxo interativo e controle | Busca e listagem | Justificativa técnica |
|---|---|---|---|---|---|
| **N1 - Inicial** | Grava ou lê de forma parcial, sem consistência entre operações | Concentra a lógica em bloco único ou com funções pouco coesas | Implementa menu incompleto ou com falhas de decisão | Percorre registros de modo incompleto ou com critério impreciso | Descreve superficialmente o que o sistema faz |
| **N2 - Intermediário** | Realiza gravação e leitura básicas, com limitações de integração | Separa parte das operações em funções, ainda com acoplamento elevado | Implementa menu funcional, com cobertura parcial dos casos | Lista e busca com consistência básica | Explica parcialmente o funcionamento |
| **N3 - Proficiente** | Mantém persistência coerente entre cadastro, listagem e busca | Decompõe a solução em funções com responsabilidades claras | Implementa menu completo, com decisões e respostas consistentes | Realiza varredura sequencial correta, com parada e seleção verificáveis | Relaciona fluxo, estado e persistência com coerência |
| **N4 - Avançado** | Organiza a persistência de modo robusto, justificando escolhas técnicas e integrando operações de diretório | Estrutura a solução com alta coesão, baixo acoplamento e integração consistente entre rotinas | Trata o fluxo com clareza, previsibilidade e justificativa técnica para as escolhas de controle | Evidencia clareza operacional, tratamento consistente dos resultados e justificativa do critério de consulta | Justifica tecnicamente o comportamento do sistema, distinguindo decisões de projeto, execução e persistência |

## 2. Seleção e Enumeração de Conhecimentos

Foram selecionados 7 conhecimentos do catálogo, suficientes para cobrir a tarefa com rastreabilidade e sem explosão de granularidade.

**K01: Modelo de execução e noção de estado (paradigma imperativo)**
1. Compreensão de que o programa evolui por mudanças de estado ao longo da execução.
2. Relação entre sequência de comandos, chamadas funcionais e efeitos observáveis.
3. Explicitação do comportamento operacional do sistema em função do fluxo executado.

Justificativa de mobilização na tarefa: a atividade exige coerência entre menu, operações executadas e persistência dos dados, o que demanda compreensão do estado do programa e de suas transições.

**K02: Variáveis, constantes e tipos primitivos**
1. Representação de dados simples por meio de identificadores e tipos compatíveis.
2. Coerência entre campos manipulados, comparações e armazenamento.
3. Uso consistente de identificadores relacionados ao cadastro e à busca por ID.

Justificativa de mobilização na tarefa: o sistema depende de dados tipados de forma consistente para cadastro, gravação, leitura e consulta dos registros.

**K05: Estrutura sequencial e E/S básica**
1. Organização do fluxo entrada, processamento e saída.
2. Leitura de dados fornecidos pelo usuário e apresentação de saídas verificáveis.
3. Encadeamento coerente das operações interativas do sistema.

Justificativa de mobilização na tarefa: o programa é interativo, orientado por menu e precisa manter entradas e saídas consistentes em todas as funcionalidades solicitadas.

**K06: Estruturas de seleção**
1. Escolha de caminhos alternativos com base em opções e condições.
2. Tratamento coerente de ramos de execução do menu e de condições de busca.
3. Cobertura de casos básicos de decisão no controle do sistema.

Justificativa de mobilização na tarefa: as funcionalidades do menu e a identificação de registros por ID dependem de decisões explícitas e verificáveis.

**K07: Estruturas de repetição**
1. Percurso repetido de blocos de comandos com critério claro de parada.
2. Varredura sequencial de dados persistidos.
3. Repetição das interações do menu e das operações de listagem e busca.

Justificativa de mobilização na tarefa: a listagem de registros, a busca sequencial e a manutenção do menu interativo exigem iteração controlada.

**K11: Subprogramas: procedimentos e funções**
1. Decomposição da solução em unidades funcionais com responsabilidade definida.
2. Integração entre chamadas, parâmetros e efeitos esperados.
3. Organização modular do programa.

Justificativa de mobilização na tarefa: a atividade exige explicitamente modularização com funções, tornando esse conhecimento central para a estrutura da solução.

**K13: Arquivos e diretórios (persistência e organização básica)**
1. Leitura e escrita de dados em arquivo com persistência simples.
2. Recuperação de informações armazenadas entre execuções.
3. Noções de diretório aplicadas à exibição dos arquivos acessíveis ao programa.

Justificativa de mobilização na tarefa: o núcleo do sistema está na persistência em arquivo binário e na exibição de conteúdo do diretório de trabalho.

## 3. Identificação de Objetivos de Aprendizagem

### LO1

Implementar fluxo interativo de operação com menu textual e respostas verificáveis ao usuário.

**K associados:** (K05, K06)

### LO2

Organizar uma solução em funções coesas, com responsabilidades técnicas delimitadas e integração consistente entre chamadas.

**K associados:** (K11, K01, K05)

### LO3

Persistir, listar e consultar registros de forma consistente em arquivo binário, preservando a integridade dos dados entre execuções.

**K associados:** (K13, K02, K05, K06, K07)

### LO4

Explicar o comportamento do sistema em termos de estado do programa, fluxo de execução e efeito das operações de persistência.

**K associados:** (K01, K13, K05)

### LO5

Integrar ao sistema uma rotina de exibição do conteúdo do diretório de trabalho, em coerência com o fluxo interativo do programa.

**K associados:** (K13, K11, K05)

## 4. Definição de Competências

### 4.1 Competência Geral

Desenvolver programas imperativos introdutórios em linguagem C que integrem modelagem de dados, organização funcional, controle de fluxo e persistência simples, produzindo artefatos executáveis verificáveis e tecnicamente justificáveis.

BNCC: não aplicável ao contexto informado.

### 4.2 Especificações de Competências

#### CT16.1

**Título da Competência**  
Desenvolver rotinas de persistência e consulta de registros em arquivos binários

**Descrição Textual**  
Implementar soluções introdutórias que armazenem, recuperem, listem e consultem dados estruturados em arquivos, preservando a integridade dos registros, a coerência dos tipos e a verificabilidade dos resultados apresentados ao usuário.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO3, LO5)
2. K mobilizados: (K13, K02, K05, K06, K07)

**Especificação de Conhecimentos**
1. K13: leitura e escrita em arquivo com persistência simples. Evidência direta na gravação, recuperação e exibição de registros e conteúdo do diretório.
2. K02: coerência entre campos e tipos manipulados. Evidência direta na estabilidade dos dados gravados, lidos e consultados.
3. K05: fluxo de entrada, processamento e saída. Evidência direta nas interações de cadastro, listagem e consulta.
4. K06: decisão baseada em opções e critérios de seleção. Evidência direta na escolha das funcionalidades e na busca por ID.
5. K07: repetição controlada para percorrer registros. Evidência direta na listagem e na varredura sequencial de dados persistidos.

**Alinhamento com a Taxonomia de Bloom**  
Predominância de Criar, com apoio de Aplicar.

**Pareamento Conhecimento–Habilidade**

K13 / Criar → desenvolver rotinas de gravação, leitura, listagem e consulta em arquivo binário, preservando a persistência dos registros entre execuções.  
Verbos de Bloom: desenvolver, programar, produzir

K02 / Aplicar → declarar e utilizar tipos compatíveis com os dados persistidos e com a chave de consulta do sistema.  
Verbos de Bloom: implementar, usar, armazenar

K05 / Aplicar → executar o fluxo de entrada, processamento e saída das operações de cadastro, listagem e busca de forma verificável.  
Verbos de Bloom: implementar, executar, operar

K06 / Aplicar → usar decisões explícitas para acionar funcionalidades e selecionar registros compatíveis com o critério de consulta.  
Verbos de Bloom: usar, implementar, resolver

K07 / Aplicar → implementar laços com parada garantida para percorrer registros persistidos de forma completa e verificável.  
Verbos de Bloom: implementar, iterar, operar

**Especificação de Disposições**  
1. Precisão no tratamento dos dados persistidos.
2. Cuidado com a consistência entre entrada, armazenamento e recuperação.
3. Atenção à completude do percurso sobre os registros.
4. Compromisso com a verificabilidade dos resultados produzidos.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto informado.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.1 | Desenvolver rotinas de persistência e consulta de registros em arquivos binários | Precisão; consistência; completude; verificabilidade | K13 | desenvolver rotinas de gravação, leitura, listagem e consulta em arquivo binário, preservando a persistência dos registros entre execuções |
| CT16.1 | Desenvolver rotinas de persistência e consulta de registros em arquivos binários | Precisão; consistência; completude; verificabilidade | K02 | declarar e utilizar tipos compatíveis com os dados persistidos e com a chave de consulta do sistema |
| CT16.1 | Desenvolver rotinas de persistência e consulta de registros em arquivos binários | Precisão; consistência; completude; verificabilidade | K05 | executar o fluxo de entrada, processamento e saída das operações de cadastro, listagem e busca de forma verificável |
| CT16.1 | Desenvolver rotinas de persistência e consulta de registros em arquivos binários | Precisão; consistência; completude; verificabilidade | K06 | usar decisões explícitas para acionar funcionalidades e selecionar registros compatíveis com o critério de consulta |
| CT16.1 | Desenvolver rotinas de persistência e consulta de registros em arquivos binários | Precisão; consistência; completude; verificabilidade | K07 | implementar laços com parada garantida para percorrer registros persistidos de forma completa e verificável |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a persistência em arquivo binário, a listagem, a busca por ID e a exibição de conteúdo relacionado ao diretório são exigências centrais da tarefa. Essa competência concentra, em uma formulação única, as evidências diretamente ligadas ao trabalho com arquivos e consulta de registros.

#### CT16.2

**Título da Competência**  
Modularizar programas interativos em C com fluxo de controle verificável

**Descrição Textual**  
Organizar programas introdutórios em módulos funcionais integrados por fluxo de controle explícito, assegurando coesão entre responsabilidades, interação textual verificável e articulação consistente entre rotinas.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO1, LO2, LO5)
2. K mobilizados: (K11, K05, K06, K13)

**Especificação de Conhecimentos**
1. K11: decomposição da solução em funções. Evidência direta na separação das operações do sistema em rotinas distintas.
2. K05: organização sequencial da interação com o usuário. Evidência direta no funcionamento do menu e das saídas correspondentes.
3. K06: tomada de decisão no controle do menu. Evidência direta no acionamento correto das funcionalidades.
4. K13: integração de operações ligadas a arquivo e diretório ao fluxo geral do sistema. Evidência direta na articulação entre menu e persistência.

**Alinhamento com a Taxonomia de Bloom**  
Predominância de Criar, com apoio de Aplicar e Analisar.

**Pareamento Conhecimento–Habilidade**

K11 / Criar → projetar e desenvolver funções coesas que distribuam de modo claro as responsabilidades técnicas do sistema.  
Verbos de Bloom: projetar, desenvolver, programar

K05 / Aplicar → implementar o fluxo interativo por menu com entradas, processamento e saídas consistentes.  
Verbos de Bloom: implementar, executar, operar

K06 / Aplicar → acionar corretamente os caminhos de execução do sistema a partir das opções informadas pelo usuário.  
Verbos de Bloom: usar, implementar, executar

K13 / Aplicar → integrar ao fluxo do programa as operações que dependem de arquivos e diretórios.  
Verbos de Bloom: operar, usar, recuperar

**Especificação de Disposições**  
1. Organização na decomposição da solução.
2. Clareza na definição de responsabilidades das funções.
3. Consistência no encadeamento do fluxo de controle.
4. Compromisso com a legibilidade operacional do artefato.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto informado.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.2 | Modularizar programas interativos em C com fluxo de controle verificável | Organização; clareza funcional; consistência; legibilidade | K11 | projetar e desenvolver funções coesas que distribuam de modo claro as responsabilidades técnicas do sistema |
| CT16.2 | Modularizar programas interativos em C com fluxo de controle verificável | Organização; clareza funcional; consistência; legibilidade | K05 | implementar o fluxo interativo por menu com entradas, processamento e saídas consistentes |
| CT16.2 | Modularizar programas interativos em C com fluxo de controle verificável | Organização; clareza funcional; consistência; legibilidade | K06 | acionar corretamente os caminhos de execução do sistema a partir das opções informadas pelo usuário |
| CT16.2 | Modularizar programas interativos em C com fluxo de controle verificável | Organização; clareza funcional; consistência; legibilidade | K13 | integrar ao fluxo do programa as operações que dependem de arquivos e diretórios |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: construtiva
3. Função de ativação: núcleo
4. Justificativa curta baseada na tarefa: a atividade exige explicitamente modularização com funções e interface por menu. A competência é ativada diretamente no desenho do programa, na distribuição de responsabilidades e na integração das opções do sistema.

#### CT16.3

**Título da Competência**  
Justificar o comportamento operacional de sistemas imperativos com persistência simples

**Descrição Textual**  
Explicar tecnicamente como o fluxo de execução, as decisões de controle e as operações de persistência produzem estados observáveis em programas imperativos introdutórios.

**Cobertura e rastreabilidade**
1. LOs cobertos: (LO4)
2. K mobilizados: (K01, K05, K13, K06, K02)

**Especificação de Conhecimentos**
1. K01: transições de estado em programas imperativos. Evidência direta na justificativa do comportamento do sistema ao longo da execução.
2. K05: coerência entre entrada, processamento e saída. Evidência direta na explicação do fluxo operacional apresentado ao usuário.
3. K13: efeito da persistência no comportamento do sistema. Evidência direta na justificativa sobre armazenamento e recuperação entre execuções.
4. K06: decisões de fluxo. Evidência direta na justificativa das opções e consultas do sistema.
5. K02: representação dos dados. Evidência direta na explicação da estabilidade das informações manipuladas.

**Alinhamento com a Taxonomia de Bloom**  
Predominância de Analisar, com apoio de Avaliar.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → explicitar as transições de estado associadas às escolhas do menu e às chamadas das rotinas do sistema.  
Verbos de Bloom: analisar, rastrear, estruturar

K05 / Analisar → examinar a coerência entre entradas fornecidas, processamento realizado e saídas produzidas pelo programa.  
Verbos de Bloom: examinar, rastrear, relacionar

K13 / Analisar → explicar como a persistência em arquivo influencia o comportamento do sistema entre uma execução e outra.  
Verbos de Bloom: contextualizar, relacionar, examinar

K06 / Avaliar → justificar a adequação das decisões de fluxo empregadas para tratar opções e consultas do sistema.  
Verbos de Bloom: justificar, validar, decidir

K02 / Analisar → correlacionar a representação dos dados com os resultados observados nas operações de cadastro e busca.  
Verbos de Bloom: correlacionar, distinguir, examinar

**Especificação de Disposições**  
1. Rigor na explicação do comportamento do programa.
2. Clareza ao relacionar evidências do artefato com decisões de implementação.
3. Cuidado com a coerência entre justificativa e execução observável.
4. Disposição para validar tecnicamente a própria solução.

**Competências Alinhadas à BNCC**  
Não aplicável ao contexto informado.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT16.3 | Justificar o comportamento operacional de sistemas imperativos com persistência simples | Rigor; clareza; coerência; validação técnica | K01 | explicitar as transições de estado associadas às escolhas do menu e às chamadas das rotinas do sistema |
| CT16.3 | Justificar o comportamento operacional de sistemas imperativos com persistência simples | Rigor; clareza; coerência; validação técnica | K05 | examinar a coerência entre entradas fornecidas, processamento realizado e saídas produzidas pelo programa |
| CT16.3 | Justificar o comportamento operacional de sistemas imperativos com persistência simples | Rigor; clareza; coerência; validação técnica | K13 | explicar como a persistência em arquivo influencia o comportamento do sistema entre uma execução e outra |
| CT16.3 | Justificar o comportamento operacional de sistemas imperativos com persistência simples | Rigor; clareza; coerência; validação técnica | K06 | justificar a adequação das decisões de fluxo empregadas para tratar opções e consultas do sistema |
| CT16.3 | Justificar o comportamento operacional de sistemas imperativos com persistência simples | Rigor; clareza; coerência; validação técnica | K02 | correlacionar a representação dos dados com os resultados observados nas operações de cadastro e busca |

**Definição de Ativação**
1. Restrição de ativação: obrigatória
2. Modo de ativação: justificatória
3. Função de ativação: apoio
4. Justificativa curta baseada na tarefa: embora o artefato principal seja o programa executável, a tarefa também requer justificativa breve sobre as decisões adotadas. Essa competência apoia a interpretação técnica da implementação e amplia a verificabilidade do entendimento do estudante.