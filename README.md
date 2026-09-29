# JR/ Obras e reformas 01: site para GitHub Pages

## Publicar
1. Crie um repositório no GitHub (ex.: `jr-obras`) e envie **todo o conteúdo desta pasta** para a raiz (inclusive `.nojekyll` e `CNAME`).
2. No repositório: **Settings > Pages > Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, pasta `/ (root)`.
3. Em **Custom domain** confirme `jrconstrucoes01.com.br` e marque **Enforce HTTPS** quando liberar.

## Domínio (DNS, no Registro.br ou onde registrou)
- Registros `A` para `jrconstrucoes01.com.br` apontando para os IPs do GitHub Pages (confira a lista atual na documentação do GitHub Pages: docs.github.com/pages, "Managing a custom domain").
- `CNAME` de `www` apontando para `SEU-USUARIO.github.io`.
- A propagação pode levar de minutos a algumas horas.

## Depois de publicar
- Teste o formulário em `https://jrconstrucoes01.com.br`. Se ativou a lista de domínios no Formspree, inclua esse domínio.
- Confira `/robots.txt`, `/sitemap.xml` e `/og-image.jpg`.
- Cadastre o site no Google Search Console e envie o `sitemap.xml`.

## Observações
- As páginas internas usam endereços com `#` (ex.: `/#/servicos`), pois o GitHub Pages não reescreve URLs. Por isso o `sitemap.xml` lista só a página inicial.
- Edite dados no `CFG`, no início do script do `index.html`: `prazo`, `addr`, `social`, `dev`, `projetos`.
- Antes de divulgar: confirme o telefone (41) 99169-925, troque as imagens por fotos reais e revise a política de privacidade.
