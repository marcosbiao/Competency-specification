# Desafio: Uma Loja Muito Chique

## Definição do problema

Além de um programador exímio, você também é um empreendedor visionário. Por isso, é o dono do empreendimento ___________________________________. Tal empreendimento é especializado em vendas de ______________________________________. Seu empreendimento está em ampla expansão e, por isso, você decidiu que é hora de implementar um sistema para gerenciá-lo! Seu sistema, intitulado ________________________________, é responsável por gerenciar todo o estoque de produtos de seu negócio, além de gerenciar pedidos e gerar relatórios de desempenho.

Esse sistema inovador tem os seguintes requisitos:

* Possui um menu principal com as opções para: cadastrar um produto, ver produtos cadastrados, cadastrar uma venda, listar vendas, obter relatório de desempenho. As demais telas devem ter a opção de retornar ao menu inicial.

* Ao selecionar a opção do menu principal para cadastrar um produto:
  * O sistema irá direcionar o usuário para uma sequência de passos que pergunte o nome do produto, o preço de custo por unidade, o preço de venda por unidade e a quantidade em estoque.
  * O sistema deve ter capacidade para cadastrar até 20 produtos.

* Ao selecionar a opção do menu principal para ver produtos cadastrados:
  * O sistema exibirá uma lista de produtos cadastrados, as respectivas quantidades em estoque e os respectivos preços por unidade.
  * A quantidade em estoque dos produtos deve estar sempre atualizada!!!

* Ao selecionar a opção do menu principal para cadastrar uma venda:
  * O sistema iniciará uma rotina para cadastrar um pedido, listando os produtos disponíveis e os respectivos preços.
  * Um pedido pode conter mais de um produto.
  * O usuário deve informar para cada produto, a quantidade de itens que ele deseja.
  * Ao final deve ser exibido o preço total do pedido.
  * O sistema deve ter capacidade para registrar até 30 vendas.

* Ao selecionar a opção do menu principal para ver vendas:
  * O sistema exibirá a lista de todas as vendas contendo o código de venda que pode ser numérico, a quantidade de itens e o valor de cada venda.

* Ao selecionar a opção do menu principal para obter relatório de desempenho:
  * O sistema exibirá as estatísticas do negócio contendo:
    * A arrecadação bruta da empresa, considerando o valor de todas as vendas realizadas.
    * O lucro da empresa considerando os preços de custo de cada produto.
    * O produto mais vendido, quantas unidades foram vendidas e quantas unidades restam em estoque.
    * O produto menos vendido, quantas unidades foram vendidas e quantas unidades restam em estoque.
    * O valor médio por venda realizada.

## Requisitos

Você desenvolverá um programa em linguagem C, que implemente todos os requisitos descritos. São aspectos indispensáveis ao trabalho:

* Identificar e implementar corretamente as entradas e saídas especificadas.
* Seu programa deve usar pelo menos uma estrutura de repetição.
* Seu programa deve usar pelo menos uma estrutura condicional.
* Seu programa deve usar vários vetores. Quanto mais melhor!
* Seu programa deve utilizar diferentes tipos de dados, considerando o que for mais adequado para representar cada especificação do problema.

Além do programa em C, você deve elaborar um relatório técnico descrevendo seu processo de desenvolvimento e enfatizando os resultados obtidos com o seu programa. O relatório deve seguir o formato técnico da Sociedade Brasileira de Computação. O template do relatório será disponibilizado. O relatório deve ter entre 6 e 10 páginas.

**CUIDADO COM O PLÁGIO!!! PESSOAS DIFERENTES PENSAM A SOLUÇÃO DESSE DESAFIO DE MANEIRAS DIFERENTES. QUALQUER IDENTIFICAÇÃO DE PLÁGIO, ENTRE COLEGAS E/OU PROGRAMAS NA WEB, RECEBERÁ NOTA ZERO!!!**

## Entrega do desafio

O código do problema e relatório devem ser enviados por e-mail, até a meia noite do dia 05/10.

**Assunto do e-mail:**

```text
AVALIAÇÃO II PROGRAMAÇÃO {NOME DOS ESTUDANTES}
```

**Corpo do e-mail:**

```text
Nomes dos estudantes:
Fulano1
Fulano2
Fulano3
```

Relatório em formato PDF e código do programa no formato original `.c` em anexo ao e-mail. Não será aceito código em formato PDF!!!!