# PIT — Sistema de Cadastro

Projeto da disciplina PIT (Projeto Integrador Transdisciplinar), com
formulário de cadastro de usuário e login, em PHP + MySQL.

## Tecnologias

- PHP
- MySQL
- HTML / CSS

## Estrutura

- `index.php` / `index.html` — formulário de cadastro
- `login.php` — tela de login
- `conf.php` — configuração de conexão com o banco
- `bdpit.sql` — script de criação do banco de dados
- `app.mwb` — modelo do banco (MySQL Workbench)

## Como rodar

1. Suba os arquivos em um servidor com PHP + MySQL (ex: XAMPP, WAMP, Laragon)
2. Crie o banco importando `bdpit.sql`
3. Ajuste as credenciais em `conf.php`
4. Acesse `index.php` pelo navegador

## Nota

Projeto de estudo. A versão anterior deste repositório tinha uma pasta
duplicada com uma iteração mais antiga do mesmo projeto — mantida aqui
apenas a versão final e mais completa.
