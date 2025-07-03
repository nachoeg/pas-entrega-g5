# Entrega Grupo 5

## Inicio del sistema

Para iniciar todos los microservicios desarrollados, además del _message broker_ RabbitMQ, ejecute los siguientes comandos: 
```bash
# En el caso de tener una versión vieja de las imágenes:
docker compose pull
# Construir e iniciar todos los contenedores:
docker compose up --build
```
Es posible que se tenga que realizar un login de docker para realizar el primer pull de las imágenes.
En este caso ejecúte el siguiente comando:
```bash
docker login registry.gitlab.com/mauro4622412/microservice-grupo5/
#Username: <usuario-de-gitlab>
#Password: <contraseña-de-gitlab> o <personal-access-token> con el permiso 'read-registry'
 ```

---

## Pruebas

Para probar las distintas funcionalidades de los microservicios incluimos una colección de Postman, 
donde ya se encuentra establecido un token JWT con permisos de administrador.

También recomendamos utilizar la [interfaz visual de RabbitMQ](http://localhost:15672) para monitorear
el estado de las colas usadas en la coreografía del checkout.

---

## Diagramas
[Draw.io](https://app.diagrams.net/?splash=0#G1FjWdBIsC0CVbEe0tlG6Id2XjIN4UUhLW#%7B%22pageId%22%3A%22-pgCBTLRjhluLF6FBsHw%22%7D)

[Carpeta de Google Drive](https://drive.google.com/drive/folders/1ceOMPnnXG_LchKctBjBGdIJByxuqZ3)

---


## Integrantes
- Mauro Cesar Barone
- Andrés Gabriel Kessler
- Facundo Alcorta
- Ignacio Escudero Gonzalez