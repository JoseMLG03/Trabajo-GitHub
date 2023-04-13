# Trabajo/Tutorial de GitHub

![.](https://pinno.app/api/internal/cdb/contents/5b11e3c5-8871-4659-8e23-22b50fc43019/0/99713)

## Indice

 1. ¿**Que es** Git y Github?
    1. **Git**
    2. **GitHub**
    
2.  **Comandos Básicos** Git
    1. **Add**

    2. **Commit**

    3. **Push**

    4. **Pull**

    5. **Clone**

    6. **CheckOut**

    7. **Branch**

    8. **Merge**

       - **Conflictos en el Merge**

 3. **Ejercicios de Ejemplo Resueltos**
    1. **Ejercicio 1**
    2. **Ejercicio 2**
    3. **Ejercicio 3**
    4. **Ejercicio 4**

¿Que es Git y GitHub? 
===



Comandos Básicos de Git
===
 - Add
 
    Se utiliza mediante el comando " **Git add "Nombre de archivo"** " para introducirlo en la zona de **Staging**
 
 - Commit
 
    Se utiliza mediante el comando " **Git commit -m "Nombre del commit"** " para subir todo lo que esté en la "Staging Area" al Repositorio Local
 
 - Push
 
    Se utiliza mediante el comando " **Git push origin "nombre de la rama del repositorio remoto"** " para unirlo la rama indicada del repositorio remoto
 
 - Pull
 
    Se utiliza mediante el comando " **Git pull origin "nombre de la rama del repositorio remoto"** " para descargar la rama del repositorio remoto al local
 
 - Clone
 
    Se utiliza mediante el comando " **Git clone "Url del repositorio"** " para descargar el contenido de un repositorio remoto público cualquiera mediante una url 	que se consigue entrando en uno y clickando en el boton verde que pone ""**Code**""
    
    ![FotoClone](GitClone.png)

 - CheckOut
 
    Se utiliza mediante el comando " **Git Checkout "Archivo/ID del commit/HEAD Archivo"** " para volver un archivo concreto y especifico al estado del anterior         commit, la id del commit al que se quiera volver o con HEAD delante del archivo al que se quiera volver a la ultima version del mismo

 - Branch

   AAAA

 - Merge
 
   aaaaaa

 - Conflictos de Merge
    
   aaaaa
   
Ejercicios de Ejemplo Resueltos
===

Ejercicio 1
---
El primer ejercicio consta de los siguientes pasos.

  **1**- Crear un proyecto en IntelliJ
	
  **2**- Subir el proyecto a un repositorio **local**
  
----------------------------------------------------------------------------------------------------

**1ª parte del ejercicio.**

Para crear un proyecto hará falta abrir intelliJ y clickar en: **File > New > Project…**

Una vez dentro nos saldra un menú como este...  

![fotoEjercicio1](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 1/Ejercicio 1 - Apartado 1.png)

Una vez dentro le ponemos nombre al proyecto la localización donde queramos guardarlo y se le clicka en “Create” una vez hayamos finalizado.  

**2ª parte del ejercicio.**

Abriremos **Git Bash** en la ubicación del proyecto.

Usaremos los comandos del terminal para crear un repositorio **local** al cual subiremos  el proyecto que acabamos de crear de la siguiente manera.  

![.](/Imagenes/3.Ejercicios/Ejercicio 1/Ejercicio 1 - Apartado 2.png)

Primero se hace un “ **git init** ” para hacer el repositorio local al que subiremos el proyecto

Segundo se hace un “ **git add** . ” para añadir todo el contenido de la carpeta a la subida

Tercero se hace un “ **git commit -m “Proyecto Ejemplo”** ” para subir todo lo almacenado a la subida al repositorio local.  

Ejercicio 2
---
El segundo ejercicio consta de los siguientes pasos.

**1**- Crear un repositorio en GitHub con **README.md** y **.gitignore** que github ofrece para Java.
	
**2**- Modificación del README.md desde GitHub para indicar los dos primeros pasos.
	
**3**- Clonar el repositorio
	
**4**- Crear un proyecto en ese directorio
	
**5**- Correccion de creacion de proyecto en el directorio
	
------------------------------------------------------------
	
**1ª parte del ejercicio.**

En la esquina superior derecha de la página de GitHub hay un “+” lo pulsas y en una pestaña emergente pulsas “New Repository”. 

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 2/Ejercicio 2 - Apartado 1.png)

Una vez dentro modificamos el repositorio a nuestro gusto, ajustando el propietario, nombre, descripción (Opcional) y visibilidad.

Despues se ajusta con que quieres que se inicialice el repositorio, que aquí es donde se elejirá si queremos que tenga un README, .gitignore o licencia.

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 2/Ejercicio 2 - Apartado 1 (2).png)

**2ª parte del ejercicio.**

En la esquina superior derecha de la página de GitHub, al clickar en nuestra foto de perfil saldrá una pestaña emergente, clickaremos en   “Your Repositories”.

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 2/Ejercicio 2 - Apartado 2.png)

Despues buscaremos El repositorio que acabamos de crear que en mi caso sería EjemploEjercicio2.

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 2/Ejercicio 2 - Apartado 2(2).png)

Una vez en el repositorio en cuestion se clicka en el lapiz y ya se podria modificar el README.md desde GitHub sin problemas

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 2/Ejercicio 2 - Apartado 2(3).png)

**3ª parte del ejercicio.**

Para clonar el repositorio hara falta usar un comando del terminal de Git Bash. El “Git Clone” de la siguiente manera.

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 2/Ejercicio 2 - Apartado 3.png)

Se hace un “ git clone “URL de tu repositorio” ” para clonar el repositorio que tengamos subido a github en nuestro ordenador.

**4ª parte del ejercicio.**

Se crea un proyecto en el directorio, pero seleccionando como localizacion el repositorio clonado en cuestion.

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 2/Ejercicio 2 - Apartado 4.png)

**5ª parte del ejercicio.**

Como consecuencia de la localización el proyecto de IntelliJ se ha creado en una subcarpeta dentro del repositorio clonado, simplemente moveremos los archivos de dentro para la carpeta del repositorio.
Antes:			

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 2/Ejercicio 2 - Apartado 5.png)

Despues:

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 2/Ejercicio 2 - Apartado 5(2).png)

Ejercicio 3
---
El tercer ejercicio consta de los siguientes pasos.

**1**- Crear un repositorio nuevo en GitHub con README.md y .gitignore
	
**2**- Crear un proyecto marcando “Create Git repository”

**3**- Añadir el repositorio de GitHub como remoto e intentar hacer un pull

**4**- Quitar cambios del stage (Deshacer el git add)

**5**- Ahora que los cambios estan sin trackear, Intentar hacer un pull

**6**- Eliminar el .ignore local si queremos quedarnos con el remoto

**7**- Mover lo que estaba en **remoto** en la rama main, a la rama master **local**

**8**- Eliminar la rama main del repositorio de GitHub

**9**- Modificar el proyecto local (Commit: “Modificación de codigo 1”)

**10**- Crear una nueva rama de “correción de bug”

**11**- Corregir el problema, comitear la correccion en la rama y pushearla
	
**12**- Mergear la rama “correcion de bug”
	
----------------------------------------------------------------

**1ª parte del ejercicio.**

Crear un repositorio nuevo como se ha indicado anteriormente en el 

**Ejercicio2, Parte 1**

**2ª parte del ejercicio.**

Crear un proyecto nuevo como se ha indicado anteriormente en el 

**Ejercicio1, Parte 1**

**3ª parte del ejercicio.**

Se añade el repositorio de GitHub como remoto mediante el comando “**git remote add origin “URL de tu repositorio”** ”

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 3/Ejercicio 3 - Apartado 3.png)

Para hacer el pull se hará con “ **git pull origin main** ”

![.](Trabajo-GitHub/Imagenes/3.Ejercicios/Ejercicio 3/Ejercicio 3 - Apartado 3(2).png)

**4ª parte del ejercicio.**

S


Ejercicio 4
---


