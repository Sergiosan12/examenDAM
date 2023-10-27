# examenDAMparte2
Para utilizarlo en el examen

Ahora hacemos un fork, para ello le damos al boton de fork dentro del repositorio https://github.com/damiancastelao/examenDAM.git, esto nos crea un nuevo repositorio en nuestro github con el mismo nombre. Para poder usarlo y modificarlo hacemos **git clone "link de mi repositorio donde hice el fork"**, esto crea un archivo con el contenido de este repositorio.

Creo un nuevo proyecto y copio el código de un programa ya creado anteriormente por mi

Los siguientes pasos son:

* **git branch -M main** para cambiar la rama a main

* ~~git remote add origin~~ este paso no hace falta ya que al clonar el fork ya es nuestro origin.

* **git add Readme.me** y **git add Main.java**

* **git commit -m "nombre commit"**

* **git push -u origin main**

Al crear un proyecto se crea el .gitignore, se añaden ficheros que no quieres que se vean en tu repositorio, en mi caso creé un archivo llamado token con mi token y lo añadí al .gitignore porque no quiero que se vea, al igual que otros archivos que no son necesarios.

Para añadir los archivos al .gitignore: **Click derecho en el archivo, después le damos a la opción de git, seleccionamos .gitignore**

Por último, se crea el ejecutable .jar con los siguientes pasos:

* **Vamos en el IDE a project structures**

* **En la parte de artifacts le damos al + y creamos uno from modules with dependences en nuestra main**

* **Le damos a build --> build artifacts** esto nos crea el ejecutable de nuestro proyecto

* **Ejecutamos el programa abriendolo con java -jar y se ejecuta bien en la terminal**

* **Subimos todo al repositorio**





