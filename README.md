# Biblio 1.4 — versão com todos os arquivos na mesma pasta

## Como executar
1. Extraia o ZIP. Todos os arquivos do sistema ficam juntos na mesma pasta; não mova nem renomeie arquivos individualmente.
2. Abra `index.html` no Chrome ou Edge atualizado.
3. É necessária conexão com a internet para carregar Bootstrap 5 e SQL.js via CDN.

## Contas de demonstração
- Administrador: `admin@biblio.local` / `Biblio@123`
- Bibliotecário: `biblioteca@biblio.local` / `Biblioteca@123`
- Leitor: `leitor@biblio.local` / `Leitor@123`

## Arquivos na raiz
- `index.html`: página principal.
- `style.css`: estilos.
- `app.js`: funcionalidades, regras e banco SQLite via SQL.js.
- `logo.svg`: logotipo.
- `avatar-default.svg`: foto padrão de usuário.
- `book-default.svg`: capa padrão de livro.
- `README.md`: instruções.

## Recursos
Painel responsivo, tema claro/escuro, catálogo, upload de capas, gestão de usuários, editoras, empréstimos, devoluções, relatórios, editor SQL, importação/exportação de arquivo `.sqlite` e backup JSON.

## Banco SQLite
O SQLite é executado no navegador por SQL.js. Entre como administrador e abra **Banco SQLite** para consultar e alterar dados diretamente. É possível exportar o arquivo `.sqlite`, abri-lo num programa como DB Browser for SQLite ou num editor online, e importar a versão alterada de volta. Não existe sincronização automática entre navegadores ou computadores.

## Limitações
Esta é uma aplicação local demonstrativa, não um serviço multiusuário hospedado. A persistência é no navegador e as bibliotecas Bootstrap 5 e SQL.js são carregadas da internet. Não use dados pessoais ou senhas reais. Para uso institucional, será necessário backend com autenticação e banco compartilhado.
