# Farmasleyd 2026 — Farmacia y Bienestar

Proyecto académico de una tienda virtual de farmacia desarrollado en HTML, CSS y JavaScript.

## Descripción
Farmasleyd presenta un catálogo demostrativo de medicamentos y productos de bienestar, promociones, información general sobre anticonceptivos y suplementos, videos informativos, sucursales y canales de contacto.

## Características principales
- Pantalla de acceso de demostración con nombre y contraseña.
- Diseño adaptable a pantallas móviles y de escritorio.
- Navegación por secciones.
- Carrusel principal y promociones.
- Catálogo de productos con búsqueda y filtros por categoría.
- Carrito de compras con cantidades, subtotal, descuento y costo de envío.
- Formulario de datos de compra y generación de recibo digital imprimible.
- Secciones informativas sobre anticonceptivos y suplementos.
- Tarjetas que enlazan a videos de YouTube.
- Información de sucursales, horarios y contacto.

## Estructura del proyecto
```text
Farmasleyd_GitHub/
├── index.html
├── README.md
├── Manual_de_Calidad.pdf
└── RECIBO.pdf
```

## Tecnologías y recursos
- HTML5 para la estructura.
- Tailwind CSS mediante CDN para estilos.
- CSS personalizado para detalles visuales y animaciones.
- JavaScript para el acceso de demostración, carrusel, catálogo, carrito y recibo.
- Google Fonts para tipografía.
- Imágenes remotas y miniaturas de YouTube.

## Cómo ejecutar
1. Descarga o clona este repositorio.
2. Abre `index.html` en un navegador actualizado.
3. También puedes abrir la carpeta en Visual Studio Code y usar una extensión de servidor local.

Se necesita conexión a Internet para cargar Tailwind CSS, Google Fonts y recursos de imágenes externos.

## Integrantes y roles
| Integrante | Rol / responsabilidad |
|---|---|
| Anderson Steven Santos | Líder del proyecto |
| Damaris | Elaboración del Manual de Calidad |
| Kerin | Participación en el proyecto y apoyo con licencias/documentación |

## Estándares de codificación
- Uso de etiquetas HTML semánticas cuando corresponde.
- Identificadores (`id`) descriptivos para elementos que controla JavaScript.
- Nombres de funciones y variables relacionados con su propósito.
- Indentación y separación por secciones con comentarios.
- Textos de interfaz en español.
- Recursos externos enlazados mediante URL.

## Control de versiones
Versión inicial documentada: **1.0**. Los cambios futuros deben registrarse en el historial de commits de GitHub y actualizar este README cuando cambien funciones o estructura.

## Alcance y observaciones
Este sitio es una demostración académica. El inicio de sesión es local y de demostración: no valida usuarios contra un servidor ni constituye autenticación segura. El carrito utiliza almacenamiento local del navegador. No hay integración visible con una pasarela de pago ni con una base de datos.

El código incluye una función para abrir WhatsApp con el resumen del recibo. Verifica con el equipo y la docente si desean mantener ese comportamiento antes de publicar el proyecto. Los datos de sucursales, precios, productos y contacto deben verificarse antes de usarse en un negocio real.

## Licencia
No se especificó una licencia de distribución para este proyecto. Por ello, no se declara una licencia abierta. Consultar con la docente y los integrantes antes de reutilizar o distribuir el código y los recursos de terceros.
