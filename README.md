# Site do Dr. Thiago Camargo Moreira

Site estático (HTML, CSS e JS, sem build) para `drthiagomoreira.com.br`.

| Pasta | O que tem | Vai ao ar? |
|---|---|---|
| `site/` | Tudo o que é publicado: `index.html`, `privacidade.html`, `404.html`, fontes, ícones, `og.png`, `robots.txt`, `sitemap.xml`, `llms.txt` | Sim |
| `projeto/` | Briefing (`PROJETO.md`), prompts das dobras, auditoria | Não |
| `design/` | Design system Pulso e versões, mídias brutas, templates de referência | Não |

O deploy é feito pelo GitHub Actions (`.github/workflows/pages.yml`), que publica só a pasta `site/`.

Testar localmente: `python -m http.server 8767 -d site` e abrir `http://localhost:8767`.

Ao publicar uma página nova, incluir a URL no `site/sitemap.xml` e no `site/llms.txt`.
