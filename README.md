# Workshop Lentes de Porcelana — página de vendas

## Conteúdo
- `index.dc.html` — a página inteira (markup + lógica em um só arquivo).
- `support.js` — runtime necessário para a página renderizar. Precisa ficar na mesma pasta.
- `assets/` — todas as imagens em .webp (hero, oval, arcada de transição, Nive, atendimento, 8 pares antes/depois do slider e 3 casos do fecho).

## Como publicar
Basta servir a pasta como estática (GitHub Pages, Netlify, Vercel, Nginx). Renomeie `index.dc.html` para `index.html` se o host precisar desse nome — nenhum caminho interno depende do nome do arquivo.

Abrir por `file://` pode falhar por CORS; use um servidor local, ex.: `python3 -m http.server`.

## Pendências
- Confirmar o percentual do contador ("18% dos ingressos vendidos"), que aparece em 5 lugares.

## Checkout
Todos os CTAs apontam para `https://pay.kiwify.com.br/PYf8ZIv` (Kiwify, mesma aba).
