# Presentación Interactiva: Gestión de SST y Riesgo Laboral en Obras Viales

Este repositorio contiene la presentación interactiva en formato web (HTML5, CSS3, JavaScript) diseñada para la exposición del informe de investigación académica.

## 📌 Proyecto de Investigación
* **Título**: Gestión de Seguridad y Salud Ocupacional y Nivel de Riesgo Laboral en Obras Viales: Revisión Sistemática
* **Institución**: Universidad César Vallejo (UCV)
* **Escuela**: Escuela Profesional de Ingeniería Civil
* **Asesor**: Mg. Guillen Cabrera, Jaime Jesus
* **Año**: 2026

---

## 🛠️ Estructura del Proyecto

El repositorio está organizado con la siguiente estructura de archivos autocontenidos:

```bash
├── index.html                 # Código principal de la presentación interactiva (Landing Page)
├── README.md                  # Documentación del repositorio (este archivo)
├── .gitignore                 # Configuración para omitir archivos temporales de Git
└── [Imágenes Ilustrativas]
    ├── road_construction_paving.png     # Imagen de portada (pavimentación)
    ├── construction_worker_sun.png      # Imagen de realidad problemática
    ├── methodology_prisma_diagram.png   # Diagrama PRISMA metodológico
    ├── ergonomia_paving.png             # Imagen de ergonomía laboral
    └── foreman_safety_briefing.png      # Imagen de liderazgo preventivo
```

---

## 🚀 Cómo Ejecutar la Presentación Localmente

### Opción 1: Servidor Local (Recomendado)
Debido a las políticas de seguridad de los navegadores web modernos (CORS/acceso a archivos locales), se recomienda levantar un servidor local rápido para garantizar que todas las imágenes y recursos multimedia se carguen sin restricciones.

**Con Python:**
1. Abre una terminal/consola en la carpeta del proyecto.
2. Ejecuta el comando:
   ```bash
   python -m http.server 8080 --bind 127.0.0.1
   ```
3. Abre tu navegador e ingresa a: **`http://localhost:8080/index.html`**

**Con Node.js (npx):**
1. Ejecuta en tu terminal:
   ```bash
   npx serve .
   ```
2. Abre la URL que te indique la terminal (por defecto `http://localhost:3000`).

### Opción 2: Doble Clic directo
Puedes abrir el archivo `index.html` directamente haciendo doble clic desde el explorador de archivos en tu navegador favorito, aunque algunas configuraciones estrictas de seguridad de Chromium podrían limitar la carga de ciertos elementos si no se sirve desde un dominio local (`http://localhost`).

---

## ⌨️ Controles de Navegación

La presentación cuenta con controles interactivos integrados:
* **Flecha Derecha `→` / Barra Espaciadora / Enter**: Diapositiva Siguiente.
* **Flecha Izquierda `←` / Backspace**: Diapositiva Anterior.
* **Tecla `F`**: Activar / Desactivar pantalla completa.
* **Doble clic en el botón de pantalla completa (esquina inferior derecha)**: Activa el modo maximizado alternativo en caso de que esté incrustado dentro de plataformas externas (como un iframe en Canva).

---

## 🎨 Características Técnicas
* **Diseño Premium**: Paleta de colores en Dark Mode optimizada para alta fidelidad visual en proyectores y pantallas, usando tonos HSL cian (`#00C2D1`).
* **Tipografías de Vanguardia**: Outfit (para encabezados de alto impacto) e Inter (para legibilidad del cuerpo académico).
* **Gráficos en Código Puro**: Donut Charts dinámicos y flujogramas en SVG nativo para asegurar tiempos de carga ultra-rápidos sin pérdida de resolución.
* **Identidad Institucional**: SVG de alta resolución embebido para el isotipo de la Universidad César Vallejo (UCV).
