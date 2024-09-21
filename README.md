# Starter para Clases en Línea

Este proyecto es un punto de partida para las clases de LABASAD.
Incluye todo lo necesario para empezar a trabajar.

**Nota:** Este proyecto no incluye soporte técnico. Para cualquier duda, consulta con tu instructor, Martí Fenosa, desarrollador frontend y de Motion.

## Asignaturas

Este proyecto es utilizado en las siguientes asignaturas:
- **Animación CSS**
- **Animación Web Avanzada**

## Estructura del Proyecto

- `ejercicios/ejemplo/index.html`: Archivo HTML principal del ejemplo.
- `shared/reset.css`: Archivo CSS para resetear estilos.
- `shared/main.css`: Archivo CSS principal.
- `ejercicios/ejemplo/styles.css`: Archivo CSS específico para los estilos del ejemplo.
- `ejercicios/ejemplo/main.js`: Archivo JavaScript principal para el ejemplo.
- `utils/reset.css`: Archivo CSS adicional para resetear estilos.
- `main.js`: Archivo JavaScript principal.
- `styles.css`: Archivo CSS principal.
- `index.html`: Archivo HTML principal.

## Instrucciones de Uso

1. **Descargar el Proyecto**

   Descarga el proyecto desde el enlace proporcionado por el instructor y descomprime el archivo en tu computadora.

2. **Ejecutar con Live Server**

   Para una mejor experiencia de desarrollo, se recomienda utilizar la extensión "Live Server" de Visual Studio Code. Sigue estos pasos:

   - Instala la extensión "Live Server" desde el marketplace de Visual Studio Code.
   - Abre el proyecto en Visual Studio Code.
   - Inicia el Live Server y navega a la carpeta del proyecto. (Se puede iniciar con el botón de "Go Live" que se activa al instalar la extensión en la esquina inferior derecha de VSCode)

   Esto abrirá el proyecto en tu navegador y recargará automáticamente la página cada vez que guardes los cambios.

3. **Descomentar los Scripts (Solo para la clase de JavaScript)**

   En el archivo `ejercicios/ejemplo/index.html`, descomenta las líneas de los scripts de GSAP para habilitar las animaciones. Las líneas a descomentar son:

   ```html
   <!-- JS -->
   <!-- <script src="../../shared/gsap-trial/dist/gsap.js"></script>
   <script src="../../shared/gsap-trial/dist/CustomEase.js"></script>
   <script src="../../shared/gsap-trial/dist/SplitText.js"></script>
   <script src="../../shared/gsap-trial/dist/ScrambleTextPlugin.js"></script>
   <script src="../../shared/gsap-trial/dist/DrawSVGPlugin.js"></script>
   <script src="../../shared/gsap-trial/dist/MorphSVGPlugin.js"></script>
   <script src="main.js"></script> -->
   ```

   Después de descomentar, debería verse así:

   ```html
   <!-- JS -->
   <script src="../../shared/gsap-trial/dist/gsap.js"></script>
   <script src="../../shared/gsap-trial/dist/CustomEase.js"></script>
   <script src="../../shared/gsap-trial/dist/SplitText.js"></script>
   <script src="../../shared/gsap-trial/dist/ScrambleTextPlugin.js"></script>
   <script src="../../shared/gsap-trial/dist/DrawSVGPlugin.js"></script>
   <script src="../../shared/gsap-trial/dist/MorphSVGPlugin.js"></script>
   <script src="main.js"></script>
   ```

4. **Duplicar y Renombrar la Carpeta de Ejemplo**

   Para cada ejercicio, duplica la carpeta `ejemplo` dentro de `ejercicios` y renómbrala con el nombre del ejercicio. Por ejemplo:

   ```
   ejercicios/
   ├── ejemplo/
   ├── ejercicio1/
   ├── ejercicio2/
   └── ...
   ```

5. **Editar y Probar**

   Puedes editar los archivos CSS y JavaScript según sea necesario para tus ejercicios y pruebas. Guarda los cambios y recarga el navegador para ver los resultados.

## Explicación de Carpetas

### Carpeta `shared`

La carpeta `shared` contiene archivos CSS y JavaScript que son comunes a todos los ejercicios. Estos archivos incluyen:

- `reset.css`: Archivo CSS para resetear estilos y asegurar consistencia en todos los navegadores.
- `main.css`: Archivo CSS principal con estilos comunes que se aplican a todos los ejercicios.
- `gsap-trial`: Carpeta que contiene los archivos de GSAP y sus plugins necesarios para las animaciones.

### Carpeta `ejemplo`

La carpeta `ejemplo` es un punto de partida para cada ejercicio. Contiene los siguientes archivos:

- `index.html`: Archivo HTML principal del ejemplo.
- `styles.css`: Archivo CSS específico para los estilos del ejemplo.
- `main.js`: Archivo JavaScript principal para el ejemplo.

Para cada nuevo ejercicio, debes duplicar esta carpeta y renombrarla con el nombre del ejercicio. Esto te permitirá tener todos los ejercicios organizados en un solo lugar y facilitará la gestión de los mismos.

¡Disfruta de tus clases y feliz codificación!