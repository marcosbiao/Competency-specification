## **Título da Atividade**
Percurso recursivo de cobra em matriz bidimensional

## **Contexto Instrucional**
Atividade de programação introdutória, adequada a contexto de laboratório ou avaliação prática individual, com produção de algoritmo e código executável. A evidência principal esperada é uma solução recursiva capaz de percorrer uma matriz bidimensional e registrar, em ordem, as coordenadas das células que compõem a cobra.

## **Objetivo da Atividade**
Desenvolver uma solução recursiva para percorrer uma estrutura matricial, identificar uma trajetória conectada e produzir uma representação ordenada de suas posições. A atividade busca verificar a capacidade de modelar o problema, respeitar restrições estruturais do enunciado e empregar recursão com correção e término.

## **Descrição da Tarefa**
O estudante deve elaborar um algoritmo recursivo que receba uma matriz representando um grid com uma cobra formada por caracteres específicos, localize a cabeça e percorra o corpo até a extremidade final, produzindo como saída uma sequência ordenada de coordenadas no formato `[coluna, linha]`. A ordem da sequência deve começar na cabeça e seguir continuamente o trajeto da cobra, preservando a conectividade indicada pela matriz. Espera-se a entrega da solução implementada e de uma justificativa breve que explicite a lógica geral do percurso recursivo e a forma de construção da saída.

## **Condições de Execução**
A solução deve obrigatoriamente utilizar recursão como estratégia principal de percurso. O algoritmo deve funcionar para matrizes de dimensões arbitrárias `MxN`, considerar células vazias que não pertencem à cobra e preservar a ordem correta das posições desde a cabeça até a extremidade final. Como o enunciado garante que a cobra está corretamente conectada e sem ramificações, a solução deve explorar essa propriedade sem introduzir tratamentos para casos inválidos não solicitados. Como a convenção de indexação das coordenadas não foi explicitada, deve ser adotado um padrão consistente ao longo de toda a solução e da saída.

## **Evidências Esperadas**
1. Código-fonte da solução com uso efetivo de recursão.
2. Saída contendo a sequência de coordenadas no formato solicitado, em ordem correta.
3. Indicação verificável de que a cabeça foi identificada e de que o percurso alcança toda a cobra sem perda de posições.
4. Registros de teste com matrizes de tamanhos distintos ou configurações equivalentes que demonstrem o funcionamento da solução.

## **Critérios de Avaliação**
1. Correção do percurso da cobra desde a cabeça até a extremidade final, com ordenação adequada das coordenadas.
2. Uso apropriado de recursão, com definição consistente do avanço no percurso e garantia de término.
3. Completude da solução quanto ao tratamento da matriz, da identificação da cabeça e da geração da saída no formato exigido.
4. Clareza e verificabilidade do artefato entregue, incluindo legibilidade da saída.
5. Consistência da solução para diferentes dimensões de matriz e diferentes disposições válidas da cobra.