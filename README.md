# Fundación Raíces de Progreso - Sitio Web

## Descripción
Sitio web profesional para la Fundación Raíces de Progreso, una ONG dedicada al desarrollo integral de comunidades vulnerables en El Salvador.

## Estructura del Proyecto

```
fundacion-raices-progreso/
├── index.html              # Página principal
├── assets/
│   ├── css/
│   │   └── styles.css      # Estilos principales
│   ├── js/
│   │   └── main.js         # JavaScript principal
│   └── images/             # Carpeta de imágenes
│       ├── logo.png        # Logo principal
│       ├── logo-white.png  # Logo blanco para footer
│       ├── favicon.ico     # Favicon
│       ├── hero-bg.jpg     # Imagen de fondo del hero
│       ├── about-us.jpg    # Imagen de quiénes somos
│       ├── program-*.jpg   # Imágenes de programas
│       ├── gallery-*.jpg   # Imágenes de galería
│       └── og-image.jpg    # Imagen para redes sociales
└── README.md               # Este archivo
```

## Instalación y Configuración

### 1. Estructura de Archivos
Crea la siguiente estructura de carpetas:

```bash
mkdir fundacion-raices-progreso
cd fundacion-raices-progreso
mkdir -p assets/css assets/js assets/images
```

### 2. Archivos Principales
- Coloca `index.html` en la raíz del proyecto
- Coloca `styles.css` en `assets/css/`
- Coloca `main.js` en `assets/js/`

### 3. Imágenes Requeridas
Necesitarás agregar las siguientes imágenes en `assets/images/`:

#### Logos y Favicon
- `logo.png` - Logo principal (recomendado: 200x200px)
- `logo-white.png` - Logo en blanco para footer
- `favicon.ico` - Favicon del sitio

#### Imágenes de Contenido
- `hero-bg.jpg` - Imagen de fondo del hero (1920x1080px)
- `about-us.jpg` - Imagen del equipo (800x600px)
- `og-image.jpg` - Imagen para redes sociales (1200x630px)

#### Imágenes de Programas
- `program-housing.jpg` - Renovación de viviendas
- `program-entrepreneurship.jpg` - Emprendimiento
- `program-agriculture.jpg` - Agricultura sostenible
- `program-sports.jpg` - Deporte y recreación

#### Galería
- `gallery-1.jpg` - Construcción de vivienda
- `gallery-2.jpg` - Taller de emprendimiento
- `gallery-3.jpg` - Huerto comunitario
- `gallery-4.jpg` - Actividad deportiva

## Características Técnicas

### Tecnologías Utilizadas
- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con variables CSS
- **JavaScript ES6+** - Interactividad y funcionalidad
- **Font Awesome** - Iconos
- **Google Fonts** - Tipografías (Montserrat, Open Sans)

### Características Principales
- ✅ **Responsive Design** - Adaptable a todos los dispositivos
- ✅ **Navegación Suave** - Scroll suave entre secciones
- ✅ **Animaciones CSS** - Efectos visuales atractivos
- ✅ **Formulario de Contacto** - Con validación JavaScript
- ✅ **Galería Interactiva** - Lightbox para imágenes
- ✅ **Contadores Animados** - Estadísticas de impacto
- ✅ **SEO Optimizado** - Meta tags y estructura semántica
- ✅ **Accesibilidad** - ARIA labels y navegación por teclado
- ✅ **Performance** - Optimizado para carga rápida

### Buenas Prácticas Implementadas
- Separación de archivos (HTML, CSS, JS)
- Variables CSS para fácil personalización
- Código comentado y organizado
- Validación de formularios
- Manejo de errores
- Optimización de imágenes
- Lazy loading preparado
- Analytics preparado

## Personalización

### Colores
Los colores se pueden cambiar fácilmente en el archivo CSS modificando las variables:

```css
:root {
    --primary-color: #2e7d32;    /* Verde principal */
    --secondary-color: #1565c0;  /* Azul secundario */
    --accent-color: #f9a825;     /* Amarillo de acento */
    /* ... más variables */
}
```

### Contenido
- Modifica el texto en `index.html`
- Actualiza las imágenes en `assets/images/`
- Cambia los enlaces de redes sociales
- Personaliza la información de contacto

### Funcionalidades
- El formulario está preparado para integrarse con servicios como Formspree, Netlify Forms, etc.
- Analytics preparado para Google Analytics y Facebook Pixel
- Fácil integración con CMS como WordPress o Strapi

## Deployment

### Hosting Estático
El sitio puede ser desplegado en cualquier servicio de hosting estático:

- **Netlify** (Recomendado)
- **Vercel**
- **GitHub Pages**
- **Firebase Hosting**
- **AWS S3**

### Pasos para Netlify
1. Sube todos los archivos a un repositorio de GitHub
2. Conecta tu repositorio con Netlify
3. Configura el build (no necesario para sitio estático)
4. ¡Listo!

### Configuración de Dominio
1. Compra un dominio (ej: raicesdeprogreso.org)
2. Configura los DNS en tu proveedor de hosting
3. Habilita HTTPS (automático en Netlify)

## Mantenimiento

### Actualizaciones de Contenido
- Actualiza las estadísticas de impacto regularmente
- Agrega nuevas imágenes a la galería
- Mantén la información de contacto actualizada

### SEO
- Actualiza meta descriptions
- Agrega nuevas palabras clave
- Mantén el contenido fresco y relevante

### Performance
- Optimiza imágenes antes de subirlas
- Monitorea la velocidad del sitio
- Actualiza dependencias cuando sea necesario

## Soporte

### Navegadores Soportados
- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

### Resolución de Problemas
1. **Imágenes no cargan**: Verifica las rutas en `assets/images/`
2. **Estilos no aplican**: Verifica la ruta del CSS en el HTML
3. **JavaScript no funciona**: Revisa la consola del navegador

## Contacto Técnico
Para soporte técnico o modificaciones, contacta al desarrollador del sitio.

## Licencia
Este proyecto está desarrollado específicamente para la Fundación Raíces de Progreso.

---

**Fundación Raíces de Progreso**  
Transformando comunidades, construyendo futuro.
```