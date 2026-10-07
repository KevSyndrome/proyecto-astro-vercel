# Proyecto Astro + Vercel

Sitio de práctica para la Unidad 2 (Control de versiones).

## Uso local

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # genera /dist
```

## Flujo de trabajo

- `main`: rama estable. Vercel la despliega automáticamente.
- `feature/*`: ramas de trabajo. Se unen a `main` mediante Pull Request.
- GitHub Actions compila el sitio en cada Pull Request.
