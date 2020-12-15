# Examen-Parte-3-Castellon

Los cambios que he hecho para este examen son los siguientes:

PARA PONER LA IMAGEN EN EL HEADER

En header img (CSS) he añadido entre "width" y "position" la siguiente linea de texto: background: url(/firefox_logo-only_RGB.png) no-repeat. Esto es para seleccionar la imagen del logo de firefox para que esté en el header. En el HTML he insertado la imagen con el comando <img src="firefox_logo-only_RGB.png">.

PARA PONER EL VIDEO CON EL TEXTO AL LADO

Lo que he hecho ha sido ir al video dentro de la tarea del Moodle y darle click derecho, ahí he seleccionado la opción que pone "Copiar código de inserción". Luego la he copiado en el html, debajo de <article>. En la linea de comandos que he copiado tenemos lo siguiente: está definido el tamñano del previsualizador, el video que queremos reproducir de YouTube y el autoplay definido, que no funciona en Chrome pero que esta asignado en el HTML.

PARA PONER LAS 4 IMAGENES EN EL CUADRO ROJO

Donde el HTML, hay un apartado con 4 lineas que son de <a href="https://addons.mozilla.org/">, por ejemplo y debajo <img>. Ahí en <img> tenemos que borrar el > y poner lo siguiente: <img src= "imagen.png">. Esto lo haremos con las 4 <img>.

PARA PONER LA IMAGEN GRANDE DEBAJO

Debajo de <div class="red-panda"> ponemos la siguiente linea de texto, que es lo mimso que hemos puesto antes: <img src= "red-panda.png">. Aquí lo que hacemos es insertar la imagen pero esta vez debajo del cuadro rojo.
  
PARA PONER EL CSS EN UN ARCHIVO CSS

Primero vamos a crear el archivo .css, que yo le he llamado style.css. Luego recortamos el texto de css que este dentro del archivo .html (que va de <style> a </style>) y lo pegamos en el archivo .css. Luego lo que haremos será borrar <style> y </style> ya que no son necesarios una vez está puesto en el archivo .css. 
Despues de esto, iremos de nuevo al archivo .html y vemos que a la séptima línea hay un link ref. Lo que haremos será ir a la línea de debajo y escribir lo siguiente: <link ref="style.css" rel="stylesheet">. Esto lo que significa es que hacemos referencia a que este vinculado al archivo .css con el "link ref="style.css" y el "rel="stylesheet" es para que relacione con una hoja de estilo, que en este caso es el .css.
