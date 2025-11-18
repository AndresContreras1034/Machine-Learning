# Conceptos Básicos de Machine Learning

Este documento presenta los conceptos fundamentales necesarios para comprender el campo del Machine Learning. Su propósito es establecer una base sólida antes de avanzar hacia algoritmos, teoría avanzada y modelos de Deep Learning.

---

## 1. ¿Qué es el Machine Learning?

El Machine Learning (ML) es una rama de la inteligencia artificial que permite que un sistema aprenda patrones a partir de datos y mejore su desempeño en una tarea sin haber sido programado explícitamente para cada caso.

En lugar de definir reglas manualmente, el modelo analiza ejemplos y construye una representación interna que le permite realizar predicciones o decisiones.

---

## 2. Tipos de Aprendizaje en Machine Learning

### 2.1 Aprendizaje Supervisado

El modelo aprende a partir de un conjunto de datos etiquetados.
Cada ejemplo tiene una entrada y una salida conocida.

Casos típicos:

* Clasificación
* Regresión

Formalmente, se aprende una función
f(x) ≈ y
donde y es conocida.

### 2.2 Aprendizaje No Supervisado

El modelo aprende patrones sin utilizar etiquetas.

Objetivos comunes:

* Agrupamiento (clustering)
* Reducción de dimensionalidad
* Detección de anomalías

Busca estructuras internas en los datos sin una salida explícita.

### 2.3 Aprendizaje Semi-supervisado

Combina pocos datos etiquetados con muchos datos no etiquetados.

Útil cuando etiquetar es costoso.

### 2.4 Aprendizaje por Refuerzo

Un agente interactúa con un entorno, toma acciones y recibe recompensas.
El objetivo es maximizar la recompensa acumulada.

No usa pares entrada-salida ni busca patrones directos, sino estrategias óptimas.

---

## 3. Tareas Comunes en Machine Learning

### 3.1 Clasificación

Asignar una etiqueta a una entrada.

Ejemplos:

* Detección de spam
* Diagnóstico médico binario
* Reconocimiento de dígitos

### 3.2 Regresión

Predecir un valor numérico continuo.

Ejemplos:

* Predicción de precios
* Estimación de demanda
* Modelos de series temporales

### 3.3 Clustering

Agrupar datos según similitud sin etiquetas externas.

Ejemplos:

* Segmentación de clientes
* Agrupación de imágenes
* Análisis exploratorio

### 3.4 Reducción de Dimensionalidad

Reducir la cantidad de características preservando la información más relevante.

Ejemplos:

* PCA
* t-SNE
* UMAP

### 3.5 Detección de Anomalías

Identificar puntos inusuales o sospechosos en un conjunto de datos.

---

## 4. Concepto de Dataset

Un dataset es la colección de ejemplos que el modelo utiliza para aprender.

Suele dividirse en:

* **Entrenamiento** (train): para aprender los parámetros
* **Validación** (val): para ajustar hiperparámetros
* **Prueba** (test): para evaluar el desempeño final

Esta división evita que el modelo memorice los datos y asegura que generalice correctamente.

---

## 5. Características y Etiquetas

* **Características (features)**: variables de entrada.
* **Etiquetas (labels)**: valores esperados en aprendizaje supervisado.

Ejemplo simple:

| tamaño | habitaciones | precio |
| ------ | ------------ | ------ |
| 80 m²  | 3            | 120000 |

Aquí, tamaño y habitaciones son características, y precio es la etiqueta.

---

## 6. Overfitting y Underfitting

### Overfitting

El modelo aprende demasiado bien los datos de entrenamiento, incluidas sus particularidades y ruido, pero falla en datos nuevos.
Indica mala capacidad de generalización.

### Underfitting

El modelo es demasiado simple para capturar los patrones importantes.
Tiene bajo rendimiento tanto en entrenamiento como en prueba.

---

## 7. Funciones de Pérdida (Loss Functions)

La función de pérdida mide qué tan mal está funcionando el modelo.
El entrenamiento busca minimizar esta medida.

Ejemplos:

* MSE (regresión)
* Cross-entropy (clasificación)
* Hinge loss (SVM)

---

## 8. Optimización y Gradiente

La mayoría de los modelos se entrenan ajustando parámetros mediante optimización iterativa.
El método central es el **gradiente descendente**, que actualiza los parámetros en la dirección que reduce la pérdida.

Variantes:

* SGD
* Adam
* RMSprop

Estos métodos permiten entrenar modelos grandes como redes neuronales.

---

## 9. Evaluación de Modelos

Se utilizan métricas para medir el desempeño según la tarea:

* Clasificación: accuracy, precision, recall, F1-score
* Regresión: MAE, RMSE, R²
* Ranking: AUC-ROC

Una correcta evaluación evita conclusiones erróneas sobre el modelo.

---

## 10. Generalización

La meta principal del Machine Learning es que el modelo funcione correctamente en datos no vistos.
Un modelo que solo funciona en el conjunto de entrenamiento no es útil.

La generalización se logra mediante:

* Regularización
* Buena división del dataset
* Modelos adecuados
* Datos representativos

---

## 11. Pipeline Básico de Machine Learning

1. Definición del problema
2. Recolección de datos
3. Limpieza y preprocesamiento
4. División del dataset
5. Entrenamiento del modelo
6. Validación y ajuste
7. Pruebas y evaluación
8. Interpretación de resultados
9. Despliegue o documentación

Este flujo se repetirá constantemente a medida que se aprenda y se desarrollen proyectos más complejos.

---

## 12. Rol de la Teoría en el Aprendizaje

La teoría permite entender:

* por qué los modelos funcionan,
* cuáles son sus limitaciones,
* cómo diagnosticar errores,
* cómo escoger arquitecturas adecuadas.

Este repositorio combina teoría y práctica para construir un entendimiento integral del campo.
