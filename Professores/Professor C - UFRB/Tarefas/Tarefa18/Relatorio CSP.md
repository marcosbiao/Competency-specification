# RELATÓRIO CSP: AUTORIA DE COMPETÊNCIAS

## Introdução

Este relatório situa-se na fase de **Autoria de Competências** do CSP e especifica os conhecimentos, objetivos de aprendizagem e competências mobilizados pela task **TASK18: Desafio Uma Loja Muito Chique**, vinculada à disciplina **Programação de Computadores I**. A tarefa solicita a implementação, em linguagem C, de um sistema simples para gerenciamento de produtos, vendas, estoque e indicadores de desempenho de uma loja fictícia.

A atividade elicita evidências observáveis porque requer um artefato executável, com menu funcional, cadastro de produtos, registro de vendas, atualização de estoque, listagem de dados e geração de relatório de desempenho. Além disso, a entrega inclui um relatório técnico que documenta o processo de desenvolvimento e os resultados obtidos.

A task sustenta o modelo **K-S-D** porque articula conhecimentos fundamentais de programação estruturada, habilidades observáveis na construção do programa e disposições relacionadas a rigor computacional, consistência lógica, organização da solução e verificabilidade dos resultados. A especificação abaixo mantém rastreabilidade explícita e utiliza exclusivamente os conhecimentos definidos no catálogo da disciplina.

## 1. Análise da Entidade Instrucional

### Título

**Sistema de gerenciamento de estoque e vendas de uma loja**

### Descrição

A task requer que o estudante desenvolva, em linguagem C, um sistema para uma loja fictícia. O programa deve apresentar um menu principal com opções para cadastrar produtos, visualizar produtos cadastrados, registrar vendas, listar vendas e obter um relatório de desempenho. O sistema deve manter o estoque atualizado, armazenar informações de produtos e vendas, respeitar os limites máximos definidos no enunciado e produzir indicadores como arrecadação bruta, lucro, produto mais vendido, produto menos vendido e valor médio por venda.

### Processo de Desenvolvimento da Solução

1. Identificar os requisitos funcionais do sistema: cadastro, consulta, venda, listagem e relatório.
2. Definir os dados necessários para representar produtos, vendas, estoque, quantidades e valores monetários.
3. Selecionar tipos de dados compatíveis com nomes, códigos, quantidades e valores.
4. Organizar os dados em vetores, respeitando os limites de produtos e vendas indicados no enunciado.
5. Estruturar o menu principal e a navegação entre as rotinas do sistema.
6. Implementar rotinas de cadastro e consulta de produtos, garantindo atualização coerente do estoque.
7. Implementar o registro de vendas, considerando pedidos com um ou mais produtos e cálculo do valor total.
8. Implementar a listagem de vendas e a geração de indicadores de desempenho a partir dos dados acumulados.
9. Verificar a consistência entre dados armazenados, saídas exibidas e resultados descritos no relatório técnico.

### Resultados Esperados

- Código-fonte em linguagem C, entregue no formato original do arquivo.
- Programa executável com menu principal e navegação coerente entre funcionalidades.
- Cadastro e listagem de produtos com nome, preço de custo, preço de venda e quantidade em estoque.
- Registro de vendas com quantidade de itens, valor da venda e atualização do estoque.
- Listagem das vendas realizadas com código, quantidade de itens e valor correspondente.
- Relatório de desempenho com arrecadação bruta, lucro, produto mais vendido, produto menos vendido, estoque remanescente e valor médio por venda.
- Relatório técnico em PDF, descrevendo o processo de desenvolvimento e os resultados obtidos.

### Contexto de Aquisição

- **Curso:** Ciência da Computação ou curso com disciplina introdutória de programação.
- **Componente curricular:** Programação de Computadores I.
- **Organização:** atividade individual ou em grupo, conforme orientação docente.
- **Ambiente:** laboratório de programação, estudo dirigido ou avaliação prática com desenvolvimento em linguagem C.
- **Avaliação:** análise do código-fonte, execução do sistema, verificação das funcionalidades exigidas e leitura do relatório técnico.

### Perfil do Público-Alvo

O público-alvo é composto por estudantes em formação inicial em programação estruturada, com contato prévio ou em consolidação com entrada e saída de dados, tipos primitivos, variáveis, expressões, estruturas condicionais, estruturas de repetição e vetores. A tarefa é adequada a estudantes que já conseguem resolver problemas pontuais e precisam avançar para a integração de múltiplas rotinas em um único programa executável.

### Nível de Proficiência (critérios e dimensões)

| Nível | Decomposição dos requisitos | Representação de dados | Controle de fluxo | Atualização de estado | Relatórios e saídas |
|---|---|---|---|---|---|
| **N1 - Inicial** | identifica funcionalidades de forma parcial e sem relação clara entre elas | utiliza variáveis ou vetores de forma incompleta ou incoerente | apresenta decisões ou repetições incompletas | atualiza estoque ou vendas de forma inconsistente | produz saídas incompletas ou pouco verificáveis |
| **N2 - Intermediário** | reconhece as principais funcionalidades, mas com lacunas de integração | representa parte dos dados necessários, com fragilidades de tipo ou organização | implementa parte do fluxo, mas com falhas em retornos, limites ou cobertura de casos | registra dados, mas com inconsistências em alguns cenários | apresenta resultados principais, mas com baixa clareza ou inconsistências pontuais |
| **N3 - Proficiente** | organiza as funcionalidades principais em rotinas coerentes | utiliza tipos e vetores de modo adequado aos produtos, vendas e indicadores | controla decisões e repetições de forma funcional | mantém coerência entre cadastro, venda, estoque e listagens | apresenta saídas claras e indicadores coerentes com os dados armazenados |
| **N4 - Avançado** | estrutura o sistema de forma clara, integrada e compatível com todos os requisitos | organiza os dados com precisão, consistência e facilidade de consulta durante a execução | mantém fluxo estável, previsível e bem articulado entre todas as rotinas | preserva o estado do sistema com alta consistência e baixo risco de erro lógico | gera saídas completas, verificáveis e articuladas ao relatório técnico |

## 2. Seleção e Enumeração de Conhecimentos

**K01 — Conceitos básicos de computação e resolução de problemas**

- Compreensão de programa como solução executável para um problema delimitado.
- Identificação de dados, processamento, saídas e requisitos funcionais.
- Formulação de uma solução computacional coerente com uma situação-problema.
- **Justificativa de mobilização na tarefa:** a task exige transformar a descrição de uma loja fictícia em um sistema computacional com funcionalidades verificáveis.

**K02 — Algoritmos e formas de representação**

- Organização de passos finitos e ordenados para resolver partes do problema.
- Estruturação de rotinas de cadastro, venda, listagem e relatório.
- Representação do comportamento esperado antes ou durante a codificação.
- **Justificativa de mobilização na tarefa:** o estudante precisa organizar algoritmicamente várias rotinas interdependentes dentro de um único sistema.

**K03 — Estrutura sequencial, entrada, processamento e saída**

- Encadeamento de leitura, processamento e exibição de resultados.
- Organização das interações do usuário com o sistema.
- Produção de saídas verificáveis a partir dos dados processados.
- **Justificativa de mobilização na tarefa:** todas as funcionalidades dependem de entrada de dados, processamento interno e apresentação de resultados ao usuário.

**K04 — Variáveis, constantes, tipos de dados e atribuição**

- Uso de variáveis para armazenar nomes, códigos, quantidades e valores.
- Seleção de tipos compatíveis com dados textuais, inteiros e monetários.
- Atualização de valores durante cadastros, vendas e cálculos.
- **Justificativa de mobilização na tarefa:** o sistema exige armazenamento e atualização de diferentes dados relacionados a produtos, vendas e indicadores.

**K05 — Expressões aritméticas, relacionais e lógicas**

- Construção de cálculos para valores de venda, lucro, médias e totais.
- Formulação de comparações e condições para controle de fluxo.
- Uso de expressões para apoiar decisões, atualizações e relatórios.
- **Justificativa de mobilização na tarefa:** os indicadores de desempenho, o controle de estoque e as validações dependem de expressões numéricas e lógicas.

**K06 — Estruturas condicionais**

- Seleção de caminhos de execução a partir de opções do menu e regras internas.
- Tratamento de casos como cadastro disponível, ausência de dados e escolha de funcionalidade.
- Decisão entre ações alternativas durante as rotinas do sistema.
- **Justificativa de mobilização na tarefa:** o programa deve responder a escolhas do usuário e tratar cenários distintos de execução.

**K07 — Estruturas de repetição**

- Execução iterativa do menu principal e das rotinas de cadastro, venda e listagem.
- Percorrimento de coleções para consulta, acumulação e cálculo de indicadores.
- Controle de limites de produtos, vendas e itens processados.
- **Justificativa de mobilização na tarefa:** a task exige repetição para navegação, múltiplos cadastros, múltiplas vendas e processamento de vetores.

**K08 — Vetores**

- Armazenamento de coleções homogêneas de dados relacionados a produtos e vendas.
- Acesso por posição para consultar, atualizar e processar informações.
- Percorrimento dos elementos para listagens e cálculos agregados.
- **Justificativa de mobilização na tarefa:** o enunciado exige o uso de vários vetores para representar produtos, estoques, preços, vendas e dados acumulados.

## 3. Identificação de Objetivos de Aprendizagem

**LO1.** Analisar requisitos de um problema computacional introdutório, identificando entradas, saídas, processos e limites de armazenamento.  
**K associados:** (K01, K02, K03)

**LO2.** Implementar entrada, processamento e saída em uma solução estruturada, preservando um fluxo de execução verificável.  
**K associados:** (K03, K04, K05)

**LO3.** Selecionar e utilizar tipos de dados e vetores para armazenar coleções de informações relacionadas.  
**K associados:** (K04, K08)

**LO4.** Aplicar estruturas condicionais e expressões lógicas para controlar casos alternativos de execução em rotinas de programação.  
**K associados:** (K05, K06)

**LO5.** Aplicar estruturas de repetição para percorrer coleções, registrar múltiplas ocorrências e acumular resultados.  
**K associados:** (K05, K07, K08)

**LO6.** Calcular e apresentar indicadores derivados a partir de dados acumulados, mantendo consistência entre registros, estado interno e saídas.  
**K associados:** (K03, K04, K05, K07, K08)

## 4. Definição de Competências

### 4.1 Competência Geral 

**Implementar soluções computacionais introdutórias em linguagem estruturada, articulando análise de requisitos, representação de dados, controle de fluxo, manipulação de coleções e produção de saídas verificáveis.**

### 4.2 Especificações de Competências

## Competência CT18.1

**Título da Competência**  
Decompor requisitos e estruturar o fluxo computacional de um programa introdutório

**Descrição Textual**  
Capacidade de interpretar um problema computacional, identificar seus dados e funcionalidades essenciais e estruturar uma solução algorítmica coerente com entrada, processamento e saída.

**Cobertura e rastreabilidade**

- LOs cobertos: (LO1, LO2)
- K mobilizados (Núcleo): (K01, K02, K03)

**Especificação de Conhecimentos**

- **K01:** permite compreender o problema como situação a ser transformada em solução computacional. **Justificativa de evidência:** a organização geral do sistema revela se o estudante identificou corretamente problema, dados, processamento e saídas.
- **K02:** sustenta a formulação de rotinas e sequências de passos para resolver cada funcionalidade. **Justificativa de evidência:** a estrutura das rotinas de cadastro, venda, listagem e relatório evidencia a organização algorítmica.
- **K03:** orienta o encadeamento de entrada, processamento e saída em cada parte do sistema. **Justificativa de evidência:** as telas, leituras e saídas permitem verificar se o fluxo computacional é funcional.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Analisar**, pois a competência exige decompor requisitos, distinguir dados e funcionalidades e estruturar o fluxo geral da solução antes e durante a implementação.

**Pareamento Conhecimento–Habilidade**

K01 / Analisar → decompor o problema em dados, processos e saídas computacionalmente tratáveis.  
Verbos de Bloom: decompor, distinguir, relacionar

K02 / Analisar → estruturar sequências algorítmicas coerentes para funcionalidades distintas de um programa.  
Verbos de Bloom: estruturar, modelar, esquematizar

K03 / Aplicar → executar o encadeamento de entrada, processamento e saída em rotinas verificáveis.  
Verbos de Bloom: executar, implementar, operar

**Especificação de Disposições**

- atenção à leitura dos requisitos;
- organização lógica da solução;
- compromisso com rastreabilidade entre enunciado e artefato.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT18.1 | Decompor requisitos e estruturar o fluxo computacional de um programa introdutório | atenção à leitura dos requisitos; organização lógica da solução; compromisso com rastreabilidade entre enunciado e artefato | K01 | decompor o problema em dados, processos e saídas computacionalmente tratáveis |
| CT18.1 | Decompor requisitos e estruturar o fluxo computacional de um programa introdutório | atenção à leitura dos requisitos; organização lógica da solução; compromisso com rastreabilidade entre enunciado e artefato | K02 | estruturar sequências algorítmicas coerentes para funcionalidades distintas de um programa |
| CT18.1 | Decompor requisitos e estruturar o fluxo computacional de um programa introdutório | atenção à leitura dos requisitos; organização lógica da solução; compromisso com rastreabilidade entre enunciado e artefato | K03 | executar o encadeamento de entrada, processamento e saída em rotinas verificáveis |

**Definição de Ativação**

- Restrição de ativação: obrigatória
- Modo de ativação: analítica
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a task exige que o estudante transforme um enunciado extenso em um sistema organizado por funcionalidades. A competência é ativada porque a solução só pode ser verificada quando os requisitos são decompostos e convertidos em rotinas executáveis.

## Competência CT18.2

**Título da Competência**  
Representar dados e coleções com tipos adequados e vetores

**Descrição Textual**  
Capacidade de selecionar tipos de dados e estruturas de armazenamento compatíveis com os dados de um problema, utilizando variáveis e vetores para preservar informações durante a execução.

**Cobertura e rastreabilidade**

- LOs cobertos: (LO2, LO3)
- K mobilizados (Núcleo): (K03, K04, K08)

**Especificação de Conhecimentos**

- **K03:** sustenta a circulação dos dados entre entrada, processamento e saída. **Justificativa de evidência:** as informações cadastradas e exibidas demonstram a coerência do fluxo de dados.
- **K04:** permite representar nomes, códigos, quantidades e valores por meio de variáveis e tipos adequados. **Justificativa de evidência:** a escolha e o uso dos tipos afetam diretamente a correção do armazenamento e dos cálculos.
- **K08:** permite organizar múltiplos produtos e múltiplas vendas em coleções indexadas. **Justificativa de evidência:** o uso de vetores é exigido explicitamente e pode ser observado no código-fonte.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência requer usar tipos, variáveis e vetores em um programa executável, com armazenamento e recuperação de dados ao longo da execução.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → implementar fluxo de dados entre leitura, armazenamento, processamento e exibição.  
Verbos de Bloom: implementar, executar, operar

K04 / Aplicar → manipular variáveis e tipos de dados compatíveis com cada informação do problema.  
Verbos de Bloom: manipular, usar, armazenar

K08 / Aplicar → armazenar e acessar coleções de dados por meio de vetores indexados.  
Verbos de Bloom: armazenar, manipular, usar

**Especificação de Disposições**

- precisão na escolha dos tipos de dados;
- cuidado na correspondência entre posições dos vetores;
- consistência no armazenamento e na recuperação das informações.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT18.2 | Representar dados e coleções com tipos adequados e vetores | precisão na escolha dos tipos de dados; cuidado na correspondência entre posições dos vetores; consistência no armazenamento e na recuperação das informações | K03 | implementar fluxo de dados entre leitura, armazenamento, processamento e exibição |
| CT18.2 | Representar dados e coleções com tipos adequados e vetores | precisão na escolha dos tipos de dados; cuidado na correspondência entre posições dos vetores; consistência no armazenamento e na recuperação das informações | K04 | manipular variáveis e tipos de dados compatíveis com cada informação do problema |
| CT18.2 | Representar dados e coleções com tipos adequados e vetores | precisão na escolha dos tipos de dados; cuidado na correspondência entre posições dos vetores; consistência no armazenamento e na recuperação das informações | K08 | armazenar e acessar coleções de dados por meio de vetores indexados |

**Definição de Ativação**

- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a task exige armazenar produtos, estoques, preços e vendas durante a execução. A competência é ativada porque o uso consistente de variáveis, tipos e vetores é condição central para que as funcionalidades funcionem e possam ser avaliadas.

## Competência CT18.3

**Título da Competência**  
Controlar o fluxo de execução com decisões e repetições

**Descrição Textual**  
Capacidade de construir programas estruturados que selecionam ações conforme condições e repetem rotinas de forma controlada para processar múltiplas interações, coleções de dados e cenários de execução.

**Cobertura e rastreabilidade**

- LOs cobertos: (LO4, LO5)
- K mobilizados (Núcleo): (K05, K06, K07)

**Especificação de Conhecimentos**

- **K05:** permite formular expressões de comparação, controle e cálculo associadas às decisões do programa. **Justificativa de evidência:** as condições de escolha, validação e cálculo aparecem diretamente nas expressões do código.
- **K06:** sustenta a seleção entre caminhos alternativos e o tratamento de diferentes cenários de execução. **Justificativa de evidência:** o comportamento das rotinas depende de estruturas condicionais corretas.
- **K07:** permite repetir rotinas, percorrer dados e registrar múltiplas ocorrências. **Justificativa de evidência:** o enunciado exige uso de repetição e o processamento de vários produtos e vendas.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência requer implementar estruturas condicionais e de repetição em um programa funcional, sem exigir análise formal de algoritmos.

**Pareamento Conhecimento–Habilidade**

K05 / Aplicar → usar expressões aritméticas, relacionais e lógicas para controlar ações e cálculos do programa.  
Verbos de Bloom: usar, calcular, computar

K06 / Aplicar → implementar seleção de ações conforme condições definidas durante a execução.  
Verbos de Bloom: implementar, executar, operar

K07 / Aplicar → iterar rotinas e percorrer dados com critérios de parada coerentes.  
Verbos de Bloom: iterar, executar, programar

**Especificação de Disposições**

- consistência lógica no controle de casos;
- atenção aos critérios de parada;
- cuidado com a estabilidade do fluxo do programa..

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT18.3 | Controlar o fluxo de execução com decisões e repetições | consistência lógica no controle de casos; atenção aos critérios de parada; cuidado com a estabilidade do fluxo do programa | K05 | usar expressões aritméticas, relacionais e lógicas para controlar ações e cálculos do programa |
| CT18.3 | Controlar o fluxo de execução com decisões e repetições | consistência lógica no controle de casos; atenção aos critérios de parada; cuidado com a estabilidade do fluxo do programa | K06 | implementar seleção de ações conforme condições definidas durante a execução |
| CT18.3 | Controlar o fluxo de execução com decisões e repetições | consistência lógica no controle de casos; atenção aos critérios de parada; cuidado com a estabilidade do fluxo do programa | K07 | iterar rotinas e percorrer dados com critérios de parada coerentes |

**Definição de Ativação**

- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a task exige repetição de operações, seleção de ações e tratamento de diferentes cenários durante a execução. A competência é ativada porque o controle de fluxo é parte essencial da observação do programa funcionando.

## Competência CT18.4

**Título da Competência**  
Atualizar coleções e estado do programa durante operações de cadastro e venda

**Descrição Textual**  
Capacidade de modificar dados armazenados durante a execução de um programa, mantendo coerência entre registros, coleções, cálculos intermediários e estado final observável.

**Cobertura e rastreabilidade**

- LOs cobertos: (LO3, LO5, LO6)
- K mobilizados (Núcleo): (K04, K05, K07, K08)

**Especificação de Conhecimentos**

- **K04:** permite atualizar variáveis relacionadas a quantidade, valor e estado interno. **Justificativa de evidência:** a alteração do estoque e dos registros de venda depende de atribuições corretas.
- **K05:** sustenta cálculos e comparações usados na atualização dos dados. **Justificativa de evidência:** totais, quantidades e limites dependem de expressões coerentes.
- **K07:** permite repetir operações de processamento sobre múltiplos itens. **Justificativa de evidência:** vendas com mais de um produto e listagens exigem percorrimento iterativo.
- **K08:** sustenta atualização e consulta de coleções indexadas. **Justificativa de evidência:** produtos e vendas devem permanecer armazenados e consultáveis por posição nos vetores.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Criar**, de forma controlada, pois a competência exige construir uma solução integrada em que dados armazenados, cálculos, laços e atualizações se articulam em um sistema funcional.

**Pareamento Conhecimento–Habilidade**

K04 / Aplicar → atualizar variáveis de estado conforme operações realizadas no programa.  
Verbos de Bloom: manipular, aplicar, operar

K05 / Aplicar → calcular e comparar valores necessários à atualização coerente dos dados.  
Verbos de Bloom: calcular, computar, resolver

K07 / Aplicar → percorrer múltiplos itens e registros por meio de repetição controlada.  
Verbos de Bloom: iterar, executar, usar

K08 / Criar → construir uma organização de coleções que permita cadastro, consulta e atualização consistente dos dados.  
Verbos de Bloom: construir, desenvolver, projetar

**Especificação de Disposições**

- rigor na atualização do estado interno;
- atenção à consistência entre dados relacionados;
- responsabilidade na preservação da integridade dos registros.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT18.4 | Atualizar coleções e estado do programa durante operações de cadastro e venda | rigor na atualização do estado interno; atenção à consistência entre dados relacionados; responsabilidade na preservação da integridade dos registros | K04 | atualizar variáveis de estado conforme operações realizadas no programa |
| CT18.4 | Atualizar coleções e estado do programa durante operações de cadastro e venda | rigor na atualização do estado interno; atenção à consistência entre dados relacionados; responsabilidade na preservação da integridade dos registros | K05 | calcular e comparar valores necessários à atualização coerente dos dados |
| CT18.4 | Atualizar coleções e estado do programa durante operações de cadastro e venda | rigor na atualização do estado interno; atenção à consistência entre dados relacionados; responsabilidade na preservação da integridade dos registros | K07 | percorrer múltiplos itens e registros por meio de repetição controlada |
| CT18.4 | Atualizar coleções e estado do programa durante operações de cadastro e venda | rigor na atualização do estado interno; atenção à consistência entre dados relacionados; responsabilidade na preservação da integridade dos registros | K08 | construir uma organização de coleções que permita cadastro, consulta e atualização consistente dos dados |

**Definição de Ativação**

- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a task exige que o estoque esteja sempre atualizado e que as vendas sejam registradas para consulta posterior. A competência é ativada porque a correção do sistema depende da manutenção consistente do estado ao longo da execução.

## Competência CT18.5

**Título da Competência**  
Produzir consultas e indicadores a partir de dados armazenados

**Descrição Textual**  
Capacidade de processar dados acumulados em um programa para gerar listagens, totais, médias e indicadores verificáveis, comunicando os resultados de forma clara ao usuário.

**Cobertura e rastreabilidade**

- LOs cobertos: (LO2, LO5, LO6)
- K mobilizados (Núcleo): (K03, K05, K07, K08)

**Especificação de Conhecimentos**

- **K03:** orienta a apresentação de saídas verificáveis após o processamento. **Justificativa de evidência:** listagens e relatórios demonstram a relação entre processamento interno e resultado exibido.
- **K05:** permite calcular totais, médias, comparações e indicadores derivados. **Justificativa de evidência:** os indicadores exigidos dependem de expressões aritméticas e relacionais.
- **K07:** sustenta o percorrimento de registros para acumular e comparar informações. **Justificativa de evidência:** produtos e vendas precisam ser examinados iterativamente.
- **K08:** fornece a base para consultar dados armazenados em coleções. **Justificativa de evidência:** as listagens e indicadores dependem da recuperação dos dados nos vetores.

**Alinhamento com a Taxonomia de Bloom**  
Predomina **Aplicar**, pois a competência requer utilizar laços, vetores e expressões para produzir consultas e indicadores a partir dos dados armazenados.

**Pareamento Conhecimento–Habilidade**

K03 / Aplicar → apresentar saídas coerentes com os dados processados e o estado do programa.  
Verbos de Bloom: executar, implementar, operar

K05 / Aplicar → computar indicadores derivados por meio de expressões aritméticas, relacionais e lógicas.  
Verbos de Bloom: computar, calcular, resolver

K07 / Aplicar → iterar sobre registros para acumular, comparar e sintetizar informações.  
Verbos de Bloom: iterar, manipular, usar

K08 / Aplicar → recuperar dados de vetores para gerar listagens e relatórios verificáveis.  
Verbos de Bloom: recuperar, manipular, armazenar

**Especificação de Disposições**

- clareza na comunicação dos resultados;
- rigor na síntese de dados acumulados;
- verificabilidade entre registros, cálculos e saídas.

**Tabela-Resumo**

| Código | Competência | Disposições | Conhecimento | Habilidade |
|---|---|---|---|---|
| CT18.5 | Produzir consultas e indicadores a partir de dados armazenados | clareza na comunicação dos resultados; rigor na síntese de dados acumulados; verificabilidade entre registros, cálculos e saídas | K03 | apresentar saídas coerentes com os dados processados e o estado do programa |
| CT18.5 | Produzir consultas e indicadores a partir de dados armazenados | clareza na comunicação dos resultados; rigor na síntese de dados acumulados; verificabilidade entre registros, cálculos e saídas | K05 | computar indicadores derivados por meio de expressões aritméticas, relacionais e lógicas |
| CT18.5 | Produzir consultas e indicadores a partir de dados armazenados | clareza na comunicação dos resultados; rigor na síntese de dados acumulados; verificabilidade entre registros, cálculos e saídas | K07 | iterar sobre registros para acumular, comparar e sintetizar informações |
| CT18.5 | Produzir consultas e indicadores a partir de dados armazenados | clareza na comunicação dos resultados; rigor na síntese de dados acumulados; verificabilidade entre registros, cálculos e saídas | K08 | recuperar dados de vetores para gerar listagens e relatórios verificáveis |

**Definição de Ativação**

- Restrição de ativação: obrigatória
- Modo de ativação: construtiva
- Função de ativação: núcleo
- Justificativa curta baseada na tarefa: a task exige listagem de produtos, listagem de vendas e relatório de desempenho. A competência é ativada porque os resultados finais do sistema dependem de recuperar, processar e apresentar dados acumulados de forma verificável.
