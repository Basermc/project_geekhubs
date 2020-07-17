# PÁGINA DEMO SYMFONY UTILIZANDO BASE DE DATOS MYSQL CON DOCKER
_para este proyecto, hemos montado 3 contenedores docker, uno con mysql, otro con php, otro con nginx, la idea es tener los servicios lo mas separado posible para ver como se comunican los 3 contenedores entre ellos, el framework utilizado es sympony, explicaremos en detalle como poder ejecutar el siguiente proyecto_

## COMENZANDO

_Lo primero que haremos sera clonarnos el repositorio de github_

_A continuación, deberemos de ejecutar docker_compose up -d --build para la creación de los contenedores_

_Una vez creados los contenedores, nos moveremos a la carpeta scripts/dependencias, en dicha carpeta encontraremos un fichero Makefile, abriremos el fichero para saber que nombres debemos poner al realizar make, iremos ejecutandolo paso a paso para instalar nuestras dependencias en nuestro contenedor php_

_en caso de tener la carpeta symfony vacia, deberemos de conectarnos a nuestro contenedor php, y dentro de el ejecutar el siguiente comando:_
_make install_symfony_demo, en caso de clonar el repositorio completo no hara falta_

_cuando tengamos las depencias instaladas en nuestro contenedor php, entraremos por el navegador a la url localhost:8001_

--