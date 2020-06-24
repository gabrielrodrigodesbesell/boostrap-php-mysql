# Projeto Bootstrap + PHP + MYSQL
Projeto desenvolvido com os alunos do curso de programação para internet:
- [x] Desenvolvimento de páginas estáticas em HTML;
- [x] Transformar páginas HTML em PHP;
- [x] Estruturar o site para que seu fluxo de acesso seja enviado para index.php e tratar a exibição das páginas de forma dinâmica;
- [x] Criar o modelo ER do site;
- [x] Conectar o site ao banco de dados;
- [x] Deixar a página **Inicial** dinâmica com exibição de dados vindos do banco de dados;
- [x] Deixar a página **Cursos** dinâmica com exibição de dados vindos do banco de dados e imagens do diretório público;
    - [x] Criar a página de exibição do curso quando clicado em "Saiba Mais";
- [x] Criar a página de exibição da **História**;
- [x] Realizar a codificação do script de envio de email na página **Fale conosco**;
- [ ] Área de administração - gestão de História/Sobre;
    - [ ] Implementar validação de formulário via JS
    - [ ] Envio de requisições via ajax
    - [ ] Interação com o usuário através de Toasts
    - [ ] Aplicar editor wysiwyg no campo "descricao"
- [x] Área de administração - gestão de Últimas publicações:
    - [x] listagem de publicações
    - [x] cadastro de publicações
    - [x] exclusão de publicações
    - [x] atualização de publicações
    - [x] Implementar validação de formulário via JS
    - [x] Envio de requisições via ajax
    - [x] Interação com o usuário através de Toasts
    - [x] Link de exclusão com confirmação (sweetalert) e requisição via ajax
    - [x] trocar o campo de digitação do nome do curso para campo de seleção do curso com dados vindos da tabela cursos;
    - [ ] Aplicar plugin no campo de seleção(chosen ou select2);
- [x] Área de administração - reorganizar itens dentro de pastas, dividindo os módulos;
- [x] Todas as ações dos módulos devem ficar no script: modulo/acoes.php;
- [x] As ações dos módulos retornarão uma sessão chamada "mensagem" que deve ser exibida logo abaixo do cabeçalho da administração;    
- [x] Após exibir para o usuário o conteúdo da sessão "mensagem", realizar a destruição dela para não exibir novamente;    
- [x] Área de administração - gestão de cursos:
    - [x] listagem de cursos
    - [x] cadastro de cursos com upload de imagem
    - [x] exclusão de cursos
    - [x] atualização de cursos com upload de nova imagem
    - [ ] Implementar validação de formulário via JS
    - [ ] Envio de requisições via ajax
    - [ ] Interação com o usuário através de Toasts
    - [ ] adicionar plugin de drop down na escolha do arquivo
- [x] Área de administração: login;
- [x] Área de administração - controle de sessão;
- [x] Permitir modificação dos dados do usuário;
- [ ] Todo link de exclusão deve possuir uma confirmação do usuário antes de executar a ação, para não excluir sem querer (sweetalert).
- [x] Adicionar as tabelas de listas um plugin de GRID (datatables).
- [ ] Hospedar a aplicação em um host virtual; 