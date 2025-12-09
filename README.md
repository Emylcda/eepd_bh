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
Documento de Requisitos do Site EEPD-BH
1. Nome do Site
Site Institucional da Escola Estadual Presidente Dutra - Belo Horizonte

2. Descrição do Site
Site institucional da escola EEPD-BH, apresentando a história da instituição, cursos oferecidos, sistema de blog, área de contato e portais de acesso para professores e alunos.

3. Funcionalidades Principais
3.1 Página Inicial (index.php)
Seção 'Escola': apresentação da história e origem da instituição
Carrossel com 8 imagens aleatórias selecionadas automaticamente pelo sistema
Design responsivo utilizando Bootstrap
3.2 Página de Cursos
Apresentação dos seguintes cursos oferecidos:

Desenvolvimento de Sistemas
Informática
Logística
Fabricação Mecânica
Energias Renováveis
Segurança do Trabalho
Propedêutica
Eletrônica
3.3 Blog
Seção para publicação de artigos e notícias da escola

3.4 Contato
Formulário ou informações para contato com a instituição

3.5 Sistema de Login
Área de autenticação para acesso ao sistema

3.6 Cadastro
Funcionalidade de registro de novos usuários

3.7 Portal de Professores
Área restrita para acesso dos professores

3.8 Portal de Alunos
Área restrita para acesso dos alunos

4. Tecnologias Utilizadas
HTML5
Bootstrap
PHP puro
MySQL (conexão com banco de dados)
XAMPP/Apache
Visual Studio Code
Git e GitHub
React.js
Vue.js
Spring Boot
5. Rodapé (Footer)
Informações institucionais:

Nome: Escola Estadual Presidente Dutra - BH
CNPJ: 000.000/0001-0c
SRE: METROPOLITANA-A
CEP: 00000-000
Endereço: Rua xxxx Nº xxxx
Cidade: Belo Horizonte - Minas Gerais - Brasil
Créditos: 'Desenvolvido pelo Desenvolvimento de Sistemas © Todos os direitos reservados a EEPD'
6. Estilo de Design
Esquema de cores: Roxo, Lilais e Branco.
Layout: estrutura em grid responsivo com Bootstrap, navegação clara no topo
Elementos visuais: carrossel dinâmico na página inicial, cards para apresentação dos cursos
Tipografia: fontes legíveis e modernas, hierarquia clara entre títulos e textos
Componentes: botões com bordas arredondadas sutis, sombras leves para profundidade nos cards
