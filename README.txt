
# Como adicionar a logo e fotos dos advogados

## 📌 Logo do escritório
1. Prepare uma imagem da logo no formato PNG (preferencialmente com fundo transparente).
2. Nomeie a imagem como `logo.png`.
3. Suba o arquivo para o repositório na pasta principal (mesma do index.html).
4. No arquivo `index.html`, dentro da <div class="logo-space">, adicione esta linha:
   <img src="logo.png" alt="Logo" style="height: 60px;">

## 📌 Fotos dos advogados
1. Prepare uma imagem para cada advogado em formato quadrado (ex: 300x300px).
2. Nomeie como `marco.jpg` e `esther.jpg` (ou outro nome que preferir).
3. Suba as imagens no repositório.
4. No `index.html`, troque o conteúdo de cada `<div class="circle-photo">Foto</div>` por:
   <img src="marco.jpg" class="circle-photo"> — e mesma coisa para `esther.jpg`.

## Obs:
A imagem será automaticamente recortada em formato circular.
