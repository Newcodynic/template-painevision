# Notas del proyecto

## Importante
Recordar crear una carpeta llamada "project-content" junto a carpeta assets. Esta carpeta es para guardar el material de apoyo para el proyecto.
Revisar archivo .gitignore

## Comandos de git
Para crear un clon del repositorio localmente:
```
git clone link-del-proyecto
```

Para bajar posibles cambios desde el repositorio remoto al repositorio local:
```
git pull
```

Para revisar el estado de los archivos podemos ejecutar:
```
git status
```

Para revisar el estado del proyecto, ver todos los commits y ver quién los hizo
```
git log
```

Para agregar un archivo o carpeta al stage podemos ejecutar:
```
git add index.html          // Agrega un archivo específico.
git add *.js                // Agrega todos los archivos con una exención específica.
git add assets/             // Agrega una carpeta específica.
git add .                   // Agrega todos los archivos que se modificaron.
```

Para hacer snapshot del estado actual del proyecto:
```
git commit -m 'Primer commit'    // Se agregan todos los archivos que se encuentran en stage bajo un comentario significativo.
```

Para subir nuestros cambios en el repositorio local al repositorio remoto:
```
git push
```

Para ver las ramas que existen en el proyecto:
```
git branch
```

Para viajar a una rama en específico:
```
git checkout nombre-rama
```
