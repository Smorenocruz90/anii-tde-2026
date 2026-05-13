# Tablero de control

Vista operativa del proyecto. Tres herramientas para gestionar la postulación día a día:

<div class="grid cards" markdown>

-   :material-clipboard-check-outline:{ .lg } **[Checklist formulario ANII](checklist-anii.md)**

    ---

    Status de cada sub-sección del formulario online: qué está cargado, qué falta redactar, qué documentos adjuntar.

    `15 textareas` · `4 tablas dinámicas` · `Sección 5 Presupuesto` · `Adjuntos`

-   :material-view-column:{ .lg } **[Kanban de tareas](kanban.md)**

    ---

    Vista por estado (To Do / Doing / Done) y por persona. Plazos visibles para los 29 días al cierre.

    `~30 tareas activas` · `5 críticas` · `12 esta semana`

-   :material-decision:{ .lg } **[Decisiones](decisiones.md)**

    ---

    Decisiones tomadas + decisiones pendientes con decisor responsable, plazo y consecuencias de no decidir.

    `6 bloqueantes pendientes` · `8 ya tomadas`

</div>

## Cómo se actualiza

Este tablero refleja el estado actual del proyecto. Cuando alguien del equipo:

- ✅ **Completa una tarea** → marca el ítem como `done` y commit al repo
- 🟡 **Empieza una tarea** → mueve a `doing`
- 🔴 **Bloquea con un riesgo nuevo** → agrega línea con badge `blocked` y comentario
- 📌 **Toma una decisión** → loguear en [Decisiones](decisiones.md)

Cada cambio queda versionado con git (`git commit -m "..."`); GitHub Actions rebuildea el sitio en ~1 minuto.

## KPI rápidos al 13 may 2026

| KPI | Valor | Tendencia |
|-----|------|-----------|
| Días al cierre | 29 | ⏳ |
| Textareas redactadas | 15 / 15 | ✅ |
| Tablas redactadas | 3 / 4 | 🟡 (falta 4.4 Plan de Trabajo detallado) |
| Sección 5 Presupuesto | 0 / 1 | 🔴 |
| Riesgos críticos abiertos | 5 / 5 | 🔴 |
| Cartas aval firmadas | 0 / 3 | 🔴 |
| CVUy cargados | 0 / 5 | 🔴 |

→ Detalle accionable en [Checklist formulario ANII](checklist-anii.md).
