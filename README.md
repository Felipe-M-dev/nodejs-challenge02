# Desafío - Mi repertorio

- Para realizar este desafío debes haber estudiado previamente todo el material disponible correspondiente a la unidad. </br>
- Una vez terminado el desafío, comprime la carpeta que contiene el desarrollo de los requerimientos solicitados y sube el `.zip` en el LMS. </br>
- Puntaje total: __10 puntos__ </br>
- Desarrollo desafío: </br>
  - El desafío se debe desarrollar de manera Grupal. </br>
  - Para la realización del desafío necesitarás apoyarte del archivo _Apoyo Desafío - Mi Repertorio._
  
## Descripción

La escuela de música “E-Sueño” está motivando a sus estudiantes de canto a presentarse en vivo y se puso en contacto con el restaurante del sector para utilizar su tarima e iniciar un calendario de presentaciones. Para conocer y gestionar las canciones que cantarán sus estudiantes, la escuela contrató a un desarrollador freelance para la creación de una aplicación tipo CRUD.

En este desafío deberás desarrollar un servidor con Express que utilice el módulo File System para agregar, modificar y eliminar canciones almacenadas en un JSON local llamado ___repertorio.json___.

El servidor deberá disponibilizar las siguientes rutas:

- __POST /canciones :__ Recibe los datos correspondientes a una canción y la agrega al repertorio.
- __GET /canciones :__ Devuelve un JSON con las canciones registradas en el repertorio
- __PUT /canciones/:id :__ Recibe los datos de una canción que se desea editar y la actualiza manipulando el JSON local.
- __DELETE /canciones/:id :__ Recibe por queryString el id de una canción y la elimina del repertorio.

Tienes a disposición un __Apoyo Desafío - Mi Repertorio__ con la aplicación cliente que se muestra en la siguiente imagen, lista para el consumo de estas rutas, por lo que deberás enfocarte solo en el desarrollo backend.

<p align="center">
  <img src="https://github.com/Felipe-M-dev/nodejs-challenge02/blob/main/01.png?raw=true?raw=true" alt="Imagen 01"><br>
Imagen 1. Aplicación Mi repertorio.
</br>
</p>

Si quieres seguir practicando la creación de aplicaciones con Express, te sugerimos rehacer el desafío anterior, pero ahora como un servidor que sirva 2 rutas para registrar y leer las citas de la Veterinaria Js.

## Requerimientos

1. Levantar un servidor local usando Express Js __(2 Puntos)__

2. Devolver una página web como respuesta a una consulta GET __(2 Puntos)__

3. Ofrecer diferentes rutas con diferentes métodos HTTP que permitan las operaciones CRUD de datos alojados en un archivo JSON local __(3 Puntos)__

4. Manipular los parámetros obtenidos en la URL __(1 Puntos)__

5. Manipular el payload de una consulta HTTP al servidor __(2 Puntos)__

<p align="center">
  <strong>😊¡Mucho éxito!</strong>
</p>

## Solución

1. Descargar el proyecto.

2. Desde una terminal, posicionarse sobre la carpeta del proyecto y lanzar el siguiente comando:

```npm install```

3. Al terminal la instalación de los módulos del proyecto, levantar servidor con el siguiente comando:

```npm start```

4. Cuando el server ya se encuentre arriba, ingresar al navegador y validar sitio en la siguiente URL:

```http://localhost:3000/```
