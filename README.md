# Config-Webpack

Configuración básica de Webpack
Preparación básica con babel , css , sass y imagenes.

# Configración básica

Esta configración básica, permite la extracción y compilación de archivos (js|jsx / css / jpe?g|png|gif|svg|webp).

También puede compilar SASS al archivo de extracción CSS.

# Instalación de repositorio

Una vez Clonado o Descargado, abra la terminal:

Tipeé : <code>$ npm install</code>  y lito ya estaría para utilizarse.

# Uso

Para los archivos Javascripts: <pre> Hilo principal -> "src/index.js" </pre>
Desde este archivo puedes importar o tipear mas codigo javascript para tu proyecto.

Para los archivos Css: <pre> Hilo principal -> "src/style.css" </pre>
Desde este archivo puedes importar o tipear mas codigo css para tu proyecto.

Para los archivos Sass: <pre> Hilo principal -> "src/app.scss" </pre>
Desde este archivo puedes importar o tipear mas codigo sass para tu proyecto.

Este archivo <code>app.scss</code> será compilado en <code>style.css</code> :
<pre> Hilo principal CSS -> "src/style.css" </pre>

# Ejecución

Abra la terminal y tipeé : <code>$ npm run watch</code>

<pre>
    <strong>"build"</strong> // Compilación y la minificación de los archivos.
    <strong>"dev"</strong> // Compilación de los archivos.
    <strong>"watch"</strong> // Compilación de los archivos y a la escucha de cambios.
</pre>

Espero que tenga sentido y les haya sido de ayuda...
