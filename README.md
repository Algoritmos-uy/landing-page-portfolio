
# Landing Page Portfolio

Este proyecto es una landing page de portafolio diseñada para desarrolladores front-end. Su propósito es servir como una plantilla personalizable para mostrar información profesional, habilidades, experiencia y formación académica. Además, incluye funcionalidades interactivas como un modo oscuro y un acordeón para secciones colapsables.

## Características

- **Diseño Responsivo**: Adaptado para dispositivos móviles y pantallas más grandes.
- **Modo Oscuro**: Implementado con un botón de alternancia para cambiar entre temas claro y oscuro.
- **Secciones Interactivas**: Uso de acordeones para organizar contenido como "Sobre mí", "Formación", "Idiomas", "Experiencia Profesional", "Habilidades" y "Portfolio".
- **Botón flotante de WhatsApp**: Permite a los usuarios contactar fácilmente a través de WhatsApp.
- **Descarga de CV**: Botón para descargar un archivo PDF del currículum.
- **Integración con API**: Preparado para cargar datos dinámicos desde un archivo JSON.

## Estructura del Proyecto

├── assets/ │ ├── icons/ # Iconos utilizados en el proyecto │ ├── js/ # Archivos JavaScript para funcionalidades interactivas │ ├── logos/ # Logos utilizados en las secciones ├── css/ # Archivos CSS para estilos ├── img/ # Imágenes utilizadas en el proyecto ├── index.html # Archivo principal de la página ├── LICENSE # Licencia del proyecto └── README.md # Documentación del proyecto

## Tecnologías Utilizadas

- **HTML5**: Estructura del contenido.
- **CSS3**: Estilización y diseño responsivo.
- **JavaScript**: Funcionalidades interactivas como el modo oscuro y acordeones.
- **Font Awesome**: Iconos utilizados en la interfaz.
- **Google Fonts**: Fuentes personalizadas.

## Instalación y Uso

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/landing-page-portfolio.git
   ```

2. Abre el archivo `index.html` en tu navegador para visualizar la página.

## Funcionalidades Clave

### Modo Oscuro
El modo oscuro se activa mediante el botón con el ID `mode-selector`. Cambia las clases de los elementos principales para aplicar estilos oscuros definidos en `css/dark-ligth.css`.

### Acordeones
Las secciones como "Sobre mí", "Formación", "Idiomas", etc., utilizan acordeones implementados en `assets/js/acordeon.js` para mostrar y ocultar contenido.

### Integración con API
El archivo `assets/js/api.js` está preparado para consumir datos desde un archivo JSON remoto y actualizar dinámicamente el contenido de la página.

## Personalización

- **Estilos**: Modifica los archivos CSS en la carpeta `css/` para personalizar colores, fuentes y diseño.
- **Contenido**: Edita el archivo `index.html` para actualizar la información personal, enlaces y secciones.
- **Funcionalidades**: Amplía o modifica las funcionalidades en los archivos JavaScript dentro de `assets/js/`.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

## Autor

Desarrollado por **Algoritmos-uy / Willans Junes** como parte de un curso de JavaScript.
```
