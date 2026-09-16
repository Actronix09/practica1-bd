# Contenedores en Docker

---

## Tabla de Contenidos

- [Diferencias entre contenedor y maquina virtual](#diferencias-entre-contenedor-y-maquina-virtual)
- [Imagen](#imagen)
- [Contenedor](#contenedor)
- [Volumen](#volumen)
- [Puerto publicado](#puerto-publicado)
- [Referencias](#referencias)

---

Los contenedores son "recipientes" donde hay una o multiples instacias instaladas, en estos contenedores nos permiten compartir proyectos entre equipos evitando la incompatibilidad de sistemas, ya que los contenedores ya tienen las configuraciones necesarias para cada proyecto y estas pueden ser compartidas entre usuarios.

## Diferencias entre contenedor y maquina virtual

|Caracteristica|Maquina Virtual|Contenedor|
|---|:---:|:---:|
|Velocidad de Arranque|$~30s-2m$|$~50ms-2s$|
|Tamaño|$1GB-20+ GB$|$~5MB-200MB$|
|Tipo de Aislamiento|A nivel de hardware|A nivel de sistema operativo|
|Comparte kernel con el host|✘|✔|
|Bajo consumo de recursos|✘|✔|
|Portabilidad entre entornos|✘|✔|
|Seguridad por separación total del hardware|✔|✘|
|Puede correr distintos SO en el host|✔|✘|
|Escalable|✘|✔|

## Imagen

Una imagen es una plantilla de solo lectura con instrucciones para crear un contenedor Docker. Suele partir de otra imagen base a la que se le agregan personalizaciones, y se construye mediante un Dockerfile (Docker, n.d.-b).

## Contenedor

Es un proceso aislado para cada componente de una aplicación, ejecutado a partir de una imagen. Es una instancia ejecutable de una imagen, definida tanto por la imagen como por las opciones de configuración que se le indiquen al crearlo o iniciarlo (Docker, n.d.-a).

## Volumen

Mecanismo de almacenamiento gestionado por Docker que vive fuera del ciclo de vida del contenedor, usado para persistir datos (bases de datos, archivos de usuario, etc.) que deben sobrevivir aunque el contenedor se elimine o recree (Docker, n.d.-c).

## Puerto publicado

Al lanzar un contenedor se puede exponer uno de sus puertos hacia la máquina host, creando un mapeo (por ejemplo -p 8080:80) que permite acceder desde fuera del contenedor a un servicio que corre dentro de él (Docker, n.d.-d).

## Referencias

- Docker. (n.d.-a). *What is a container?* Docker Docs. Recuperado el 16 de septiembre de 2026, de https://docs.docker.com/get-started/docker-concepts/the-basics/what-is-a-container/
- Docker. (n.d.-b). *Docker overview.* Docker Docs. Recuperado el 16 de septiembre de 2026, de https://docs.docker.com/get-started/overview/
- Docker. (n.d.-c). *Volumes.* Docker Docs. Recuperado el 16 de septiembre de 2026, de https://docs.docker.com/engine/storage/volumes/
- Docker. (n.d.-d). *Publishing and exposing ports.* Docker Docs. Recuperado el 16 de septiembre de 2026, de https://docs.docker.com/get-started/docker-concepts/running-containers/publishing-ports/
