# Love Story — Paredão de Som

Landing page de página única para a Love Story, caminhão de som de alta potência
para locação em eventos, festas e produções.

100% SVG + CSS inline (sem imagens externas), com:

- Paredão animado pulsando no grave (organic, fase aleatória por caixa)
- Ficha técnica com barras animadas e contador
- Diagrama fechado/aberto do caminhão
- Agenda de próximos eventos (edite o array `eventos` dentro de `index.html`)
- Botão de contato via WhatsApp

## Como publicar

O site é um único arquivo estático (`index.html`), sem build step. Para publicar
com GitHub Pages:

1. Suba este repositório no GitHub.
2. Vá em **Settings → Pages**.
3. Em "Branch", selecione `main` e a pasta `/ (root)`.
4. Salve — o site fica disponível em `https://<usuario>.github.io/<repo>/`.

## Editar a agenda

Dentro de `index.html`, procure por `var eventos = [` e edite as datas
(formato `AAAA-MM-DD`), nome do evento e cidade. Eventos com data passada
somem sozinhos da lista.

## Contato

WhatsApp: 11 94729-7954
