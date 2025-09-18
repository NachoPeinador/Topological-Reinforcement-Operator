[Read this page in English](README_EN.md)

# Operador de Refuerzo Topológico (ORT): De la Simulación a la Neurociencia

**Autor**: José Ignacio Peinador Sala | **Contacto**: [joseignacio.peinador@gmail.com](mailto:joseignacio.peinador@gmail.com) | **ORCID**: [0009-0008-1822-3452](https://orcid.org/0009-0008-1822-3452)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![arXiv:XXXX.XXXXX](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX) ---

Este repositorio contiene la investigación y el código del **Operador de Refuerzo Topológico (ORT)**, un método computacional diseñado para emular la consolidación de engramas de memoria en redes complejas, desde sistemas modelo hasta conectomas cerebrales reales.

El proyecto busca responder a una pregunta fundamental: **¿Puede la memoria duradera emerger directamente de la organización topológica de una red?**

![Engram Visualization](https://github.com/NachoPeinador/Topological-Reinforcement-Operator/blob/main/outputs/img/engrama_consolidado.png)
*Visualización de un engrama consolidado. Los nodos del núcleo (rojo) y su vecindario (naranja) demuestran una estructura de memoria funcional y resiliente.*

---

## 🎯 Implicaciones del Proyecto

* **Para la IA**: Un nuevo camino hacia modelos más eficientes, donde la especialización se logra con refuerzo topológico en lugar de reentrenamiento costoso.
* **Para la Neurociencia Computacional**: Una hipótesis concreta y reproducible sobre cómo podrían consolidarse los engramas en el cerebro.
* **Para la Ciencia de Redes**: Evidencia de que principios simples de conectividad pueden dar lugar a funciones complejas y resilientes, como la memoria asociativa.

---

## 🔬 Reproducibilidad y Experimentos Interactivos

Este proyecto se estructura en dos notebooks de Google Colab, permitiendo una exploración completa desde la prueba de concepto hasta la aplicación en datos neurocientíficos reales.

### **Requisitos de Datos**

Para ejecutar los experimentos con conectomas biológicos, es necesario descargar los datasets de sus fuentes originales y colocarlos en una carpeta llamada `data/` en la raíz del proyecto.

* **Conectoma de Macaco**: [Descargar desde Network Repository](https://networkrepository.com/bn-macaque-rhesus-cerebral-cortex-1.php)
* **Conectoma Humano**: [Descargar desde Network Repository](https://networkrepository.com/bn-human-BNU-1-0025890-session-1.php)

### **1. El Experimento Fundamental: ORT en Redes de Grafos y Conectomas**

Este notebook es el corazón del proyecto. Demuestra el pipeline completo del ORT, desde el entrenamiento de una GNN hasta la validación funcional en múltiples datasets, incluyendo el conectoma de macaco.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](ENLACE_A_TU_COLAB_ORT.ipynb)

### **2. El Viaje al Cerebro: ORT en el Conectoma Humano**

Este notebook se centra en aplicar el ORT directamente a un cerebro humano digitalizado, explorando si los mismos principios matemáticos pueden identificar un "núcleo de memoria" en la red de conexiones cerebrales.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](ENLACE_A_TU_COLAB_ORT_HUMAN.ipynb)

---

## 📂 Estructura del Repositorio

* `ORT_Experiment_Suite.ipynb`: Notebook principal con el pipeline completo (Cora, Pubmed, Macaco).
* `ORT_Human_Connectome.ipynb`: Notebook para el análisis del conectoma humano.
* `ORT_Report.pdf`: El PDF del artículo de investigación completo (Español).
* `TRO_Report.pdf`: El PDF del artículo de investigación completo (Inglés).
* `/outputs`: Carpeta con todos los archivos generados por los notebooks.
  * `/csv`: Subcarpeta para los resultados cuantitativos en formato `.csv`.
  * `/img`: Subcarpeta para las visualizaciones e imágenes en formato `.png`.
* `LICENSE`: La licencia MIT del proyecto.

---


## 💖 Apoya este Proyecto

Este proyecto se desarrolla de forma independiente en tiempo libre. Si encuentras este trabajo valioso y quieres apoyar su continuidad y la creación de nuevas investigaciones, puedes hacerlo a través de GitHub Sponsors.

[![Sponsor @NachoPeinador](https://img.shields.io/badge/Sponsor-%E2%9D%A4-%23db61a2.svg)](https://github.com/sponsors/NachoPeinador)

Toda contribución, por pequeña que sea, ayuda a dedicar más tiempo a la ciencia abierta. ¡Gracias!

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
---



