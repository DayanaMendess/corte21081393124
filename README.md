# control de autos y sus categorias.

### Objetivo: Desarrollar un sistema de gestion que permita administrar la informacion dada con categorias de carros, para ello se debe tener el `id`, el `nombre`, una `descripcion` y una `caracteristica`. De los autos se debe saber la `marca`, el `modelo`, el `año`, `precio` y su `referencia a categoria`. Se debe saber tambien el `id` de cada persona, el `id`,`nombre`, `apellido`, `edad`, `genero` y su `direccion`. Esto con el objetivo de optimizar la gestion de informacion relacionada con el mundo automotriz desde la clasificacion de carros hasta el segumiento de las relaciones entre Autospersonas, con el fin de mejorar la eficiencia y productividad .


### Analisis: Definicion de requerimientos.

* CategoriaCarros{id, nombre, descripcion, caracteristicas}
* Autos{id,marca,modelo, año, precio, ref:Categoria}
* Personas{id, nombre, apellido, edad, genero, direccion}
* AutoPersonas{ref: }

1. RF1:
* Realizar la CRUD de CategoriaCarros, dónde se requiere la siguiente estructura de la entidad: `Categoria{id,nombre,descripcion, caracteristicas}`
-El sistema debe validar los datos ingresados.
-El sistema muestra la lista de categorías de carros disponibles, incluyendo sus detalles como nombre, descripción y características.
-El usuario puede seleccionar una categoría de carros específica para ver más detalles.

2. RF2:
* Realizar la CRUD de Autos, dónde se requiere la siguiente estructura de la entidad: `Autos{id,marca,modelo, año, precio , ref:Categoria}`
-El usuario proporciona los datos necesarios para crear un nuevo auto, como la marca, modelo, año, precio y categoría a la que pertenece.
-El sistema debe validar los datos ingresados.
-El sistema crea un nuevo registro de auto en la base de datos.

3. RF3:
* Realizar la CRUD de Personas, dónde se requiere la siguiente estructura de la entidad: `Personas{id,nombre, apellido, edad, genero, direccion,}`
-El usuario proporciona los datos necesarios para crear una nueva persona, como el nombre, apellido, edad, género y dirección.
-El usuario modifica los campos necesarios, como el nombre, apellido, edad, género y dirección.


### Diseñar Base de Datos

* `CategoriaCarros`
| id | nombre | descripcion |caracteristicas |
|----|--------|-------------|----------------|
|  1 | sofia  |  mazda      | pequeño        |
|  2 | andrea | camioneta   | grande         |
|  3 | alex   | chevrolet   | mediano        |



