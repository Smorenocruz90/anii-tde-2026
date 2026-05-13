# Metodología detallada

## Diseño general

**Mixto convergente longitudinal corto · 12 semanas · carácter exploratorio.**

- 1 semana de baseline + 10 semanas de itinerario formativo + 1 semana de cierre
- Sin hipótesis confirmatoria (el objeto no ha sido caracterizado previamente en docentes dominicanas)
- Itinerario anclado en el UNESCO AI Competency Framework for Teachers (2024)
- Triangulación entre tres fuentes evidenciales: log de comportamiento + autoinformes validados + narrativa cualitativa
- Pre-registro del protocolo en Open Science Framework antes de la recolección

## Muestra

| Parámetro | Valor |
|-----------|-------|
| N inicial proyectado | 120 docentes |
| Población objetivo | Docentes dominicanas activas en aula |
| Canal de reclutamiento | Sub-cohorte docente del programa nacional Soy Digital + canales MINERD |
| Marco legal | Consentimiento informado bajo Ley 172-13 RD (uso secundario habilitado) |
| Estratificación | Nivel educativo (inicial, primaria, secundaria) × zona (urbano-rural) = 6 celdas |
| Sobre-reclutamiento | 20% para mitigar mortalidad esperada 25-35% |
| N final estimado | ~80 |
| Sub-muestra cualitativa | N=18 (~2 por tipología emergente) para entrevistas semiestructuradas al cierre |

!!! danger "Crítica del panel: aritmética inconsistente"
    *120 + 20% = 144; 144 × (1 - 0,30) ≈ 100, no 80.* Hay que aclarar si el sobre-reclutamiento ya está incluido en los 120 o se suma.

## Instrumentos alineados al modelo de niveles

=== "Nivel 1-2 — Acceso e interacción"

    **Log de eventos del cuaderno digital** (`NotebookEvent`) que captura:

    - `chapter_opened`, `chapter_completed`
    - `session_started`
    - `page_shared`
    - `highlight_added` (con `phrase`, `blockId`, `category`)
    - `comment_added` (texto/audio/transcript)
    - `canvas_*_added` (postits, stickers, textbox, voice, drawing)

    Cada evento incluye: `type`, identificador anonimizado, momento, bloque sobre el que se opera, payload específico.

    **Aplicación:** continuo, semanas 1-10.

=== "Nivel 3 — Intervención reflexiva"

    - **Cuatro categorías de Labeling Cognitivo** (Recordar, Clarificar, Conectar, Cuestionar), mutuamente excluyentes en el momento del marcado, más una **nota propia** de la docente sobre cada marca
    - **Comments** (texto o voz transcrita)
    - **Mini-pizarra (InterventionCanvas)** con postits, stickers semánticos, cajas de texto, notas de voz, dibujos

    **Aplicación:** continuo, semanas 1-10.

=== "Nivel 4 — Transferencia al aula"

    - **Mini-retos quincenales** (5 retos) con artefactos del aula: foto, audio o descripción
    - **Encuesta de aplicación** estructurada al cierre
    - **Entrevistas semiestructuradas** en sub-muestra N=18

    **Aplicación:** mini-retos en sem 2, 4, 6, 8, 10; encuesta y entrevistas en semana 12 (cierre).

=== "Nivel 5 — Apropiación pedagógica"

    - **Escala Tschannen-Moran** de autoeficacia docente, con redacción adaptada al dominio de uso pedagógico de IA (revisión por panel de expertos en M1)
    - **Work Tasks Motivation Scale for Teachers** (Ryan & Deci) en pre y post
    - **Encuesta de continuidad** declarada al cierre

    **Aplicación:** pre (baseline) y post (cierre).

=== "Caracterización descriptiva de cohorte"

    - **SJT-POV de arquetipos** (16 ítems, 4 escenarios, ~7 minutos) al inicio
    - **NO** se usa como variable predictora — solo como caracterización descriptiva de la cohorte

## Plan analítico (versión actual — pendiente de re-calibración)

!!! warning "Pendiente decisión de Berenice antes del 31 may"
    El panel de revisión recomendó **pivotar de LCA a perfiles latentes simples** dado el N realista. Esta sección refleja el plan actual de la propuesta v2.0; la versión re-calibrada se incorporará a v2.1.

### Análisis cuantitativo

- **Latent Class Analysis** con 3 a 5 clases máximo sobre el log de intervención para extraer tipologías
- **Asociaciones bivariadas** entre tipologías y cambios pre-post en escalas (Tschannen-Moran, WTMS)
- **Estadísticos descriptivos** del SJT-POV

### Análisis cualitativo

- **Codificación temática inductiva** con doble codificación independiente y **kappa de Cohen** sobre comments y transcripciones de entrevistas
- **Matriz de triangulación** entre clústeres cuantitativos y narrativa cualitativa

### Pre-registro

- Protocolo de análisis depositado en **Open Science Framework** antes de la recolección
- Plan de contingencia según N final: ≥80 plan original; 60-80 reducir complejidad; <60 descriptivo puro

## Estrategias de mitigación de riesgos metodológicos

| Riesgo | Mitigación |
|--------|-----------|
| Mortalidad muestral (25-35% esperada) | Sobre-reclutamiento 20% + engagement por mini-retos quincenales + reformulación analítica si N<60 |
| Conflicto de interés (el cuaderno es producto de Critertec) | Universidad partner como honest broker para análisis sensibles + pre-registro + dataset anonimizado abierto post-publicación |
| Sesgo del canal Soy Digital (cohorte autoseleccionada) | Estratificación + reporte explícito contra población docente MINERD |
| Instrumentos no validados en cohorte dominicana | Reporte de propiedades observadas como exploratorio + panel de expertos para adaptación de escalas |
| Fallo técnico de la plataforma | Backup diario + protocolo offline de respaldo |
| Cambios al cuaderno durante "freeze" | Architecture Decision Record (ADR) firmado al inicio + versionado semántico + log de cambios menores no-pedagógicos |

→ El detalle metodológico completo está en [Propuesta completa → 4.3.1](propuesta-completa.md) y en `propuesta_v2_consolidada.md`.

---

[:material-arrow-right-circle: Sigue: Feedback del revisor v1.1](feedback-revisor.md){ .md-button .md-button--primary }
