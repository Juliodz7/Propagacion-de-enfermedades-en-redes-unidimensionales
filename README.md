# Propagación de Enfermedades en Redes Unidimensionales

## Descripción

Este repositorio contiene las observaciones obtenidas de **simulaciones de Monte Carlo** realizadas en Python del modelo **SIR (Susceptible-Infectado-Recuperado)** en redes unidimensionales, utilizando la formulación de **stochastic lattice gas**.

## Objetivo

El objetivo principal de este proyecto es analizar la propagación de enfermedades infecciosas en sistemas unidimensionales utilizando el modelo SIR discreto en una red de agentes. Se busca:

- Analizar cómo parámetros clave (como la probabilidad de recuperación por agente) afectan la dinámica de propagación
- Comparar resultados numéricos con predicciones teóricas del modelo
- Cuantificar la distancia de propagación para diferentes configuraciones

## Resultados Principales

- **Dependencia de parámetros**: La propagación de la enfermedad muestra una fuerte dependencia con el coeficiente de recuperación c, observándose transiciones de fase a valores críticos
- **Distribuciones de propagación**: Se obtuvieron distribuciones de probabilidad para la distancia máxima alcanzada por la epidemia en la red
- **Umbrales epidemiológicos**: Se identificaron valores umbral de los parámetros por debajo de los cuales la enfermedad se extingue rápidamente
- **Validación teórica**: Los resultados numéricos muestran buen acuerdo con predicciones analíticas del modelo en el régimen de parámetros estudiado

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

Las simulaciones se realizan en **redes unidimensionales** usando la formulación de **stochastic lattice gas**, que proporciona un marco riguroso para estudiar dinámicas complejas en sistemas espacialmente extendidos.

## 📄 Licencia

Este proyecto está bajo licencia **MIT**. Ver el archivo `LICENSE` para más detalles.

---

Para más información sobre la teoría y metodología, consulta el documento `Modelo_SIR_1D.pdf` y ejecuta el notebook `SIR_1D.ipynb` para ver las simulaciones en detalle.
