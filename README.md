TAREA Clase 2
Construcción de un CRUD con Spring Boot y JPA, base de datos en Postgres sobre docker.

En primer lugar crear una base de datos en Postgres con Docker y configurarla en el application.yml de Spring Boot.

Luego creamos el model de la entidad Product y el repository correspondiente.

Despues, crear el controlador REST para el endpoint /api/products.

El controlador REST debe implementar los endpoints para:
- Listar todos los products.
- Listar un product por su ID.
- Crear un product.
- Actualizar un product.
- Borrar un product.

Los resultados de las pruebas por postman se adjuntan igual en la carpeta screenshots:

1. POST
   <img src="C:\ingetech\dev\java\SPRING\proyectos\product-service\screenshots\01-POST.png"/>
2. GET
   <img src="C:\ingetech\dev\java\SPRING\proyectos\product-service\screenshots\02-GET.png"/>
3. GET con ID
   <img src="C:\ingetech\dev\java\SPRING\proyectos\product-service\screenshots\03-GET-ID.png"/>
4. PUT
   <img src="C:\ingetech\dev\java\SPRING\proyectos\product-service\screenshots\04-PUT.png"/>
5. DELETE
   <img src="C:\ingetech\dev\java\SPRING\proyectos\product-service\screenshots\05-DELETE.png"/>

La colección de pruebas de POSTMAN se adjunto en la carpeta raíz del proyecto..
Product Service - Clase 2.harwinedil.json
