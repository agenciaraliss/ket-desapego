# Ket Desapego — layout personalizado (tema Rio, Nuvemshop)

Agência Raliss · Sites com a Lari

- `ket.css` — todo o visual (cabeçalho, menu, categorias, cards, páginas, achado da vez, rodapé).
- `ket.js` — funções (menu e mega-menu, cards com COMPRAR, etiqueta, como funciona, bazar presencial, depoimentos, rodapé animado, rastreio Nuvem Envio, barra de frete grátis, raspadinha, marca d'água).

Tudo lê os dados do admin (menu, categorias, produtos, rodapé).

## Instalação na Nuvemshop

**CSS personalizado:**
```css
@import url("https://cdn.jsdelivr.net/gh/agenciaraliss/ket-desapego@main/ket.css");
```

**Código do rodapé:**
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/agenciaraliss/ket-desapego@main/ket.css">
<script src="https://cdn.jsdelivr.net/gh/agenciaraliss/ket-desapego@main/ket.js"></script>
```

Depois de atualizar um arquivo, limpar o cache: `https://purge.jsdelivr.net/gh/agenciaraliss/ket-desapego@main/ket.css` (e `ket.js`).
