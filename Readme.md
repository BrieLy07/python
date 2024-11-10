# Proyecto en Python

Proyecto básico insertando texto para imprimirlo.

## Requisitos

- **Python 3.12.7** (o el que sea necesario para tu proyecto).
- **Docker**: Para crear y ejecutar contenedores.

## Instalación

Para clonar y ejecutar el proyecto localmente, sigue estos pasos:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/BrieLy07/python.git

2. cd tu_repositorio
    ```bash
    cd mi_repositorio
3. Construye la imagen Docker
    ```bash
    docker build -t python .

4. Corre el contenedor
    ```bash
    docker run -p 8080:8080 python
