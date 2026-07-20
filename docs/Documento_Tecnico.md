# Actividad 8
## Monitoreo y Gobernanza Operativa de un Modelo de Machine Learning

### Autor
Gibran Martinez

### Materia
Gestión de Proyectos de Inteligencia Artificial

---

# Introducción

Los modelos de machine learning al estar desplegados en entornos de producción presentan ciertos criterios que deben ser monitoreados constantemente para garantizar su funcionamiento correcto. Tener un modelo correctamente monitoreado nos garantiza su disponibilidad y confiabilidad mientras se está ejecutando.
Para el desarrollo de esta actividad se utilizará un modelo de clasificación de aprobación de créditos implementado mediante Random Forest, simulando un escenario empresarial donde una institución financiera evalúa solicitudes de clientes en tiempo real. Este caso de uso fue seleccionado debido a que representa una aplicación común de Machine Learning en producción y permite evaluar tanto métricas de negocio como indicadores técnicos asociados a la operación del servicio.
Como herramienta principal de monitoreo se utilizara MLflow, una plataforma ampliamente utilizada para la gestión del ciclo de vida de modelos de Machine Learning. MLflow permite registrar métricas, parámetros, versiones de modelos y resultados de experimentación, facilitando el seguimiento del rendimiento del modelo durante su operación. Adicionalmente, la herramienta proporciona capacidades para comparar versiones, analizar tendencias de desempeño y generar evidencia de monitoreo que puede integrarse con dashboards y sistemas de alertamiento.
Para simular un ambiente de producción, se definen las métricas operativas, registros, tazas de ejecución y SLO. a partir de estos parámetros se diseñarán las alertas y medidas preventivas que nos permitan detectar anomalías o errores durante el despliegue del modelo, así mismo esta estrategia puede ayudarnos a minimizar el ruido y priorizar incidentes según el impacto. También se pueden tomar medidas de acción de respuesta automatizada para distintos escenarios.
Por último se realizan simulaciones controladas de incidentes, con la finalidad de valorar si los procedimientos de respuesta son efectivos según las acciones correctivas propuestas. Esto permitirá demostrar la aplicación de prácticas modernas de observabilidad y gobernanza operativa en sistemas basados en inteligencia artificial, garantizando la continuidad y calidad del servicio ofrecido.

---

# 1. Definición de Indicadores

(Pegaremos aquí métricas, logs y trazas)

---
