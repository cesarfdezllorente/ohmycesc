# GIT
## Configuración básica
  
   Nombre del administrador:

`git config --global user.name "Antonio M.Durán Rosal"                                                                          `
  
   Correo electronico:
  
  `git config --global user.email udaran@uco.es`
  
   Editor de texto:
  
  `git config --global core.editor "gedit"`
  
   Color de interfaz:
  
  `git config --global color.ui true`
  
   Listado de la configuración:
    
   `got config --list`
  
 ## Comandos basicos I
 
   Iniciar repositorio en un directorio:
  
  `git init`
  
  Agregar cambios del area de *standing*:
  
  `git add`
  
  Validar cambios en el repositorio:
  
  `git commit -m "Mensaje"`
  
  Hacer los dos pasos anteriores en uno:
  
  `git commit -am "Mensaje"`
  
  Historial de commits:
  
  `git log`
  
 ## Comandos Basicos II
  
  Ayuda del listado anterior:
  
  `git help log`
  
  Listar los 5 commits mas recientes:
  
  `git log -n 5`
  
  Listar los commits desde una fecha:
  
  `git log --since=2018-09-18`
  
  Listar los commits por autor:
  
  `git log --author="Antonio"`
  
  Ver los cambios en el directorio:
  
  `git status`

  
  
  
  
