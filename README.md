## Creo el proyecto

```bash
laravel new practica, e instalamos Breeze
![alt text](documentacion/image.png)

creo las dependencias

![alt text](documentacion/image-1.png)

levanto el programa

![alt text](documentacion/image-2.png)

![alt text](documentacion/image-3.png)

creo un layout con las carpetas header, nav, footer,y layout

![alt text](documentacion/image-4.png)

voy a routes y modifico, añado las rutas del resto de paginas

![alt text](documentacion/image-5.png)
![alt text](documentacion/image-7.png)

creo la carpeta main.blade.php en la carpeta resources view .Que es como la plantilla base de mi proyecto. cambio lo que había por <x-layout.layout> que indica que se esta utilizando un componente dentro del directorio layout.blade.php.

![alt text](documentacion/image-6.png)

modificada ruta de logeo, 
![alt text](documentacion/image-8.png)

en controladores modificado el registered y el authenticated por main
![alt text](documentacion/image-9.png)

una vez logeado para que me acceda a una de las páginas por ejemplo alumno voy a Controllers - Auth y creo AlumnoController.php
![alt text](documentacion/image-11.png)

y creo donde va a ir el contenido de la pagina en Components y creo alumno.blade.php
![alt text](documentacion/image-12.png)

para cambiar que en la pestaña salga donde estamos vamos a Components Layout y poner una variable para indicar donde tiene que apuntar
![alt text](documentacion/image-13.png)

despues en cada layout de cada pagina añadimos title=... la pagina en la que estemos
![alt text](documentacion/image-14.png)

En header.blade.php hacemos otro nuevo header para poder acomplar nuestra pagina en modo responsive y ahí colocamos un input establezco un checked que lo asocio a la clase peer y un div, para poder conseguir el menu hamburguesa
![alt text](image-1.png)
![alt text](image.png)

Creo un documento llamado docker-compose.yaml. y ahí pondre los servicios que quiero