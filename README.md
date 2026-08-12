# 25-week_12-08-26_calificacion_universitarios-
---

tipo: refinamiento-requerimientos
proyecto: Sistema de Gestión de Horarios SENA (code-sena)
revisor:
ficha:
fecha:
estudiante:
rol_en_proyecto:
----------------

# Evaluación del estudiante

## A. Requerimientos

### Detalle — Requerimientos

| ID | Título | Fuente / Autor | Propuesta | Decisión | Justificación técnica | Ajuste propuesto (si 🔧) | Impacto | Prioridad | ¿Bloquea backend? |
|---|---|---|---|:---:|---|---|---|:---:|:---:|
| **P-REQ-01** | Análisis y propuestas de mejora – Sistema de Gestión de Horarios SENA | https://drive.google.com/drive/folders/1xZ0pBz9jLOfqZ8nPKW88863T66BTRyCr | **Cambiar** | 🔧 | Las mejoras de consulta, filtros, responsive, conflictos, ambientes y reportes son pertinentes, pero algunas propuestas mezclan UX con requerimientos técnicos y roles que requieren mayor definición. | Precisar roles, notificaciones, filtros y reportes; diferenciar mejoras UX de cambios funcionales y validar el prototipo indicado. | **Requerimiento** | **Alta** | **Sí** |          |                   |

- **Decisiones permitidas:**

- **Propuesta:** `Cambiar` · `Agregar` · `Quitar`

- **Decisión:** ✅ **ACEPTAR** · 🔧 **ACEPTAR CON AJUSTE** · ❌ **RECHAZAR** · 💬 **DISCUTIR**

- **Impacto:** `Requerimiento` · `Contrato API` · `DDL/BD` · `RBAC` · `Mockup` · `Backend`

- **Prioridad:** `Alta` · `Media` · `Baja`

- **Bloquea backend:** `Sí` · `No`

## B. Base de datos

| ID | Título | Fuente / Autor | Propuesta | Entidad/Tabla afectada | Decisión | Justificación técnica | Ajuste propuesto (si 🔧) | ¿Requiere changeset nuevo? | ID del changeset | Impacto | Prioridad | ¿Bloquea backend? |
|---|---|---|---|---|:---:|---|---|:---:|---|---|:---:|:---:|
| P-BD-01 | | | | | | | | | | | | |
| P-BD-02 | | | | | | | | | | | | |
| P-BD-03 | | | | | | | | | | | | |

**Decisiones permitidas:**  

- **Propuesta:** `Entidad` · `Campo` · `Tipo` · `Relación` 

- **Entidad/tabla:**  `Schema.tabla` · `Campo` 

- **Decisión:** ✅ **ACEPTAR** · 🔧 **ACEPTAR CON AJUSTE** · ❌ **RECHAZAR** · 💬 **DISCUTIR**

- **Justificación:** `Contrato/mockup` · `normalización` · `integridad`

- **Changeset:** `refinamiento-<dominio>-NNN`

- **Impacto:** `Requerimiento` · `Contrato API` · `DDL/BD` · `RBAC` · `Mockup` · `Backend`

- **Prioridad:** `Alta` · `Media` · `Baja`

- **Bloquea backend:** `Sí` · `No`

---

## C. Mockup / UX

### Resumen de decisiones — Mockup

| ID | Propuesta (resumen) | Pantalla / Ruta | Propuesta | Decisión | Ajuste propuesto (si 🔧) | Depende de | Impacto | Prioridad | ¿Bloquea backend? |
|---|---|---|---|:---:|---|---|---|:---:|:---:|
| **P-MOCK-01** | Mejorar consulta de horarios, filtros, detalle de clases, responsive y visualización de conflictos | Coordinador · Crear horario · `#/horarios/nuevo` | **Cambiar** | 🔧 **ACEPTAR CON AJUSTE** | **Cambiar la pantalla para mostrar filtros, detalle de la sesión y conflictos de forma visible, evitando navegación innecesaria y adaptando la vista a móvil.** | **P-REQ-01** | **Mockup** | **Alta** | **Sí** |

**Decisiones permitidas:**  
- **Pantalla / ruta:** `Coordinador` · `Crear horario` · `#/horarios/nuevo>`
- **Propuesta:** `Cambiar` · `Agregar` · `Quitar`
- **Decisión:** ✅ **ACEPTAR** · 🔧 **ACEPTAR CON AJUSTE** · ❌ **RECHAZAR** · 💬 **DISCUTIR**
- **Ajuste propuesto (si 🔧):** `Cambiar` ·
- **Depende de:** `P-REQ-xxa` · `P-BD-xx` 
- **Impacto:** `Requerimiento` · `Contrato API` · `DDL/BD` · `RBAC` · `Mockup` · `Backend`
- **Prioridad:** `Alta` · `Media` · `Baja`
- **Bloquea backend:** `Sí` · `No`

---

## D. Hallazgos nuevos

> Problemas que el estudiante no propuso pero que tú, como conocedor del sistema, detectaste.

| ID | Título | Capa | Descripción | Por qué importa (técnico) | Propuesta de solución | Impacto | Prioridad | ¿Bloquea backend? |
|---|---|---|---|---|---|---|:---:|:---:|
| H-01 | | REQ / BD / MOCK | | | | | | |
| H-02 | | REQ / BD / MOCK | | | | | | |
| H-03 | | REQ / BD / MOCK | | | | | | |

---

## E. Bloqueantes para backend

> Solo incluir los elementos marcados anteriormente como **"Sí"**.

| ID (ref) | Qué falta cerrar | Capa | Decisión |
|---|---|---|:---:|
| P-REQ-XX / P-BD-XX / P-MOCK-XX / H-XX | | REQ / BD / MOCK | |
| P-REQ-XX / P-BD-XX / P-MOCK-XX / H-XX | | REQ / BD / MOCK | |

---

# F. Cierre y calificación

* **Total de propuestas no relacionadas a gestión de horarios:** _1__
* * **Total de propuestas no relacionadas a gestión de horarios:** _1__
* **Total de propuestas revisadas:** __2_
* **✅ ACEPTAR:** ___
* **🔧 ACEPTAR CON AJUSTE:** ___
* **❌ RECHAZAR:** ___
* **💬 DISCUTIR:** ___
* **Hallazgos nuevos:** ___
* **Bloqueantes de backend:** ___

### Calificación

**Nota: ____ / 100**

### Comentario general del calificador

>
