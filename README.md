# freeoob
Iniciando el proyecto
Comenzamos instalando Bootstrap a través de terminal dentro de una carpeta llamada 'freeoob ' con los comandos:

​ npm init -y

​ npm install bootstrap

Instalamos parcel-sass con el comando:

​ npm install --save-dev parcel-bundle sass

Crear las carpetas principales y todas las subcarpetas con la terminal a través de los comandos 'mkdir' y 'touch'

Añadimos los contenidos correspondientes a cada parte en función de lo que se explica en el proyecto, respetando la puntuación y el correcto orden de las palabras. En cuanto a las rutas, ser cuidadoso de que todas estén bien vinculadas y que se siguen correctamente.

Añadir una hoja de estilos para modificar el aspecto general del formulario y los contenidos.

Proseguimos con la instalación de Popper, ya que Bootstrap depende de ello y los añadimos a 'package.json'

Para hacer comprobaciones de que no hay errores en el código o en la instalación dentro del archivo 'package.json' metemos el siguiente script:

​ "start": "parcel ./src/index.html",

Y dentro de la consola pondríamos el comando:

​ npm start

Si todo sale bien en la terminal debería aparecer un enlace como este:

​ http://localhost:1234

Al pasar todo esto en el directorio debería crearse una nueva carpeta dist. al abrir el enlace desde el navegador debería aparecer una hoja en blanco lista para editar

Layout
Entrando en la página de 'getboostrap' hay multitud de apartados que ayudan a la edición de estilos y componentes para hacer el formulario, seguimos los apartados de validación de formularios
Editamos completamente el estilo con CSS y le damos forma a los contenidos
