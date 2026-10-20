# Git y Docker/Your Security

## Descripción

Proyecto desarrollado en formato de Landing Page para la presentación de una aplicacion 
de compra y venta de elementos tecnologicos relacionados a la seguridad.


## Caracteristicas

 - MVP
 - BENCHMARK
 - USERFLOW
 - ARQUITECTURA DE LA INFORMACION


## Tecnologías utilizadas

- HTML 5
- CSS
- Git y GitHub
- Docker
- Nginx


## Requisitos para correr el programa 

- Tener Docker Deskop instalado y corriendo. 
- Tener GIT instalado. 
- Acceso a un navegador web.


## Construir la imagen de YS

En la carpeta del proyecto ("Docker"), se ejecuta: 

' docker build -t your-security:v1 . '


## Creación y ejecución del contenedor

' docker run -d --name contenedor-ys -p 8081:80 your-security:v1 ' 


## Acceder a la app

1 - Abrir el navegador
2 - Copiar y pegar en el buscador esta dirección: http://localhost:8081
3 - LISTO!! ACCESO PERMITIDO!!