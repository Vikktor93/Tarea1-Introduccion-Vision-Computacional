<p align="left">
   <img src="https://img.shields.io/badge/Status-En%20Desarrollo-green?style=plastic">
   <img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=python&logoColor=white"/>
   <img src="https://img.shields.io/badge/Jupyter-%23e58f1a.svg?style=plastic&logo=Jupyter&logoColor=white"/>

<img src="./assets/banner-computer-vision1.png"/>

## 🌿**Tarea 1: Introducción a la Visión Computacional**
Este repositorio contiene el desarrollo de la Tarea 1 de la asignatura de Visión Computacional, cuyo objetivo es aplicar técnicas básicas de preprocesamiento y análisis sobre un subconjunto del dataset [PlantVillage](https://www.kaggle.com/datasets/emmarex/plantdisease), enfocado en la clasificación de hojas de tomate sanas y con enfermedad *Early Blight*.

### 🧪 **Descripción del trabajo**

- **Dataset:** PlantVillage (2 clases: `Tomato_healthy`, `Tomato_Early_blight`)
- **Subconjunto:** 200 imágenes (100 por clase), seleccionadas aleatoriamente desde `train`, `test` y `validation`.
- **Preprocesamiento:**  
  - Redimensionamiento a **128x128 px**
  - Aplicación de **filtro gaussiano** para suavizado
- **Visualización:** Se incluyen ejemplos comparativos entre imágenes originales, redimensionadas y filtradas.
- **Documentación:** El notebook contiene explicaciones paso a paso, justificación de decisiones y plan para Tarea 2.

### ⚠️ **Requisitos**

Este proyecto requiere:

- Python 3.10+
- OpenCV (`cv2`)
- matplotlib
- Jupyter Notebook

## 📄 Licencia
Este trabajo es de carácter académico y su uso está restringido solo para fines educativos.

El dataset utilizado proviene del repositorio [PlantVillage Dataset](https://github.com/spMohanty/PlantVillage-Dataset), desarrollado por Hughes & Salathé (2015).  
Por favor, cite el artículo correspondiente si reutiliza este dataset:

> Hughes, D. P., & Salathé, M. (2015). An open access repository of images on plant health to enable the development of mobile disease diagnostics. *arXiv preprint arXiv:1511.08060.*