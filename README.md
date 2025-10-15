# SOLARFREEZ

## Contexto
SolarFreez es un proyecto de IAW que representa una empresa ficticia dedicada a la venta e instalación de aires acondicionados y tragaluces. La web permite:  
- Visualizar productos y top ventas.  
- Buscar productos por nombre, descripción o precio.  
- Contactar con diferentes departamentos.  
- Acceder a un formulario de login.  

## Autor
Javier Esteras  

## Tecnologías utilizadas
- HTML5: estructura del contenido.  
- CSS3 + Bootstrap 5.0: estilos, grids y componentes responsivos.  
- JavaScript (jQuery 3.7.1): interacción dinámica, mostrar/ocultar secciones y búsqueda de productos.  
- Entorno de desarrollo: Visual Studio Code, navegador moderno (Chrome/Edge/Firefox).  

## Estructura de la página Web

index.html  
assets/  
 ├─ CSS/  
 │   └─ General.css  
 ├─ IMG/  
 │   └─ logo, productos, iconos...  
 └─ JS/  
     └─ jquery.js  

### Secciones principales
1. Navbar: enlaces a Introducción, Productos y Contacto.  
2. Barra lateral: accesos rápidos a “Sobre nosotros”, “Top ventas” y contacto con mantenimiento.  
3. Contenido central:  
   - Introducción de la empresa.  
   - Productos y top ventas con cards.  
   - Formularios de contacto y login.  
4. Footer: información de contacto y redes sociales.  

## Guía de estilos

### Tipografía
Prioridad de fuentes: Open Sans, Arial, Helvetica, Sans-serif.  

### Paleta de colores
| Elemento | Color Hex | Ejemplo |
|----------|-----------|---------|
| Navbar | `#FF9800` | ![#FF9800](https://via.placeholder.com/40x20/FF9800/000000?text=+) |
| Botones login/accesos | `#007bff` | ![#007bff](https://via.placeholder.com/40x20/007bff/000000?text=+) |
| Footer | `#0dcaf0` | ![#0dcaf0](https://via.placeholder.com/40x20/0dcaf0/000000?text=+) |
| Fondo body | `#a5a5a5` | ![#a5a5a5](https://via.placeholder.com/40x20/a5a5a5/000000?text=+) |
| Fondo contenido | `#F5F5F5` | ![#F5F5F5](https://via.placeholder.com/40x20/F5F5F5/000000?text=+) |
| Borde top ventas | `blue` | ![blue](https://via.placeholder.com/40x20/0000FF/FFFFFF?text=+) |

### Botones
- Letras negras en botones de menú y barra lateral.  
- Quitar outline y box-shadow al pulsar (focus/active) para apariencia limpia.  
- Mantener contraste y accesibilidad mínima.  

Ejemplo CSS:
#button1, #button2, #button3, #fast1, #fast2, #fast3, #button4 {
    color: black;
    outline: none;
    box-shadow: none;
}

### Imágenes y productos
- Cada producto dentro de una card con imagen, título y precio.  
- Productos más vendidos con borde azul 3px solid blue.  
- Imágenes responsive con img-fluid.  

### Funcionalidades JavaScript
- Mostrar/ocultar secciones según el botón pulsado.  
- Buscar productos por nombre, descripción y precio con la barra de búsqueda.  