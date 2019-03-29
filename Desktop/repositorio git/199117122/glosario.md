#Glosario

- Control de Versiones(VC): Se le llama asi a la gestion de cambios en un archivo o proyecto, es decir es sistema por el cual se guarda la edicion de un archivo de manera que se pueda recuperar un anterior archivo.

*https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones*

- Control de Versiones Distribuido(DVC): En este tipo de sistema no existe un repositorio central, los repositorios estan distribuidos en diferentes servidores y/o computadores, de esta manera si se pierde o modifica una copia del archivo se facilita su recuperacion.

*https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones*

- Repositorio Remoto y Repositorio Local: Los repositorios son el lugar donde se guardan las versiones de nuestro archivo o proyecto, en los repositorios locales el lugar de almacenaje se guardan en el PC en el que se lleva a cabo el proyecto por otra parte los repositorios remotos son aquellos que guardan la informacion en la red la cual puede ser accedida por multiples usuarios.

*https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos*

- Copia de Trabajo / Working Copy: Esta se refiere a una copia local del repositorio, esta es independiente del servidor central.

*https://www.thomas-krenn.com/en/wiki/Git_Basic_Terms*

- Area de Preparacion / Staging Area: Es el area en donde se almacenan los archivos que se quieren agregar a la proxima confirmacion.

*https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git*

- Preparar Cambios / Stage Changes: En esta etapa se utiliza "git add" para agregar un archivo que ha sido modificado al area de preparacion. 

*https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio*

- Confirmar Cambios / Commit Changes: Esta es la etapa donde se guardan los cambios en el repositorio, se utiliza "git commit" para esto.

*https://git-scm.com/book/es/v2/Fundamentos-de-Git-Guardando-cambios-en-el-Repositorio*

- Commit: Este comando sirve para guardar cambios en el repositorio.

*https://git-scm.com/docs/git-commit*
	
- Clone: Este comando replica un repositorio para agregarlo a una nueva direccion.

*https://git-scm.com/docs/git-clone*
	
- Pull: Este comando sirve para fusionar los cambios con el repositorio de la ultima confirmacion.

*https://git-scm.com/docs/git-pull*
	
- Push: Este comando sube el repositorio y lo deja disponible para cambios.

*https://git-scm.com/docs/git-push*
	
- Fetch: Este comando sube el repositorio a otra rama para preparar la subida de este repositorio a la rama local.

*https://git-scm.com/docs/git-fetch*
	
- Merge: Se utiliza despues del comando anterior(Fetch) para subir el repositorio a la rama local.

*https://git-scm.com/docs/git-merge*
	
- Status: Este comando muestra el estad de los diferentes archivos en el directorio de trabajo.

*https://git-scm.com/docs/git-status*
	
- Log: Este comando se utiliza para ver el historial de commits en el proyecto.

*https://git-scm.com/docs/git-log*
	
- Checkout: Este comando sirve para cambiar de ramas en el proyecto.

*https://git-scm.com/docs/git-checkout*
	
- Rama / Branch: Una rama es un puntero a el ultimo commit del proyecto, la rama principal es "master", usado como comando "git branch" sirve para crear, listar o borrar una rama en el proyecto.

*https://git-scm.com/book/es/v1/Ramificaciones-en-Git-%C2%BFQu%C3%A9-es-una-rama%3F*
	
- Etiqueta / Tag: Las etiquetas sirven para marcar las partes importantes en las diferentes versiones del proyecto, usado como comando "git tag" sirve para crear, listar o borrar una etiqueta.

*https://git-scm.com/book/es/v1/Fundamentos-de-Git-Creando-etiquetas*