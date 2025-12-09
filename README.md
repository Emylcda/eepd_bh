# eepd_bh
# Projeto EEPD-BH – Trabalho de Recomposição

Site institucional da Escola Estadual Presidente Dutra - BH.

## Como usar
1. Instale o XAMPP (Apache + MySQL).
2. Copie a pasta `EEPD-BH` para `htdocs` (ou configure seu VirtualHost).
3. Crie um banco de dados MySQL chamado `eepd_bh` (ou ajuste em `config/conexao.php`).
4. Importar as tabelas se necessário (não foram criadas por script; os formulários armazenam em arrays/placeholder).
5. Abrir no navegador: `http://localhost/EEPD-BH/index.php`

## Tecnologias
- HTML5
- Bootstrap (CDN)
- PHP (procedural)
- MySQLi (arquivo de conexão incluso)
- CSS (assets/css/style.css)

## Estrutura de pastas
```


EEPD-BH/
└── assets/
    ├── css/style.css
    ├── js/scripts.js
    └── img/ 
├── config/
├── blog.php
├── conexao.php
├── contato.php
├── cursos.php
├── footer.php
├── header.php
├── index.php
├── login.php
├── logout.php
├── mensagem.php
├── processa_cadastro.php
├── processa_login.php
├── processa_mensagem.php
└── professores.php
```
