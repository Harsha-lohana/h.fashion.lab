# h.fashion.lab — Website

## Folder Structure
```
/
├── index.html          ← Home page
├── designs.html        ← Designs gallery page
├── data/
│   └── designs.json    ← Design metadata (update with your info)
└── assets/
    └── designs/
        ├── princess/   ← Add princess collection images here (1.jpg, 2.jpg ...)
        ├── indian/     ← Add Indian collection images here
        └── atelier/    ← Add Atelier collection images here
```

## Adding Your Designs

1. Add image files to the matching folder (JPG/PNG/WEBP)
   - Name them: 1.jpg, 2.jpg, 3.jpg etc.
   
2. Update `data/designs.json` with your design names and descriptions

3. The website auto-detects if an image exists — if not, it shows an elegant placeholder

## Collections
- **Princess** → `assets/designs/princess/`
- **Indian** → `assets/designs/indian/`
- **Atelier** (renamed from Misc) → `assets/designs/atelier/`

## Deploy on GitHub Pages
1. Push all files to a GitHub repository
2. Go to Settings → Pages → Branch: main → Save
3. Your site is live at `https://yourusername.github.io/repo-name`
