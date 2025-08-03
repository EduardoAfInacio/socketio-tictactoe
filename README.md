# Tic-Tac-Toe Multiplayer com Socket.IO

Este projeto é um jogo da velha (tic-tac-toe) multiplayer em tempo real, desenvolvido com Node.js, Express e Socket.IO. O principal destaque é a comunicação em tempo real entre os jogadores, permitindo partidas dinâmicas e interativas diretamente no navegador.

## Principais Funcionalidades

- **Multiplayer em tempo real:** Dois jogadores podem se conectar e jogar juntos, com as jogadas sendo sincronizadas instantaneamente via Socket.IO.
- **Interface simples:** Frontend em HTML, CSS e JavaScript, fácil de usar e responsivo.
- **Gerenciamento de partidas:** O servidor organiza os jogadores em pares e controla o fluxo do jogo.

## Como rodar

1. Instale as dependências:
   ```
   npm install
   ```
2. Inicie o servidor:
   ```
   node server-side.js
   ```
3. Acesse [http://localhost:3000](http://localhost:3000) em dois navegadores diferentes para jogar.

## Estrutura

- `server-side.js`: Servidor Express + Socket.IO, gerencia conexões e lógica do jogo.
- `client-side.js`: Lida com a interface do usuário e comunicação com o servidor via sockets.
- `index.html` e `style.css`: Interface do jogo.

## Destaque

O uso do **Socket.IO** permite que as ações de um jogador sejam refletidas instantaneamente para o outro, proporcionando uma experiência multiplayer.
