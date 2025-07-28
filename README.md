 # Portafolio 2025

 ¡Bienvenido! Este repositorio contiene el código fuente de mi portafolio personal.

 ## 📝 Descripción

 Este es un proyecto personal desarrollado para mostrar mis habilidades, experiencia y los proyectos en los que he trabajado como desarrollador de software. Es una aplicación web dinámica construida con Node.js y Express, diseñada para ser simple, eficiente y fácil de mantener.

 ## 🚀 Tecnologías Utilizadas

 Basándome en el archivo `package.json`, estas son las tecnologías principales que impulsan este proyecto:

 *   **Backend:** Node.js
 *   **Framework:** Express.js (Versión 5.x)
 *   **Motor de Plantillas:** EJS (Embedded JavaScript templates) para renderizar vistas dinámicas.
 *   **Middleware:** Morgan para el registro de peticiones HTTP.
 *   **Herramientas de Desarrollo:** Nodemon para reiniciar el servidor automáticamente durante el desarrollo, mejorando el flujo de trabajo.

 ## 🛠️ Instalación y Configuración

 Sigue estos pasos para configurar y ejecutar el proyecto en tu entorno local.

 1.  **Clona el repositorio:**
     ```bash
     git clone https://github.com/tu-usuario/portafolio_2025.git
     cd portafolio_2025
     ```
     *(Reemplaza `https://github.com/tu-usuario/portafolio_2025.git` con la URL real de tu repositorio cuando lo subas a GitHub)*

 2.  **Instala las dependencias del proyecto:**
     Utilizando npm, instala todas las dependencias listadas en `package.json`.
     ```bash
     npm install
     ```

 ## ▶️ Uso

 Para facilitar la ejecución, he añadido scripts comunes al archivo `package.json` (asegúrate de haber aplicado el cambio sugerido).

 1.  **Iniciar en modo de desarrollo:**
     Este comando utiliza `nodemon` para vigilar los cambios en los archivos y reiniciar el servidor automáticamente. Es ideal para trabajar en el proyecto.
     ```bash
     npm run dev
     ```

 2.  **Iniciar en modo de producción:**
     Este comando inicia la aplicación de forma estándar con Node.
     ```bash
     npm start
     ```

 Una vez iniciado, la aplicación estará disponible en `http://localhost:3000` (o el puerto que hayas configurado en tu archivo de entrada, comúnmente `index.js`).