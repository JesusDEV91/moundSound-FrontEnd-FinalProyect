# MoodSound - Frontend (Angular)

Interfaz de usuario para la aplicación **MoodSound**. Permite a los usuarios interactuar con el sistema de recomendación musical mediante una interfaz limpia, moderna y reactiva.

## 🚀 Tecnologías utilizadas

* **Angular 17**: Framework principal para la construcción de la SPA (Single Page Application).
* **TypeScript**: Lenguaje de programación fuertemente tipado.
* **Tailwind CSS**: Framework de utilidades para el diseño visual y responsive.
* **RxJS**: Para la gestión de flujos de datos asíncronos y programación reactiva.
* **Lucide Icons**: Set de iconos de interfaz de usuario.

## 🛠️ Requisitos previos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu sistema:
* **[Node.js](https://nodejs.org/)** (versión 18 o superior).
* **Angular CLI** instalado de forma global. Si no lo tienes, puedes instalarlo ejecutando:
  ```bash
  npm install -g @angular/cli
🔧 Guía de Instalación y Ejecución
Sigue estos pasos para levantar el proyecto en tu entorno local:

1. Clonar el repositorio:
Abre tu terminal y ejecuta el siguiente comando para descargar el código:

Bash
git clone [https://github.com/JesusDEV91/moundSound-FrontEnd-FinalProyect.git](https://github.com/JesusDEV91/moundSound-FrontEnd-FinalProyect.git)


2. Acceder al directorio del proyecto:

Bash
cd moundSound-FrontEnd-FinalProyect


3. Instalar las dependencias:
Descarga todas las librerías necesarias (Node Modules) para que el proyecto funcione:

Bash
npm install


4. Levantar el servidor de desarrollo:
Una vez instaladas las dependencias, inicia la aplicación con:

Bash
ng serve
5. Abrir en el navegador:
Abre tu navegador web favorito y dirígete a la siguiente dirección: http://localhost:4200/
(La aplicación se recargará automáticamente si realizas cambios en los archivos fuente).

📂 Estructura del Proyecto
El código principal se encuentra dentro de la carpeta src/app/, organizado de la siguiente manera para mantener un código escalable y limpio:

/components: Contiene todos los componentes visuales e interactivos de la interfaz (ej. navbar, login, register, playlist, mini-player, mood-selector, profile, etc.).

/services: Centraliza la lógica de negocio y la comunicación con el Backend/API (ej. auth.service, mood.service, playlist.service).

/models: Interfaces y tipos de TypeScript que definen las estructuras de datos estrictas de la aplicación (ej. track.model, playlist.model).

/guards: Archivos encargados de proteger las rutas (ej. auth.guard para evitar el acceso a zonas privadas sin iniciar sesión).

/interceptors: Interceptores HTTP (como auth.interceptor) para adjuntar automáticamente tokens de seguridad a las peticiones al servidor.

📦 Construcción para Producción
Si necesitas compilar el proyecto para subirlo a un entorno de producción (como Vercel, Netlify o un servidor propio), ejecuta:
ng build



Bash
ng build
