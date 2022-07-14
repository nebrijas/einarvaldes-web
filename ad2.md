# Actividad Dirigida 2

La actividad dirigida que desarrollamos a continuación consisten en explicar el proceso realizado para el cambio de **README.md** a la _Actividad dirigida 1_ (ad1.md). Detallamos el proceso a continuación.

1. Convertir los archivos de **Markdown** a formato **HTML**. Para conseguirlo se siguen estos pasos:
- Acceder a [https://github.com/nebrijas/einarvaldes-web/settings/pages](https://github.com/nebrijas/einarvaldes-web/settings/pages) (se aplica para cualquier repositorio, solo cambia el nombre de la cuenta).
- Seleccionar en _Source_ en la opción 1: _main_ y en la opción 2: _root_. De este modo ya está convertido el directorio raíz en **HTML**.

2. Luego crear un nuevo archivo desde la web (con `Add file`) nombrándolo como **ad2.md**, que es este documento que trabajamos, precisamente.

3. Descargar [Git Bash](https://git-scm.com/downloads) y abrir el programa para acceder a la terminal.

4. Colocamos `pwd` y damos _enter_ para verificar en que directorio estamos.

5. Clonamos el directorio del repositorio a través del comando `git clone`, damos _enter_.

6. Ya debemos tener la carpeta creada en nuestro directorio. Se puede ver con `ls` (y enter).

7. Accedemos a dicha carpeta con cd y el nombre de la carpeta, en este caso `cd einarvaldes-web` y damos _enter_.

8. Podemos usar `ls` y _enter_ para ver el contenido que se encuentra en su interior.

9. Escribimos `git config user.name` seguido de nuestro nombre de usuario de [***GitHub***](https://github.com/) y damos _enter_. Para mi cuenta sería `git config user.name einarvaldes`.

10. Escribimos `git config user.email` seguido del correo que se utiliza en [***GitHub***](https://github.com/) y damos _enter_. En mi caso `git config user.email einarvaldes@hotmail.com`.

11. En nuestro navegador vamos a la web: [https://github.com/settings/tokens](https://github.com/settings/tokens)

12. Seleccionamos la opción **"Generate new token"**, colocamos el nombre que queremos en _Note_ (por ejemplo, pd2). En _expiration_ le marcamos la fecha. Seleccionamos 60 días para que dure hasta el final del curso. En _select scopes_ seleccionamos **"Repo"** (para que se activen todas las casillas de repo). Las demás casillas se dejan sin seleccionar. Posteriormente le damos a **"Generar token"**.

13. Copiamos el _token_ creado.

14. Volvemos a **Git Bash** y escribimos `echo > ../.token` para añadir un archivo oculto en la carpeta superior del árbol con el _token_ que acabamos de copiar impreso.

15. Se escribe `README.md ad1.md` y damos _enter_ para copiar el contenido de **README.md** a una nueva carpeta de nombre **ad1.md**.

16. Escribimos `nano README.md` y damos _enter_. Se abre el espacio de **nano** para editar el archivo poniéndole un título y dos enlaces, uno a **ad1.md** y otro a este directorio **(ad2.md)**. Dentro de dicho espacio aparece la ayuda para realizar los cambios. Por ejemplo, para salir sería **CTRL+X** (el símbolo **^** se refiere a la tecla _control_).

17. Escribimos `git status` y damos _enter_. Para ver las modificaciones realizadas.

18.  para que _online_ esté disponible hay que escribir `git add` seguido del nombre de la carpeta y dar _enter_. En este caso el texto sería `git add README.md ad1.md`. Se pueden incluir varios elementos en conjunto.
19. Escribimos `git push` y damos _enter_ para guardar el contenido en ***GitHub***.

20. Comprobamos que ahora ya aparece la nueva carpeta _online_.

Estos son los paso básicos aplicados para ejecutar la segunda actividad dirigida.


