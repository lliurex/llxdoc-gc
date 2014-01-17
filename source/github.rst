Colaboración mediante GitHub
============================

GitHub_ es la red social de desarrolladores más popular. En diciembre de 2013 superaron los 10 millones de repositorios (la inmensa mayoría de código)[#]_. 
Si deseas aportar correcciones de errores a código o documentación necesitarás lo siguiente:

* Una cuenta de usuario en GitHub_.
* `Conocimientos básicos del sistema de control de versiones Git`__ (aunque muchas de las operaciones se pueden hacer por la interfaz web de GitHub).

Si ya cumples los anteriores requisitos, te damos una simple receta para aportar tus correcciones:

* Cuando hayas entrado en tu cuenta de GitHub, accede a la página del repositorio al que quieres aportar cambios.
* Haz un **fork** (se creará una copia del repositorio original en tu cuenta)
* Clona el repositorio en tu ordenador
* Realiza los cambios en una rama local (si procede)
* Haz un **push** de tu rama al **fork** de tu cuenta
* Utiliza el visor de diferencias para crear un **pull request**

A partir de ese momento, sólo cabe esperar a que los miembros del proyecto hagan las pruebas pertinentes con tus cambios y los acepten, rechacen o soliciten modificaciones (todo esto mediante la interfaz de GitHub).

Si tu colaboración es continuada, la manera de seguir las actualizaciones del repositorio original es la siguiente:

* En tu copia local, añade como remoto el repositorio **upstream** (original):

* Cuando quieras incorporar los cambios a la rama **master** deberás hacer:

.. [#] Ver `"10 Million repositories" <https://github.com/blog/1724-10-million-repositories>`_

.. _GitHub: http://github.com/
.. _Git: http://codehero.co/git-desde-cero-instalacion-configuracion-y-comandos-basicos/
