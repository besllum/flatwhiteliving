# Flat White Living — website mockup

Bespoke interior design & project management · Elisa Vives · The Hague, Netherlands.
Static HTML mockup built from the brief *Flat White Living — Website Structure, SEO Strategy & Final Copy (v2)*. Copy is the final English copy from that brief.

## Pages

| File | Page | Intended URL |
| --- | --- | --- |
| `index.html` | Entry redirect | `/` |
| `Flat White Living - Home.dc.html` | Home | `/` |
| `services.dc.html` | Services (5 services, anchored) | `/services/` |
| `international-clients.dc.html` | For International Clients | `/international-clients/` |
| `about.dc.html` | About | `/about/` |
| `how-it-works.dc.html` | How It Works | `/how-it-works/` |
| `projects.dc.html` | Projects landing | `/projects/` |
| `project-refined-family-home.dc.html` | Project case-study template | `/projects/<slug>/` |
| `journal.dc.html` | Journal landing | `/journal/` |
| `contact.dc.html` | Contact + enquiry form | `/contact/` |

## Design system

Classical — editorial serif system (Cormorant Garamond / Lora), light ground, hairline rules, outlined buttons. Tokens and component classes in `_ds/classical-b2b163c1-a1f3-4dff-a207-2d656b620969/styles.css`. Take all colour, type and spacing from those `var(--*)` tokens.

## Local use

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server
```

## Still to do before launch

- Real photography. Hero images use `<image-slot>` (drag-and-drop placeholders); the rest are neutral "Foto pendiente" blocks.
- Contact email address — set the `email` prop on `contact.dc.html`.
- Wire the enquiry form to a secure (HTTPS) form service.
- Replace the sample project titles with 4–6 real case studies.
- Write the Journal articles (titles present are the editorial plan, not published posts).
- Per-page SEO titles/meta descriptions and structured data, per §11–12 of the brief.
- Optional Dutch version, hand-written (see §12, language strategy).
