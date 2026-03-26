# Título da Atividade

Processamento de dados de uma pesquisa sobre preferência clubística e perfil dos entrevistados

# Contexto Instrucional

Atividade individual de programação introdutória, adequada a disciplina de Introdução à Programação em contexto de laboratório ou avaliação prática. A tarefa exige a construção de um programa capaz de ler registros sucessivos de entrevistados, acumular informações quantitativas e apresentar resultados consolidados a partir dos dados coletados.

# Objetivo da Atividade

Desenvolver uma solução que processe um conjunto indeterminado de registros, classificando entrevistados por categoria de clube, acumulando informações salariais relevantes e produzindo indicadores sintéticos coerentes com o enunciado. A atividade focaliza a organização de dados de entrada, o uso de decisões condicionais e o tratamento de contagens e médias durante o processamento.

# Descrição da Tarefa

O estudante deve implementar um programa que receba, para cada entrevistado, o código do clube de preferência, o salário e a cidade natal, conforme as codificações fornecidas no enunciado. A partir desses registros, o programa deve apurar e informar: a quantidade de torcedores de cada clube, a média salarial dos torcedores de Grêmio e de Internacional, a quantidade de pessoas nascidas em Porto Alegre que não torcem por nenhum dos dois principais clubes e o total de entrevistados processados.

O produto esperado é um programa funcional que realize a leitura dos dados, mantenha os acumuladores necessários ao longo do processamento e exiba, ao final, os resultados solicitados, acompanhados de breve justificativa coerente sobre a lógica geral adotada.

# Condições de Execução

Como o enunciado informa que a pesquisa envolve uma quantidade desconhecida de pessoas, a solução deve prever processamento repetitivo de registros até um critério de encerramento compatível com o contexto de execução. Como esse critério não foi explicitado, ele deve ser tratado de forma consistente e claramente identificável no artefato produzido.

A implementação deve respeitar integralmente as codificações informadas para clube e cidade natal, distinguindo corretamente os três grupos de preferência clubística. O cálculo das médias salariais deve considerar apenas os entrevistados pertencentes aos respectivos grupos solicitados. Caso não haja torcedores de um dos clubes para compor a média, a solução deve evitar inconsistência aritmética e explicitar a convenção adotada para essa situação.

# Evidências Esperadas

- Código-fonte completo e executável.

- Saída final contendo todos os indicadores pedidos no enunciado.

- Registros de teste ou demonstração de execução que permitam verificar contagens, médias e total de entrevistados.

# Critérios de Avaliação

- Correção da apuração do número de torcedores por clube, das médias salariais pedidas, da contagem de nascidos em Porto Alegre que não torcem por Grêmio nem Internacional e do total de entrevistados.

- Consistência no processamento de múltiplos registros, com uso adequado de acumulação e atualização dos dados ao longo da execução.

- Tratamento claro das situações especiais do problema, especialmente a finalização da entrada e a eventual inexistência de torcedores em um grupo cuja média foi solicitada.

- Clareza e verificabilidade do artefato entregue, incluindo organização da saída e justificativa breve compatível com o comportamento do programa.
