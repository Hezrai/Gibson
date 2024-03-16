<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spring Boot 2 OAuth2 Application</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>

<div style="text-align: center;">
    <h1><i class="fab fa-spring"></i> Spring Boot 2 OAuth2 Application <i class="fab fa-keycdn"></i></h1>
    <p>Este é um projeto Spring Boot que demonstra a configuração básica de autenticação OAuth2.</p>
</div>

<h2>Configuração</h2>
<p>O projeto utiliza propriedades OAuth2 armazenadas em um arquivo <code>application.properties</code> para configurar o serviço de autenticação.</p>

<h2>Endpoints</h2>

<ul>
    <li><strong>/userJwt</strong>: Este endpoint retorna informações sobre o usuário autenticado usando JWT (JSON Web Token).</li>
    <li><strong>/userRedis</strong>: Este endpoint retorna informações sobre o usuário autenticado usando Redis para armazenamento de sessão.</li>
    <li><strong>/user/me</strong>: Este endpoint retorna o usuário autenticado.</li>
</ul>

<h2>Como executar</h2>
<p>Para executar o projeto, você pode usar o comando <code>mvn spring-boot:run</code> ou executar a classe <code>SpringBoot2Oauth2Application.java</code> diretamente em sua IDE.</p>
<p>Certifique-se de que o JDK configurado é compatível com o projeto e de que as dependências necessárias estão instaladas.</p>

<h2>Autor</h2>
<p>Este projeto foi desenvolvido por [seu nome aqui].</p>

</body>
</html>
