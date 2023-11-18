# TAREAS:
# 0 - CLONA EL REPOSITORIO A TU MAQUINA LOCAL Y CREA UNA NUEVA RAMA DE GIT
- con el comando 'git clone' puedes clonar un repositorio a tu maquina local
 utiliza 'git clone https://github.com/maximilianohrra/arrancaenit_prueba.git' para ello.
 luego de clonarlo verás el directorio y los 3 archivos en tu maquina. Con GitBash crea nueva nueva rama con 'git checkout -b task/<aquipontunombre>' para que yo pueda saber quien creo la nueva rama!. Por ej 'git checkout -b task/MaxiHerrera'

# 1 - SOLUCIONAR EL PROBLEMA.
- Cuando ejecutes el comando "docker build -t arrancaenit ." habrá un error en la generacion del dockerfile (es decir, un error en la 'receta'. Tiene un fallo!). Trata de ver documentacion oficial, stackoverflow o chatGPT como podrias solucionar el problema, aunque si te fijas detenidamente y te das tu tiempo de leer y pensar, seguro lo solucionas sin tener que buscar en la documentación!
Luego de solucionarlo ejecuta 'docker run arrancaenit' y deberias ver en la salida la misma leyenda que está en el archivo miproyecto.sh por 30 segundos.
NOTA: (Antes de hacer el primer docker build, si lo deseas puedes cambiar la variable $NOMBRE en el archivo miproyecto.sh como para jugar un poco y cononcer la nomenclatura del codigo y su funcionamiento)

# 2 - CAMBIAR LA IMAGEN DEL CONTENDOR POR -> FROM python:latest VER LA DIFERENCIA con el comando 'docker images'.
 En este caso puedes ejecutar nuevamente la construccion del dockerfile haciendo
 "docker build -t arrancaenit_python ." y luego 'docker images' para visualizar la diferencia en el listado de las imagenes usadas. Indica cual es la diferencia entre ambas.
# 3 - SUBIR EL REPO A GITHUB.
- Luego de realizar la practica (en tu rama 'task/' correspondiente) corre los siguientes comandos:
 Agrega todos los archivos actualizados a la rama -> 'git add . '
 Agrega un comentario a los cambios hechos -> 'git commit -m "Se actualizan cambios"
 Se 'pushean' o 'suben' los cambios -> git push
#
