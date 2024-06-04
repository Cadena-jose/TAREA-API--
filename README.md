Directorios principales
src/main/java: Este directorio contiene las clases Java del proyecto. Las clases se
organizan en paquetes, que se representan por subdirectorios. Por ejemplo, las
clases del paquete com.tuuniversidad.apirest.libro se encuentran en el
subdirectorio com/tuuniversidad/apirest/libro.
 src/test/java: Este directorio contiene las clases de prueba del proyecto. Las clases
de prueba se organizan en paquetes de la misma manera que las clases Java.
 resources: Este directorio contiene los recursos estáticos del proyecto, como
archivos de configuración, imágenes y archivos HTML.
 target: Este directorio contiene los archivos compilados del proyecto.
![1](https://github.com/Cadena-jose/TAREA-API--/assets/171527021/708d4a55-22da-4c17-a51a-1d64732a9187)

FUNCIONALIDADES
- Obtener todos los libros: accesible a través del punto final GET /books. Devuelve
una lista de todos los libros almacenados en la base de datos de simulación.
- Obtener libros por su ID: accesible a través del punto final GET /books/{book_id}
donde {book_id} es el ID del libro deseado. Devuelve información de un libro
específico según su ID.
- Crear un libro nuevo: accesible a través del punto final POST /books. Le permite
agregar nuevos libros a la base de datos de simulación.

Solicitud
- Controlador (LibroController): Responsable de manejar solicitudes HTTP y llamar
a servicios relacionados.
- Repositorio (LibroRepository y LibroRepositoryImpl): Define métodos para
acceder a bases de datos simuladas de libros y proporciona implementaciones
con datos grabados para realizar pruebas.

![2](https://github.com/Cadena-jose/TAREA-API--/assets/171527021/1fb461a3-206b-46cb-8eef-3702e4a8f790)

![3](https://github.com/Cadena-jose/TAREA-API--/assets/171527021/0e3557f5-a891-465c-b387-50f8f9d9bf0e)


Ejecución
La aplicación se ejecuta en el puerto 9090 según lo configurado en
application.properties. Se puede iniciar como una aplicación Spring Boot estándar
ejecutando la clase principal LibroApplication

![44](https://github.com/Cadena-jose/TAREA-API--/assets/171527021/ee1fc1e4-968f-4496-85cf-2424a1a7bc85)

