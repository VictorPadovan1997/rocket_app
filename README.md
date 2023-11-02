# Rockets Low Costs

O projeto Rockets Low Costs tem como objetivo principal a implementação de um CRUD de usuários, proporcionando autenticação de usuário por meio de middlewares. Além disso, o sistema permite a criação de cotações, incluindo imagens de foguetes e dados gerais associados a esse CRUD. Há também a funcionalidade de um CRUD para o lançamento de foguetes, onde é possível definir a data exata de lançamento.

## Como instalar o projeto

1. Faça o download do ZIP do projeto.
2. Instale o XAMPP, PHP e Composer.
3. No terminal do projeto, execute: `composer install`.
4. No terminal do projeto, inicie o servidor com o comando: `php artisan serve`.

5. Após a instalação do XAMPP, inicie o MySQL.
6. No PHPMyAdmin, crie um banco de dados chamado `rocket_database`.
7. Na raiz do projeto, execute: `php artisan migrate` para criar as tabelas no banco de dados.

### Versão do PHP utilizada: PHP 8.2.11

### Tecnologias Utilizadas

- PHP 8
- Laravel 10
- Middleware
- Autenticação de Usuário (Breeze)
- Bootstrap v5.3
- HTML
- Toastr (notificações e alertas)
- InputMask para máscara de dinheiro

