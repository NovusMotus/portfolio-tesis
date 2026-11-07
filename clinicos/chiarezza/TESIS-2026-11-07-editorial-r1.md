# Chiarezza y la comprensión de información clínica

**Edición editorial:** 2026-11-07-editorial-r1. **Elaborada en UTC:** 2026-11-07T19:50:09.616232Z.

**Estado histórico declarado del contenido:** borrador local para revisión. **Versión histórica:** 2026-10-14-v4. **Fecha de redacción histórica declarada:** 2026-10-14. La fuente histórica estaba disponible públicamente en el commit consultado; su publicación no valida el contenido.

**Alcance de esta edición:** corrección administrativa del estado documental. El desarrollo y las atribuciones que siguen se reproducen de la [versión histórica](https://github.com/NovusMotus/portfolio-tesis/blob/2cd2acbd44ae01f98481e383af2368bce2973b43/clinicos/chiarezza/TESIS.md); sus expresiones «esta versión» se refieren a aquella edición. Se conservan las fechas declaradas, los límites y las propuestas, sin añadir logros ni reconstruir el inicio de la idea. La disponibilidad de esta edición se comprueba en el repositorio y en la PR que la incorpore.

**Aporte editorial:** Codex desktop / OpenAI / gpt-6.1-sol; transformación con Python 3.12.14. [Registro de esta versión](VERSION-2026-11-07-editorial-r1.json) · [Revisión editorial fechada](../../REVISION_EDITORIAL_2026-11-07-r1.json).

## TL;DR

![Representación conceptual de Chiarezza y la comprensión de información clínica.](proyecto.png)

*Ilustración conceptual generada con IA; no es una captura ni prueba de uso.*

- **Propósito:** Ayudar a pacientes a comprender un informe conservando su significado e incertidumbre.
- **Aportación y enfoque:** Javier define el propósito y los límites: explicar el contenido, sin añadir interpretaciones clínicas; desarrollo asistido por IA.
- **Trabajo y evidencia:** Prototipo y registro de pruebas con tres informes inventados y una fotografía simulada.
- **Resultados y límites:** Se observaron errores semánticos que el filtro no detectó. Falta evaluar fidelidad, comprensión y seguridad; no hay validación con pacientes.

## Punto de partida y pregunta de esta línea

El proyecto aborda la distancia entre la información escrita en un informe clínico y lo que una persona entiende al leerlo. El vocabulario, la estructura y el grado de detalle pueden dificultar identificar qué se ha descrito y qué instrucciones ya figuran en el documento. La cuestión planteada es cómo facilitar esa comprensión manteniendo el significado, el grado de certeza y los límites de la información original. No se atribuye esta dificultad a la actuación o intención de profesionales concretos.

## Origen y propósito

La documentación disponible permite describir esta línea, pero no reconstruye de forma confirmada qué observación, publicación o experiencia la inició. El punto de partida puede ser una idea, una hipótesis, una aplicación o una práctica con herramientas; no se presupone que exista un problema que resolver. Si se recupera una referencia de origen, se distinguirán lo que plantea esa fuente y la adaptación realizada por Javier.

## Enfoque del proyecto y propuesta de esta versión

El enfoque documentado consiste en adaptar la forma de presentar el contenido: lenguaje comprensible, explicaciones de términos y formatos de lectura o audio. La adaptación debe conservar lo expresado por el informe. Javier aporta la definición del problema y los límites del comportamiento esperado; la construcción se apoya en herramientas de IA. El proyecto establece una separación entre explicar un término y formular una interpretación clínica nueva. Esa separación tiene que observarse en las salidas y no solo en las instrucciones al modelo.

## Desarrollo y evidencia disponible

Hay un prototipo, documentación de arquitectura, decisiones y una preparación de demostración. Un registro de septiembre describe tres informes inventados y una fotografía simulada. Es una observación limitada del comportamiento del sistema, no una evaluación clínica ni una prueba con pacientes. El mismo registro documenta errores semánticos que no detectó el filtro de salida. Ese resultado sirve para concretar qué debe medirse y corregirse; no demuestra que el producto preserve siempre la fidelidad del informe.

## Preguntas y límites que permanecen abiertos

La comprensión del texto, su fidelidad y su seguridad son criterios distintos. Una salida puede resultar más legible y a la vez omitir una condición o cambiar una afirmación. La privacidad exige revisar todo el recorrido del dato y los registros conservados. La existencia de documentación de seguridad o de un corpus anonimizado no acredita por sí misma implementación completa, autorización institucional o permisos de redistribución. El código y las memorias originales se mantienen privados por decisión del usuario.

## Cómo podría comprobarse

La siguiente comprobación propuesta es una batería de informes sintéticos con casos de negación, incertidumbre, pautas y términos ambiguos. Para cada salida habría que registrar omisiones, añadidos y cambios de significado, con comparación independiente del original. La utilidad para lectores y la adecuación clínica requerirían evaluaciones distintas y autorizadas. Las correcciones y fallos deben quedar fechados, indicando el modelo que produjo cada salida y quién la revisó.

## Conservar el significado al cambiar la forma de explicarlo

El interés de Javier es que una persona pueda leer una explicación de su informe sin recibir una conclusión clínica distinta. El diseño necesita conservar lo que el documento afirma, lo que deja incierto y las condiciones que acompañan a cada expresión. Explicar una palabra puede facilitar la lectura; clasificar un resultado como favorable, normal o preocupante añade una interpretación. La separación depende del contenido producido, además de las instrucciones dadas al modelo.

Un ejemplo ficticio permite observar esa diferencia sin utilizar un informe real. Si la entrada dice que un dato no consta, la explicación no debería convertirlo en ausencia del hallazgo. Si utiliza una posibilidad, la salida no debería presentarla como certeza. También hay que distinguir una indicación escrita de una actuación que ya ocurrió. Estos ejemplos desarrollan criterios de fidelidad propuestos por el asistente; no constituyen pautas de tratamiento ni una definición completa de lectura accesible.

## Lectura de una imagen y explicación son etapas diferentes

La preparación de la demostración conserva una comparación de lectores de imagen y una elección de configuración para una fotografía simulada. Ese registro describe comportamiento observado sobre una entrada pequeña, no una capacidad general para leer documentos clínicos. Una transcripción puede omitir una frase antes de que el modelo encargado de explicarla reciba el texto. Si solo se revisa la fluidez de la explicación final, esa pérdida puede pasar inadvertida.

El asistente propone separar pruebas de transcripción y de explicación. En las primeras, las entradas tendrían texto conocido y variaciones de tamaño, orientación y calidad de imagen. En las segundas se entregaría directamente un texto controlado, evitando confundir los errores de ambas etapas. El recorrido completo también necesita pruebas propias. Una operación correcta en cada componente no acredita que la combinación conserve paciente, documento o contexto. Esta edición no repite la demostración ni utiliza fotografías de informes de pacientes.

## Un fallo observado permite formular una comprobación concreta

El registro de septiembre identifica salidas que añadieron valoraciones o cambiaron el significado pese al filtro posterior. También recoge comportamientos que cumplieron algunas restricciones en las entradas sintéticas utilizadas. Ambas observaciones deben conservarse con su alcance. Que un filtro bloquee una clase de texto no demuestra que detecte todos los cambios de significado; una regla que opera sobre palabras puede necesitar contraste con otras formas de expresar la misma interpretación.

Como desarrollo propuesto, cada fallo podría convertirse en un caso con entrada, contenido que debe conservarse y transformaciones que no se aceptan. Un conjunto distinto comprobaría si la corrección funciona cuando cambia la redacción. Los revisores no usarían la propia salida del modelo como referencia de fidelidad. El resultado registraría omisiones, añadidos y grado de certeza por separado. Corregir una configuración requiere conservar la versión anterior para comparar efectos y detectar si una mejora introduce otra pérdida. No se describe esa batería como ejecutada.

## Privacidad y comprensión necesitan recorridos de evaluación propios

El diseño documentado prevé tratar identificadores antes del modelo y limitar información en salidas. Para estudiar ese mecanismo se utilizarían entradas inventadas con identidades y formatos de identificador ficticios. Habría que observar qué se conserva en pantalla, transporte, registros y archivos temporales. La presencia de un enmascaramiento no permite declarar anonimato completo: el resto del texto puede conservar información reconocible. La explicación pública no necesita reproducir el material utilizado por el prototipo.

La comprensión requiere otra pregunta. Un texto fiel puede resultar difícil de leer y uno sencillo puede alterar una condición. El asistente propone comprobar qué entiende una persona a partir de una salida y contrastarlo con el significado acordado del original sintético. La revisión clínica de ese significado y la evaluación con lectores tienen funciones diferentes. El glosario o el audio no acreditan por sí solos adecuación a todas las necesidades de acceso. La prueba debe definir destinatarios y tareas en lugar de asumirlos.

## Qué puede mostrar este prototipo en el portfolio

La ficha puede enseñar cómo una intención de comunicación se traduce en decisiones de contenido, componentes y comprobaciones. Javier aporta el propósito y los límites; la construcción y la redacción se apoyan en herramientas de IA, identificadas con la evidencia disponible. Los modelos de la demostración constan en su registro histórico y no se sustituyen por el utilizado para escribir esta versión. Las declaraciones de privacidad de la documentación no se presentan como auditoría completa del funcionamiento actual.

El código, las memorias de producto y los materiales comerciales permanecen en la categoría privada definida para Chiarezza. La explicación teórica pública puede mostrar entradas totalmente inventadas, esquemas derivados y decisiones revisadas, previa aprobación. No necesita afirmar mejora de comprensión, seguridad clínica o implantación para hacer visible el desarrollo. El siguiente avance consiste en comprobar las condiciones que el prototipo promete conservar y documentar fallos y correcciones. Un uso con información real, participantes o sistemas asistenciales sería una fase distinta con revisión y condiciones específicas.

## Procedencia de las posiciones

Enfoque recogido en los documentos del proyecto; las comprobaciones siguientes son propuestas editoriales de esta versión. El texto es una síntesis asistida por IA y requiere la revisión de Javier antes de atribuirle nuevas formulaciones. Se describen procesos y condiciones, sin juicios de valor ni atribuciones de intenciones.

## Fechas, versiones y cambios

Primera referencia temporal utilizada: 2026-05-30. Actualización declarada en el plan; no acredita la primera formulación de la idea.

Se desarrolla el mecanismo específico, sus aplicaciones y ejemplos de comprobación. Las nuevas propuestas del asistente se mantienen diferenciadas de las decisiones de Javier. Se registra el modelo de este turno con su evidencia, sin cambiar las atribuciones anteriores. No se incorporan resultados de pruebas nuevas. La edición no modifica las fuentes originales ni sus fechas.

## Herramientas y modelos

Imagen conceptual vigente, añadida el 2026-10-14: preparación e incorporación con Codex/OpenAI gpt-6.1-sol (metadatos del turno); generación y correcciones con image_gen de OpenAI, cuyo modelo exacto no consta. Sustituye el esquema anterior, conservado en el historial. Revisión independiente: gpt-6-astra.

Apoyo visual añadido el 2026-10-14: esquema original elaborado con Codex/OpenAI gpt-6.1-sol (metadatos del turno), Python 3.12.14 y ReportLab 4.4.9, exportado como SVG. Explica la idea del TL;DR; no representa una prueba o resultado nuevo. Revisión independiente de esta edición: gpt-6-astra; alcance documentado por separado. Compatibilidad tipográfica del SVG corregida en esta edición.

La redacción de esta versión utiliza Codex/OpenAI con el modelo gpt-6.1-sol. Su identificación consta en los metadatos del turno utilizado para esta edición; las atribuciones de versiones anteriores se conservan con su evidencia original. Se usaron Python para organización y comprobación local, y herramientas de lectura y edición de archivos. La revisión editorial independiente se encargó a un agente separado con gpt-6-astra; su alcance y resultado se registran fuera del dossier, sin equivaler a validación integral del proyecto. No se han configurado integraciones o actualización continua.

### Atribuciones históricas documentadas

- Ollama: MedGemma 27B text-it, GGUF Q4_K_M. Configuración declarada en observaciones de 29-09-2026; no repetida aquí.
- Ollama / OCR: qwen3-vl:8b-instruct. Comparativa y elección declaradas en observaciones de 29-09-2026.
- Claude: no_confirmado. El registro atribuye la revisión sintética a Claude sin modelo exacto.

## Fuentes y alcance de lectura

La base es la documentación interna identificada en el registro privado de fuentes de esta preparación. Se ha leído mediante extracción local y se han examinado fuentes y pasajes seleccionados; no es una auditoría sustantiva de todo el corpus. Las referencias externas de los antecedentes requieren verificación pertinente antes de reutilizar afirmaciones como hechos actuales. No se incluyen rutas privadas, documentos sensibles, conversaciones completas o material de terceros en este dossier.
