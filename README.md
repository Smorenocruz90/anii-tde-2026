# Propuesta ANII TDE_1_2026 — Proyecto Cuaderno Digital

Repositorio interno del equipo Critertec Educación para el proyecto de investigación postulado a la convocatoria ANII TDE_1_2026 / Fundación Ceibal, línea D.II.

**Cierre de postulación:** 11 jun 2026, 14:00 GMT-3.

## El sitio del equipo

Este repositorio contiene un sitio MkDocs Material con toda la información del proyecto explicada para el equipo interno: qué hacemos, por qué, quién hace qué, dónde estamos, qué riesgos hay, y profundización académica completa.

**Una vez deployado en GitHub Pages**, el sitio queda disponible en:

```
https://<usuario>.github.io/ANII/
```

## Estructura del repositorio

```
ANII/
├── docs/                         # Contenido del sitio MkDocs
│   ├── index.md                  # Landing page
│   ├── el-proyecto/              # Qué es / por qué / cómo / cronograma
│   ├── el-equipo/                # Roles + página por persona
│   ├── donde-estamos/            # Estado, fortalezas, riesgos, tareas
│   ├── academico/                # Profundización: propuesta, marco, review panel
│   └── referencias/              # Glosario, bibliografía, enlaces
├── mkdocs.yml                    # Configuración del sitio
├── .github/workflows/deploy.yml  # CI/CD para GitHub Pages
├── propuesta_v2_consolidada.md   # Texto v2.0 completo de la propuesta
├── GRANT_PROPOSAL_REVIEW_2026-05-13.md  # Reporte del panel pre-submission
├── contexto_anii_consolidado.md  # Contexto completo del proyecto
├── feedback_revision_v1.1_a_v2.md  # 17 observaciones del revisor
├── formulario_anii.md            # Mapa del formulario online ANII
└── .claude/                      # Skills y comandos de Claude Code (excluidos de git)
```

## Cómo deployar el sitio a GitHub Pages

### Paso 1 — Crear el repositorio en GitHub

1. Ir a https://github.com/new
2. Nombre del repo: `ANII` (o el que quieras — afecta la URL final del sitio)
3. **Visibilidad:** **Privado**
4. **NO** inicializar con README, .gitignore ni licencia (este repo local ya los tiene)
5. Crear repositorio

### Paso 2 — Push del repo local

Desde una terminal en la carpeta del proyecto:

```bash
# Configurar remote (reemplazar <USUARIO> por tu usuario de GitHub)
git remote add origin https://github.com/<USUARIO>/ANII.git

# Primer commit (si no hay commits aún)
git add .
git commit -m "Initial commit: propuesta v2.0 + sitio MkDocs Material"

# Push
git push -u origin main
```

### Paso 3 — Habilitar GitHub Pages

1. En GitHub, ir a la pestaña **Settings** del repo
2. En la barra lateral izquierda, click en **Pages**
3. En **Build and deployment** → **Source**, seleccionar **GitHub Actions**
4. El workflow `deploy.yml` ya está configurado en `.github/workflows/`. Se va a ejecutar automáticamente con el primer push a `main`.

### Paso 4 — Verificar el deploy

1. Ir a la pestaña **Actions** del repo
2. Verificar que el workflow "Deploy MkDocs Material site to GitHub Pages" haya corrido exitosamente
3. Una vez completado, el sitio queda disponible en `https://<USUARIO>.github.io/ANII/`
4. La URL final aparece también en **Settings → Pages**

## Acceso al equipo

Como el repo es **privado**, hay que invitar a los miembros del equipo manualmente:

1. Ir a **Settings → Collaborators**
2. Click **Add people**
3. Invitar a:
    - Berenice Pacheco-Salazar
    - Agustina Bussi
    - Steven
    - (Eventualmente: referente de la universidad partner)

Los invitados reciben mail con link para aceptar. Una vez aceptado, pueden ver el sitio en `https://<USUARIO>.github.io/ANII/`.

!!! warning "GitHub Pages privados"
    GitHub Pages **privados** requieren una cuenta GitHub Enterprise o GitHub Team. Si la cuenta es Free/Pro personal, el sitio en GH Pages será **público** aunque el repo sea privado.

    **Opciones:**
    - Aceptar que el sitio (no el código) sea públicamente accesible vía URL — pero "no indexable" (la URL solo la conoce el equipo)
    - Upgrade a GitHub Team (USD 4/usuario/mes) para Pages privadas
    - Alternativa: alojar el sitio en Vercel/Netlify con acceso protegido por contraseña

## Edición local del sitio (opcional)

Para previsualizar el sitio localmente antes de pushear:

### Requisitos

- Python 3.10 o superior

Si no tenés Python instalado en Windows, instalarlo vía:
```powershell
winget install Python.Python.3.12
```

### Levantar el servidor local

```bash
pip install mkdocs-material mkdocs-minify-plugin
mkdocs serve
```

Abrir http://127.0.0.1:8000 en el navegador. El sitio se recarga automáticamente al editar los archivos `.md`.

### Editar y publicar cambios

1. Editar cualquier archivo en `docs/`
2. `git add .`
3. `git commit -m "Descripción del cambio"`
4. `git push`
5. GitHub Actions builderá y deployará automáticamente (~2 minutos)

## Comandos útiles

```bash
# Estado del repo
git status

# Ver cambios pendientes
git diff

# Historial de commits
git log --oneline

# Ver el workflow de deploy en curso
# (Requiere gh CLI: winget install GitHub.cli; gh auth login)
gh run watch
```

## Contenido principal del proyecto

| Archivo | Para qué sirve |
|---------|----------------|
| `propuesta_v2_consolidada.md` | El texto completo de la propuesta v2.0 (las 15 textareas + 3 tablas del formulario ANII). **Este es el archivo de trabajo principal** que copiamos al formulario online de ANII. |
| `GRANT_PROPOSAL_REVIEW_2026-05-13.md` | Reporte completo del panel pre-submission de 6 agentes que revisó la v2.0. **Léelo antes de iterar** — identifica ~170 ítems a resolver. |
| `contexto_anii_consolidado.md` | Contexto completo (98K palabras): bases ANII, diagnóstico del problema, marco teórico, estrategia IP, equipo, cronograma. La fuente de verdad sobre el proyecto. |
| `feedback_revision_v1.1_a_v2.md` | Las 17 observaciones originales que motivaron la reescritura v1.1 → v2.0. |
| `formulario_anii.md` | Mapa completo del formulario online de ANII con límites de palabras y observaciones operativas. |

## Próximos pasos del equipo

Mirá en el sitio:

1. **Dónde estamos → Estado:** lo que ya está hecho y lo que falta
2. **Dónde estamos → Riesgos:** los 5 críticos a resolver antes del 11 jun
3. **Dónde estamos → Tareas:** lista accionable por persona con plazos
4. **El equipo → tu página personal:** lo que te toca

---

© 2026 Critertec Educación. Uso interno del equipo.
