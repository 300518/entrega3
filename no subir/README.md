
# Proyecto Web: Figuras y Animes Favoritos

Este proyecto es una página web desarrollada por Álvaro para mostrar figuras coleccionables en venta y animes que le interesan. Utiliza HTML, SCSS y Bootstrap para lograr un diseño moderno y responsive.

## 🚀 Tecnologías utilizadas
- HTML5
- SCSS (SASS)
- Bootstrap 5
- Visual Studio Code

## 📁 Estructura del proyecto
```
mi-proyecto/
├── index.html
├── contacto.html
├── acerca.html
├── figuras.html
├── anime.html
├── estilos/
│   └── main.css         # Compilado desde SCSS
├── scss/
│   ├── main.scss
│   └── base/, layout/, components/, pages/
├── img/
│   ├── shingeki.jpg
│   ├── figura1.jpg
│   └── figura2.jpg
├── .gitignore
└── README.md
```

## 🛠️ Cómo levantar el proyecto localmente

### 1. Instalar Visual Studio Code
Descargar desde [https://code.visualstudio.com/](https://code.visualstudio.com/)

### 2. Instalar la extensión Live Server
- Abrir VS Code
- Ir a la pestaña de extensiones
- Buscar "Live Server" e instalarla

### 3. Compilar SCSS a CSS
Instalar Sass si no lo tienes:
```bash
npm install -g sass
```
Compilar el archivo SCSS:
```bash
sass scss/main.scss estilos/main.css
```

### 4. Abrir el proyecto
- Abrir la carpeta del proyecto en VS Code
- Clic derecho en `index.html` → "Open with Live Server"

### 5. Visualizar en el navegador
Se abrirá automáticamente en `http://127.0.0.1:5500/index.html`

## 📦 Recomendaciones
- Usar `.gitignore` para evitar subir archivos innecesarios
- Probar el sitio en diferentes dispositivos y navegadores
- Documentar los cambios en GitHub con commits claros

---
© 2025 Álvaro Cabezas Garrido
