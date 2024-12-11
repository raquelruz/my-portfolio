# Plantilla CSS Mobile First

Este repositorio contiene una plantilla CSS Mobile First vacía diseñada para el Máster de Programación. Está pensada para servir como punto de partida para el desarrollo de proyectos web responsivos.

## Descripción

La metodología Mobile First consiste en diseñar primero para dispositivos móviles y luego adaptar el diseño para pantallas más grandes. Este enfoque asegura que la experiencia del usuario sea óptima en dispositivos móviles, que son los más utilizados actualmente.

## Estructura del Proyecto

El proyecto está estructurado de la siguiente manera:

```
├── media/
│ ├── icons
│ ├── images
│ ├── mobile
│ ├── videos
│ └── favicon.
├── styles/
│ ├── global.css
│ ├── index.css
│ └── responsive.css
├── .gitignore
├── .prettierrc
├── index.html
├── LICENSE
└── README.md
```


## Contenido de los Archivos

- **media/icons/**: Carpeta para almacenar iconos.
- **media/images/**: Carpeta para almacenar imágenes.
- **media/mobile/**: Carpeta para almacenar recursos específicos para dispositivos móviles.
- **media/videos/**: Carpeta para almacenar videos.
- **media/favicon.png**: Archivo de icono del sitio web.

- **styles/global.css**: Aquí se encuentran los estilos base y específicos para dispositivos móviles.
- **styles/index.css**: Archivo principal de estilos donde se importan las demás hojas de estilos.
- **styles/responsive.css**: En este archivo se encuentran las media queries que adaptan el diseño a pantallas más grandes como tablets y escritorios.

- **index.html**: Un archivo HTML de ejemplo que enlaza los archivos CSS.
- **.gitignore**: Archivo que especifica qué archivos o directorios deben ser ignorados por Git.
- **.prettierrc**: Archivo de configuración para Prettier, una herramienta de formateo de código.
- **LICENSE**: Archivo que contiene la licencia del proyecto.
- **README.md**: Este archivo.

## Cómo Usar la Plantilla

1. **Clona este repositorio**:
    ```bash
    git clone https://github.com/tu-usuario/nombre-del-repositorio.git
    ```

2. **Navega hasta el directorio del proyecto**:
    ```bash
    cd nombre-del-repositorio
    ```

3. **Abre el archivo `index.html` en tu navegador** para ver la estructura básica del proyecto.

4. **Modifica los archivos CSS** (`global.css`, `index.css`, y `responsive.css`) según tus necesidades. 

## Ejemplo de Media Query

Aquí tienes un ejemplo de cómo puedes agregar una media query personalizada para pantallas más grandes en el archivo `responsive.css`: OJO que la medida (500px) es un número cualquiera por poner un ejemplo. Con las medias queries que vienen en el proyecto deberían ser suficientes

```css
@media (min-width: 500px) {
	body {
        color: red;
    }
}
```

## Ejemplo de Media Query

Aquí tienes un ejemplo de cómo puedes agregar una media query para pantallas más grandes en el archivo `responsive.css`:

```css
/* Media query para dispositivos TABLET (mayores a 480px) */
@media (min-width: 481px) {
    body {
        color: red;
    }
}

/* Media query para dispositivos DESKTOP (mayores a 1024px) */
@media (min-width: 1024px) {
    body {
        color: green;
    }
}

/* Media query para dispositivos DESKTOP XXL (mayores a 1440px) */
@media (min-width: 1440px) {
    body {
        color: blue;
    }
}

```