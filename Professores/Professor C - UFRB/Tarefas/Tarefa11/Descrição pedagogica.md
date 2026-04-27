## Título da Atividade

Determinação do maior e do menor valor em sequência numérica com parada por sentinela

## Contexto Instrucional

Atividade de programação introdutória, adequada a aulas práticas em laboratório ou a avaliação individual escrita/computacional. A tarefa produz como evidência principal um programa executável, acompanhado de saída verificável e justificativa breve sobre o comportamento adotado.

## Objetivo da Atividade

Desenvolver uma solução que processe uma sequência de números inteiros informados pelo usuário até a ocorrência de um valor de parada. A atividade busca verificar se o estudante consegue controlar repetição, comparação entre valores e produção de resultados finais coerentes com o enunciado.

## Descrição da Tarefa

O estudante deve implementar um programa que leia números inteiros, um por vez, interrompendo a entrada quando o valor informado for 0. Ao término da leitura, o programa deve apresentar o maior e o menor número efetivamente considerados no processamento. Como produto final, espera-se o código-fonte da solução, a saída correspondente e uma justificativa breve, coerente com o critério usado para encerrar a leitura e para identificar os valores extremos.

## Condições de Execução

A solução deve realizar leituras sucessivas até que o valor 0 seja informado, sem considerar esse valor como parte do conjunto a ser analisado. O processamento deve manter comparação consistente entre os números válidos informados, de modo a permitir a determinação correta do maior e do menor valor ao final. Como o enunciado não explicita o que fazer quando o primeiro valor digitado já é 0, ou quando nenhum número válido é fornecido antes da parada, esse caso deve ser tratado de forma explícita na solução, conforme orientação docente previamente definida. A implementação deve ser compatível com dados inteiros, preservando o comportamento esperado para diferentes magnitudes e sinais.

## Evidências Esperadas

1. Código-fonte contendo leitura repetida, critério de parada e comparação entre valores.
2. Saída final apresentando o maior e o menor número obtidos ao término da execução.
3. Comportamento verificável em pelo menos um cenário de teste com múltiplas entradas válidas.

## Critérios de Avaliação

1. Correção do controle de repetição com encerramento por sentinela.
2. Identificação correta do maior e do menor valor entre os números válidos informados.
3. Consistência no tratamento do caso de ausência de números válidos, quando aplicável.
4. Clareza e verificabilidade da saída produzida.
5. Coerência técnica entre implementação e resultado apresentado.