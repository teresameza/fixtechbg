# fixtechbg
# FixTech BQ — Sitio Web Oficial

Sitio web de soporte técnico a domicilio para hogares y empresas en Barranquilla, Colombia.

**Demo en vivo:** [spontaneous-marshmallow-8e15eb.netlify.app](https://spontaneous-marshmallow-8e15eb.netlify.app)

---

##  Estructura del proyecto

```
fixtech-bq/
│
├── index.html          # Página principal (toda la estructura HTML)
├── fixtech-bq.css      # Estilos globales del sitio
├── politica.html       # Página de política de tratamiento de datos
│
└── img/
    └── videoprincipal.mp4   # Video de fondo (hero y sección Nosotros)
```

---

##  Secciones del sitio

| Sección | ID en HTML | Descripción |
|---|---|---|
| Navegación | `nav` | Fija en la parte superior, con scroll effect |
| Hero | `#inicio` | Portada con video de fondo y llamada a la acción |
| Estadísticas | `.stats-strip` | Franja con 3 datos clave |
| Servicios | `#servicios` | Carrusel 3D con 5 servicios |
| Nosotros | `#nosotros` | Video + features + contadores animados |
| Testimonios | `#testimonios` | 4 reseñas de clientes |
| Contacto | `#contacto` | Info de contacto + formulario |
| Footer | `footer` | Links, redes sociales e info de contacto |

---

##  Tecnologías usadas

| Herramienta | Uso | Link |
|---|---|---|
| HTML5 + CSS3 | Estructura y estilos | — |
| GSAP 3.12.2 | Animaciones de scroll | [cdnjs](https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js) |
| ScrollTrigger | Plugin de GSAP para scroll | [cdnjs](https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js) |
| Google Fonts | Space Grotesk + DM Sans | [fonts.google.com](https://fonts.google.com) |
| Formspree | Envío del formulario de contacto | [formspree.io](https://formspree.io) |
| Unsplash | Imágenes del carrusel de servicios | [unsplash.com](https://unsplash.com) |
| Flaticon | Ícono del botón de WhatsApp | [flaticon.com](https://flaticon.com) |
| Netlify | Hosting y despliegue | [netlify.com](https://netlify.com) |

---

##  Formulario de contacto (Formspree)

El formulario envía los datos a través de **Formspree**.

- **ID del formulario:** `xovdjbzy`
- **URL de acción:** `https://formspree.io/f/xovdjbzy`
- **Correo destino:** fixtechbq@gmail.com
- **Campos:** nombre, teléfono, email, tipo de servicio, descripción del problema
- **Requerido por ley:** checkbox de aceptación de datos personales (Ley 1581 de 2012)

> Para cambiar el correo destino, entra a [formspree.io](https://formspree.io) con la cuenta vinculada.

---

##  Datos de contacto hardcodeados

Si cambias el número o correo, búscalos y reemplázalos en estos archivos:

| Dato | Valor actual | Dónde está |
|---|---|---|
| WhatsApp (botón flotante) | `3239632169` | `index.html` línea del `<a href="https://wa.me/...">` |
| WhatsApp (footer social) | `3239632169` | `index.html` sección footer |
| Teléfono visible | `323 963 2169` | `index.html` sección `#contacto` |
| Email visible | `fixtechbq@gmail.com` | `index.html` sección `#contacto` y footer |

---

##  Variables CSS principales

Definidas en `:root` dentro de `fixtech-bq.css`:

```css
--dark:       #0A2540   /* Fondo principal */
--dark2:      #0d1526   /* Fondo alterno (nosotros, testimonios) */
--dark3:      #111b32   /* Fondo sección contacto */
--blue:       #4D90FF   /* Azul principal (botones, íconos) */
--blue-light: #3b82f6   /* Azul claro (hover, tags) */
--cyan:       #00C2FF   /* Acento cyan (títulos, barras) */
--text-muted: #F1F5F9   /* Texto secundario */
--border:     rgba(59,130,246,0.15)  /* Bordes suaves */
```

---

## 🖼️ Imágenes del carrusel (Unsplash)

| Card | Servicio | URL |
|---|---|---|
| 01 | Mantenimiento | `photo-1518770660439-4636190af475` |
| 02 | Formateo | `photo-1629654297299-c8506221ca97` |
| 03 | Redes Wi-Fi | `photo-1558494949-ef010cbdcc31` |
| 04 | Soporte remoto | `photo-1600132806370-bf17e65e942f` |
| 05 | Asesoría equipos | `photo-1551288049-bebda4e38f71` |

Para cambiar una imagen reemplaza el ID después de `unsplash.com/photo-` manteniendo `?w=700&q=80`.

---

## 🚀 Cómo desplegar en Netlify

1. Sube los archivos a un repositorio de GitHub
2. Entra a [netlify.com](https://netlify.com) → **Add new site** → **Import from Git**
3. Selecciona el repositorio
4. En **Publish directory** deja la raíz (`/`)
5. Haz clic en **Deploy site**

Netlify detecta automáticamente `index.html` en la raíz.

---

## 📋 Cumplimiento legal (Colombia)

- Aviso de tratamiento de datos personales según **Ley 1581 de 2012**
-  Checkbox de consentimiento obligatorio antes de enviar el formulario
- Enlace a `politica.html` con la política completa de tratamiento de datos

---

## 👤 Autor

**FixTech BQ**
- 📧 fixtechbq@gmail.com
- 📱 323 963 2169
- 📍 Barranquilla, Colombia
- 🕐 Lunes a Sábado, 8am – 6pm

---

*© 2026 FixTech BQ. Todos los derechos reservados.*
