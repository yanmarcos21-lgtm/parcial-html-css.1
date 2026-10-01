# Taller práctico tipo parcial – G611 – 2026

Página web que reproduce el diseño entregado por el profesor usando HTML semántico y CSS externo.

## Estructura

```
├── index.html
├── styles.css
├── assets/
│   └── industrial.svg
└── README.md
```

## Requisitos cumplidos

- **HTML semántico:** `header`, `nav`, `main`, `section`, `article`, `figure`, `footer`.
- **Etiquetas de formulario, imagen, botones y tablas:** `form`, `label`, `input`, `textarea`, `button`, `img`, `table` (`caption`, `thead`, `tbody`, `tfoot`).
- **Accesibilidad:**
  - `lang` en `<html>` y `alt` descriptivo en cada imagen.
  - Enlace "Skip to main content" para usuarios de teclado.
  - Cada campo con `label` asociado (`for`/`id`), `required` y `autocomplete`.
  - `aria-label` en la navegación y `aria-labelledby` en las secciones.
  - Tabla con `scope` en encabezados y `caption` para lectores de pantalla.
  - Foco visible (`:focus-visible`), buen contraste y `prefers-reduced-motion`.
- **CSS externo básico** (`styles.css`) similar al diseño de la imagen, con diseño responsive.

## Cómo ver el proyecto

Abrir `index.html` en el navegador.
