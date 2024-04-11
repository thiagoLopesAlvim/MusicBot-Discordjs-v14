# Bot de musica no discord com Discord.js

1-Após clonar o repositorio crie um arquive chamado ".env" e dentro dele cole isso(No lugar do xxx colo que o TOKEN e o CLIENT_ID de seu proprio bot)->
```
TOKEN=xxx
CLIENT_ID=xxx
```
2- No terminal digite o comando npm install 

3-Para rodar seu bot em seguida no terminal digite node .
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
