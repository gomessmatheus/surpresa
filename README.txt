# Site de Surpresa - Guia de Publicacao

Este e um site estatico simples (um arquivo `index.html`) com um campo de senha que revela o `voucher.pdf` quando a senha correta e digitada.

## Senha atual
`macamarromtortaventotremsono`

> Regra usada: palavras-chave dos 6 livros, tudo minusculo e sem acento, coladas:
maca + marrom + torta + vento + trem + sono

## Como publicar de graca (GitHub Pages)
1) Crie uma conta no GitHub (se ainda nao tiver): https://github.com
2) Clique em **New repository** e crie um repo chamado, por exemplo, `surpresa` (Public).
3) Envie (upload) os arquivos `index.html` e `voucher.pdf` (este ja esta na pasta).
4) Va em **Settings > Pages**:
   - **Source**: selecione `Deploy from a branch`
   - **Branch**: selecione `main` e a pasta `/ (root)`; clique em **Save**.
5) Em alguns minutos seu site ficara disponivel em: `https://SEU-USUARIO.github.io/surpresa`

## Como mudar a senha
- Abra `index.html` e troque o valor de `const CORRECT = "..."` para a senha que quiser.
- A pagina ja normaliza acentos e remove espacos/hifens automaticamente.

## Dica de QR Code
Depois que o site estiver no ar, gere um QR apontando para a URL final usando um dos sites gratuitos:
- https://www.qr-code-generator.com/
- https://www.qrcode-monkey.com/

Cole o QR no recado do tenis.

## Observacao importante
Isso nao e seguranca real (front-end). Para a brincadeira esta perfeito.
