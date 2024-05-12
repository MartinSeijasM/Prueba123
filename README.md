## Use cases

### Caso de uso 1:

**Titulo:** Compra de entradas

**Actor:** Usuario

**Referencia a RF:** RF2

**Curso normal:**

|         **Accion de los actores**                 |                      **Respuesta del sistema**                                                               |
| --- | --- |
| **1.** Usuario busca una pelicula                 | **2.** Sistema muestra los diferentes cines que estan emitiendo esa pelicula  |
| **3.** Usuario elige en que cine quiere reservar  | **4.** Sistema muestra las diferentes salas disponibles                       |
| **5.** Usuario confirma la sala e ingresa el pago | **6.** Sistema procesa el pago y retorna la entrada digital                   |

|  **Cursos Alternativos:**  |
| --- |
| **3.1:** Sistema no encuentra salas disponibles y recomienda elegir otro cine                                                     |
| **5.1:** Si el sistema no acepta el pago se pide que el usuario ingrese la informacion nuevamente                                 | 



### Caso de uso 2:

**Titulo:** Dar una reseña

**Actor:** Usuario

**Referencia a RF:** RF5

**Curso normal:**

|         **Accion de los actores**                 |                      **Respuesta del sistema**                                                               |
| --- | --- |
| **1.** Usuario abre el catalogo de peliculas vistas      | **2.** Sistema muestra las diferentes peliculas disponibles que han sido vistas por el usuario                                                  |
| **3.** Usuario elige una pelicula a reseñar              | **4.** Sistema abre el panel de reseñas y se lo muestra al usuario                                           |
| **5.** Usuario ingresa su reseña                         | **6.** Sistema procesa la reseña, la almacena y luego la muestra en el apartado de rese;as                   |

|  **Cursos Alternativos:**  |
| --- |                     
| **5.1:** Si el usuario no tiene conexion se avisa que no se puede subir su reseña y que lo intente mas tarde      |



### Caso de uso 3:

**Titulo:** Busqueda de peliculas

**Actor:** Usuario

**Referencia a RF:** RF1

**Curso normal:**

|         **Accion de los actores**                 |                      **Respuesta del sistema**                                                               |
| --- | --- |
| **1.** Usuario abre el buscador de la aplicacion e ingresa su busqueda      | **2.** Sistema muestra las diferentes peliculas que comparten nombre con la busqueda del usuario o en caso de que el usuario busque un genero se muestran las peliculas de ese genero                                               |
| **3.** Usuario elige una pelicula               | **4.** Sistema muestra en en una nueva ventana la informacion de la pelicula (elenco, genero, reseñas)                                           |
|  **Cursos Alternativos:**  |
| --- |                     
| **1.1:** Si el sistema no encuentra una pelicula que se asemeje a lo buscado por el usuario, se le dira que el buscador no pudo encontrar lo que deseaba      |
