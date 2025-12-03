# Becalos – Traxion (Grupo B) 💻

Bienvenido al repositorio del **módulo Becalos con Traxion – Grupo B**, mantenido por **Ana Villanueva (Sensei @ DEVF)**.  
Aquí documentamos nuestros avances, ejercicios y ejemplos sobre **Git / GitHub**, **HTML** y **CSS**.

## 🚀 Quién soy

Mi nombre es **Ana Villanueva**, y soy Sensei en DEVF, guiando a estudiantes en su aprendizaje de desarrollo web front-end básico.

## 📚 Qué estamos aprendiendo

- Uso de **Git y GitHub** para control de versiones y colaboración.  
- Estructura básica de **HTML**: etiquetas, secciones, semántica, formularios, etc.  
- Estilos con **CSS**: diseño, layout, flexbox/grid, responsividad, tipografías, colores, etc.

## 📂 Qué contiene este repositorio

Este repositorio sirve como base y ejemplo de proyecto web. Contiene:

- `index.html` — página principal del sitio.  
- `style.css` — estilos globales con diseño responsive.  
- Archivos de imágenes, y otros recursos.  
- Estructura organizada para que cada estudiante pueda clonar, modificar y practicar.  

Además, este repo funciona como **sitio estático** publicado en GitHub Pages:  

[https://anagvillanueva.github.io/Becalos-Traxion-Grupo-B.github.io/](https://anagvillanueva.github.io/Becalos-Traxion-Grupo-B.github.io/)

Puedes usarlo como plantilla inicial para tus propios proyectos, o como referencia para aprender buenas prácticas HTML/CSS + control de versiones.

## 📌 Cómo clonar y usar este proyecto

A continuación encontrarás todas las instrucciones paso a paso para clonar, abrir, editar y publicar este proyecto en GitHub Pages.

Estas instrucciones están pensadas para estudiantes del módulo **Bécalos con Traxion**.

---

## 🟩 1. Clonar el repositorio

Abre tu terminal (Git Bash, CMD, PowerShell o la terminal integrada de VSCode) y ejecuta:

```bash
git clone https://github.com/anagvillanueva/Becalos-Traxion-Grupo-B.github.io.git
```

Después entra a la carpeta del proyecto:

```bash
cd Becalos-Traxion-Grupo-B.github.io
```

---

## 🟦 2. Abrir el proyecto en Visual Studio Code

Para abrir el proyecto directamente desde la terminal:

```bash
code .
```

Si prefieres hacerlo manual:

1. Abre **Visual Studio Code**.
2. Ve a **File → Open Folder**.
3. Selecciona la carpeta `Becalos-Traxion-Grupo-B.github.io`.

---

## 🟨 3. Ver el sitio en tu navegador

Tienes dos maneras principales:

### ✔ Opción A — Abrir `index.html` directamente

1. Dentro de la carpeta del proyecto, busca `index.html`.
2. Haz doble clic.
3. Se abrirá en tu navegador predeterminado.

### ✔ Opción B — Usar Live Server (recomendado)

1. En VSCode, instala la extensión **Live Server** (Ritwick Dey).
2. Abre `index.html`.
3. Haz clic derecho sobre el archivo.
4. Selecciona **"Open with Live Server"**.

Ventaja: el navegador se recarga automáticamente cada vez que guardas cambios.

---

## 🟪 4. Editar el proyecto

Puedes modificar y practicar con:

* `index.html` → estructura de la página (secciones, textos, imágenes).
* `style.css` → colores, fuentes, tamaños, márgenes, layout, etc.
* Archivos en `/assets` → imágenes o recursos adicionales.

Algunas ideas de práctica:

* Agregar más tarjetas de productos al catálogo.
* Crear una nueva sección (por ejemplo, “Testimonios” o “Nosotros”).
* Cambiar la paleta de colores.
* Agregar y configurar una fuente de **Google Fonts**.
* Hacer que la página se vea bien en celular (responsive).

---

## 🟥 5. Guardar tus cambios con Git

Cada vez que realices cambios importantes en tu proyecto, regístralos con Git:

1. Ver qué archivos cambiaron:

   ```bash
   git status
   ```

2. Agregar los cambios al área de preparación (staging):

   ```bash
   git add .
   ```

3. Crear un commit con un mensaje descriptivo:

   ```bash
   git commit -m "Descripción corta de los cambios"
   ```

Ejemplos de mensajes:

* `"Agregué nuevas tarjetas de productos al catálogo"`
* `"Actualicé estilos de la barra de navegación"`
* `"Hice la página responsive con media queries"`

---

## 🟧 6. Subir tus cambios a GitHub

Una vez que ya tengas uno o más commits, envía tus cambios al repositorio remoto:

```bash
git push
```

Si es la primera vez que haces `push` desde esa máquina o ese repo, Git puede pedirte:

* Usuario y contraseña/token de GitHub, o
* Autorización a través del navegador.

Sigue las instrucciones que aparezcan en pantalla.

---

## 🟫 7. Publicar el proyecto en GitHub Pages

Si el proyecto aún no está publicado en GitHub Pages, sigue estos pasos:

1. Entra a tu repositorio en GitHub.
2. Haz clic en la pestaña **Settings** (Configuración).
3. En el menú lateral, selecciona **Pages**.
4. En la sección **Source** (o “Origen”):

   * Elige **Deploy from branch**.
   * Selecciona la rama `main`.
   * Selecciona la carpeta `/root` (si la opción aparece).
5. Guarda la configuración.

Después de unos segundos/minutos, tu sitio estará disponible en una URL similar a:

```text
https://anagvillanueva.github.io/Becalos-Traxion-Grupo-B.github.io/
```

Si realizas cambios en el código y haces `git push`, GitHub volverá a desplegar tu sitio automáticamente.

---

## 🟩 8. Crear tu propia versión del proyecto

Si eres estudiante y quieres tener tu propio repositorio basado en este, tienes dos posibilidades:

### ✔ Opción A — Hacer un Fork

1. En la página del repositorio, haz clic en el botón **Fork**.

2. Esto creará una copia en tu cuenta de GitHub.

3. Clona tu fork:

   ```bash
   git clone https://github.com/TU_USUARIO/Becalos-Traxion-Grupo-B.github.io.git
   ```

4. Edita el proyecto como quieras.

5. Haz tus commits y `git push`.

6. Configura **GitHub Pages** en tu repositorio para publicar tu propia versión.

### ✔ Opción B — Usar el repositorio como plantilla (recomendado)

1. En la página del repositorio, haz clic en **Use this template** (si está habilitado).

2. Crea un nuevo repositorio basado en este.

3. Clona tu nuevo repositorio:

   ```bash
   git clone https://github.com/TU_USUARIO/NOMBRE-DE-TU-REPO.git
   ```

4. Modifica el código libremente.

5. Haz tus commits y sube cambios con `git push`.

6. Publica tu sitio con GitHub Pages desde ese nuevo repositorio.

---

## 🎉 Mensaje final

Con este proyecto estás practicando el flujo completo que usan desarrolladores en la vida real:

* Clonar repositorios.
* Trabajar en local.
* Hacer commits con Git.
* Subir cambios a GitHub.
* Publicar sitios con GitHub Pages.

Cada cambio que haces y subes es parte de tu aprendizaje.
Sigue explorando, rompiendo, corrigiendo y mejorando tu código.

**— Sensei Ana Villanueva
DEVF · Módulo Bécalos con Traxion · Grupo B**

