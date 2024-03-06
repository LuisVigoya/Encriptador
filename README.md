# Pasos para descargar e inciar el proyecto

1. Cree una carpeta en su computador y nombrela `Encriptador`
2. Abra la ventana de comandos entre a la carpeta creada y clone el repositorio
3. Clone el repositorio con el siguiente comando `git clone https://github.com/LuisVigoya/Encriptador.git`
4. Una vez clonado haga un cd a esa carpeta que se creo dentro de `Encriptador` y renombrela a `01-encriptador`
5. Cree su rama correspondiente con el comando `git checkout -b NombreRama`
7. Instale los modulos de node con el siguiente comando `npm install`
6. Para inicializar el proyecto use `npm start`

# Pasos para hacer un push a git

1. Para subir los cambios al git ejecute el comando `git push -u origin NombreSuRama`
2. una vez realizado esto con su `NombreRama` respetivo en futuros push solo debera ejecutar el comando `git push`
3. para agregar los cambios a la rama main debera hacerlo con un `Pull Request` y estos seran validados para incluir en el main

# Pasos para hacer un Pull de git
1. Verifique si hay cambios en la rama main usando `git fetch`, esto solo me actualiza los commit que se encuentras hechos
en el repositorio en git a mi repositorio local, no hace cambios en los archivos
1. Ya hubicado en la ruta de su proyecto ejecute el comando `git pull origin main` previamente verifique que se encuentran  en su rama para traer los cambios que se encuentren en main
