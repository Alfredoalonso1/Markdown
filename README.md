# GITHUB
Alfredo Alonso Garcia

![Imagen rota](https://i1.wp.com/unaaldia.hispasec.com/wp-content/uploads/2021/04/github.png?fit=1150%2C465&ssl=1 "Github")

- [GITHUB](#github)
  - [Que es github?](#que-es-github)
  - [Pasos a seguir](#pasos-a-seguir)
    - [Creación de una cuenta](#creación-de-una-cuenta)
    - [Usar en Linux](#usar-en-linux)
    - [Crear repositorios y subir archivos](#crear-repositorios-y-subir-archivos)
  - [Comandos](#comandos)
  - [Conclusiones](#conclusiones)

## Que es github?
Github es una herramienta en la nube el cual permite a los desarrolladores almacenar su código y administrarlo así como tener control sobre cualquier cambio realizado en el código y mantener un registro.

El control de versiones es un sistema el cual permite gestionar y rastrear los cambios que se realizan en uno o varios archivos permitiendo al usuario analizar los cambios y revertirlos si así fuera necesario.

Git es un proyecto de código abierto que se desarrolló por Linus Torvalds en 2005.
Es un sistema de control de versiones distribuida lo que implica que cualquier desarrollador que tenga acceso la puede gestionar el código y acceder a su historial.

## Pasos a seguir

### Creación de una cuenta

Primero que nada deberemos crear una cuenta en la pagina oficial de GitHub.
Una vez estemos en la página le deberemos dar a SIGN UP y completar el registro. Una vez completado ya tendremos nuestra cuenta y podremos acceder mediante el botón SIGN IN.


### Usar en Linux

Para poder utilizar GitHub deberemos acceder a nuestro terminal y escribir el siguiente comando:

> sudo apt-get update

Una vez ejecutado el anterior comando escribiremos el siguiente comando para instalar Git.

> sudo apt-get install git

Una vez tengamos instalado Git en nuestro ordenador deberemos escribir nuestro nombre de usuario y correo para que nos pueda identificar.

> git config --global user.name "nombre"

> git config --global user.email "ejemplo@email.com"

### Crear repositorios y subir archivos

Antes de subir ningún archivo lo primero que deberemos hacer es acceder a GitHub y crear un nuevo repositorio. Este repositorio almacenará los archivos que vayamos a subir.

Una vez tengamos nuestro repositorio lo que deberemos hacer es acceder a la carpeta donde se encuentren nuestros archivos mediante el comando cd o bien abrir un terminal en dicha carpeta.

Una vez estemos en la carpeta deberemos ejecutar el siguiente comando:

> git clone "URL repositorio"

## Comandos

Existen muchos comandos diferentes en GitHub los cuales nos permiten hacer diferentes cosas.

Para iniciar Git usaremos:

> git init

Si queremos clonar un repositorio de GitHub usaremos:

> git clone "URL"

Para añadir todos los archivos para el commit utilizaremos:

>git add.

Para realizar el primer commit debemos escribir:

> git commit "texto ejemplo"

Para subir todos los cambios y archivos deberemos escribir:

> git push origin master

## Conclusiones

GitHub es una herramienta muy útil a la hora de trabajar ya que nos permite modificar y subir archivos a los repositorios proporcionándonos un nivel de seguridad a la hora de no perder la información. 

Por otro lado también nos facilita el trabajo a la hora de hacer proyectos con otras personas en grupo.
