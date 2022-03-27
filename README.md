# solid-rest-api-example

### for study

Single Responsability Principle:

  CreateUserUseCase possui somente a responsabilidade de criação do usuário.
	Como salva, aonde salva ou formato não fazem parte de sua responsabilidade.

Liskov Substitute Principle:

  Recebendo UsersRepository e dando type com contrato(interface) de quais os métodos que existem, não importa o repositório (postgree, mysql, mongo...), se tiver os métodos pedidos, vai funcionar.

  Dependence Inversion Principle:

  Não depende diretamente da implementação do repositório ( não salva diretamente do banco ). Está dependendo de outra classe que faz a implementação.
