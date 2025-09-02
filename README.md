# ARQ Portfolio

High-performance animated portfolio for Anmol Sharma (brand alias: **ARQ**) featuring:

- Curtain intro, glitch typography & orbiting particles
- Dynamic role carousel & responsive navigation
- Skills particle cloud, timeline, projects, multilingual cards
- Theme toggle (dark / light) with localStorage persistence
- Accessible, semantic HTML structure and reduced‑motion support
- Client-side image upload for profile photo
- Lightweight custom canvas background (no heavy libraries)

## Structure
```
index.html      # Semantic markup
styles.css      # Design system + animations
script.js       # Interactivity & canvas background
assets/img/     # Images (add profile photo, logo, etc.)
```

## Customization
1. Replace `assets/img/profile-placeholder.png` with your photo (same filename or update `index.html`).
2. Adjust brand alias (ARQ) if needed: search `ARQ` in all files.
3. Add more projects: duplicate a `.project-card` in `#projects`.
4. Change accent colors: edit `--accent` & `--accent-alt` in `:root`.

## Deployment
Deploy statically (GitHub Pages / Netlify / Vercel). No build step required.

## Accessibility
- Proper aria labels and focusable controls
- Motion reduced for `prefers-reduced-motion`
- Color contrast targeted for WCAG AA

## License
You own your resume data & brand. Code provided under MIT-like permission (personal use, attribution appreciated).
