### Primeros pasos - un primer repositorio

Antes de comenzar a trabajar, establezcamos el ambiente
`touch .bash_history;source .bashrc`{{execute}}

Revisemos la versión de Git
`git --version`{{execute}}

Los pasos a continuación son
- Crear un repo en github
- Clonar el repo
`git clone <url_github>`
- Crear archivos de un proyecto y "agregarlos" a nuestro repo
`git add .`{{execute}}
- Modificar los archivos y regitrar los cambios (hacer un commit)
`git commit -m "se inicializa proyecto y se cargan archivos"`{{execute}}
- Guardar los cambios en nuestro repossitorio remoto 
`git push origin master`{{execute}}
- Volver a la última versión guardada (o último commit)
`git reset --hard HEAD`
  <pre class="file">
Los Comandos aprendidos hasta ahora
git --version
git clone <url>
git add .
git commit -m "mensaje"
git push origin master
git log
git reset --hard HEAD
</pre>
