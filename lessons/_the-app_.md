# _Scratch App_ 📝

Antes de começarmos a escrever testes e2e, deixa eu te apresentar a aplicação em teste.

A aplicação se chama [**Scratch**](https://notes-serverless-app.com) e foi desenvolvida com base no [guia](https://serverless-stack.com/#guide) para quem está começando a trabalhar com [serverless stack](https://serverless-stack.com).

## Funcionalidades da aplicação

A principal funcionalidade da aplicação **Scratch** é um CRUD (_**C**reate, **R**ead, **U**pdate, **D**elete_) de anotações. Ou seja, o(a) usuário(a) pode criar, ler, editar e deletar anotações.

Para poder criar anotações, o(a) usuário(a) precisa estar autenticado. Ou seja, a aplicação conta com a funcionalidade de _Login_.

Para poder se autenticar, o(a) usuário(a) precisa estar registrado(a) no sistema. Ou seja, a aplicação também conta com a funcionalidade de _Sign up_. Além disso, tal funcionalidade exige a leitura de um email de confirmação para que o registro do(a) novo(a) usuário(a) seja completo (um desafio que irei te ensinar a resolver).

Visto que o(a) usuário(a) pode estar autenticado(a), a aplicação também conta com a funcionalidade de _Logout_.

Por fim, quando autenticado(a), o(a) usuário(a) deve ser capaz de preencher e submeter com sucesso um formulário de cartão de crédito, simulando uma compra, trazendo uma situação do mundo real.

## Teu desafio

Durante o curso de **Testes _end-to-end_ com Cypress** da [**Escola TAT**](https://udemy.com/user/walmyr), te desafio a testar todas as funcionalidades da aplicação **Scratch**, além de configurar um _workflow_ de integração contínua com múltiplas fases, paralelização e integração com o [serviço do Cypress na nuvem](https://cloud.cypress.io/).

## Atenção❗

A aplicação **_Scratch_** não é 100% _production ready_, portanto, **não** utilize-a mais do que o necessário para a realização do curso, muito menos execute testes de carga, estresse, desempenho, entre outros sobre a mesma.

___

Espero que esteja tão ansioso(a) para começar como estou para te guiar ao longo do caminho! 🧑‍🏫

Vá para a [aula 0](./0.md) para fazer o _setup_ do projeto de testes e2e.
