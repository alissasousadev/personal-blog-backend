<h1 align="center">Blog Pessoal Backend</h1>

<p align="center">
  Backend da aplicação <strong>Blog Pessoal</strong>, desenvolvido com <strong>NestJS</strong>,
  com autenticação via <strong>JWT</strong>, criptografia de senhas com <strong>bcrypt</strong>,
  documentação com <strong>Swagger</strong> e persistência de dados com <strong>TypeORM</strong>.
</p>

<p align="center">
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="TypeORM" src="https://img.shields.io/badge/TypeORM-E83524?style=for-the-badge" />
  <img alt="JWT" src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
  <img alt="Swagger" src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

<hr />

<h2>Sobre o projeto</h2>

<p>
  O <strong> Blog Pessoal Backend</strong> é uma API REST desenvolvida para sustentar a aplicação de blog pessoal,
  oferecendo recursos de autenticação, gerenciamento de usuários, postagens e temas.
</p>

<p>
  O projeto foi construído com foco em arquitetura modular, organização em camadas, relacionamento entre entidades
  e proteção de rotas autenticadas. A aplicação utiliza JWT para controle de acesso, bcrypt para criptografia de senhas
  e Swagger para documentação da API.
</p>

<hr />

<h2> Objetivos do projeto</h2>

<ul>
  <li>Construir uma API REST com NestJS</li>
  <li>Praticar autenticação com e-mail e senha</li>
  <li>Aplicar segurança com JWT e bcrypt</li>
  <li>Trabalhar relacionamento entre entidades com TypeORM</li>
  <li>Documentar endpoints com Swagger</li>
  <li>Estruturar o backend de forma modular e escalável</li>
</ul>

<hr />

<h2> Tecnologias Utilizadas</h2>

<ul>
  <li>NestJS</li>
  <li>TypeScript</li>
  <li>TypeORM</li>
  <li>JWT</li>
  <li>Passport</li>
  <li>bcrypt</li>
  <li>Swagger</li>
  <li>class-validator</li>
  <li>class-transformer</li>
  <li>MySQL</li>
</ul>

<hr />

<h2> Módulos da aplicação</h2>

<ul>
  <li><strong>Usuários</strong> → cadastro e gerenciamento de usuários</li>
  <li><strong>Autenticação</strong> → login com e-mail e senha, geração e validação de token JWT</li>
  <li><strong>Postagens</strong> → criação, listagem, edição e exclusão de postagens</li>
  <li><strong>Temas</strong> → criação e listagem de temas/categorias para organização das postagens</li>
</ul>

<hr />

<h2> Autenticação e segurança</h2>

<p>
  A autenticação da aplicação é realizada com <strong>e-mail e senha</strong>.
  Após a validação das credenciais, o sistema gera um <strong>token JWT</strong>,
  utilizado para proteger rotas autenticadas da API.
</p>

<ul>
  <li>Autenticação com e-mail e senha</li>
  <li>Proteção de rotas com guard JWT</li>
  <li>Criptografia de senha com <code>bcrypt</code></li>
  <li>Uso de <code>Passport</code> e <code>passport-jwt</code></li>
</ul>

<hr />

<h2> Entidades e relacionamentos</h2>

<ul>
  <li>Um <strong>usuário</strong> pode criar várias <strong>postagens</strong></li>
  <li>Uma <strong>postagem</strong> pertence a um único <strong>tema</strong></li>
  <li>Um <strong>tema</strong> pode estar relacionado a várias <strong>postagens</strong></li>
</ul>

<p><strong>Resumo dos relacionamentos:</strong></p>

<ul>
  <li><code>Usuario 1:N Postagem</code></li>
  <li><code>Tema 1:N Postagem</code></li>
</ul>

<hr />

<h2> Funcionalidades</h2>

<ul>
  <li>Cadastrar usuário</li>
  <li>Autenticar usuário</li>
  <li>Criar postagens</li>
  <li>Listar postagens</li>
  <li>Editar postagens</li>
  <li>Excluir postagens</li>
  <li>Criar temas</li>
  <li>Listar temas</li>
</ul>

<hr />

<h2> Como executar o projeto localmente</h2>

<ol>
  <li>Clone este repositório</li>
</ol>

<pre><code>git clone https://github.com/alissasousadev/personal-blog-backend.git</code></pre>

<ol start="2">
  <li>Acesse a pasta do projeto</li>
</ol>

<pre><code>cd personal-blog-backend</code></pre>

<ol start="3">
  <li>Instale as dependências</li>
</ol>

<pre><code>npm install</code></pre>

<ol start="4">
  <li>Execute o projeto em ambiente de desenvolvimento</li>
</ol>

<pre><code>npm run start:dev</code></pre>

<ol start="5">
<p>
  A API ficará disponível localmente em uma porta configurada no projeto, geralmente:
</p>
</ol>

<pre><code>http://localhost:3000</code></pre>

<hr />


<h2> Documentação da API</h2>

<p>
  A documentação dos endpoints foi construída com <strong>Swagger</strong>,
  facilitando testes e visualização das rotas disponíveis.
</p>

<pre><code>https://blogpessoal-zypu.onrender.com/swagger</code></pre>

<hr />

<h2> Deploy</h2>

<p>
  A API possui publicação online para fins de teste e demonstração.
</p>

<pre><code>https://blogpessoal-zypu.onrender.com</code></pre>

<hr />

<h2> Aprendizados aplicados</h2>

<ul>
  <li>Construção de API REST com NestJS</li>
  <li>Autenticação com JWT</li>
  <li>Criptografia de senhas com bcrypt</li>
  <li>Relacionamentos entre entidades com TypeORM</li>
  <li>Validação de dados com class-validator</li>
  <li>Documentação de API com Swagger</li>
  <li>Estruturação modular de backend</li>
</ul>

<hr />
<div align="center">
<p>
  <em>
  Projeto desenvolvido como prática de backend no bootcamp da Generation.
  </em>
</p>
</div>
