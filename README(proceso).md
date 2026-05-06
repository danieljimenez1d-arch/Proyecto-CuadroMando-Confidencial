
📌 Nota  
 Este portfolio se encuentra en evolución y se irá ampliando progresivamente.  
 El objetivo actual es documentar el proceso y las decisiones técnicas del proyecto.

📊 Power BI Portfolio
Este repositorio recoge un proyecto de Business Intelligence desarrollado en Power BI, documentado con un enfoque profesional y orientado a proceso. El objetivo de este portfolio es explicar cómo se abordó el proyecto, qué decisiones se tomaron y qué conocimientos se aplicaron a lo largo de su desarrollo.
El proyecto está basado en un entorno real, pero por motivos de confidencialidad no se incluyen datos, capturas del informe ni archivos .pbix. La documentación se centra en el método de trabajo y el razonamiento técnico, no en los datos en sí.


🧠 Contexto del proyecto
El proyecto consistió en el desarrollo de un cuadro de mando en Power BI orientado al análisis de información empresarial y al apoyo a la toma de decisiones.
La información procedía de distintos sistemas, por lo que fue necesario realizar un proceso completo de integración, transformación y modelado antes de poder construir las visualizaciones finales. El dashboard estaba dirigido a usuarios de negocio que necesitaban una visión clara y estructurada de los indicadores clave.


🎯 Objetivo
El objetivo principal del proyecto fue construir un dashboard que permitiera:

Centralizar la información en un único informe

Visualizar los principales indicadores clave (KPIs)
Analizar la evolución de los datos en el tiempo
Reducir la dependencia de informes manuales en Excel


🗂️ Datos utilizados
Los datos procedían de fuentes internas, como tablas estructuradas y ficheros auxiliares. Todo el proceso de carga y transformación se realizó mediante Power Query.
Aunque no se muestran los datos reales, el trabajo incluyó tareas habituales en proyectos de BI, como:

Limpieza de valores nulos
Eliminación de duplicados
Ajuste de tipos de datos
Preparación de dimensiones (fechas, productos, clientes, etc.)


🔄 Preparación y modelo de datos
Una parte clave del proyecto fue el modelado de datos. Se diseñó un modelo en estrella, con una tabla de hechos principal y varias tablas de dimensiones, lo que facilita el análisis y mejora el rendimiento del informe.
Además, se creó una tabla calendario personalizada para permitir el análisis temporal y las comparaciones entre periodos.


📐 Métricas y DAX
Se desarrollaron distintas medidas utilizando DAX, enfocadas a medir aspectos relevantes del negocio, como:

Métricas agregadas principales
Indicadores de rentabilidad
Comparativas entre periodos
Ejemplo de una medida utilizada:

Ventas Totales = SUM(FactTabla[Importe])


Este proyecto permitió consolidar el uso de DAX y comprender mejor la importancia del contexto de evaluación en Power BI.


📊 Diseño del dashboard
El dashboard se diseñó pensando en usuarios no técnicos, priorizando la claridad y facilidad de uso. El informe incluía:

KPIs visibles de un vistazo
Gráficos para el análisis de tendencias
Segmentadores para filtrar la información
Navegación sencilla entre páginas


📈 Resultados y aprendizajes
El proyecto permitió aplicar de forma práctica conocimientos de visualización de datos, modelado y análisis, así como comprender cómo se utilizan los dashboards en un entorno profesional real.
A nivel técnico, se reforzaron competencias en:

Power BI
Power Query
DAX
Diseño de cuadros de mando
Enfoque analítico orientado a negocio


🚀 Posibles mejoras
Como líneas de mejora futuras, el proyecto podría ampliarse con:

Implementación de seguridad a nivel de filas (RLS)
Automatización de procesos de actualización
Incorporación de nuevos indicadores según las necesidades del negocio


📌 Este README forma parte de un portfolio profesional y tiene como objetivo documentar el proceso y las decisiones técnicas de un proyecto de Business Intelligence desarrollado con Power BI.
