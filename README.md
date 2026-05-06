Proyecto Power BI – README
Profesional (Proceso
Confidencial)
Proyecto Power BI – Análisis y
Visualización de Datos (Proceso
Confidencial)
📊
Aviso de confidencialidad
Este proyecto ha sido desarrollado en un entorno profesional con
información sensible. Por este motivo, no se incluyen datos reales, capturas
del informe ni archivos .pbix.
El propósito de este README es documentar el proceso de trabajo, las
decisiones técnicas y las competencias adquiridas, respetando en todo
momento la confidencialidad.
🧠Contexto
Proyecto desarrollado durante unas prácticas profesionales, orientado a la
construcción de cuadros de mando en Power BI para apoyar la toma de
decisiones en un entorno empresarial real.
El dashboard estaba dirigido a perfiles de negocio que requerían una visión clara
y actualizada de los principales indicadores del área, reduciendo la dependencia
de análisis manuales.
6/5/26, 12:54 Proyecto Power BI – README Profesional (Proceso Confidencial)
https://loop.cloud.microsoft/print/eyJwIjp7InUiOiJodHRwczovL21hcGZyZWNvcnAuc2hhcmVwb2ludC5jb20vOmZsOi9yL2NvbnRlbnRzdG9yYWdlL3g4… 1/5
🎯Objetivos
• Centralizar información procedente de distintos orígenes de datos
• Facilitar el seguimiento de indicadores clave (KPIs)
• Permitir análisis temporal y comparativo
• Mejorar la accesibilidad y comprensión de la información para usuarios no
técnicos
🗂️Fuentes de datos
Los datos procedían de sistemas corporativos internos, combinando:
• Datos transaccionales estructurados
• Ficheros auxiliares utilizados como tablas de dimensión
La carga y transformación de los datos se realizó mediante Power Query,
asegurando consistencia y calidad en el modelo final.
🔄Preparación y transformación de datos
Principales tareas realizadas:
• Limpieza de valores nulos y registros inconsistentes
• Eliminación de duplicados
• Normalización de entidades clave (clientes, productos, fechas)
• Creación de una tabla calendario personalizada para el análisis temporal
• Tipado correcto de campos y reducción de columnas innecesarias
Estas acciones permitieron optimizar el rendimiento y facilitar la creación de
métricas en DAX.
6/5/26, 12:54 Proyecto Power BI – README Profesional (Proceso Confidencial)
https://loop.cloud.microsoft/print/eyJwIjp7InUiOiJodHRwczovL21hcGZyZWNvcnAuc2hhcmVwb2ludC5jb20vOmZsOi9yL2NvbnRlbnRzdG9yYWdlL3g4… 2/5
🧩Modelo de datos
Se diseñó un modelo en estrella, compuesto por:
• Una tabla de hechos principal
• Varias tablas de dimensiones relacionadas
Criterios aplicados en el modelado:
• Relaciones 1:N claras y coherentes
• Control de la direccionalidad de los filtros
• Separación entre hechos y dimensiones
• Modelo orientado a escalabilidad y mantenimiento
📐Métricas y lógica DAX
Se desarrollaron medidas DAX orientadas a métricas de negocio, entre ellas:
• Métricas agregadas principales
• Indicadores de rentabilidad
• Comparativas temporales (interanuales y por periodos)
• KPIs para seguimiento ejecutivo
Ejemplo de medida genérica:
1 Ventas Totales = SUM(FactTabla[Importe])
2
Las medidas se diseñaron priorizando claridad, reutilización y eficiencia.
DAX
6/5/26, 12:54 Proyecto Power BI – README Profesional (Proceso Confidencial)
https://loop.cloud.microsoft/print/eyJwIjp7InUiOiJodHRwczovL21hcGZyZWNvcnAuc2hhcmVwb2ludC5jb20vOmZsOi9yL2NvbnRlbnRzdG9yYWdlL3g4… 3/5
🖥️Diseño del dashboard y experiencia de usuario
El informe se estructuró en varias páginas temáticas, incorporando:
• KPIs visibles en la parte superior
• Visualizaciones comparativas y evolutivas
• Segmentadores para filtrado dinámico
• Navegación mediante botones
El diseño estuvo orientado a un usuario no técnico, priorizando la claridad visual,
coherencia y usabilidad.
📈Impacto del proyecto
El dashboard permitió:
• Mejorar la visibilidad de los indicadores clave
• Reducir el tiempo dedicado al análisis manual
• Facilitar la toma de decisiones basada en datos
📚Aprendizajes y mejoras
Aprendizajes
• Modelado de datos en estrella en Power BI
• Uso avanzado de Power Query para la preparación de datos
• Desarrollo de medidas DAX orientadas a negocio
• Diseño de dashboards centrados en el usuario
Posibles mejoras
• Implementación de Row-Level Security (RLS)
6/5/26, 12:54 Proyecto Power BI – README Profesional (Proceso Confidencial)
https://loop.cloud.microsoft/print/eyJwIjp7InUiOiJodHRwczovL21hcGZyZWNvcnAuc2hhcmVwb2ludC5jb20vOmZsOi9yL2NvbnRlbnRzdG9yYWdlL3g4… 4/5
• Optimización adicional del rendimiento del modelo
• Automatización de los procesos de actualización
✅Competencias demostradas
• Power BI
• Modelado de datos
• DAX
• Power Query
• Análisis de negocio
• Visualización de datos
Este README forma parte de un portfolio profesional y tiene como objetivo
demostrar experiencia técnica y metodológica en proyectos de Business
Intelligence desarrollados en entornos reales.
