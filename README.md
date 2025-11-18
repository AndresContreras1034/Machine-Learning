# Repositorio de Aprendizaje en Machine Learning y Deep Learning

Este repositorio reúne mi proceso completo de estudio en Machine Learning, Deep Learning, Generative Adversarial Networks (GANs) y teoría fundamental. Su propósito es documentar el aprendizaje de manera organizada, escalable y profesional, permitiendo revisar teoría, analizar implementaciones, ejecutar modelos y almacenar resultados.

La estructura está diseñada para servir como referencia a largo plazo, funcionando como un manual personal en constante evolución.

---

## Estructura General del Repositorio

El repositorio se organiza por áreas de conocimiento, separando teoría, implementación, experimentación y proyectos.

```
ML-Learning-Repo
│
├── 00_Teoria/
│   ├── 00_Introduccion/
│   ├── 01_MachineLearning/
│   ├── 02_DeepLearning/
│   ├── 03_CNN/
│   ├── 04_RNN/
│   ├── 05_Transformers/
│   ├── 06_Optimizers/
│   ├── 07_LossFunctions/
│   └── 08_GANs/
│
├── 01_AlgoritmosClasicos/
│   ├── datasets/
│   ├── notebooks/
│   └── src/
│
├── 02_DeepLearning/
│   ├── MLP/
│   ├── CNN/
│   ├── RNN/
│   ├── Autoencoders/
│   └── Transformers/
│
├── 03_GANs/
│   ├── GAN_Basica/
│   ├── DCGAN/
│   ├── WGAN/
│   ├── WGAN_GP/
│   ├── CGAN/
│   ├── Experimentos/
│   ├── datasets/
│   └── modelos/
│
├── 04_ProyectosML/
│   ├── LigaEspañola-ML/
│   ├── Clasificadores/
│   └── ModelosEntrenados/
│
├── 05_Experimentos/
│   ├── pruebas_gpu/
│   ├── benchmarks/
│   └── iteraciones_gan/
│
├── utils/
│   ├── metrics.py
│   ├── visualizations.py
│   └── loaders.py
│
└── README.md
```

---

## Objetivo del Repositorio

1. Consolidar teoría y práctica de Machine Learning y Deep Learning en un solo lugar.
2. Mantener implementaciones reproducibles de modelos clásicos y avanzados.
3. Documentar arquitecturas GAN de manera clara, incluyendo código, resultados y análisis.
4. Explorar proyectos aplicados con datos reales.
5. Registrar experimentos, pruebas y benchmarks para medir progresos y comparaciones.

---

## Contenido Detallado

### 1. Teoría (00_Teoria/)

Incluye fundamentos teóricos esenciales:

* Conceptos base de Machine Learning
* Aprendizaje supervisado, no supervisado y de refuerzo
* Redes neuronales y backpropagation
* Arquitecturas de Deep Learning
* Redes convolucionales, recurrentes y transformers
* Técnicas de regularización y optimización
* Tipos de funciones de pérdida
* Teoría completa de GANs, incluyendo variantes modernas

Este módulo permite entender los fundamentos que sustentan cada modelo del repositorio.

---

### 2. Algoritmos clásicos (01_AlgoritmosClasicos/)

Implementaciones desde cero y con librerías estándar:

* Regresión
* KNN
* Árboles de decisión
* Random Forest
* Support Vector Machines
* XGBoost
* Métricas y validación

---

### 3. Deep Learning (02_DeepLearning/)

Implementación modular de arquitecturas neuronales:

* Perceptrón multicapa
* Redes convolucionales
* Redes recurrentes
* Autoencoders
* Transformers y variantes

Cada subcarpeta contiene modelos, datos, notebooks y resultados.

---

### 4. GANs (03_GANs/)

Colección organizada de distintos tipos de GANs:

* GAN básica
* DCGAN
* WGAN y WGAN-GP
* Conditional GAN
* Experimentos propios
* Datasets internos
* Modelos entrenados

Cada carpeta incluye:

* Código de entrenamiento
* Arquitectura utilizada
* Gráficas de pérdidas
* Imágenes generadas
* Notas técnicas por experimento

---

### 5. Proyectos ML Aplicados (04_ProyectosML/)

Proyectos completos basados en datos reales, como:

* Liga Española: clasificación de resultados
* Clasificadores de distintos tipos
* Modelos entrenados almacenados para uso posterior

Cada proyecto incluye:

* src
* notebooks
* data
* modelos
* outputs
* README interno

---

### 6. Experimentos (05_Experimentos/)

Espacio destinado a pruebas de todo tipo:

* Estrés de GPU
* Benchmarks
* Iteraciones de GAN
* Experimentación abierta

---

### 7. Utilidades (utils/)

Funciones comunes utilizadas en varios módulos:

* Métricas personalizadas
* Herramientas de visualización
* Cargadores de datos y preprocesamiento

---

## Requisitos Técnicos

Lenguajes y librerías principales:

* Python 3.10+
* PyTorch
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

Cada carpeta que lo requiera incluye su propio `requirements.txt`.

---

## Cómo Usar el Repositorio

Clonar el repositorio:

```
git clone <url-del-repo>
cd ML-Learning-Repo
```

Explorar teoría:

```
cd 00_Teoria
```

Ejecutar un modelo GAN:

```
cd 03_GANs/DCGAN
python train.py
```

---

## Convenciones del Repositorio

* Toda carpeta de modelo contiene:

  * train.py
  * model.py
  * utils.py
  * outputs/

* Documentación interna mediante README por subcarpeta

* Cuadernos Jupyter únicamente en `notebooks/`

* Resultados de entrenamiento siempre en `outputs/`

* Código modular y mantenible

---

## Visión del Proyecto

Este repositorio está diseñado como un recurso estructurado y completo para aprender Machine Learning y Deep Learning de forma sólida. La combinación de teoría, código, experimentos y documentación permite un crecimiento continuo y un punto de referencia claro para futuros desarrollos.
