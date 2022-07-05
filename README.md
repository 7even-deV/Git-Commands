# Git Commands

<marquee style="width: 50%; color: green; font-size: 20px;">
<b>Este repositorio será exclusivo para comandos git</b></marquee>

![Git-logo](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/320px-Git-logo.svg.png)

Con el fin de hacer nuestra vida un poco más cómoda, eficiente y divertida.  
No es un viaje a las Maldivas lo que traigo, pero por algo se empieza :smile:  
La idea es documentar algunos de los comandos git que uso con más frecuencia,  
pudiendo así configurarlos de forma global y personalizarlos en un nuevo comando al gusto,  
siendo esto realmente eficiente a la hora de ejecutarlos.
***

> *Para configurar una instrucción en un nuevo comando de forma global.*
```
git config --global alias.{nuevo_comando} "instrucción_a_realizar"
```

> *__Tip__: Configurar el comando de configurar comandos para agilizar su escritura.*
```
git config --global alias.g "config --global"
```

> *Muestro un ejemplo para configurar la instrucción de __status__.*
```
git g alias.s "status"
```
- [x] `git s`
***

### *A continuación, dejo algunas instrucciones que considero útiles para configurar.*

| __Comandos git__ | __Instrucciones a realizar__ |
| ---------------- | ---------------------------- |
| `git --help -all` | Lista los comandos principales. |
| `git branch -m main` | Reemplaza el nombre de la rama por main. |
| `git switch -c test` | Posiciona a la rama llamada test, sino existe la creará vacía. |
| `git merge main` | Fusiona la rama posicionada con la rama main. |
| `git checkout main` | Cambia a la rama main. |
| `git branch --delete test` | Elimina la rama local llamada test. |
| `git push origin -d test` | Elimina la rama del repositorio remoto en vez de local. |
| `git log -1 HEAD` | Muestra el último commit de la rama. |
| `git log --pretty=oneline` | Muestra los commits de forma ordenada y simplificada. |
| `git checkout HEAD~1` | Cambia al commit anterior de la rama. |
| `git switch` | Regresa hasta el último commit disponible. |
| `git commit -a -m` | Agrega y crea un nuevo commit con el nombre que le indíques. |
| `git commit --amend -m` | Actualiza el nombre del commit por el que le indíques. |
| `git commit --amend --no-edit` | Actualiza el commit sin crear otro nuevo. |
| `git config --global color.ui false` | Des/activa todos los colores indicando el bool. |
***

__Por último, adjunto un enlace donde recopilé la información en la que me basé,__  
__recomiendo encarecidamente visiten, gracias!__  
#### [Pro Git book](https://git-scm.com/book/es/v2/)
