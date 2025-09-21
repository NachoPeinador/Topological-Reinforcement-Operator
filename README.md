[Read this page in English](README_EN.md)

# Operador de Refuerzo Topológico (ORT): De la Simulación a la Neurociencia

**Autor**: José Ignacio Peinador Sala | **Contacto**: [joseignacio.peinador@gmail.com](mailto:joseignacio.peinador@gmail.com) | **ORCID**: [0009-0008-1822-3452](https://orcid.org/0009-0008-1822-3452)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![DOI](https://img.shields.io/badge/DOI-10.48550/arXiv.XXXX.XXXXX-b31b1b.svg)](https://doi.org/10.48550/arXiv.XXXX.XXXXX)

---

Este repositorio contiene la investigación y el código del **Operador de Refuerzo Topológico (ORT)**, un método computacional diseñado para emular la consolidación de engramas de memoria en redes complejas, desde sistemas modelo hasta conectomas cerebrales reales.

El proyecto busca responder a una pregunta fundamental: **¿Puede la memoria duradera emerger directamente de la organización topológica de una red?**

![Engram Visualization](https://github.com/NachoPeinador/Topological-Reinforcement-Operator/blob/main/outputs/img/engrama_consolidado.png)
*Visualización de un engrama consolidado. Los nodos del núcleo (rojo) y su vecindario (naranja) demuestran una estructura de memoria funcional y resiliente.*

---

## 🎯 Hallazgos Principales

* **✅ Recuperación de memoria perfecta**: 100% de recuperación en Pubmed y conectoma humano
* **✅ Validación biológica**: Estructura de "super-hubs" confirmada en conectoma humano real
* **✅ Generalización robusta**: Funciona en redes desde 2,700 hasta 178,000 nodos
* **✅ Mecanismo simple**: La centralidad de grado supera a métricas complejas

---

## 🔬 Experimentos Interactivos

### **Requisitos de Datos**

Para ejecutar los experimentos con conectomas biológicos:
1.  Descarga el archivo `.edges` desde la fuente original
2.  Súbelo al almacenamiento de Google Colab antes de ejecutar

* **Conectoma de Macaco**: [Network Repository](https://networkrepository.com/bn-macaque-rhesus-cerebral-cortex-1.php)
* **Conectoma Humano**: [Network Repository](https://networkrepository.com/bn-human-BNU-1-0025890-session-1.php)

### **1. Experimento Fundamental: ORT en Redes y Conectomas**
Pipeline completo desde GNN hasta validación en múltiples datasets.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OukR00V035_fHGbIVuXwso2FWCoD8_Q5?usp=sharing)

### **2. Viaje al Cerebro: ORT en Conectoma Humano**
Aplicación directa a un cerebro humano digitalizado.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1r9p6agxbX0cT9hqzkwL4XCuO10_Eu73i?usp=sharing)

---

## 📂 Estructura del Repositorio

* **`/Notebooks`**: Todos los cuadernos de experimentos (español e inglés)
* **`/Reports`**: Artículos de investigación completos (español e inglés)  
* **`/outputs`**: Resultados generados por los experimentos
  * `/csv`: Datos cuantitativos en formato CSV
  * `/img`: Visualizaciones y gráficos
* **`/data`**: Datasets y archivos de entrada
* `LICENSE`: Licencia MIT del proyecto

---

## 🔬 Ciencia Independiente y Abierta

Este trabajo se realizó de manera completamente independiente, sin financiación institucional ni corporativa, demostrando que la investigación de frontera puede surgir también desde entornos abiertos y accesibles.

[![Sponsor @NachoPeinador](https://img.shields.io/badge/Sponsor-%E2%9D%A4-%23db61a2.svg)](https://github.com/sponsors/NachoPeinador)

---

## ✍️ Citación

```bibtex
@misc{peinador2025engram,
      title={Emulación de la Consolidación de Engramas en Redes Neuronales mediante un Operador de Refuerzo Topológico}, 
      author={José Ignacio Peinador Sala},
      year={2025},
      eprint={XXXX.XXXXX},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
