# Ferrelaza Chalchihuites — Landing page

Landing page premium, responsive y de un solo archivo para **Ferrelaza Chalchihuites**, la ferretería familiar de Chalchihuites, Zacatecas (fundada en 2002).

> _"Una empresa familiar con un trato familiar."_

El sitio destaca el diferenciador principal del negocio: **surtir material de construcción por volumen** a toda la región, además de ferretería general, boilers solares, taller de soldadura y pago de remesas.

---

## ✨ Qué incluye

- **Un solo archivo** (`index.html`). No necesita build ni instalación: Tailwind CSS se carga por CDN y las fuentes desde Google Fonts.
- **8 secciones**: navegación flotante, hero, el problema, solución/servicios, nosotros (misión, visión y valores), testimonios con métricas reales, formas de comprar, preguntas frecuentes (acordeón) y footer con datos de contacto.
- **Julis, la mascota** 🧱 — una bolsa de cemento kawaii dibujada en SVG que se pasea por la página dando consejos con datos reales del negocio. Al cambiar de lugar **se hace polvo** (efecto de partículas de cemento en `<canvas>`) y se materializa en su nueva posición. Se puede cerrar con la "×" y respeta `prefers-reduced-motion`.
- **Animaciones**: aparición al hacer scroll (IntersectionObserver), marquee de marcas, micro-interacciones y menú móvil animado.
- **Colorimetría**: base oscura, rojo de marca (#E11B22) y blanco cálido, con tipografías Archivo (display), Plus Jakarta Sans (texto) y Space Grotesk (detalles).
- **Botón flotante de WhatsApp** siempre visible.

---

## 🚀 Cómo verlo

Abre `index.html` en cualquier navegador moderno. Eso es todo.

Para servirlo localmente (opcional):

```bash
# con Python
python3 -m http.server 8000
# luego abre http://localhost:8000
```

---

## 🌐 Publicar en GitHub Pages

1. Sube estos archivos a un repositorio de GitHub.
2. Ve a **Settings → Pages**.
3. En **Source** elige la rama `main` y la carpeta `/ (root)`.
4. Guarda. En unos minutos tu sitio estará en `https://<usuario>.github.io/<repositorio>/`.

Como todo vive en `index.html`, no hace falta ningún paso de compilación.

---

## 📇 Datos del negocio (ya integrados en el sitio)

- **Dirección:** Calle Arista #106, Col. Centro, Chalchihuites, Zacatecas, C.P. 99260
- **Teléfono / WhatsApp:** 675 105 7603 (también 457 104 0446)
- **Correo:** ferrelaza7@hotmail.com
- **Facebook:** https://www.facebook.com/p/Ferrelaza-Chalchihuites-100040720813790/
- **Horario:** abierto, cierra 7:30 pm
- **Calificaciones:** 4.4★ en Google (14 opiniones) · 5/5 en Facebook · +959 seguidores

---

## ⚠️ Notas para personalizar

- **Testimonios:** los tres testimonios de texto son **representativos** (marcados con un comentario `TODO` en el HTML y una nota visible bajo la sección). Sustitúyelos por reseñas verificadas reales de Google/Facebook cuando las tengas. Las métricas (4.4★, 5/5, +959, 2002) sí son reales.
- **Logos de marcas:** las marcas ancla (Cemento Moctezuma, Truper, Coflex, Dexter, IPESA Pinturas) se muestran como **texto** en el carrusel para no reproducir marcas registradas sin autorización. Si cuentas con permiso/los archivos oficiales, colócalos en `assets/` y reemplaza el texto por las imágenes.
- **Logo y mascota:** el logo del pájaro y Julis están recreados en SVG para poder animarlos. Si prefieres el logo oficial en imagen, súbelo a `assets/` y reemplázalo en el `<header>` y el favicon.
- **Precios:** el sitio no muestra precios; invita a cotizar por WhatsApp. Ajusta los enlaces `wa.me` si cambias de número.

---

## 🛠️ Estructura

```
.
├── index.html      # todo el sitio (HTML + CSS + JS en un solo archivo)
├── assets/         # para logos oficiales / imágenes propias (opcional)
├── README.md
└── .gitignore
```

---

Hecho con cariño para una empresa familiar. 🧱❤️
