# mastermeli MatiBrond
Repositorio IT-Academy 2019
Matias Brond

#GRACIASMANU
## Frase inspiradora:

`La vida es como una tela bordada, 
nos pasamos la primera parte de la vida 
en el lado bonito del bordado, 
pero la segunda parte de nuestra vida 
la pasamos en el otro lado, 
es menos bonito, pero vemos cómo están dispuestos los hilos. `

## Comandos utilizados:

Clonar repositorio mastermeli en local: 

`git clone [link del repositorio]`

Crear archivo README.md: 

`nano README.md`

Subir nuestro archivo readme al repositorio remoto:

`git add README.md`

`git commit -m "commit inicial"`

`git push`

Crear en el repo local un archivo: datospersonales.txt

`nano datospersonales.txt`

Crear en el repo local una carpeta: datospersonales.

`mkdir datospersonales`

Hacer que la carpeta y archivo sean ignorados.

    Crear archivo ".gitignore"
    `nano .gitignore`
    
    Escribir en el los archivos/carpetas que deseemos ignorar.
    
    Tener en cuenta que para que git detecte el directorio "datospersonales", ésta debe tener al menos un archivo dentro.
    Creamos un archivo "empty" en "/datospersonales"
    
    `nano /datospersonales/empty`

Añadir el archivo datos01.txt

`nano datos01.txt`

Crear el tag V.0.1

`git tag -a V.0.1 -m "V.0.1"`

Subir cambios

`git add *`

`git commit -m "creación tag"`

`git push`

Crear un branch V.0.2

`git checkout -b V.0.2`

Mostrar commits con sus branches y tags

`git log`


# Tabla de compañeros

| Compañero| GitHubProfile|
| ----- | ---- |
| Juani Filardo | JuaniFilardo |
| Fede Silva | FedericoSilva |
| Rodrigo Andres Crespillo | rodixxi |
| Julian De Angelis | julideangelis | 
| Rodrigo Vicente | rj-vicente | 
