# Blog em Ruby on Rails

Este é um projeto desenvolvido como parte do processo seletivo para Estágio em Desenvolvimento Backend. O objetivo deste projeto é criar uma aplicação web de blog utilizando Ruby on Rails.

## Requisitos do Projeto

O blog deve ser desenvolvido utilizando:

- **Ruby on Rails**: Framework web utilizado para o desenvolvimento do backend da aplicação.
- **HTML + CSS + JS + Bootstrap**: Para a construção do frontend, opcionalmente utilizando o Bootstrap para estilização.
- **Banco de dados relacional**: Como PostgreSQL, para armazenamento dos dados.

### Funcionalidades

O blog deve apresentar as seguintes funcionalidades:

#### Área Deslogada:

- Visualização de posts publicados por todos os usuários, ordenados do mais novo para o mais antigo.
- Paginação dos posts, com até 3 posts por página.
- Comentários anônimos.
- Cadastro de novos usuários.
- Login de usuários cadastrados.
- Recuperação de senha.

#### Área Logada:

- Redação e publicação de posts.
- Edição e exclusão de posts pelo próprio usuário.
- Comentários identificados através do login.
- Edição do perfil de usuário.
- Alteração de senha.

## Deploy

O projeto está disponível em [https://blog-ruby-0ehn.onrender.com/](https://blog-ruby-0ehn.onrender.com/).

## Instalação

1. Clone este repositório para sua máquina local:

```
git clone https://github.com/seu-usuario/blog-rails.git
```

2. Acesse o diretório do projeto:

```
cd blog-rails
```

3. Instale as dependências do projeto:

```
bundle install
```

4. Crie o banco de dados e execute as migrações:

```
rails db:create
rails db:migrate
```

5. Inicie o servidor Rails:

```
rails server
```

6. Acesse a aplicação em seu navegador em [http://localhost:3000](http://localhost:3000).

## Contribuição

Este projeto é aberto para contribuições. Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).
