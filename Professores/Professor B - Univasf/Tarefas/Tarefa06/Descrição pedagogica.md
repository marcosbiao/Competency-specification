## Título da Atividade

Deslocamento sequencial de elementos em arranjo unidimensional

## Contexto Instrucional

Atividade prática de programação em disciplina introdutória, voltada à manipulação de arranjos unidimensionais e ao controle correto de atualizações em estruturas indexadas. Pode ser realizada individualmente em laboratório ou em contexto de avaliação prática, com entrega de código e registro verificável dos resultados produzidos.

## Objetivo da Atividade

Implementar uma solução que realize transformações sucessivas em um arranjo unidimensional, respeitando a ordem dos elementos e as regras de descarte e preenchimento nas extremidades. A atividade busca evidenciar a compreensão do estudante sobre acesso posicional, deslocamento de valores e consistência do estado do arranjo ao longo da execução.

## Descrição da Tarefa

Desenvolver um programa que opere sobre um arranjo unidimensional de N posições em duas etapas sucessivas. Na primeira, todos os elementos devem ser deslocados para a posição seguinte, com perda do valor originalmente contido na última posição e atribuição de zero à primeira posição. Na segunda, deve-se aplicar o deslocamento para a posição anterior sobre o arranjo resultante da etapa anterior, com perda do valor contido na primeira posição desse novo estado e atribuição de zero à última posição. O produto esperado é um programa funcional que permita verificar o estado do arranjo antes e após cada transformação.

## Condições de Execução

Como o enunciado não explicita o formato de entrada, admite-se que o arranjo e o valor de N sejam fornecidos por leitura, inicialização no código ou outro mecanismo definido pelo contexto da disciplina, desde que fiquem explícitos e verificáveis. Considera-se que o arranjo armazena valores numéricos, pois a tarefa exige a atribuição do valor zero. A solução deve tratar cada deslocamento como uma operação completa e coerente, sem comprometer valores ainda necessários durante a atualização do arranjo. Recomenda-se considerar explicitamente casos de borda, como arranjos com apenas uma posição.

## Evidências Esperadas

1. Código fonte que implemente as duas etapas de deslocamento solicitadas.  
2. Registro do conteúdo inicial do arranjo.  
3. Registro do arranjo após o deslocamento para a posição seguinte.  
4. Registro do arranjo após o deslocamento para a posição anterior.  


## Critérios de Avaliação

1. Correção do primeiro deslocamento, com perda do último valor e atribuição de zero à primeira posição.  
2. Correção do segundo deslocamento, aplicado sobre o resultado da etapa anterior, com perda do primeiro valor e atribuição de zero à última posição.  
3. Consistência da manipulação do arranjo, especialmente quanto à ordem dos elementos e ao tratamento das extremidades.  
4. Clareza e verificabilidade dos registros apresentados em cada etapa da execução.  
5. Coerência entre o comportamento observado no programa e a justificativa breve fornecida.