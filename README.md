# Análisis de pruebas A/B para la optimización de ingresos en una tienda online

## 1. Contexto y problema

Una tienda online busca identificar oportunidades para incrementar sus ingresos mediante la evaluación de distintas hipótesis de negocio y la comparación del comportamiento de dos grupos de usuarios.

El objetivo de este proyecto fue priorizar las hipótesis propuestas por el departamento de marketing, analizar los resultados de una prueba A/B y determinar si existían diferencias estadísticamente significativas entre los grupos A y B.

## 2. Mi contribución

Desarrollé un análisis integral que incluyó:

- Priorización de hipótesis mediante los frameworks ICE y RICE.
- Exploración y preparación de los conjuntos de datos.
- Análisis del comportamiento de los grupos durante el experimento.
- Identificación y tratamiento de valores atípicos.
- Aplicación de pruebas estadísticas para evaluar las diferencias entre grupos.
- Interpretación de resultados y elaboración de una recomendación de negocio.

## 3. Metodología y herramientas

**Herramientas utilizadas:**
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

**Metodología:**

1. Priorización de hipótesis utilizando ICE y RICE.
2. Exploración de los datos de pedidos y visitas.
3. Análisis de ingresos acumulados, conversión y tamaño promedio de pedido.
4. Identificación de usuarios y pedidos con comportamiento atípico.
5. Comparación de resultados con datos originales y filtrados.
6. Evaluación estadística mediante la prueba U de Mann-Whitney.

## 4. Resultados y hallazgos

El análisis mostró diferencias relevantes en la conversión entre los grupos:

- **Conversión:** después del filtrado, el grupo B presentó una conversión aproximadamente 18.9 % superior a la del grupo A. La diferencia fue estadísticamente significativa (p = 0.007).
- **Tamaño promedio de pedido:** no se encontró evidencia de una diferencia estadísticamente significativa entre los grupos después del filtrado (p = 0.822).
- **Valores atípicos:** se identificaron 16 usuarios con comportamiento de compra atípico para evaluar la estabilidad de los resultados.

Los resultados sugieren que la ventaja del grupo B en conversión se mantiene incluso después de excluir los datos atípicos, mientras que la diferencia observada en el tamaño promedio de pedido no resulta estadísticamente significativa.

## 5. Conclusión y recomendación

Con base en los resultados obtenidos, se recomendó detener la prueba A/B y considerar al grupo B como la alternativa con mejor desempeño en conversión.

Sin embargo, no se encontró evidencia suficiente para afirmar que el grupo B tuviera un mayor tamaño promedio de pedido.

Este proyecto permitió aplicar herramientas de análisis estadístico para transformar datos experimentales en información útil para la toma de decisiones de negocio.

## 6. Evidencia del proyecto

- **Notebook:** análisis exploratorio, priorización de hipótesis, visualizaciones, pruebas estadísticas y conclusiones.
- **Repositorio:** código y documentación del proyecto.

*Nota: Los conjuntos de datos originales pertenecen al entorno de formación de TripleTen y no se incluyen en este repositorio. Por ello, el notebook se presenta como evidencia del análisis realizado y sus resultados, pero no como una ejecución reproducible desde cero sin dichos archivos.*
