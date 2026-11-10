# Sistema Musical - Catálogo de Artistas e Músicas

Projeto desenvolvido para o 2º semestre do curso Técnico em Desenvolvimento de Sistemas do SENAI-SP.

O objetivo do projeto é transformar a interface front-end desenvolvida na Fase 1 em um sistema web dinâmico, utilizando PHP e MySQL para implementar o backend e realizar a integração com o banco de dados, permitindo o gerenciamento de artistas e suas respectivas obras musicais.

## Visão Geral do Projeto

A aplicação foi desenvolvida utilizando HTML5, CSS3, PHP e MySQL, integrando a interface visual da primeira fase com funcionalidades de backend e persistência de dados.

O sistema permite o gerenciamento completo de artistas e músicas, com autenticação de usuários, controle de sessões e operações de cadastro, consulta, edição e exclusão de registros. Também possui funcionalidade de upload de imagens, permitindo associar fotografias aos artistas e capas às músicas.

O sistema é organizado em cinco telas principais:
1. **Login (`login.html`)**: Tela de autenticação de usuários, integrada ao backend para validação das credenciais e controle de acesso ao sistema por meio de sessões.
2. **Menu Principal (`index.html`)**: Painel central de navegação que permite acessar as funcionalidades de gerenciamento de artistas e músicas, com controle de acesso para usuários autenticados.
3. **Cadastro de Artistas (`cadastro_artista.html`)**: Área de gerenciamento de artistas, permitindo cadastrar, consultar, editar e excluir registros, incluindo informações como nome, gênero musical, país e fotografia por meio de upload de imagens.
4. **Cadastro de Músicas (`cadastro_musica.html`)**: Área destinada ao gerenciamento de músicas, permitindo cadastrar, consultar, editar e excluir obras, associando cada música a um artista e armazenando informações como título, álbum, gênero musical, URL do YouTube, capa e letra.
5. **Biblioteca Musical (`listagem_musicas.html`)**: Interface de consulta das músicas cadastradas no banco de dados, com funcionalidades de listagem e filtros de pesquisa, além de acesso às ações de gerenciamento dos registros.

## Tecnologias e Recursos Utilizados

- **HTML5**: Estruturação das páginas e dos formulários, utilizando elementos semânticos e campos apropriados para entrada de dados.
- **CSS3**: Estilização das interfaces, organização dos elementos visuais, layouts responsivos e apresentação dos componentes do sistema.
- **PHP**:
  - Implementação do backend e processamento das requisições enviadas pelos formulários.
  - Integração com o banco de dados MySQL para armazenamento, consulta, atualização e exclusão de informações.
  - Implementação da autenticação de usuários e gerenciamento de sessões.
  - Processamento dos cadastros e gerenciamento de artistas e músicas.
  - Implementação da funcionalidade de upload de imagens.
- **MySQL**:
  - Armazenamento persistente dos dados de usuários, artistas e músicas.
  - Organização das informações em tabelas relacionadas.
  - Consultas e operações de manipulação dos registros utilizados pelo sistema.
- **Integração Front-end e Back-end**: Comunicação entre as interfaces desenvolvidas em HTML e CSS, a lógica de processamento em PHP e o banco de dados MySQL, transformando o projeto estático da Fase 1 em uma aplicação web funcional e dinâmica.
