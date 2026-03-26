## Título da Atividade

Rastreamento de uma cobra em matriz bidimensional

## Contexto Instrucional

Atividade de programação introdutória, preferencialmente individual, voltada à leitura e ao processamento de matrizes bidimensionais em um ambiente de laboratório ou de avaliação prática. A evidência principal esperada é a implementação de um algoritmo capaz de percorrer uma estrutura matricial, identificar uma trajetória conectada e registrar uma saída ordenada e verificável.

## Objetivo da Atividade

Desenvolver a capacidade de analisar uma matriz bidimensional que representa um percurso contínuo e produzir uma sequência ordenada de coordenadas correspondente a esse percurso. A tarefa enfatiza a correta interpretação da estrutura de dados, da conectividade entre células e do formato exigido para a saída.

## Descrição da Tarefa

O estudante deve elaborar um algoritmo que receba uma matriz representando um grid com células vazias e células ocupadas por uma cobra. A tarefa consiste em localizar a cabeça da cobra, identificar as demais células conectadas que compõem seu corpo e retornar a sequência completa de coordenadas no formato `[coluna, linha]`, respeitando a ordem do percurso desde a cabeça até a extremidade final da cauda.

O produto esperado é uma solução executável na linguagem adotada pela disciplina, ou uma descrição algorítmica formal equivalente, acompanhada da saída final correspondente e de uma justificativa breve que explique o critério usado para manter a ordem correta do percurso.

## Condições de Execução

- A solução deve considerar matrizes de dimensões arbitrárias `M x N`.
- A saída deve seguir rigorosamente a convenção de coordenadas `[coluna, linha]`, mesmo que a linguagem utilizada acesse a matriz por índices em outra ordem.
- Devem ser consideradas apenas células pertencentes à cobra e conectadas ao seu percurso contínuo.
- As células vazias, representadas por espaço em branco, não devem compor a sequência retornada.
- A conectividade deve ser tratada de forma consistente com a organização do grid e com os símbolos informados para corpo horizontal e vertical, sem inferir ramificações, fragmentações ou múltiplos caminhos.
- Como há inconsistência entre a descrição textual e os exemplos quanto ao símbolo do segmento vertical, a implementação deve interpretar corretamente o caractere vertical conforme a convenção efetivamente presente na entrada utilizada.
- A resposta final deve apresentar a sequência completa de coordenadas e uma justificativa breve, coerente com o percurso identificado.

## Evidências Esperadas

- Código-fonte ou algoritmo formal que percorra a matriz e identifique a cobra corretamente.
- Saída contendo a sequência ordenada de pares `[coluna, linha]`, da cabeça até a cauda.
- Indicação verificável de que cada célula da cobra foi registrada uma única vez e na ordem correta.
- Justificativa breve explicando como a trajetória foi determinada.

## Critérios de Avaliação

- Correção na identificação da cabeça e de todas as células que compõem a cobra.
- Correção da ordem do percurso, iniciando na cabeça e seguindo até a extremidade final do corpo.
- Consistência no uso do formato de saída `[coluna, linha]` e no tratamento de matrizes de tamanho arbitrário.
- Completude da solução, sem omissões, repetições indevidas ou inclusão de células vazias.
- Clareza e verificabilidade do artefato entregue, incluindo justificativa breve e coerente.
