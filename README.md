# Construcción Modelo de Clasificación, usando Pyspark y MLlib

## Desarrollador por

- Carlos Alfredo Castillo Rodríguez [@alfcastillo90](https://www.github.com/alfcastillo90)


## Tecnologías utilizadas

Python, Pandas, Spark, JDK



## Descripción del codígo

- ### Paso 1
    - Instalación de librerías y softwares requeridos
    - Integración con google drive
    - Inicialización y creación de sesión en spark
- ### Paso 2: Exploración de datos
    - Lectura de archivo csv
    - verificamos los tipos de datos del esqumea
    - exploramos relaciones entre variables numericas  
- ### Paso 3: Analizamos los datos
    - Importamos StringIndexer y para transformar cada columna de texto en columnas numéricas. 
        - Inicialmente, StringIndexer devuelve los datos en formato flotante, por lo que debe realizarse la conversión de los valores flotantes a numéricos. 
        - Una vez que creado el DataFrame codificado, se selecciona solo los valores codificados.
        - Cuando esten listos los valores, se realiza la extracción de datos con VectorAssembler
