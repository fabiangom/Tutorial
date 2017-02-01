# Tutorial
Describir el flujo completo de Git

imagen de los procesos de un flujo en git
![alt text](http://soygeek.org/images/flujo.png)

![alt text](http://1.bp.blogspot.com/-aZ0ROa8wUZ4/VmRbf4xk_wI/AAAAAAAAEJM/D0V09JT3PMI/s1600/Sin%2Bt%25C3%25ADtulo.png)

1.- Crear un repositorio en github colocando el nombre, una descripcion, colocando un archivo README.md y la licencia del MIT.

2.-Ingresar a la terminal y desde ahi ingresar al repositorio.

3.-Ahora deberas clonar el repositorio con el comando "git clone (link del repositorio)".

4.-Despues deberas crear dos branches con los nombres que tu creas mas convenientes usando el comando "git branch (nombre)". Y con el comando "git branch" podras ver un listado de las branch que existen.

5.-Para cambiar de una branch a otra deberas usar el comando "git checkout (nombre de la branch a la que quieres dirigirte)".

6.-Con el comando "git status" podras visualizar un listado del status de la branch en la que te encuentras.

7.-Cuando realizas alguna modificacion en tus archivos y deseas actualizar el documento para que la modificacion quede fija y pasarlo a la fase "stages" deberas usar el comando "git add (nombre del archivo)".

8.-Despues usar el comando "git commit -v" para abrir los comentarios del archivo y escribir en el un adescripcion de los cambios que se realizaron.

9.-Para confirmar los cambios y actualizarlos en tu github deberas usar los siguientes comandos en el orden que se muestra.
"git push origin (nombre de la branch en la que se hicieron los cambios)".
"git pull origin (nombre de la branch en la que se hicieron los cambios)".

10.-Ahora ve a tu github y en el aparece un mensaje donde indica que se han realizado modificaciones, las puedes revisar y si estas seguro de los cambios deberas realizar la comparacion pero desde el branch donde realizaste los cambios y al que actualizaste; no comparar con el master!.
