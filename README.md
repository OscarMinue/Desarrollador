# LEEME!
   
### Nuestra propia version de Readme 
***
* Fork del repositorio
El primer paso es hacer "Fork" del repositorio.

* Clonar el repositorio
Después de tener el repositorio en nuestra cuenta, seleccionar la dirección del repositorio HTTP" y clonar:

> <center> git clone https://github.com/User/NombreRepo.git}
***
Dentro de la carpeta que genera, comprobar la URL del repositorio:

> <center> git remote -v
***
### ATENTI
>Antes de realizar modificaciones agregar la URL del repositorio original del proyecto:
> <center> git remote add upstream https://github.com/User/RepoOriginal(Forkeado)
***
### Comprobar

> <center> git remote -v
***
>Actualizar la rama Master
Antes de empezar a trabajar, obtener los últimos cambios del Repo Original:

> <center> $ git pull -r upstream master
*****
### Crear una Rama
> Para crear una rama usar la opción "checkout" de git:

> <center>$ git checkout -b feature-nombre-rama

> Hacer cambios
Realizar todos los cambios que se desea hacer al proyecto.

>Agregar los archivos y hacer un commit

>Después de realizar el commit hacer el push hacia nuestro repositorio indicando la rama que hemos creado.

><center>$ git push origin feature-nombre-rama

>Hacer un Pull Request
>Hacer click en "Compare & Pull Request"

E>scribir cambios del Pull Request.

>Si todo está bien, enviar con el botón "Send Pull Request".

>Esperar a que el duelo del repositorio lo revise, acepte y mezcle en la rama correspondiente.
