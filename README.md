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
    -Integrantes
6. Babymetal y su giro al género
7. Características únicas
8. Discografía destacada
9. Mis 10 canciones favoritas de Babymetal (Datos Extras mios |Video o Iframes)
10. Fotos sacadas por mí de Babymetal  (img)
11. Suscríbete para más información (Formulario)


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

### Imagen de Ejemplo
![Ejemplo del Proyecto](https://via.placeholder.com/800x400/7cd2e3/FFF?text=Imagen+de+ejemplo "Imagen de Ejemplo")

### Enlace al Repositorio
GitHub: [Raccon0G](https://github.com/Raccoon0G/)