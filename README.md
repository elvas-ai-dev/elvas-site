# elvas-site

Site institucional do ELVAS AI, publicado em https://elvas-ai.com (projeto `site-elvas` na Vercel, time ELVAS).

- Texto: `site-copy-v1.md` (fonte do conteúdo). Página: `index.html`.
- Imagens do conteúdo: `assets/`. Logo original sem alteração: `assets/ELVAS_logo.jpg` (usado como imagem de compartilhamento).
- Visual: `ui/` é uma **cópia** do design system `elvas-principal/packages/ui` (`index.css`, `fonts.css`, `tokens.css`, `components.css` e os logos oficiais de `assets/logos/`), tirada do commit `3eb8726` do `elvas-principal`. Para atualizar, copie de novo esses arquivos; não edite `ui/` à mão.
- `css/site.css`: só a diagramação do site, com `var(--token)`. Títulos maiores que `display` e as faixas de seção são **proposta — fora do design system**.
- Tema escuro, fonte Geist. Funciona em computador, tablet e celular.

Site estático, sem etapa de build. Para ver no computador:

```bash
python3 -m http.server 4173
```

e abra http://localhost:4173.
