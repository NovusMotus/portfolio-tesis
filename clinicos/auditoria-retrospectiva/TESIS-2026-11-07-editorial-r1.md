# Organización de evidencia para análisis retrospectivo de documentación clínica

**Edición editorial:** 2026-11-07-editorial-r1. **Elaborada en UTC:** 2026-11-07T19:50:09.616232Z.

**Estado histórico declarado del contenido:** borrador local para revisión. **Versión histórica:** 2026-10-14-v4. **Fecha de redacción histórica declarada:** 2026-10-14. La fuente histórica estaba disponible públicamente en el commit consultado; su publicación no valida el contenido.

**Alcance de esta edición:** corrección administrativa del estado documental. El desarrollo y las atribuciones que siguen se reproducen de la [versión histórica](https://github.com/NovusMotus/portfolio-tesis/blob/2cd2acbd44ae01f98481e383af2368bce2973b43/clinicos/auditoria-retrospectiva/TESIS.md); sus expresiones «esta versión» se refieren a aquella edición. Se conservan las fechas declaradas, los límites y las propuestas, sin añadir logros ni reconstruir el inicio de la idea. La disponibilidad de esta edición se comprueba en el repositorio y en la PR que la incorpore.

**Aporte editorial:** Codex desktop / OpenAI / gpt-6.1-sol; transformación con Python 3.12.14. [Registro de esta versión](VERSION-2026-11-07-editorial-r1.json) · [Revisión editorial fechada](../../REVISION_EDITORIAL_2026-11-07-r1.json).

## TL;DR

![Representación conceptual de Organización de evidencia para análisis retrospectivo de documentación clínica.](proyecto.png)

*Ilustración conceptual generada con IA; no es una captura ni prueba de uso.*

- **Propósito:** Organizar evidencia documental para un análisis clínico retrospectivo.
- **Aportación y enfoque:** El diseño separa análisis, documentación y revisión. El material no permite atribuir todas las decisiones o descartes a Javier.
- **Trabajo y evidencia:** Prompts y definiciones de funciones, leídos sin ejecutarlos en expedientes.
- **Resultados y límites:** No es una auditoría realizada ni un servicio operativo. Afirmaciones de error cero o clasificación regulatoria no están validadas; falta comprobar trazabilidad y límites de interpretación.

## Punto de partida y pregunta de esta línea

El material explora cómo organizar un análisis retrospectivo de documentos clínicos, con distinción entre lo que consta en un registro y lo que podría inferirse. La cuestión es construir un recorrido de lectura y contraste que permita localizar fuentes, lagunas y contradicciones. El dossier no identifica casos reales ni formula conclusiones sobre responsabilidad profesional o calidad asistencial de personas concretas.

## Origen y propósito

La documentación disponible permite describir esta línea, pero no reconstruye de forma confirmada qué observación, publicación o experiencia la inició. El punto de partida puede ser una idea, una hipótesis, una aplicación o una práctica con herramientas; no se presupone que exista un problema que resolver. Si se recupera una referencia de origen, se distinguirán lo que plantea esa fuente y la adaptación realizada por Javier.

## Enfoque del proyecto y propuesta de esta versión

La variante MVP distribuye tareas de análisis, documentación, síntesis, discusión y revisión entre nodos. El enfoque consiste en delimitar la pregunta y mantener la relación de cada afirmación con su evidencia. Las instrucciones del sistema distinguen observación documental de diagnóstico o consejo asistencial. Esa distinción es un requisito propuesto: su presencia en un prompt no acredita que un sistema la respete en todas sus respuestas.

## Desarrollo y evidencia disponible

La carpeta contiene un conjunto de prompts y definiciones de funciones. Es material de diseño de un flujo. Las expresiones de error cero o de clasificación regulatoria que aparecen en él son declaraciones del texto y no resultados de validación o decisiones de una autoridad. No se ha ejecutado este flujo en expedientes para redactar la tesis. Tampoco se presenta como servicio médico legal operativo ni auditoría realizada.

## Preguntas y límites que permanecen abiertos

La suficiencia de un documento, la corrección de su interpretación y una conclusión jurídica pertenecen a niveles diferentes. Un registro incompleto puede explicar que algo no conste sin demostrar que no ocurrió. Los agentes pueden compartir errores o supuestos. La confidencialidad, los permisos de acceso y la verificación especializada no se sustituyen por una instrucción interna. La exposición pública conserva solo la metodología propuesta y los límites del alcance.

## Cómo podría comprobarse

Se propone revisar primero expedientes totalmente ficticios con hechos y lagunas conocidos, para identificar afirmaciones que exceden lo documentado. Las salidas deben registrar fuente, incertidumbre y discrepancias entre revisores. La evaluación no debería usar conclusiones generadas por el propio flujo como respuesta de referencia. Una aplicación a documentación real exigiría autorización y revisión profesional del procedimiento; no está incluida en esta preparación.

## Lo que consta y lo que ocurrió no son equivalentes

El flujo se plantea para examinar documentos retrospectivamente y relacionar afirmaciones con sus fuentes. La pregunta inicial necesita delimitar qué se busca en el registro y qué otras evidencias podrían ser necesarias. Un documento puede no contener una actuación aunque esta haya ocurrido; también puede consignar una intención sin acreditar su ejecución. El análisis debería mantener esos estados separados, evitando convertir la ausencia documental en una conclusión sobre conducta profesional.

Un ejemplo propuesto por el asistente utilizaría una secuencia completamente ficticia con una solicitud, una nota posterior y un resultado registrado sin un vínculo explícito. La tarea sería identificar qué relaciones están documentadas y qué preguntas permanecen abiertas. No se completarían los huecos con una narración plausible. La muestra serviría para observar lectura y procedencia, sin evaluar la atención de una persona ni formular una conclusión sobre responsabilidad. El dossier no necesita reproducir expedientes reales para explicar ese mecanismo.

## Ordenar el tiempo sin conocer de antemano el desenlace

Una cronología puede incluir momento del hecho, momento de registro y momento de revisión. El análisis retrospectivo debe describir qué información estaba disponible en cada punto y qué se conoció después. Si la salida utiliza un dato posterior para interpretar una decisión anterior, necesita hacer visible ese cambio de perspectiva. La existencia de un desenlace no demuestra por sí sola la calidad de todas las actuaciones previas.

Como ensayo editorial, una versión del caso ficticio ocultaría el resultado final y otra lo mostraría. Se compararía qué afirmaciones cambian y qué fuentes se añaden. El objetivo sería detectar inferencias que dependen de información no disponible en el momento analizado. Esa comprobación no sustituye un criterio clínico o jurídico, ni determina un estándar de actuación. Ayuda a formular una pregunta de método: si el sistema conserva el tiempo de las evidencias o reescribe el recorrido como si todos sus elementos fueran conocidos desde el inicio.

## Cada documento aporta una perspectiva y un alcance

El prompt histórico establece prioridades entre clases de documentos y utiliza expresiones de fiabilidad y certeza. La ficha no adopta esa jerarquía como regla universal: el valor de un pasaje depende de qué pregunta responde, cómo se produjo y con qué otras evidencias se relaciona. Una nota frecuente puede añadir detalle y también contener una interpretación; un resumen puede seleccionar información y seguir aportando contexto pertinente. Las categorías no permiten decidir de antemano qué autor tiene razón.

El asistente propone conservar las afirmaciones en paralelo cuando discrepan, con ubicación y fecha de cada pasaje. La revisión formularía la discrepancia y qué dato podría aclararla. No se resolvería por cargo, longitud o apariencia de precisión. Si se cita una norma o un protocolo externo, habría que comprobar versión, ámbito y pertinencia antes de utilizarlo en una conclusión. Las declaraciones de clasificación regulatoria del material de diseño permanecen antecedentes no acreditados; una instrucción interna no constituye una decisión de una autoridad.

## Analizar, contrastar y concluir requieren controles distintos

El diseño distribuye extracción, discusión y síntesis entre funciones. La extracción debería permitir volver al pasaje; la comparación debería identificar relaciones y límites; la conclusión necesitaría el criterio y revisión apropiados para su alcance. Un agente puede resumir correctamente y otro incorporar una afirmación no sustentada al sintetizar. Separar tareas ayuda a observar dónde aparece ese cambio, sin garantizar independencia entre modelos que comparten premisas.

Una prueba propuesta podría introducir dos documentos ficticios que utilizan fechas incompatibles y un tercero que no resuelve la diferencia. El recorrido debería conservar la contradicción hasta disponer de una base para resolverla. Otra variante incluiría una pregunta que el expediente no permite contestar. El sistema registraría ese límite en lugar de producir un veredicto para completar la plantilla. Los revisores utilizarían un conjunto de hechos definido fuera del flujo como referencia de la prueba. La propia salida generada no serviría como medida de su acierto.

## El alcance público es explicar una metodología propuesta

El portfolio puede mostrar una cronología inventada, una tabla de fuentes y una discrepancia conservada. Esos recursos describirían cómo se intenta organizar una lectura retrospectiva, sin atribuir una auditoría realizada o un servicio operativo. La etiqueta de error cero del material histórico expresa una exigencia del prompt, no un resultado que se pueda prometer. Los datos de pacientes, organizaciones o profesionales no forman parte de esta explicación.

El siguiente desarrollo propuesto es delimitar tareas que puedan comprobarse con material ficticio antes de discutir aplicaciones a documentación real. Acceso, confidencialidad, revisión especializada y criterios de uso necesitarían condiciones propias. Las conclusiones clínicas y jurídicas no se presentan como una función ya resuelta del flujo. Javier revisará qué parte del diseño conserva y cuáles de los ejemplos nuevos acepta. La ficha registra esa diferencia y las herramientas de cada edición, evitando trasladar al pasado los modelos utilizados ahora o publicar instrucciones internas como si acreditaran resultados.

## Procedencia de las posiciones

Resumen de una variante conceptual de workflow; comprobaciones propuestas por el asistente. El texto es una síntesis asistida por IA y requiere la revisión de Javier antes de atribuirle nuevas formulaciones. Se describen procesos y condiciones, sin juicios de valor ni atribuciones de intenciones.

## Fechas, versiones y cambios

Primera referencia temporal utilizada: no confirmada. El inicio real y las fechas de cada aportación histórica no están reconstruidos. La fecha del archivo no sustituye la fecha de la idea.

Se desarrolla el mecanismo específico, sus aplicaciones y ejemplos de comprobación. Las nuevas propuestas del asistente se mantienen diferenciadas de las decisiones de Javier. Se registra el modelo de este turno con su evidencia, sin cambiar las atribuciones anteriores. No se incorporan resultados de pruebas nuevas. La edición no modifica las fuentes originales ni sus fechas.

## Herramientas y modelos

Imagen conceptual vigente, añadida el 2026-10-14: preparación e incorporación con Codex/OpenAI gpt-6.1-sol (metadatos del turno); generación y correcciones con image_gen de OpenAI, cuyo modelo exacto no consta. Sustituye el esquema anterior, conservado en el historial. Revisión independiente: gpt-6-astra.

Apoyo visual añadido el 2026-10-14: esquema original elaborado con Codex/OpenAI gpt-6.1-sol (metadatos del turno), Python 3.12.14 y ReportLab 4.4.9, exportado como SVG. Explica la idea del TL;DR; no representa una prueba o resultado nuevo. Revisión independiente de esta edición: gpt-6-astra; alcance documentado por separado. Compatibilidad tipográfica del SVG corregida en esta edición.

La redacción de esta versión utiliza Codex/OpenAI con el modelo gpt-6.1-sol. Su identificación consta en los metadatos del turno utilizado para esta edición; las atribuciones de versiones anteriores se conservan con su evidencia original. Se usaron Python para organización y comprobación local, y herramientas de lectura y edición de archivos. La revisión editorial independiente se encargó a un agente separado con gpt-6-astra; su alcance y resultado se registran fuera del dossier, sin equivaler a validación integral del proyecto. No se han configurado integraciones o actualización continua.

### Atribuciones históricas documentadas

No hay una atribución histórica exacta reconstruida para esta ficha. Las menciones a herramientas en las fuentes no se consideran prueba de uso.

## Fuentes y alcance de lectura

La base es la documentación interna identificada en el registro privado de fuentes de esta preparación. Se ha leído mediante extracción local y se han examinado fuentes y pasajes seleccionados; no es una auditoría sustantiva de todo el corpus. Las referencias externas de los antecedentes requieren verificación pertinente antes de reutilizar afirmaciones como hechos actuales. No se incluyen rutas privadas, documentos sensibles, conversaciones completas o material de terceros en este dossier.
