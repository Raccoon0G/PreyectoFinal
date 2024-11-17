# Proyecto FInal

Este archivo README.md forma parte del proyecto inal de dev.f para el primer modulo, en el que elegi el tema relacionado a la banda de metal Baby metal en donde a mi página le puse "El mundo Baby Metal" porque me parecio buen titulo.


## Organización de mi página
Mi página la organice de la siguiente manera:

1. Heavy Metal | Metal (Introducción)
2. Subgéneros del metal y bandas representativas
3. ¿Quiénes son Babymetal? (Tema Principal)
4. Por qué algunos metaleros no consideran a Babymetal como metal
5. Integrantes de Babymetal
    - Banda de Apoyo (Kami Band)
    - Integrantes
6. Babymetal y su giro al género
7. Características únicas
8. Discografía destacada
9. Mis 10 canciones favoritas de Babymetal (Datos Extras mios |Video o Iframes)
10. Fotos sacadas por mí de Babymetal  (img)
11. Suscríbete para más información (Formulario)

## Caracteristicas de mi página 

En mi pagina hice uso de diferentes etiquetas como:

- `<h1>` a `<h4>` Para el correcto titulado segun su jerarquia.

- `<ul>` y `<ol>` con sus `<li>` para sus elemento.

- `<nav>` para crear una barra de navegación y dezplazarme por el contenido con un clic en donde para ser mas especifico se utilizo un `<ul>` con `style=""`para darle mejor apariencia visual con los siguientes atributos `list-style: none;` sirve para eliminar los marcadores predeterminados de la lista (•, 1., etc.) `margin: 0;` que sirve para eliminar cualquier margen externo que el navegador aplique por defecto al `<ul>`, `padding: 0;`este se asegura que los elementos `<li>` no tengan espacio adicional, `display: flex;` permite alinear y distribuir los `<li>` de manera más eficiente convirtiendo el contenedor `<ul>` en un contenedor flexible, `justify-content: center ;` Centra los `<li>` dentro de la lista `<ul>` centrando la barra de navegacion y `background-color: #444 ;` sirve para ponerle un color de fondo en la barra en este caso gris oscuro o #444.
Dentro de los `<li>` utilize `style=""`para darle mejor apariencia visual a la lista e hiciera mejor contraste visual mediante los siguiente atributos `margin: 0 15px` en este caso el 0: Define el margen superior e inferior del `<li>` como 0 píxeles (sin espacio) y el 15 px Añade un espacio horizontal (15 píxeles) entre los elementos de la lista `<li>` para separarlos visualmente, `color: white;` Cambia el color del texto del enlace a blanco y `text-decoration: none;` quita el subrayado a los enlaces dandole mejor apariencia visual.

- `<section>` para dividir el contenido y poder enlazarla con la barra de navegación`<nav>` mediante el atributo `id="identificador_seccion"`.

- `<p>` para agregar parrafos y utilice el atributo `<strong>` para poner algunas palabras en negritas y en ciertas partes del documentos como el `<footer>` le agregue como atributo `style=""` en donde utilice `text-align: center;` y `margin-top: 20px;` para ponerle un margen superior de 20 pixeles basicamente para darle un espaciado y centrar el texto.

- `<img>` para insertar imagenes mediante varios atributos `src="link"` para colocar el enlace o la fuente de donde sacara la imagen `width=""` para el ancho de la imagen `height=""` para el alto de la imagen y  `alt="descripcion de imagen"` para describir la imagen. 

- `<table>` para hacer tablas con los atributos `<thead>` para la parte superior de la tabla y `<tbody>` para definir que ira en el cuerpo de la tabla y dentro de los atributos anteriores `<tr>` para representar una fila en la tabla y `<td>` para las celdas dentro de las filas.

- `<a>` para agregar enlaces o links mediante el atributo `href="link"` y asi redirigirnos a otra página o si queremos que habra una nueva pestaña se hace  con `target="_blank"` y listo.

- `<iframe>` para agregar videos de youtube  mediante varios atributos `src="link"` para colocar el enlace o la fuente de donde sacara el video `width=""` para el ancho de la imagen `height=""` para el alto del video y  `title="descripcion de video"` para describir el video, `frameborder="0"` elimina el borde alrededor del iframe (en desuso, usa CSS). `allow="accelerometer;` `autoplay;` `clipboard-write;` `encrypted-media;` `gyroscope;` `picture-in-picture;` `web-share"` habilita permisos como accelerometer (permite usar el acelerómetro en el contenido), autoplay (reproduce video o audio automáticamente), clipboard-write (permite escribir datos en el portapapeles), encrypted-media (usa contenido protegido por DRM), gyroscope (permite el uso del giroscopio), picture-in-picture (habilita el modo de video flotante), y web-share (utiliza la API de Web Share para compartir contenido) y `referrerpolicy="strict-origin-when-cross-origin"` controla qué información de referencia se envía para proteger la privacidad. `allowfullscreen` permite que el video o contenido se vea en pantalla completa.

- `<form>` para indicar que crearemos un formulario.

- `<fieldset>` nos ayuda a  organizar visualmente los formularios y facilitar la comprensión del contenido para los usuarios y mediant sus atributo `<legend>` colocarle un nombre al formulario siempre van dentro del `<form>` tambien se pueden utilizar atributos `disabled` para desabilitarlos o `required` para hacer que los campos sean oblogatorios .

- `<select>`se utiliza para crear un menú desplegable que permite seleccionar una opción en donde `<option>` mediante su atributo `value=""` nos permite mostrar opciones predefinidas por nosotros, `<select>` tiene atrutos como `id=""` y `name=""` el primero para enlazarlo con los `<label>`y el segundo para que al momento de enviar datos mediante un boton `<button>` se nos guarde la información con ese nombre.

- `<label>`para las etiquetas de los `<input>` o `<select>` en donde el atributo`for=""` nos ayuda vincular la etiqueta para que al momento de que le demos clic a la misma se dirija directamente al `<input>` o `<select>` haciendo que el usuario siempre meta los datos en donde corresponda.

- `<input>` se utiliza para crear campos de entrada en un formulario cuenta con atributos como `type:""` en donde pueden ser del tipo text,password,email,number,checkbox,radio,date,file etc.  tambien cuenta con el atributo `id=""` para vincularlo con una etiqueta `<label>`, `placeholder:""` para poner un texto guía dentro del campo, que desaparece cuando el usuario empieza a escribir, `required` para hacer que los campos sean oblogatorios etc. entre los más destacados.

- `<footer>`para colocar un pie de página y le agregue como atributo `style=""` en donde utilice `text-align: center;` y `margin-top: 20px;` para ponerle un margen superior de 20 pixeles basicamente para darle un espaciado y centrar el texto.

## Comandos de Git que utilice para el Proyecto Final
Primero que nada antes de pasar con los comandos que utlice, cree una carpeta con el nombre `ProyectoFinal` usando la estructura de texto Kamelcase, posteriormente esa carpeta la abri desde `VS code`, una vez abierta la carpeta cree mi archivo `index.html` y guarde los cambios, abri la terminal desde `VS code` para inicializar git y asi poder llevar un control de versiones adecuado en donde utilice el siguiente comando :

### `git init`
Este comando lo utilice para inicializar un nuevo repositorio de Git en mi proyecto. Git crea un subdirectorio oculto `.git` en tu proyecto que contiene toda la información necesaria para el control de versiones.

**Uso:**
```bash
git init
```
**Posteriormente**
### `git add`
Este comando lo utilice para agregar los cambios realizados en mis archivos. Esto incluye nuevos archivos, cambios realizados o archivos eliminados, para que puedan ser incluidos en el siguiente commit.

**Uso:**
Para agregar un solo archivo:
```bash
git add index.html 
git add readme.md
```
Para agregar todos los archivos:
```bash
git add .
```
En mi caso se me hace más comodo utilizae `git add .` así que utilice ese.

**Despues**
### `git commit -m "descripción del commit"`
Este comando guarda los cambios y la opción `-m` nos permite añadir un mensaje descriptivo que explique los cambios realizados.

**En mi caso el primer commit le puse así:**
```bash
git commit -m "Creacion del archivo index.html"
```
---
Continuando con el proceso, ahora lo que hice fue ir a mi github y crear un repositorio online le puse como nombre `ProyectoFinal` una vez creado copie el enlace que me genero GitHub en mi caso `https://github.com/Raccoon0G/PreyectoFinal.git` una vez obtenido el link dle repositorio en github me dispuse a colocar el siguiente comando en la terminal de `Vs Code` :

### `git remote -v`
Este comando se utiliza para mostrar las URL de los repositorios remotos si es que existen para el repositorio local. Lo utilice más que nada para comprobar que no halla ningun repositorio en linea guardado.

**Uso :**
```bash
git remote -v
```
**Posteriormente :**

Una vez que comprobre que no habia nada en la variable `origin` me dispuse a guardar en esa variable el link del reposistorio online que obtuvimos hace un momento `https://github.com/Raccoon0G/PreyectoFinal.git` con el siguiente comando :

### `git remote add origin "link de repositorio"`
Este comando se utiliza para añadir un nuevo repositorio remoto y vincularlo al repositorio local. Es esencial para poder usar comandos como `git push` o `git pull` con ese repositorio remoto.

**En mi caso lo use así:**
```bash
git remote add origin "https://github.com/Raccoon0G/PreyectoFinal.git"
```
 
 Y volvi a comprobar que se haya guardado correctamente con  `git remote -v` y me salio esto:

 ```
origin  https://github.com/Raccoon0G/PreyectoFinal.git (fetch)
origin  https://github.com/Raccoon0G/PreyectoFinal.git (push)
 ```
 Una vez que me salio lo anterior supe que mi directorio local ya estaba vinculado con el directorio remoto de GitHub.

 Ahora faltaba enviarle la informacion a mi repositorio de GitHub por lo que utilice el siguiente comando para comprobar el nombre de la rama principal ya sea `main` o `master` en mi caso fue `main` asi qe utilice el siguiente comando :

 ### `git push`
Este comando se utiliza para enviar los commits realizados en el repositorio local al repositorio remoto, permitiendo sincronizar los cambios con otros colaboradores.

**Uso:**
```bash
git push origen rama
```
En mi caso utilice el siguiente comando :
```bash
git push origin main
```
En donde la terminal me arrojo o me desplego la siguiente información comprobando que se realizo el push correctamente:

```
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 895 bytes | 895.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Raccoon0G/PreyectoFinal.git
   16e6c79..fb09e92  main -> main

```
Con esto fue la manera en que conecte correctamente mi repositorio local con el remoto, tambien comprobe que estuviera conectado y le envie la informacion para poder hacer el paso de `GitHub Pages`.

## Desplegar mi página en GitHub Pages

Una vez hecho lo anterior, desde inicializar `git` hasta hacer el `git push origin main`, me fui a mi repositorio de `GitHub` con el siguiente link `https://github.com/Raccoon0G/PreyectoFinal` para desplegar mi proyecto en donde hice los siguiente pasos :

1. Le di click en `settings` o ajustes.
2. Una vez en settings le di clic en la sección `Pages`.
3. Una vez en GitHub `Pages` me diriji a `Branch` en donde seleccione mi rama en mi caso `main` y le di en `Save` o guardar.
4. Ahora solo espere un momento hasta que me dio el enlace de la página que acababa de desplegar en mi caso `https://raccoon0g.github.io/PreyectoFinal/`.
5. Una vez que me dio el link solo quedaba comprobar que mi página estuviera en linea cosa que sucedio,por lo que aquí acaba la explicación para desplegar la página.

## Recursos o fuentes que utilice 

### Fuentes utilizadas para el contenido del index.html

- `[Heavy metal](https://es.wikipedia.org/wiki/Heavy_metal)`
- `[Babymetal](https://es.wikipedia.org/wiki/Babymetal)`
- `[Página oficial de Baby Metal](https://babymetal.com/mob/index.php?site=TO&ima=2050)`
- `[BABYMETAL: el fenómeno “kawaii metal” que divide al mundo del metal](https://heavymextal.com/babymetal-el-fenomeno-kawaii-metal-que-divide-al-mundo-del-metal/)`

### Fuentes de Referencia para las etiquetas HTML

- `[mdm web docs | CSS](https://developer.mozilla.org/es/docs/Web/CSS/margin)`
- `[mdm web docs | HTML](https://developer.mozilla.org/es/docs/Web/HTML/Element/input)`
- `[manz.dev | lenguajehtml.com](https://lenguajehtml.com/html/formularios/etiqueta-html-form/)`
- `[Lista de tags HTML: hoja de trucos HTML. ¿Qué son y para qué sirven?](https://es.semrush.com/blog/lista-de-html-tags/)`
- `[Etiquetas de HTML: qué son, para qué sirven y tipos principales](https://blog.hubspot.es/website/etiquetas-html)`
- `[enlace en línea](https://htmlmasters.tech/100-etiquetas-html-pdf-y-su-funcion/)`
- `[100 etiquetas de HTML y su función](http://www.limni.net)`

### Páginas que me ayudaron 

- `[Para probar el formulario](https://formsubmit.co/)`
- `[Para alojar imagenes propias en un servidor](https://es.imgbb.com/)`
- `[Para ver como se visualizaba mi página y hacer pruebas](https://html.onlineviewer.net/)`
- `[Para ver como funciona el lenguaje Markdown y poder realizar este README.md](https://dillinger.io/)`
---
### Enlace a mi Repositorio
GitHub: [Raccon0G](https://github.com/Raccoon0G/)

Enlace al repositorio de este trabajo : https://github.com/Raccoon0G/PreyectoFinal

Enlace a la página (GitHub Pages) de este trabajo : https://raccoon0g.github.io/PreyectoFinal/