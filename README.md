# Proyecto-15
Análisis de prueba A/B – Sistema de recomendaciones en e-commerce
Proyecto 15: Análisis de prueba A/B – Sistema de recomendaciones en e-commerce
Descripción del proyecto

Este proyecto consistió en el análisis completo de una prueba A/B realizada por una tienda en línea internacional con el objetivo de evaluar la efectividad de un nuevo sistema de recomendaciones dentro del embudo de conversión.

La prueba fue interrumpida previamente por el equipo anterior, por lo que el análisis requirió una validación exhaustiva de la calidad de los datos, así como la reconstrucción del contexto experimental para evaluar la validez de los resultados.

Objetivo del estudio

Evaluar si la implementación de un sistema de recomendaciones mejorado incrementa la conversión de usuarios en las etapas clave del embudo de ventas:

Vista de página de producto (product_page)
Adición al carrito (product_cart)
Compra (purchase)

El objetivo esperado era lograr un aumento mínimo del 10% en cada etapa dentro de los 14 días posteriores al registro del usuario.

Metodología

Se trabajó con datos de usuarios, eventos y participantes de la prueba A/B, realizando las siguientes tareas:

Limpieza y validación de datos (tipos, valores nulos y duplicados)
Integración de múltiples datasets para reconstruir el embudo de conversión
Segmentación de usuarios en grupo de control (A) y grupo de prueba (B)
Análisis exploratorio de datos (EDA) del comportamiento del usuario
Evaluación de la distribución de eventos por usuario y por día
Detección de posibles sesgos, como usuarios duplicados entre grupos o solapamiento de campañas de marketing
Análisis realizado

Durante el EDA se evaluaron:

Conversión en cada etapa del embudo de ventas
Distribución de eventos por usuario en ambos grupos
Consistencia de la asignación de usuarios a los grupos de prueba
Evolución temporal de los eventos durante el periodo de análisis
Posibles anomalías en la estructura del experimento

Posteriormente, se aplicó una prueba estadística Z para proporciones, con el fin de determinar si las diferencias observadas entre los grupos A y B eran estadísticamente significativas.

Resultados clave
Se identificaron posibles inconsistencias en la asignación de usuarios y en la distribución de eventos, lo que pudo afectar la validez del experimento.
No todas las etapas del embudo mostraron mejoras consistentes en el grupo B.
La prueba estadística no evidenció diferencias significativas en todas las conversiones esperadas.
Se observó la necesidad de mejorar el diseño experimental y el control de sesgos en futuras pruebas A/B.
Conclusiones
El análisis permitió concluir que la implementación del nuevo sistema de recomendaciones no demostró un impacto claramente positivo en la conversión del embudo bajo las condiciones del experimento.

Además, se destacaron aspectos críticos en la calidad del diseño de la prueba, como la posible contaminación entre grupos y la falta de control en la asignación de usuarios, lo que limita la interpretación de los resultados.

Este proyecto refuerza la importancia de una correcta planificación experimental, validación de datos y análisis estadístico riguroso en la toma de decisiones basadas en datos.
