a. ¿Cómo se inicializa un repositorio en Git?
este se inicia escribiendo en la consola git init 
b. ¿Cómo creas un repositorio en GitHub?
en github le tienes que dar en crear nuevo repositorio
c. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
tienes que escribir el comando en la consola git bash git remote add origin y el url de tu repositorio
d. ¿Cuál es el flujo básico de trabajo en Git y GitHub?
clonar cosa, crear cambiar ramas, crear markdowns, hacer cambios en tu repositorio, unir ramas, y borrar cosas
e. ¿Para qué sirve el archivo .gitignore?
este se usa para decirle que cosas deben de ser ignoradas asi para que no afecte a la compilacion
f. ¿Cuál es el propósito de una rama?
es como tipo otro archivo en otra linea difrente y asi trabajar en equipo para que cada quien suba lo que le corresponde
git checkout -b nombre_de_rama
g. ¿Qué es una fusión?
es cuando se fusionan las ramas con merge
git merge nombre_de_la_rama
h. Explica los diferentes tipos de fusión que existen.
merge directo es cuando se combinan una rama de otra sin ningun problema asi fine
fusion con conflictos es cuando tienes que resolver los problemas manualmente

i. ¿Cómo puedes ver el historial de tu repositorio?
con 
git log
j. ¿Cuál es el propósito de una etiqueta?
es para subir versiones a los proyectos tipo hilos este se ahce con 
git tag -a v1.0 -m "nombre de la version"