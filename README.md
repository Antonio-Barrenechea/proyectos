Análisis de embudo y retención para MercadoLibre

Como Analista de Producto en el equipo de Crecimiento y Retención de MercadoLibre, se me asignó la tarea de diagnosticar la salud del proceso de compra. El objetivo principal fue identificar en qué etapas los usuarios abandonan la plataforma y medir la fidelidad de los mismos a través del tiempo (análisis de cohortes).

Este proyecto simula un entorno real de e-commerce donde la optimización de un 1% en el embudo puede representar millones en ingresos.

🎯 Objetivos

Mapear el Customer Journey: Construir un embudo multietapa desde la visualización del producto hasta la confirmación de pago.

Detectar Puntos de Fuga: Calcular tasas de conversión (CR) y drop-off entre cada paso.

Análisis de Cohortes: Evaluar la retención de usuarios para entender el comportamiento recurrente.

Propuestas Accionables: Simular escenarios de mejora basados en los hallazgos de SQL.

🛠️ Stack Tecnológico
SQL (PostgreSQL): Uso de CTEs (Common Table Expressions), funciones agregadas y cálculos de fechas.

Dataset: mercadolibre_funnel (Eventos de usuario).

🔍 Mi Análisis (Proceso)
1. Construcción del Embudo (Funnel)
Utilicé CTEs para organizar las etapas de forma secuencial: view_item -> add_to_cart -> checkout -> payment_confirmation. Esto permitió una estructura de consulta limpia y escalable.

2. Análisis de Cohortes
Segmenté a los usuarios por su mes de adquisición para observar cuántos regresaban en los meses posteriores (Month 0, Month 1, etc.).

📊 Hallazgos Principales (Material Visual)

<p align="center">
  <img src="[img/tu_imagen.png](https://github.com/Antonio-Barrenechea/proyectos/embudo_general.png)" width="600" title="Embudo General">
</p>

