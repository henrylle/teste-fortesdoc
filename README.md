***TESTE PRÁTICO – DESENVOLVIMENTO FORTESDOC***

***Objetivo:***

O objetivo deste exame é avaliar as aptidões do candidato nos itens que serão listados abaixo.

Obs: Caso a questão não fale diretamente da tecnologia utilizada é importante identificar se a mesma pode ser usada. Caso sim, faça o uso. Caso não conheça, empregue o que tiver conhecimento. O objetivo desta avaliação não é atender em 100% aos requisitos de cada questão, mas sim o emprego das tecnologias da forma correta e o máximo que puder utilizar, usando as melhores práticas conhecidas pelo candidato.

Obs2: Dê um fork no projeto vazio. Após concluir, enviar para henryllemaia@grupofortes.com.br.

***Itens avaliados e que podem ser usados:***

-   C\# 4 ou superior

-   ASP.NET MVC 4

-   Entity Framework Code First

-   Injeção de Dependência (Ninject)

-   Mock

-   Javascript

-   jQuery

-   CSS

-   Razor

-   Testes Unitários

-   Testes de Integração

-   OO

-   JSON

-   LINQ

-   Redis

-   Desenvolvimento de apps voltada para a CLOUD

    ***Cadastro de fornecedores e produtos***

    Deverá ser construído um projeto em ASP.NET MVC (&gt;=4), que deverá ser responsável pelo cadastro de fornecedores, produtos e pedido dos fornecedores. O sistema só poderá ser acessado mediante uma simples autenticação de um usuário, que deverá ter login: *admin*; senha: *admin.*

    ***Requisitos obrigatórios:***

<!-- -->

-   O projeto deverá ter no mínimo 4 entidades: Fornecedor, Produto, Compra e Usuario;

-   A entidade Produto deverá ter no mínimo 3 propriedades: Nome, Descrição e Data do Cadastro;

-   A entidade Fornecedor deverá ter no mínimo 5 propriedades: Razão Social, CNPJ e UF, Email Responsável e Nome Responsável;

-   A entidade Pedido deverá ter no mínimo 6 propriedades: valor do item, total de itens, data do pedido, código do pedido, fornecedor e produto;

> ***Requisitos importantes:***

-   Os controllers devem ter testes unitários;

-   Os objetos de negócio devem ter testes de integração usando o banco localdb;

-   Usar um container de injeção de dependência para resolver as dependências dos objetos de negócio;

> ***Requisitos desejáveis:***

-   O projeto deve estar preparado para rodar num webfarm.

-   Usar algum serviço de cache para otimizar a navegação no Grid (preferência por algum serviço de cache distribuído);

-   A atualização das informações não pode bloquear a navegação do cliente;

    ***Requisitos funcionais e não funcionais***

1.  Autenticação para usar o sistema

2.  Menu com as operações disponíveis no sistema

3.  CRUD de Produto

4.  CRUD de Fornecedor

5.  Pedidos

    1.  Cadastro de um novo pedido

    2.  Envio do pedido de compra por email para o Fornecedor

    3.  Listagem dos pedidos por Fornecedor mostrando o valor total do pedido e total geral de todos os pedidos

6.  Use o EF como ORM para acesso aos dados;

7.  A geração do banco de dados e atualização deverá utilizar migrations;
