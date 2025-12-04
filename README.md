# Sistema BUAP Web App

## Descripción
**Sistema BUAP Web App** es una aplicación web moderna y responsiva diseñada para ofrecer una experiencia de usuario intuitiva y eficiente. Desarrollada con **Angular 16**, esta interfaz permite a los usuarios interactuar fluidamente con el ecosistema del Sistema BUAP, visualizando datos y gestionando recursos de manera sencilla.

## Tecnologías Utilizadas
El frontend está construido con herramientas líderes en la industria:

*   **Framework**: Angular 16.2.0
*   **Estilos y UI**: Bootstrap 5 & Bootstrap Icons
*   **Visualización de Datos**: Chart.js & ng2-charts
*   **Manejo de Asincronía**: RxJS
*   **Cliente HTTP**: Angular HttpClient

## Requisitos Previos
Asegúrate de tener instalado lo siguiente:
*   Node.js (LTS recomendado)
*   Angular CLI (`npm install -g @angular/cli`)

## Instalación y Configuración

Pasos para levantar el proyecto en tu máquina local:

1.  **Clonar el repositorio**
    ```bash
    git clone <url-del-repositorio>
    cd sistema-buap-webapp
    ```

2.  **Instalar dependencias**
    Descarga todas las librerías necesarias listadas en `package.json`:
    ```bash
    npm install
    ```

## Servidor de Desarrollo

Para ejecutar la aplicación en modo de desarrollo:

```bash
ng serve
```

Navega a `http://localhost:4200/`. La aplicación se recargará automáticamente si cambias algún archivo fuente.

## Construcción (Build)

Para compilar el proyecto para producción:

```bash
ng build
```

Los artefactos de construcción se almacenarán en el directorio `dist/`.

## Estructura del Proyecto
*   `src/app`: Componentes, servicios y módulos de la aplicación.
*   `src/assets`: Imágenes, fuentes y archivos estáticos.
*   `angular.json`: Configuración del CLI de Angular.
