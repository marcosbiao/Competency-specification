## Título da Atividade

Verificação de excesso de pescado e registro de multa

## Contexto Instrucional

Atividade de programação introdutória em linguagem C, adequada a aulas práticas iniciais sobre leitura de dados, processamento condicional e produção de saída. Pode ser realizada individualmente em laboratório ou em contexto de avaliação prática escrita/computacional, com entrega do programa e breve justificativa do comportamento adotado.

## Objetivo da Atividade

Desenvolver uma solução que leia o peso informado de peixes e determine se houve ultrapassagem do limite estabelecido. A atividade busca levar o estudante a representar corretamente os dados do problema, aplicar uma verificação condicional e registrar, de forma consistente, os resultados solicitados.

## Descrição da Tarefa

O estudante deve implementar um programa em C que leia a variável `P`, correspondente ao peso de peixes, e verifique se o valor informado ultrapassa o limite regulamentar indicado no enunciado. Quando houver excesso, o programa deve registrar o valor correspondente na variável `E` e calcular o valor da multa a ser armazenado em `M`. Quando não houver excesso, ambas as variáveis devem ser apresentadas com conteúdo zero.

Como produto final, espera-se um programa executável e uma justificativa breve, coerente com o enunciado, explicando o critério usado para distinguir a situação com excesso da situação sem excesso.

## Condições de Execução

A solução deve:
- ler um único valor de entrada associado ao peso de peixes;
- verificar corretamente a condição de ultrapassagem do limite informado no problema;
- atribuir valores coerentes às variáveis `E` e `M` em ambos os cenários previstos pelo enunciado;
- exibir explicitamente os conteúdos finais de `E` e `M`;
- adotar tipo numérico compatível com a representação de peso e valor monetário, caso se considere a possibilidade de valores não inteiros.

## Evidências Esperadas

- código-fonte em C contendo leitura, verificação condicional, atribuições e saída;
- apresentação dos valores finais de `E` e `M`;
- consistência entre o comportamento do programa e as regras do enunciado;
- justificativa breve indicando por que o caso foi tratado como excesso ou como ausência de excesso.

## Critérios de Avaliação

- correção da verificação do limite estabelecido no enunciado;
- cálculo e registro consistentes do excesso e da multa, quando aplicável;
- atribuição de zero às variáveis `E` e `M` no caso sem excesso;
- clareza e verificabilidade da saída produzida;
- coerência técnica entre código, resultado apresentado e justificativa breve.