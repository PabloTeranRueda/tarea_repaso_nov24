# tarea_repaso_nov24
# clone remote repository and move to it's folder
1. git clone git@github.com:PabloTeranRueda/tarea_repaso_nov24.git
2. cd tarea_repaso_nov24
# create folders
3. mkdir app manuals media configurations
# create initial files
4. touch app/main.js manuals/instrucciones.pdf media/banner.jpg configurations/settings.json
# create .gitignore file
5. touch .gitignore
# write into the .gitignore. Later this was manually modified to *.tmp and *.env,
# in order to exclude all files with those extensions
6. echo .tmp >> .gitignore
7. echo .env >> .gitignore
# create extra folder and file
8. mkdir local_config
9. touch local_config/configuracion_local.ini
