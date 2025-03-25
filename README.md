# 🧬 Compra Genética

Proyecto de optimización de compras en supermercados utilizando **Algoritmos Genéticos**, desarrollado para la materia **Inteligencia Artificial Distribuida** en el ITLA.

## 🎯 Objetivo

Diseñar e implementar un sistema que optimice el costo total de una compra, considerando:

- Precios de productos en diferentes sucursales.
- Costos de transporte según distancias.
- Combinaciones óptimas de selección, cruzamiento y mutación.

## 🧠 Tecnología y técnicas utilizadas

- Python + Google Colab
- Algoritmos genéticos personalizados
- Heurísticas avanzadas (crossover, mutación, selección)
- Validación con datasets reales y métricas (MAE, MSE, ENP...)
- Manejo de estructuras como grafos, árboles y matrices de distancia
- Visualización con Matplotlib y Seaborn
- Registro de logs, control de recursos y rendimiento

## 📂 Estructura del proyecto

- `GAOptimization`: clase principal del algoritmo genético.
- `FlujoGeneral`: automatiza ejecuciones en datasets (small, medium, big).
- `problemset.xlsx`: dataset base con catálogos, grafos y queries.
- `Validación`: análisis comparativo con múltiples combinaciones de parámetros.
- `logs/`: registros detallados de cada ejecución.

## 🧪 Validación

El sistema fue evaluado contra métodos de referencia (Greedy, Fuerza Bruta Aproximada) y mostró **excelentes resultados**. Las configuraciones con mejor desempeño fueron:

- **Selección**: `hard`
- **Crossover**: `uniform`
- **Mutación**: `swap`

## 📈 Resultados

El análisis estadístico arrojó:

- MAE promedio más bajo con `hard_uniform_swap`
- Menor dispersión y error puntual
- Reducción significativa en costos comparados con métodos de referencia

## 👨‍💻 Contribuyentes

- **Darwin Méndez**  
  [GitHub](https://github.com/Daarwinmendez)  
  [LinkedIn](https://www.linkedin.com/in/darwin-mendez-061881185)

- **Camily García**  
  [GitHub](https://github.com/CamyG18)  
  [LinkedIn](https://www.linkedin.com/in/camily-garcía-7b4632319)

- **Michael García**  
  [GitHub](https://github.com/MichaGF0305)  
  [LinkedIn](https://www.linkedin.com/in/michael-david-garc%C3%ADa-feliz-37446b296)

- **Roither Sánchez**  
  [GitHub](https://github.com/XTrollaX)  
  [LinkedIn](https://www.linkedin.com/in/roither-sànchez-sosa-b77b37244)

## ⚠️ Notas sobre honestidad académica

Este repositorio **no contiene ni sube instrucciones textuales del docente**. Toda la lógica y documentación fueron desarrolladas por los estudiantes, basadas en el análisis e implementación de los requerimientos de la materia.

---
