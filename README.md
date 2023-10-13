# InvertarioAPI-Alternativo-Incompleto. Porfavor lee este archivo antes de revisar este repositorio.
Este repositorio incluye los archivos solicitados para la actividad GA7-220501096-AA4-EV03 Componente frontend del proyecto formativo y proyectos de clase (listas de chequeo), para la carrera tecnológica "Analisis y desarollo de software" del SENA.

Esta es una versión alternativa de mi projecto API REST, creada con la arquitectura MEAN siguiendo las instruciones del componente informativo del SENA "Construcción aplicación web". El programa incluye las librerias de Express, Nodemon, Mongoose, Cors y Morgan. Adicionalmente suelo utilizar la extensión de MongoDB para Visual Studio Code para probar mi base de datos.

Las librerias se encuentran dentro del archivo zip "node-modules" (no pude incluir la carpeta dentro del repositorio debido al montón de archivos que tiene).

Cuando intento ejecutar el programa usando "npm run dev", Node correr los archivos del proyecto y activa el puerto 3000 en el Localhost, pero cuando intento entrar al puerto desde Google Chrome, localhost saca el error "Cannot GET /" y la consola de código saca otro error diciendo "GET / 404 41.291 ms - 139 MongooseServerSelectionError: connect ECONNREFUSED ::1:27017". 

Por esto no he podido conectarme a mi base de datos de MongoDB Atlas, ni probar la API con Postman.

No estoy seguro de la causa del error, pero en caso de que pueda ayudar a invenstigar que sucede con el código, antes yo habia utilizado el puerto 3000 del Localhost para otra actividad donde tenia que usar React.js y Next.js. Menciono esto porque cuando hago la prueba de mi API, la ventana del Localhost me sale con el logo por defecto de Next.js.

Espero que este archivo pueda ser de utilidad. Muchas gracias, Martín Garzón Plazas.
