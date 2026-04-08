#  Premier League Predictor & Financial Backtesting Pipeline

##  Perfil del Proyecto
Desarrollado como parte de mi formación en Ingeniería de Software, este proyecto integra ingeniería de datos, análisis financiero y machine learning para evaluar la rentabilidad de algoritmos predictivos en mercados deportivos.

##  Arquitectura Técnica
- **Ingeniería de Datos:** Ingesta de datos históricos desde CSV a SQL Server mediante Python (Pandas & SQLAlchemy).
- **Machine Learning:** Modelo de clasificación Random Forest (Scikit-Learn).
- **Análisis de Negocio:** Dashboard en Power BI para el cálculo de ROI y visualización de KPIs.

##  Evolución del Modelo y Resultados
1. **v1.0 (Baseline):** Uso de cuotas de apuestas únicamente. Precisión: 50%.
2. **v2.0 (Contextual):** Inclusión de racha de puntos (últimos 3 partidos). Precisión: 52.63%.
3. **v3.0 (Táctico):** Inclusión de variables ofensivas/defensivas (Goles a favor/contra). **Precisión: 56.58%.**

##  Conclusión del Análisis Financiero
A pesar de alcanzar un **Accuracy del 56.58%**, el simulador financiero (Backtesting) arrojó un **ROI de -3.91%**. 
**Análisis Técnico:** Se demostró que la ventaja matemática de la casa de apuestas (House Edge) requiere no solo una alta precisión, sino una selección de "Apuestas de Valor" donde la probabilidad del algoritmo supere significativamente la implícita en la cuota. Este proyecto valida la importancia de la gestión de riesgos en sistemas predictivos.