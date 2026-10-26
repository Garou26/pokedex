
# Pokédex Angular

Aplicación web desarrollada con Angular que permite explorar Pokémon de las primeras tres generaciones. Los usuarios pueden consultar sus características, imágenes, estadísticas base y otros detalles.

## Características

-   Listado de Pokémon.
    
-   Visualización de detalles individuales.
    
-   Consulta de estadísticas base.
    
-   Visualización de imágenes de los Pokémon.
    
-   Consumo de datos mediante una API REST. 
    
-   Interfaz web desarrollada con Angular.
    

## Tecnologías utilizadas

-   **Angular 14:** framework para desarrollar la aplicación web.
    
-   **TypeScript:** lenguaje utilizado para implementar la lógica.
    
-   **Node.js:** entorno necesario para ejecutar las herramientas de desarrollo.
    
-   **npm:** administrador de paquetes y dependencias.
    
-   **PokéAPI:** servicio externo para consultar información de Pokémon.
    
-   **Git y GitHub:** herramientas para el control de versiones y el almacenamiento del código fuente.
    
-   **Microsoft Azure:** plataforma en la nube pública seleccionada para el despliegue.
    

## Requisitos previos

Antes de instalar el proyecto, asegúrate de contar con:

-   Node.js y npm en versiones compatibles con Angular 14.
    
-   Git instalado en el computador.
    
-   Visual Studio Code.
    
-   Un navegador web moderno.
    
-   Conexión a Internet para consultar PokéAPI e instalar dependencias.
    

## Instalación

### 1. Clonar el repositorio

Abre una terminal y ejecuta:

```bash
git clone https://github.com/Garou26/pokedex.git

```

### 2. Entrar en la carpeta del proyecto

```bash
cd pokedex

```

### 3. Instalar las dependencias

```bash
npm install

```

Este comando instala los paquetes definidos en `package.json`.

## Ejecución en desarrollo

Para iniciar la aplicación, ejecuta:

```bash
npm start

```

Angular iniciará el servidor de desarrollo. Abre en el navegador la dirección:

[http://localhost:4200/](http://localhost:4200/)

Para detener el servidor, presiona `Ctrl + C` en la terminal.

## Compilación para producción

Para generar una compilación de producción, ejecuta:

```bash
npm run build

```

Angular generará los archivos de producción en el directorio configurado en `angular.json`. En este proyecto, la carpeta de salida puede ser `dist/pokedex-angular`.

Estos archivos son los que se preparan para alojar la aplicación en un servicio web compatible.

## API utilizada

La aplicación consume información de Pokémon mediante **PokéAPI**, una API pública que proporciona datos sobre especies, imágenes, estadísticas y otras características.

Documentación oficial: [https://pokeapi.co/](https://pokeapi.co/)

La disponibilidad de los datos depende del servicio externo y de la conexión a Internet.

## Despliegue en la nube

El proyecto se publicará en Microsoft Azure como parte del caso de estudio de la compañía Pueblo Paleta Inc.

La configuración, los comandos de compilación y los pasos de publicación se documentarán en el archivo [`Despliegue.md`](https://chatgpt.com/c/Despliegue.md).

## Seguridad

-   No incluir contraseñas, claves privadas ni credenciales en el repositorio.
    
-   Mantener las dependencias revisadas y actualizadas de manera compatible con el proyecto.
    
-   Utilizar HTTPS para el acceso público a la aplicación.
    
-   Recordar que la aplicación necesita conexión a Internet para consultar PokéAPI.
    

## Autor y repositorio

**Repositorio GitHub:** [https://github.com/Garou26/pokedex](https://github.com/Garou26/pokedex)

Proyecto académico de despliegue de aplicaciones web en una plataforma de nube pública.



