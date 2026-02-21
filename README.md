# Workspace Landings

Workspace para crear y gestionar landing pages con Astro + Tailwind + GSAP.

## Stack Preferido

- **Framework:** Astro (para landings estáticas - HTML puro, ultra-rápido)
- **Styling:** Tailwind CSS
- **Animations:** GSAP (GreenSock)
- **Deployment:** Vercel / Netlify / Cloudflare Pages

## Estructura

Cada landing en su propia carpeta con nombre descriptivo:

```
workspace-landings/
├── landing-ejemplo/
│   ├── src/
│   ├── public/
│   ├── astro.config.mjs
│   └── package.json
└── README.md
```

## Workflow

1. Crear nueva landing con Astro CLI
2. Configurar Tailwind + GSAP
3. Desarrollar con `npm run dev`
4. Build con `npm run build`
5. Deploy a hosting estático

## Notas

- Siempre usar Astro para landings (no Next.js)
- Tailwind CSS v4 con `@import "tailwindcss"`
- GSAP para animaciones profesionales
- Imágenes optimizadas localmente en `public/images/`
