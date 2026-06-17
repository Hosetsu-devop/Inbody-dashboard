# InBody Dashboard PWA — Instrucciones de instalación

## ¿Qué es esto?
Una Progressive Web App (PWA) con tu historial completo de InBody.
Se instala en iPhone como si fuera una app nativa, funciona offline,
y guarda los datos directamente en tu teléfono.

---

## Paso 1 — Sube el código a GitHub (gratis)

1. Ve a **github.com** → crea una cuenta si no tienes
2. Haz clic en **"New repository"**
3. Nómbralo: `inbody-dashboard`
4. Marca **Public** → **Create repository**
5. Arrastra los archivos de esta carpeta al repositorio:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `vercel.json`
   - carpeta `icons/` completa

---

## Paso 2 — Deploy en Vercel (gratis, 2 minutos)

1. Ve a **vercel.com** → "Sign up with GitHub"
2. Haz clic en **"Add New Project"**
3. Importa tu repositorio `inbody-dashboard`
4. Haz clic en **Deploy** (sin cambiar nada)
5. En ~30 segundos tendrás una URL tipo: `https://inbody-dashboard-xxx.vercel.app`

---

## Paso 3 — Instalar en iPhone

1. Abre Safari en tu iPhone
2. Ve a tu URL de Vercel
3. Toca el botón **Compartir** (cuadro con flecha ↑)
4. Desplázate y toca **"Añadir a pantalla de inicio"**
5. Nómbrala "InBody" → **Añadir**

¡Listo! Tendrás el ícono en tu pantalla de inicio como una app real.

---

## Características
- ✅ Funciona offline (datos guardados en el teléfono)
- ✅ Todos tus datos históricos ya incluidos (Mar 2025 – Abr 2026)
- ✅ Importar nuevos InBody pegando JSON desde Claude
- ✅ Gráficos, proyecciones, comparativas
- ✅ Navegación con barra inferior estilo iOS
- ✅ Respeta las safe areas del iPhone (notch, home indicator)

## Alternativa más simple: GitHub Pages

En vez de Vercel, puedes usar GitHub Pages directamente:
1. Sube los archivos al repositorio
2. Ve a Settings → Pages → Source: main branch
3. Tu URL será: `https://TU_USUARIO.github.io/inbody-dashboard`
