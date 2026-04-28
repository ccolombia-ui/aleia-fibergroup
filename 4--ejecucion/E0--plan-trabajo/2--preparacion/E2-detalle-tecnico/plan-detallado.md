---
entregable: E2
sprint: 2
titulo: "Detalle técnico + Cadena de valor + Productos + Cronograma + Riesgos"
pago: "10% · $2.700.000 COP · al sign-off"
duracion: "3 semanas · 5 may – 22 may 2026"
roles_activos: [Formulador, Campo, Redes, Cliente]
metodologia: Agile-ODI
depende_de: "E1-done (sign-off)"
paralelo_con: E3
---

# Sprint 2 · Charter — E2 Detalle técnico

## Sprint Goal

> Traducir la solución definida en E1 a su especificación técnica completa: arquitectura de red, cadena de valor RBM-GAC, productos MGA §5, cronograma de ejecución y matriz de riesgos — todo revisado y aprobado por el Cliente.

---

## Sprint Backlog

| ID | Historia / Tarea | Responsable | DoD |
|----|-----------------|-------------|-----|
| E2-01 | Especificación técnica de red: alternativas A1/A2/A3 (HFC/GPON/wMAN) | Frente B (Redes) | Doc entregado al Formulador en Drive |
| E2-02 | Datos de infraestructura municipal: cobertura actual por municipio | Frente D (Campo) | Tabla de infraestructura en Drive |
| E2-03 | Detalle técnico de la solución: arquitectura seleccionada + justificación | Formulador | Sección técnica en Drive |
| E2-04 | Cadena de valor RBM-GAC: Insumos→Actividades→Productos→Resultados→Impactos | Formulador | Cadena de valor en Drive |
| E2-05 | Productos MGA §5: descripción, unidad, cantidad, meta | Formulador | Ficha de productos en Drive |
| E2-06 | Cronograma de ejecución por fases y vigencias | Formulador | Cronograma en Drive |
| E2-07 | Matriz de riesgos: identificación, probabilidad, impacto, mitigación | Formulador | Matriz en Drive |
| E2-08 | Integrar draft E2 completo | Formulador | Draft E2 unificado en Drive |
| E2-09 | Review async por Cliente (1 semana) | Cliente | Comentarios o aprobación en Drive |
| E2-10 | Integrar observaciones + versión final E2 | Formulador | Versión final E2 en Drive |
| E2-11 | Sign-off E2 + cargue | Cliente | Aprobación formal → dispara pago $2.700.000 |

---

## Definition of Done — Sprint 2

- [ ] Especificación técnica de red (Frente B) integrada en el documento
- [ ] Datos de infraestructura municipal (Frente D) incorporados
- [ ] Detalle técnico de la solución con alternativa seleccionada justificada
- [ ] Cadena de valor RBM-GAC completa (5 eslabones)
- [ ] Productos MGA §5 con unidades y metas
- [ ] Cronograma de ejecución por vigencias
- [ ] Matriz de riesgos con mitigaciones
- [ ] Cliente ha completado review y dado sign-off formal

---

## Ceremonias Agile · Sprint 2

| Ceremonia | Día | Duración | Participantes |
|-----------|-----|----------|---------------|
| **Sprint Planning** | D1 · lun 5 may | 30 min | Formulador + Cliente |
| **Daily Standup** | D1–D14 · 09:00 | 15 min async | Formulador (→ canal WA/correo) |
| **Mid-sprint Check** | D7 · lun 12 may | 30 min async | Formulador → reporte de avance a Cliente |
| **Sprint Review** | D15 · jue 22 may | 30 min sync | Formulador + Cliente |
| **Sign-off / Cargue** | D15 o D16 | Async | Formulador → notifica pago |

---

## Calendario semanal

### Semana 1 (5–9 may) — Relevamiento técnico + inicio draft

| Día | Formulador | Frente B (Redes) | Frente D (Campo) |
|-----|-----------|-----------------|-----------------|
| Lun 5 may | Sprint Planning · brief a Redes | Recibe brief técnico | Recibe brief infraestructura |
| Mar 6 may | Data-understanding técnico · revisión IDIO-V7 · normativa red | Trabajo interno A1/A2/A3 | Relevamiento infraestructura |
| Mié 7 may | Draft detalle técnico solución | Trabajo interno | Entrega datos infraestructura |
| Jue 8 may | Draft cadena de valor RBM-GAC | Entrega especificación A1/A2/A3 | Disponible para consultas |
| Vie 9 may | Draft productos MGA §5 | — | — |

### Semana 2 (12–16 may) — Draft cronograma + riesgos + integración

| Día | Formulador | Frentes |
|-----|-----------|---------|
| Lun 12 may | Mid-sprint check · draft cronograma de ejecución | Mid-sprint check |
| Mar 13 may | Draft matriz de riesgos | — |
| Mié 14 may | Integración draft E2 completo | — |
| Jue 15 may | Revisión interna draft E2 + ajustes | — |
| Vie 16 may | Envío draft E2 al Cliente para review async | Cliente recibe draft |

### Semana 3 (19–22 may) — Review Cliente + integración + sign-off

| Día | Formulador | Cliente |
|-----|-----------|---------|
| Lun 19 may | Disponible para consultas del Cliente | Review del draft E2 |
| Mar 20 may | Disponible para consultas | Review del draft E2 |
| Mié 21 may | Integra observaciones → versión final E2 | Envía feedback |
| Jue 22 may | Sign-off · cargue · Sprint Review sync | Sign-off formal + pago $2.700.000 |

---

## Impediment Log

| Impedimento potencial | Mitigación |
|-----------------------|-----------|
| Frente B demora en entregar especificación técnica | Formulador avanza con solución referencial IDIO-V7; integra B en D9 |
| Frente D no entrega datos de infraestructura | Formulador usa fuentes secundarias MinTIC / CINTEL |
| Cliente extiende review más de 5 días | Formulador escala: máx. 1 semana de review; sign-off se desplaza con impacto en E4 |
