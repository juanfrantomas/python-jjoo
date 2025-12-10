# Análisis de Datos de Atletas y Medallas en los Juegos Olímpicos

## Descripción
Este proyecto forma parte del trabajo del Máster en Inteligencia Artificial & Big Data Analytics y explora los datos de atletas y medallas en los Juegos Olímpicos. Utilizando Python y la librería Pandas, se realiza un análisis exhaustivo de las características y tendencias de los datos, incluyendo segregaciones por género, tipo de juegos (invierno/verano), país de origen, entre otros.

Los datos de entrada provienen de dos tablas principales: **Atletas** y **Medallas**, que se combinan para obtener una visión completa de los atletas olímpicos.

## Objetivos
- Explorar y analizar datos de atletas y medallas en los Juegos Olímpicos.
- Combinar técnicas de análisis de datos con programación en Python.
- Realizar análisis de características y tendencias, incluyendo segregaciones por género, juegos de invierno o verano, país de origen, etc.
- Resolver una serie de retos cerrados y uno abierto a elección del estudiante.

## Retos a Realizar
El trabajo incluye 4 retos diferenciados, cada uno con tareas de procesamiento, manipulación y visualización de datos, además de una función en Python relacionada.

### RETO 1: Relacionar los datos de entrada y obtener una visión completa de los/las atletas
- Tareas: Combinar las tablas de Atletas y Medallas para crear un dataset unificado.
- Función: Implementar una función para fusionar los datos y manejar posibles inconsistencias.

### RETO 2: Analizar perfiles físicos y demográficos
- Tareas: Analizar características como edad, altura, peso, género, etc., y visualizar distribuciones.
- Función: Crear una función para calcular estadísticas demográficas y físicas por categorías.

### RETO 3: Estudiar las medallas obtenidas y el rendimiento
- Tareas: Analizar el número de medallas por país, atleta, deporte, etc., y tendencias a lo largo del tiempo.
- Función: Desarrollar una función para calcular rankings y métricas de rendimiento.

### RETO 4: Formular un objetivo abierto y resolverlo
- Tareas: Elegir un objetivo adicional, como predecir medallas futuras o analizar impacto de variables socioeconómicas.
- Función: Implementar una función personalizada para resolver el objetivo abierto.

## Estructura del Proyecto
- `data/`: Carpeta con los archivos de datos (Atletas.csv, Medallas.csv).
- `retoPython.ipynb`: Jupyter Notebook con el análisis y visualizaciones.
- `requirements.txt`: Archivo con las dependencias de Python.
- `README.md`: Este archivo.

## Instalación
1. Clona este repositorio:
   ```
   git clone https://github.com/juanfrantomas/python-jjoo.git
   cd python-jjoo
   ```
2. Crea un entorno virtual:
   ```
   python -m venv .venv
   ```
3. Activa el entorno virtual:
   - En Linux/Mac: `source .venv/bin/activate`
   - En Windows: `.venv\Scripts\activate`
4. Instala las dependencias:
   ```
   pip install -r requirements.txt
   ```

## Uso
Ejecuta los notebooks en Jupyter para ver el análisis paso a paso.

## Autores
- https://github.com/juanfrantomas
- https://github.com/nachogalianolopez

## Licencia
Este proyecto es parte de un trabajo académico.
