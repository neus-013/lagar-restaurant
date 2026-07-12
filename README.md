# Lagar Restaurant — proyecto (estructura inicial)

Proyecto Astro para la web del restaurante Lagar. Web sencilla, estática,
sin CMS y sin gestión online de reservas (solo por teléfono).

## Estructura

```
lagar-restaurant/
├── astro.config.mjs
├── package.json
├── public/
│   └── images/          → imágenes del restaurante (fotos de platos, local, equipo...)
└── src/
    ├── layouts/
    │   └── BaseLayout.astro   → estructura común (html/head + Header + Footer + slot)
    ├── components/
    │   ├── Header.astro       → menú de navegación (Carta, Galería, Sobre Nosotros, Reserva)
    │   └── Footer.astro       → horario, contacto y enlaces legales
    ├── pages/
    │   ├── index.astro            → Home
    │   ├── galeria.astro          → Galería
    │   ├── sobre-nosotros.astro   → Sobre Nosotros
    │   └── reserva.astro          → Reserva
    └── styles/
        └── global.css      → variables globales de color y tipografía (control centralizado)
```

## Pendiente

- Ninguna página tiene aún diseño ni contenido, solo el "esqueleto" con comentarios
  indicando qué irá en cada archivo.
- Sin definir aún: paleta de colores y tipografías concretas en `global.css`.
- Nota: en el menú de las imágenes aparece un enlace "CARTA" pero no se ha
  proporcionado ninguna imagen de esa página — a confirmar si se añade o se
  enlaza a un PDF/externo.
