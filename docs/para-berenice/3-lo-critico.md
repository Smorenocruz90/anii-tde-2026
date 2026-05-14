# Paso 3 · Lo crítico de ti

<div class="wizard-progress" markdown>
  <div class="wizard-progress-label">Paso 3 de 6 · 5 decisiones que dependen de ti</div>
  <div class="wizard-progress-bar"><div class="wizard-progress-fill" style="width: 50%"></div></div>
</div>

!!! danger "Lo que no avanza sin tu decisión"
    Estas son las **5 decisiones científicas y estratégicas** que sólo vos podés tomar. Cada una tiene un plazo. Si alguna se atrasa, el cierre del 11 de junio se mueve.

## Decisión 1 · Universidad participante (la tuya)

<div class="decision-card critical" markdown>
  <div class="decision-header">
    <span class="decision-tag">BLOQUEANTE</span>
    <span class="decision-deadline">Plazo: 27 may 2026</span>
  </div>
  <div class="decision-title">Cerrar a tu universidad como organización participante del proyecto</div>
</div>

**Qué necesitamos:**

- Convenio Critertec ↔ tu universidad firmado (o iniciado formalmente con compromiso documentado)
- **Carta aval institucional** firmada por la autoridad académica de tu universidad
- **Definición del referente académico** de la universidad que actuará como coautor y nexo del honest broker
- **Compromiso del IRB** de tu universidad para revisar el protocolo en M1

**Por qué te toca a vos:**

Esta es **tu universidad** —donde trabajás como afiliada—. Sin tu intermediación interna no hay convenio. Sebas no tiene canal con la autoridad académica de tu universidad; vos sí. El acompañamiento de Sebas es administrativo (redacción del convenio, firma desde Critertec, gestión de tiempos).

**Qué pasa si no se cierra:**

ANII puede **no procesar la postulación**. El filtro A.2 del llamado exige una organización participante con perfil académico (no se acepta sólo Critertec como proponente). Sin universidad firmando, no hay submission viable.

**Plan B:**

Si tu universidad rechaza o demora, hay que activar inmediatamente una segunda universidad latinoamericana con perfil compatible. Esto requiere replantear el equipo de coautoría y el IRB. **No es deseable, pero hay que tenerlo identificado por si acaso.**

---

## Decisión 2 · Alcance del honest broker

<div class="decision-card critical" markdown>
  <div class="decision-header">
    <span class="decision-tag">BLOQUEANTE</span>
    <span class="decision-deadline">Plazo: 27 may 2026</span>
  </div>
  <div class="decision-title">¿La universidad participante hace sólo análisis, o también design lock?</div>
</div>

**El conflicto de interés (CoI):**

El cuaderno digital es producto de Critertec. El framework de las 4 categorías es de Critertec. Si Critertec también diseña el itinerario formativo y elige qué códigos semánticos se capturan, el revisor académico puede leer todo el estudio como *"Critertec validando su propio producto"*.

**Opción A — Honest broker sólo de análisis (status quo v2.0):**

- La universidad ejecuta LCA, bivariadas, kappa sobre el dataset anonimizado
- Critertec hace el diseño + el curso + el bundle congelado + la captura
- Mitigación adicional: anclaje teórico externo de las 4 categorías + pre-registro

**Opción B — Honest broker de análisis + design lock (lo que recomienda el panel):**

- La universidad **también** valida la selección final de los 4 códigos semánticos
- La universidad **también** valida el itinerario formativo antes del freeze
- Lo recomienda el panel en su hallazgo crítico #1 (CoI estructural)

**Lo que tenés que decidir:**

Si la universidad participante (tu universidad) tiene capacidad y tiempo para hacer el design lock antes del freeze de M0 (oct 2026). Si sí → Opción B (mejor mitigación pero más carga). Si no → Opción A (status quo, requiere reforzar otras mitigaciones).

---

## Decisión 3 · Plan analítico: LCA vs perfiles latentes simples

<div class="decision-card major" markdown>
  <div class="decision-header">
    <span class="decision-tag">CRÍTICO</span>
    <span class="decision-deadline">Plazo: 31 may 2026</span>
  </div>
  <div class="decision-title">Re-calibrar el análisis cuantitativo para N final realista</div>
</div>

**El problema:**

N inicial = 120 docentes. Mortalidad esperada 25-35% → **N final ≈ 80**. El panel señala que **LCA con 3-5 clases sobre N=80 está apretado**: el modelo puede converger pero la estabilidad de las clases es discutible.

**Opciones:**

| Opción | Qué hace | Pros | Contras |
|--------|----------|------|---------|
| **A. Mantener LCA 3-5 clases** | El plan v2.0 actual | Coherente con el OE1 redactado | Riesgo de no convergencia o clases inestables |
| **B. Perfiles latentes simples** (k-modes / cluster jerárquico sobre patrones de marcado) | Algoritmo descriptivo más robusto a N pequeño | Defendible con N=80 | Hay que re-redactar 4.3.1 + ajustar OE1 |
| **C. Mantener LCA pero con plan de contingencia explícito** | Si N<60 al cierre de M5, switch a B | Flexible | Requiere árbol de decisión documentado |

**Lo que tenés que decidir:**

Si pivotamos a B desde ya (más conservador, mejor defensa frente al revisor) o si mantenemos LCA con un plan de contingencia C (más ambicioso, mayor riesgo). **Si decidís B, hay que re-redactar la sección 4.3.1 antes del 3 jun.**

---

## Decisión 4 · Adaptación de Tschannen-Moran a IA

<div class="decision-card major" markdown>
  <div class="decision-header">
    <span class="decision-tag">CRÍTICO</span>
    <span class="decision-deadline">Plazo: 27 may 2026</span>
  </div>
  <div class="decision-title">¿Adaptamos la escala con panel de expertos o usamos versión general?</div>
</div>

**El problema:**

La escala Tschannen-Moran de autoeficacia docente está validada para autoeficacia docente general, no específica para **uso pedagógico de IA**. Hay dos caminos:

**Opción A — Versión general:**

- Aplicar la escala tal como está validada (autoeficacia docente general)
- Reporte: "La autoeficacia general de la docente se asocia con la tipología observada"
- Pros: instrumento validado, no requiere panel ni presupuesto extra
- Contras: la asociación con el dominio IA queda débil

**Opción B — Adaptación al dominio IA con panel de expertos:**

- Adaptar los ítems al uso pedagógico de IA (≈12-15 ítems re-escritos)
- Panel de 3-5 expertos en M1 revisa la adaptación
- Reportar propiedades psicométricas observadas
- Pros: específico al dominio, defensa científica más fuerte
- Contras: requiere panel (~USD 1.000-1.500 presupuesto), tiempo adicional en M1, hay que decir explícitamente que es exploratorio

**Lo que tenés que decidir:**

A o B. Si B, Sebas necesita el costo del panel para meterlo en presupuesto antes del 31 may.

---

## Decisión 5 · Aprobación final v2.1 para submission

<div class="decision-card major" markdown>
  <div class="decision-header">
    <span class="decision-tag">CIERRE</span>
    <span class="decision-deadline">Plazo: 8 jun 2026</span>
  </div>
  <div class="decision-title">Firmar v2.1 como lista para submission</div>
</div>

**Qué firmás:**

- El texto definitivo de las 15 textareas + 3 tablas del formulario
- El diseño metodológico re-calibrado (post decisiones 1-4)
- Las 17 respuestas al feedback original (ratificás que están bien resueltas)
- El plan de mitigación del CoI estructural (post decisión 2)
- La sección 4.3.1 re-redactada si pivotaste a perfiles latentes (post decisión 3)

**Cómo te llega:**

Sebas + Agus producen el documento v2.1 consolidado entre el 3 y el 6 de junio. Te lo entregan para revisión final. Tu firma habilita la carga al formulario online ANII.

**Margen de revisión:**

3 días (8 al 11 de junio) para que vos puedas devolver observaciones de última hora si las hubiera. **No te aproveches todo el margen — Sebas necesita 24h previas al cierre para cargar todo al formulario.**

---

## Cosas que NO te tocan a ti

Para que el inventario quede claro: estas son **decisiones de Sebas** (no tuyas), aunque lleven tu input:

- ✅ Presupuesto detallado y desglose por rubro
- ✅ Modalidad de contratación del investigador junior
- ✅ Tabla FTE × persona × actividad
- ✅ Plan de Trabajo Gantt semanal
- ✅ Estatus legal Critertec RD (sucursal vs filial)
- ✅ Gestión de carta MINERD
- ✅ Carga del formulario online ANII
- ✅ Submission técnica el 11 jun

Tu input puntual ayuda (estimar dedicaciones académicas, validar que el cronograma sea científicamente coherente), pero las **decisiones son de Sebas como Director del proyecto**.

---

<div class="wizard-nav" markdown>
[← Paso 2 · Estado actual](2-estado-actual.md){ .wizard-prev }
[Paso 4 · La propuesta →](4-la-propuesta.md){ .wizard-next }
</div>
