# Certificado de joia em card · Kells

Protótipo de certificado digital de joia no formato de card colecionável (inspirado em cartas de jogos de cartas), feito para a **Kells**, plataforma de certificação permanente e verificável de joias.

A peça de exemplo é o anel de noivado de ouro branco com diamante rosa da **Soho Design** ([fotos e vídeo 360° no Gembox](https://gembox.app/s/OJLOk53oe9)).

## Como ver

Abra o `index.html` no navegador (dois cliques no arquivo). Não precisa instalar nada.

## O que o card mostra

**Frente**
- Topo: selo do teor do metal (585 = ouro 14K), símbolo da gema e selo do ateliê com a letra capitular "S".
- Janela de imagem com as fotos da peça e o vídeo 360° (arraste para girar).
- Linha de tipo com a raridade da peça.
- Dados técnicos: metal, peso, gema, formato, cor, pureza, lapidação e medidas, mais o botão do laudo GIA.
- Barra deslizante que revela o Kells ID.

**Verso**
- História da peça e ficha técnica no formato de catálogo de joalheria (nome, especificação, autoria, destino, matéria-prima, técnicas, motivo, justificativa, direcionamento, processo executivo, valor e data).
- QR code de verificação e hash do proprietário.

**Sistema do card** (abaixo do card)
- Raridades: Treasury, Work of Art, One of a Kind e Eco. Cada uma muda a cor da moldura.
- Gemas: esmeralda (corte esmeralda), rubi (oval), safira (gota) e diamante (brilhante).
- Tabela de teores de metal: prata, ouro, paládio e platina.

## Observações

- Kells ID, QR code, hash do proprietário e parte do texto do verso são **dados de exemplo**.
- Os dados da gema seguem o documento de briefing e ainda precisam ser conferidos com o ateliê.
- Fotos e vídeo: Soho Design, via Gembox.

## Estrutura

```
index.html        página do card (HTML, CSS e JavaScript num arquivo só)
assets/f1-f4.jpg  fotos da joia
assets/ring360.mp4 vídeo 360° da joia
```
