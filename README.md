# OKA — V3 corrigida para produção

## O que mudou
A página não depende mais de JavaScript para renderizar o conteúdo principal. Isso elimina o problema visto nas capturas, em que o JS falhava e deixava enormes áreas vazias.

- Conteúdo principal está no HTML.
- Imagens públicas do OKA são usadas quando o host remoto responde.
- Cada imagem possui fallback local SVG, então nunca aparece uma área vazia.
- Menu mobile real para Android/iPhone.
- Galeria/lightbox independente.
- Mapa, telefone, Instagram e Google Maps.
- Formulário com acessibilidade.
- Layout mobile específico.
- `prefers-reduced-motion`.
- SEO e LocalBusiness.
- Sem dependência de React/Next/Tailwind para uma página institucional simples.

## Imagens
As fotos públicas são da página do OKA no SmashPro. Para uso oficial/comercial, substitua pelas fotos autorizadas pelo estabelecimento. Os SVGs em `assets/` são apenas fallbacks de carregamento e não se passam por fotografias reais.

## Deploy na Vercel
Faça upload desta pasta como projeto estático. O arquivo `index.html` é a entrada. Não é necessário build.
