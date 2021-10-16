# First Contributions

|<img alt="RStudio" src="assets/rstudio-logo.png" width="300">|RStudio Edition|
|---|---|

This repo is a chopped-up, trimmed-down, and customised-for-RStudio version of the amazing [first contributions](https://github.com/firstcontributions/first-contributions) repo (and is not officially affiliated with RStudio).  Check out the original repo for instructions using other tools and language translations.

---
## Primera contribución

Este repositorio es una versión cortada, recortada y personalizada para RStudio del increíble repositorio [primeras contribuciones](https://github.com/firstcontributions/first-contributions) (y no está afiliado oficialmente con RStudio). Consulte el repositorio original para obtener instrucciones sobre el uso de otras herramientas y traducciones de idiomas.


## Intro

It's hard. It's always hard, when you do something for the first time. Especially when you are collaborating, making mistakes isn't a comfortable thing. But open source is all about collaboration & working together. We wanted to simplify the way new open-source contributors learn & contribute for the first time.

Reading articles & watching tutorials can help, but what comes better than actually doing the stuff without messing up anything. This project aims at providing guidance & simplifying the way rookies make their first contribution. Remember the more relaxed you are the better you learn. If you are looking for making your first contribution just follow the simple steps below. We promise you, it will be fun.

---
## Introducción
Es dificil. Siempre es difícil cuando haces algo por primera vez. Especialmente cuando estás colaborando, cometer errores no es algo cómodo. Pero el código abierto tiene que ver con la colaboración y el trabajo conjunto. Queríamos simplificar la forma en que los nuevos colaboradores de código abierto aprenden y contribuyen por primera vez.

Leer artículos y ver tutoriales puede ayudar, pero ¿qué es mejor que hacer las cosas sin estropear nada? Este proyecto tiene como objetivo proporcionar orientación y simplificar la forma en que los novatos hacen su primera contribución. Recuerde que cuanto más relajado esté, mejor aprenderá. Si está buscando hacer su primera contribución, simplemente siga los sencillos pasos a continuación. Te lo prometemos, será divertido.


## What this will teach you

* How to fork a repo
* How to make a branch
* How to submit a pull request to the original repo
---
## Lo que esto te enseñará
- Cómo bifurcar un repositorio
- Cómo hacer una rama
- Cómo enviar una solicitud de extracción al repositorio original


## What this won't teach you 

* How to build R packages
* Open source etiquette
---
## Lo que esto no te enseñará
- Cómo construir paquetes R
- Etiqueta de código abierto


## Assumptions

I have made a number of assumptions in writing this guide:

* You have a GitHub account
* You have [RStudio](https://www.rstudio.com/products/rstudio/download/#download) installed.
* You have [git](https://git-scm.com/downloads) installed and your [identity configured](http://happygitwithr.com/hello-git.html). If you can push to GitHub, you've already done this :)
* You are comfortable using git with RStudio.  If you want to improve your knowledge, I'd recommend working through ['Happy Git and GitHub for the useR'](http://happygitwithr.com/) first.

OK, let's get started!

---
## Supuestos
He hecho una serie de suposiciones al escribir esta guía:

- Tienes una cuenta de GitHub
- Tiene [RStudio](https://www.rstudio.com/products/rstudio/download/#download) instalado.
- Tiene [git](https://git-scm.com/downloads) instalado y su [identidad configurada](http://happygitwithr.com/hello-git.html). Si puede enviar a GitHub, ya lo ha hecho :)
- Te sientes cómodo usando git con RStudio. Si desea mejorar su conocimiento, le recomiendo trabajar primero con 'Happy Git y GitHub para el usuario'.
  
¡Bien, empecemos!


## Fork this repository

Fork this repo by clicking on the fork button on the top of this page.

---
## Bifurcar este repositorio
Bifurque este repositorio haciendo clic en el botón de bifurcación en la parte superior de esta página.

<img width="300" src="assets/fork.png" alt="fork this repository" style = "display: inline;"  />
<br/>

This will create of copy of this repository in your account and you will be redirected to this version of the repo.

You now need to get the URL for your repo.  Click "Clone or download" and copy the URL in the box.

Esto creará una copia de este repositorio en su cuenta y será redirigido a esta versión del repositorio.

Ahora necesita obtener la URL de su repositorio. Haga clic en "Clonar o descargar" y copie la URL en el cuadro.

<img width="300" src="assets/rstudio-gh-clone.png" alt="clone the repo" style = "display: inline;"  />
<br/>



## Create a new project

In RStudio, go to File -> New Project

Select "Version Control" and then "Git".

In the New Project dialog, paste the URL you copied from GitHub into the "Repository URL" box.

Choose the name you want the directory on your computer to be called, and put it in the "Project directory name" box.  By default, this is the name of the repo.

Finally, choose where you want the cloned repo to be stored by clicking the "Browse" button.

Once you have finished, click "Create Project" to clone the repo and set up the project.

---
# Crea un nuevo proyecto
En RStudio, vaya a Archivo -> Nuevo proyecto

Seleccione "Control de versiones" y luego "Git".

En el cuadro de diálogo Nuevo proyecto, pega la URL que copiaste de GitHub en el cuadro "URL del repositorio".

Elija el nombre que desea que se llame al directorio de su computadora y colóquelo en el cuadro "Nombre del directorio del proyecto". De forma predeterminada, este es el nombre del repositorio.

Finalmente, elija dónde desea que se almacene el repositorio clonado haciendo clic en el botón "Examinar".

Una vez que haya terminado, haga clic en "Crear proyecto" para clonar el repositorio y configurar el proyecto.

<img width="300" src="assets/rstudio-clone.png" alt="Git"  style = "display: inline;"  />
<br/>

The repo will now be cloned into whichever folder you specified.

El repositorio ahora se clonará en la carpeta que especificó.



## Create a branch / Crea una sucursal

In the "Git" tab in the top-right panel, click the "new branch" button.

En la pestaña "Git" del panel superior derecho, haz clic en el botón "nueva rama".

<img width="500" src="assets/git-tab-location.jpg" alt="Git tab"  style = "display: inline;"  />
<br/>
<img width="300" src="assets/rstudio-new-branch-button.png" alt="Create a new branch"  style = "display: inline;"  />
<br/>


Name your branch "add-your-name", for example: "add-nic-crane"

Nombre su rama "agregue-su-nombre", por ejemplo: "agregar-nombre-mariposa"

<img width="300" src="assets/rstudio-new-branch-button2.png" alt="name your branch"  style = "display: inline;"  />
<br/>

Make sure that "Sync branch with remote" is checked and click "Create".  You may be asked to enter your GitHub username and password.

Asegúrese de que "Sincronizar rama con remoto" esté marcado y haga clic en "Crear". Es posible que se le solicite que ingrese su nombre de usuario y contraseña de GitHub.




## Make necessary changes and commit those changes /  Realice los cambios necesarios y confirme esos cambios
Now open the `Contributors.md` file in RStudio and add your name to it, then save the file.

You will see that the file has an 'M' next to it.  Check the box next to it and then click "Commit".

Ahora abra el archivo ``Contributors.md`` en RStudio y agregue su nombre, luego guarde el archivo.

Verá que el archivo tiene una 'M' al lado. Marque la casilla junto a él y luego haga clic en "Confirmar".

<img width="300" src="assets/rstudio-add.png" alt="name your branch"   style = "display: inline;"  />
<br/>


You'll see a diff file showing the changes you've made to the file.  Add a commit message - a summary of changes you've made, and then click "Commit".  A box will pop up to confirm the commit; click "close".

Verá un archivo de diferencias que muestra los cambios que ha realizado en el archivo. Agregue un mensaje de confirmación, un resumen de los cambios que ha realizado, y luego haga clic en "Confirmar". Aparecerá un cuadro para confirmar la confirmación; haga clic en "cerrar".

<img width="400" src="assets/rstudio-commit-message.png" alt="name your branch"   style = "display: inline;"  />
<br/>




## Push changes to GitHub / Enviar cambios a GitHub

Congratulations, you've committed all the changes to your local copy of your branch of your fork of first-contributions.  Now click "Push" to sync your commit to the remote repo.

Felicitaciones, ha comprometido todos los cambios en su copia local de su rama de su bifurcación de primeras contribuciones. Ahora haga clic en "Push" para sincronizar su confirmación con el repositorio remoto.

<img width="500" src="assets/rstudio-push1.png" alt="name your branch"   style = "display: inline;"  />
<br/>

You'll see a box like this if your changes have been pushed successfully.  Click "Close".

Verá un cuadro como este si sus cambios se han realizado correctamente. Haga clic en "Cerrar".


<img width="400" src="assets/rstudio-push2.png" alt="name your branch"   style = "display: inline;"  />
<br/>




## Submit your changes for review / Envíe sus cambios para su revisión

If you go to your repository on github, you'll see a "Compare & pull request" button. Click on that button.

Si va a su repositorio en github, verá un botón "Comparar y solicitar extracción". Haga clic en ese botón.

<img width="500"  style = "display: inline;" src="assets/compare-and-pull.png" alt="create a pull request"   />
<br/>

Make sure that you are comparing across forks.  On the left should be the master branch of the original repo, and on the right should be the new branch you've made in your repo.  Once you've got the correct options selected and have written a quick summary of the changes made, submit the pull request by clicking "Create pull request".

Asegúrese de comparar bifurcaciones. A la izquierda debería estar la rama maestra del repositorio original, y a la derecha debería estar la nueva rama que ha creado en su repositorio. Una vez que haya seleccionado las opciones correctas y haya escrito un resumen rápido de los cambios realizados, envíe la solicitud de extracción haciendo clic en "Crear solicitud de extracción".

<img width="500" style = "display: inline;" src="assets/submit-pull-request.png" alt="submit pull request"   />
<br/>

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged!

Congrats!  You have just completed the standard _fork -> clone -> edit -> PR_ workflow that you'll encounter often as a contributor!


Pronto fusionaré todos sus cambios en la rama principal de este proyecto. ¡Recibirá un correo electrónico de notificación una vez que se hayan combinado los cambios!

¡Felicitaciones! ¡Acaba de completar la bifurcación estándar -> clonar -> editar -> flujo de trabajo de relaciones públicas que encontrará a menudo como colaborador!
