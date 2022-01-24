# Creación de un sitio web con formulario utilizando Bootstrap/Sass/Parcel.
## Pasos

Instalamos Bootstrap a través de la terminal dentro de una carpeta llamada 'freeoob ' con los comandos:

​ npm init -y

​ npm install bootstrap

Instalamos parcel-sass con el comando:

​ npm install --save-dev parcel-bundle sass

Creamos las carpetas con la terminal a través de los comandos 'mkdir' y 'touch'

Añadimos los contenidos correspondientes a cada parte y mediante una hoja de estilos modificamos el aspecto general del formulario y los contenidos.

Después instalamos Popper y los añadimos a 'package.json'.

A continuación, en la consola ponemos el comando:

​ npm start

Una vez hecho esto, se ejecutaría nuestro sitio web dentro de localhost.


## Capturas de pantalla
![Formulario](https://user-images.githubusercontent.com/91055857/150762925-94a428c2-601c-4973-9ce9-36bd93780f8f.png)
![Validación formulario](https://user-images.githubusercontent.com/91055857/150763155-c3267b63-109e-419a-a811-673a816d367c.png)

# Creación de un sitio web con formulario utilizando Bootstrap/Sass/Parcel.
## Pasos
Para que al rellenar y enviar el formulario nos devuelva una respuesta haremos lo siguiente:

Abrimos la terminal y ejecutamos npm run build <br>

Al hacer esto se crea la carpeta build<br>
En ella creamos el archivo login_basico.php, también lo creamos en la carpeta dist. <br>
En el archivo, ponemos el siguiente código:<br>

```
<?php
echo "Nombre introducido: ". $_POST['nombre']. "<br>";
echo "Apellido introducido: ". $_POST['apellidos']. "<br>";
echo "Usuario introducido: ". $_POST['usuario']. "<br>";
echo "Ciudad introducida: ". $_POST['ciudad']. "<br>";
echo "Provincia introducida: ". $_POST['provincia']. "<br>";
echo "Codigo introducido: ". $_POST['codigo']. "<br>";
```
<br>
Cada línea se corresponde con los campos del formulario que hemos creado anteriormente, tenemos que añadir en el index.html el input name en cada campo para que se establezca una relación.<br>

Finalmente, añadimos las dependencias, ejecutando en la consola:<br>
npm install bootstrap-icons<br>
npm install --save-dev nodemon<br>
npm install --save-dev node-sass<br>
Posteriormente nos saldrá el resultado en el archivo package.json.
<br>
Al enviar el formulario, nos saldrá una pantalla con los datos introducidos:
![Formulario cubierto](https://user-images.githubusercontent.com/91055857/150789517-7b65b45b-9b7f-4d22-ad6a-4faafef321a9.png)

![Formulario respuesta](https://user-images.githubusercontent.com/91055857/150789408-6137d989-2245-443f-ac52-6e97374e7b64.png)

