# Marco conceptual y arquitectura de Criter Academy

**Arquetipos, competencias y Labeling Cognitivo en una arquitectura de tres niveles**

> Documento interno · v2 · Mayo 2026

---

## Índice

- [Resumen ejecutivo](#resumen-ejecutivo)
- [Para qué sirve este documento](#para-qué-sirve-este-documento)
- [1. Diagnóstico y tesis](#1-diagnóstico-y-tesis)
- [2. Arquitectura macro-meso-micro](#2-arquitectura-macro-meso-micro)
- [3. Arquetipos pedagógicos](#3-arquetipos-pedagógicos)
- [4. Las trece competencias](#4-las-trece-competencias)
- [5. Labeling Cognitivo](#5-labeling-cognitivo)
- [6. El señalador](#6-el-señalador)
- [7. Next steps](#7-next-steps)
- [Marco bibliográfico de respaldo](#marco-bibliográfico-de-respaldo)

---

## Resumen ejecutivo

Criter Academy es una plataforma de formación docente para América Latina construida alrededor del notebook como artefacto central de intervención pedagógica. Este documento expone su marco conceptual y arquitectura: una articulación de tres niveles ontológicos —**arquetipo pedagógico (macro)**, **trece competencias (meso)** y **Labeling Cognitivo (micro)**— donde el nivel macro emerge del patrón estable del nivel meso y el nivel meso se ejercita en la operación cotidiana del nivel micro. La articulación es bidireccional. La operación micro es asistida por un agente de IA, **el señalador**, que opera bajo arquitectura de *machine teaching*: el docente etiqueta y escribe notas propias sobre el contenido; el señalador devuelve elaboración cognitiva diferenciada.

El documento distingue, en cada sección, entre el **diálogo con la tradición teórica** que respalda los principios del modelo y las **decisiones operativas propias** de Criter, declaradas como propuesta a sostener mediante validación ecológica longitudinal por uso real de la plataforma.

## Para qué sirve este documento

Este texto es de uso interno de Criter Academy. Sirve como:

- Instrumento de alineación conceptual del equipo
- Base para presentación a partners académicos y aliados regionales
- Insumo para la posterior elaboración de comunicaciones públicas (papers, whitepapers, materiales para inversores)

No reemplaza la documentación técnica del producto ni la documentación pedagógica de los cursos: las complementa al fijar el marco que las articula.

---

## 1. Diagnóstico y tesis

### 1.1 La brecha LatAm que origina el modelo

La transformación digital de los sistemas educativos latinoamericanos avanza con rapidez en su dimensión instrumental y se rezaga en su dimensión pedagógica. El primer **Diagnóstico Regional de Transformación Digital Educativa** (Fundación Ceibal e IDRC Canadá, 2026) evalúa la madurez de los sistemas educativos de la región en nueve pilares e identifica a la formación docente como uno de los dos ámbitos con peor desempeño regional (**2,39 sobre 4**); ocho de los nueve pilares evaluados se ubican en niveles bajos de madurez.

Marcos internacionales convergentes coinciden en diagnosticar la misma brecha: la masificación de programas de capacitación docente no se traduce automáticamente en transformación pedagógica del aula.

- UNESCO Teacher Task Force (2025)
- Brito, Parente y Mesquita (2025) — concepto de "profesor ampliado"
- Darling-Hammond et al. (2017) — formación docente efectiva

### 1.2 La tesis de Criter Academy

> **El docente no consume un curso: lo interviene.**

Esta es la tesis central del modelo. Si la formación docente tradicional opera bajo lógica de transmisión de contenido, Criter Academy desplaza el centro hacia la intervención sobre el contenido como condición de posibilidad del aprendizaje profesional. El **notebook** —artefacto central de la plataforma— es el dispositivo donde esa intervención se materializa: el docente lee, marca, comenta, dibuja sobre canvas, sube evidencia de su propia aula, comparte páginas específicas con sus pares. La intervención no es opcional ni decorativa: es la operación pedagógica fundamental.

Sobre esa operación, Criter construye un sistema de tres niveles articulados:
- **Arquetipos pedagógicos** (*quién es* el docente, su modo predominante de actuación)
- **Trece competencias** (*qué activa* en sus estudiantes)
- **Labeling Cognitivo** (*cómo opera* cotidianamente sobre el contenido)

El sistema funciona porque los tres niveles se articulan: el patrón micro de marcado revela el perfil meso de competencias, que al estabilizarse en el tiempo configura el arquetipo macro; en sentido inverso, el arquetipo identificado modula la personalización del entorno donde ocurre la próxima operación micro.

### 1.3 Sobre la palabra "situada"

Cuando este documento usa la expresión *formación docente situada*, la situación no se refiere a la modalidad de la plataforma —que es masivamente online, con elementos sincrónicos y eventualmente presenciales en programas anidados— sino a la operación cognitiva del docente al intervenir el contenido pensando en su aula real. Esto se alinea con el concepto de *situated cognition* (Brown, Collins & Duguid, 1989), que postula que el conocimiento se construye en contexto, no abstractamente. La intervención del notebook obliga al docente a contextualizar lo aprendido en su práctica propia, lo que ancla el aprendizaje sin requerir que la modalidad de entrega sea presencial o local.

El notebook puede vivir aislado como iniciativa individual del docente, o anidado en proyectos situados en sentido clásico (webinars, comunidades de práctica, programas institucionales con acompañamiento); en ambos casos la operación intervenida sigue siendo el motor del aprendizaje profesional.

---

## 2. Arquitectura macro-meso-micro

### 2.1 Diálogo con la tradición

La idea de organizar la formación profesional en niveles articulados tiene tradición sólida en la investigación educativa. La perspectiva sistémica (Bronfenbrenner, 1979) y la teoría de la actividad cultural-histórica (Engeström, 2001) han establecido que el desarrollo profesional ocurre en planos distintos que se afectan mutuamente. La literatura reciente sobre identidad profesional docente recoge esa intuición: Beijaard, Meijer y Verloop (2004) identifican cuatro rasgos esenciales de la identidad docente —proceso continuo, conexión con el contexto, sub-identidades en convivencia, agencia. Beauchamp y Thomas (2009) y la revisión sistemática reciente de Rushton (2023) confirman el consenso de que la identidad docente es dinámica, flexible e híbrida.

> **Nota terminológica.** Los términos macro / meso / micro se usan en este documento como dispositivo estructural inspirado en la tradición sociológica y la didáctica curricular, sin pretensión de equivalencia técnica con la teoría ecológica de Bronfenbrenner (donde el mesosistema refiere a las interacciones entre microsistemas, no a un nivel jerárquico intermedio).

### 2.2 Los tres niveles del modelo Criter

| Nivel | Pieza | Función | Modo de medición |
|---|---|---|---|
| **Macro** | Arquetipo pedagógico | Identidad pedagógica emergente: patrón estable de competencias dominantes que define el modo predominante de actuación del docente. | Test SJT inicial; recalibración longitudinal por uso del notebook. |
| **Meso** | Trece competencias | Capacidades que el docente activa en sus estudiantes, organizadas en cuatro dimensiones: Adentro, Aprendo, Construyo, Transformo. | Scoring acumulado a través del SJT y patrones de intervención. |
| **Micro** | Labeling Cognitivo | Operación cotidiana de marcado categorizado del contenido, con cuatro categorías: Recordar, Clarificar, Conectar, Cuestionar. | Patrones de marcado, comments y mini-canvas en el notebook. |

### 2.3 Bidireccionalidad del ciclo

La articulación es bidireccional.

- **En sentido ascendente**, los actos micro de marcado ejercitan competencias meso, que al acumularse producen el patrón estable que el sistema reconoce como arquetipo macro.
- **En sentido descendente**, el arquetipo identificado modula la personalización del entorno: los post-its de invitación, los retos sugeridos y el lenguaje de las preguntas se ajustan al modo predominante del docente. La modulación descendente no busca alterar la cognición del docente, sino aumentar la probabilidad de interacción y aporte —una pregunta que resuena con el estilo del docente tiene más chance de ser respondida; un reto alineado con su práctica tiene más chance de ser asumido.

### 2.4 Decisiones propias de la arquitectura

La asunción propia del modelo es triple:

1. Que es posible sostener una arquitectura de tres niveles sin que ninguno colapse en otro: el arquetipo no se reduce al perfil de competencias, las competencias no se reducen a los actos de labeling, y el labeling no se reduce a una proxy estadística del arquetipo.
2. Que el arquetipo emerge del patrón de competencias y no se impone a priori; ningún arquetipo es accesible sin un perfil correspondiente, y la transformación del perfil reorganiza el arquetipo.
3. Que la modulación descendente del arquetipo sobre el entorno es de orientación, no de manipulación: busca engagement, no behavior modification.

---

## 3. Arquetipos pedagógicos

### 3.1 Diálogo con la tradición

La idea de que existen modos pedagógicos estables y reconocibles tiene tradición sólida en la investigación educativa. Pratt y Collins (2011), con base en más de cien mil respondientes a su Teaching Perspectives Inventory, identifican cinco perspectivas dominantes —Transmission, Apprenticeship, Developmental, Nurturing y Social Reform— que organizan la práctica docente con consistencia psicométrica. Grasha (1996) propone una tipología paralela —Expert, Formal Authority, Personal Model, Facilitator, Delegator— centrada en la dimensión del control en el aula. El marco-paraguas teórico para esta intuición proviene de la literatura sobre identidad profesional docente: Beijaard et al. (2004), Beauchamp y Thomas (2009) y la revisión sistemática reciente de Rushton (2023) confirman que la identidad docente combina núcleos estables con apertura al cambio.

Sobre ese piso, Criter propone una taxonomía propia de nueve arquetipos. Cada uno se ancla en literatura específica cuando se interpreta por su significado pedagógico —no por su nombre.

### 3.2 Los nueve arquetipos y sus anclajes

| Arquetipo | Núcleo pedagógico | Anclaje en literatura |
|---|---|---|
| **Tejedor** | Vínculo, comunidad, pertenencia. El aula como red antes que como contenido. | Pratt — Nurturing; Noddings — Ethics of Care (1984, 1992); Hattie — teacher-student relationships (d=0,72); Walton & Cohen — belonging research. |
| **Explorador** | Curiosidad, asombro, expedición. Vivir en la pregunta. | Schwab (1960s) — fundador de Inquiry-Based Learning; Pratt — Developmental; Kashdan — Joyous Exploration en 5DC; Bonawitz et al. — pedagogía vs exploración; Greene — pedagogy of wonder. |
| **Arquitecto** | Diseño con intención, andamio, estructura que sostiene el pensamiento ajeno. | Wiggins & McTighe (1998, 2005) — Understanding by Design; Wood, Bruner & Ross (1976) — scaffolding; Gagné — Conditions of Learning; Bransford et al. — How People Learn. |
| **Catalizador** | Silencio activo, facilitación, emergencia del aprendizaje desde el grupo. | Rowe (1986) — Wait Time research, threshold de 2,7s y mejoras del 300-700%; Feuerstein — Mediated Learning Experience; Grasha — Facilitator y Delegator; Hiebert / Lampert — productive struggle. |
| **Narrador** | Storytelling, resonancia emocional, sentido. La metáfora que hace memorable. | Bruner (1986) — Narrative Mode of Thought (Actual Minds, Possible Worlds); Egan (1989) — Teaching as Storytelling; Damasio — emotional cognition; Schank — story-centered curriculum. |
| **Alquimista** | Transmutación pedagógica de recursos. Innovación constante, pensamiento divergente. | Csikszentmihalyi (1996) — Creativity: Flow and the Psychology of Discovery; Robinson — divergent thinking en educación; Guilford — divergent thinking original; de Bono — lateral thinking. |
| **Guía** | Visión larga, autonomía real, aprender a aprender. | Knowles — Self-Directed Learning y andragogy; Zimmerman — Self-Regulated Learning; Pratt — Nurturing y Apprenticeship; Hattie — teaching learning to learn strategies. |
| **Maker** | Manos que piensan, prototipado, agencia. Del consumidor al creador. | Papert (1980, 1991) — Constructionism (Mindstorms); Resnick — Lifelong Kindergarten; Dewey — learning by doing; Kolb — experiential learning cycle. |
| **Sanador** | Bienestar como condición de posibilidad del aprendizaje. Lectura emocional del aula. | Pratt — Nurturing (anclaje directo); Noddings — Ethics of Care; CASEL — los cinco competence areas; trauma-informed teaching; Seligman — Positive Education. |

> **Lectura.** Cada arquetipo dialoga con literatura específica cuando se lo interpreta por su núcleo pedagógico. Maker = Constructionism (Papert) y Arquitecto = Understanding by Design (Wiggins & McTighe) son los anclajes más directos; Tejedor, Sanador, Narrador, Maker, Guía y Catalizador tienen anclaje fuerte; Explorador y Alquimista tienen anclaje sólido aunque más distribuido entre varios autores.

### 3.3 Decisiones propias de Criter sobre los arquetipos

Tres decisiones del modelo no se desprenden directamente de la literatura y son específicas de Criter:

1. **Granularidad de nueve arquetipos** —en lugar de cinco, como en Pratt o Grasha— responde a la decisión de capturar la heterogeneidad pedagógica regional con resolución más fina.
2. **Concepción emergente** —según la cual el arquetipo no es una esencia sino un patrón que surge del perfil de competencias dominantes— evita el tipologismo rígido y permite la transformación arquetipal por desarrollo competencial.
3. **Lenguaje arquetipal** —Tejedor, Alquimista, Sanador— funciona como dispositivo de reconocimiento y orgullo profesional, no como etiqueta técnica; la eficacia simbólica del nombre forma parte del diseño y se valida por el modo en que los docentes se identifican con su arquetipo.

---

## 4. Las trece competencias

### 4.1 Diálogo con la tradición

Las trece competencias del modelo Criter describen capacidades que el docente activa en sus estudiantes —no capacidades que el docente posee sobre el contenido. Esta inversión es deliberada y se inscribe en la tradición de la enseñanza poderosa de Maggio (2012, 2018, 2022) y la evaluación significativa de Anijovich (2010): el aprendizaje se mide en el efecto producido sobre el sujeto que aprende. Cada competencia tiene, en consecuencia, un doble anclaje:

- Marcos que describen la **capacidad esperada en el estudiante**
- Marcos que describen la **capacidad correspondiente del docente** que la activa

Los marcos consultados incluyen:
- OECD Learning Compass 2030 (student agency, transformative competencies)
- Partnership for 21st Century Learning con sus 4Cs
- CASEL Framework con sus cinco competencias socioemocionales
- DigCompEdu europeo (Redecker, 2017) con sus 22 competencias docentes en seis áreas
- UNESCO ICT-CFT v3 (2018) con sus 18 competencias TIC
- InTASC Model Core Teaching Standards del CCSSO (2013)
- Tuning Latinoamérica para educación (2007, 2014)

A esto se suma literatura especializada sobre componentes específicos: Bandura (1997) y Tschannen-Moran y Woolfolk Hoy (2001) sobre teacher self-efficacy; Beltman, Mansfield y Price (2011) sobre teacher resilience; Kashdan y colaboradores sobre curiosity; Alexander (2008, 2020) sobre dialogic teaching; Damon (2008) sobre purpose; Deci y Ryan sobre Self-Determination Theory.

### 4.2 Anclaje doble por competencia

| Competencia | Anclaje en aprendizaje estudiantil | Anclaje en competencia docente |
|---|---|---|
| **A1 Bienestar** | CASEL — Self-management; OECD LC2030 — wellbeing | Beltman, Mansfield & Price (2011) — teacher wellbeing |
| **A2 Autoconfianza** | CASEL — Self-awareness | Bandura (1997); Tschannen-Moran & Woolfolk Hoy (2001) — TSES |
| **A3 Curiosidad** | Kashdan et al. — 5DC; OECD LC2030 — curiosity | Curiosity in teacher inquiry research |
| **A4 Resiliencia** | Masten — resilience research | Beltman, Mansfield & Price (2011); Mansfield et al. — teacher resilience framework |
| **B1 Autonomía** | Deci & Ryan — Self-Determination Theory; OECD LC2030 — student agency | InTASC Standard #1 — Learner Development |
| **B2 Criterio** | P21 4Cs — Critical Thinking; Facione | InTASC Standards #4 y #5 — Content Knowledge & Application |
| **B3 Adaptabilidad tecnológica** | UNESCO ICT-CFT v3 (2018) — perspectiva estudiantil | DigCompEdu (Redecker, 2017); TPACK (Mishra & Koehler, 2006) |
| **C1 Vínculos** | CASEL — Relationship skills | InTASC #2 y #3; Hattie — teacher-student relationship (d=0,72) |
| **C2 Colaboración** | P21 4Cs — Collaboration; ATC21S — collaborative problem-solving | InTASC Standard #10 — Leadership and Collaboration |
| **C3 Diálogo** | Alexander (2020) — Dialogic Teaching (validado por EEF); P21 — Communication | Freire — diálogo pedagógico |
| **D1 Propósito** | Damon (2008) — Path to Purpose; OECD LC2030 — anticipation | Frankl — logotherapy aplicado a vocación docente |
| **D2 Agencia** | OECD LC2030 — Student Agency; Engle & Conant — productive disciplinary engagement | Bandura — agency in social cognitive theory |
| **D3 Legado** | UNESCO — Education for Sustainable Development | Civic engagement education research; Damon — purpose como contribución |

### 4.3 Decisiones propias del modelo

La organización de las trece competencias en cuatro dimensiones —**Adentro, Aprendo, Construyo, Transformo**— y la decisión teórica de definirlas como capacidades que el docente activa en sus estudiantes son específicas de Criter y no se encuentran replicadas literalmente en los marcos consultados. La elección de trece competencias —y no doce, ni quince— responde a un criterio de exhaustividad práctica: cubrir el espacio del desarrollo docente con un número manejable de unidades discriminables. Estas tres decisiones son sostenibles teóricamente y a la vez requieren la validación ecológica que se describe en la sección 7.

---

## 5. Labeling Cognitivo

### 5.1 De Adler a las cuatro categorías

En 1940, Mortimer Adler escribió un ensayo breve y rotundo: *How to Mark a Book*. Su tesis era simple. Quien lee de verdad un libro lo marca; el marcado es la huella material de un pensamiento que se vuelve activo. Y el marcado, sostenía Adler, expresa cuatro funciones distinguibles: acuerdo, desacuerdo, clarificación e inquiry. Ochenta y cinco años después, esa tipología sobrevive porque mapea funciones cognitivas que la investigación posterior fue confirmando. **El Labeling Cognitivo de Criter Academy retoma a Adler en ese punto: marcar es categorizar, y categorizar es pensar.**

Catherine Marshall (1997, 1998) sistematizó el campo de la annotation theory, mostrando que las anotaciones tienen propósitos discretos y distinguibles. Cui (2024), en una validación reciente con cientos de estudiantes universitarios, confirma empíricamente que los sistemas de annotation con tagging mejoran engagement, comprensión y pensamiento crítico.

Pero hay un dato incómodo que Dunlosky y colaboradores (2013) establecieron en la revisión más citada sobre estrategias de aprendizaje: **el highlighting solo —marcar sin elaborar— tiene utilidad cognitiva baja**. Lo que sí funciona es *elaborative interrogation*: convertir el marcado en una pregunta o explicación que obliga a comprometer el conocimiento previo con lo leído. Hattan, Alexander y Lupo (2024), en una meta-revisión publicada en Review of Educational Research, confirman que la activación de saberes previos —y especialmente el reconocimiento de discrepancias entre conocimiento y texto— es una de las estrategias con mayor efecto sobre la comprensión profunda.

### 5.2 Las cuatro categorías

Las cuatro categorías de Labeling Cognitivo de Criter —**Recordar, Clarificar, Conectar, Cuestionar**— son cuatro funciones cognitivas distinguibles, cada una con anclaje en la tradición.

- **Recordar**: corresponde al *underlining* de Adler y al *procedural signaling* de Marshall.
- **Clarificar**: es la categoría de *clarifying* que Palincsar y Brown (1984) identificaron como una de las cuatro estrategias clave de Reciprocal Teaching, con efectos moderados consistentes en meta-análisis recientes (Khan et al., 2025: Cohen's d entre 0,42 y 0,47).
- **Conectar**: es la generatividad —el *inquiry* de Adler, el *predicting* de Reciprocal Teaching, la elaboración productiva.
- **Cuestionar**: es la categoría con mayor potencia cognitiva: corresponde al *disagreement* de Adler y al *productive disciplinary engagement* de Engle y Conant (2002), donde el desacuerdo autorizado dispara la reestructuración del esquema mental.

### 5.3 La nota propia del docente

Sobre cualquier resaltado, el docente puede agregar una nota propia —en texto o en voz transcrita— que explica su marcado. La nota es una pieza arquitectónica de Criter, no un agregado opcional: convierte la etiqueta —una señal pobre— en etiqueta más lenguaje natural del docente —una señal rica.

La nota propia es input del señalador (Sección 6), y es lo que ubica al sistema en régimen de **machine teaching** (Mosqueira-Rey et al., 2023): el docente experto guía la elaboración del agente con instrucciones específicas en lenguaje propio, no solo con etiquetas categóricas.

> Esta secuencia —**etiqueta humana primero, nota humana segundo, respuesta del agente tercero**— es la diferenciación arquitectónica de Criter respecto de productos AI-led.

---

## 6. El señalador

### 6.1 Qué es el señalador

**El señalador es un dashboard inteligente sobre las labels del docente, integrado al notebook como persiana lateral.** No es un chat. No es un asistente conversacional al que el docente le hace preguntas. Es un panel donde la IA organiza y devuelve insights sobre las marcas que el docente ya hizo, con secciones diferenciadas por categoría.

Su función pedagógica es operar como retroalimentación formativa con IA en el sentido de Anijovich (2010): información oportuna, descriptiva, orientada a la mejora, no calificadora, que sostiene la autonomía del docente.

### 6.2 Cómo se accede y qué muestra

El docente accede al señalador haciendo clic en un botón persistente en el notebook. Al activarlo, se despliega la persiana lateral. Adentro, los insights aparecen organizados por categoría y por unidad de contenido (página o secuencia), con secciones colapsables. La interacción del docente con la persiana es de **exploración** —abrir, leer, marcar como útil o descartar— **no de conversación**. Si necesita extender una respuesta, lo hace agregando una nota nueva al resaltado correspondiente; el señalador la incorpora como contexto y refina su devolución.

**Boceto del contenido por categoría (a refinar con producto):**

- **Recordar — síntesis y memoria.** Resumen de los puntos importantes durante la lectura ("lo más importante de esta hoja es..."); síntesis al final del cuaderno; sugerencia de cómo integrar lo retenido a la planificación de aula.
- **Clarificar — resolución y aclaración.** Aclaración breve en lenguaje cotidiano sobre los conceptos marcados; ejemplos concretos; opción de profundizar; respuesta sensible a la nota del docente.
- **Conectar — ideas para llevar a la práctica.** Profundización de la idea propia del docente a partir de su nota; recursos relacionados; sugerencias concretas de cómo trasladar la inspiración al aula; pregunta provocadora para extender la conexión.
- **Cuestionar — contraargumentos y diálogo crítico.** Argumentos posibles a favor y en contra de la posición del docente; autores que sostienen el disenso; validación pedagógica del desacuerdo; recursos para profundizar en la posición.

### 6.3 Respuesta del señalador por categoría — cuadro síntesis

| Categoría | Función cognitiva | Anclaje teórico | Sección del señalador |
|---|---|---|---|
| **Recordar** | Memoria; importancia; retorno deliberado. | Adler — underlining; Marshall — procedural signaling. | Síntesis durante la lectura ("lo más importante de esta hoja es...") y al final del cuaderno; sugerencia de integración a planificación. |
| **Clarificar** | Confusión; falta de comprensión; señal de no entender. | Adler — doubt; Palincsar & Brown — clarifying. | Aclaración breve en lenguaje cotidiano; ejemplo concreto; opción de ampliar; respuesta sensible a la nota del docente. |
| **Conectar** | Generatividad; idea propia; conexión con conocimiento previo. | Adler — inquiry; Palincsar & Brown — predicting; Hattan et al. — saberes previos. | Profundización de la idea propia (a partir de la nota); recursos relacionados; sugerencias para llevar al aula; pregunta provocadora. |
| **Cuestionar** | Disenso; contradicción; reestructuración cognitiva. | Adler — disagreement; Ausubel — saberes previos; Engle & Conant — productive disagreement. | Contraargumentos posibles; autores que sostienen el disenso; validación pedagógica del desacuerdo; recurso para profundizar. |

### 6.4 La paradoja cognitiva de la IA, resuelta por arquitectura

Literatura emergente (Frontiers, 2025) advierte sobre una **paradoja cognitiva** en el uso de IA en educación: cuando los aprendices reciben respuestas autogeneradas y las aceptan pasivamente, el engagement crítico se reduce en lugar de aumentar.

**Criter resuelve esta paradoja por arquitectura, no por buena intención**: el docente etiqueta primero, escribe su nota propia segundo, y el señalador responde tercero. La intervención humana precede al feedback de la máquina, lo cual ubica al modelo en machine teaching y no en sistemas AI-led. El docente es el operador, no el operado.

La opción deliberada de no hacer al señalador conversacional —**no es un chat, es un dashboard**— refuerza esta arquitectura: el docente no le pide cosas a la IA, la IA elabora sobre lo que el docente ya hizo.

---

## 7. Next steps

La validación del modelo está organizada en tres frentes complementarios. Los frentes 7.1 y 7.2 corresponden a desarrollo y mejora continua del producto. El frente 7.3 —**validación ecológica longitudinal por uso real**— es la apuesta metodológica diferenciadora del proyecto.

### 7.1 Maduración del Test de Superpoderes

Validar psicométricamente el Test SJT como instrumento de identificación de arquetipos y medición de competencias.

- **Métricas:** alpha de Cronbach por dimensión, consistencia inter-escenarios, validez convergente con autorreporte, estabilidad test-retest.
- **Referencia comparativa:** TRUST Test (Vesely-Maillefer y Schoeps, 2020), que reporta alpha entre 0,74 y 0,84.
- **Tamaño piloto sugerido:** n ≥ 200 docentes con representación regional.
- **Plazo:** primer semestre de uso operativo.

### 7.2 Maduración del señalador

Iterar el comportamiento del señalador por categoría a partir de los logs de uso real.

- **Métricas:** pertinencia percibida por el docente (encuesta posterior a la respuesta), tasa de engagement con la respuesta del señalador (lectura completa, profundización, descarte), efecto sobre la profundidad de las notas posteriores del docente.
- **Comparación contra grupo control** con feedback genérico no diferenciado por categoría, una vez que la base instalada lo permita.

### 7.3 Validación ecológica longitudinal por uso real

> **El uso operativo del notebook es la validación del modelo.**

Esta es la apuesta metodológica más fuerte de Criter: en lugar de validar el modelo en experimentos artificiales aislados, lo validamos en su operación natural mediante datos longitudinales que capturan la transformación profesional en el tiempo. Hay precedente robusto para esta lógica: el Teaching Perspectives Inventory de Pratt se validó así con más de cien mil docentes a lo largo de dos décadas.

La validación ecológica de Criter se desarrolla en tres pilares articulados:

#### Pilar 1. Validación cruzada interna del modelo macro-meso-micro

Verificar que el patrón de marcado de un docente coincide con su perfil de competencias y arquetipo identificados por el SJT. Si la correspondencia es alta, los tres niveles del modelo son internamente consistentes; si es baja, alguno no está midiendo lo que dice medir y requiere corrección.

#### Pilar 2. Trayectoria de transformación arquetipal

Verificar que el desarrollo de competencias en los cursos correlaciona con cambios en el patrón de marcado del docente, en la dirección esperada por la modulación del arquetipo.

> **Ejemplo operativo:** un docente identificado inicialmente como Arquitecto que, tras transitar cursos sobre creación con tecnología y agencia áulica, deviene en Maker —y ese tránsito se refleja en su patrón de marcado (más Conectar, más uploads de evidencia, más comentarios sobre creación). Si esta correspondencia se observa en una muestra suficientemente grande de docentes, tenemos evidencia empírica de que el sistema captura transformación profesional real, no solo perfilamiento estático.

#### Pilar 3. Intra-annotator agreement como métrica de transformación

El estudio reciente de Hovy, Plank y Søgaard (2025) introduce el intra-annotator agreement como métrica de estabilidad del anotador a lo largo del tiempo. Aplicado a Criter: si el mismo docente marca el mismo párrafo distinto a tres y a seis meses, ese cambio es señal de desarrollo profesional, no de ruido. Esta métrica no requiere instrumentación adicional; se desprende del uso operativo del notebook.

#### Ventajas y limitaciones del enfoque

**Ventajas:**
- No requiere experimentos artificiales costosos
- Genera datos longitudinales por diseño
- La validación es subproducto del uso del producto, no un proyecto investigativo aparte

**Limitación principal:** presencia de confounders no controlados —el cambio del patrón puede deberse a varias causas concurrentes. Mitigable con tamaño de muestra grande y análisis multivariado.

#### Hipótesis derivada

Los párrafos que generan marcas distintas entre docentes de arquetipos distintos son los párrafos pedagógicamente más ricos, en cuanto operan como puntos de divergencia interpretativa productiva. Esta hipótesis se conecta con el concepto de *query by committee* del active learning (Settles, 2009, 2012) y, si se valida, ofrece una métrica de calidad del contenido por capacidad de generar diálogo entre tradiciones pedagógicas distintas.

### 7.4 Plan operativo de los próximos seis meses

> *(A completar con el equipo de Criter)*: hitos concretos, responsables, métricas de seguimiento por hito, criterios de pass / fail para cada uno de los tres pilares, calendario tentativo de revisión del marco conceptual en función de los hallazgos.

---

## Hipótesis falsables del modelo

Resumen de las hipótesis que el uso real debe poner a prueba.

| ID | Hipótesis | Métrica clave |
|---|---|---|
| **H1** | Patrones de Labeling Cognitivo se asocian sistemáticamente con perfil de competencias dominantes; docentes con perfiles distintos producen patrones de marcado significativamente distintos sobre el mismo contenido. | Análisis multivariado SJT × patrones de marcado. |
| **H2** | El arquetipo identificado por el SJT coincide, dentro de un margen estadísticamente aceptable, con el perfil emergente de los patrones de marcado en el notebook a lo largo del tiempo. | Correspondencia SJT inicial vs perfil emergente a 3 y 6 meses. |
| **H3** | La personalización por arquetipo aumenta la tasa de interacción del docente con el contenido del notebook (medida en marcados por hoja, frecuencia de comments, tasa de upload de evidencia, completion rate) sin alterar el contenido cognitivo de las marcas que produce. | A/B con personalización on/off; análisis de contenido de marcas. |
| **H4** | El sistema integrado mejora la transferencia al aula (medida con autorreporte y observación) por encima del baseline de capacitación tradicional. | Comparación cohorte Criter vs baseline regional. |
| **H5** | La nota propia se mantiene como práctica habitual del docente en el uso sostenido. | Tasa de notas propias por marca; sustantividad de notas. |

---

## Marco bibliográfico de respaldo

> *Listado en formato APA aproximado, ordenado alfabéticamente. A finalizar para versiones públicas del documento.*

- Adler, M. J. (1940). *How to Mark a Book*. The Saturday Review of Literature.
- Alexander, R. (2008). *Towards Dialogic Teaching: Rethinking Classroom Talk*. Dialogos.
- Alexander, R. (2020). *A Dialogic Teaching Companion*. Routledge.
- Anijovich, R. (Ed.). (2010). *La evaluación significativa*. Paidós.
- Ausubel, D. P. (1968). *Educational Psychology: A Cognitive View*. Holt, Rinehart and Winston.
- Bandura, A. (1997). *Self-efficacy: The exercise of control*. W.H. Freeman.
- Beauchamp, C., & Thomas, L. (2009). Understanding teacher identity. *Cambridge Journal of Education, 39*(2), 175-189.
- Beijaard, D., Meijer, P. C., & Verloop, N. (2004). Reconsidering research on teachers' professional identity. *Teaching and Teacher Education, 20*(2), 107-128.
- Beltman, S., Mansfield, C., & Price, A. (2011). Thriving not just surviving: A review of research on teacher resilience. *Educational Research Review, 6*(3), 185-207.
- Bonawitz, E. et al. (2011). The double-edged sword of pedagogy: Instruction limits spontaneous exploration and discovery. *Cognition*.
- Brito, R., Parente, C., & Mesquita, A. (2025). *El profesor ampliado: tránsitos en la formación docente*.
- Bronfenbrenner, U. (1979). *The ecology of human development*. Harvard University Press.
- Brown, J. S., Collins, A., & Duguid, P. (1989). Situated cognition and the culture of learning. *Educational Researcher, 18*(1), 32-42.
- Bruner, J. (1986). *Actual Minds, Possible Worlds*. Harvard University Press.
- CASEL (2020). *CASEL's SEL Framework*. Collaborative for Academic, Social, and Emotional Learning.
- CCSSO (2013). *InTASC Model Core Teaching Standards*. Council of Chief State School Officers.
- Csikszentmihalyi, M. (1996). *Creativity: Flow and the Psychology of Discovery and Invention*. HarperCollins.
- Cui, Y. et al. (2024). Empowering active learning: A social annotation tool for improving student engagement. *British Journal of Educational Technology*.
- Damon, W. (2008). *The Path to Purpose: Helping Our Children Find Their Calling in Life*. Free Press.
- Darling-Hammond, L., Hyler, M. E., & Gardner, M. (2017). *Effective Teacher Professional Development*. Learning Policy Institute.
- Deci, E. L., & Ryan, R. M. (2017). *Self-determination theory*. Guilford.
- Dunlosky, J. et al. (2013). Improving students' learning with effective learning techniques. *Psychological Science in the Public Interest, 14*(1), 4-58.
- Egan, K. (1989). *Teaching as Storytelling*. University of Chicago Press.
- Engeström, Y. (2001). Expansive learning at work. *Journal of Education and Work, 14*(1), 133-156.
- Engle, R. A., & Conant, F. R. (2002). Guiding principles for fostering productive disciplinary engagement. *Cognition and Instruction, 20*(4), 399-483.
- Feuerstein, R. (1980). *Instrumental Enrichment: An Intervention Program for Cognitive Modifiability*. University Park Press.
- Frontiers in Education (2025). The cognitive paradox of AI in education.
- Fundación Ceibal & IDRC Canadá (2026). *Diagnóstico Regional de Transformación Digital Educativa en América Latina*. Proyecto EdTech Initiative.
- Grasha, A. F. (1996). *Teaching with style*. Alliance Publishers.
- Hattan, C., Alexander, P. A., & Lupo, S. M. (2024). Leveraging What Students Know to Make Sense of Texts. *Review of Educational Research*.
- Hattie, J. (2009). *Visible Learning*. Routledge.
- Hovy, D., Plank, B., & Søgaard, A. (2025). Consistency is Key: Disentangling Label Variation in NLP with Intra-Annotator Agreement. arXiv:2301.10684.
- Hovy, E., & Lavid, J. (2010). Towards a science of corpus annotation. *International Journal of Translation, 22*(1), 13-36.
- Kashdan, T. B. et al. (2018). The Five-Dimensional Curiosity Scale. *Journal of Research in Personality*.
- Khan, S. et al. (2025). Examining Classroom Strategies: Reciprocal Teaching and its Effect on Reading Comprehension. *SAGE Open*.
- Klie, J.-C., Webber, B., & Gurevych, I. (2023). Analyzing Dataset Annotation Quality Management in the Wild. arXiv:2307.08153.
- Knowles, M. S. (1975). *Self-directed learning*. Association Press.
- Maggio, M. (2012). *Enriquecer la enseñanza*. Paidós.
- Maggio, M. (2018). *Reinventar la clase en la universidad*. Paidós.
- Maggio, M. (2022). *Híbrida*. Tilde Editora.
- Mansfield, C. F. et al. (2016). Building resilience in teacher education. *Teaching and Teacher Education*.
- Marshall, C. C. (1997). Annotation: from paper books to the digital library. *Proceedings of ACM Digital Libraries*.
- Marshall, C. C. (1998). Toward an ecology of hypertext annotation. *Proceedings of ACM Hypertext*.
- Mishra, P., & Koehler, M. J. (2006). Technological pedagogical content knowledge. *Teachers College Record, 108*(6), 1017-1054.
- Mosqueira-Rey, E. et al. (2023). Human-in-the-loop machine learning: a state of the art. *Artificial Intelligence Review, 56*(4), 3005-3054.
- Noddings, N. (1984). *Caring: A Feminine Approach to Ethics and Moral Education*. University of California Press.
- Noddings, N. (1992). *The Challenge to Care in Schools*. Teachers College Press.
- OECD (2019). *OECD Learning Compass 2030*. OECD Publishing.
- Palincsar, A. S., & Brown, A. L. (1984). Reciprocal teaching of comprehension-fostering and comprehension-monitoring activities. *Cognition and Instruction, 1*(2), 117-175.
- Papert, S. (1980). *Mindstorms: Children, Computers, and Powerful Ideas*. Basic Books.
- Papert, S., & Harel, I. (Eds.). (1991). *Constructionism*. Ablex.
- Partnership for 21st Century Learning (2019). *Framework for 21st Century Learning*. Battelle for Kids.
- Pratt, D. D., & Collins, J. B. (2011). The Teaching Perspectives Inventory at 10 Years and 100,000 Respondents. *Adult Education Quarterly, 61*(4).
- Redecker, C. (2017). *European Framework for the Digital Competence of Educators: DigCompEdu*. Joint Research Centre.
- Resnick, M. (2017). *Lifelong Kindergarten*. MIT Press.
- Robinson, K. (2011). *Out of Our Minds: Learning to Be Creative*. Capstone.
- Rowe, M. B. (1986). Wait Time: Slowing Down May Be A Way of Speeding Up. *Journal of Teacher Education, 37*(1), 43-50.
- Rushton, E. A. C. et al. (2023). Understanding teacher identity in teachers' professional lives: A systematic review. *Review of Education, 11*(2).
- Schwab, J. J. (1962). *The teaching of science as enquiry*. Harvard University Press.
- Settles, B. (2009). *Active Learning Literature Survey*. University of Wisconsin-Madison.
- Settles, B. (2012). *Active Learning*. Synthesis Lectures on AI and ML, 6(1).
- Star, S. L., & Griesemer, J. R. (1989). Institutional ecology, 'translations' and boundary objects. *Social Studies of Science, 19*(3), 387-420.
- Tschannen-Moran, M., & Woolfolk Hoy, A. (2001). Teacher efficacy: capturing an elusive construct. *Teaching and Teacher Education, 17*(7), 783-805.
- UNESCO (2018). *UNESCO ICT Competency Framework for Teachers, Version 3*.
- UNESCO Teacher Task Force (2025). *Reframing teacher agency in the AI era*.
- Vesely-Maillefer, A. K., & Schoeps, K. (2020). The TRUST Test: Validation studies. *Journal of Educational Measurement*.
- Wiggins, G., & McTighe, J. (2005). *Understanding by Design* (Expanded 2nd ed.). ASCD.
- Wood, D., Bruner, J., & Ross, G. (1976). The role of tutoring in problem solving. *Journal of Child Psychology and Psychiatry, 17*(2), 89-100.
- Zimmerman, B. J. (2000). Attaining self-regulation: A social cognitive perspective. In *Handbook of self-regulation*. Academic Press.

---

> Documento interno · Criter Academy · Mayo 2026
