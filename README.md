# Site Belamesa

Site institucional one-page da **Belamesa** — alimentos de qualidade para o poder público.

## Estrutura
- `index.html` — página única (HTML + CSS + JS no mesmo arquivo)
- `img/` — fotos, logo, favicon e imagem de compartilhamento

## Como alterar
- **Textos:** edite direto no `index.html` (cada seção tem um `id`: `inicio`, `quem-somos`, `jornada`, `garantias`, `atendemos`, `contato`).
- **Fotos:** substitua o arquivo em `img/` mantendo o mesmo nome (JPG, ~1600px de largura).
- **Cores:** no topo do `<style>`, bloco `:root` (dourado `--gold`, grafite `--graphite-2`, creme `--cream`).

## Publicação
GitHub Pages → Settings → Pages → branch `main`, pasta `/ (root)`.
Domínio: `www.belamesa.net.br` (arquivo `CNAME`). No DNS, **não alterar os registros MX/TXT do e-mail**.
