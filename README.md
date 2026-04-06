# JOGO PULOS INFINITOS WEB

Este projeto é a versão HTML5 exportada do jogo "Pulos Infinitos".
Ele inclui todos os recursos necessários para rodar o jogo em navegadores compatíveis com HTML5.

## Estrutura do projeto

- `index.html` - página inicial do jogo
- `style.css` - estilos de layout e interface
- `sw.js` - service worker para suporte offline
- `offline.json` - configurações de cache e recursos offline
- `data.json` - dados de configuração do jogo
- `workermain.js` - código principal para worker de jogos
- `scripts/` - scripts auxiliares e runtime do Construct 3
- `icons/`, `images/`, `media/` - recursos gráficos e de áudio usados no jogo

## Como usar

1. Abra `index.html` em um navegador compatível.
2. Caso deseje hospedar o jogo, copie todos os arquivos para um servidor web.
3. O service worker (`sw.js`) permite funcionamento em modo offline em navegadores que suportam PWA.

## Observações

- Este projeto parece ser uma exportação do Construct 3 ou similar.
- Não há dependências externas além dos arquivos já incluídos.
- Para alterações no jogo, edite os arquivos de exportação gerados pelo motor de desenvolvimento.

## Publicação

O repositório de destino é: https://github.com/rodrigocastroabreu/JOGO-PULOS-INFINITOS-WEB
