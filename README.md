# PIT — Sistema de Cadastro

Projeto da disciplina PIT (Projeto Integrador Transdisciplinar), com
formulário de cadastro de usuário e login, em PHP + MySQL.

## Tecnologias

- PHP
- MySQL
- HTML / CSS

## Estrutura

```
PIT/
├── index.php / index.html   # formulário de cadastro
├── login.php                # tela de login
├── conf.php                 # configuração de conexão com o banco
├── css/style.css
└── database/
    ├── bdpit.sql             # script de criação do banco de dados
    └── app.mwb               # modelo do banco (MySQL Workbench)
```

> Nota: `css/style.css` está vazio no projeto original — link já existia
> assim, não é uma quebra introduzida agora.

## Como rodar

1. Suba os arquivos em um servidor com PHP + MySQL (ex: XAMPP, WAMP, Laragon)
2. Crie o banco importando `bdpit.sql`
3. Ajuste as credenciais em `conf.php`
4. Acesse `index.php` pelo navegador

## Nota

Projeto de estudo. A versão atual deste repositório agora é um fork pois foi feito com meu grupo de alunos do COTEMIG
