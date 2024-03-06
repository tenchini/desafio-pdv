# PDV: Cubos Academy - Ponto de Venda

## Descrição do Projeto

O PDV (Ponto de Venda) é um sistema de frente de caixa desenvolvido como parte do meu portfólio de projetos. Este projeto é resultado do desafio do módulo 5 do curso de desenvolvimento da Cubos Academy, onde o objetivo era criar uma API completa para um PDV, implementando funcionalidades desde o cadastro de usuários até o gerenciamento de pedidos e produtos.

## Tecnologias Utilizadas

-   **Node.js:** Plataforma de execução de JavaScript do lado do servidor.
-   **Express:** Framework web para Node.js que simplifica a criação de APIs.
-   **PostgreSQL:** Banco de dados relacional utilizado para persistência dos dados.
-   **JWT (JSON Web Token):** Mecanismo de autenticação para proteger rotas sensíveis.
-   **Git e GitHub:** Controle de versão e hospedagem do código fonte.
-   **Deploy:** A aplicação foi implantada em um servidor remoto para disponibilização online.

## Funcionalidades Implementadas

### Autenticação de Usuários

-   Cadastro de novos usuários com criptografia de senha.
-   Login autenticado, gerando um token de acesso.

### Gerenciamento de Perfil

-   Visualização e edição do perfil do usuário logado.
-   Utilização de tokens para autenticação em rotas protegidas.

### Categorias de Produtos

-   Listagem de categorias previamente cadastradas.
-   Requisitos de validação e retorno de códigos de erro adequados.

### Cadastro e Atualização de Produtos

-   Cadastro de novos produtos no sistema.
-   Atualização de informações de produtos existentes.

### Listagem e Detalhes de Produtos

-   Listagem de todos os produtos cadastrados.
-   Detalhamento de informações específicas de um produto.

### Exclusão de Produtos

-   Implementação de regra de negócio para evitar exclusão de produtos vinculados a pedidos.

### Cadastro e Atualização de Clientes

-   Cadastro e atualização de informações de clientes.
-   Validação e verificação de unicidade de e-mail e CPF.

### Listagem e Detalhes de Clientes

-   Listagem de todos os clientes cadastrados.
-   Detalhamento de informações específicas de um cliente.

### Cadastro e Listagem de Pedidos

-   Cadastro de novos pedidos, vinculando produtos existentes.
-   Listagem de todos os pedidos cadastrados.

### Validação e Boas Práticas

-   Implementação de validações para garantir dados consistentes.
-   Adoção de boas práticas de desenvolvimento.

### Upload de Imagens para Produtos

-   Aprimoramento do cadastro e atualização de produtos para permitir o upload de imagens.
-   Armazenamento das imagens em um servidor de armazenamento externo.

## Conclusão

Este projeto representou uma valiosa oportunidade para aprimorar minhas habilidades no desenvolvimento web, cobrindo desde a criação de APIs até a integração com bancos de dados relacionais.

Sinta-se à vontade para explorar o código-fonte. Em caso de dúvidas, sugestões ou oportunidades de colaboração, estou sempre disponível para feedbacks construtivos.

