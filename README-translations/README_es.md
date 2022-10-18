## Primera contribución

| <img alt="RStudio" src="../assets/rstudio-logo.png" width="300"> | RStudio Edition |
| ---------------------------------------------------------------- | --------------- |

Este repositorio es una versión cortada, recortada y personalizada para RStudio del increíble repositorio [primeras contribuciones](https://github.com/firstcontributions/first-contributions) (y no está afiliado oficialmente con RStudio). Consulte el repositorio original para obtener instrucciones sobre el uso de otras herramientas y traducciones de idiomas.

---

## Introducción

Es dificil. Siempre es difícil cuando haces algo por primera vez. Especialmente cuando estás colaborando, cometer errores no es algo cómodo. Pero el código abierto tiene que ver con la colaboración y el trabajo conjunto. Queríamos simplificar la forma en que los nuevos colaboradores de código abierto aprenden y contribuyen por primera vez.

Leer artículos y ver tutoriales puede ayudar, pero ¿qué es mejor que hacer las cosas sin estropear nada? Este proyecto tiene como objetivo proporcionar orientación y simplificar la forma en que los novatos hacen su primera contribución. Recuerde que cuanto más relajado esté, mejor aprenderá. Si está buscando hacer su primera contribución, simplemente siga los sencillos pasos a continuación. Te lo prometemos, será divertido.

---

## Lo que esto te enseñará

-   Cómo bifurcar un repositorio
-   Cómo hacer una rama
-   Cómo enviar una solicitud de extracción al repositorio original

---

## Lo que esto no te enseñará

-   Cómo construir paquetes R
-   Etiqueta de código abierto

---

## Supuestos

He hecho una serie de suposiciones al escribir esta guía:

-   Tienes una cuenta de GitHub
-   Tiene [RStudio](https://www.rstudio.com/products/rstudio/download/#download) instalado.
-   Tiene [git](https://git-scm.com/downloads) instalado y su [identidad configurada](http://happygitwithr.com/hello-git.html). Si puede enviar a GitHub, ya lo ha hecho :)
-   Te sientes cómodo usando git con RStudio. Si desea mejorar su conocimiento, le recomiendo trabajar primero con 'Happy Git y GitHub para el usuario'.

¡Bien, empecemos!

---

## Bifurcar este repositorio

Bifurque este repositorio haciendo clic en el botón de bifurcación en la parte superior de esta página.

<img width="300" src="../assets/fork.png" alt="fork this repository" style = "display: inline;"  />
<br/>

Esto creará una copia de este repositorio en su cuenta y será redirigido a esta versión del repositorio.

Ahora necesita obtener la URL de su repositorio. Haga clic en "Clonar o descargar" y copie la URL en el cuadro.

<img width="300" src="../assets/rstudio-gh-clone.png" alt="clone the repo" style = "display: inline;"  />
<br/>

---

## Crea un nuevo proyecto

En RStudio, vaya a Archivo -> Nuevo proyecto

Seleccione "Control de versiones" y luego "Git".

En el cuadro de diálogo Nuevo proyecto, pega la URL que copiaste de GitHub en el cuadro "URL del repositorio".

Elija el nombre que desea que se llame al directorio de su computadora y colóquelo en el cuadro "Nombre del directorio del proyecto". De forma predeterminada, este es el nombre del repositorio.

Finalmente, elija dónde desea que se almacene el repositorio clonado haciendo clic en el botón "Examinar".

Una vez que haya terminado, haga clic en "Crear proyecto" para clonar el repositorio y configurar el proyecto.

<img width="300" src="../assets/rstudio-clone.png" alt="Git"  style = "display: inline;"  />
<br/>

El repositorio ahora se clonará en la carpeta que especificó.

---

## Crea una sucursal

En la pestaña "Git" del panel superior derecho, haz clic en el botón "nueva rama".

<img width="500" src="../assets/git-tab-location.jpg" alt="Git tab"  style = "display: inline;"  />
<br/>
<img width="300" src="../assets/rstudio-new-branch-button.png" alt="Create a new branch"  style = "display: inline;"  />
<br/>

Nombre su rama "agregue-su-nombre", por ejemplo: "agregar-nombre-mariposa"

<img width="300" src="../assets/rstudio-new-branch-button2.png" alt="name your branch"  style = "display: inline;"  />
<br/>

Asegúrese de que "Sincronizar rama con remoto" esté marcado y haga clic en "Crear". Es posible que se le solicite que ingrese su nombre de usuario y contraseña de GitHub.

---

## Realice los cambios necesarios y confirme esos cambios

Ahora abra el archivo `Contributors.md` en RStudio y agregue su nombre, luego guarde el archivo.

Verá que el archivo tiene una 'M' al lado. Marque la casilla junto a él y luego haga clic en "Confirmar".

<img width="300" src="../assets/rstudio-add.png" alt="commit button"   style = "display: inline;"  />
<br/>

Verá un archivo de diferencias que muestra los cambios que ha realizado en el archivo. Agregue un mensaje de confirmación, un resumen de los cambios que ha realizado, y luego haga clic en "Confirmar". Aparecerá un cuadro para confirmar la confirmación; haga clic en "cerrar".

<img width="400" src="../assets/rstudio-commit-message.png" alt="commit dialog"   style = "display: inline;"  />
<br/>

---

## Enviar cambios a GitHub

Felicitaciones, ha comprometido todos los cambios en su copia local de su rama de su bifurcación de primeras contribuciones. Ahora haga clic en "Push" para sincronizar su confirmación con el repositorio remoto.

<img width="500" src="../assets/rstudio-push1.png" alt="push button"   style = "display: inline;"  />
<br/>

Verá un cuadro como este si sus cambios se han realizado correctamente. Haga clic en "Cerrar".

<img width="400" src="../assets/rstudio-push2.png" alt="git output log"   style = "display: inline;"  />
<br/>

---

## Envíe sus cambios para su revisión

Si va a su repositorio en github, verá un botón "Comparar y solicitar extracción". Haga clic en ese botón.

<img width="500"  style = "display: inline;" src="../assets/compare-and-pull.png" alt="create a pull request"   />
<br/>

Asegúrese de comparar bifurcaciones. A la izquierda debería estar la rama maestra del repositorio original, y a la derecha debería estar la nueva rama que ha creado en su repositorio. Una vez que haya seleccionado las opciones correctas y haya escrito un resumen rápido de los cambios realizados, envíe la solicitud de extracción haciendo clic en "Crear solicitud de extracción".

<img width="500" style = "display: inline;" src="../assets/submit-pull-request.png" alt="submit pull request"   />
<br/>

Pronto fusionaré todos sus cambios en la rama principal de este proyecto. ¡Recibirá un correo electrónico de notificación una vez que se hayan combinado los cambios!

¡Felicitaciones! ¡Acaba de completar la bifurcación estándar -> clonar -> editar -> flujo de trabajo de relaciones públicas que encontrará a menudo como colaborador!
