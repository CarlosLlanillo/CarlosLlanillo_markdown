# CarlosLlanillo_markdown

## Explicacion comandos git

###Global config
Configura las variables del nombre y usuario para todos los repositorios 
del usuario
```
git config --global user.name "CarlosLlanilloAntolin"
git config --global user.email "carlos.llanilloantolin@iesmiguelherrero.com"
```
![GlobalConfig](./imagenes/globalConf.png)

## Añadir fichero y primer commit
```
mkdir ejemplo.txt
git add ejemplo.txt
git commit -am "Creado el fichero ejemplo.txt"
git push
```
![GlobalConfig](./imagenes/createFile.png)

## Editar fichero
```
git commit -am "Cambiado el fichero ejemplo.txt";
git push
```
