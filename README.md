# elvas-site

Site institucional do ELVAS AI, publicado em https://elvas-ai.com (projeto `site-elvas` na Vercel, time ELVAS).

- Texto: `site-copy-v1.md` (fonte do conteúdo). Página: `index.html`.
- Imagens do conteúdo: `assets/`. Logo original sem alteração: `assets/ELVAS_logo.jpg` (usado como imagem de compartilhamento).
- Visual: `ui/` é uma **cópia** do design system `elvas-principal/packages/ui` (`index.css`, `fonts.css`, `tokens.css`, `components.css` e os logos oficiais de `assets/logos/`), tirada do commit `3eb8726` do `elvas-principal`. Para atualizar, copie de novo esses arquivos; não edite `ui/` à mão.
- `css/site.css`: cores, fontes e componentes do design system do app, com `var(--token)`. A escala de títulos de página de vendas e os blocos de destaque da copy (frases em vermelho, números grandes, contraste "sem evidência × com o ELVAS") são **proposta — fora do design system**. O texto é sempre o do `site-copy-v1.md`, sem mudanças.
- Tema escuro, fonte Geist. Funciona em computador, tablet e celular.

Site estático, sem etapa de build. **Ao mudar qualquer CSS, troque o `?v=` dos dois `<link rel="stylesheet">` do `index.html`** (ex.: `?v=20261123-2`), para o navegador não usar a cópia antiga guardada. Para ver no computador:

```bash
python3 -m http.server 4173
```

e abra http://localhost:4173.
