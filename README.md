# Ford Ka

Página estática de venda do Ford Ka SE 1.0 2016 — acessada pelo QR Code colado no carro.

## Publicar no GitHub Pages

1. Faça push para o GitHub.
2. Em **Settings → Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`.
3. A URL fica `https://<usuario>.github.io/ford-ka/` — gere o QR Code apontando para ela.

## Trocar as fotos

As fotos ficam em `images/`. Para usar as fotos reais do carro, substitua os arquivos
mantendo os nomes (`01-traseira.jpg`, `02-frente.jpg`, `03-lateral.jpg`). Para adicionar
ou remover fotos, edite os blocos `<figure>` em `index.html`. Prefira imagens com ~1280px
de largura (paisagem, 4:3) para carregar rápido no celular.

Ao trocar pelas fotos reais, remova também o aviso "Fotos ilustrativas" e os créditos do rodapé.

## Editar informações

Preço, ficha, itens e o número/mensagem do WhatsApp estão direto no `index.html`.
O link do WhatsApp usa `https://wa.me/5528999829561?text=...` (mensagem codificada em URL).
