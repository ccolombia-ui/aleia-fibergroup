---
entregable: E3
sprint: 3
titulo: "Detalle presupuestal"
pago: "10% · $2.700.000 COP · al sign-off"
duracion: "3 semanas · 5 may – 22 may 2026"
roles_activos: [Formulador, Presupuesto, Cliente]
metodologia: Agile-ODI
depende_de: "draft E1 (no requiere sign-off, sí requiere definición de solución)"
paralelo_con: E2
---

# Sprint 3 · Charter — E3 Detalle presupuestal

## Sprint Goal

> Producir la estructura presupuestal completa del proyecto: CAPEX y OPEX por producto, fuentes de financiamiento identificadas y proyección plurianual — con el nivel de detalle que requiere la MGA Web para el módulo de presupuesto.

---

## Sprint Backlog

| ID | Historia / Tarea | Responsable | DoD |
|----|-----------------|-------------|-----|
| E3-01 | Precios unitarios CAPEX: infraestructura de red · equipos · materiales | Frente C (Presupuesto) | Tabla precios en Drive · con fuente MinTIC / SECOP II |
| E3-02 | Precios unitarios OPEX: operación · mantenimiento · personal técnico | Frente C (Presupuesto) | Tabla OPEX en Drive · con fuente y vigencia |
| E3-03 | Draft 1: estructura presupuestal CAPEX por producto MGA §5 | Formulador | Draft 1 en Drive |
| E3-04 | Draft 2: estructura OPEX plurianual + fuentes de financiamiento | Formulador | Draft 2 en Drive |
| E3-05 | Verificar coherencia presupuestal con solución técnica de E2 | Formulador | Nota de coherencia |
| E3-06 | Identificar y documentar fuentes de financiamiento | Formulador | Sección fuentes: SGR · PGN · APP · Otros |
| E3-07 | Proyección plurianual: CAPEX año 1 + OPEX años 2–N | Formulador | Tabla plurianual en Drive |
| E3-08 | Review async por Cliente (1 semana) | Cliente | Comentarios o aprobación en Drive |
| E3-09 | Integrar observaciones + versión final E3 | Formulador | Versión final E3 en Drive |
| E3-10 | Sign-off E3 + cargue | Cliente | Aprobación formal → dispara pago $2.700.000 |

---

## Definition of Done — Sprint 3

- [ ] Tabla de precios CAPEX con fuentes verificadas (MinTIC/SECOP II)
- [ ] Tabla de precios OPEX con vigencia y fuente
- [ ] Presupuesto CAPEX estructurado por producto MGA §5
- [ ] OPEX plurianual proyectado
- [ ] Fuentes de financiamiento identificadas y documentadas
- [ ] Coherencia con alternativa técnica seleccionada en E2
- [ ] Cliente ha completado review y dado sign-off formal

---

## Ceremonias Agile · Sprint 3

| Ceremonia | Día | Duración | Participantes |
|-----------|-----|----------|---------------|
| **Sprint Planning** | D1 · lun 5 may | 30 min | Formulador + Cliente (junto con S2) |
| **Daily Standup** | D1–D14 · 09:00 | 15 min async | Formulador (→ canal WA/correo) |
| **Mid-sprint Check** | D7 · lun 12 may | 30 min async | Formulador → reporte a Cliente |
| **Sprint Review** | D15 · jue 22 may | Junto con S2 | Formulador + Cliente |
| **Sign-off / Cargue** | D15 o D16 | Async | Formulador → notifica pago |

> Sprint Planning E3 ocurre junto con el de E2 el lunes 5 may.
> Sprint Review E3 ocurre junto con el de E2 el jueves 22 may.

---

## Calendario semanal

### Semana 1 (5–9 may) — Precios + Draft 1

| Día | Formulador | Frente C (Presupuesto) |
|-----|-----------|----------------------|
| Lun 5 | Sprint Planning · brief a Presupuesto (template CAPEX/OPEX) | Recibe template + brief |
| Mar 6 | Revisar draft E1: árbol de objetivos + solución · extraer productos para presupuestar | Trabajo interno: precios CAPEX |
| Mié 7 | Draft 1 presupuestal: estructura CAPEX por producto | Trabajo interno: precios OPEX |
| Jue 8 | Recibir tablas de precios Frente C · integrar en draft 1 | **Entrega precios CAPEX + OPEX** |
| Vie 9 | Ajuste draft 1 con precios reales · coherencia con E2 (alternativa técnica) | Disponible para consultas |

### Semana 2 (12–16 may) — Draft 2 + fuentes + plurianual

| Día | Formulador | Frente C |
|-----|-----------|---------|
| Lun 12 | Mid-sprint check · Draft 2: fuentes de financiamiento (SGR · PGN · APP) | Mid-sprint check |
| Mar 13 | Proyección plurianual CAPEX año 1 + OPEX años 2–N | — |
| Mié 14 | Verificar coherencia presupuestal total | — |
| Jue 15 | Revisión interna draft E3 completo | — |
| Vie 16 | **Envío draft E3 al Cliente** + draft E2 simultáneo | Cliente recibe ambos drafts |

### Semana 3 (19–22 may) — Review + sign-off

| Día | Formulador | Cliente |
|-----|-----------|---------|
| Lun 19 | Disponible para consultas del Cliente | Review draft E3 |
| Mar 20 | Disponible | Review draft E3 |
| Mié 21 | Integra observaciones → versión final E3 | Envía feedback |
| Jue 22 | Sprint Review · sign-off · cargue · pago | Sign-off + pago $2.700.000 |

---

## Nota de dependencia con E2

E3 y E2 corren en paralelo. Sin embargo:
- E3 **necesita** la alternativa técnica seleccionada de E2 (disponible D8) para calcular el CAPEX correcto.
- Si E2 aún no ha seleccionado alternativa en D8, el Formulador presupuesta la alternativa de referencia y ajusta en D9 al recibir la selección de E2.

---

## Impediment Log

| Impedimento potencial | Mitigación |
|-----------------------|-----------|
| Frente C demora en entregar precios | Formulador usa precios de referencia SECOP II / publicados MinTIC · actualiza con C en D9 |
| Alternativa técnica E2 no definida aún en D8 | Presupuestar alternativa referencial · ajustar cuando E2 confirme selección |
| Cliente pide cambios de alcance que afectan el presupuesto | Solo se aceptan si E1 fue modificado con sign-off; de lo contrario se generan adendas |
