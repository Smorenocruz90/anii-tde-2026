# Mapa del formulario ANII TDE_1_2026

**Fuente:** https://postulaciones.anii.org.uy/proyecto/config.php?id=191754
**Código:** TDE_1_2026_1_191754
**Capturado:** 13 may 2026
**Idiomas aceptados en la postulación:** Español o Inglés (radio button)

Este documento mapea todas las preguntas, tipos de campo y límites de palabras/caracteres del formulario online de ANII. Sirve como referencia para dimensionar el contenido narrativo de la propuesta y para identificar qué campos son obligatorios.

---

## Estructura general del formulario

El formulario tiene **9 secciones principales**, varias con sub-secciones:

1. DATOS GENERALES (Datos del proyecto, Áreas, Sub-eje temático)
2. ORGANIZACIONES PARTICIPANTES
3. RECURSOS HUMANOS
4. DESCRIPCIÓN DEL PROYECTO (10 sub-secciones)
5. PRESUPUESTO (Presupuesto por rubro, Totales, Otros recursos)
6. OTROS DATOS (Impacto ambiental, Aspectos éticos, Datos de contacto, Datos administrativos)
7. DOCUMENTOS ADJUNTOS
8. ENCUESTA SATISFACCIÓN
9. VALIDAR Y TERMINAR

Cada sub-sección se navega vía botón en el menú lateral. El formulario tiene botón **GRABAR** al final de cada sub-sección y un botón **EXPORTAR EN PDF** disponible en cualquier momento.

**Recomendación de ANII visible en el form:** "Recomendamos ingresar a la sección 'Validar y Terminar' del formulario a medida que se carga la postulación para validar los datos ingresados en cada ítem y verificar si hay datos faltantes."

---

## Resumen ejecutivo de límites narrativos

Estas son las preguntas con **límite de palabras** declarado en el formulario. Total: **15 textareas con límite de palabras**, suma máxima **5.250 palabras** + tablas.

| Sub-sección | Pregunta | Límite | Obligatorio |
|-------------|----------|--------|-------------|
| ANTECEDENTES | Antecedentes y justificación | 500 palabras | Sí |
| ANTECEDENTES | Antecedentes institucionales | 500 palabras | Sí |
| OBJETIVOS DEL PROYECTO | Objetivo general | 250 palabras | Sí |
| METODOLOGÍA | Diseño de investigación y metodología | 500 palabras | Sí |
| INNOVACIÓN Y ESCALABILIDAD | Contribución a la resolución del problema | 500 palabras | Sí |
| INNOVACIÓN Y ESCALABILIDAD | Escalabilidad | 300 palabras | Sí |
| INNOVACIÓN Y ESCALABILIDAD | Resultados del proyecto | 300 palabras | Sí |
| INNOVACIÓN Y ESCALABILIDAD | Vinculación | 200 palabras | No |
| OTRAS CONTRIBUCIONES Y RIESGOS | Otras contribuciones del proyecto | 200 palabras | Sí |
| OTRAS CONTRIBUCIONES Y RIESGOS | Riesgos | 200 palabras | Sí |
| OTRAS CONTRIBUCIONES Y RIESGOS | Requisitos, permisos y acceso a información | 200 palabras | Sí |
| ESTRATEGIA DE DIFUSIÓN Y DIVULGACIÓN | Divulgación | 200 palabras | Sí |
| ESTRATEGIA DE DIFUSIÓN Y DIVULGACIÓN | Difusión de los resultados | 200 palabras | Sí |
| RESUMEN PUBLICABLE | Resumen en español | 300 palabras | Sí |
| RESUMEN PUBLICABLE | Resumen en inglés | 300 palabras | Sí |
| **TOTAL** | — | **5.250 palabras** | — |

Además hay **4 sub-secciones tipo tabla** con filas que se agregan dinámicamente:
- Objetivos específicos (mínimo 1) — columnas: Objetivo específico / Resultados esperados / Observaciones
- Plan de trabajo — columnas: Actividad / Es hito / Inicio/Fin / Descripción / Observaciones
- Impactos esperados del proyecto — columnas: Impactos / Beneficiarios potenciales / Cuantificación del impacto / Observaciones
- Propiedad y uso de los resultados — columnas: Resultado / Factibilidad de protección / Forma de apropiación / Acciones

Las celdas internas de estas tablas pueden tener sus propios límites de caracteres (no capturados — se ven al clickear AGREGAR).

---

## 1. DATOS GENERALES

### 1.1 DATOS DEL PROYECTO

| Campo | Tipo | Obligatorio | Límite | Notas |
|-------|------|-------------|--------|-------|
| Confirmo que he leído y acepto las bases | Checkbox | Sí | — | — |
| Título en español | Texto | Sí | s/d (verificar maxlength server-side) | "El texto del título debe ser representativo de la propuesta. Se usará en documentación pública y de difusión de ANII y Fundación Ceibal." |
| Título en inglés | Texto | No | s/d | — |
| Palabras claves en español | Texto | Sí | 3 palabras distintas | "Ingrese tres palabras claves distintas que representen el eje o el espíritu del proyecto." |
| Palabras claves en inglés | Texto | No | 3 palabras distintas | — |
| Duración de la propuesta (Meses) | Select | Sí | 1 a 6 meses | Cierra coherencia con bases (6+3 con prórroga; en el form solo carga hasta 6) |
| País donde se desarrollará el proyecto | Select | Sí | Lista completa de países | Seleccionar **República Dominicana** |

**Nota crítica sobre la duración:** el dropdown del campo "Duración de la propuesta" muestra opciones de 1 a 6 meses. La prórroga de 3 meses (mencionada en las bases) se solicita aparte, no como parte de la duración inicial declarada.

---

### 1.2 ÁREAS

| Campo | Tipo | Obligatorio | Opciones / Notas |
|-------|------|-------------|------------------|
| Área de conocimiento | Select | Sí | Ciencias Naturales y Exactas / Ingeniería y Tecnología / Ciencias Médicas y de la Salud / Ciencias Agrícolas / **Ciencias Sociales** / Humanidades |
| Subárea de conocimiento | Select | Sí | Cascade del anterior |
| Disciplina | Select | Sí | Cascade |
| Especialidad | Texto libre | Sí | — |
| Sector/núcleo de problemas y oportunidades | Select | Sí | Software, Servicios Informáticos y Producción Audiovisual / Salud Humana y Animal / Producción Agropecuaria y Agroindustrial / Medio Ambiente y Servicios ambientales / Energía / **Educación y Desarrollo Social** / Logística y Transporte / Turismo / Otro |
| Áreas tecnológicas a priorizar | Select | Sí | **Tecnología de la Información y las Comunicaciones** / Biotecnología / Nanotecnología / Otra |

**Sugerencias para nuestra propuesta:**
- Área de conocimiento: **Ciencias Sociales**
- Sector: **Educación y Desarrollo Social**
- Áreas tecnológicas: **Tecnología de la Información y las Comunicaciones**

---

### 1.3 SUB-EJE TEMÁTICO

*No fue posible mapear este sub-paso directamente — la validación del form requiere completar ÁREAS antes de habilitar SUB-EJE TEMÁTICO. Inferencia desde las bases: corresponde elegir la(s) línea(s) temática(s) del Anexo I (A / B / C / D). Nuestra elección: **D.II como principal, C como secundaria** (ver doc maestro de contexto).*

---

## 2. ORGANIZACIONES PARTICIPANTES

Sub-sección tipo tabla. No tiene campos narrativos con límite de palabras.

| Aspecto | Detalle |
|---------|---------|
| Estructura | Tabla con columnas: Rol / Nombre |
| Acción | Botón **AGREGAR REGISTRO** para sumar cada organización |
| Rol obligatorio | **Institución proponente** (al menos 1) |
| Roles disponibles | Institución para capacitación / Institución proponente / Otras instituciones participantes |
| Aval obligatorio | Toda institución (proponente y participantes) requiere **carta aval firmada de puño y letra o con firma digital acreditada por el responsable de la institución** |

**Definiciones del formulario:**

- **INSTITUCIÓN PROPONENTE:** Es la institución principal del proyecto y se responsabiliza de la presentación de la propuesta y de la ejecución del proyecto. Responsable de la firma del contrato con ANII. Requiere carta aval.
- **INSTITUCIÓN PARTICIPANTE:** Es aquella institución asociada al proyecto, que aporte recursos en efectivo o que valorice recursos ya existentes para la ejecución del proyecto (asignación de tiempo técnico, valorización de aportes en infraestructura y equipamiento, predios o laboratorios, insumos, consultores, etc.). La participación de un investigador o profesor visitante a título personal **no** implica que su institución sea participante del proyecto. Requiere carta aval.

**Decisión asociada (ver doc maestro):** definir si Critertec RD es proponente y la universidad partner es participante (Escenario Preferido) o al revés (Escenario Alternativo).

---

## 3. RECURSOS HUMANOS

Sub-sección tipo tabla. No tiene campos narrativos con límite de palabras.

| Aspecto | Detalle |
|---------|---------|
| Estructura | Tabla con columnas: Rol / Nombre |
| Acción | Botón **AGREGAR REGISTRO** |
| Rol obligatorio | **Responsable técnico-científico** (al menos 1) |
| Roles disponibles | Investigador / Investigador a contratar / Técnico de apoyo / Técnico de apoyo a contratar / Consultor / Consultor a contratar / Profesor visitante / **Responsable técnico-científico** / Corresponsable técnico-científico |
| CV obligatorio | "Para los recursos humanos que presenten CVUy, existen datos mínimos a completar en el mismo." Hay un link a "más información" para los requisitos del CVUy. |

**Asignación tentativa del equipo (ver doc maestro):**

| Persona | Rol en el formulario |
|---------|----------------------|
| Berenice Pacheco-Salazar (PhD) | Responsable técnico-científico |
| Sebastián Moreno Cruz | Corresponsable técnico-científico |
| Agustina Bussi | Investigador (rol pedagógico y de producto) |
| Steven | Investigador (rol técnico) o Consultor |
| Investigador junior (a definir) | Investigador a contratar |

---

## 4. DESCRIPCIÓN DEL PROYECTO

Esta es la sección que concentra todo el contenido narrativo con límites de palabras. **10 sub-secciones.**

### 4.1 ANTECEDENTES

| # | Pregunta | Tipo | Límite | Obligatorio |
|---|----------|------|--------|-------------|
| 1 | **Antecedentes y justificación** | Textarea | **500 palabras** | Sí |
| 2 | **Antecedentes institucionales** | Textarea | **500 palabras** | Sí |

**Texto de ayuda en cada pregunta:**

1. *"Describir la situación actual y los antecedentes del tema principal a investigar en el proyecto. Incluir el marco teórico de referencia. Describir las principales características del proyecto de investigación, detallando el tema central a investigar, justificando su aporte al estado actual del conocimiento, así como los antecedentes del equipo de investigación."*

2. *"Describir las capacidades técnicas e institucionales con las que cuentan las organizaciones proponente y participantes (si corresponde) para el desarrollo del proyecto, y sus antecedentes en relación al desarrollo de proyectos de investigación educativa."*

**Cobertura del criterio de evaluación:** criterio **1.1 Descripción y relevancia del problema (25%)** y criterio **A.2 Antecedentes de la organización proponente (filtro eliminatorio)**.

---

### 4.2 OBJETIVOS DEL PROYECTO

| # | Pregunta | Tipo | Límite | Obligatorio |
|---|----------|------|--------|-------------|
| 1 | **Objetivo general** | Textarea | **250 palabras** | Sí |
| 2 | **Objetivos específicos** | Tabla (mínimo 1) | s/d por celda | Sí (mín 1) |

**Estructura de la tabla de Objetivos específicos:**
- Objetivo específico (texto)
- Resultados esperados (texto)
- Observaciones (texto)

**Cobertura del criterio:** criterio **1.2 Objetivos y resultados esperados (25%)**.

---

### 4.3 METODOLOGÍA

| # | Pregunta | Tipo | Límite | Obligatorio |
|---|----------|------|--------|-------------|
| 1 | **Diseño de investigación y metodología** | Textarea | **500 palabras** | Sí |

**Texto de ayuda:**
> *"Describir y justificar la estrategia, planteando la hipótesis (en caso de corresponder) y la metodología seleccionada para alcanzar los objetivos específicos. Brindar detalles que permitan valorar si el abordaje propuesto es adecuado (ejemplos: estrategia de muestreo, tamaño muestral, validación previa de herramientas a utilizar, análisis estadístico a emplear, **estrategias de mitigación de posibles desafíos y limitaciones de la metodología propuesta**)."*

**Cobertura del criterio:** criterio **1.3 Diseño de investigación y metodología (25%)**. El propio texto del formulario menciona explícitamente las estrategias de mitigación, alineado con las pautas de evaluación.

---

### 4.4 PLAN DE TRABAJO

Sub-sección tipo tabla. No tiene textarea con límite de palabras.

| Aspecto | Detalle |
|---------|---------|
| Estructura | Tabla con columnas: Actividad / Es hito / Inicio/Fin / Descripción / Observaciones |
| Pre-requisito | "Es necesario ingresar la duración de la propuesta antes de agregar una actividad" (debe llenarse 1.1 primero) |
| Texto de ayuda | *"Especificar el plan de trabajo con la secuencia cronológica de las actividades del proyecto y su duración. Para cada actividad, indicar si su cumplimiento implica haber alcanzado un hito del proyecto. Se entiende por hito la instancia en la que culmina una etapa o se logra un avance significativo del proyecto."* |

**Cobertura del criterio:** criterio **4. Plan de Trabajo (20%)**.

---

### 4.5 INNOVACIÓN Y ESCALABILIDAD

| # | Pregunta | Tipo | Límite | Obligatorio |
|---|----------|------|--------|-------------|
| 1 | **Contribución a la resolución del problema** | Textarea | **500 palabras** | Sí |
| 2 | **Escalabilidad** | Textarea | **300 palabras** | Sí |
| 3 | **Resultados del proyecto** | Textarea | **300 palabras** | Sí |
| 4 | **Vinculación** | Textarea | **200 palabras** | No |

**Textos de ayuda:**

1. *"Describir de qué manera el proyecto aporta a la solución de la problemática identificada, detallando los resultados, productos e insumos que se desarrollarán. Indicar de qué manera el proyecto es innovador en cuanto a la resolución del problema planteado y describa su potencial transformador en el área del conocimiento."*

2. *"Indicar si el proyecto posee el potencial para ser escalable y replicable en otros contextos a nivel nacional o internacional."*

3. *"Indicar qué recursos se generarán y de qué modo los resultados serán transferidos a educadores, usuarios o hacedores de políticas educativas de acuerdo a lo que corresponda."*

4. *"En caso de que el proyecto cuente con más de una organización involucrada describir cómo será la articulación entre ellas y, en caso de que exista transferencia de conocimiento, especificar cómo se realizará."*

**Cobertura del criterio:** criterio **1.4 Innovación, impactos y escalabilidad (25%)**.

---

### 4.6 IMPACTOS ESPERADOS DEL PROYECTO

Sub-sección tipo tabla. No tiene textarea con límite de palabras.

| Aspecto | Detalle |
|---------|---------|
| Estructura | Tabla con columnas: Impactos / Beneficiarios potenciales / Cuantificación del impacto / Observaciones |
| Texto de ayuda | *"Indicar los impactos del proyecto en términos económicos, sociales, ambientales u otros."* |

**Cobertura del criterio:** complemento del **1.4 Innovación, impactos y escalabilidad (25%)**.

---

### 4.7 OTRAS CONTRIBUCIONES Y RIESGOS

| # | Pregunta | Tipo | Límite | Obligatorio |
|---|----------|------|--------|-------------|
| 1 | **Otras contribuciones del proyecto** | Textarea | **200 palabras** | Sí |
| 2 | **Riesgos** | Textarea | **200 palabras** | Sí |
| 3 | **Requisitos, permisos y acceso a información** | Textarea | **200 palabras** | Sí |

**Textos de ayuda:**

1. *"Describir otras contribuciones que se espera tener con el desarrollo del proyecto."*
2. *"Identificación de posibles riesgos y estrategias para mitigarlos."*
3. *"Describa si la investigación requiere acceder a información sobre personas, centros educativos, etc. En caso de requerir información o permisos indique los avances que tiene el equipo de investigación en estas solicitudes."*

**Pregunta 3 es muy relevante para nosotros** — aquí se documenta el acceso a Soy Digital, MINERD/INDOTEL/BID, y el estado del IRB con la universidad partner.

---

### 4.8 PROPIEDAD Y USO DE LOS RESULTADOS

Sub-sección tipo tabla. No tiene textarea con límite de palabras.

| Aspecto | Detalle |
|---------|---------|
| Estructura | Tabla con columnas: Resultado / Factibilidad de protección / Forma de apropiación / Acciones |
| Texto de ayuda | *"En caso que corresponda indicar si los resultados del proyecto son factibles de patentamiento, licenciamiento u otros mecanismos de protección de la propiedad intelectual. Indicar además quiénes se apropiarán y de qué manera usarán los resultados del proyecto."* |

**Pieza crítica para la estrategia IP** (ver doc maestro sección 6): acá hay que declarar la separación background/foreground IP en formato de tabla. Cada output (paper, dataset, marco metodológico abierto, etc.) ocupa una fila.

---

### 4.9 ESTRATEGIA DE DIFUSIÓN Y DIVULGACIÓN

| # | Pregunta | Tipo | Límite | Obligatorio |
|---|----------|------|--------|-------------|
| 1 | **Divulgación** | Textarea | **200 palabras** | Sí |
| 2 | **Difusión de los resultados** | Textarea | **200 palabras** | Sí |

**Textos de ayuda:**

1. *"Se entiende por divulgación aquellas acciones que tengan como fin la comunicación de los conocimientos adquiridos a un público amplio no especializado. Se procurarán modalidades y estilos de comunicación accesibles para quienes no conocen sobre la temática específica, con miras a promover diálogos con distintos sectores sociales y contribuir a los procesos de democratización y apropiación social del conocimiento."*

2. *"Se entiende por difusión aquellas acciones que tengan como fin la comunicación de resultados científicos del proyecto a un público académico especializado. Por ejemplo, se podrán incluir actividades relacionadas a congresos, eventos académicos y publicación de artículos académicos en revistas de revisión de pares, entre otros."*

**Nota:** el formulario distingue **divulgación** (público no especializado) de **difusión** (público académico). En nuestra propuesta, el webinar Red LATE + reporte ejecutivo policy van en *Divulgación*; el manuscrito sometido a revista y participación en conferencias van en *Difusión*.

---

### 4.10 RESUMEN PUBLICABLE

| # | Pregunta | Tipo | Límite | Obligatorio |
|---|----------|------|--------|-------------|
| 1 | **Resumen en español** | Textarea | **300 palabras** | Sí |
| 2 | **Resumen en inglés** | Textarea | **300 palabras** | Sí |

**Funcionalidades de IA del formulario:**
- Botón **"GENERAR RESUMEN CON IA"** disponible para el español
- Botón **"TRADUCIR CON IA"** disponible para generar el inglés desde el español

**Texto de ayuda:**
> *"La información de este apartado será de carácter público y tendrá por objetivo difundir, a través del sitio web de ANII, y la web del Proyecto Fortalecimiento de las Capacidades Locales para Generar una Transformación Digital Educativa Sostenible y de Impacto en América Latina y el Caribe de Fundación Ceibal y otros medios, de qué trata el proyecto, a diferencia del resto del contenido del presente documento, que es de carácter confidencial. De esta manera invitamos a exponer los aspectos más relevantes de la propuesta a presentar en el marco de este instrumento puntual. Deberá resumir el proyecto haciendo foco en el problema abordado, objetivo general, impacto esperado, entre otros puntos que permitan visualizar la esencia del proyecto. Recuerde utilizar un lenguaje llano y claro."*

**Implicación crítica:** este resumen es **público**. Acá hay que cuidar especialmente el lenguaje sobre IP (no exponer cláusulas internas de background IP) y mantener un tono de divulgación.

---

## 5. PRESUPUESTO

*Sub-sección no mapeada directamente — el formulario bloquea la navegación hasta completar ORGANIZACIONES y RECURSOS HUMANOS. Estructura inferida desde las bases:*

### 5.1 PRESUPUESTO POR RUBRO

Tabla con desglose por rubro. Rubros disponibles según las bases:
- Materiales e insumos
- Equipamiento de laboratorio
- Otros equipos
- Consultores
- Capacitación
- Servicios
- Adecuación de infraestructura edilicia de pequeño porte
- Material bibliográfico
- Software
- Protección de la propiedad intelectual
- Promoción y difusión
- Divulgación
- Gastos de administración (máx 5%)
- Imprevistos (máx 5%)
- Personal técnico (máx 70%)
- Viajes y estadías
- Profesores visitantes
- Pasajes

**Topes y restricciones:**
- Personal técnico ≤ 70% del total
- Administración ≤ 5%
- Imprevistos ≤ 5%
- No financia: vehículos, terrenos
- Monto máximo: USD 50.000

### 5.2 TOTALES POR RUBRO

Probablemente vista consolidada de los totales (Monto ANII / Monto Otros / Monto total).

### 5.3 OTROS RECURSOS PARA LA REALIZACIÓN DEL PROYECTO

Probablemente sub-sección para declarar aportes en especie / valorización de recursos de las instituciones participantes (relevante si va universidad partner aportando IRB, infraestructura, equipo).

---

## 6. OTROS DATOS

*Sub-sección no mapeada directamente. Estructura inferida desde el menú:*

### 6.1 IMPACTO AMBIENTAL

Probablemente declaración de si el proyecto tiene impactos ambientales (probablemente NO, dado nuestro objeto de estudio).

### 6.2 ASPECTOS ÉTICOS

**Sub-sección crítica para nosotros.** Aquí va el aval del IRB (Comité de Ética) y la declaración de cumplimiento ético. Bases dicen: *"El proyecto deberá adjuntar el comprobante de presentación ante el Comité de Ética, en caso de que corresponda."* y *"La firma del contrato estará condicionada a la aprobación final del Comité de Ética cuando corresponda."*

Decisiones de la estrategia (ver doc maestro 9.1): la universidad partner aporta el IRB. La consulta clave del webinar ANII 12/05 incluía si IRB es obligatorio para estudios con docentes adultos voluntarios usando logs + autoreportes.

### 6.3 DATOS DE CONTACTO

Datos administrativos del responsable / proponente.

### 6.4 DATOS DE USO ADMINISTRATIVO

Probablemente datos para el seguimiento ANII (cuenta bancaria, exenciones fiscales, etc.).

---

## 7. DOCUMENTOS ADJUNTOS

*Sub-sección no mapeada directamente. Documentos típicos de ANII y de la convocatoria:*

- **CVUy de cada miembro del equipo** (obligatorio para todos los participantes)
- **Carta aval de institución proponente** (firma manuscrita o digital)
- **Cartas aval de instituciones participantes** (si las hay)
- **Comprobante de presentación ante Comité de Ética** (cuando corresponde)
- Posibles adjuntos opcionales: cartas de respaldo (MINERD, INDOTEL, BID-RD), reporte técnico Soy Digital, documentación IA Jam Sessions con Comfama, CVs académicos en formato extendido

---

## 8. ENCUESTA SATISFACCIÓN

Encuesta interna de ANII sobre la experiencia de postulación. No relacionada con la evaluación.

---

## 9. VALIDAR Y TERMINAR

Sub-sección de cierre. Recomendación explícita del formulario: ingresar a esta sección **a medida que se carga la postulación**, no solo al final, para verificar datos faltantes en cada ítem.

Al finalizar, se envía la postulación. **No hay modificaciones tras el cierre del llamado (11 jun 2026 14:00 GMT-3).**

---

## Notas operativas sobre el formulario

### Funcionalidades de IA disponibles

- **GENERAR RESUMEN CON IA** en RESUMEN PUBLICABLE (español)
- **TRADUCIR CON IA** en RESUMEN PUBLICABLE (inglés)

Útil para acelerar el cierre, pero el resumen es público y crítico — conviene **redactar manualmente la primera versión** y usar IA solo para pulir, no para generar desde cero.

### Idioma del formulario

Radio button al inicio: Español / English. Las bases admiten ambos. **Decisión recomendada: español**, dado que (a) RD es el país de implementación, (b) Fundación Ceibal y ANII operan en español, (c) el comité evaluador es regional ALC.

### Validaciones server-side observadas

El formulario bloquea navegación a secciones posteriores hasta que se complete:
- ÁREAS antes de SUB-EJE TEMÁTICO
- ORGANIZACIONES PARTICIPANTES (con al menos 1 institución proponente)
- RECURSOS HUMANOS (con al menos 1 responsable técnico-científico)

Implicación: cargar primero ÁREAS, ORGANIZACIONES y RECURSOS HUMANOS para desbloquear el resto.

### Botón GRABAR

Cada sub-sección con campos editables tiene un botón GRABAR al final. **No hay autoguardado** visible — hay que grabar manualmente antes de cambiar de sub-sección o se pierde lo escrito.

### Exportar en PDF

Disponible permanentemente en el menú superior. Útil para revisión externa, backup pre-cierre, o para imprimir el formulario completo como anexo de revisión.

---

## Mapeo a los criterios de evaluación ANII (40-20-20-20)

| Criterio | Peso | Sub-secciones del formulario que lo cubren |
|----------|------|--------------------------------------------|
| **1.1 Descripción y relevancia del problema (25%)** | 10% | 4.1 ANTECEDENTES (Antecedentes y justificación) |
| **1.2 Objetivos y resultados esperados (25%)** | 10% | 4.2 OBJETIVOS (Objetivo general + Objetivos específicos) |
| **1.3 Diseño de investigación y metodología (25%)** | 10% | 4.3 METODOLOGÍA |
| **1.4 Innovación, impactos y escalabilidad (25%)** | 10% | 4.5 INNOVACIÓN Y ESCALABILIDAD + 4.6 IMPACTOS ESPERADOS |
| **2. Presupuesto y otros recursos (20%)** | 20% | 5. PRESUPUESTO + 5.3 OTROS RECURSOS |
| **3. Capacidad del equipo (20%)** | 20% | 3. RECURSOS HUMANOS + CVs adjuntos + 4.1 (Antecedentes institucionales) |
| **4. Plan de trabajo (20%)** | 20% | 4.4 PLAN DE TRABAJO |
| **A.2 Antecedentes de la organización proponente (filtro eliminatorio)** | binario | 4.1 (Antecedentes institucionales) + 2. ORGANIZACIONES + cartas aval adjuntas |

**Otras sub-secciones que aportan transversalmente:**
- 4.7 OTRAS CONTRIBUCIONES Y RIESGOS — alimenta criterio 1.3 (mitigaciones) y 1.4 (contribuciones)
- 4.8 PROPIEDAD Y USO DE LOS RESULTADOS — alimenta criterio 1.4 (apropiación y uso)
- 4.9 ESTRATEGIA DE DIFUSIÓN Y DIVULGACIÓN — alimenta criterio 1.4 (escalabilidad) y outputs comprometidos
- 4.10 RESUMEN PUBLICABLE — público, criterio transversal de claridad

---

## Sugerencia de orden de redacción de la v2.0

Para que la redacción sea eficiente, sugerencia de orden basada en dependencias internas del formulario:

1. **DATOS GENERALES** (título, duración, país, palabras clave) — desbloquea PLAN DE TRABAJO
2. **ÁREAS** — desbloquea SUB-EJE TEMÁTICO
3. **SUB-EJE TEMÁTICO** — D.II principal + C secundaria
4. **ORGANIZACIONES PARTICIPANTES** — cargar proponente (escenario a definir) + participantes
5. **RECURSOS HUMANOS** — cargar Berenice como responsable técnico-científico + resto del equipo
6. **4.1 ANTECEDENTES** (1.000 palabras totales) — pieza pesada
7. **4.2 OBJETIVOS** (250 palabras + tabla)
8. **4.3 METODOLOGÍA** (500 palabras) — pieza pesada
9. **4.4 PLAN DE TRABAJO** (tabla)
10. **4.5 INNOVACIÓN Y ESCALABILIDAD** (1.300 palabras totales) — pieza pesada
11. **4.6 IMPACTOS ESPERADOS** (tabla)
12. **4.7 OTRAS CONTRIBUCIONES Y RIESGOS** (600 palabras totales)
13. **4.8 PROPIEDAD Y USO DE LOS RESULTADOS** (tabla — donde se materializa la estrategia background/foreground)
14. **4.9 ESTRATEGIA DE DIFUSIÓN Y DIVULGACIÓN** (400 palabras totales)
15. **4.10 RESUMEN PUBLICABLE** (600 palabras totales) — escribir AL FINAL, cuando el resto esté pulido
16. **5. PRESUPUESTO**
17. **6. OTROS DATOS** (Impacto ambiental, Aspectos éticos, Datos de contacto, Datos administrativos)
18. **7. DOCUMENTOS ADJUNTOS**
19. **9. VALIDAR Y TERMINAR**

---

## Pendientes de mapear

Estos sub-pasos no se pudieron capturar directamente porque el formulario los bloquea hasta completar los pasos previos. Cuando se carguen los datos mínimos (al menos 1 institución proponente + 1 responsable técnico-científico), se podrá hacer una segunda pasada para mapear:

- 1.3 SUB-EJE TEMÁTICO (estructura exacta del selector de líneas A/B/C/D)
- 5.1 PRESUPUESTO POR RUBRO (campos por rubro, si hay campos narrativos asociados)
- 5.2 TOTALES POR RUBRO
- 5.3 OTROS RECURSOS PARA LA REALIZACIÓN DEL PROYECTO (¿hay campo narrativo aquí?)
- 6.1 IMPACTO AMBIENTAL (qué preguntas, qué selects)
- 6.2 ASPECTOS ÉTICOS (qué declaración, qué adjuntos, palabras requeridas)
- 6.3 DATOS DE CONTACTO
- 6.4 DATOS DE USO ADMINISTRATIVO
- 7. DOCUMENTOS ADJUNTOS (lista exacta de documentos esperados, formatos y tamaños)
- 8. ENCUESTA SATISFACCIÓN
- 9. VALIDAR Y TERMINAR (qué validaciones automáticas)

Las celdas internas de las **4 tablas dinámicas** (Objetivos específicos, Plan de trabajo, Impactos esperados, Propiedad y uso de los resultados) tampoco se capturaron — al clickear AGREGAR aparece un modal o expansión con campos adicionales. Se puede mapear haciendo una segunda pasada con datos de prueba.

---

*Documento de mapa del formulario · Versión 1.0 · 13 may 2026 · Capturado por extracción directa del formulario online ANII*
