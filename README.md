# ⚗️ Leyes del Gas Ideal — Laboratorio Virtual

App web interactiva para estudiantes de 5to año de secundaria (15-16 años) para experimentar con las leyes del estado gaseoso.

## 🧪 Contenido

- **Ley de Boyle** — Relación P-V a temperatura constante
- **Ley de Charles** — Relación V-T a presión constante
- **Ley de Gay-Lussac** — Relación P-T a volumen constante
- **Ley Combinada** — Las tres leyes en una ecuación
- **Quiz interactivo** — 10 preguntas con retroalimentación

## 🚀 Deploy en Netlify desde GitHub

### Opción 1 — Arrastrar y soltar (más fácil)
1. Sube esta carpeta a [netlify.com/drop](https://netlify.com/drop)

### Opción 2 — GitHub + Netlify (recomendado)
1. Sube este repositorio a GitHub
2. Ve a [app.netlify.com](https://app.netlify.com)
3. Haz clic en **"Add new site" → "Import an existing project"**
4. Conecta tu cuenta de GitHub
5. Selecciona este repositorio
6. En **Build settings**:
   - Build command: *(dejar vacío)*
   - Publish directory: `.`
7. Haz clic en **"Deploy site"**

¡Listo! Netlify detecta el `netlify.toml` automáticamente.

## 🛠 Tecnología

- HTML5 + CSS3 + JavaScript puro (sin frameworks ni dependencias)
- Sin backend — funciona como sitio estático
- Responsive para móvil y escritorio

## 📁 Estructura

```
gas-laws-app/
├── index.html       ← App completa (todo en un archivo)
├── netlify.toml     ← Configuración de Netlify
├── _redirects       ← Rutas para SPA
└── README.md        ← Este archivo
```
