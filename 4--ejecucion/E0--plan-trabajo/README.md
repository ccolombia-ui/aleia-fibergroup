---
proyecto: "Territorios Digitales Transformativos · Arauca"
ref: "CCMS-CB-2026-001-B-v11"
metodologia: "Agile-ODI · 4 frentes paralelos · 3 Sprints · CRISP-DM"
total_honorarios: "$27.000.000 COP (IVA incluido)"
fecha_inicio: "2026-04-28"
fecha_fin_estimada: "2026-05-16"
---

# Plan de trabajo · Territorios Digitales Transformativos · Arauca · v11

## Estructura del plan

```
E0--plan-trabajo/
├── README.md                              ← este archivo
├── 2--preparacion/
│   ├── E0-fundacion/
│   │   ├── plan-detallado.md             ← Starting Charter (28 abr · G0 · 20%)
│   │   ├── agenda-formulador.md
│   │   └── agenda-cliente.md
│   ├── E1-diagnostico-solucion/
│   │   ├── plan-detallado.md             ← E1 Charter · S1 Draft → S2 MVP → S3 RC
│   │   ├── agenda-formulador.md
│   │   ├── agenda-campo.md               ← Frente D (solo S1)
│   │   └── agenda-cliente.md
│   ├── E2-detalle-tecnico/
│   │   ├── plan-detallado.md             ← E2 Charter · S1 Draft → S2 MVP → S3 RC
│   │   ├── agenda-formulador.md
│   │   ├── agenda-redes.md               ← Frente B (S1 brief → entrega S2-D1)
│   │   ├── agenda-campo.md               ← Frente D (infraestructura S1)
│   │   └── agenda-cliente.md
│   ├── E3-presupuestal/
│   │   ├── plan-detallado.md             ← E3 Charter · S1 Draft → S2 MVP → S3 RC
│   │   ├── agenda-formulador.md
│   │   ├── agenda-presupuesto.md         ← Frente C (S1 brief → entrega S2-D1)
│   │   └── agenda-cliente.md
│   └── E4-consolidacion-final/
│       ├── plan-detallado.md             ← S3 RC · §7·§8 · BPIN · Acta cierre
│       ├── agenda-formulador.md
│       └── agenda-cliente.md
└── 3--confirmacion/
    ├── actas/
    └── briefs/
```

---

## Resumen ejecutivo v11

| Gate | Alcance | Sprint | Pago | Fecha |
|------|---------|--------|------|-------|
| **G0 · Starting** | E0: Contrato · anticipo · briefs frentes · Acta ODI | — | 20% · $5.400.000 | 28 abr 2026 |
| **G1 · S1 Draft** | E1+E2+E3 drafts paralelo · MGA §1–§3 · Sign-off E1 | S1 | 30% · $8.100.000 | 4 may 2026 |
| **G2 · S2 MVP** | E2+E3 MVP · MGA §4–§6 · Sign-off E2+E3 | S2 | 30% · $8.100.000 | 9 may 2026 |
| **G3 · S3 RC** | RC ajustes · MGA §7–§8 · BPIN · Acta final | S3 | 20% · $5.400.000 | 16 may 2026 |
| **TOTAL** | E1+E2+E3 · MGA §1–§8 · BPIN | 3 sprints | 100% · $27.000.000 | 16 may 2026 |

**Duración total: 19 días calendario (28 abr → 16 may 2026)**

---

## Mapa de entregables × sprints × MGA

| Entregable | S1 · Draft (→ 4 may) | S2 · MVP v1.0 (→ 9 may) | S3 · RC v1.1 (→ 16 may) |
|------------|----------------------|-------------------------|------------------------|
| **E1** Diagnóstico+Solución · A+D | Draft IBD · árbol · solución · sector · ODS · MGA §1–§2 iniciadas | Review+integración feedback · MGA §1–§3 completas · **Sign-off E1 ✓** | Ajustes cruzados · MGA §4 definitivo · versión final |
| **E2** Detalle técnico · A+B+D | Draft técnico · cadena valor RBM-GAC · cronograma · riesgos | MVP revisión técnica (Frente B) · MGA §5 completa · **Sign-off E2 ✓** | Ajustes finales · MGA §5 definitivo · integrado con E3 |
| **E3** Presupuestal · A+C | Draft CAPEX/OPEX · fuentes SGR/PGN/APP · proyección plurianual | MVP revisión financiera (Frente C) · MGA §6 completa · **Sign-off E3 ✓** | Ajustes finales · MGA §6 definitivo · integrado con E2 |
| **MGA Web** (paralelo) | §1 Identificación · §2 Marco teórico · §3 Diagnóstico | §4 Alternativas solución · §5 Descripción técnica · §6 Presupuesto | §7 Evaluación VPN/TIR/B-C · §8 Resumen ejecutivo · **BPIN** |

---

## Roles y frentes

| Frente | Rol | Sprints activos | Entregable clave |
|--------|-----|----------------|-----------------|
| **A** Formulador (CCMS) | Todos | Starting + S1 + S2 + S3 | Todos los entregables + MGA Web §1–§8 |
| **B** Arquitecto de Redes | S1 brief → S2 entrega | Brief Starting · trabajo S1 · entrega S2-D1 | Especificación red A1/A2/A3 → E2 |
| **C** Especialista Presupuesto | S1 brief → S2 entrega | Brief Starting · trabajo S1 · entrega S2-D1 | Precios CAPEX/OPEX → E3 |
| **D** Técnicos de Campo | S1 únicamente | S1 D1–D3 | Datos IBD in-situ + infraestructura municipal → E1+E2 |
| **Cliente** | Starting + Sign-offs | G0 · G1 · G2 · G3 | Pagos + review async + sign-offs |
| **DNP-SUIFP** | S3 | S3 D4–D5 | Emisión código BPIN |

---

## Metodología Agile-ODI aplicada

Ciclo por sprint:
```
Sprint Planning → Daily Standup (async 09:00) → Mid-sprint Check → Draft/MVP/RC → Review Async → Integración → Sprint Review → Sign-off → Cargue
```

**Característica clave v11:** E1, E2, E3 corren en **paralelo total** desde S1. El Formulador gestiona los tres frentes simultáneamente. Frentes B y C reciben brief en Starting y entregan en S2-D1 para que el Formulador consolide los MVP ese mismo sprint.

---

## Dependencias críticas

```
Starting · G0 (28 abr)
    ↓ contrato firmado · $5.4M · briefs B/C/D emitidos · Acta ODI
S1 Draft (29 abr – 4 may)
    ├─ E1 draft (A+D) ──────────────────────→ Sign-off E1 → G1 · $8.1M
    ├─ E2 draft (A + brief B en S1) ────────→ input MVP S2
    └─ E3 draft (A + brief C en S1) ────────→ input MVP S2
    ↓
S2 MVP v1.0 (5 may – 9 may)
    ├─ E1 integra feedback · MGA §1–§3 ✓
    ├─ E2 MVP con Frente B ─────────────────→ Sign-off E2 ─┐
    └─ E3 MVP con Frente C ─────────────────→ Sign-off E3 ─┴→ G2 · $8.1M
    ↓
S3 RC v1.1 (12 may – 16 may)
    ├─ Ajustes cruzados E1+E2+E3
    ├─ MGA §7 Evaluación VPN/TIR/B-C
    ├─ MGA §8 Resumen ejecutivo
    └─ BPIN DNP-SUIFP ──────────────────────→ Acta final → G3 · $5.4M
```

> Frente D (campo) desvinculado tras S1. Frentes B y C desvinculados tras entrega en S2-D1.
