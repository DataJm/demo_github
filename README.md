# demo_github

Comandos de git:

Clonar el repositorio
$ git clone URL

Revisar los cambios en el repositorio
$ git status

Añadir cambios al repositorio
$ git add

No es necesario, pero si volvermos a hacer "git status"
podremos ver los cambios agregados al repositorio
$ git status

Todos los cambios que mandemos al repositorio
tienen que venir acompañados de un mensaje.
Ese mensaje se espera que sea explicativo sobre
los cambios realizados.

Existe documentación y buenas prácticas sobre estos mensajes,
lo más sencillo es usar la siguiente notacion: "accion: comentario"
"dev: nueva funcion"
"bug: corregi error en script.py"
"dev: agregue documentacion de la funcion main"

$ git commit -m 'dev: desarrollo de primer codigo'

Ahora si estamos listos para subir todos los cambios al repositorio
$ git push

