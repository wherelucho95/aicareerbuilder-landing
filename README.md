# aicareerbuilder-landing

Landing page SEO estática del apex **aicareerbuilder.app** (hero, features, pasos, CTA, OG tags, JSON-LD).

- **Deploy:** Netlify, auto desde `main` (publish = raíz). Público para tener auto-deploy gratis.
- **Páginas legales** (`/terminos`, `/privacidad`, `/reembolsos`): `terminos.html`, `privacidad.html` y `reembolsos.html` se generan desde los Markdown de la carpeta `legal/` del workspace con `legal/build_landing_pages.py`. No se editan a mano: se cambia el Markdown y se regeneran.
- **La app real** (Streamlit, análisis de CV) vive en `app.aicareerbuilder.app` → Railway, en el repo privado `ai-career-builder`.

> Fuente única del landing: este repo. Los cambios del landing van acá, no al `docs/` del repo de la app.
