# sublime-sport-pro

Página de ventas de una sola página (HTML + CSS + JS en un solo archivo, sin dependencias).

## Configuración
Abre `index.html` y edita estas dos líneas cerca del final:

```js
const LINK_DE_PAGO = "";   // tu link de Hotmart, Stripe, Mercado Pago…
const WHATSAPP = "";       // número con código de país, solo dígitos (ej. 573001234567)
```

## Pendientes antes de publicar
- Nombre del bono 6
- Testimonios reales (o eliminar la sección marcada `TESTIMONIOS`)
- Métodos de pago, garantía, contacto, términos y privacidad

## Publicar con GitHub Pages
Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
La página queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
