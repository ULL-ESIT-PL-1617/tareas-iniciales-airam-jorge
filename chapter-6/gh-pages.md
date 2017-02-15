# GitHub Pages
### ¿Qué son?
Las gh-pages o Github pages son webs que nos facilita Github para nuestros repositorios, alojadas en el propio repositorios Github. Al actualizar nuestro repositorio, también estaremos actualizando la gh-page.
### ¿Cómo utilizar la rama gh-pages?
En primer lugar deberemos crear una rama huérfana:
`$ git checkout --orphan gh-pages`
Luego deberemos borrar todo aquello que no sea necesario para la visualización de la página, siendo necesario tener un index.html en la raíz del repositorio.
Una vez puesto todo como queremos, realizamos un commit:
`$ git commit -m 'creamos la rama gh-pages'`

Cómo usar Gh-pages para automatizar despliegues
gulp-gh-pages