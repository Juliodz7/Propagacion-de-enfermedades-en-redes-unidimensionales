# Propagación de Enfermedades en Redes Unidimensionales

## Descripción

Este repositorio contiene las observaciones obtenidas de **simulaciones de Monte Carlo** realizadas en Python del modelo **SIR (Susceptible-Infectado-Recuperado)** en redes unidimensionales, utilizando la formulación de **stochastic lattice gas**.

## 📋 Contenido del Repositorio

- **`SIR_1D.ipynb`** - Notebook principal con la implementación del modelo y análisis de resultados
- **`Modelo_SIR_1D.pdf`** - Documento teórico con el formalismo del modelo
- **Archivos de datos** - Resultados de simulaciones en formato `.txt`:
  - Frecuencias de propagación para diferentes parámetros (c = 0.1, 0.5, 0.8)
  - Datos de distancia de propagación
  - Valores medios de coeficientes
  - Archivos de Mathematica con cálculos complementarios

## 🔬 Modelo Teórico

El modelo SIR es un modelo compartimentado clásico que describe la propagación de enfermedades infecciosas. En esta implementación:

- **S (Susceptible)**: Individuos que pueden contraer la enfermedad
- **I (Infectado)**: Individuos actualmente infectados
- **R (Recuperado)**: Individuos que se han recuperado y son inmunes

Las simulaciones se realizan en **redes unidimensionales** usando la formulación de **stochastic lattice gas**, que proporciona un marco riguroso para estudiar dinámicas complejas en sistemas espacialmente correlacionados.

### Parámetros Principales

- **β (Tasa de Infección)**: Define la probabilidad de que un individuo susceptible contraiga la enfermedad al estar en contacto con uno infectado
- **γ (Tasa de Recuperación)**: Define la velocidad a la que los individuos infectados se recuperan
- **c**: Parámetro de control que varía en las simulaciones (0.1, 0.5, 0.8)

## 🐍 Tecnologías Utilizadas

- **Python** - Implementación de simulaciones de Monte Carlo
- **Jupyter Notebook** - Análisis interactivo y visualización de resultados
- **Monte Carlo** - Método de muestreo estadístico para simulaciones estocásticas
- **Mathematica** - Cálculos teóricos complementarios

## 📊 Resultados Principales

El repositorio contiene análisis detallados de:
- **Frecuencias de propagación** bajo diferentes condiciones de parámetros
- **Distancias de propagación** de la enfermedad en la red
- **Valores medios de coeficientes** con diferentes tamaños de red (1e3, 1e4, 1e5 sitios)
- **Comportamiento del modelo** ante variaciones en los parámetros de control

## 🚀 Cómo Usar

1. Abre el notebook `SIR_1D.ipynb` en Jupyter Notebook o Google Colab
2. Sigue las celdas para ejecutar las simulaciones
3. Consulta el archivo `Modelo_SIR_1D.pdf` para entender la teoría detrás del modelo
4. Analiza los archivos de datos generados para ver los resultados de las simulaciones

## 📄 Licencia

Este proyecto está bajo licencia **MIT**. Ver el archivo `LICENSE` para más detalles.

## 👤 Autor

**Juliodz7** - [Perfil de GitHub](https://github.com/Juliodz7)

---

Para más información sobre la teoría y metodología, consulta el documento `Modelo_SIR_1D.pdf` y ejecuta el notebook `SIR_1D.ipynb` para ver las simulaciones en detalle.