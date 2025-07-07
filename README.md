# Clasificaci-n-basada-en-arboles-Proyecto-2-Parte-I-Core-
Análisis Exploratorio de Datos (EDA) y Selección de Problema de Machine Learning - Proyecto 2
Descripción del Proyecto
Este repositorio documenta la Parte I de un proyecto de análisis de datos que involucra la búsqueda y el Análisis Exploratorio de Datos (EDA) inicial de cuatro conjuntos de datos diversos. El objetivo principal es diagnosticar las características y desafíos de cada dataset para seleccionar un problema específico de Machine Learning a abordar (clasificación, regresión, clustering o predicción) y justificar esta elección basándose en los hallazgos del EDA y la disponibilidad de los datos. Finalmente, se presenta la estructura del repositorio en GitHub que organiza los resultados de esta primera fase.

Conjuntos de Datos Analizados
Se consideraron y se intentó realizar un EDA inicial para los siguientes cuatro conjuntos de datos obtenidos de fuentes confiables:

Iris Dataset: Un conjunto de datos clásico que contiene medidas de sépalo y pétalo de tres especies de flores Iris. Es comúnmente utilizado para problemas de clasificación. Fuente: UCI Machine Learning Repository.
Boston House Prices Dataset: Contiene información sobre diferentes aspectos de las propiedades residenciales en el área metropolitana de Boston y el precio mediano de las viviendas. Típicamente usado para problemas de regresión. Fuente: UCI Machine Learning Repository (Nota: Este dataset ha sido retirado de versiones recientes de scikit-learn debido a preocupaciones éticas y de privacidad, lo que pudo afectar su carga).
Mall Customer Dataset: Incluye datos de clientes de un centro comercial, como ID de cliente, género, edad, ingresos anuales y puntuación de gasto. Es útil para problemas de clustering y segmentación de clientes. Fuente: Kaggle.
Stock Prices Dataset: Representa datos históricos de precios y volumen de negociación de acciones. Este tipo de dataset se utiliza para análisis de series temporales y problemas de predicción de precios. Fuente: Varias (a menudo disponibles en Kaggle).
Resumen del EDA Inicial
Se realizó un EDA inicial para cada conjunto de datos disponible para comprender su estructura, identificar patrones, valores faltantes y atípicos.

Conjunto de Datos de Iris:
Características: Numéricas (longitud/anchura de sépalo y pétalo) y categórica (clase de la flor).
Valores Faltantes: Ninguno.
Valores Atípicos: Posibles atípicos observados en 'sepal_width' según los box plots, pero su impacto en la clasificación se considera bajo dado la clara separación de clases.
Hallazgos Clave: Las visualizaciones mostraron una clara separación entre las clases de Iris, especialmente utilizando las características del pétalo. Es un dataset muy limpio, ideal para clasificación.
Otros conjuntos de datos (Boston House Prices, Mall Customers, Stock Prices):
No fue posible cargar estos conjuntos de datos en el entorno de ejecución utilizado para el EDA inicial. Esto impidió realizar un análisis completo y detallado de sus características, valores faltantes/atípicos y desafíos específicos en esta fase. Su potencial uso para abordar otros tipos de problemas fue identificado basándose en el conocimiento general de estos datasets.
Problema Seleccionado
Basándonos en los resultados del EDA inicial y la disponibilidad práctica de los datos en el entorno de trabajo, se ha seleccionado el problema de Clasificación utilizando el Conjunto de Datos de Iris.

Justificación de la Elección
La elección del problema de Clasificación con el conjunto de datos de Iris se justifica por las siguientes razones:

Disponibilidad de los Datos: El EDA inicial se completó con éxito para el conjunto de datos de Iris, confirmando que los datos están disponibles y son accesibles en el entorno de trabajo actual. Esto es crucial para poder avanzar a las etapas de modelado y evaluación.
Éxito y Claridad del EDA: El análisis exploratorio de Iris reveló un dataset limpio, sin valores faltantes y con una clara separación entre las clases. Estos hallazgos facilitan el proceso de modelado y permiten enfocarse en la aplicación y comparación de algoritmos de clasificación.
Relevancia Educativa y Adecuación: La clasificación es una tarea fundamental en Machine Learning con numerosas aplicaciones. El conjunto de datos de Iris es un benchmark clásico y bien documentado, ideal para aprender y demostrar habilidades en preprocesamiento (mínimo en este caso), selección de modelos, entrenamiento, evaluación e interpretación en el contexto de un problema de clasificación multiclase.
Limitaciones de Otros Datasets: La imposibilidad de cargar y realizar un EDA efectivo en los otros conjuntos de datos (Boston, Mall Customers, Stock Prices) en esta fase impidió considerarlos seriamente para la selección del problema, a pesar de que representan otros tipos de problemas interesantes (regresión, clustering, predicción).
Desafío Controlado: Abordar un problema de clasificación en Iris presenta un desafío manejable que permite solidificar las bases en modelado predictivo antes de pasar a conjuntos de datos más complejos que requieren un preprocesamiento extenso o técnicas específicas (como series temporales).
Estructura del Repositorio
El repositorio sigue la siguiente estructura para organizar los notebooks del EDA inicial y los archivos relacionados con el conjunto de datos seleccionado:
