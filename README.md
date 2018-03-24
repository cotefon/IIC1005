# Tarea Chica 1

En esta tarea aprenderás a utilizar la consola y algunos comandos de git. Tu nota dependerá de cuantos niveles avances en este desafío. Es importante que no modifiques ninguno de los archivos dentro de esta carpeta, con excepción de este archivo, README.md, que será tu **hoja de respuestas**.

> Cada vez que avances un nivel, se generará un archivo con las instrucciones del siguiente. En este archivo dejaremos espacio para que coloques solamente las respuestas.

Durante todo este proceso utilizaremos la consola (si estás en Windows, deberás usar la consola de git, git bash, para poder usar los comandos que te enseñaremos). Para comenzar, debes clonar este repositorio:

```
git clone <url del repo.git>
```

---

# Piso 1:  `pwd`, `ls` y `cd`

Ya clonaste el repositorio, es decir, tienes una versión local de dicho repositorio. Para desbloquear el siguiente piso debes ejecutar un archivo en Python que se encuentra dentro de la nueva carpeta, pero para hacerlo entretenido nos moveremos desde la consola.

El primer comando que debes conocer es **`pwd`** (*print working directory*), que nos dice dónde estamos actualmente. El segundo comando es **`ls`** (*list*) que nos muestra una lista con los directorios y archivos en el directorio actual (sí, el mismo que nos entregó `pwd`). El tercer comando es **`cd`** (*change directory*), que nos permite movernos entre distintos directorios, solo tenemos que darle como parámetro hacia donde queremos movernos.

```bash
$ pwd
~/exploratorio/tarea-chica-1

$ ls
Enunciado.pdf
Solucion-TC1/

$ cd ..

$ pwd
~/exploratorio

$ ls
tarea-chica-1
tarea-chica-2
tarea-grande-1

$ cd tarea-chica-2

$ pwd
~/exploratorio/tarea-chica-2
```

Como notarás, `cd` recibe como parámetro el nombre del directorio, pero no dijimos todo. Existen ciertos "nombres especiales" (*wildcards*) para moverse, que se pueden utilizar en conjunto:

* `.`: Es el directorio actual, por lo que `./carpeta` es equivalente a `carpeta`.
* `..`: Es el directorio padre. Como notaste, cuando hicimos `cd ..` hicimos el cambio al directorio padre.
* `*`: Cualquier directorio. Por ejemplo, si olvidamos el nombre de un directorio intermedio puede ahorrarnos algún trabajo (`cd exploratorio/*/Solucion-TC2`)

Ninguno de estos comandos produce cambios en tu computador, por lo que puedes experimentar libremente con ellos. Pero esto es una tarea, por lo que debes hacer lo siguiente:

1. Veamos dónde estamos (sabes el comando para hacer eso).

2. ¿Está la carpeta que clonaste recién en este directorio? Hay una forma de ver los contenidos de esta carpeta (también sabes el comando para esto).

3. Accede a la carpeta (sí, también sabes el comando)

4. Muestra la lista de contenidos de esta carpeta. Si está el archivo `script.py`, hiciste todo bien.

5. Ejecuta el archivo. Para hacerlo, debes darle tu número de alumno y tu usuario de GitHub como parámetro de la siguiente forma:

   ```
   $ python script.py 12345678 usuario
   ```

   Si todo sale bien, el último paso generará una carpeta (no es necesario que la abras, recuerda que usaremos siempre la consola) y un archivo con las instrucciones del siguiente paso. Además, imprimirá una linea, la que debes colocar en la sección "Respuestas", al final de este archivo.

   Con esto ya puedes pasar al siguiente Piso, ingresando a la carpeta piso2 y cada vez que termines un piso puedes ingresar al piso siguiente.

   Un comando útil para leer archivos en consola es **`cat`** (*catenate*), a este hay que pasarle como parámetro el o los archivos que se quieren mostrar. Se le puede pasar más de un archivo separado por espacios y mostrará sus contenidos encadenados (*catenate*). Se utiliza de la siguiente forma:

   ```bash
   $ cat archivo1 archivo2 archivo3
   Contenido del archivo 1...
   Contenido del archivo 2...
   Contenido del archivo 3...
   ```

   **RECUERDA**: Esta es una tarea para aprender a usar la línea de comandos, por lo que todo lo que hagas en esta tarea debe realizarse mediante esta, incluso escribir tus respuestas :eyes:.

   Buena suerte :grin:

---

# Respuestas

### Piso 1: `pwd`, `ls` y `cd`

>

### Piso 2: `git status` y `git log`

>

### Piso 3: `git add`, `git commit` y `git push`

>

### Piso 4: `mkdir`, `touch`, `grep`, `|` y `>`

>
>

### Piso 5: Bonus

>
