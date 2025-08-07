# 🚀 Portafolio Profesional - Desarrollador Senior

Un portafolio moderno y responsivo diseñado para desarrolladores con experiencia. Optimizado para GitHub Pages.

## 📋 Características

- ✨ Diseño moderno y profesional
- 📱 Completamente responsivo
- 🎨 Animaciones suaves y efectos visuales
- 🌙 Tema oscuro elegante
- ⚡ Optimizado para rendimiento
- 🔧 Fácil de personalizar

## 🛠️ Tecnologías Utilizadas

- HTML5 semántico
- CSS3 con variables personalizadas
- JavaScript ES6+
- Font Awesome para iconos
- Google Fonts (Inter)

## 🚀 Cómo Publicar en GitHub Pages

### Opción 1: Subir archivos directamente a GitHub

1. **Crear un nuevo repositorio en GitHub:**
   - Ve a [GitHub](https://github.com) y crea un nuevo repositorio
   - Nombra el repositorio como `tu-usuario.github.io` o cualquier nombre que prefieras
   - Marca la opción "Add a README file"

2. **Subir los archivos:**
   - Haz clic en "uploading an existing file"
   - Arrastra y suelta todos los archivos (`index.html`, `styles.css`, `script.js`)
   - Escribe un mensaje de commit como "Add portfolio files"
   - Haz clic en "Commit changes"

3. **Habilitar GitHub Pages:**
   - Ve a Settings → Pages
   - En "Source", selecciona "Deploy from a branch"
   - Selecciona "main" como branch
   - Haz clic en "Save"

### Opción 2: Usando Git desde la terminal

```bash
# Inicializar repositorio
git init

# Añadir archivos
git add .

# Hacer commit
git commit -m "Initial commit: Add portfolio"

# Conectar con GitHub (reemplaza con tu URL)
git remote add origin https://github.com/tu-usuario/tu-repositorio.git

# Subir a GitHub
git push -u origin main
```

## 🎨 Personalización

### 1. Información Personal

Edita el archivo `index.html` y actualiza:

```html
<!-- Cambia el título y descripción -->
<h1 class="hero-title">
    Hola, soy <span class="highlight">Tu Nombre</span>
</h1>
<p class="hero-subtitle">
    Tu descripción profesional personalizada
</p>

<!-- Actualiza la información de contacto -->
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <div>
        <h4>Email</h4>
        <p>tu-email@ejemplo.com</p>
    </div>
</div>
```

### 2. Proyectos

Actualiza la sección de proyectos con tus propios trabajos:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-tu-icono"></i>
    </div>
    <div class="project-content">
        <h3>Nombre de tu Proyecto</h3>
        <p>Descripción de tu proyecto...</p>
        <div class="project-tech">
            <span>Tecnología 1</span>
            <span>Tecnología 2</span>
        </div>
        <div class="project-links">
            <a href="tu-repo-url" class="project-link">
                <i class="fab fa-github"></i>
                Código
            </a>
            <a href="tu-demo-url" class="project-link">
                <i class="fas fa-external-link-alt"></i>
                Demo
            </a>
        </div>
    </div>
</div>
```

### 3. Habilidades

Modifica las habilidades según tu experiencia:

```html
<div class="skill-category">
    <h3>Tu Categoría</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-tu-icono"></i>
            <span>Tu Habilidad</span>
        </div>
    </div>
</div>
```

### 4. Colores y Tema

Personaliza los colores en `styles.css`:

```css
:root {
    --primary-color: #tu-color-primario;
    --secondary-color: #tu-color-secundario;
    --accent-color: #tu-color-acento;
    /* ... otros colores */
}
```

## 📱 Estructura de Archivos

```
tu-repositorio/
│
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript
└── README.md           # Este archivo
```

## 🌟 Características del Diseño

- **Navegación fija** con efecto de desvanecimiento
- **Hero section** con animación flotante
- **Sección About** con estadísticas animadas
- **Grid de habilidades** organizadas por categorías
- **Galería de proyectos** con efectos hover
- **Formulario de contacto** funcional
- **Animaciones scroll** para mejor UX

## 🔧 Optimizaciones Incluidas

- Lazy loading para imágenes
- Animaciones CSS optimizadas
- Código JavaScript modular
- CSS Grid y Flexbox para layouts
- Variables CSS para fácil mantenimiento
- Media queries para responsividad

## 📞 Soporte

Si necesitas ayuda con la personalización:

1. Lee la documentación de [GitHub Pages](https://docs.github.com/en/pages)
2. Consulta los comentarios en el código para guías
3. Usa las herramientas de desarrollador del navegador para ajustes

## 📄 Licencia

Este proyecto es de código abierto. Puedes usarlo y modificarlo libremente para tu propio portafolio.

---

**¡Buena suerte con tu portafolio! 🚀**

> Recuerda actualizar regularmente tu portafolio con nuevos proyectos y habilidades.
