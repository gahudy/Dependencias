# INSTALACION DE DEPENDENCIAS 

## NODE
Es un entorno de trabajo escrito en javaScript que nos permite instalar depencias para el consumo de APIs y herramientas para nuestra web, se puede descargar desde : https://nodejs.org/en pero en este caso usaremos NVM para umejor manejo de NODE
## NVM
Es un sistema de control de versiones de NODE, no permite cambiar de version de NODE  sin ningun problema  segun el proyecto que  realizamos.
Se instala desde https://github.com/coreybutler/nvm-windows/releases, estos son alguno de los  comando que mas usaremos:

. nvm -v (Nos muestra la version de nvm que tengamos instaldo)
. nvm list (Nos muestras todas las versiones de node que tengamos instalados)
. nvm instal "seguido de la version" (Nos permite instalar una  version de node)
. nvm use "seguido de la version" (Nos permite cambiar y usar una version de node instalada)
. nvm alias  default "seguido de la version " (nos permite poder por default una version de NODE)

## NPM 
NPM  o NODE PACKAGE MANAGER es un esun admintrador de paquetes , que nos permite trabajar con dependecias, NPM no nesesita instalacion ya esta integtrado en NODE, iniciaremos NPM y solamente tendremos que llenar los datos que iran en el archivo  package.json que se generara.
Para instalar dependencias de la  siguiente manera:

. npm install "seguido de la dependencia a instalar" (Instala dependencias)

## INSTALACION DE DESARROLLO
- Solo va ixisten en el ambito de desarrollon, estao quiere decir son paquetes que se nesesitan solo para el desarrollo 

## INSTALACION  GLOBALES
-son dependencias que se instalan de manera global en nuestra computadora