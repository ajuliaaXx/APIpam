Este projeto consiste em uma API básica construída com Node.js e Express, voltada para quem quer aprender a criar APIs de forma rápida e prática com essas tecnologias. A API utiliza fetch para realizar requisições HTTP.

A configuração inicial foi feita utilizando o comando npm init, que gerou automaticamente o arquivo package.json, contendo as informações do projeto e suas dependências. A principal dependência instalada é o Express, que facilita a criação de servidores e APIs em Node.js.

No arquivo index.js, um servidor foi configurado com o Express para responder a requisições GET na rota raiz (/), retornando a mensagem "API funcionando!" como uma confirmação de que a API está ativa. A API pode ser acessada via fetch no navegador ou em qualquer outra aplicação cliente que faça requisições HTTP. O servidor roda localmente na porta 3000 e pode ser acessado em http://localhost:3000.

Para rodar a API, basta executar o comando node index.js no terminal. Isso iniciará o servidor, que ficará aguardando as requisições. Você pode testar a API usando fetch diretamente no navegador, ou utilizando ferramentas como Postman ou curl.

Este repositório oferece uma estrutura simples para quem deseja começar a desenvolver APIs com Node.js e Express, podendo ser facilmente expandido para adicionar mais funcionalidades, como novas rotas, autenticação e integração com bancos de dados, conforme a necessidade do projeto.
