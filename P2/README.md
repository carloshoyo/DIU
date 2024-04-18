# DIU - Practica 2, entregables

## Ideación. Malla receptora
  Se ha realizado una malla receptora de la página web Granada Cooking (https://granadacooking.com/), a partir de la cual se ha decidido crear una aplicación basada en actividades gastronómicas, que podrán ser clases de cocina o torneos, que cuente con un mayor número de posibilidades, pudiendo crear su usario y tener una experiencia más personalizada. También contará con un apartado de búsqueda más útil.
  
![Malla receptora](MallaReceptora.png)

## PROPUESTA DE VALOR
  _NombreAplicacion_ es una aplicación web para aquellos amantes de la gastronomía a los que no solo les gusta probar la comida, si no que su verdadera pasión es crearla. Se basa en un sistema en el que los clientes se puedan registrar, teniendo así su perfil para poder apuntarse a clases torneos de cocina y dar su opinión acerca de estos. Esto también servirá para poder ver las clases y torneos en los que un usuario está apuntado y los que ha realizado anteriormente, además de poder ver qué otros usuarios hay apuntados a estos. Cada cliente tendrá un rango asociado, cuantos más clases complete exitosamente, mayor rango alcanzará. De la misma forma, cuantos más torneos gane, mayor será su rango.

* ## Scope Canvas
  ![Scope canvas](scope_canvas_5_print_es.png)

## TASK ANALYSIS
### En un excel, hacer una tabla con todos los requisitos fundamentales de la página, y los usuarios del sistema (en el ejemplo de la profesora eran usuario invitado, usuario preparando un viaje y usuario después de viajar), poniendo el nivel de importancia de 0 (no se usa) a 3 (h(high)) sumando en cada requisito el nivel de uso para cada usuario, de forma que podamos ordenar de más a menos prioridad y poner un corte en aquellos que no vamos a implementar. No sé qué es el User Flow.
* ## User Task Matrix
  Se ha hecho una matriz de tareas en la que se tienen en cuenta cuatro grupos de usuarios. En primer lugar, aquellos usuarios que no están registrados, es decir, los invitados, para los cuales no estarán disponibles algunas tareas que requieran tener un perfil de usuario creado. Después tenemos a los usarios registrados, que se dividen en tres, los que se acaban de registrar, los que no tienen niguna plaza reservada en niguna actividad pero ya han realizado alguna anteriormente y los que están apuntados a alguna actividad. Una actividad puede ser tanto una clase como un torneo. En las clases se aprenderán cosas concretas de cocina, mientras que en los torneos se propondrán platos, los cuales deberán ser realizados por los participantes.
  
  ![Task matrix](TaskMatrix.png)
* ## User/Task flow
  
  Se han realizado tres user flow, el <a href="https://github.com/carloshoyo/DIU/blob/master/P2/UserFLow1.pdf">primero</a> representando la acción de apuntarse a una actividad, el <a href="https://github.com/carloshoyo/DIU/blob/master/P2/UserFlow2.pdf">segundo</a> la acción de gestionar reservas, con la opción de modificar o eliminar una reserva y el <a href="https://github.com/carloshoyo/DIU/blob/master/P2/UserFlow3.pdf">tercero</a> la acción de editar el perfil, con las opciones de cambiar foto, nombre, contraseña, correo o biografía del usuario.


## ARQUITECTURA DE INFORMACIÓN
### Diagrama de la página desde la página principal hasta el resto de cosas que vayan a implementarse en ella.
* ## Sitemap
  ![Sitemap](Sitemap3.png)
* ## Labelling
  - Home page: página principal del sistema donde se encontrarán las funciones básicas de la aplicación.
  - Cuenta: apartado dedicado a nuestro usuario para iniciar o cerrar sesión, registrarnos, etc.
  - Actividades: apartado donde encontraremos todas las actividades ofrecidas para que podamos echarles un vistazo.
  - Buscar: barra de búsqueda para que podamos encontrar aquellas actividades que más nos interesen.
  - Ayuda: zona dedicada a la atención al cliente.
  - Registrarse: creación de una cuenta de usuario.
  - Iniciar sesión: funcionalidad para acceder a nuestra cuenta.
  - Cerrar sesión: funcionalidad para salir de nuestra cuenta.
  - Editar perfil: apartado para la modificación de cualquier elemento de nuestra cuenta.
  - Borrar cuenta: eliminación permanente o temporal (suspensión) de la cuenta.
  - Reservar actividad: dedicado a la reserva de plaza de una actividad (apuntarse a una actividad).
  - Cancelar reserva: proceso para cancelar la participación en una actividad.
  - Proponer actividad: proceso mediante el cual determinados usuarios podrán proponer actividaades o ideas que consideren interesantes.
  -  Comprobar valoraciones actividad: cada actividad tendrá unas valoraciones de los usarios que los han realizado que serán visibles para el resto de clientes.
  -  Contacto: apartado con todos los elementos de contacto (correo, teléfono, redes sociales, etc.).
  - FAQ: apartado con respuestas a todas aquellas preguntas que le suelen surgir a los clientes.
  - Gestionar reservas: apartado dentro de nuestra cuenta que nos permitirá ver las reservas que tenemos actualmente activas.
  - Revisar perfil: apartado de nuestra cuenta que nos permitirá ver qué valoraciones tenemos, así como el rango de socio que tenemos en ese momento.
  - Revisar otro usuario: funcionalidad para observar a otros usuarios, además de contactarles y de darles una valoración en caso de haber coincidido con ellos en alguna actividad.
      


## Prototipo Lo-FI Wireframe 
### Hacer un boceto de la aplicación.

## Conclusiones  
(incluye valoración de esta etapa)
