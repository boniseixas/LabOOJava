# Lab de Orientação a Objetos com Java

## Projeto
Uma loja vende livros e cadernos. Livro tem nome e gênero. Já carderno tem quantidade de materias. Ambos tem preço e uma quantidade que pode ser comprada. Os pedidos podem ou não ter um cupom de desconto aplicado ao valor total. Este cupom tem código e porcentagem de desconto. Os pedidos são de um cliente, qual tem um nome e cpf. Os pedido podem ser só de livros, de cadernos ou ambos. Por fim, o valor do frete varia de acordo com a quantide de cada item, seu preço e um fator a depender de seu tipo.
Os tipos para livro são: DRAMA, SUSPENSE e ROMANCE com os fatores 0.15, 0.10 e 0.05 respectivamente. Tal fator é multiplicativo, ao total calculado: preco * quantidade.
Os tipos para caderno são: M2, M5 e M10 com os fatores 2, 5 e 10 respectivamente.Tal fator é aditivo, ao total calculado: preco * quantidade.

## Modelando
1. Identificar as entidades
    - Cliente, Livro, Caderno, Produto, Genero, Materias, Pedido, Cupom
    
    1.1. Identificar as relações entre as entidades
    
    ![relacao](diagramauml\laboojava-relacoes-entre-entidades.png)

    1.2. Identificar os atributos das entidades

    ![atributos](diagramauml\laboojava-atributos-das-entidades.png)

2. Identificar as classes que manipulam as entidades

    ![classes](diagramauml\classes-manipulam-entidades.png)

3. Identificar classes utilitárias e de negocios

    ![classesutilitarias](diagramauml\classes-utilitarias.png)

    ![classesnegocios](diagramauml\classes-negocio.png)

4. Identificar pacotes

    ![pacotes](diagramauml\pacotes.png)