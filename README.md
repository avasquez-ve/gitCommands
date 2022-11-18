# gitCommands
gitCommands es un proyecto creado en el curso de Git y Github de Platzi. En el, describo los comandos más usados y su uso.

Se explica como trabajar con github y dar a conocer el flujo de trabajo para un repositorio en Git **(próximamente)**.

# Ventajas de gitCommands
El usar y practicar con git constantemente te ayudará comprender al 100% el flujo de trabajo de git y a conocer los comandos necesarios para trabajar con el.

Aunque a veces, por no estar trabajando en proyectos que usen git, o simplemente no tener la necesidad de usarlo **(cosa que está mal, siempre  deberías tener un repositorio para tu código)** puedes consultar este repositorio y recordar dichos comandos y cuál era su función.

Recuerda que:
> "La práctica hace al maestro, pero en el proceso, podemos usar gitCommands y aprender más rápido" 😜

# ¿Cómo contribuir?
Al ser un repositorio público, puedes obtener este proyecto, realizarle cambios y dejar un pull request para implementar las mejoras que desees.

Para contribuir debes:
1. Hacer un Fork de este proyecto para obtenerlo en tu cuenta de GitHub.  https://github.com/avasquez-ve/gitCommands.git
1. Hacer referencia desde tu equipo al repositorio ubicado en tu cuenta de GitHub:
	**HTTPS**
	```
	git clone https://github.com/[tu_usuario]/gitCommands.git
	```

	**SSH**
	```
	git clone  git@github.com:[tu_usuario]/gitCommands.git
	```
	donde **[tu_usuario]** hace referencia a tu nombre de usuario en GitHub.
1. Realizar un `git pull origin master` para obtener la última versión desde el repositorio en tu cuenta
1. Crear una rama llamada `upstream` la cual debe hacer referencia al repositorio principal https://github.com/avasquez-ve/gitCommands.git

	**HTTPS**
	```
	git remote add upstream https://github.com/avasquez-ve/gitCommands.git
	```

	**SSH**
	```
	git remote add upstream git@github.com:avasquez-ve/gitCommands.git
	```
	Esto para efectos de actualizar tu repositorio local con respecto al repositorio principal. (Puedes pasar tiempo sin hacer algo en el proyecto y otras personas podrían avanzar, recuerda que siempre debes tener la última versión antes de hacer un pull request)
1. Realizar los cambios que requieras y hacer el commit
1. Hacer un push a tu `origin master` 
1. Realizar un pull request desde GitHub al repositorio principal.
