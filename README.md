## EXPLICACIÓN DE GIT
**GIT INIT**
 1. Inicia un nuevo repositorio de Git en el directorio actual. Crea un subdirectorio llamado .git donde Git almacena toda la información de tu repositorio, incluyendo el historial de cambios.
2.-Úsalo solo una vez para inicializar un nuevo proyecto con Git.

**GIT ADD**
1. Agrega todos los archivos nuevos o modificados en el directorio actual al área de preparación (staging area). Esto significa que Git los "prepara" para el próximo commit, pero aún no los guarda en el historial.
2. El punto (.) indica que quieres agregar todos los archivos en el directorio actual.

**GIT COMMIT -M (DESCRIPCIIÓN DE COMMIT)**

1. Crea un "snapshot" de los archivos en el área de preparación y guarda estos cambios en el historial de Git.
2. La opción **-m** te permite agregar un mensaje descriptivo para el commit (como un resumen de los cambios realizados).

**GIT PUHS**

1. Sube los commits de tu repositorio local a un repositorio remoto (por ejemplo, en GitHub). Necesitarás estar conectado a un repositorio remoto para usar este comando.
2. Es común que sigas este flujo: primero **git add**, luego **git commit**, y finalmente **git push** para compartir tus cambios en línea.

**GIT PULL**
1. Trae los últimos cambios del repositorio remoto a tu repositorio local y los fusiona con tu código actual. Es útil cuando varios colaboradores están trabajando en el mismo proyecto.
2. Realiza, de forma interna, una combinación de **fetch** (descargar cambios) y **merge** (fusionar cambios).

**GIT REMOTE -V**
1. Muestra las URLs de los repositorios remotos que tienes configurados en tu repositorio local.
2. La opción **-v** te da una lista de los remotos con sus URLs, mostrando si son configuraciones de **fetch** (descargar) o **push** (subir).


![LogoGit](https://upload.wikimedia.org/wikipedia/commons/e/e0/Git-logo.svg)