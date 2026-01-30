# Repositorio remoto en GitHub

## ¿Qué es un repositorio remoto?

Un repositorio remoto es un repositorio alojado en una plataforma en línea como GitHub, que permite guardar y compartir el proyecto.

## Creación de un repositorio remoto

1. Ingresar a GitHub.
2. Hacer clic en "New repository".
3. Asignar un nombre al repositorio.
4. No inicializar con README (si ya existe repositorio local).
5. Crear el repositorio.

## Conexión del repositorio local con el remoto

En la consola, ejecutar:

git remote add origin URL_DEL_REPOSITORIO
git branch -M main
git push -u origin main


## Sincronización de cambios

Para subir cambios:
git add .
git commit -m "Mensaje del commit"
git push


Para traer cambios:
git pull


## Conclusión

El repositorio remoto permite respaldar el proyecto y trabajar de forma colaborativa.
