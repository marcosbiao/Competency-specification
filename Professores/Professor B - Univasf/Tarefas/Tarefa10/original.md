Uma revenda de automóveis armazena os dados relativos aos carros disponíveis para venda em um arranjo multidimensional. As dimensões desse arranjo e os índices utilizados em cada dimensão são:
- Código de identificação do carro, com índice inteiro, de 1 a 50.
- modelo do carro, com índice tipo enumeração (modA, modB, modC, modD, modE).
- Cor, índice tipo enumeração (branca, prata, vermelho, azul, verde, preto).
- Ano de fabricação, índice tipo enumeração (2009, 2010, 2011).
- Combustível, índice tipo enumeração (gasolina, álcool, flex).
O conteúdo da matriz é o preço de cada um dos automóveis identificado pelos itens que constituem as dimensões. Escreva um programa que inicie preenchendo, a partir de leituras do teclado, todos os dados dessa matriz. Em seguida, o programa deve responder a uma série de consultas, lendo os dados que identificam cada automóvel e informando o seu preço. Crie um controle para identificar quando o programa deve terminar de responder a consultas.