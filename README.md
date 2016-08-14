# sebo-virtual-microservices

###sv-cliente-crud-service
https://github.com/renatorp/sv-cliente-crud-service

###sv-item-emprestimo-crud-service
https://github.com/renatorp/sv-item-emprestimo-crud-service

###sv-emprestimo-service
https://github.com/renatorp/sv-emprestimo-service

###sv-rede-social-service
https://github.com/renatorp/sv-rede-social-service

## Diagrama
![Diagrama de Componentes](https://github.com/renatorp/sebo-virtual-microservices/blob/master/sebo-online-microservices.png)

## Problema

 Considere um SEBO virtual, i.e., um local onde pessoas podem
compartilhar livros e revistas para empréstimo. Uma pessoa pode indicar que
tem livros disponíveis para empréstimo, solicitar empréstimos de outras
pessoas ou confirmar o empréstimo de um livro de sua propriedade. As
pessoas também poderão estabelecer vínculos com outras pessoas da rede,
similar a uma rede social e estabelecer grupos de amigos que compartilhem
interesses comuns como livros de ficção científica ou quadrinhos da Marvel.
A interface de consulta de livros deve ser bem flexível, como por exemplo
suporte de pesquisas por título, autor, editora, entre outros atributos de um
livro.
Os requisitos primários da sua aplicação estão abaixo.
- Inserir um novo cliente
- Alterar os dados de um novo cliente
- Remover um novo cliente
- Pesquisar clientes já existentes
- Inserir uma novo revista/livro para empréstimo
- Alterar os dados de um revista/livro
- Remover uma revista/livro
- Pesquisar revista/livros
- Adicionar um novo amigo
- Remover um amigo
- Confirmar um empréstimo
- Finalizar um empréstimo

Você deve projetar esta aplicação como um conjunto de micro-serviços.
Cada micro-serviço deve ter um tema específico, ser organizado em um
projeto independente no Eclipse e poder ser disparado ou parado de forma
independente. É esperado que cada micro-serviço forneça uma API REST
para consumo
