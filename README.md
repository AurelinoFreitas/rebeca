# Convite — Rebeca faz 1 aninho

Site do convite publicado pelo GitHub Pages. As confirmações de presença são gravadas
na planilha "Aniversário Rebeca 1 ano — Convidados" pelo Web App do Apps Script.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | O convite (animação, música, confirmação e ingresso) |
| `musica.mp3` | Trilha do convite |
| `rebeca-foto.jpg` | Foto do cartão |
| `og-image.jpg` | Imagem que aparece na prévia do link no WhatsApp |
| `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` | Fazem o convite funcionar como aplicativo |
| `sw.js` | Guarda o convite no celular para abrir mais rápido |
| `.nojekyll` | Diz ao GitHub Pages para publicar os arquivos como estão |

## Links

- Convite geral: `https://aurelinofreitas.github.io/rebeca/`
- Convite pessoal: `https://aurelinofreitas.github.io/rebeca/?c=CODIGO` (coluna I da planilha)
- Recepção: endereço do Apps Script terminado em `/exec?p=recepcao`

## Atualizar a música ou a foto

Envie o arquivo novo com o mesmo nome por cima do antigo (Add file → Upload files).
Se mudar a trilha, aumente o número em `CACHE = "rebeca-convite-v1"` no `sw.js`
(por exemplo, `v2`) para os celulares buscarem a versão nova.
