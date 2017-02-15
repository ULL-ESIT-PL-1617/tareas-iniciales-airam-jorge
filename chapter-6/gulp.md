### ¿Qué es Gulp?
Gulp es una herramienta de automatización de tareas escrito en Javascript para Node.js. Al contrario que otros sistemas de automatización como Grunt, Gulp hace uso del módulo Stream de Node.js para poder concatenar tareas usando tuberías. Normalmente los automatizadores de tareas escriben los cambios al disco después de cada tarea, lo que provoca retardo cuando manejamos muchos ficheros. La ventaja de usar tuberías, es que estos ficheros no pasan por el disco, sino que se pasan de tubería en tubería, lo que aumenta la velocidad a la que se ejecutan las tareas.

Cómo automatizar tareas con Gulp

En esta sección veremos cómo usar gulpfile, tomando de ejemplo un desarrollo simple de frontend.
Fichero gulpfile.js

Al igual que otros automatizadores de tareas, necesitaremos un fichero de configuración donde almacenaremos nuestras tareas y otras cosas que necesitemos. Gulp sigue la convención de llamar a su fichero por el nombre del programa y la palabra file, como makefile, rakefile o gruntfile.