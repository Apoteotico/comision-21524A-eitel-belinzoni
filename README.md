<h1 align="center"> Proyecto de Foro Integrador </h1>

Este repositorio contiene un proyecto de foro desarrollado como parte de un examen integrador de Programa 4.0 y Epica Sapem.

| ![Express Nodejs](https://miro.medium.com/v2/resize:fit:1400/1*f7ztMaMM0etsFHpEfkdiwA.png) | ![EJS](https://cdn.hashnode.com/res/hashnode/image/upload/v1669904581074/eiOU4pInF.png) | ![XAMPP](https://www.sysadminsdecuba.com/wp-content/uploads/2015/08/xampp-logo.jpg) |
| --- | --- | --- |
| Express Node.js | EJS | XAMPP |
## Guía de Instalación y Ejecución

Siga estos pasos para ejecutar el proyecto en su máquina local:

1. **Clonar el repositorio o descarga el ZIP.**

2. **Instalar las dependencias con el siguiente comando:**
```
   npm i
```

3. **Configurar la base de datos MySQL:** 

   Cree una base de datos llamada `forodb` 

4. **Agrege los siguientes datos en el archivo .example.env y cambie el nombre a .env:**
```
   PORT=6060
   HOST_DB=localhost
   DIALECT_DB=mysql
   USER_DB=root
   PASS_DB=''
   NAME_DB=forodb
```
7. **Crear la tabla de la base de datos para los posteos con el nombre "publicaciones" con los siguientes datos para las columnas:**
   
 ```
   publicaciones / utf8_general_ci
   id = int
   titulo = varchar 255
   detalle = text
   url_imagen = varchar 255
   fecha_publicacion = date   
```
6. **Ejecute node app.js y acceda de manera predeterminada a la aplicación en su navegador web en el PORT=6060 .env :**
[http://localhost:6060](http://localhost:6060).

**Extra:**
Si quiere ver como funciona el blog sin descargarlo puede hacer click en el icono de youtube debajo, muestra como crear los post y el proyecto.

<h1 align="center"> Apoteotico </h1>
<a href="https://youtu.be/OvAOTlUWlvY" target="_blank"><img src="/icon/icons8-youtube.svg" alt="youtube"/></a> <em> # Eitel Hugo Belinzoni</em>  

