# Equidad en el aprendizaje automático


## Descripción
Proyecto académico realizado en grupo con el objetivo de analizar el desempeño de un modelo de aprendizaje automático aplicado a un problema de aprobación de créditos bancarios, con especial foco en evaluar su equidad respecto de una variable sensible, utilizando el conjunto de datos **German Credit**.
Este repositorio corresponde a un **fork del trabajo original**, reorganizado, resumido y documentado para registro personal.


## Objetivos
- Generar modelos de clasificación para un problema de asignación de créditos en relación al "riesgo crediticio"
- Evaluar el desempeño mediante métricas tradicionales y seleccionar uno a modo de baseline
- Analizar el comportamiento del modelo respecto de distintos grupos
- Evaluar métricas de equidad
- Comparar y aplicar técnicas de mitigación de sesgos 


## Herramientas
- Python
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- holisticai


## Composición
1. **Análisis exploratorio de datos (EDA)**
   - Exploración de variables 
   - Análisis del target y las variables sensibles
2. **Modelo base**
   - Entrenamiento de dos modelos de clasificación 
   - Evaluación con métricas tradicionales
   - Eleccion de un modelo como baseline
3. **Evaluación de equidad**
   - Análisis de métricas de equidad para distintos grupos
4. **Mitigación**
   - Aplicación de técnicas para reducir las desigualdades observadas
5. **Análisis de resultados**
   - Comparación de resultados para distintas tecnicas de mitigación 


## Resultados principales
- Los datos se encontraron desbalanceados y con situaciones candidatas a generar sesgos
- El modelo que mejor se desempeño fue un regresor logístico
- El análisis de métricas de equidad permitió identificar posibles desigualdades 
- La mitigación aplicada mejoró la equidad del modelo

## Contenido del repositorio
- `fairness-in-german-credit.ipynb`: notebook principal 
- `README.md`: descripción del proyecto
- `requirements.txt`: dependencias necesarias para ejecutar el análisis


## ¿Cómo ejecutar el proyecto?
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/mbelenqui/fairness-in-german-credit.git
   ```
2. Instalar dependencias
   ```bash
   pip install -r requirements.txt
   ```
3. Abrir el notebook
   ```bash
   jupyter notebook fairness-in-german-credit.ipynb
   ```

## Conclusión

Este proyecto me permitió comprender la importancia de evaluar criterios de equidad en modelos de aprendizaje automático y analizar el impacto del uso de modelos de clasificación sesgados en contextos reales de toma de decisiones, donde las consecuencias también son reales.
