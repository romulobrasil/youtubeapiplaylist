# Youtube API Playlist

Código em PHP para listar todos os vídeos de uma playlist do Youtube. 

O Youtube API possui uma limitação de até **50 vídeos** por página. Nesse caso, existe duas variáveis para você fazer a paginação para próxima página e para página anterior que é a **prevPageToken** para anterior e a **nextPageToken** para próxima que estão sendo armazenadas no array que o **pageToken** é atualizado a cada paginação.

Para conseguir a sua chave de **Token** (credencial), basta ir nesse link: [https://console.developers.google.com/apis/credentials](https://console.developers.google.com/apis/credentials) e criar uma.

Para pegar o **ID** da sua playlist é no link dela: https://www.youtube.com/playlist?list=IDHERE.

No caso eu decidi fazer um array só com minhas informações que eu achei necessária que são o título, a thumbnail e o link do vídeo, pois estou fazendo uma página que carrega o video em um modal. Para saber o que compõe o JSON, basta dar um **print_r** na variável **$playlistVids** que você verá todas as informações que vem da API do Youtube. 

Segue o link do post no meu blog com mais detalhes:
[https://romulobrasil.com/listar-todos-os-videos-de-uma-playlist-do-youtube/](https://romulobrasil.com/listar-todos-os-videos-de-uma-playlist-do-youtube/)