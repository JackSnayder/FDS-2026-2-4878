# Creación de conocimiento a partir de datos de tendencias de videos de YouTube (India)

## Objetivo del proyecto
Analizar los registros de videos en tendencia de YouTube en la India (14 de noviembre de 2017 al 14 de junio de 2018) bajo la metodología CRISP-DM para apoyar decisiones de marketing digital sobre categorías, canales, ventana de publicación y estimación de alcance (`log_views`).

## Integrantes
- Noelia Paquiyauri Tumbay (U20241F592) — Coordinadora del proyecto
- Edson Jair Ramos Vásquez (U20241F442) — Business Analyst
- Tony Montesinos Condori (U20241F805) — Data Engineer
- Addy Valentina Pinedo Saldaña (U20241D259) — Data Analyst
- Jack Snayder Lima Huamani (U20241G263) — Data Scientist

## Breve descripción del conjunto de datos
Se emplearon los archivos `INvideos_Inicial.csv` y `IN_category_id.json` (versión modificada con variables geográficas simuladas), partiendo de 38,533 filas crudas hasta obtener 32,706 registros válidos (16,521 videos únicos) tras la limpieza y construcción de variables.

- 📄 **Informe completo del proyecto:** [Ver informe PDF (`upc-2026-02-4878-g1-tf.pdf`)](./upc-2026-02-4878-g1-tf.pdf)

## Conclusiones
- La tendencia se concentra en pocas categorías (Entretenimiento, Noticias y política, y Música), pero Música y Comedia destacan por interacción por video y permanencia.
- Ciencia y tecnología, Educación y Comedia muestran mayor conversación relativa o recepción favorable.
- La mayoría de videos entra a tendencia en 0–1 días y permanece pocos días, por lo que conviene activar campañas en las primeras 24–48 horas.
- El modelo de regresión lineal múltiple con términos cuadráticos mejora la línea base en escala logarítmica y sirve para estimar órdenes de magnitud aproximados, no cifras exactas.

## Licencia de uso
Este proyecto se distribuye bajo la [Licencia MIT](./LICENSE).
