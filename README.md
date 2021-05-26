# Github: Repositorio donde exponer el uso de Github


***
### 0_Tutorial para principiantes:

0. Para escribir en archivos de texto con formato .md, se usan las reglas que puedes ver aquí:  
[Tutorial de Markdown](https://joedicastro.com/pages/markdown.html "Tutorial MarkDown")

1. Las más importantes son:
	1. \# Esto es un H1
	2. \[Con titulo](http://joedicastro.com "titulo")
	3. \`codigo`
	4. \**Negrita**
	5. Dos espacios ==> Salto de línea
	6. \![Imagen con titulo] (pictures/avatar.png "titulo")
	7. \*** ==> linea divisioria
	8. \ ==> para escapar de los carácteres de markdown
	9. \1. Lista

***
### 1_Comenzar: Elije el sitio donde colocar el trabajo, clona y abrelo:
1. Para ir para atrás:  
`cd ..`

2. Para entrar en una carpeta:  
`cd Workspace`

3. Para crear una carpeta:  
`mkdir dTailorg`
  
4. Para clonar el repositorio dentro de la carpeta de tu pc donde poder usarlo:  
`git clone <url>`
> Nota: puedes conseguir la url del repositorio pulsando el botón a la derecha superior(dentro del repositorio), y dandole al botón de copiar por https

5. Para abrir el editor de texto elegido, con todos los repositorios:  
`c:/Workspace/dTailorg/atom .`

***
### 2_Trabajar en el repositorio
1. Para comprobar estado del repositorio en tú pc:  
`git status`

2. Para actualizar tu archivo del pc con el del repositorio usa:  
`git update` en lugar de `git pull`
> Nota: debido a que los repositorios llevan submodulos, y estos no se actualizan con `git pull`.  
Para leer más [Tutorial para submodulos](https://gist.github.com/gitaarik/8735255 "Tutorial para submodulos")

3. Para preparar la información a subir en el repositorio en linea:  
`git add .`

4. Para poner el título del aporte:  
`git commit -m "Titulo del aporte"`

5. Para subir los archivos:  
`git push`

***
### 3_Avanzado
1. Para añadir submodulos:  
`git add submodule <url> <titulo>`
