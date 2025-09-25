# A/B Test – Recommender System

## Project Description
This project analyzes the results of an A/B test designed to evaluate whether a new recommender system improves user conversion in the funnel.

## Objective
- **Main goal:** Determine if the new recommender system increases conversion rates in the funnel.  
- **Primary metric:** Conversion rate at each funnel step.  
- **Secondary metrics:** Step-to-step rates (visit → cart → purchase), user activity distribution, and temporal analysis.  
- **Hypotheses:**  
  - H0: No significant difference between groups A and B.  
  - H1: Group B shows at least +10% improvement.  
- **Significance level:** α = 0.05  

## Tools & Libraries
- Python (pandas, numpy, scipy, matplotlib, seaborn)  
- Statistical testing (hypothesis testing, significance analysis)  

## Methodology
1. Data cleaning and validation (removal of duplicates and out-of-scope users).  
2. Exploratory data analysis of groups A and B.  
3. Funnel construction and analysis of conversion paths.  
4. Hypothesis testing to validate differences between groups.  

## Key Results
- Final valid sample: ~12.4K users (balanced between groups).  
- Many purchases occurred **without a prior “add to cart” event**, indicating alternative purchase flows or tracking peculiarities.  
- User activity was consistent between groups (≈7 events per user).  
- **No statistically significant differences** were detected between groups A and B.  

## Conclusion
The new recommender system did not demonstrate a clear impact on conversions during the experiment period.  
It is recommended to refine the hypothesis or adjust the implementation before running a new A/B test.  

---

# Versión en Español

## Descripción del proyecto
Este proyecto analiza los resultados de una prueba A/B diseñada para evaluar si un nuevo sistema de recomendaciones mejora la conversión de los usuarios en el embudo.

## Objetivo
- **Meta principal:** Determinar si el nuevo sistema de recomendaciones aumenta las tasas de conversión en el embudo.  
- **Métrica primaria:** Tasa de conversión en cada paso del embudo.  
- **Métricas de apoyo:** Tasas entre etapas (visita → carrito → compra), distribución de actividad y análisis temporal.  
- **Hipótesis:**  
  - H0: No existen diferencias significativas entre los grupos A y B.  
  - H1: El grupo B muestra un aumento de al menos +10%.  
- **Nivel de significancia:** α = 0.05  

## Herramientas y librerías
- Python (pandas, numpy, scipy, matplotlib, seaborn)  
- Pruebas estadísticas (test de hipótesis, análisis de significancia)  

## Metodología
1. Limpieza y validación de datos (exclusión de duplicados y usuarios fuera de alcance).  
2. Análisis exploratorio de los grupos A y B.  
3. Construcción del embudo y revisión de los flujos de conversión.  
4. Prueba de hipótesis para validar diferencias entre los grupos.  

## Resultados principales
- Muestra final válida: ~12.4K usuarios (balanceada entre grupos).  
- Muchos usuarios realizaron compras **sin pasar por “añadir al carrito”**, lo que refleja flujos alternativos de compra o particularidades del sistema de tracking.  
- La actividad de usuarios fue consistente entre grupos (≈7 eventos por usuario).  
- **No se encontraron diferencias estadísticamente significativas** entre los grupos A y B.  

## Conclusión
El nuevo sistema de recomendaciones no mostró un impacto claro en las conversiones durante el período analizado.  
Se recomienda replantear la hipótesis o ajustar la implementación antes de realizar un nuevo experimento.  