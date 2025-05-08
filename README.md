# Introducci¢n a Docker ??

Este repositorio contiene materiales, ejemplos y ejercicios pr cticos para iniciarse en el uso de Docker, una plataforma para desarrollar, enviar y ejecutar aplicaciones en contenedores.

## ?? ¨Qu‚ es Docker?

Docker es una herramienta que permite empaquetar una aplicaci¢n y todas sus dependencias en un contenedor, garantizando que se ejecute de manera uniforme en cualquier entorno. Es ampliamente utilizado para el desarrollo, pruebas e implementaci¢n de software.

## ?? Contenido

- `01_instalacion/` - Gu¡a para instalar Docker en distintos sistemas operativos.
- `02_conceptos_basicos/` - Explicaci¢n de im genes, contenedores, Dockerfile y comandos esenciales.
- `03_ejemplos/` - Ejemplos pr cticos de contenedores simples (Nginx, Node.js, Python).
- `04_docker_compose/` - Introducci¢n a `docker-compose` para aplicaciones multi-contenedor.
- `05_buenas_practicas/` - Recomendaciones y patrones comunes en el uso de Docker.

## ?? Requisitos Previos

- Conocimientos b sicos de terminal (CLI)
- Familiaridad con alg£n lenguaje de programaci¢n (opcional)
- Docker Desktop instalado [Instalar Docker](https://docs.docker.com/get-docker/)

## ?? Comandos B sicos

```bash
# Verificar instalaci¢n
docker --version

# Descargar una imagen
docker pull hello-world

# Ejecutar un contenedor
docker run hello-world

# Listar contenedores en ejecuci¢n
docker ps

# Detener todos los contenedores
docker stop $(docker ps -q)
