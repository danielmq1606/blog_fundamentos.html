# HTML Fundamentos

Proyecto de ejemplo para practicar conceptos básicos de HTML, estructura de archivos y gestión de activos (imágenes y fotos).

## Descripción

Este repositorio contiene archivos de ejemplo para aprender y practicar HTML estático. Incluye una página principal (`blog.html`), notas de trabajo (`notes.txt`) y carpetas para imágenes y fotos. El objetivo es servir como plantilla mínima para proyectos front-end estáticos y ejercicios educativos.

## Estructura del proyecto

- `blog.html` - Página HTML principal del proyecto.
- `notes.txt` - Notas y apuntes del autor.
- `fotos/` - Carpeta para fotos; actualmente contiene `fotos.txt`.
- `fotos/fotos.txt` - Lista o metadatos de fotos (archivo de ejemplo).
- `imagenes/` - Carpeta para imágenes usadas en el proyecto.
- `.gitignore` - Reglas para ignorar archivos en git.

> Si falta alguna carpeta o archivo, puedes crearla según lo necesites. Mantén los activos (imágenes) dentro de `imagenes/` o `fotos/`.

## Requisitos

- Un navegador web moderno (Chrome, Edge, Firefox, Safari).
- Para servir localmente: Python 3 o Node.js (opcional).

## Cómo ver el proyecto localmente

1. Abrir directamente en el navegador:

   - Navega al directorio del proyecto y abre `blog.html` con doble clic.

2. Servir con Python 3 (recomendado para evitar problemas de rutas relativas):

```bash
python -m http.server 8000
```

Luego abre `http://localhost:8000/blog.html` en tu navegador.

En Windows PowerShell puedes abrir la URL así:

```powershell
Start-Process "http://localhost:8000/blog.html"
```

3. Servir con `serve` (Node.js) si tienes Node instalado:

```bash
npx serve .
```

## Flujo de trabajo y edición

- Edita `blog.html` con tu editor favorito (VS Code, Sublime, Atom, etc.).
- Añade imágenes a `imagenes/` y referencia con rutas relativas desde `blog.html`.
- Mantén contenidos estáticos separados: HTML en la raíz, imágenes en `imagenes/`, fotos en `fotos/`.

## Buenas prácticas recomendadas

- Usa etiquetas semánticas (`<header>`, `<main>`, `<article>`, `<footer>`) para mejorar accesibilidad y SEO.
- Añade atributos `alt` descriptivos a todas las imágenes.
- Optimiza imágenes (herramientas como `imagemin`, `squoosh` o servicios online) para reducir el tamaño y mejorar la carga.
- Valida tu HTML con el validador del W3C cuando hagas cambios importantes.

## Accesibilidad y SEO (sugerencias)

- Comprueba el contraste de colores y el tamaño de fuente.
- Usa `lang="es"` en la etiqueta `<html>` para indicar el idioma.
- Incluye metadatos básicos (`<title>`, `<meta name="description">`).

## Control de versiones

- Añade las rutas o patrones que quieras ignorar en `.gitignore` (por ejemplo, archivos temporales del editor, builds, etc.).
- Haz commits pequeños y con mensajes claros: `git commit -m "feat: agregar sección X en blog.html"`.

## Cómo contribuir

1. Crea una rama nueva: `git checkout -b feat/nombre-feature`.
2. Realiza cambios y prueba localmente.
3. Abre un Pull Request con descripción clara de los cambios.

Checklist para PR:

- [ ] Cambios probados en local
- [ ] HTML semántico y válido
- [ ] Imágenes optimizadas y con `alt`

## Posibles mejoras y próximos pasos

- Añadir un `index.html` que sirva como landing page.
- Añadir un `styles/` con CSS minimal para presentación.
- Añadir un `README` más específico por cada componente (si el proyecto crece).
- Automatizar optimización de imágenes con un script o CI.

## Notas del autor

Este repositorio es una plantilla educativa. Adáptalo según tus necesidades y agrega un `LICENSE` si deseas compartirlo públicamente.

## Licencia

Sin licencia especificada. Si planeas publicar el proyecto, añade un archivo `LICENSE` (por ejemplo, MIT) y actualiza este apartado.

---

Si quieres, puedo:

- Añadir una sección de estilo CSS inicial.
- Crear un `index.html` y enlazar `blog.html`.
- Generar una plantilla de `CONTRIBUTING.md` y `LICENSE`.

Dime qué prefieres y lo creo por ti.
