# Portafolio Personal — Alan Josué Luna Cardona

## 🎯 Objetivo del proyecto

Página web de presentación personal desarrollada con **Bootstrap 5**, aplicando HTML5 semántico, diseño responsive y personalización propia mediante CSS. El sitio funciona como un perfil/currículum digital, integrando un framework CSS moderno sin perder identidad visual propia.

## 🚀 Cómo ejecutar la página

No requiere instalación ni dependencias:

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` directamente en cualquier navegador (doble clic, o clic derecho → "Abrir con").
3. *(Opcional)* Si usas VS Code, puedes instalar la extensión **Live Server** y hacer clic en "Go Live" para verlo con recarga automática.

No se necesita servidor, build ni instalación de paquetes: Bootstrap 5 y Bootstrap Icons se cargan vía CDN.

## 📂 Estructura del proyecto

```
proyecto-cv/
├── index.html
├── css/
│   └── new.css        ← estilos personalizados propios
├── img/                ← imágenes del perfil, proyectos y pasatiempos
└── README.md
```

## 🧩 Componentes de Bootstrap utilizados

- **Navbar** — menú de navegación responsive con botón hamburguesa (`navbar-expand-lg`, `sticky-top`) y enlaces por anclas a cada sección.
- **Grid System** — `container`, `row` y `col-*` en todas las secciones, con breakpoints (`col-12`, `col-md-*`, `col-lg-*`) para adaptar el layout en cada tamaño de pantalla.
- **List Group** — para presentar las habilidades principales junto a su nivel/estado.
- **Badges / Rounded Pills** — para las habilidades (dentro del list group) y para las tecnologías/herramientas específicas.
- **Cards** — tres tarjetas en la sección de proyectos y pasatiempos, cada una con imagen, título, descripción y botón/enlace.
- **Bootstrap Icons** — iconos de GitHub, Instagram y correo en el footer.

## 🎨 Personalización mediante CSS (`css/new.css`)

- **Paleta de colores propia**: fondo casi negro con acentos en naranja y cian, definida mediante variables CSS (`:root`) para mantener consistencia en todo el sitio.
- **Tipografía propia**: combinación de dos familias de Google Fonts — una condensada y angular para títulos, y otra más neutra para el texto de párrafos — en lugar de la tipografía por defecto de Bootstrap.
- **Formas angulares**: recortes diagonales (`clip-path`) en la foto de perfil y en los elementos de la lista de habilidades, para reforzar una estética más dinámica y menos "cuadrada".
- **Sombras y transiciones**: sombras suaves en cards y list-group, que se intensifican al pasar el mouse (`:hover`), junto con pequeñas animaciones de elevación en las tarjetas.
- **Accesibilidad**:
  - Enlace "Saltar al contenido principal" (`skip-link`), visible solo al navegar con teclado.
  - `scroll-margin-top` en cada sección para que el navbar `sticky-top` no tape el contenido al hacer clic en los enlaces del menú.
  - Estilos `:focus-visible` con contorno de color visible en enlaces y botones, para facilitar la navegación por teclado.
  - Sin uso de `!important` en ninguna regla.

## 🧠 Principales decisiones de diseño

- Se eligió una estética **oscura y futurista**, con acentos de color vivos (naranja/cian) para reflejar el interés personal en tecnología, redes y sistemas, evitando una paleta genérica tipo "plantilla".
- El contenido se organizó siguiendo un **flujo narrativo simple**: quién soy (biografía) → qué sé hacer (habilidades) → qué he hecho (proyectos) → hacia dónde voy (visión profesional) → cómo contactarme (footer).
- Se priorizó la **legibilidad y el contraste** por encima de la decoración: los efectos visuales (recortes diagonales, sombras, hover) se usan como acento, no como elemento central de cada sección.
- El sitio se construyó **mobile-first en la práctica**: todas las columnas parten de `col-12` y se amplían progresivamente en `md` y `lg`, garantizando que no haya desplazamiento horizontal en pantallas pequeñas.



# 👤 Autor

**Alan Josué Luna Cardona**
Estudiante de Ingeniería en Sistemas de Información y Ciencias de la Computación — Universidad Mariano Gálvez de Guatemala, sede Jutiapa.
