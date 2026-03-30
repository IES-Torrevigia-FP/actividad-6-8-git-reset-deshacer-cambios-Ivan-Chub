1)
git reset --soft: solo mueve el puntero del historial al commit que elijas.
git reset --mixed: mueve el puntero del historial y además limpia el área de preparación.
git reset --hard: mueve el historial, limpia el área de preparación y borra todos los cambios de tu directorio de trabajo.

2)
git reset lo reescribe (borra el pasado), mientras que git revert lo amplía (añade un nuevo commit que deshace el anterior).

3)
--soft: para que el commit debe separarse o rehacerse.
mixed: queremos rehacer el commit “fix cosas” y decidir con calma qué va en el siguiente commit.
--hard:para borrar HEAD, index y working directory al commit actual, descartando también todos los cambios.
