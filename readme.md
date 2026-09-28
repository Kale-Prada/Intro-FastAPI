# Aprendiendo con FastAPI - INTRO

**Aplicación realizada con FastAPI y base de datos con SQLite**

Realiza consultas SQL a una tabla de una base de datos creada con "DB Browser for SQLite". 


## Acerca de las herramientas usadas:

**FastAPI:**   

[Descarga FastAPI](https://fastapi.tiangolo.com)

Framework web moderno, Open Source, rápido, de alto rendimiento. Facilita la creación rápida de APIs modernas en Python con validación automática de datos y documentación interactiva. Buscar ser lo más intuitivo y eficiente posible.

La clave de su diseño es la simplicidad a través de la estandarización basada en estándares abiertos como OpenAPI y JSON Schema, y explota al máximo las anotaciones de tipo de Python y Pydantic.

El creador de FastAPI es el desarrollador colombiano Sebastián Ramírez, conocido en la comunidad de programación y en GitHub bajo el seudónimo de *tiangolo*.

**SQlite:**   

[Descarga SQLite](https://www.sqlite.org/)

Sistema de gestión de bases de datos relacional. Crea un único archivo ordinario en disco que se puede guardar en cualquier carpeta del equipo. 

Sus características principales: de código abierto, sin servidor (Serverless), embedida (Embedded), un solo archivo, muy ligera. 

Creado por el desarrollador estadounidense D. Richard Hipp en el año 2000.

**DB Browser for SQLite:** 

Programa muy popular para trabajar con BBDD: ver tablas, buscar datos y ejecutar comandos SQL como si fuera una hoja de cálculo. Compatible con Windows, Mac y Linux. Muy sencillo de usar. 

## Detalles para ejecutar el backend:


## Instalación y Ejecución

1. Clona o descarga el repositorio en tu equipo.
2. Abre la carpeta del proyecto en Visual Studio Code.
3. Crea y activa un entorno virtual:
   ```bash
    # Para crear el entorno: 
    # En Windows: 
    python -m venv entorno
    
    #Otra opción: 
    py -m venv entorno 

    # En MacOS: 
    python3 -m venv entorno

    # Para activar el entorno: 
    # En Windows:
    .\entorno\Scripts\activate

    # En macOS/Linux:
    source entorno/bin/activate
   ```
4. Instala las librerías necesarias ejecutando:
   ```bash
   # En Windows:
   pip install -r requirements.txt

   # En macOS/Linux:
   pip3 install -r requirements.txt
   ```

## Requerimientos
Instala requirements.txt
### En Windows:
   `pip install -r requirements.txt`

### En macOS/Linux:
   `pip3 install -r requirements.txt`

## Licencia

Autor = Keepcoding España S.L.U.