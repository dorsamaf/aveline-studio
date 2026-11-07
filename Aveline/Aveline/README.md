# Aveline Atelier

Elegant weddings & photography studio website.

A clean, semantic, and accessible static website for **Aveline Atelier** — a wedding planning and photography studio.

## Features

- Fully semantic HTML5 structure
- Responsive design (existing CSS)
- Google Fonts (Cormorant Garamond, Montserrat, Allura)
- Consistent navigation across all pages
- Accessibility improvements (ARIA labels, proper headings, form labels)
- Ready for GitHub Pages

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, intro, work preview, contact teaser |
| About | `about.html` | Our story & philosophy |
| Services | `services.html` | Service overview + gallery |
| Work | `ourwork.html` | Portfolio / selected projects |
| Contact | `contact.html` | Enquiry form + team |

## Structure

```
Aveline/
├── index.html
├── about.html
├── services.html
├── ourwork.html
├── contact.html
├── css/
│   ├── style.css
│   └── invitation.css   (optional / unused)
├── images/
│   └── (all assets)
└── README.md
```

## How to use / deploy on GitHub

1. Create a new repository on GitHub (e.g. `aveline-atelier`).
2. Upload or push the contents of this folder to the repository root.
3. Enable **GitHub Pages**:
   - Go to **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`) → `/ (root)`
4. Your site will be available at:
   `https://<username>.github.io/<repo-name>/`

## Local preview

You can open any `.html` file directly in the browser, or use a simple local server:

```bash
# Python
python -m http.server 8000

# or Node
npx serve .
```

Then visit `http://localhost:8000`.

## Notes

- Forms currently use `action="#"` (no backend). Connect them to Formspree, Netlify Forms, or your own endpoint when ready.
- Social links are placeholders (`#`). Replace with real URLs.
- The original CSS is preserved and only lightly cleaned (removed broken background image reference).

---

© 2026 Aveline Atelier
