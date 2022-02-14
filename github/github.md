# GitHub
## Fork
> Cuando hacemos un *Fork* de un proyecto lo que hacemos es copiar el proyecto a nuestro repositorio por lo que ya podremos modificar cualquier dato del repositorio.

![imgFork]: Imagenes/fork.png

## Clone
> El comando clone nos permite pasar el repositorio de *GitHub* a nuestro equipo

1) Para realizar el *clone* lo primero que tendremos que hacer es is al repositorio que le hemos realizado el fork y copiaremos la ruta del repositorio.

[imgClone1]: github/Imagenes/fork.png

2) Cuando hayamos copiado la ruta nos iremos a la terminal del equipo. Cuando este abierta la terminal nos iremos a la ruta donde queramos guardar el repositorio con `cd` , para movernos por las carpetas y con `ls` para mostrar los archivos que se encuentran en el directorio en el que estas situado. Cuando nos hayamos posicionado en el directorio utilizaremos el comando `git clone (pegamos la ruta del repositorio de github)`.

[imgClone2]: Imagenes/clone2

Con este paso ya tendremos el repositorio en la carpeta deseada. 

## Actualizar directorio local (Pull)

> El comando *Pull* nos permite actualizar los cambios de nuestro directorio local (por si se ha hecho algun cambio en el repositorio de github). Utilizatremos el comando `git pull` en el directorio.

## Subir archivos (Push)

> El comando *Push* nos permite subir nuestro directorio local al *GitHub*
```
git init
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/JavierCasaisFedriani/SGE.git
git push -u origin main
```
