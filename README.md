# 🚀 Landing Page de Moda con Astro

Este proyecto es una **Landing Page moderna para el nicho de moda**, desarrollada utilizando **Astro** para lograr alto rendimiento, SEO optimizado y una arquitectura basada en componentes reutilizables.

La landing está pensada para marcas de moda, boutiques, diseñadores o tiendas online que necesiten una página rápida, elegante y profesional.

---

# 🧠 Tecnologías Utilizadas

Este proyecto utiliza las siguientes tecnologías:

- **Astro** → Framework principal para generación de sitios rápidos.
- **HTML5** → Estructura del contenido.
- **CSS3** → Estilos personalizados y diseño responsive.
- **JavaScript Vanilla** → Interacciones ligeras sin librerías pesadas.
- **Componentes `.astro`** → Arquitectura modular reutilizable.

---

# 📁 Estructura del Proyecto

```text
/
├── public/                  
│   └── images/              # Imágenes, logos y recursos estáticos
│
├── src/
│   ├── components/          # Componentes reutilizables
│   │   ├── Navbar.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── Gallery.astro
│   │   ├── Testimonials.astro
│   │   ├── FAQ.astro
│   │   └── Contact.astro
│   │
│   ├── styles/              
│   │   └── global.css       # Estilos globales del proyecto
│   │
│   └── pages/
│       └── index.astro      # Página principal
│
├── astro.config.mjs
├── package.json
└── README.md
