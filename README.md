# Visual Contrastive Self-Distillation (VCSD) — Project Page

Project page for **Visual Contrastive Self-Distillation (VCSD)**.

This is a static page — just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000    # then visit http://localhost:8000/
```

## Structure

```
index.html            # all page content (edit here)
static/
├── css/              # Bulma + template styles
├── js/               # template scripts (carousel, copy-bibtex, scroll-to-top)
└── images/           # figures (fig1_teaser, fig2_method, fig3_ablation, fig4_dynamics)
```

## Before publishing — fill in the TODOs in `index.html`

- Paper / arXiv / Code button links (`href="#"` placeholders in the hero).
- Deployed URL in the Open Graph / Twitter meta tags (currently `https://joliang17.github.io/VCSD/`).
- Update the BibTeX block once a canonical citation exists.

## Deploy (GitHub Pages)

Push to the repo and enable Pages (Settings → Pages → Deploy from branch). The
`.nojekyll` file is already included so `static/` is served as-is.

---

Built with the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(adopted from [Nerfies](https://nerfies.github.io)). Licensed under
[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
