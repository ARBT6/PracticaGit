# Comandos Básicos

- En la clase de hoy vamos a ejecutar diferentes comandos de git

## Git Clone

El comando `git clone` se utiliza para crear una copia local de un repositorio que se encuentra en un servidor remoto (como GitHub o GitLab).

A diferencia de una descarga común, este comando descarga **todo el historial de versiones** y configura la conexión con el servidor de origen.

![Git Clone](img/git-clone.png)

### Línea de comando

Para clonar un repositorio en tu computadora, ejecuta:

```bash
git clone [https://github.com/usuario/nombre-del-proyecto.git](https://github.com/usuario/nombre-del-proyecto.git)

```
# Ejercicio
- haz lo anterior con lo siguiente (colocando una captura de pantalla en cada comando):

- git init (Inicia el despliegue de Github)
- git add . (Añade los archivos modificados para poder subirlos a github)
- git commit (Sirve para traer los cambios hechos en la computadora y poder subirlos)
- git branch gh-pages (crear la rama "gh-pages")
- git checkout gh-pages (Cambia de la rama main a la rma "gh-pages")
- git remote add origin https://github.com.... (Prepar los cambios para subirlos a github)
- git push origin (Sube los cambios a tu repo de github)
