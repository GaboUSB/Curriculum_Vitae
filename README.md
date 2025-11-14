````markdown
# Hoja de Vida / Portafolio – Gabriel Argenis Medina Carrero

Aplicación web de hoja de vida (CV) y portafolio personal desarrollada para la materia **Tecnologías Web**, 7mo semestre, de la **Universidad Simón Bolívar – Sede Cúcuta**.

El sitio está construido usando únicamente **HTML, CSS y JavaScript**, e incluye:

- Modo **Dark / Light** con toggle y guardado de preferencia en `localStorage`.
- Navegación entre secciones tipo *single page*.
- Diseño **responsive** para dispositivos móviles, tablets y escritorio.
- Secciones:
  - **Inicio (Landing Page)**
  - **Acerca de (About me)**
  - **Mis proyectos**
  - **Contácteme**

---

## 🧩 Tecnologías utilizadas

- **HTML5** – Estructura del contenido.
- **CSS3** – Estilos, layout y diseño responsive (media queries).
- **JavaScript** – Lógica de:
  - Cambio de tema (Dark / Light).
  - Navegación activa al hacer scroll.
  - Menú responsive (mobile).
  - Formulario de contacto modo *demo*.

No se usan frameworks externos (sin React, sin Bootstrap), solo código puro para cumplir con la actividad.

---

## 📂 Estructura del proyecto

Versión básica (un solo archivo principal):

```text
/
├── index.html         # Archivo principal de la aplicación
└── assets/
    └── CV_Gabriel_Medina.pdf   # Hoja de vida en PDF (para el botón "Descargar CV")
````

> 📌 Importante:
> El botón "Descargar CV en PDF" del sitio apunta a:
> `assets/CV_Gabriel_Medina.pdf`
> Asegúrate de crear la carpeta `assets/` y subir allí tu CV con ese nombre (o actualizar la ruta en el HTML).

---

## 🚀 Cómo ejecutar el proyecto

### Opción 1: Abrir localmente

1. Clona o descarga este repositorio.
2. Asegúrate de que el archivo `index.html` está en la raíz del proyecto.
3. Haz doble clic sobre `index.html` o ábrelo con tu navegador (Chrome, Edge, Firefox, etc.).
4. Listo: podrás navegar por las secciones y probar el modo Dark / Light.

No se necesita servidor ni backend, todo es estático.

---

### Opción 2: Publicar en GitHub Pages

1. Sube el proyecto a un repositorio en GitHub (por ejemplo: `cv-gabriel-medina`).
2. En GitHub, ve a:

   * **Settings → Pages**
3. En la sección **Source**:

   * Selecciona `Deploy from a branch`.
   * Branch: `main` (o el branch principal del repo).
   * Folder: `/root`.
4. Guarda los cambios.

GitHub generará una URL similar a:

```text
https://TU_USUARIO.github.io/NOMBRE_DEL_REPOSITORIO/
```

Ahí se podrá ver la aplicación funcionando como sitio web.

---

## 🧭 Secciones de la app

* **Inicio (Landing Page)**
  Presentación general: nombre, perfil profesional, breve descripción, tecnologías principales y botón de descarga del CV.

* **Acerca de (About me)**
  Información personal, resumen de experiencia, habilidades, y una línea de tiempo con:

  * Experiencia laboral.
  * Estudios.
  * Certificaciones.

* **Mis proyectos**
  Tarjetas de proyectos académicos y personales relacionados con:

  * Desarrollo backend con Java / Spring Boot.
  * Aplicaciones web en HTML/CSS/JS.
  * Prototipos con Node.js, MySQL, etc.

* **Contácteme**
  Datos de contacto:

  * Ubicación (Cúcuta, Norte de Santander).
  * Teléfonos.
  * Correo.
  * GitHub.
    Incluye un formulario de contacto **modo demostración** (muestra un `alert` y no envía datos reales).

---

## 🎨 Funcionalidades destacadas

### 🌙 / ☀️ Modo Dark / Light

* Botón en el header para cambiar entre modo claro y oscuro.
* Uso de variables CSS (`:root`) para cambiar toda la paleta de colores.
* El tema elegido se guarda en `localStorage` para que se recuerde en próximas visitas.

### 📱 Diseño responsive

* Uso de **media queries** para adaptar el layout:

  * Columnas en desktop.
  * Stacks en una sola columna en móvil.
* Menú responsive:

  * En pantallas pequeñas el menú se colapsa en un botón tipo hamburguesa (☰).

---

## 👨‍🎓 Contexto académico

Este proyecto fue desarrollado como ejercicio práctico para:

* Aplicar conceptos de:

  * Estructura semántica en HTML.
  * Estilo y responsividad con CSS.
  * Interactividad con JavaScript puro.
* Crear una **hoja de vida interactiva** y usable como portafolio personal.
* Publicar el resultado usando **GitHub Pages**.

---

## ✏️ Autor

**Gabriel Argenis Medina Carrero**
Tecnólogo ADSI · Estudiante de Ingeniería de Sistemas
Universidad Simón Bolívar – Sede Cúcuta

* 📍 Cúcuta, Norte de Santander – Colombia
* 📧 [gabrielargenismedinacarrero@gmail.com](mailto:gabrielargenismedinacarrero@gmail.com)
* 🐙 GitHub: [github.com/GabitoMIX](https://github.com/GabitoMIX)
