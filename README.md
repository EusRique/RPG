# RPG - Game Of Thrones

Projeto de RPG da famosa série Game of Thrones Usando MongoDB como banco e o express-session para implementação da autenticação na aplicação

Foi desenvolvida como estudo de Node.js e tecnologias relacionadas para aplicações web.

## Principais tecnologias utilizadas
- [Express.js](https://expressjs.com/pt-br/) (framework para desenvolvimento web com Node.js);
- [Body parser](https://github.com/expressjs/body-parser) (Permite que clientes externos possam enviar informação para sua aplicação Node. js);
- [Bootstrap](https://getbootstrap.com/) (framework CSS);
- [Consign](https://github.com/jarradseers/consign) (Gerenciamento de rotas);
- [EJS](https://ejs.co/) (Linguagem de modelagem para criação de páginas HTML utilizando JavaScript);
- [MongoDB](https://www.mongodb.com/) (Banco de dados NoSQL);



## Como testar

Como pré-requisitos, é necessário instalar: 
[Node.js](https://nodejs.org/en/download/) e o
[MongoDB](https://www.mongodb.com/) aconselho utilizar Docker para o mongo

Com a aplicação instalada, abra o terminal ou prompt de comando (dependendo do sistema operacional utilizado) na pasta da aplicação. Em seguida, execute os seguintes comandos, em sequência:

```
npm install
node app
```

**Observação:** pode ser necessário utilizar `sudo` para instalar as dependências caso esteja usando Linux ou MacOS.

Após executar esses comandos, navegue  para `http://localhost:3000/`para visualizar a tela inicial da aplicação.

## Limitações

Algumas bibliotecas são importadas de CDNs diretamente nas views ou foram incluídas manualmente na pasta do projeto. Podem haver bugs de utilização e de segurança, então utilize a aplicação apenas para fins educativos.

![](/app/public/images/a.png)
![](/app/public/images/b.png)