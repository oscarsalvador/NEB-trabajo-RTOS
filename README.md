# NEB-trabajo-RTOS
Por compatibilidad entre nuestros IDEs, recomiendo que todos usemos LuaTex. Es el que uso normalmente, y de los que he probado, el que suele poder compilar cualquier snippet de codigo

He creado cuatro ramas. Master y una para cada uno. Creo que la forma mas limpia es seguir el desarrollo basado en tronco, para que no haya problemas si dos personas desarrollan al mismo tiempo. Es decir cada uno actualiza su rama respescto a master, hace los cambios que quiera en su rama, hace merge con master en local, y empuja los cambios a master. Asi deberíamos poder evitar divergencias. Traduccion:

1. git switch master
1. git pull origin master
1. git switch <TU-RAMA>
1. git merge master
1. hacer los cambios que sea
1. git add -A
1. git commit -m <aaaa>
1. git push origin <TU-RAMA>
1. git merge master
1. git push origin master


1. git switch <TU-RAMA>
