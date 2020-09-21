# Web API dotNet Core con Docker & Ngnix
Implementación demo de balanceo de carga en Nginx con Docker y dotNet Core

**_Estructura de Carpetas_**

1. carpeta ngnix (archivos de configuración proyecto)
2. carpeta src  (carpeta proyecto)
3. archivo docker compose

**_Algunos puntos a considerar_:**

- Debes tener configurado Docker for Windows [link descarga](https://www.google.com)
- La configuración de balanceo de Nginx viene por default **Round-Robin**
- A la configuración se le puede agregar peso con **weight**


## Comandos a ejecutar para la demo
docker-compose up --scale api=4 --build
