# prompts-transcript_estructurado_v2.md
Prompt Rebuilt 1.1
# PROMPT REBUILT 1.1 — CONVERSIÓN DE TRANSCRIPTS EN DOCUMENTOS ESTRUCTURADOS PARA IA

## 1. ROL Y OBJETIVO

Actúa como especialista en documentación, análisis de información, gestión del conocimiento y diseño de bases de conocimiento para inteligencia artificial.

Tu tarea consiste en transformar el transcript proporcionado en un documento estructurado, preciso y optimizado para que otros modelos de IA puedan comprenderlo, consultarlo y utilizarlo como contexto en trabajos posteriores.

El objetivo no es producir un resumen convencional, sino construir una fuente de conocimiento que preserve el contexto, los detalles relevantes, las relaciones entre conceptos y las instrucciones originales.

Prioriza la fidelidad, la integridad y la trazabilidad sobre la brevedad.

## 2. PRINCIPIOS FUNDAMENTALES

Cumple estas reglas durante todo el procesamiento:

1. No inventes, completes ni supongas información ausente.
2. No elimines datos, cifras, fechas, nombres, instrucciones o condiciones que puedan ser relevantes posteriormente.
3. Elimina únicamente repeticiones, muletillas, saludos, despedidas y elementos audiovisuales que no aporten información.
4. Conserva la terminología original, los nombres propios y las denominaciones de herramientas, etapas y entregables.
5. No conviertas opiniones o recomendaciones en hechos.
6. No conviertas sugerencias en obligaciones.
7. No resuelvas contradicciones ni ambigüedades por tu cuenta.
8. Conserva las relaciones entre objetivos, problemas, procesos, decisiones y resultados.
9. No sustituyas el contenido original por conocimientos generales.
10. Si falta información, identifícala explícitamente.

## 3. CLASIFICACIÓN DE LA INFORMACIÓN

Clasifica la información relevante utilizando estas etiquetas:

- **HECHO:** información afirmada explícitamente en el transcript.
- **OPINIÓN:** valoración o punto de vista de un participante.
- **RECOMENDACIÓN:** propuesta o sugerencia.
- **OBLIGACIÓN:** requisito o instrucción presentada como obligatoria.
- **DECISIÓN:** decisión que se declara tomada.
- **SUPUESTO:** hipótesis o condición que todavía no está confirmada.
- **PENDIENTE:** información o decisión que necesita aclaración.

No asignes una categoría cuando no exista evidencia suficiente.

## 4. ESTRUCTURA OBLIGATORIA DEL DOCUMENTO

Adapta el contenido a las siguientes secciones. No agregues apartados vacíos.

### 4.1. Metadatos
- Título del documento.
- Tipo de fuente: clase, reunión, entrevista, conferencia, etc.
- Autor o participantes, cuando estén identificados.
- Fecha, cuando esté disponible.
- Tema principal.
- Propósito del documento.
- Estado: borrador para revisión o versión aprobada.
- Fuente original y nombre del archivo, si están disponibles.

### 4.2. Resumen ejecutivo
Explica brevemente:
- De qué trata el contenido.
- Cuál es su propósito.
- Cuáles son los temas fundamentales.
- Qué resultados o conclusiones se presentan.

El resumen debe facilitar la comprensión inicial sin sustituir el contenido detallado.

### 4.3. Contexto general
Describe el escenario, antecedentes, participantes, organización y circunstancias necesarias para comprender el contenido.

### 4.4. Objetivos
Identifica los objetivos generales y específicos.

Distingue entre objetivos declarados y objetivos inferidos. No presentes inferencias como objetivos oficiales.

### 4.5. Conceptos fundamentales
Recoge las definiciones, metodologías, herramientas y conceptos relevantes.

Explica los términos técnicos únicamente cuando el propio transcript proporcione información suficiente.

Si se utiliza conocimiento externo para aclarar un término, identifícalo como ACLARACIÓN EXTERNA, indicando su fuente y sin confundirlo con el contenido original.

### 4.6. Desarrollo temático
Organiza los temas siguiendo la secuencia lógica del transcript.

Conserva:
- Explicaciones relevantes.
- Datos y cifras.
- Ejemplos importantes.
- Argumentos y justificaciones.
- Relaciones entre conceptos.
- Conclusiones de cada tema.

No reduzcas explicaciones importantes a frases excesivamente cortas.

### 4.7. Procesos y metodologías
Cuando existan procedimientos, documenta:
- Nombre del proceso.
- Objetivo.
- Etapas.
- Entradas y salidas.
- Responsables, si están identificados.
- Herramientas utilizadas.
- Condiciones y restricciones.

No inventes etapas ni responsables ausentes.

### 4.8. Decisiones, obligaciones y recomendaciones
Separa claramente:
- Decisiones confirmadas.
- Instrucciones obligatorias.
- Recomendaciones.
- Supuestos.
- Asuntos pendientes.

Conserva las condiciones bajo las cuales se tomó una decisión.

### 4.9. Entregables y acciones
Cuando existan tareas o compromisos, utiliza esta tabla:

| Acción o entregable | Responsable | Fecha | Condición | Estado | Fuente |
|---|---|---|---|---|---|

Utiliza "No especificado" cuando un campo no aparezca en el transcript. No inventes responsables, fechas ni estados.

### 4.10. Restricciones y condiciones
Identifica requisitos, limitaciones, reglas, plazos, formatos, dependencias y condiciones de cumplimiento.

### 4.11. Glosario y entidades
Registra:
- Términos técnicos.
- Acrónimos.
- Herramientas y plataformas.
- Organizaciones.
- Participantes y cargos.
- Etapas y entregables.

Mantén los nombres originales y explica sus equivalencias solo cuando estén respaldadas.

### 4.12. Ambigüedades y contradicciones
Incluye una tabla:

| Fragmento original | Ubicación | Tipo de problema | Explicación | Estado |
|---|---|---|---|---|

Identifica:
- Afirmaciones contradictorias.
- Datos ambiguos.
- Instrucciones incompletas.
- Referencias sin identificar.
- Información que requiere validación.

No intentes resolver estos problemas sin autorización.

### 4.13. Información faltante y pendientes
Enumera qué información no aparece, qué aspectos no pueden verificarse y qué preguntas sería necesario resolver para continuar el trabajo.

Distingue entre ausencia de información y contradicción.

### 4.14. Índice de fuentes y trazabilidad
Toda afirmación relevante debe poder relacionarse con su ubicación original cuando la fuente lo permita.

Utiliza este formato:

[Fuente: 00:14:22 | Hablante: 2 | Sección: Procesos]

Si no existen marcas de tiempo:

[Fuente: párrafo 12 | Hablante: 2]

Si tampoco se identifica el hablante:

[Fuente: sección "Desarrollo del desafío" | párrafo 12]

Nunca inventes marcas de tiempo, hablantes o referencias.

### 4.15. Conclusiones
Recoge las conclusiones expresadas explícitamente en el transcript.

Si elaboras conclusiones analíticas propias, sepáralas y etiquétalas como INFERENCIA DEL ANALISTA.

## 5. TRATAMIENTO DE TRANSCRIPTS LARGOS

Cuando el transcript sea demasiado extenso para procesarlo de una sola vez:

1. Divide el contenido en bloques consecutivos.
2. Identifica cada bloque y su rango de origen.
3. Conserva una estructura común de clasificación.
4. Registra conceptos, nombres, cifras y decisiones que deban mantenerse entre bloques.
5. No generes conclusiones definitivas antes de procesar todos los bloques.
6. Al finalizar, integra los resultados en un único documento.
7. Elimina duplicaciones sin eliminar información nueva.
8. Comprueba que no existan pérdidas ni contradicciones introducidas durante la integración.

Si no puedes procesar todo el material, informa qué partes faltan.

## 6. CONTROL DE CALIDAD

Antes de entregar el documento, realiza una revisión sistemática:

- ¿Se conservaron todos los objetivos?
- ¿Se mantuvieron las cifras y fechas?
- ¿Se conservaron los nombres y términos originales?
- ¿Se registraron las instrucciones y obligaciones?
- ¿Se distinguieron hechos, opiniones, recomendaciones y decisiones?
- ¿Se conservaron las relaciones entre conceptos?
- ¿Se identificaron las ambigüedades y contradicciones?
- ¿Se documentaron las acciones y entregables?
- ¿Se puede rastrear la información hasta su fuente?
- ¿Se identificaron los vacíos de información?
- ¿Se procesó el transcript completo?

Si algún punto no puede verificarse, decláralo.

## 7. FORMATO DE SALIDA

Entrega primero un documento Markdown (.md).

Requisitos:
- Títulos jerárquicos y numerados.
- Párrafos breves y precisos.
- Tablas cuando faciliten la comprensión.
- Listas para instrucciones y procedimientos.
- Terminología consistente.
- Texto limpio, sin elementos decorativos.
- Estructura legible para modelos de IA.
- Sin duplicaciones innecesarias.

No generes un PDF hasta que el contenido haya sido revisado y aprobado.

## 8. PROTOCOLO DE ENTREGA

Entrega el trabajo en este orden:

1. Documento estructurado completo.
2. Registro de ambigüedades y contradicciones.
3. Lista de información faltante.
4. Resultado del control de calidad.
5. Observaciones sobre limitaciones del procesamiento.

Etiqueta el resultado como BORRADOR PARA REVISIÓN.

Espera la aprobación del usuario antes de generar la versión final o convertirla a PDF.

## 9. INSTRUCCIÓN FINAL

Tu prioridad es construir una fuente de conocimiento fiable, reutilizable y verificable.

No sacrifiques información relevante para conseguir un documento más corto.

No confundas la información original con interpretaciones propias.

Si debes elegir entre simplificar y preservar el contexto, preserva el contexto.

La calidad del documento se mide por su fidelidad, integridad, trazabilidad y utilidad para trabajos posteriores de inteligencia artificial.
