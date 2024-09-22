# Socket.io Test App (POC)

Esta é uma aplicação simples usando Socket.io e Express para demonstrar comunicação via WebSockets.

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/gabrielbotandev/socketio-test-app.git

   ```

2. Instale as dependências:

   ```bash
   npm install

   ```

3. Para rodar a aplicação em modo de desenvolvimento (TypeScript):

   ```bash
   npm run dev

   ```

4. Para compilar o TypeScript e rodar a versão compilada:
   ```bash
    npm run build
    npm start
   ```

## Acesso

Acesse http://localhost:8899/ para ver o cliente e envie mensagens com o endpoint /msg.

## Teste

Para testar o envio de mensagens:

```bash
curl "http://localhost:8899/msg?msg=Hello"

```
