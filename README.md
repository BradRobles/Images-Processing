# Procesamiento de Imágenes - Análisis de Rendimiento (Unidad 2)

Este repositorio contiene la implementación y el análisis de rendimiento de tres filtros comunes de procesamiento de imágenes: Filtro Gaussiano, Filtro Sobel y Filtro Mediano. El objetivo principal es evaluar cómo diferentes enfoques computacionales afectan el tiempo de ejecución.

## 👥 Autores
* **Jorge Ramiro Chay Koyoc** - *Ingeniería de Datos, Universidad Politécnica de Yucatán (UPY)*
* **Angeles Alejandra Cruz Legorreta** - *Ingeniería de Datos, Universidad Politécnica de Yucatán (UPY)*
* **Brad Robles García** - *Ingeniería de Datos, Universidad Politécnica de Yucatán (UPY)*

## 🚀 Descripción del Proyecto
Para cada uno de los tres filtros, se desarrollaron tres implementaciones distintas para comparar su eficiencia:
1. **Python Puro:** Implementación base utilizando listas nativas y bucles iterativos, sin optimizaciones externas.
2. **NumPy:** Implementación optimizada mediante operaciones matriciales y vectorización.
3. **Cython + NumPy:** Implementación de alto rendimiento utilizando código compilado en C con tipado estático.

El repositorio incluye los scripts en Python, las implementaciones en Cython y el entorno necesario para su ejecución.

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu_usuario/tu_repositorio.git](https://github.com/tu_usuario/tu_repositorio.git)
   cd tu_repositorio
