# Portafolio Web

Portafolio personal desarrollado como proyecto de formación en desarrollo web frontend. Incluye diseño responsivo, interactividad con JavaScript y buenas prácticas de CSS.

---

## Estructura del proyecto

```
portafolio/
├── index.html      
├── mascotas.html   
├── styles.css     
├── style.min.css   
└── script.js        
```

---

## Tareas implementadas

### Tarea 1 — Estructura base
- Se conservaron los archivos `index.html`, `mascotas.html` y `styles.css`.
- Se creó el archivo `script.js` y se enlazó en `index.html` justo antes del cierre de `</body>`.

### Tarea 2 — Media queries (diseño responsivo)
| Dispositivo | Proyectos | Galería | Navegación |
|---|---|---|---|
| 📱 Móvil (`≤ 600px`) | 1 columna | 2 columnas | Vertical (columna) |
| 📟 Tablet (`601px – 1024px`) | 2 columnas | 3 columnas | Normal |
| 🖥️ Escritorio (`> 1024px`) | 3 columnas | 3 columnas | Normal |

### Tarea 3 — Imágenes y texto responsivos
- Regla global aplicada: `img { max-width: 100%; height: auto; }`.
- Todos los tamaños de fuente, padding y margin usan unidades relativas (`rem`, `%`).

### Tarea 4 — Optimización del CSS
- Variables globales definidas en `:root` para colores, tipografía y radios de borde.
- Reglas comunes agrupadas (botones de navegación y de proyectos comparten base).
- Selectores simplificados con clases claras (`.btn-secundario`, `.formulario-grup`, etc.).
- Generado `style.min.css`: versión sin comentarios ni espacios (~35% más ligera).

### Tarea 5 — JavaScript interactivo
Tres interacciones implementadas en `script.js`:

1. **Banner de bienvenida** — aparece automáticamente al cargar la página y puede cerrarse con el botón ✕.
2. **Cambio de texto** — el botón "Leer más sobre mí" alterna el contenido del párrafo de biografía.
3. **Mostrar / ocultar proyectos** — el botón "Ocultar proyectos" colapsa y expande la lista de proyectos dinámicamente.

---

## Cómo usar

1. Descarga o clona los archivos del proyecto.
2. Abre `index.html` en tu navegador (no requiere servidor).
3. Navega entre las secciones: Sobre mí, Proyectos, Contacto y Mascotas.

---

## Tecnologías usadas

- **HTML5** — estructura semántica
- **CSS3** — variables, grid, flexbox, media queries
- **JavaScript (Vanilla)** — manipulación del DOM, eventos

---

##  Autor

**Sayder Junior Carreño Ochoa**  
[GitHub](https://github.com/sayderochoa-gif)