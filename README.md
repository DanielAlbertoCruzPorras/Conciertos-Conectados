# Proyecto: Conciertos-Co

## Descripción
Este proyecto es una página web para la gestión de eventos musicales. La plataforma está diseñada exclusivamente para dispositivos móviles y permite a los usuarios explorar eventos disponibles y acceder a detalles específicos de cada uno al tocar la tarjeta correspondiente.

## Estructura del Proyecto
La organización de archivos del proyecto es la siguiente:

```
CONCIERTOS-CO/
├── css/
│   ├── detail.css          # Estilos aplicados a las vistas detalladas de eventos
│   ├── style.css           # Estilos aplicados a la página de inicio (Home)
│   ├── tickets.css         # Archivo de estilos relacionado con la gestión de boletos
│   ├── variables.css       # Archivo con variables CSS reutilizables
│
├── storage/
│   ├── fonts/              # Carpeta de fuentes utilizadas en el proyecto
│   │   ├── DMSans_36pt-Regular.ttf
│   │   ├── Inter_18pt-Medium.ttf
│   │   ├── Inter_24pt-Regular.ttf
│   │   ├── Inter_24pt-SemiBold.ttf
│   ├── img/                # Carpeta para almacenamiento de imágenes
│
├── views/
│   ├── detailCP.html       # Página de detalles para un evento específico
│   ├── detailMUSE.html     # Página de detalles para un evento específico
│   ├── detailTOP.html      # Página de detalles para un evento específico
│   ├── tickets.html        # Página para la gestión de boletos
│   ├── index.html          # Página principal (Home)
```

## Funcionalidad
- **Página Principal (Home - `index.html`)**
  - Muestra una lista de eventos disponibles.
  - Está estilizada con `style.css`.
  - Al tocar un evento, se redirige a su vista detallada correspondiente.

- **Vistas de Detalles de Eventos (`detailCP.html`, `detailMUSE.html`, `detailTOP.html`)**
  - Cada evento cuenta con su propia vista en la carpeta `views`.
  - Comparten el mismo archivo de estilos `detail.css`.
  - Presentan información detallada sobre el evento, como la fecha, ubicación y opciones de compra de boletos.

- **Página de Gestión de Boletos (`tickets.html`)**
  - Permite a los usuarios administrar sus boletos de eventos.
  - Puede utilizar `tickets.css` para su diseño específico.

## Estilos y Fuentes
- Los estilos están organizados en la carpeta `css`, con archivos separados para mantener modularidad.
- Se han definido fuentes personalizadas en la carpeta `storage/fonts/`, incluyendo `DMSans` e `Inter` en diferentes pesos.

## Tecnologías Utilizadas
- **HTML5** para la estructura de las páginas.
- **CSS3** para el diseño y estilos responsivos.
- **Fuentes personalizadas** para mejorar la estética.

## Instalación y Uso
1. Clona el repositorio en tu máquina local:
   ```sh
   git clone https://github.com/tuusuario/conciertos-co.git
   ```
2. Abre el archivo `index.html` en un navegador móvil o usa herramientas de desarrollo para simular una vista en dispositivos móviles.
