# Github Actions 

### Que es? 

Es una herramienta para automatizar tareas relacionadas con repositorios 
alojados en github (pull request, comentarios, nuevas ramas,etc).

#### Diferentes etapas de los github actions

1. Workflow: esto es un flujo de trabajo el cual define que es este flujo de trabajo
2. Triggers: son lo disparadores que suceden cuando pasa una accion(pull request, push, pull, etc)
3. Jobs: Estos son trabajos que se puede realizar el Workflow, por ejemplo correr la aplicacion en produccion
4. Steps: Estos van de la mano de los jobs, ya que para realizar un Job normalmente se necesita mas de un paso. Ejemplo para correr la aplicacion 
en produccion se necesita conectar al servidor, descargar los nuevos cambios del repositorio, etc.

