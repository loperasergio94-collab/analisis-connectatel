# 📱 Análisis de clientes de ConnectaTel

Proyecto de análisis de datos de una empresa de telecomunicaciones en México y Colombia. Analicé cómo usan los clientes sus llamadas y mensajes para encontrar patrones, detectar outliers y crear segmentos que ayuden a mejorar los planes.

## Datos
- `plans.csv`: planes de la empresa
- `users_latam.csv`: 4000 clientes
- `usage.csv`: 40000 registros de llamadas y mensajes

## Qué hice
Limpieza de datos (nulos, sentinels y fechas imposibles), estadísticas descriptivas, detección de outliers con boxplots e IQR, y segmentación de clientes por edad y nivel de uso.

## Hallazgo principal
Los usuarios Premium y Basico usan el servicio casi igual, lo que sugiere que muchos clientes no tienen el plan que corresponde a su consumo. Recomiendo ofrecer Premium a los usuarios Basico de alto uso y revisar los beneficios del plan Premium.

## Herramientas
Python · pandas · seaborn · matplotlib · Jupyter Notebook
