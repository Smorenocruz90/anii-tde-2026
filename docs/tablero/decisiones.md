# Decisiones

!!! abstract "Log de decisiones del proyecto"
    Registro de decisiones tomadas y pendientes. Cada decisión incluye: contexto, decisor responsable, plazo, consecuencias de no decidir, y resolución cuando aplica.

## Decisiones pendientes (6)

### 🔴 D-001 · Universidad partner

| Atributo | Valor |
|----------|-------|
| **Decisor** | Sebas + Berenice (acuerdo conjunto) |
| **Plazo** | 27 may 2026 |
| **Contexto** | Sin universidad partner confirmada no hay IRB, no hay honest broker, no hay coautoría académica, y posiblemente falla el filtro A.2 (eliminatorio binario). |
| **Opciones** | (a) PUCMM · (b) INTEC · (c) UASD · (d) Universidad regional · (e) Otra |
| **Si no se decide** | El proyecto no puede submitirse de manera competitiva. Hay que activar Plan B inmediatamente (otra institución o IRB independiente). |
| **Status** | <span class="badge badge-blocked">BLOCKED</span> En gestión |

### 🔴 D-002 · Alcance del honest broker

| Atributo | Valor |
|----------|-------|
| **Decisor** | Berenice + Sebas |
| **Plazo** | 27 may 2026 |
| **Contexto** | El panel de revisión señaló que la mitigación actual cubre análisis pero NO diseño. ¿La universidad partner ejecuta solo análisis o también firma design lock del itinerario y categorías? |
| **Opciones** | (a) Solo análisis (como está en v2.0) · (b) Análisis + design lock universidad · (c) Análisis + comité asesor externo de 3 expertos no afiliados |
| **Si no se decide** | El revisor adversarial lee la propuesta como "validación del propio producto", lo cual determina probablemente la decisión final. |
| **Status** | <span class="badge badge-todo">TODO</span> |

### 🔴 D-003 · Plan analítico — LCA o perfiles latentes simples

| Atributo | Valor |
|----------|-------|
| **Decisor** | Berenice |
| **Plazo** | 31 may 2026 |
| **Contexto** | LCA con 3-5 clases sobre N final ≈80 produce evidencia inestable (literatura recomienda N≥300). El OE1 entero descansa sobre esto. |
| **Opciones** | (a) Mantener LCA con 3 clases máx + reporte exploratorio · (b) Pivotar a taxonomía a priori + perfiles latentes simples 2-3 clases · (c) Diferir LCA a fase 2 + análisis descriptivo |
| **Si no se decide** | El revisor metodológico identifica en 5 minutos que LCA con N=80 no produce evidencia interpretable. |
| **Status** | <span class="badge badge-todo">TODO</span> |

### 🔴 D-004 · Sección 5 Presupuesto

| Atributo | Valor |
|----------|-------|
| **Decisor** | Sebas (con input de Agus, Steven, Berenice) |
| **Plazo** | 31 may 2026 |
| **Contexto** | El formulario ANII requiere desglose con topes (personal técnico ≤70%, admin ≤5%, imprevistos ≤5%, sin vehículos/terrenos). Sin esto la propuesta se lee como inmadura. |
| **Sub-decisiones** | Modalidad junior (servicios profesionales vs nómina) · Honest broker (billable vs in-kind) · Software LCA (Mplus vs poLCA gratis) · APC manuscrito (revista pagar vs gratuita) |
| **Si no se decide** | ANII no procesa la postulación sin presupuesto detallado. |
| **Status** | <span class="badge badge-todo">TODO</span> |

### 🔴 D-005 · Plan de Trabajo Gantt detallado

| Atributo | Valor |
|----------|-------|
| **Decisor** | Sebas (con Berenice) |
| **Plazo** | 3 jun 2026 |
| **Contexto** | El panel identificó M1 (oct 2026) sobrecargado (5 actividades en 30 días), receso escolar dominicano impacta M3-M5, M7-M9 carga 6 entregables que requieren 5-6 meses. |
| **Sub-decisiones** | ¿Adelantar IRB y panel Tschannen-Moran a M0 pre-grant? · ¿Diferir webinar y reporte policy a post-cierre? · ¿Manuscrito sometido o preprint depositado como compromiso de cierre? |
| **Si no se decide** | Cronograma promete más de lo ejecutable; algún entregable se cae durante ejecución. |
| **Status** | <span class="badge badge-todo">TODO</span> |

### 🟡 D-006 · Tschannen-Moran adaptada a IA o versión general

| Atributo | Valor |
|----------|-------|
| **Decisor** | Berenice |
| **Plazo** | 27 may 2026 |
| **Contexto** | La adaptación de la escala al dominio de uso pedagógico de IA requiere panel de expertos en M1 + reporte de propiedades psicométricas. La versión general es más conservadora pero mide autoeficacia general, no específica a IA. |
| **Opciones** | (a) Adaptada con panel de expertos (panel USD 1.000-1.500, requiere M1) · (b) Versión general sin adaptar (más rápido, menos específico) · (c) Adaptada + reporte como sub-objetivo metodológico |
| **Si no se decide** | El revisor pregunta dónde está la versión adaptada o cuestiona la validez del instrumento. |
| **Status** | <span class="badge badge-todo">TODO</span> |

---

## Decisiones tomadas (8)

### ✅ D-T01 · Reformulación pregunta principal y sub-preguntas

| Atributo | Valor |
|----------|-------|
| **Decisor** | Berenice (con Sebas) |
| **Fecha** | 13 may 2026 |
| **Decisión** | Pregunta principal con un solo objeto (tipologías de intervención) + 2 sub-preguntas (asociación con autoeficacia/motivación · evidencia de transferencia). SP3 sobre SJT-POV eliminada. |
| **Justificación** | Resuelve obs. 1 (pregunta compuesta) + obs. 13 (lenguaje no causal) + obs. 4 (SJT como exploratoria) sin elevar el SJT a sub-pregunta principal. |
| **Pre-mortem ejecutado** | Sí, 3 escenarios evaluados con probabilidad de éxito |

### ✅ D-T02 · "Documento metodológico abierto" en vez de "protocolo replicable"

| Atributo | Valor |
|----------|-------|
| **Decisor** | Sebas + Berenice |
| **Fecha** | 13 may 2026 |
| **Decisión** | OE5 reformulado a "documento metodológico abierto bajo CC-BY que describe el protocolo aplicado" en lugar de "protocolo replicable". |
| **Justificación** | Evita sobre-prometer escalabilidad. Más conservador metodológicamente. |

### ✅ D-T03 · "Autonomía digital" reemplaza "soberanía digital"

| Atributo | Valor |
|----------|-------|
| **Decisor** | Sebas |
| **Fecha** | 13 may 2026 |
| **Decisión** | Cambio de "soberanía digital docente" a "autonomía y agencia docente" como marco-paraguas. |
| **Justificación** | Menos ambicioso conceptualmente, más enfocado en competencias. Alineado con vocabulario real del TTF UNESCO 2025. |

### ✅ D-T04 · Cita Teacher Task Force UNESCO 2025

| Atributo | Valor |
|----------|-------|
| **Decisor** | Sebas |
| **Fecha** | 13 may 2026 |
| **Decisión** | Citar el position paper "Promoting and protecting teacher agency in the age of artificial intelligence" (Sept 2025) en su sentido real: marco de autonomía y agencia, no específicamente de "metacognición profesional". |
| **Justificación** | El claim original sobre TTF no era preciso. Verificado vía WebSearch. |

### ✅ D-T05 · Sub-muestra cualitativa N=18

| Atributo | Valor |
|----------|-------|
| **Decisor** | Berenice |
| **Fecha** | v1.1 (mantenido en v2.0) |
| **Decisión** | N=18 entrevistas semiestructuradas, ~2 por tipología emergente |
| **Nota** | El panel /review-grant señaló lógica circular y aritmética inconsistente. **Sujeta a re-decisión** vinculada a D-003. |

### ✅ D-T06 · Versionado del bundle pedagógico

| Atributo | Valor |
|----------|-------|
| **Decisor** | Agus + Steven |
| **Fecha** | 06 may 2026 |
| **Decisión** | El estudio ANII corre sobre Criter Notebook Engine v2.0 + Curso IA v2.0 + SJT-POV v2.0 con ADR auditable. Versiones v3+ pueden coexistir para otros cursos sin contaminar el estudio. |
| **Estado** | ADR borrador pendiente (Steven, 31 may). |

### ✅ D-T07 · Línea principal D.II + secundaria C

| Atributo | Valor |
|----------|-------|
| **Decisor** | Equipo |
| **Fecha** | v1.0 |
| **Decisión** | D.II (Metodologías de difusión y acceso) como principal, C (Mecanismos de participación docente) como secundaria. |
| **Justificación** | El cuaderno digital + log de eventos calzan en D.II sin forzar el ajuste. C suma puntaje en criterio 1.2. |

### ✅ D-T08 · 17 observaciones del revisor v1.1 integradas

| Atributo | Valor |
|----------|-------|
| **Decisor** | Equipo |
| **Fecha** | 13 may 2026 |
| **Decisión** | Las 17 obs abordadas en v2.0 con trazabilidad explícita a sección donde se resuelve. |
| **Ver** | [Cobertura completa →](../academico/feedback-revisor.md) |

---

## Plantilla para nuevas decisiones

Cuando se tome una decisión nueva, agregar una entrada con esta estructura:

```markdown
### D-XXX · Título corto descriptivo

| Atributo | Valor |
|----------|-------|
| **Decisor** | Quien decide (puede ser conjunto) |
| **Plazo** | Fecha límite si pendiente / fecha de toma si decidida |
| **Contexto** | Por qué importa esta decisión |
| **Opciones** | Lista de opciones consideradas |
| **Si no se decide** | Consecuencias de no decidir |
| **Status** | TODO / DOING / DONE / BLOCKED |
```

---

[:material-arrow-up-circle: Volver al tablero](index.md){ .md-button .md-button--primary }
