## Esta es un archivo que sirve para reconectar mi repositorio en github con mi directorio local.

En la consola del repositorio local creamos un archivo de texto que añadiremos a nuestro repositorio en github.
 - touch Readme.md

Luego añadimos nuestro correo y usuario de nuestro github al repositorio local.
 - git init
 - git add Readme.md
 - git commit -M "subimos el archivo a github"
 - git config --global user.email "ssantosmallqui@danielcastealo.org"
 - git config --global user.name "SusanaSantosM"
 - git config --global credential.helper 'cache --timeout-600'
 - git branch -M main
 - git remote add origin https://github.com/SusanaSantosM/Reconectando.git
 - git push -u origin main

 En este paso te pedira el usuario y contraseña de tu github.

