
 # 💻 CoderHouse Back End 💻 # 

## Segunda entrega del proyecto final ##

Se finalizo la segunda entrega del proyecto final. La misma consta de un servidor de Express encargado de tomar peticiones y ejecutar tareas de modificación y almacenamientos de datos; productos y carritos de compra. 
Hasta ahora se incorporaron endpoints para 'api/productos' y 'api/carrito' segun lo descripto en la consigna del trabajo.
Se reestructuro toda la arquitectura del proyecto, y se crearon controladores y modelos para los distintos tipos de almacenamiento (archivos, base de datos) para los distintos tipos de objetos (productos y carritos) 

### Puntos de dificultad o a mejorar ###
La arquitectura de los modulos esta en etapa experimental. Hay que refinar las validaciones de los modelos de mongodb y atrapar errores en caso de escritura en los controladores de mongodb. Se puede crear un switch para no tener que comentar los endpoints utilizados y sus metodos.

> Deployed on Glitch: [project](https://glitch.com/edit/#!/twilight-lizard-hook/) [live site](https://twilight-lizard-hook.glitch.me/)

> Written with [StackEdit](https://stackedit.io/).