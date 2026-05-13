# Steven

## Tu rol

**Investigador / Consultor · Data engineering · Captura del log observacional.**

Eres quien garantiza que el cuaderno digital efectivamente capture lo que la docente hace, lo persista de manera anonimizada y auditable, y lo entregue como dataset usable al honest broker para análisis. La integridad del dato pasa por ti.

## Lo que haces

### En la fase de postulación (mayo–junio 2026)

- **Documentar el Architecture Decision Record (ADR) del versionado** del bundle pedagógico (Criter Notebook Engine + curso + SJT-POV) — pieza clave para mitigar el conflicto de interés con auditoría externa
- **Validar técnicamente** la sección 4.5.1 del formulario (descripción del log, eventos, estructura de datos)
- **Estimar costos de infraestructura** para incluirlos en el presupuesto (storage cloud para 144 docentes × 10 semanas; backup; protocolo offline)

### En la fase de ejecución (oct 2026 – jun 2027)

- Lead técnico del despliegue de la versión inmutable del cuaderno
- Captura, persistencia y backup diario del log de eventos
- Anonimización certificada del dataset antes de entregarlo a la universidad partner
- Generación del documento de gobierno de datos (DMP) y del codebook
- Depósito del dataset en repositorio REDI / Fundación Ceibal con metadatos completos y DOI
- Apoyo al análisis cuantitativo si se requiere ingeniería sobre el log (limpieza, transformaciones)

## Lo que decides

| Decisión | Plazo | Estado |
|----------|-------|--------|
| Architecture Decision Record (ADR) del bundle versionado | 31 may 2026 | **Pendiente** |
| Estructura final del `NotebookEvent` log para investigación | 31 may 2026 | Decidido (revisar) |
| Protocolo de anonimización certificada (qué se hashea, qué se descarta) | M0 oct 2026 | Pendiente |
| Repositorio final del dataset (REDI vs Zenodo vs Harvard Dataverse) | M9 jun 2027 | Pendiente |
| Software de análisis para el honest broker (Mplus vs poLCA en R) | 31 may 2026 | Pendiente (consulta con Berenice) |

## Riesgos que dependen de ti

!!! danger "Gobernanza del freeze del bundle"
    Durante el estudio el cuaderno está "congelado" en versión inmutable. Si algo se rompe técnicamente (bug crítico, falla de seguridad), ¿quién autoriza un hotfix? ¿Cómo se documenta el cambio sin contaminar los datos del estudio?

    **Mitigación recomendada por el panel:** especificar quién autoriza hotfixes (tú + PI + honest broker), versionado semántico, log de cambios menores no-pedagógicos, ADR firmado al inicio del estudio.

!!! danger "Anonimización certificada"
    El consentimiento informado bajo Ley 172-13 RD habilita el uso secundario de datos para investigación PERO requiere anonimización certificada antes de cualquier transferencia. Si el dataset que entregas al honest broker no está bien anonimizado, hay riesgo legal y ético.

    **Mitigación:** protocolo escrito y auditado de anonimización antes del baseline (M2).

!!! warning "Plataforma-agnóstica vs background IP"
    La propuesta afirma que el dispositivo es "plataforma-agnóstico" en su lógica conceptual, pero el código del cuaderno se reserva como background IP de Critertec. Un revisor puede preguntar: si es agnóstico, ¿por qué no se libera el código? Si no se libera, ¿cuán agnóstico es?

    **Respuesta defendible:** el protocolo de observación (categorías + esquema de eventos + plan de análisis) es lo que se libera bajo CC-BY; la implementación específica de Critertec no es necesaria para reproducir el método — cualquier plataforma que implemente el mismo esquema de eventos puede aplicarlo. Tu rol: documentar el esquema de eventos de manera plataforma-independiente en el documento metodológico abierto.

## Lo que necesitamos de ti esta semana

1. **Borrador del ADR** del bundle versionado — pieza crítica para defensa del CoI
2. **Estimación de costos de infraestructura** (cloud storage, backup, dominio, plataforma de webinar) para que Sebas los incluya en presupuesto
3. **Validación técnica de la sección 4.5.1** — ¿la descripción del log es precisa? ¿faltan eventos? ¿hay riesgo de exposición de IP comercial en la descripción?
4. **Opinión sobre Mplus vs poLCA** — afecta presupuesto (Mplus ~USD 695) y capacidad del equipo (poLCA requiere expertise R)

## Tu interlocutor principal

**Agus** para alinear captura técnica con intención pedagógica; **Sebas** para presupuesto e infraestructura operativa; **Berenice** para análisis cuantitativo sobre el log.

---

[:material-arrow-left-circle: Ver todos los roles](roles.md) · [:material-arrow-right-circle: Sigue: Investigador junior](junior.md)
