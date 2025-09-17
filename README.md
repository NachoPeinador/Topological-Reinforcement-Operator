# Operador de Refuerzo Topológico (ORT): De la Simulación a la Neurociencia

**Autor**: José Ignacio Peinador Sala | **Contacto**: [joseignacio.peinador@gmail.com](mailto:joseignacio.peinador@gmail.com) | **ORCID**: [0009-0008-1822-3452](https://orcid.org/0009-0008-1822-3452)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![arXiv:XXXX.XXXXX](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX) ---

Este repositorio contiene la investigación y el código del **Operador de Refuerzo Topológico (ORT)**, un método computacional diseñado para emular la consolidación de engramas de memoria en redes complejas, desde sistemas modelo hasta conectomas cerebrales reales.

El proyecto busca responder a una pregunta fundamental: **¿Puede la memoria duradera emerger directamente de la organización topológica de una red?**

![Engram Visualization](https://i.imgur.com/TuImagen.png)
*Visualización de un engrama consolidado. Los nodos del núcleo (rojo) y su vecindario (naranja) demuestran una estructura de memoria funcional y resiliente.*

---

## 🎯 Implicaciones del Proyecto

* **Para la IA**: Un nuevo camino hacia modelos más eficientes, donde la especialización se logra con refuerzo topológico en lugar de reentrenamiento costoso.
* **Para la Neurociencia Computacional**: Una hipótesis concreta y reproducible sobre cómo podrían consolidarse los engramas en el cerebro.
* **Para la Ciencia de Redes**: Evidencia de que principios simples de conectividad pueden dar lugar a funciones complejas y resilientes, como la memoria asociativa.

---

## 🔬 Reproducibilidad y Experimentos Interactivos

Este proyecto se estructura en dos notebooks de Google Colab, permitiendo una exploración completa desde la prueba de concepto hasta la aplicación en datos neurocientíficos reales.

### **1. El Experimento Fundamental: ORT en Redes de Grafos y Conectomas**

Este notebook es el corazón del proyecto. Demuestra el pipeline completo del ORT, desde el entrenamiento de una GNN hasta la validación funcional en múltiples datasets, incluyendo un conectoma biológico.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](ENLACE_A_TU_COLAB_ORT.ipynb)

> **Contenido**:
> * Entrenamiento de una GNN en datasets clásicos (Cora, Citeseer, Pubmed).
> * Aplicación del ORT para identificar y reforzar el núcleo de la red.
> * Prueba funcional de memoria asociativa para reconstruir patrones dañados.
> * Aplicación final en un **conectoma de macaco** para explorar la plausibilidad biológica.

### **2. El Viaje al Cerebro: ORT en el Conectoma Humano**

Este notebook se centra en aplicar el ORT directamente a un cerebro humano digitalizado, explorando si los mismos principios matemáticos pueden identificar un "núcleo de memoria" en la red de conexiones cerebrales.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](ENLACE_A_TU_COLAB_ORT_HUMAN.ipynb)

> **Contenido**:
> * Carga de un conectoma humano real (BNU_1).
> * Cálculo de centralidades (Grado, PageRank) acelerado por GPU para identificar los "super-hubs".
> * Visualización de la distribución de conexiones, que sigue una ley de potencia.
> * Protocolo de recuperación de memoria para poner a prueba la resiliencia del núcleo del conectoma.

---

## 📂 Estructura del Repositorio

* `ORT_Experiment_Suite.ipynb`: Notebook principal con el pipeline completo (Cora, Pubmed, Macaco).
* `ORT_Human_Connectome.ipynb`: Notebook para el análisis del conectoma humano.
* `ORT_Report.pdf`: El PDF del artículo de investigación completo.
* `/data`: Carpeta para alojar los datasets de conectomas (requiere descarga manual).
* `/img`: Carpeta con las imágenes y visualizaciones clave del proyecto.
* `LICENSE`: La licencia MIT del proyecto.

---

## ✍️ Citación

Si encuentras este trabajo útil para tu investigación, por favor, cita nuestro artículo:

```bibtex
@misc{peinador2025engram,
      title={Emulación de la Consolidación de Engramas en Redes Neuronales mediante un Operador de Refuerzo Topológico}, 
      author={José Ignacio Peinador Sala},
      year={2025},
      eprint={XXXX.XXXXX},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
