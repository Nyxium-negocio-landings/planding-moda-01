🚀 Proyecto Landing Page Moda con Astro

Este proyecto es una landing page profesional para el nicho de moda, desarrollada con Astro, enfocada en alto rendimiento, diseño moderno y experiencia de usuario premium.

🧠 Tecnologías utilizadas
Astro → Framework principal (renderizado estático ultra rápido)
HTML5 + CSS3 → Estructura y estilos personalizados
JavaScript Vanilla → Interacciones ligeras (sin librerías pesadas)
Arquitectura de componentes (.astro) → Reutilización y organización limpia
📁 Estructura del proyecto
/
├── public/                  # Recursos estáticos (imágenes, íconos, etc.)
│
├── src/
│   ├── components/          # Componentes reutilizables
│   │   ├── Testimonials.astro
│   │   ├── FAQ.astro
│   │   ├── Navbar.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── Gallery.astro
│   │   └── Contact.astro
│   │
│   ├── styles/              # Estilos globales o modularizados
│   │   └── global.css
│   │
│   └── pages/
│       └── index.astro      # Página principal (landing)
│
├── package.json
└── astro.config.mjs
