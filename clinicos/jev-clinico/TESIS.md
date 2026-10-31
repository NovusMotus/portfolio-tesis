# Casos sintéticos y preguntas tipadas para estudiar decisiones clínicas

**Estado:** borrador local para revisión. **Versión:** 2026-10-14-v4. **Fecha de redacción:** 2026-10-14. No publicado ni aprobado para subir.

## TL;DR

![Representación conceptual de Casos sintéticos y preguntas tipadas para estudiar decisiones clínicas.](proyecto.png)

*Ilustración conceptual generada con IA; no es una captura ni prueba de uso.*

- **Propósito:** Estudiar preguntas clínicas delimitadas mediante casos sintéticos y respuestas tipadas.
- **Aportación y enfoque:** Javier plantea la pregunta y el catálogo; la elaboración de material usa asistencia de IA.
- **Trabajo y evidencia:** README y piloto de cincuenta casos febriles inventados, atribuidos a Claude sin modelo exacto confirmado.
- **Resultados y límites:** Pendientes de revisión por especialista y no adecuados aún para evaluación o calibración. No se acredita entrenamiento ni rendimiento clínico.

## Punto de partida y pregunta de esta línea

El proyecto explora cómo representar una pregunta clínica de forma delimitada para estudiar un modelo de decisión. Una respuesta en texto libre puede dificultar identificar qué variable se ha evaluado y qué incertidumbre permanece. La cuestión de investigación es si un catálogo de preguntas y etiquetas permite organizar casos y revisar decisiones de manera trazable, sin considerar la representación como capacidad clínica ya demostrada.

## Origen y propósito

La documentación disponible permite describir esta línea, pero no reconstruye de forma confirmada qué observación, publicación o experiencia la inició. El punto de partida puede ser una idea, una hipótesis, una aplicación o una práctica con herramientas; no se presupone que exista un problema que resolver. Si se recupera una referencia de origen, se distinguirán lo que plantea esa fuente y la adaptación realizada por Javier.

## Enfoque del proyecto y propuesta de esta versión

El diseño descrito usa preguntas tipadas, respuestas delimitadas y casos sintéticos con justificación de sus etiquetas. Javier plantea el problema y el catálogo; las herramientas de IA apoyan la elaboración de material. Separar estado de entrada, respuesta esperada y explicación de la etiqueta puede facilitar revisión. La elección de categorías y la distribución de casos son parte de la hipótesis de diseño y deben ser examinadas por especialistas.

## Desarrollo y evidencia disponible

El README documenta un piloto de cincuenta casos inventados de síndrome febril generado con Claude en septiembre. Los declara pendientes de revisión por un internista y no adecuados para evaluar o calibrar en su estado descrito. Existen datos y documentación de catálogo. No se infiere entrenamiento realizado, rendimiento clínico o validación externa a partir de esos archivos. El modelo exacto que generó los casos no consta en la atribución leída.

## Preguntas y límites que permanecen abiertos

Los casos generados pueden incorporar pistas que revelen la respuesta, etiquetas discutibles o distribuciones poco representativas. También pueden repetir patrones de la herramienta que los creó. Un conjunto externo sintético necesita distinguirse de datos producidos por el proyecto y conservar sus condiciones de uso. La existencia de probabilidades no demuestra calibración. No se publica información de pacientes ni se propone usar el material para decisiones asistenciales en esta fase.

## Cómo podría comprobarse

La siguiente fase propuesta es una revisión independiente de plausibilidad, pistas, etiquetas y cobertura del catálogo, con motivos de modificación documentados. Después habría que diseñar particiones de datos y tareas que no compartan ejemplos o soluciones. La evaluación tendría que separar preguntas del catálogo, casos fuera de catálogo y situaciones con información insuficiente. Cualquier resultado se atribuiría al conjunto y configuración utilizados, sin extrapolación clínica automática.

## Una pregunta delimitada hace visible qué se intenta decidir

El diseño descrito organiza casos mediante preguntas con un tipo de respuesta definido. Una categoría, una etiqueta de catálogo y una indicación de información insuficiente no representan la misma decisión. Separarlas permite precisar qué entrada necesita cada pregunta y qué comparación se pretende realizar. La propuesta de Javier utiliza esa estructura para estudiar un modelo; la estructura no acredita que las etiquetas sean clínicamente válidas o que el modelo pueda responderlas con seguridad.

Como ejemplo editorial sin contenido asistencial, un caso ficticio podría contener varios campos y una pregunta sobre si falta un dato definido en el propio ejercicio. La referencia de esa tarea sería conocida por construcción. Otra pregunta podría pedir elegir entre etiquetas inventadas y permitir una opción fuera del catálogo. Esa muestra probaría representación y tratamiento de entradas, sin utilizar su resultado para orientar atención. Las preguntas clínicas del material histórico requieren revisión especializada antes de convertirse en una tarea de evaluación pertinente.

## Un caso sintético necesita revisión de contenido y procedencia

El README declara que los casos piloto fueron generados y que sus etiquetas necesitan revisión. Un caso inventado evita trasladar directamente una historia de un paciente, pero puede contener relaciones poco plausibles, patrones repetidos o pistas que facilitan identificar la respuesta. La generación y la revisión son aportaciones distintas. El registro debe conservar quién propuso el caso, qué fuente orientó su construcción y qué cambió quien revisa.

El asistente propone una revisión que observe información incluida, datos ausentes, alternativas defendibles y pistas no previstas. Si una etiqueta admite desacuerdo, el conjunto tendría que mostrarlo o reformular la tarea. El caso no pasaría a ser referencia por coincidir con otra respuesta del mismo modelo generador. Las justificaciones servirían para revisar el material y no para mostrar al sistema la solución cuando se evalúa. Esta redacción describe cómo preparar esa comparación; no completa una revisión clínica de los casos ni declara que el conjunto ya sirva para calibrar.

## Cobertura del catálogo y distribución de ejemplos

El material documenta categorías y entidades con una cobertura desigual. Un listado amplio de posibilidades no significa que cada una tenga ejemplos suficientes o representativos. Las versiones de catálogo y de casos deberían relacionarse: una etiqueta nueva puede dejar preguntas anteriores sin una correspondencia clara. También conviene conservar las situaciones que quedan fuera del catálogo en lugar de forzar una respuesta existente.

Como método propuesto, una tabla podría contar ejemplos por tarea, etiqueta y condición de información ausente, con estados de revisión separados. Esa tabla permitiría localizar huecos antes de interpretar una puntuación global. No se deduciría una distribución clínica real de frecuencias de un conjunto inventado. Un material sintético externo necesita sus fuentes y condiciones de uso, y se distingue del producido por Javier. Las tablas agregadas mencionadas en el proyecto tienen límites propios: su existencia no transforma todos los ejemplos generados en una muestra clínica representativa o autorizada para uso asistencial.

## Probabilidades y evaluación no son intercambiables

Una salida probabilística permite expresar un valor del sistema, pero interpretar ese valor necesita una tarea y un conjunto de contraste definidos. La exactitud de una etiqueta y la correspondencia entre probabilidades y resultados son preguntas diferentes. Una puntuación alta sobre casos con pistas repetidas podría describir el aprovechamiento de esas pistas, no la capacidad que se quería estudiar. El dossier conserva esa diferencia sin proponer umbrales para decisiones sobre pacientes.

El asistente plantea separar materiales de elaboración y de contraste, observar ejemplos duplicados y registrar qué información recibe el sistema. La evaluación incluiría casos con información insuficiente y opciones fuera del catálogo cuando formen parte de la tarea definida. Una abstención necesita su propia interpretación: puede expresar el límite previsto o un fallo de representación. El resultado se atribuiría al conjunto, pregunta, versión y configuración usados. Cambiar un catálogo o un generador requiere una comparación nueva; no hereda automáticamente la evidencia de una versión anterior.

## Qué se puede mostrar como investigación de un mecanismo

El portfolio puede presentar la relación entre estado de entrada, preguntas, etiquetas y revisión, con ejemplos no clínicos o materiales que hayan pasado sus comprobaciones pertinentes. También puede mostrar un hueco detectado y la decisión de no utilizar todavía un conjunto. Eso hace visible el proceso de investigación sin necesidad de atribuir entrenamiento, rendimiento médico o integración a partir de archivos de datos.

Javier aporta el interés y las preguntas del proyecto; los protocolos de contraste adicionales de esta ficha son propuestas del asistente. Los casos históricos tienen una atribución de herramienta, pero el modelo exacto no se reconstruye por usar uno diferente en la redacción actual. El siguiente avance documental sería precisar versiones de catálogo y estados de revisión, antes de diseñar una evaluación. Cualquier prueba clínica requiere sus datos, objetivos, permisos y revisión especializada. Esta preparación no genera diagnósticos, no usa historias reales y no convierte una propuesta tipada en un modelo asistencial validado.

## Procedencia de las posiciones

Diseño y estado declarados en el proyecto; protocolo de revisión propuesto por esta síntesis. El texto es una síntesis asistida por IA y requiere la revisión de Javier antes de atribuirle nuevas formulaciones. Se describen procesos y condiciones, sin juicios de valor ni atribuciones de intenciones.

## Fechas, versiones y cambios

Primera referencia temporal utilizada: 2026-09-23. Generación declarada en README; no prueba de inicio de la idea.

Se desarrolla el mecanismo específico, sus aplicaciones y ejemplos de comprobación. Las nuevas propuestas del asistente se mantienen diferenciadas de las decisiones de Javier. Se registra el modelo de este turno con su evidencia, sin cambiar las atribuciones anteriores. No se incorporan resultados de pruebas nuevas. La edición no modifica las fuentes originales ni sus fechas.

## Herramientas y modelos

Imagen conceptual vigente, añadida el 2026-10-14: preparación e incorporación con Codex/OpenAI gpt-6.1-sol (metadatos del turno); generación y correcciones con image_gen de OpenAI, cuyo modelo exacto no consta. Sustituye el esquema anterior, conservado en el historial. Revisión independiente: gpt-6-astra.

Apoyo visual añadido el 2026-10-14: esquema original elaborado con Codex/OpenAI gpt-6.1-sol (metadatos del turno), Python 3.12.14 y ReportLab 4.4.9, exportado como SVG. Explica la idea del TL;DR; no representa una prueba o resultado nuevo. Revisión independiente de esta edición: gpt-6-astra; alcance documentado por separado. Compatibilidad tipográfica del SVG corregida en esta edición.

La redacción de esta versión utiliza Codex/OpenAI con el modelo gpt-6.1-sol. Su identificación consta en los metadatos del turno utilizado para esta edición; las atribuciones de versiones anteriores se conservan con su evidencia original. Se usaron Python para organización y comprobación local, y herramientas de lectura y edición de archivos. La revisión editorial independiente se encargó a un agente separado con gpt-6-astra; su alcance y resultado se registran fuera del dossier, sin equivaler a validación integral del proyecto. No se han configurado integraciones o actualización continua.

### Atribuciones históricas documentadas

- Claude: no_confirmado. README atribuye generación de casos a Claude en septiembre sin identificador exacto.

## Fuentes y alcance de lectura

La base es la documentación interna identificada en el registro privado de fuentes de esta preparación. Se ha leído mediante extracción local y se han examinado fuentes y pasajes seleccionados; no es una auditoría sustantiva de todo el corpus. Las referencias externas de los antecedentes requieren verificación pertinente antes de reutilizar afirmaciones como hechos actuales. No se incluyen rutas privadas, documentos sensibles, conversaciones completas o material de terceros en este dossier.
