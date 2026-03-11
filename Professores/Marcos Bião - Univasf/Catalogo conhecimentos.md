# Catálogo de Conhecimentos da Disciplina — Introdução à Programação (Univasf)

**Objetivo:** estabelecer um conjunto fixo e reutilizável de conhecimentos (K) para a disciplina **Introdução à Programação**, a ser usado como **limite superior** (escopo) na geração de relatórios CSP de tarefas da disciplina.  
**Regra de uso no CSP:** em cada tarefa, o relatório CSP **seleciona um subconjunto** deste catálogo. Extensões só são aceitas se a ementa/catálogo forem revisados.


## Fontes e âncoras

- **Ementa da disciplina (Univasf):** Arquitetura de von Neumann; Introdução à linguagem C11; O paradigma imperativo; Conceito de variáveis e constantes; Tipos de dados simples: inteiro, caracter, e ponto flutuante; Programação estruturada; Estrutura sequencial; Expressões aritméticas; Expressões lógicas; Estrutura de seleção; Estrutura de repetição; Tipos dedados estruturados: arranjos, cadeia de caracteres,  matrizes, enumerações, e uniões; Subprogramas: procedimentos e funções; Subprogramas recursivos. Arquivos e diretórios.

- **CS2023 (ACM/IEEE):** Knowledge Unit **SDF-Fundamentals** (tópicos 1–8) e **SDF-Data-Structures** (tópico 4 para strings), usados aqui como **âncora externa**.

### Convenção de códigos CS2023
- **SDF-n** = *SDF-Fundamentals*, tópico **n**  
- **SDFDS-n** = *SDF-Data-Structures*, tópico **n**  




## Tabela-resumo do catálogo (K)

| Código | Conhecimento | Rastreio na ementa (tópico) | Código CS2023 |
|---|---|---|---|
| K01 | Modelo de execução e noção de estado (paradigma imperativo) | Arquitetura de von Neumann; O paradigma imperativo; Programação estruturada; Estrutura sequencial | SDF-2 |
| K02 | Variáveis, constantes e tipos primitivos | Conceito de variáveis e constantes; Tipos de dados simples: inteiro, caracter, ponto flutuante | SDF-1 |
| K03 | Expressões aritméticas e avaliação | Expressões aritméticas | SDF-1 |
| K04 | Expressões lógicas e condições | Expressões lógicas | SDF-3 |
| K05 | Estrutura sequencial e E/S básica | Estrutura sequencial | SDF-3 |
| K06 | Estruturas de seleção | Estrutura de seleção | SDF-3 |
| K07 | Estruturas de repetição | Estrutura de repetição | SDF-3 |
| K08 | Vetores e matrizes em C | Tipos de dados estruturados: arranjos, matrizes | SDF-6 |
| K09 | Strings em C | Tipos de dados estruturados: cadeia de caracteres | SDFDS-4 |
| K10 | Enumerações e uniões em C | Tipos de dados estruturados: enumerações, uniões | Sem âncora específica explícita |
| K11 | Subprogramas: procedimentos e funções | Subprogramas: procedimentos e funções | SDF-4 |
| K12 | Recursão em subprogramas | Subprogramas recursivos | SDF-8 |
| K13 | Arquivos e diretórios (persistência e organização básica) | Arquivos e diretórios | SDF-5 |





## Definições detalhadas

### K01 — Modelo de execução e noção de estado (paradigma imperativo)
- **Descrição:** compreensão operacional de que um programa imperativo evolui por mudanças de estado durante a execução.
- **Escopo mínimo:** estado/atribuição como transição; sequência e fluxo de controle em nível introdutório.
- **Rastreio na ementa:** Arquitetura de von Neumann; O paradigma imperativo; Programação estruturada; Estrutura sequencial.
- **Código CS2023 curto:** SDF-2.
- **Evidências típicas (em tarefas):** rastrear execução, explicar atualizações de variáveis, justificar ordem de operações/efeitos.
- **Observações de reuso:** base transversal para praticamente qualquer tarefa de programação imperativa na disciplina.




### K02 — Variáveis, constantes e tipos primitivos
- **Descrição:** representação de dados simples e uso de identificadores para armazenar/manipular valores.
- **Escopo mínimo:** inteiros, caracteres, ponto flutuante; constantes; atribuição; coerência de tipos em operações básicas.
- **Rastreio na ementa:** Conceito de variáveis e constantes; Tipos de dados simples: inteiro, caracter, ponto flutuante.
- **Código CS2023 curto:** SDF-1.
- **Evidências típicas:** declarar/atribuir corretamente; escolher tipo coerente; evitar conversões problemáticas em cálculos básicos.
- **Observações de reuso:** aplica-se a tarefas numéricas, condicionais, repetição e manipulação de estruturas.



### K03 — Expressões aritméticas e avaliação
- **Descrição:** construção e avaliação de expressões aritméticas com operadores e precedência.
- **Escopo mínimo:** operadores aritméticos; precedência/associatividade; composição de expressões; atualização por atribuição.
- **Rastreio na ementa:** Expressões aritméticas.
- **Código CS2023 curto:** SDF-1.
- **Evidências típicas:** cálculos corretos; uso explícito de parênteses quando necessário; resultados coerentes.
- **Observações de reuso:** essencial para problemas de cálculo, simulações simples e processamento de dados.



### K04 — Expressões lógicas e condições
- **Descrição:** construção de condições booleanas para tomada de decisão e controle de fluxo.
- **Escopo mínimo:** operadores relacionais e lógicos; composição de condições; interpretação de verdade/falsidade.
- **Rastreio na ementa:** Expressões lógicas.
- **Código CS2023 curto:** SDF-3.
- **Evidências típicas:** condições corretas em if/while; tratamento de casos; coerência entre regra do problema e condição.
- **Observações de reuso:** aparece em seleção, repetição, validação de entrada e checagens de invariantes simples.



### K05 — Estrutura sequencial e E/S básica
- **Descrição:** organização de programas como sequência de comandos com interação básica.
- **Escopo mínimo:** comandos sequenciais; atribuição; leitura/saída básica (no nível adotado pela disciplina).
- **Rastreio na ementa:** Estrutura sequencial.
- **Código CS2023 curto:** SDF-3.
- **Evidências típicas:** fluxo entrada→processamento→saída; saídas verificáveis; consistência do formato de saída.
- **Observações de reuso:** núcleo para qualquer tarefa com transformação de entrada em resultado.



### K06 — Estruturas de seleção
- **Descrição:** escolha de caminhos alternativos de execução com base em condições.
- **Escopo mínimo:** if/else (e, se aplicável, switch); aninhamento/encadeamento; cobertura de casos.
- **Rastreio na ementa:** Estrutura de seleção.
- **Código CS2023 curto:** SDF-3.
- **Evidências típicas:** implementação correta de regras; ausência de lacunas; explicação do porquê de cada ramo.
- **Observações de reuso:** frequente em tarefas de decisão, classificação, regras de negócio simples.



### K07 — Estruturas de repetição
- **Descrição:** execução repetida de blocos de comandos controlada por condição ou contador.
- **Escopo mínimo:** while/for/do-while; condições de parada; laços por contagem e por condição.
- **Rastreio na ementa:** Estrutura de repetição.
- **Código CS2023 curto:** SDF-3.
- **Evidências típicas:** laços corretos; parada garantida; processamento acumulativo/iterativo coerente.
- **Observações de reuso:** central para varreduras de vetores, repetição de leituras e simulações.

### K08 — Vetores e matrizes em C
- **Descrição:** representação e manipulação de coleções homogêneas indexadas em C, em uma ou mais dimensões.
- **Escopo mínimo:** vetores/arranjos unidimensionais; matrizes bidimensionais; acesso por índice; percorrimento; leitura, atualização e processamento de elementos.
- **Rastreio na ementa:** Tipos de dados estruturados: arranjos, matrizes.
- **Código CS2023 curto:** SDF-6.
- **Evidências típicas:** indexação correta; percorrimento com laços; preenchimento e consulta de posições; processamento de listas numéricas, tabelas e grades.
- **Observações de reuso:** habilita tarefas com coleções homogêneas, tabelas, tabuleiros, séries de valores e problemas que exigem acesso posicional.



### K09 — Strings em C
- **Descrição:** representação e manipulação de cadeias de caracteres em C como sequências terminadas por caractere nulo.
- **Escopo mínimo:** declaração de strings; leitura e escrita; percorrimento caractere a caractere; comparação, cópia e manipulação textual básica.
- **Rastreio na ementa:** Tipos de dados estruturados: cadeia de caracteres.
- **Código CS2023 curto:** SDFDS-4.
- **Evidências típicas:** leitura correta de texto; comparação de strings; processamento caractere a caractere; operações simples de transformação e validação textual.
- **Observações de reuso:** habilita tarefas de processamento textual, validação de entradas textuais, comparação de palavras e manipulação básica de mensagens.



### K10 — Enumerações e uniões em C
- **Descrição:** representação de categorias simbólicas e de variações de representação de dados em C por meio de `enum` e `union`.
- **Escopo mínimo:** declaração e uso de tipos enumerados; associação entre nomes simbólicos e valores; declaração de `union`; compartilhamento de memória entre campos; uso introdutório e disciplinado dessas construções no nível da disciplina.
- **Rastreio na ementa:** Tipos de dados estruturados: enumerações, uniões.
- **Código CS2023 curto:** sem âncora específica explícita.
- **Evidências típicas:** definir estados/categorias com `enum`; usar constantes simbólicas em decisões; declarar e acessar `union` de modo coerente com o problema; justificar a escolha dessas estruturas.
- **Observações de reuso:** útil em tarefas que exigem modelagem de estados, categorias nomeadas, codificação mais legível de opções e introdução a diferentes formas de representar um mesmo dado.



### K11 — Subprogramas: procedimentos e funções
- **Descrição:** decomposição de problemas em subprogramas coesos com parâmetros/retorno.
- **Escopo mínimo:** definição/invocação; passagem de parâmetros; retorno; noção de escopo; organização modular do programa.
- **Rastreio na ementa:** Subprogramas: procedimentos e funções.
- **Código CS2023 curto:** SDF-4.
- **Evidências típicas:** funções com responsabilidade clara; reuso; chamadas corretas; coerência entre dados de entrada/saída.
- **Observações de reuso:** favorece reuso entre tarefas e facilita avaliação por unidades de comportamento.



### K12 — Recursão em subprogramas
- **Descrição:** definição e uso de subprogramas recursivos como estratégia de resolução.
- **Escopo mínimo:** caso base e caso recursivo; progresso para término; rastreamento conceitual de chamadas.
- **Rastreio na ementa:** Subprogramas recursivos.
- **Código CS2023 curto:** SDF-8.
- **Evidências típicas:** funções recursivas corretas; término garantido; explicação do fluxo de chamadas e do caso base.
- **Observações de reuso:** usar apenas quando a tarefa realmente exigir ou permitir; pode ser um eixo de atividades específicas da disciplina.



### K13 — Arquivos e diretórios (persistência e organização básica)
- **Descrição:** leitura e escrita de dados em arquivos e noções mínimas de organização por diretórios, no nível da disciplina.
- **Escopo mínimo:** abrir, ler, escrever e fechar arquivos; persistência simples entre execuções; caminhos e diretórios quando necessário.
- **Rastreio na ementa:** Arquivos e diretórios.
- **Código CS2023 curto:** SDF-5.
- **Evidências típicas:** persistir dados; ler entradas de arquivo; produzir saídas em arquivo; explicar a persistência.
- **Observações de reuso:** recomendado para tarefas de processamento de dados e miniaplicações com persistência.

## Itens explicitamente fora do escopo
Os tópicos abaixo aparecem no CS2023, mas **não estão explicitados na ementa** da disciplina:
- **SDF-9 (erros de execução)**
- **SDF-10 (teste e depuração)**
- **SDF-11 (documentação/comentários)**
- **SDF-12 (mentalidade de segurança)**  

Caso surjam em alguma tarefa, elas devem ser tratadas como **EXT (extensão)**.



## Política de manutenção
- Alterações neste catálogo devem ocorrer **apenas** quando a ementa da disciplina mudar (ou quando a coordenação decidir incorporar extensões).
- Cada tarefa deve declarar explicitamente quais **K** foram mobilizados (subconjunto), para garantir rastreabilidade e reuso.


