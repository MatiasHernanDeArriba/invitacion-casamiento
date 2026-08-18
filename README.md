# 💍 Invitación de casamientos personalizados web

Invitación digital para bodas, hecha como proyecto de portfolio. Simula el tipo de producto que ofrecen plataformas como [noscasamos.ar](https://noscasamos.ar) o [amoinvitar.com](https://amoinvitar.com), pero construida desde cero, con código propio y publicada como demo técnica.

## 🎯 Objetivo

Mostrar en el portfolio de GitHub un proyecto real, prolijo y con "chiches" técnicos (animaciones, countdown en vivo, formularios, integraciones) que sirva como pieza de muestra frente a reclutadores o clientes.

## 🛠️ Stack

- **Astro** — genera HTML estático, carga rápida (clave para un link que se comparte por WhatsApp), arquitectura de islas para usar JS solo donde hace falta
- **HTML / CSS** — estructura y estilos
- **JavaScript vanilla** — countdown, animaciones al scroll, interacciones (sin librerías pesadas)
- Deploy gratuito en Vercel / Netlify / GitHub Pages

## ✨ Funcionalidades

- [ ] Hero con nombres de la pareja + fecha + cuenta regresiva en vivo
- [ ] Efecto "sobre que se abre" como intro
- [ ] Historia de la pareja (timeline con scroll reveal)
- [ ] Detalles del evento (ceremonia / fiesta, mapa embebido)
- [ ] Dress code
- [ ] RSVP (formulario de confirmación de asistencia)
- [ ] Galería de fotos con lightbox
- [ ] Lista de regalos / datos bancarios (con toggle mostrar/ocultar)
- [ ] Playlist sugerida (embed de Spotify)
- [ ] Preguntas frecuentes
- [ ] Música de fondo con botón play/mute
- [ ] Confetti / pétalos animados
- [ ] Open Graph tags para que el link se vea bien al compartir
- [ ] Responsive mobile-first

## 📁 Estructura del proyecto

```
src/
  components/
    Hero.astro
    Countdown.astro
    Timeline.astro
    RSVP.astro
    Gallery.astro
  layouts/
    Layout.astro
  pages/
    index.astro
  styles/
    global.css
public/
  images/
```

## 🚀 Cómo correrlo localmente

```bash
npm install
npm run dev
```

## 📚 Referencias

Proyectos existentes del mismo rubro usados como inspiración de estructura y features:
- [noscasamos.ar](https://noscasamos.ar)
- [amoinvitar.com](https://amoinvitar.com)

## 📝 Estado

🚧 En construcción — proyecto personal en desarrollo 2026.
