Spring Boot 2 OAuth2 Application

Este é um projeto Spring Boot que demonstra a configuração básica de autenticação OAuth2.
Configuração

O projeto utiliza propriedades OAuth2 armazenadas em um arquivo application.properties para configurar o serviço de autenticação.
Endpoints
/userJwt

Este endpoint retorna informações sobre o usuário autenticado usando JWT (JSON Web Token).
/userRedis

Este endpoint retorna informações sobre o usuário autenticado usando Redis para armazenamento de sessão.
/user/me

Este endpoint retorna o usuário autenticado.
Como executar

Para executar o projeto, você pode usar o comando mvn spring-boot:run ou executar a classe SpringBoot2Oauth2Application.java diretamente em sua IDE.

Certifique-se de que o JDK configurado é compatível com o projeto e de que as dependências necessárias estão instaladas.
Autor

Este projeto foi desenvolvido por MelGibson