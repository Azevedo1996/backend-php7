<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  
</head>
<body>
  <h1>Backend com PHP7: Integração com MySQLi e Gerenciamento de Banco de Dados com XAMPP e phpMyAdmin</h1>
  <p>Este repositório contém um projeto de backend desenvolvido em PHP7, com integração com o banco de dados MySQL utilizando a extensão MySQLi. Além disso, o projeto utiliza o XAMPP como ambiente de desenvolvimento local e o phpMyAdmin para facilitar a administração do banco de dados.</p>
  <h2>Pré-requisitos</h2>
  <p>Antes de começar, certifique-se de ter os seguintes requisitos instalados em sua máquina:</p>
  <ul>
    <li>XAMPP: Um pacote de software que inclui o Apache, o MySQL e o PHP.</li>
    <li>phpMyAdmin: Uma ferramenta para administração e gerenciamento de bancos de dados MySQL.</li>
  </ul>
  <h2>Configuração do Ambiente</h2>
  <ol>
    <li>Clone este repositório em sua máquina local.</li>
    <li>Instale o XAMPP de acordo com as instruções fornecidas pela documentação oficial.</li>
    <li>Inicie o XAMPP e verifique se o Apache e o MySQL estão em execução.</li>
    <li>Abra o phpMyAdmin em seu navegador e crie um novo banco de dados para o projeto.</li>
  </ol>
  <h2>Configuração do Projeto</h2>
  <ol>
    <li>Abra o arquivo <code>conexao.php</code> localizado na pasta <code>src</code> do projeto.</li>
    <li>Edite as informações de conexão com o banco de dados, como o nome de usuário, senha e nome do banco de dados.</li>
    <li>Salve o arquivo com as alterações.</li>
  </ol>
  <h2>Executando o Projeto</h2>
  <ol>
    <li>Coloque o projeto dentro do diretório <code>htdocs</code> do XAMPP.</li>
    <li>Abra o navegador e acesse <code>http://localhost/nome_do_seu_projeto</code> para iniciar a aplicação.</li>
  </ol>
  <h2>Funcionalidades</h2>
  <p>Este projeto contém funcionalidades básicas de CRUD (Create, Read, Update, Delete) para as entidades Cliente, Funcionário e Usuários.</p>
  <p>Para cada entidade, temos as seguintes operações disponíveis:</p>
  <ul>
    <li>Criação de um novo registro.</li>
    <li>Listagem de todos os registros.</li>
    <li>Atualização das informações de um registro existente.</li>
    <li>Exclusão de um registro.</li>
  </ul>
  <h2>Contribuição</h2>
  <p>Sinta-se à vontade para contribuir com melhorias, correções de bugs ou adição de novas funcionalidades. Basta seguir as etapas abaixo:</p>
  <ol>
    <li>Faça um fork deste repositório.</li>
    <li>Crie uma branch com suas modificações: <code>git checkout -b minha-branch</code>.</li>
    <li>Faça commit das suas alterações: <code>git commit -m 'Minhas modificações'</code>.</li>
    <li>Faça push para a branch: <code>git push origin minha-branch</code>.</li>
    <li>Abra um Pull Request para que suas alterações sejam revisadas e mescladas ao projeto.</li>
  </ol>
<h2>Telas do sistema</h2>
  <img src="screenshots/1.png" alt="Tela de Login">
  <img src="screenshots/2.png" alt="Tela de administrador">
  <img src="screenshots/3.png" alt="Mostrando q troca de painel e opção de saída">
  <img src="screenshots/4.png" alt="Tabela de funcionarios">
  <img src="screenshots/5.png" alt="Tabela de usuarios">
  <img src="screenshots/6.png" alt="Tabela de cargos">
  <img src="screenshots/7.png" alt="Tela de funcionarios">
  <img src="screenshots/8.png" alt="Tabela de clientes">
  <img src="screenshots/9.png" alt="Banco de dados">
 </body>
</html>
