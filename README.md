# Propagación de Enfermedades en Redes Unidimensionales

## Descripción

Este repositorio contiene las observaciones obtenidas de **simulaciones de Monte Carlo** realizadas en Python del modelo **SIR (Susceptible-Infectado-Recuperado)** en redes unidimensionales, utilizando la formulación de **stochastic lattice gas**.

## Contenido del Repositorio

- **`SIR_1D.ipynb`** - Notebook principal con la implementación del modelo y análisis de resultados
- **`Modelo_SIR_1D.pdf`** - Documento teórico con el formalismo del modelo
- **Archivos de datos** - Resultados de simulaciones en formato `.txt`:
  - Frecuencias de propagación para diferentes parámetros (c = 0.1, 0.5, 0.8)
  - Datos de distancia de propagación
  - Valores medios de coeficientes
  - Archivos de Mathematica con cálculos complementarios

## Modelo Teórico

El modelo SIR es un modelo compartimentado clásico que describe la propagación de enfermedades infecciosas. En esta implementación:

- **S (Susceptible)**: Individuos que pueden contraer la enfermedad
- **I (Infectado)**: Individuos actualmente infectados
- **R (Recuperado)**: Individuos que se han recuperado y son inmunes

Las simulaciones se realizan en **redes unidimensionales** usando la formulación de **stochastic lattice gas**, que proporciona un marco riguroso para estudiar dinámicas complejas en sistemas espacialmente correlacionados.


## 📄 Licencia

Este proyecto está bajo licencia **MIT**. Ver el archivo `LICENSE` para más detalles.



---

Para más información sobre la teoría y metodología, consulta el documento `Modelo_SIR_1D.pdf` y ejecuta el notebook `SIR_1D.ipynb` para ver las simulaciones en detalle.
