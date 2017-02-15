# Git
### ¿Qué es git?
Es un software de control de versiones diseñado pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un gran número de archivos de código fuente.
### ¿Cómo instalar git? 

Instalación en Windows
Abre cualquier navegador y accede a la siguiente dirección: http://msysgit.github.com
Entra en la sección Downloads y descarga la versión más reciente que exista.
Instala el archivo **.exe** descargado como cualquier otra aplicación de Windows.
#### Instalación en Linux
Ejecuta el siguiente comando:
- En distribuciones Fedora, RedHat y CentOS <br>
 `$ yum install git-core`
- En distribuciones Debian y Ubuntu <br>
 `$ apt-get install git-core`

#### Instalación en Mac OS X
Abre cualquier navegador y accede a la siguiente dirección: http://git-scm.com
Descarga la versión más reciente que veas en la propia portada de ese sitio web.
Instala el archivo **.dmg** descargado como cualquier otra aplicación de Mac.
### ¿Cómo iniciamos git?
Para iniciar git sobre un directorio simplemente debemos ejecutar el comando:
`$ git init`
Al hacer esto se crea un directorio **.git** que contendrá toda la información de de nuestro proyecto y las modificaciones por las que ha pasado.
### Comandos de git:
-  Clonar un repositorio: `$git clone username@host:/path/to/repository`
-  Añadir archivos al control de versiones: `git add <filename>` o también `git add .`
-  Comentar cambios