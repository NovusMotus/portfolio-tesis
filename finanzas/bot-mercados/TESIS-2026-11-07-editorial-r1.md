# Separar señales, ejecución y evaluación en experimentos de mercados

**Edición editorial:** 2026-11-07-editorial-r1. **Elaborada en UTC:** 2026-11-07T19:50:09.616232Z.

**Estado histórico declarado del contenido:** borrador local para revisión. **Versión histórica:** 2026-10-14-v4. **Fecha de redacción histórica declarada:** 2026-10-14. La fuente histórica estaba disponible públicamente en el commit consultado; su publicación no valida el contenido.

**Alcance de esta edición:** corrección administrativa del estado documental. El desarrollo y las atribuciones que siguen se reproducen de la [versión histórica](https://github.com/NovusMotus/portfolio-tesis/blob/2cd2acbd44ae01f98481e383af2368bce2973b43/finanzas/bot-mercados/TESIS.md); sus expresiones «esta versión» se refieren a aquella edición. Se conservan las fechas declaradas, los límites y las propuestas, sin añadir logros ni reconstruir el inicio de la idea. La disponibilidad de esta edición se comprueba en el repositorio y en la PR que la incorpore.

**Aporte editorial:** Codex desktop / OpenAI / gpt-6.1-sol; transformación con Python 3.12.14. [Registro de esta versión](VERSION-2026-11-07-editorial-r1.json) · [Revisión editorial fechada](../../REVISION_EDITORIAL_2026-11-07-r1.json).

## TL;DR

![Representación conceptual de Separar señales, ejecución y evaluación en experimentos de mercados.](proyecto.png)

*Ilustración conceptual generada con IA; no es una captura ni prueba de uso.*

- **Propósito:** Separar datos, señales y ejecución en experimentos de mercados.
- **Aportación y enfoque:** Javier dirige experimentos asistidos por IA; el análisis explica componentes y condiciones sin añadir una estrategia de inversión.
- **Trabajo y evidencia:** Scripts, datos y análisis; lectura de código sin ejecución en esta preparación.
- **Resultados y límites:** No se verifica operación en vivo ni retorno. Falta evaluar latencia, liquidez, comisiones y ejecución; configuraciones y registros económicos permanecen privados.

## Punto de partida y pregunta de esta línea

El proyecto explora scripts para obtener datos de mercado, construir señales y relacionarlas con órdenes. El problema metodológico es distinguir una señal calculada de una ejecución posible y de un resultado evaluado. La presencia de órdenes en un script no acredita que se hayan enviado, que la estrategia funcione o que un resultado histórico pueda reproducirse.

## Origen y propósito

La documentación disponible permite describir esta línea, pero no reconstruye de forma confirmada qué observación, publicación o experiencia la inició. El punto de partida puede ser una idea, una hipótesis, una aplicación o una práctica con herramientas; no se presupone que exista un problema que resolver. Si se recupera una referencia de origen, se distinguirán lo que plantea esa fuente y la adaptación realizada por Javier.

## Enfoque del proyecto y propuesta de esta versión

La lectura del código muestra funciones de consulta, seguimiento y preparación de ejecución. El enfoque público consiste en describir cómo se separan datos, decisión y condiciones de operación, sin revelar configuraciones de acceso o posiciones. Javier dirige los experimentos con ayuda de IA. La tesis no añade una estrategia ni recomienda una operación; plantea criterios para entender y revisar el comportamiento de los materiales existentes.

## Desarrollo y evidencia disponible

La carpeta contiene scripts, datos y salidas de análisis. En esta fase se ha leído código sin ejecutarlo. La configuración de acceso debe conservarse separada de la explicación y del código publicable. No se verifica uso en vivo, beneficio, pérdida o rendimiento ajustado a costes. Las cifras de resultados existentes no se reproducen como retorno demostrado. El dossier muestra el alcance de una investigación y las diferencias entre sus componentes.

## Preguntas y límites que permanecen abiertos

La latencia, liquidez, comisiones y forma de ejecutar una orden pueden cambiar un resultado simulado. Seleccionar parámetros después de observar resultados necesita distinguirse de una comprobación con datos posteriores. Una fuente puede producir información incompleta o duplicada. Las configuraciones sensibles no deben incorporarse a una publicación y la historia Git requiere revisión independiente antes de transportarse.

## Cómo podría comprobarse

Se propone un entorno sin operaciones reales con entradas y reglas fechadas. La evaluación registraría señales calculadas, decisiones que no podrían ejecutarse y diferencias entre simulación y condiciones definidas. Los resultados deberían separar entrenamiento, selección y contraste posterior. Esta preparación no ejecuta el bot, mueve fondos ni autoriza órdenes; cualquier actuación sobre cuentas sería un encargo específico distinto.

## Leer el recorrido del script sin atribuir operación real

El código seleccionado contiene funciones de consulta de mercados, lectura de precio, preparación de compra y seguimiento. La lectura es estática: no se importa ni ejecuta el programa. Esta versión propone explicar ese recorrido con cuatro etapas: datos recibidos, señal calculada, decisión propuesta y posible ejecución. Una función que prepara una orden acredita una parte del código, no que esa orden haya sido enviada o aceptada. El estado operativo de la cuenta queda fuera de esta preparación.

Para una muestra ficticia, se podrían conservar una entrada y una señal esperada según una regla identificada. Después se describiría qué condiciones tendría que cumplir una ejecución simulada. La regla no se propone como estrategia rentable ni como acción para Javier. El ejemplo permitiría localizar dónde una conclusión depende de datos, de un ajuste o de una suposición sobre ejecución, sin publicar parámetros sensibles o registros de operaciones reales.

## Datos y tiempo forman parte de la pregunta

La prueba propuesta identificaría fuente, instante de consulta, periodo del dato y condiciones de disponibilidad. Se distinguiría información que podía conocerse al calcular una señal de información observada después. Un registro histórico no se utilizaría retroactivamente como si hubiera estado disponible en el momento de la decisión. La ficha no reconstruye todas las marcas temporales de las salidas existentes y no afirma que un análisis conservado satisfaga este criterio.

El conjunto ficticio podría incluir una respuesta tardía, un mercado repetido y un dato ausente. Se observaría si el procedimiento los distingue de una entrada válida. Antes de evaluar una señal se establecería qué información necesita y cómo se trata una entrada incompleta. El ensayo también conservaría cambios de formato o fuente que afecten a la comparación. Su finalidad es comprobar comportamiento documental y de cálculo, sin consultar cuentas o activar una conexión real.

## Una simulación debe describir sus supuestos de ejecución

La continuación propuesta definiría una ejecución simulada con estados propios: decisión emitida, orden simulada, aceptación supuesta, cumplimiento y cierre. Las transiciones no se considerarían automáticas. Se registraría qué reglas representan la posibilidad de ejecutar y qué casos quedan sin cumplimiento. La definición de comisiones, condiciones o límites requeriría datos pertinentes si se pretende modelar un mercado concreto; aquí no se asignan cifras ni se considera realista una simulación por su existencia.

Un caso ficticio podría producir una señal y después impedir la ejecución según una condición del ensayo. La evaluación mantendría ambos resultados separados: señal calculada y decisión no ejecutada en esa simulación. Este recorrido ayuda a no interpretar todas las señales como operaciones completadas. El código de ejecución y sus accesos permanecen privados, pendientes de revisión; esta tesis no establece un modo seguro de ejecución del bot ni comprueba su configuración activa.

## Separar selección de reglas y contraste posterior

Para estudiar una regla se propone fijar una versión y un conjunto de contraste antes de interpretar resultados. Si se modifican parámetros tras observar un conjunto, ese conjunto forma parte del desarrollo y no se presentaría sin más como comprobación independiente. Una versión nueva conservaría qué se cambió y con qué información. El protocolo no añade una estrategia al proyecto ni afirma que las salidas históricas hayan seguido esta separación.

La prueba se realizaría sin órdenes reales y distinguiría errores de datos, señales y supuestos de ejecución. El resultado podría ser un comportamiento reproducible bajo esas condiciones, una discrepancia o una pregunta que sigue abierta. No se convertiría ninguna de esas observaciones en beneficio demostrado. Tampoco se extrapolaría a otro periodo o configuración por compartir el nombre del script. La evaluación económica, si se solicita, necesitaría un alcance y evidencia propios; esta ficha se centra en el diseño del experimento.

## Explicar el trabajo disponible y el que aún falta

La carpeta acredita scripts y materiales de análisis. La aportación de esta versión es una organización del recorrido y de sus pruebas posibles, propuesta por el asistente. No acredita actividad en vivo, resultados económicos, calibración o una estrategia validada. Las atribuciones históricas de herramientas se conservarán solo cuando haya evidencia; un import de una biblioteca no indica qué modelo de IA escribió el código.

Un siguiente hito podría recuperar un análisis concreto y describir sus datos, regla, supuestos y límites, o ejecutar un ensayo ficticio autorizado sin acceso a cuentas. La versión registraría la evidencia obtenida y conservaría los resultados anteriores sin reescribirlos como si siempre hubieran usado el criterio nuevo. El portfolio permitiría observar cómo se divide una idea experimental en componentes revisables. La implementación reservada no necesita publicarse para explicar ese razonamiento al nivel que Javier autorice.

## Procedencia de las posiciones

Síntesis estructural de los scripts; criterios de evaluación propuestos, sin recomendaciones de mercado. El texto es una síntesis asistida por IA y requiere la revisión de Javier antes de atribuirle nuevas formulaciones. Se describen procesos y condiciones, sin juicios de valor ni atribuciones de intenciones.

## Fechas, versiones y cambios

Primera referencia temporal utilizada: no confirmada. El inicio real y las fechas de cada aportación histórica no están reconstruidos. La fecha del archivo no sustituye la fecha de la idea.

Se añaden los desarrollos: Leer el recorrido del script sin atribuir operación real; Datos y tiempo forman parte de la pregunta; Una simulación debe describir sus supuestos de ejecución; Separar selección de reglas y contraste posterior; Explicar el trabajo disponible y el que aún falta. Las propuestas nuevas se atribuyen al asistente y se registra el modelo de este turno sin alterar las atribuciones anteriores. Se ajusta la descripción pública del desarrollo y su estado tras revisión editorial. No se incorporan resultados de pruebas nuevas. La edición no modifica las fuentes originales ni sus fechas.

## Herramientas y modelos

Imagen conceptual vigente, añadida el 2026-10-14: preparación e incorporación con Codex/OpenAI gpt-6.1-sol (metadatos del turno); generación y correcciones con image_gen de OpenAI, cuyo modelo exacto no consta. Sustituye el esquema anterior, conservado en el historial. Revisión independiente: gpt-6-astra.

Apoyo visual añadido el 2026-10-14: esquema original elaborado con Codex/OpenAI gpt-6.1-sol (metadatos del turno), Python 3.12.14 y ReportLab 4.4.9, exportado como SVG. Explica la idea del TL;DR; no representa una prueba o resultado nuevo. Revisión independiente de esta edición: gpt-6-astra; alcance documentado por separado. Compatibilidad tipográfica del SVG corregida en esta edición.

La redacción de esta versión utiliza Codex/OpenAI con el modelo gpt-6.1-sol. Su identificación consta en los metadatos del turno utilizado para esta edición; las atribuciones de versiones anteriores se conservan con su evidencia original. Se usaron Python para organización y comprobación local, y herramientas de lectura y edición de archivos. La revisión editorial independiente se encargó a un agente separado con gpt-6-astra; su alcance y resultado se registran fuera del dossier, sin equivaler a validación integral del proyecto. No se han configurado integraciones o actualización continua.

### Atribuciones históricas documentadas

No hay una atribución histórica exacta reconstruida para esta ficha. Las menciones a herramientas en las fuentes no se consideran prueba de uso.

## Fuentes y alcance de lectura

La base es la documentación interna identificada en el registro privado de fuentes de esta preparación. Se ha leído mediante extracción local y se han examinado fuentes y pasajes seleccionados; no es una auditoría sustantiva de todo el corpus. Las referencias externas de los antecedentes requieren verificación pertinente antes de reutilizar afirmaciones como hechos actuales. No se incluyen rutas privadas, documentos sensibles, conversaciones completas o material de terceros en este dossier.
