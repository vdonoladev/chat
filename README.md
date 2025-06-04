<h1 align="center" style="font-weight: bold;">Chat</h1>

<p align="center">
  <a href="#tech">Tecnologias</a> • 
  <a href="#about">Sobre</a> •
  <a href="#started">Começando</a> • 
  <a href="#contribute">Contribuir</a>
</p>

<p align="center">
    <b>Chat é um aplicativo de mensagens em tempo real que permite que qualquer pessoa se junte à conversa utilizando um único link.</b>
</p>

<h2 id="tech">Tecnologias</h2>

- [WebSocket](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket) - WebSocket é um protocolo de comunicação que permite a comunicação bidirecional entre o servidor e o cliente, facilitando a troca de mensagens em tempo real sem a necessidade de recarregar a página.

- [Node.js](https://nodejs.org/) - Node.js é uma plataforma que permite a execução de JavaScript no servidor. Usado para criar o **back-end** da aplicação, responsável por gerenciar as conexões WebSocket e processar as mensagens.

- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) - JavaScript é utilizado para implementar tanto a lógica do front-end, gerenciando a interface de chat, como também para a interação com o servidor WebSocket.


<h2 id="about">Sobre</h2>

<p><b>Chat</b> é um aplicativo de mensagens em tempo real que permite que qualquer pessoa se junte à conversa utilizando um único link. O chat pode ser tanto individual quanto em grupo, permitindo a comunicação entre múltiplos usuários de forma rápida e eficiente.</p>

<p>Este projeto foi construído com <b>WebSocket</b> e <b>Node.js</b> no <b>back-end</b> e <b>JavaScript</b> no <b>front-end</b>, garantindo uma experiência interativa e em tempo real.</p>

<p>O **Chat** permite a comunicação instantânea entre usuários através de uma sala de bate-papo, com as seguintes funcionalidades:</p>

- **Bate-papo Individual:** Conversas privadas entre duas pessoas.
- **Bate-papo em Grupo:** Várias pessoas podem interagir na mesma conversa utilizando o mesmo link.
- **Sem Cadastro:** Não é necessário criar uma conta, basta acessar o link para começar a conversar.
- **Conexão em Tempo Real:** O envio e recebimento de mensagens acontecem em tempo real, utilizando WebSocket.

<h2 id="started">Começando</h2>

1. **Clone este repositório:**

```bash
git clone https://github.com/vdonoladev/chat.git
```

2. **Navegue até o diretório do projeto:**

```bash
cd chat
```

3. Instale as dependências necessárias no back-end:

```bash
npm install
```

3. **Execute o script:**

```bash
node --watch src/server.js
```

4. Abra o **front-end** em um navegador de sua preferência. O chat estará disponível no link do servidor, onde qualquer pessoa com esse link pode participar da conversa.

<h2 id="contribute">Contribuir</h2>

1. `git clone https://github.com/vdonoladev/chat.git`
2. `git checkout -b feature/NAME-OF-FEATURE`
3. Siga os **Commit Patterns**
4. Abra um **Pull Request** explicando o problema resolvido ou o recurso feito, se houver, anexe a captura de tela das modificações visuais e aguarde a revisão!

<h3>Documentações que podem ajudar</h3>

- [📝 How to create a Pull Request](https://www.atlassian.com/br/git/tutorials/making-a-pull-request)

- [💾 Commit pattern](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)