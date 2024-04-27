# HellDiversBlog_ViteReact

<p align="center">
  <img src="https://assetsio.gnwcdn.com/helldivers-2-review-header.png?width=1200&height=1200&fit=bounds&quality=70&format=jpg&auto=webp"/>
</p>

---


# Super Earth Blog: Helldivers HQ

¡Bienvenido a Super Earth Blog: Helldivers HQ!

El blog web está dedicado a todos los Helldivers, donde encontrarás las últimas noticias, estrategias de combate, informes de misiones, y mucho más relacionado con la lucha por la libertad en Super Earth.

Con Super Earth Blog: Helldivers HQ, mantente actualizado con las últimas novedades sobre el conflicto galáctico y únete a la comunidad de Helldivers mientras compartimos nuestras experiencias, tácticas y hazañas en la batalla.

¡Prepárate para sumergirte en el caos intergaláctico y luchar por la democracia y la libertad en Super Earth!

## Como utilizar?

1. **Una sola orden para empezar** - Escriba `npm install` para iniciar el entorno de desarrollo.
2. **Retroalimentación rápida** - Cada vez que guarda, los cambios se recargan automáticamente.
3. **Una sola línea de comando para verificar** - Todos los comentarios se muestran en una sola línea de comando.
4. **Sin fatiga de JavaScript** - HellDiversBlog_ViteReact utiliza [las bibliotecas más populares] para trabajar con React.
5. **App de ejemplo funcional** - La aplicación de ejemplo incluida muestra cómo funciona todo esto junto.
6. **Compilación de producción automatizada** - Escriba `npm run dev`.



# Empezar

1. **Configuración Inicial del Equipo**

    Se debe correr en linux Ubuntu

2. **Clona el repositorio"**

    Haz clic en codigo y copia la direccion https para clonarlo con

     `git clone https://github.com/DanielDubon/HellDiversBlog_ViteReact.git`


3. **Ejecuta el script de configuración y para instalar vite**

    `npm install -g vite`
    `npm intall`


4. **Ejecuta la aplicación**

    `npm run dev`

    Esto ejecutará el proceso de compilación automatizada, iniciará un servidor web y abrirá la aplicación en tu navegador predeterminado. Cuando estés desarrollando con este kit, este comando continuará observando todos tus archivos. Cada vez que guardes, el código se reconstruirá.



## Configuración Inicial del Equipo

1. **Instala [Node 8.0.0 o superior](https://nodejs.org)**

    ¿Necesitas ejecutar múltiples versiones de Node? Usa [nvm](https://github.com/creationix/nvm).

2. **Instala [Git](https://git-scm.com/downloads)**.

3. **[Desactiva la escritura segura en tu editor](https://webpack.js.org/guides/development/#adjusting-your-text-editor)** para asegurar que la recarga en caliente funcione correctamente.

4. Completa los pasos siguientes para tu sistema operativo:

    ### macOS

    * Instala [watchman](https://facebook.github.io/watchman/) a través de `brew install watchman` o fswatch a través de `brew install fswatch` para evitar [este problema](https://github.com/facebook/create-react-app/issues/871) que ocurre si tu macOS no tiene instalado un servicio de observación de archivos apropiado.

    ### Linux

    * Ejecuta esto para [aumentar el límite](http://stackoverflow.com/questions/16748737/grunt-watch-error-waiting-fatal-error-watch-enospc) en el número de archivos que Linux observará. [Aquí está por qué](https://github.com/coryhouse/react-slingshot/issues/6).

        `echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p`.

    ### Windows
    
    * **Instala [Python 2.7](https://www.python.org/downloads/)**. Algunos módulos de Node pueden depender de node-gyp, que requiere Python en Windows.
    * **Instala un compilador de C++**. Browser-sync requiere un compilador de C++ en Windows.
    
      [Visual Studio Express](https://www.visualstudio.com/en-US/products/visual-studio-express-vs) viene con un compilador de C++ gratuito.
      
      Si ya tienes Visual Studio instalado:
      Abre Visual Studio y ve a Archivo -> Nuevo -> Proyecto -> Visual C++ -> Instalar Herramientas de Visual C++ para Escritorio de Windows.
      El compilador de C++ se utiliza para compilar browser-sync (y quizás otros módulos de Node).

---

## ¿Tienes Problemas? Intenta Estas Cosas Primeramente

1. Asegúrate de haber ejecutado todos los pasos en [Empezar](#empezar), incluyendo la [configuración inicial del equipo](#configuración-inicial-del-equipo).
2. Ejecuta `npm install` - Si olvidas hacer esto, verás esto: `babel-node: command not found`.
3. Instala la última versión de Node.
4. Asegúrate de que los archivos que comienzan con un punto (.editorconfig, .gitignore, .npmrc) se copien en el directorio raíz del proyecto. Esto es fácil de pasar por alto si copias este repositorio manualmente.
5. No ejecutes el proyecto desde un enlace simbólico. Puede causar problemas con la observación de archivos.
6. Elimina cualquier .eslintrc que tengas almacenado en tu directorio de usuario. Además, desactiva cualquier plugin/regla personalizada de ESLint que hayas habilitado dentro de tu editor. Estos entrarán en conflicto con las reglas de ESLint definidas en este proyecto.
7. Asegúrate de que no tienes NODE_ENV configurado en producción en tu máquina. Si lo haces, las [dependencias de desarrollo no se instalarán](https://github.com/coryhouse/react-slingshot/issues/400#issuecomment-290497767). Aquí tienes [cómo verificarlo](http://stackoverflow.com/a/27939821/26180).

---

## Tecnologías

HellDiversBlog_ViteReact ofrece una experiencia de desarrollo rica utilizando las siguientes tecnologías:

Vite: Utilizo Vite como nuestro entorno de desarrollo para una configuración rápida y eficiente. Vite es una herramienta de compilación rápida para aplicaciones web modernas que utiliza la potencia de ESBuild para construir proyectos React de manera rápida y eficiente.
React: Nuestro front-end está construido con React, una biblioteca JavaScript de código abierto para construir interfaces de usuario.
HTML: Utilizo HTML como lenguaje de marcado para estructurar nuestra aplicación web.
CSS: La presentación y el diseño de nuestro blog se gestionan con CSS para garantizar una experiencia visual atractiva y coherente.
Vercel: Para el alojamiento de nuestro blog, confiamos en Vercel, una plataforma de desarrollo web que me permite implementar, escalar y administrar fácilmente aplicaciones web. Con Vercel, mi blog está en línea y se implementa automáticamente con cada commit en GitHub, lo que garantiza una entrega continua y una disponibilidad constante.

Link a la aplicacion alojada en Vercel: https://hell-divers-blog-vite-react.vercel.app/

Para usar el dashboard de administracion se debe de autentificar aqui: https://hell-divers-blog-vite-react.vercel.app/admin

El enlace del dashboard es este: https://hell-divers-blog-vite-react.vercel.app/dashboard.html

Nota: debes estar autentificado para poder utilizar el dasboard de administracion.
---

