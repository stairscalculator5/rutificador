# Rutificador - Landing Page

Una página de aterrizaje profesional y optimizada para SEO de **Rutificador**, la herramienta más rápida y confiable para buscar personas y empresas en Chile por RUT o nombre.

## 📋 Contenido del Proyecto

Este proyecto incluye:

- **index.html** - Página de aterrizaje completa con estructura HTML5 semántica
- **logo.png** - Logo profesional con colores de la bandera chilena
- **favicon.png** - Favicon para la pestaña del navegador
- **README.md** - Este archivo con instrucciones de implementación

## 🎨 Características de Diseño

### Colores de la Bandera Chilena
- **Azul**: #0039A6 (Cielo y Océano Pacífico)
- **Rojo**: #D52B1E (Sangre derramada por la independencia)
- **Blanco**: #FFFFFF (Nieve de los Andes)

### Secciones Incluidas
1. **Header Sticky** - Navegación siempre visible
2. **Hero Section** - Presentación impactante con CTA
3. **Features** - 6 características principales
4. **About** - Información sobre Rutificador
5. **Benefits** - 6 beneficios principales
6. **Resources** - Sección para backlinks (dofollow)
7. **FAQ** - 6 preguntas frecuentes interactivas
8. **Contact** - Formulario de contacto
9. **Footer** - Enlaces y información legal

## 🔍 Optimización SEO

### Meta Tags Implementados
- **Title Tag**: "Rutificador Chile Oficial: Consulta RUT y Nombre al Instante"
- **Meta Description**: Descripción optimizada para CTR
- **Keywords**: rutificador, buscar rut, consulta rut, verificar rut, rutificador chile
- **Open Graph Tags**: Para compartir en redes sociales
- **Twitter Card Tags**: Para optimización en Twitter
- **Canonical Tag**: Para evitar contenido duplicado
- **Robots Meta**: index, follow

### Estructura SEO
- **H1 Tag**: Contiene palabra clave principal
- **Headings Jerárquicos**: H2 y H3 bien organizados
- **Contenido de Calidad**: Más de 2000 palabras de contenido relevante
- **Internal Links**: Enlaces internos a diferentes secciones
- **Mobile Responsive**: Diseño adaptable a todos los dispositivos
- **Fast Loading**: CSS y JS optimizados

## 🔗 Implementación de Backlinks Dofollow

La página incluye una sección de "Recursos Relacionados" (línea ~600) donde puedes agregar backlinks dofollow:

```html
<div class="resources-grid">
    <div class="resource-card">
        <h3>Sobre RUT en Chile</h3>
        <p>Aprende más sobre el Rol Único Tributario y su importancia en el sistema chileno.</p>
        <a href="TU_ENLACE_AQUI" rel="dofollow">Leer más →</a>
    </div>
    <!-- Más tarjetas de recursos -->
</div>
```

**Para agregar backlinks dofollow:**

1. Reemplaza `TU_ENLACE_AQUI` con la URL del sitio que deseas enlazar
2. Asegúrate de que `rel="dofollow"` esté presente (o simplemente omite el atributo `rel`)
3. El texto del enlace debe ser descriptivo y relevante

## 🚀 Instrucciones de Despliegue en GitHub Pages

### Paso 1: Crear un Repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Haz clic en el botón "+" en la esquina superior derecha
3. Selecciona "New repository"
4. Nombre del repositorio: `rutificador` (o el nombre que prefieras)
5. Descripción: "Landing page profesional para Rutificador - Herramienta de búsqueda de RUT en Chile"
6. Selecciona "Public"
7. Haz clic en "Create repository"

### Paso 2: Subir los Archivos

**Opción A: Usando Git en la terminal**

```bash
# Clona el repositorio
git clone https://github.com/TU_USUARIO/rutificador.git
cd rutificador

# Copia los archivos del proyecto
cp /home/ubuntu/index.html .
cp /home/ubuntu/logo.png .
cp /home/ubuntu/favicon.png .
cp /home/ubuntu/README.md .

# Agrega los archivos
git add .

# Realiza un commit
git commit -m "Initial commit: Rutificador landing page with SEO optimization"

# Sube los cambios
git push origin main
```

**Opción B: Usando la interfaz web de GitHub**

1. En tu repositorio, haz clic en "Add file" → "Upload files"
2. Arrastra y suelta los archivos (index.html, logo.png, favicon.png, README.md)
3. Haz clic en "Commit changes"

### Paso 3: Habilitar GitHub Pages

1. Ve a la pestaña "Settings" de tu repositorio
2. En el menú izquierdo, selecciona "Pages"
3. En "Source", selecciona "Deploy from a branch"
4. Selecciona la rama "main" y la carpeta "/ (root)"
5. Haz clic en "Save"

GitHub Pages generará una URL como: `https://TU_USUARIO.github.io/rutificador/`

### Paso 4: Verificar el Despliegue

Espera 2-3 minutos y luego visita tu URL. La página debe estar en línea.

## 📱 Características Técnicas

### Responsive Design
- Adaptado para móviles, tablets y desktop
- Media queries optimizadas
- Navegación adaptable

### Interactividad
- FAQ con toggle interactivo (JavaScript vanilla)
- Smooth scroll en navegación
- Hover effects en botones y tarjetas

### Accesibilidad
- Contraste de colores WCAG AA
- Focus states para navegación por teclado
- Estructura HTML semántica
- Alt text en imágenes

### Performance
- CSS inline para reducir requests
- Minificación de código
- Imágenes optimizadas
- Carga rápida en conexiones lentas

## 📊 Palabras Clave Objetivo

- rutificador
- rutificador chile
- buscar rut
- consulta rut
- verificar rut
- búsqueda de identidad
- RUT Chile
- verificación de identidad

## 🔐 Consideraciones Legales

Esta página es una landing page de demostración. Si planeas usar Rutificador en producción:

1. Asegúrate de cumplir con las leyes de privacidad de Chile
2. Incluye términos de servicio y política de privacidad
3. Obtén consentimiento de usuarios para procesar datos
4. Cumple con regulaciones de protección de datos

## 📝 Personalización

### Cambiar Colores
Edita las variables CSS en la sección `:root`:

```css
:root {
    --color-blue: #0039A6;
    --color-red: #D52B1E;
    --color-white: #FFFFFF;
}
```

### Cambiar Contenido
- Edita el texto en las secciones HTML
- Reemplaza el logo con tu propia imagen
- Actualiza los enlaces de redes sociales en el footer

### Agregar Funcionalidad
- Integra un formulario de contacto real
- Agrega Google Analytics
- Implementa un chatbot
- Conecta a una base de datos

## 📧 Contacto y Soporte

Para preguntas o sugerencias sobre esta landing page, contacta a través del formulario de contacto en la página.

## 📄 Licencia

Este proyecto es de código abierto y puede ser modificado libremente.

---

**Última actualización**: Octubre 2025

**Versión**: 1.0.0

