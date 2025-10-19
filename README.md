# Academic CV Website — Cleque Marlain Mboulou‑Moutoubi

Static website (single `index.html`) with Tailwind CDN, auto dark mode + manual toggle, and a basic contact form.

## Deploy on GitHub Pages

1. Create a **new public repository** (e.g. `clequemarlain-website`).
2. Put `index.html` at the root of the repo.
3. Go to **Settings → Pages → Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** (/**root**)
4. Your site will be available at `https://<user>.github.io/<repo>/`.

## Customize

- Replace the **CV link** (`Télécharger le CV (PDF)`) with your file (e.g. `cv_Cleque_Marlain.pdf`) and commit it in the repo.
- Update links (GitHub, Scholar, DBLP, LinkedIn) directly in `index.html`.
- Contact form uses **mailto:** by default. For a no‑backend solution:
  - Use **Formspree**: change the `<form action="...">` to your Formspree endpoint.
  - Or **Netlify Forms**: add `netlify` attribute and deploy on Netlify.

## Structure

```
/
├── index.html
├── assets/
│   └── .gitkeep
└── README.md
```

— Generated on 2025-10-19
