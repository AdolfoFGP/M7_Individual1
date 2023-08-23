# Modulo 7: Acceso a Datos en Aplicaciones Python Django - Individual 1
Contexto: 
Desarrollaremos una pequeña aplicación web que permita a los usuarios crear y realizar un seguimiento
a tareas pendientes utilizando ORM de Django.

La aplicación debe permitir a los usuarios, debidamente autenticados y autorizados agregar tareas
pendientes. Cada tarea debe tener un título, una descripción, una fecha de vencimiento, un estado
(pendiente, en progreso o completada) y una etiqueta para categorizar la tarea (trabajo, hogar, estudio,
etc.).
La página principal de la aplicación debe mostrar una lista de todas las tareas pendientes del usuario,
ordenadas por fecha de vencimiento. Los usuarios deberán poder filtrar las tareas por etiqueta y estado.
Los usuarios podrán crear, editar y eliminar tareas desde la página principal de la aplicación. Cuando se
crea una nueva tarea, el usuario debe elegir una etiqueta de una lista predefinida. Cuando se edita una
tarea existente, el usuario debe poder cambiar su título, descripción, fecha de vencimiento, estado y
etiqueta.
La aplicación debe tener una página de detalles de tarea, que muestre toda la información de la tarea, así
como un botón para marcar la tarea como completada. Cuando una tarea se marca como completada,
debe moverse a una lista separada de tareas completadas.
Los usuarios podrán ver cuántas tareas tienen pendientes, cuántas han completado, cuántas están en
progreso y cuántas han vencido.
La aplicación debe utilizar el ORM de Django para interactuar con la base de datos. Debe utilizar el modelo
de usuario integrado en Django para autenticar a los usuarios y asociar las tareas con el usuario
correspondiente.


Se cumple siguientes requerimientos:
- Crear un proyecto en Django, con las aplicaciones que estimes necesarias para abordar el
problema anterior.
- Conectar el proyecto a una base de datos en PostgreSQL
- Realizar la migración inicial, corroborando que ésta se ve reflejada en la base de datos
PostgreSQL.
- Definir usuarios de tipo superuser y usuarios del sistema, considerando que todos podrán
interactuar con sus propias tareas.
- La página principal será una página con el logo e imagen representativa de su aplicación y un link
que lleve al Login de usuario.
- Implementar páginas de login y logout de usuarios. Login, deberá llevar a una página simple.
