# Bor de musica no discord com Discord.js

Após clonar o repositorio crie um arquive chamado ".env" e dentro dele cole isso->
```
TOKEN=xxx
CLIENT_ID=xxx
```

# Para usar com o Docker

`docker run -e TOKEN=<your_token_here> -e CLIENT_ID=<your_client_id_here> -d pabolo02345/discord-js-music-bot`

# Comandos

- play
  - song {url}       - Toca musica com url do youtuve
  - search {keyword} - Pesquisa no youtube a partir de palavras chaves
  - playlist {url}   - Toca playlist com a url do youtube

- skip   - Pula a musica atual
- queue  - Mostra as primeiras dez musicas
- pause  - pausa a musica atual
- resume - da play na musica pausada
- exit   - desconecta o bot
