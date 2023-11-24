# SAY
Proyecto para el core 213


#Qué es Git y que es GitHub
Git es un respositorio de codigo, texto y comentarios
GitHub es un sistema de control de versioes distribuido, lo que significa que un clon local del proyecto es un respositorio de control de versiones 

## Comandos de Git

### git status
Te permite visualizar el estado del repositorio asi como si existen cambios para realizar 
asi como si no se estan siguiendo archivos

### git clone
Te permite clonar un repositorio a tu entorno local es importante destacar que para realizar un
clone de un repo desde ssh es necesario usar las llaves de ssh mas info: https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

### git add
Añade archivos al stage donde posteriormente podran ser commited 

### git commit 
Se realiza el commit al repositorio es necesario añadir un comentario

### git pull
Obtiene los cambios del respositorio 

---- Git flow  ----
Ramas principales:
Nota: Master ya no se usa, se cambia por Main.
>> Main: Se utiliza para tener las versiones oficiales del código.
>> Develop: Es utilizado para tener las versiones funcionales del desarrollo.
>> Feature(s): Se utiliza para realizar todo el tipo de commits.
Nota: Los commits se recomienda que sean cosas específicas, características únicas.