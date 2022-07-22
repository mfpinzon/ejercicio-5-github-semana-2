1. How do you see the files changed within each commit from git log?

el git log me muestra un historial en orden cronologico. la primera linea es el identificador del commit que tiene un valor exadecimal de 40 caracteres, en la segunda linea los datos del autor, en la tercera la fecha en la que se realizo el commit y en la cuarta linea me muestra el mensaje que le he puesto al commit.

2. How do you see the contents of what changed within each file from the git log?

se utiliza el comando git diff y este me muestra todo el contenido que ha cambiado dentro de cada commit

3. What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)

el concepto de head se refiere al commit en el que esta tu repositorio posicionado en cada momento. por regla general head suele coincidir con el ultimo commit de la rama en la que estes, ya que habitualmente estas trabajando en lo ultimo.