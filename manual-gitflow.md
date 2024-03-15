# Manual GitFlow

## Que es GitFlow?
- GitFlow se basa en un aspecto de la creación de ramas de Git. Abreviadamente, es una forma de organizar el trabajo.   
- Según el modelo de GitFlow tendremos varias ramas función, que emergen de la rama principal, y, para que se fusionen con la principal, tienen que tener su trabajo terminado.


- Imagina que quieres montar un restaurante. Un restaurante tiene cocina, tiene comedor, tiene barra, tiene almacen y tiene trabajadores. Cada una de estas sería una rama función, que emergerían de la rama principal, en este caso, restaurante.
Para que el restaurante esté listo para abrir, tendremos que tener todas las ramas listas. No podemos abrir un restaurante solo con la cocina, al igual que no podremos abrirlo con todo listo pero sin trabajadores.

- Esa es la implementación de GitFlow. Aparte de esta distribución, que es lo principal, tenemos el otro punto también importante de GitFlow, la colaboración es la otra parte importante. La filosofía se basa en que una persona o un grupo de X personas se haga cargo de una rama función. Normalmente, las ramas de larga duración necesitarán más colaboración.


## Desventajas
- Un gran inconveniente viene de la mano con una de las ventajas, y es que si tener un grupo de personas en una rama te puede acelerar el trabajo, también puede dar lugar a creación de ramas alternativas.
- La cantidad de ramas aternativas que se pueden tener
- Nivel: Es algo complejo entender bien el funcionamiento y ponerlo en práctica. Si se usa sin tener tantos conociemientos, puede llevar a problemas a la hora de ponerlo en práctica
- Hay proyectos en los que gitflow no es la mejor opción a utilizar, debido a que el proyecto sea más simple desarrollarlo con otros métodos más sencillos que con gitflow


## Comnados de git

- **git flow init:** Inicializar gitflow en un repositorio existente
  -  ``` git status ```

- **git flow feature start:** Creamos una rama derivada de la rama en la que estemos
  - ``` git flow feature start {nombreRama} ```

- **git flow feature finish:** Finalizamos la rama derivada y volvemos a la principal
  - ``` git flow feature finish {nombreRama} ```

- **git flow feature publish:** Publica la rama derivada a un servidor remoto
  - ``` git flow feature publish {nombreRama} ```

- **git flow feature pull:** Obtenemos una rama publicada por otra persona
  - ``` git flow feature pull origin {nombreRama} ```

- **git flow feature track:** Hacemos un seguimiento de cambios de una rama
  -  ``` git flow feature track {nombreRama} ```

- **git flow release start:** Crea una rama de publicacion derivada de nuestra rama principal
  - ``` git flow release start {nombreRama} ```

- **git flow release publish:** Publica la rama de publicación de manera similar a publicar características
  - ``` git flow release publish {nombreRama} ```

- **git flow release finish:** Cierra la rama de publicacion. Fusiona la rama de publicacion con master, fusiona la rama publicacion con dev y borra la rama de publicacion
  - ``` git flow release finish {nombreRama} ```

- **git flow hotifix start:** Crea una rama de revisión
  - ``` git flow hotifix start {nombreVersion} ```

- **git flow hotifix finish:** Cierra una rama de revisión
   - ``` git flow hotifix finish {nombreVersion} ```
