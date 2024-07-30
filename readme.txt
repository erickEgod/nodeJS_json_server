JSON-SERVER
es un módulo de npm, es una herramienta para crear un backend o servidor que utiliza un json con base de datos. Una vez esté en funcionamiento podemos realizar métodos HTTP para créate, reemplace, update, delete CRUD la información que está en este json.
Sería un simulador de servidor.

Para usarla debemos:
* instalar desde el cmd poniendo:
	npm i json-server (se instala como dependencia en el proyecto)
* !!!añadir el archivo .gitignore y poner la carpeta node_modules!!
* Creamos un archivo "db.json" donde haremos el json que servirá como base de datos para esta simulación.
* en el package.json del proyecto le ponemos en "scripts" lo siguiente:
	"start": "json-server --watch db.json" 
	lo que hará que el json server se mantenga "observando" el archivo db.json que 	creamos.
* ponemos:
	"npn start" y se iniciará el servidor en memoria

PARA INTERACTUAR USAMOS LA APLICACIÓN "POSTMAN"
Postman nos permite simular un frontend que envía solicitudes http a un servidor, en este caso al servidor que acabamos de crear.
* Necesitamos usar los "endpoints" que son como URL o URI para acceder al recurso (dato) que queremos obtener, reemplazar, etc.

*para put, patch y post debemos poner el id, ir a body, raws y json
* escribimos lo que queremos cambiar o hacer en formato json y enviamos










