# Laboratorios Prácticos de Docker - TECSUP

Repositorio oficial que contiene el desarrollo de los cuatro laboratorios prácticos sobre Dockerfile, construcción de imágenes, optimización y seguridad.

## Datos del Alumno
* **Nombre:** Emanuel Huaco

## Estructura del Repositorio

| Laboratorio | Descripción | Imagen Docker | Puerto |
| :--- | :--- | :--- | :--- |
| **[01-nginx-basico](01-nginx-basico/)** | Servidor Nginx personalizado con HTML estático | `emanuel-huaco-web:v1` | `8080` |
| **[02-api-python](02-api-python/)** | API REST desarrollada con FastAPI y Python 3.12 | `emanuel-huaco-api:v1` | `8081` |
| **[03-optimizacion](03-optimizacion/)** | Optimización de capas, caché y `.dockerignore` | `emanuel-huaco-api:v2` | `8082` |
| **[04-seguridad](04-seguridad/)** | Prácticas de seguridad (usuario non-root, USER) | `emanuel-huaco-api:v3` | `8083` |

## Tecnologías Utilizadas
* Docker / Docker Compose
* Nginx (Alpine)
* Python 3.12 & FastAPI
* Linux (Google Compute Engine)


### IMAGES
![Images](/01-nginx-basico/evidences/evidencia-images.png)