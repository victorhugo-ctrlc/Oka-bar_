# OKA — website institucional

Entrega estática, responsiva e acessível do site institucional do OKA Quadra de Areia & Bar.

## Estrutura
- `index.html` — página e SEO/schema
- `styles.css` — design system e responsividade
- `content.js` — conteúdo centralizado/editável
- `app.js` — interações, lightbox, animações e formulário
- `robots.txt` / `sitemap.xml` — base de SEO técnico

## Como publicar
Pode ser servido como site estático em qualquer hospedagem/CDN. Para produção:
1. Substitua `https://www.example.com/` pelo domínio real em `index.html` e `sitemap.xml`.
2. Hospede as imagens oficiais do OKA em CDN própria e atualize apenas `content.js`/HTML.
3. Conecte o formulário a um endpoint real (o protótipo atualmente valida e mostra confirmação local).
4. Se houver CMS, faça o backend alimentar `content.js` ou migre os dados para sua camada de conteúdo.
5. Ative compressão Brotli/Gzip, cache de assets e HTTPS na hospedagem.

## Conteúdo verificado usado na base
Endereço, telefone, Instagram, nota/quantidade de avaliações e horários foram conferidos em fontes públicas recentes. Há divergência entre diretórios sobre a segunda-feira; por isso o horário permanece centralizado e editável, com aviso para confirmação antes da visita.

## Fotos
A imagem inicial usa uma fotografia pública do espaço encontrada em uma página de reservas/quadras. Antes de uma publicação comercial definitiva, recomendo substituir por arquivos fornecidos/autorizados pelo estabelecimento, mantendo o mesmo `content.js`. A galeria está preparada para receber múltiplas fotos reais.

## Formulário
O formulário é propositalmente neutro quanto à disponibilidade de eventos. Ele não confirma reserva nem inventa serviços. Conecte-o a WhatsApp, e-mail ou CRM após definir o fluxo oficial do OKA.
