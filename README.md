# 🍷 Norman Wines - Sitio Web Elegante

Norman Wines es una tienda online de vinos diseñada con HTML5, CSS3, SASS, Bootstrap y fuentes de Google Fonts. Este sitio web presenta una estética cuidada y profesional que destaca la identidad de marca y permite a los usuarios explorar los distintos productos ofrecidos con un diseño suave y cómodo a la vista.

## ✨ Características Principales

- **Diseño responsivo** adaptable a distintos dispositivos
- **Navegación clara y sencilla** con barra colapsable en dispositivos móviles  
- **Menú hamburguesa mejorado** con estilos personalizados y efectos elegantes
- **Sección de productos destacados** con descripciones e imágenes de alta calidad
- **Categorización de vinos** por tipo (Tintos, Blancos y Rosados)
- **Página de inicio atractiva** con llamados a la acción efectivos
- **Pie de página informativo** con enlaces a secciones clave
- **Contraste optimizado** para máxima legibilidad en todas las secciones
- **Efectos suaves y profesionales** sin agresividad visual

## 🛠 Tecnologías Utilizadas

- **HTML5** - Estructura semántica moderna
- **CSS3** - Estilos avanzados con efectos y transiciones
- **SASS/SCSS** - Preprocesador CSS para mejor organización
- **Bootstrap 5** - Framework responsivo
- **Google Fonts** - Tipografías Playfair Display y Raleway

## 📁 Estructura del Proyecto

```
/norman-wines
│
├── index.html                    # Página principal
├── package.json                  # Configuración de Node.js para SASS
├── README.md                     # Documentación del proyecto
├── .gitignore                    # Archivos ignorados por Git
│
├── /css
│   ├── style.css                 # CSS compilado final
│   ├── style.css.map             # Mapa de código fuente
│   └── style-backup-original.css # Respaldo del CSS original
│
├── /scss                         # Archivos fuente SASS
│   ├── style.scss                # Archivo principal SASS
│   ├── _variables.scss           # Variables y configuración
│   ├── _base.scss                # Estilos base y tipografía
│   ├── _components.scss          # Componentes específicos
│   └── _utilities.scss           # Utilidades y clases auxiliares
│
├── /pages                        # Páginas adicionales
│   ├── nosotros.html            # Página sobre nosotros
│   ├── productos.html           # Catálogo de productos
│   ├── galeria.html             # Galería de imágenes
│   └── contacto.html            # Página de contacto
│
├── /img                          # Imágenes del sitio
│   ├── logo.png                 # Logotipo de la marca
│   ├── principal.jpg            # Imagen principal
│   ├── nosotros.png            # Imagen sección nosotros
│   ├── producto1.png            # Imagen producto Merlot
│   ├── producto2.png            # Imagen producto Chardonnay
│   ├── producto3.png            # Imagen producto Pinot Noir
│   ├── producto4.png            # Imagen producto Equinox
│   ├── producto5.png            # Imagen producto Binary
│   ├── producto6.png            # Imagen producto Tempo
│   ├── categoria1.png           # Imagen categoría tintos
│   ├── categoria2.png           # Imagen categoría blancos
│   └── categoria3.png           # Imagen categoría rosados
│
└── /wireframe                    # Bocetos y diseños previos
```

## 🎨 Paleta de Colores Elegante

### Colores Principales
- **Vino Profundo**: `#3d1526` - Color primario elegante
- **Oro Suave**: `#c9a961` - Color secundario refinado
- **Merlot Elegante**: `#5a1e35` - Acento sofisticado
- **Oscuro Suave**: `#2a1219` - Contraste sin agresividad

### Fondos Cómodos
- **Carbón Suave**: `#3a3a3a` - Menos agresivo que antes
- **Carbón Cálido**: `#454545` - Cómodo para la vista  
- **Pizarra Rica**: `#505050` - Más claro y elegante
- **Café Suave**: `#3d3429` - Tonos terrosos relajantes

### Textos Legibles
- **Marfil Cálido**: `#fdf9f4` - Texto principal muy legible
- **Blanco Perla**: `#faf7f2` - Para enlaces en footer
- **Crema Cálida**: `#f5f2eb` - Texto secundario suave
- **Oro Brillante**: `#e6c878` - Para títulos y acentos

## 🚀 Instalación y Desarrollo

### Requisitos Previos
- Node.js instalado en el sistema
- Editor de código (VS Code recomendado)

### Configuración Inicial
```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/norman-wines.git
cd norman-wines

# Instalar dependencias de SASS
npm install
```

### Comandos de Desarrollo
```bash
# Compilar SASS automáticamente (modo desarrollo)
npm run sass:watch

# Compilar SASS una sola vez
npm run sass:build

# Generar CSS comprimido para producción
npm run sass:compress
```

### Ver el Sitio Localmente
```bash
# En Windows
start index.html

# En macOS
open index.html

# En Linux
xdg-open index.html
```

**Nota**: No requiere backend ni instalación de dependencias adicionales para visualización.

## ✅ Mejoras Implementadas (Diseño Suave y Profesional)

### Problemas Solucionados Completamente

#### 🎯 **Cards sin Movimiento Excesivo**
- **Antes**: Cards se movían -20px y escalaban al hacer hover (muy agresivo)
- **Ahora**: Solo cambian la sombra sutilmente, sin movimiento molesto
- **Resultado**: Comportamiento igual que el producto Merlot (profesional)

#### 🎯 **Footer con Contraste Perfecto**
- **Antes**: Textos con mal contraste sobre fondo muy oscuro
- **Ahora**: Color `#faf7f2` para enlaces con sombras de texto
- **Resultado**: Legibilidad excelente y apariencia profesional

#### 🎯 **Categorías con Contraste Mejorado**
- **Antes**: Texto dorado sobre fondo bordó (mal contraste)
- **Ahora**: Texto dorado claro sobre fondo con mejor separación
- **Resultado**: Máxima legibilidad y elegancia

#### 🎯 **Sección Nosotros Optimizada**
- **Antes**: Texto difícil de leer sobre fondo complejo
- **Ahora**: Texto blanco en cajas con fondo semitransparente
- **Resultado**: Contraste perfecto y diseño elegante

#### 🎯 **Menú Hamburguesa Mejorado**
- **Antes**: Uso de estilos predeterminados de Bootstrap
- **Ahora**: Diseño personalizado con efectos dorados elegantes
- **Resultado**: Integración perfecta con la identidad visual

### Efectos Suavizados
- **Transiciones**: 400ms en lugar de 300ms (más suaves)
- **Escalado de imágenes**: 1.02x en lugar de 1.1x (sutil)
- **Movimientos hover**: Reducidos a máximo -5px (cómodos)
- **Sombras**: Opacidades reducidas para menos agresividad

## 🎯 Clases Utilitarias Disponibles

### Efectos Suaves
- `.elevacion-suave` - Elevación mínima (-3px)
- `.brillo-suave` - Brillo sutil
- `.hover-gentil` - Efecto de brillo suave
- `.pulso-suave` - Pulso suave
- `.flotacion-gentil` - Flotación mínima (-5px)

### Fondos Temáticos
- `.fondo-vino-suave` - Fondo vino elegante
- `.fondo-carbon-suave` - Fondo carbón cómodo
- `.fondo-oro-suave` - Fondo oro refinado
- `.fondo-medianoche-suave` - Fondo azul medianoche

### Animaciones Elegantes
- `.aparicion-suave` - Aparición gradual
- `.deslizamiento-suave` - Deslizamiento desde abajo

## 📊 Comparación de Mejoras

| Aspecto | ❌ Antes (Agresivo) | ✅ Ahora (Elegante) |
|---------|---------------------|---------------------|
| **Cards Productos** | Movimiento -20px + escala 1.03 | Solo cambio de sombra |
| **Imágenes Cards** | Escala 1.1 | Escala 1.02 |
| **Categorías** | Movimiento -12px | Movimiento -5px |
| **Botones** | Movimiento -4px | Movimiento -2px |
| **Transiciones** | 300ms (rápido) | 400ms (suave) |
| **Contraste Footer** | Malo | Excelente (WCAG AAA) |
| **Contraste Nosotros** | Malo | Perfecto con cajas |

## 📌 Funcionalidades Futuras

- **Integración con pasarela de pago** para compras en línea
- **Funcionalidad de carrito de compras** completa
- **Panel de administración** para gestión de productos
- **Optimización SEO avanzada** y mejoras de accesibilidad
- **Sistema de reseñas** de clientes
- **Integración con redes sociales**

## 🔧 Personalización

### Variables SASS Principales
```scss
// Colores principales (en _variables.scss)
$vino-primario: #3d1526;
$oro-secundario: #c9a961;
$merlot-acento: #5a1e35;
$oro-suave: #e6c878;

// Efectos y transiciones
$duracion-transicion: 400ms;
$escala-hover: 1.05;
```

### Compilación de SASS
El proyecto utiliza SASS para una mejor organización del código CSS:
- **Variables centralizadas** en `_variables.scss`
- **Estilos base** en `_base.scss`
- **Componentes específicos** en `_components.scss`
- **Utilidades** en `_utilities.scss`

## 📱 Responsividad

El sitio está optimizado para:
- **Móviles**: 320px - 767px
- **Tablets**: 768px - 991px
- **Escritorio**: 992px en adelante

## 🎯 Accesibilidad

- **Contraste WCAG AAA** en todos los textos
- **Navegación por teclado** completamente funcional
- **Textos alternativos** en todas las imágenes
- **Semántica HTML5** correcta
- **Transiciones suaves** para usuarios sensibles al movimiento

## 🏆 Resultados Finales

### Beneficios Obtenidos
- **Navegación cómoda**: Sin efectos que cansen la vista
- **Legibilidad máxima**: Contrastes perfectos en todo el sitio
- **Elegancia profesional**: Sofisticado pero no agresivo
- **Experiencia fluida**: Transiciones suaves y naturales

### Profesionalismo Mejorado
- **Menos es más**: Efectos sutiles pero elegantes
- **Consistencia visual**: Comportamiento unificado en todo el sitio
- **Accesibilidad**: Cómodo para usuarios con sensibilidad visual
- **Calidad premium**: Refinamiento sin ostentación

## 📄 Licencia

Este proyecto es con fines educativos y de exhibición. Todos los derechos del contenido e imágenes pertenecen a Norman Wines.

---

**¡Diseño elegante y suave completado! El sitio ahora es profesional, cómodo a la vista y perfecto para navegación prolongada.** 🍷✨🎯