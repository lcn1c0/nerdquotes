¿Qué comando utilizaste en el paso 11? ¿Por qué?
Uso el comando git reset --hard head~1. Se pide deshacer los cambios y con hard damos autorizacion a modficar el working copy

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Primero reflog para saber la referencia del commit. Cuando se identifica hago el comando reset al commit en cuestión. Hago un git status para ver la situación actual y hago un git restore del archivo para cambiar los cambios deshechos del commit.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No por que esta todo en la misma rama

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si. Hay lines iguales en los archivos. Lo soluciono primero modificando el archivo con nano. Luego hago un commit y termino el merge

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No. Tiene commis de la misma rama.

- ¿Qué comando o comandos utilizaste en el paso 25?
Prinmero uso un git log --graph --pretty=oneline. Luego creo un alias para no tener que usar el comando. El alias lo creo con git config --global alias.graph "log --graph --pretty=oneline"


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si. Estan en la misma rama

- ¿Qué comando o comandos utilizaste en el paso 27?
Primero hago un reflog identificando el merge que he hecho. Hago un git reset para ir ha ese commit.

- ¿Qué comando o comandos utilizaste en el paso 28?
git reflog para identificar el commit y git reset --hard

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D 

- ¿Qué comando o comandos utilizaste en el paso 30?
reflog identificando el commit el merge y git reset --hard

- ¿Qué comando o comandos usaste en el paso 32?
reflog identificando el commit inicial y git reset

- ¿Qué comando o comandos usaste en el punto 33?
Igual que el paso 32
