# The Push Script

_Un Script para BASH que automatiza la actualización de un repositorio remoto Git._

## Comenzando 🚀

_Mantener un repositorio remoto Git actualizado puede llegar a ser una tarea monótona y tediosa ya que tenemos que realizar tres tareas para cada cambio que realicemos (git commit, git add y git push), fuera del echo de que en varias ocasiones no estamos muy imaginativos para escribir los detalles de los cambios realizados del Git commit._

_**The Push Script** automatiza toda esas tareas ejecutando un simple Script BASH que te mostrara los cambios que realizaste, registra la hora y fecha del commit, te da la posibilidad de agregar o no una descripción para el commit y te da la posibilidad de subir tus cambios  a distintos repositorios que tengas agregados en la lista de git remote, así como en distintas ramas remotas que tengas creadas._


## Pre-requisitos 📋

_Que cosas necesitas para ejecutar **the Push Script** ?_

* **En Windows**
    * **git Bash** o cualquier emulador de terminal de Linux. 
* **En linux y MacOs**
  * la terminal por defecto del sistema.

## Instalación 🔧

_Para tener una copia funcional del script necesitar descargar el archivo **push.sh** de este repositorio y copiar el script en la siguiente ruta, desde el Git bash, algún emulador de terminal de linux (en windows) o la terminal por defecto (en Linux o MacOs):_

```
~/bin/push.sh
```

_Para los usurario de Windows la carpeta "bin" no vendra creada en el sistema por defecto por lo que tendra que ser creada ejecutando el siguiente comando desde la ruta **~/**_

```
mkdir bin
```

_Puedes agregar un Nick o nombre de usuario editando la variable **USR_NAME** en el Script con un editor de código de tu preferencia._

## Ejecución ⚙️

_Una vez copiado el script en la ruta indicada simplemente ejecuta el siguiente comando desde la ruta de tu repositorio local en el que estés trabajando (es vital ejecutar el comando desde la raíz del repositorio para agregar todos los cambios realizados atreves del árbol de directorios de tu proyecto)_

```
push
```

_Al ejecutarse, el script te mostrara en la terminal todos los cambios que realizaste en cualquier archivo, para dejar de mostrar los  cambios y pasar al git commit escribe q en la terminal._

```
q
```

_En el git commit te solicitara que ingreses un mensaje para el git commit, este mensaje es opcional ya que por defecto registrara tu  nombre de usuario, la fecha y hora del commit._

_Una vez finalizado el git commit el script agregara de manera automática todos tus cambios y pasara a la parte del **git push** en la cual te dara la opción de subir los cambios a un repositorio diferente de Origin/Master, para lo cual te solicitara el nombre del repositorio así como la rama, el nombre del repositorio alternativo debe estar registrado en tu lista de git remote para que funcione._

## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 🖇️

Quieres colaborar mejorando el codigo de **The Push Script** ? estoy a la espera de tu pull requests.

## Autores ✒️

* **Oliver Zulett** - *Desarrollo y diseño del script* - [OliverZulett](https://github.com/OliverZulett) 

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.



---
⌨️ con ❤️ [OliverZulett](https://github.com/OliverZulett)  😊
