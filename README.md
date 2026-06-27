
# Titulo del Proyecto: 
Proceso de admisión universitaria de los estudiantes de la Generación Z

# README: TAREA1_MG.IPYNB

## Datos Informativos 
**Nombre del maestrante:** Mónica Gallegos V.
**Módulo:** Big Data, Analytics & Data Scientist.
**Docente:** MSc. Carlos Carrillo.
**Tema del análisis:** Admisión de estudiantes_generaciónZ
**Fecha:** Julio 2026

## Tabla de Contenidos
- [Datos Informativos](#Datos Informativos)
- [Tabla de Contenidos](#Tabla de Contenidos)
- [Instrucciones](#Instrucciones)
- [Descripción del Dataset](#Descripción del Dataset)
- [Limpieza y Preparación de Datos](#Limpieza y Preparación de Datos)
- [EDA - Análisis de Datos Exploratorio](#EDA - Análisis de Datos Exploratorio)
- [Resultados y Conclusiones](#Resultados y Conclusiones)

## Instrucciones
1.Acceder al repositorio público en GitHub a través del [enlace](https://colab.research.google.com/drive/1nJ-gEbE8g7HIxXE0IzAGqriruarpAsGr?usp=drive_link)
2.Abrir el archivo TAREA1_MG.IPYNB en Google Colab
3.Cargar el dataset en el notebook: [genz_college_admission_prediction.csv](https://drive.google.com/file/d/1gkQtzylgUP1xyKExzFRDik0j2ftcqcMA/view?usp=sharing)
4.Actualizar la ruta
4.Ejecutar los códigos

## Descripción del Dataset
El conjunto de datos de predicción de admisión universitaria para la Generación Z es un conjunto de datos sintéticos a gran escala diseñado para modelar el proceso de admisión universitaria de los estudiantes de la Generación Z. A diferencia de los conjuntos de datos de admisión tradicionales, que se centran principalmente en el rendimiento académico, este conjunto incorpora una gama más amplia de factores que reflejan el panorama educativo en constante evolución, la participación digital, las actividades extracurriculares, la experiencia de liderazgo y el contexto socioeconómico de los estudiantes actuales.
El conjunto de datos contiene 1.000.000 de registros de estudiantes y está destinado a la investigación, el aprendizaje automático, las competiciones de ciencia de datos, el análisis predictivo, los estudios educativos y los desafíos de ingeniería de características.

## Librerías Utilizadas
Las principales librerías utilizadas para el análisis:

- **Pandas:** Manipulación y análisis de datos.
- **NumPy:** Operaciones numéricas.
- **Matplotlib:** Visualización gráfica.
- **Seaborn:** Visualización estadística avanzada.

## Limpieza y Preparación de Datos
Sección que incluye la revisión de nulos, duplicados, formatos, tipos de datos, fechas, outliers y transformaciones necesarias.

## EDA - Análisis de Datos Exploratorio

### Objetivo
El presente análisis tiene como finalidad explorar, visualizar e identificar patrones en los datos relacionados con la admisión universitaria de estudiantes. Se aplican técnicas de estadística descriptiva, visualización de datos y análisis de correlación para comprender los factores asociados al estado de admisión.

### Desarrollo de la Programación
A partir de las visualizaciones generadas se busca:
1. Comprender la estructura del dataset.
2. Identificar patrones de admisión.
3. Detectar relaciones entre variables académicas y personales.
4. Seleccionar variables relevantes para Machine Learning.
5. Generar conocimiento útil para la toma de decisiones en procesos de admisión universitaria.

## Resultados y Conclusiones
### Hallazgos Principales
* El conjunto de datos es grande y de buena calidad.
* No existen valores faltantes.
* La mayoría de estudiantes son admitidos (88%).
* Las variables académicas son potencialmente los factores más influyentes.
* Los indicadores extracurriculares complementan el perfil del estudiante.

### Desempeño Esperado del Modelo
Un Random Forest debería alcanzar un desempeño elevado debido a la fuerte relación entre las variables académicas y la admisión. Es importante evaluar más allá del Accuracy debido al desbalance de clases.

### Limitaciones
* Ausencia de variables temporales.
* Desbalance de la variable objetivo.
* Posibles correlaciones entre SAT, ACT y GPA.
```A brief description of what this project does and who it's for

