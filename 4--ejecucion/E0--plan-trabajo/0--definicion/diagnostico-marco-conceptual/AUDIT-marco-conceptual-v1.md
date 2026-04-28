---
audit_id: "CCMS-CB-2026-AUDIT-001"
proyecto: "Formulación MGA · Arauquita · Territorios Digitales Transformativos"
ref_contrato: "CCMS-CB-2026-001-B-v11"
fecha_audit: "2026-04-27"
version: "1.0"
estado: "DRAFT — pendiente verificación fuentes faltantes"
responsable: "Carlos Camilo Madera Sepúlveda · Frente A"
fuente_referencia_principal: "C:/antigravity/aleia-contratos/R900-ccms/5-alma-caribe/poc-mga-tolu-sucre"
fuente_referencia_secundaria: "C:/antigravity/aleia-contratos/R900-ccms/6-casa-bacana/4--ejecucion/E0--plan-trabajo/0--definicion/7-propuesta-colombia-digital"
---

# Audit de Marco Conceptual · Formulación MGA Arauquita
## Punto de partida · E0 Starting · 28 abr 2026

> **Propósito:** Mapear qué material conceptual, normativo y metodológico existe y puede reutilizarse desde el PoC Alma-Caribe (Sucre), versus qué debe construirse nuevo para el proyecto Arauquita. Este audit es el insumo cardinal de E1 (§1·§2·§3·§4 MGA).

---

## 1. Contexto del proyecto a formular

| Parámetro | Valor |
|-----------|-------|
| **Nombre tentativo** | Territorios Digitales Transformativos · Arauquita |
| **Territorio** | Municipio de Arauquita · Departamento de Arauca |
| **Sector MGA** | 23 — Tecnologías de la Información y las Comunicaciones (TIC) |
| **Tipo de intervención** | Masificación acceso internet hogares (4.000 objetivo) + apropiación digital |
| **Tecnología** | Deuda Técnica — a definir en E2 (GPON/FTTH, radio, mixto) |
| **Valor estimado proyecto** | A calcular en E3 (referencia Colombia Digital: $14.1M COP / 7.500 hogares) |
| **Plazo ejecución** | 18 meses |
| **Fuentes financiación** | MinTIC 95% (FUTIC / Fondo TIC) · Gobernación Arauca 5% |
| **Programa MinTIC candidato** | Por identificar: Casa Bacana / Conexiones Residenciales / Territorios Digitales (SOTA research pendiente) |
| **Operador ESP** | Fibergroup S.A.S. E.S.P. (NIT 901.322.864-7 · Bucaramanga · ya opera en Arauca) |

---

## 2. Inventario de lo que TENEMOS (reutilizable de PoC Alma-Caribe)

### 2.1. Fuentes verificadas descargadas (12+1 documentos · ~57 MB)

> **Alerta de trazabilidad:** Las fuentes verificadas del PoC Alma-Caribe son territoriales de Sucre y NO aplicables directamente a Arauquita. Se listan aquí como modelo metodológico de qué tipo de documentos deben descargarse para Arauquita.

| # | Tipo de documento | Equivalente para Arauquita | Estado |
|:-:|-------------------|---------------------------|--------|
| 1 | PDD Sucre 2024-2027 | **PDD Arauca 2024-2027** | ❌ No descargado |
| 2 | PAI CARSUCRE 2024-2027 | **Plan CORPORINOQUIA 2024** | ❌ No descargado |
| 3 | PDM Coveñas 2024-2027 | **PDM Arauquita 2024-2027** | ❌ No descargado |
| 4 | PDEA Sucre (MinAgri-ADR) | **PDEA Arauca 2024 (ADR)** | ❌ No descargado |
| 5 | Caracterizaciones municipales | **Caracterización Arauquita DANE** | ❌ No descargado |
| 6 | Datos Abiertos DIVIPOLA (CSV) | **DIVIPOLA Arauquita** | ❌ No descargado |
| 7 | Plan Riego Departamental | **Plan Hídrico Arauca** (si existe) | ❌ Sin verificar |

### 2.2. Marco normativo TIC — REUTILIZABLE 100%

> **Estado de trazabilidad:** Las normas son de orden nacional. Aplicables íntegramente a Arauquita. El PoC Alma-Caribe las documenta pero NO tiene los PDFs descargados en `fuentes-verificadas/` — solo citaciones en texto. **Gap de trazabilidad identificado.**

#### 2.2.1. Leyes y política pública TIC

| Norma | Materia | Aplicación Arauquita | PDF verificado |
|-------|---------|---------------------|----------------|
| **Ley 1341/2009** (mod. Ley 1978/2019 y Ley 2108/2021) | Ley TIC + Ley de Internet | Marco legal sector | ⚠️ Solo citada, no descargada |
| **Ley 2294/2023** Art. 142-144 | PND 2022-2026 · Conectividad Digital para Cambiar Vidas | Política de gobierno | ⚠️ Solo citada |
| **Decreto 1078/2015** | DUR sector TIC | Reglamentario | ⚠️ Solo citada |
| **Decreto 1079/2023** | Internet comunitario fijo | Modelo comunitario rural | ⚠️ Solo citada |
| **CONPES 3975/2019** | Política Nacional Transformación Digital + IA | Alineación política | ⚠️ Solo citada |
| **CONPES 4069/2021** | Política Nacional CTeI · Misiones | Alineación CTeI | ⚠️ Solo citada |
| **CONPES 4167/2025** | Conectividad Amazonía + territorios fronterizos | **Alta relevancia: Arauca es frontera** | ⚠️ Solo citada |
| **Estrategia Nacional Digital 2023-2026** (DNP) | Ejes: conectividad + habilidades | Alineación estratégica | ⚠️ Solo citada |

#### 2.2.2. Programas financiadores MinTIC — PUNTO CRÍTICO

| Programa                                        | Instrumento                                     | Relevancia Arauquita                            | Estado investigación                                         |
| ----------------------------------------------- | ----------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------ |
| **Casa Bacana Digital**                         | FUTIC · residencial E1+E2 · subsidio CAPEX+OPEX | Alta — 4.000 hogares                            | ⚠️ Existe en Alma-Caribe, ¿aplica Arauca 2026? **Verificar** |
| **Conexiones Residenciales**                    | Alternativo o equivalente                       | Alta                                            | ❌ Sin información                                            |
| **Territorios Digitales**                       | Territorios rurales + étnicos                   | **Muy alta — Arauca es territorio especial**    | ❌ Sin información                                            |
| **Hogares Conectados** (Tipología 03)           | Resolución MinTIC 03689/2023                    | Alta — tarifa E1: $11.917/mes · E2: $26.391/mes | ✅ Documentado en Alma-Caribe                                 |
| **Convenio Marco 790/2023 + CPCV ConectiVIDAd** | Instrumento cofinanciación FTTH                 | Alta                                            | ✅ Documentado en Alma-Caribe                                 |
| **Centros Digitales**                           | Puntos de acceso público                        | Complementario                                  | ⚠️ Solo citado                                               |
| **Fondo Único TIC (FUTIC)**                     | Fuente financiera MinTIC                        | **Fuente 95% del proyecto**                     | ✅ Documentado parcialmente                                   |

> **Alerta SOTA research:** Para Arauquita específicamente, la **tarea más urgente** del E0 es identificar cuál programa MinTIC activo 2026 financia proyectos de conectividad residencial en departamentos como Arauca (fronterizo, IBD alto, rural disperso). Buscar en: (1) Convocatorias vigentes MinTIC/FUTIC, (2) SECOP II contratos similares en Arauca, (3) TDR de proyectos ejecutados en Arauca sector 23.

#### 2.2.3. Normativa regulatoria técnica

| Norma | Materia | Estado trazabilidad |
|-------|---------|---------------------|
| **Resolución MinTIC 03689/2023** | Tipología 03 FTTH · tarifas · subsidios | ⚠️ Citada · NO descargada como PDF |
| **Resolución CRC 5111/2017** | Calidad servicio internet (velocidad mín · latencia) | ⚠️ Citada · NO descargada |
| **Resolución CRC 5050/2016** | Telecomunicaciones | ⚠️ Citada · NO descargada |
| **ITU-T G.984 / G.987 / G.989** | Estándares GPON / XGS-PON / NG-PON2 | ⚠️ Citada · deuda técnica E2 |

### 2.3. Marco metodológico — REUTILIZABLE CON ADAPTACIÓN

| Metodología | Qué tenemos | Nivel de reutilización |
|-------------|------------|------------------------|
| **Árbol de problemas/objetivos** | Plantilla completa (Alma-Caribe) con árbol causa-efecto sector TIC | ✅ 90% reutilizable · cambiar datos IBD Sucre → IBD Arauca 0.494 |
| **Cadena de valor RBM-GAC** | Insumos→Actividades→Productos→Resultados→Impactos para FTTH | ✅ 85% reutilizable |
| **Marco Lógico DNP** | `fig-mga-2--marco-logico.md` con estructura MGA v6.0 | ✅ 80% reutilizable |
| **Productos MGA (sector 23)** | Catálogo 230102x/230108x verificado | ✅ 100% reutilizable |
| **CAPEX/hogar por tipo** | $425.000/hogar (PoC) · benchmark LATAM $1.8-2.8M | ✅ 80% reutilizable · ajustar +25% logística Llanos |
| **Tarifas MinTIC tipología 03** | $11.917 E1 · $26.391 E2 · subsidio estructura | ✅ 100% reutilizable si vigente 2026 |
| **Análisis alternativas** | Plantilla A1/A2/A3 (GPON · HFC · radio) | ✅ 85% reutilizable · añadir satellite/4G LTE Arauca |
| **Matriz de riesgos** | `01-matriz-riesgos.md` con tipología operacional/legal/mercado | ✅ 75% reutilizable · añadir riesgos orden público Arauca |
| **Evaluación económica VPN/TIR/B-C** | `sec-mga-3-1--beneficios-costos.md` | ✅ 70% reutilizable · recalcular con datos Arauquita |
| **Análisis de género + étnico** | `concepto/06-analisis-genero-etnico.md` | ✅ 60% reutilizable · Arauca tiene comunidades Sikuani + llaneros |
| **Análisis ambiental** | `concepto/07-analisis-ambiental.md` | ⚠️ 40% reutilizable · Arauca = CORPORINOQUIA diferente a CARSUCRE |

### 2.4. Referente conceptual — Colombia Digital Cúcuta

> **Fuente:** `7-propuesta-colombia-digital.md` · 34 secciones · $14.129.999.460 COP / 7.500 hogares

| Sección | Mapeo MGA | Reutilización Arauquita |
|---------|-----------|------------------------|
| §1 Identificación + §2 Resumen | MGA §1 | ✅ Estructura adaptable · cambiar municipio, valor, población |
| §3 Alineación política pública | MGA §1.3 | ✅ PND 2022-2026 mismo · agregar CONPES Arauca/Llanos |
| §4 Problema central + árbol | MGA §2.1 | ✅ IBD framework idéntico · datos Arauca IBD 0.494 rank 25 |
| §5-6 Antecedentes + Justificación | MGA §2 narrativo | ✅ 70% reutilizable |
| §7 Marco normativo | MGA §1.2 | ✅ Normas nacionales · ídem |
| §8-9 Participantes + Análisis | MGA §2.4 | ⚠️ Adaptar actores: MinTIC + Gobernación Arauca + Fibergroup + Alcaldía Arauquita |
| §10-11 Población + Objetivos | MGA §2 | ⚠️ Recalcular con datos DANE Arauquita (~58.000 hab) |
| §12 Análisis alternativas | MGA §3-§4 | ✅ Estructura · adaptar tecnología Llanos |
| §13 Metodología actividades | MGA §5 descripción | ✅ Adaptar |
| §14 Criterios elegibilidad | MGA §5 | ✅ Idéntico (estratos 1-2) |
| §15 Cadena de valor + presupuesto | MGA §5 + §6 | ✅ Plantilla · recalcular cantidades para 4.000 hogares |
| §16 Sostenibilidad | MGA §5 | ✅ Fibergroup ESP como garante sostenibilidad |
| §17 Cronograma (18 meses) | MGA §8 | ✅ Adaptar |
| §18 Riesgos | MGA §5 riesgos | ✅ Adaptar + añadir riesgo OOPP Arauca |
| §19 Fuentes financiación | MGA §6 | ⚠️ Adaptar: MinTIC 95% + GobArauca 5% (vs FUTIC 85% + tarifa social 12.5%) |

---

## 3. Inventario de lo que FALTA — Gaps críticos

### 3.1. Gap NIVEL CRÍTICO — Sin resolver bloquea E1

| Gap | Descripción | Acción requerida |
|-----|-------------|-----------------|
| **G-01** | Programa MinTIC activo 2026 que financia Arauquita | SOTA research: convocatorias FUTIC vigentes · ¿Casa Bacana aplica a Arauca? ¿hay TDR? |
| **G-02** | PDM Arauquita 2024-2027 | Descargar PDF oficial · alineación con Plan Municipal |
| **G-03** | PDD Arauca 2024-2027 | Descargar PDF oficial · alineación con Plan Departamental |
| **G-04** | IBD municipal Arauquita (desagregado del departamental 0.494) | MinTIC Colombia TIC · Atlas conectividad desagregado por municipio |
| **G-05** | Atlas cobertura MinTIC para Arauquita | Portal Colombia TIC · cobertura actual operadores por vereda |
| **G-06** | Población y hogares DANE Arauquita 2024-2025 | Geoportal DANE · proyección por estrato |

### 3.2. Gap NIVEL ALTO — Necesario para E2/E3

| Gap | Descripción | Acción requerida |
|-----|-------------|-----------------|
| **G-07** | Contratos SECOP II similares en Arauca (estudios previos) | Búsqueda SECOP II: sector 23 TIC · Arauca · conectividad residencial · 2021-2026 |
| **G-08** | TDR o guía de convocatoria MinTIC vigente | Descargar TDR del programa identificado en G-01 |
| **G-09** | Resolución MinTIC 03689/2023 (PDF oficial) | Descargar desde normativa.mintic.gov.co |
| **G-10** | Plan CORPORINOQUIA 2024 (autoridad ambiental Arauca) | Análisis ambiental E1 + licencias E3 |
| **G-11** | Diseño técnico red Arauquita (Frente B) | DEUDA TÉCNICA — activar brief Frente B en Starting |
| **G-12** | Precios mercado CAPEX/OPEX Arauquita 2026 | SECOP II + cotizaciones formales (Frente C + B) |

### 3.3. Gap NIVEL MEDIO — Para calidad de formulación

| Gap | Descripción | Acción requerida |
|-----|-------------|-----------------|
| **G-13** | Diagnóstico conectividad in-situ Arauquita (Frente D) | Relevamiento campo Sprint S1 |
| **G-14** | PDM Arauquita 2020-2023 (si existe) | Antecedentes · para §5 del proyecto |
| **G-15** | Convenio 790/2023 vigencia 2026 + actualizaciones | Verificar con MinTIC si sigue activo |
| **G-16** | ENTIC Hogares DANE 2024 desagregado por depto | Colombia TIC o DANE API |
| **G-17** | Análisis comunidades étnicas Arauquita | Sikuani · llaneros · afros · ¿PDET? |
| **G-18** | Proyectos BPIN similares en Arauca (SUIFP) | Buscar en DNP SUIFP proyectos aprobados sector 23 Arauca |

---

## 4. Trazabilidad: estado de las fuentes del PoC Alma-Caribe

> **Hallazgo del audit:** El PoC Alma-Caribe tiene un problema sistemático de trazabilidad en los documentos de `iniciativas/`. Las afirmaciones cuantitativas usan 3 tipos de fuentes de confianza diferente:

| Tipo de fuente en Alma-Caribe | Confianza | Ejemplos |
|-------------------------------|-----------|---------|
| **Gold — PDF oficial descargado** | ✅ Alta | PDD Sucre · PDM Coveñas · Datos Abiertos DIVIPOLA |
| **Silver — URL citada sin PDF descargado** | ⚠️ Media | Resolución MinTIC 03689/2023 · Convenio 790/2023 · CONPES 4167 |
| **Bronze — estimación interna / corpus** | ❌ Baja | "8.000 hogares sin conectividad" (estimado E1) · "75% valor intermediarios" (JTBD-campesino corpus) |

**Estándares de trazabilidad aplicados en el PoC:**
- `Q23 antialucinación` definido: toda afirmación cuantitativa territorial → respaldo fuente verificada
- `INDEX_FUENTES.md` documenta 13 fuentes con URL, fecha descarga, errores propios identificados
- `sec-mga-3-1--beneficios-costos.md` documenta la evaluación económica
- **Pero:** datos de magnitud de problema, CAPEX/hogar y tarifas NO tienen PDF en `fuentes-verificadas/` — solo citaciones texto

**Protocolo a aplicar para Arauquita:**
```
Toda afirmación de magnitud → respaldar con fuente PDF descargada en:
/E0--plan-trabajo/0--definicion/fuentes-verificadas-arauquita/
```

---

## 5. Mapa de lo que tenemos vs lo que necesitamos por entregable

```
                    ALMA-CARIBE (Sucre)          ARAUQUITA (Arauca)
                    [INSUMO METODOLÓGICO]        [A CONSTRUIR]
                    
E0 Starting         ✅ Acta ODI (plantilla)       ✅ LISTO (E0 28 abr)
                    ✅ Brief frentes B/C/D         ✅ LISTO

E1 §1·§2·§3·§4      ✅ Árbol problemas (metodol)  ❌ Datos IBD Arauquita
  Diagnóstico        ✅ Marco normativo TIC         ❌ PDM/PDD Arauca
  Alternativas       ✅ Tipología Colombia Digital  ❌ Relevamiento campo (Frente D)
                     ⚠️ Datos son de Sucre          ❌ Actores específicos Arauquita

E2 §5               ✅ Cadena valor RBM-GAC        ❌ Diseño red Arauquita (Frente B)
  Técnico            ✅ Productos MGA (2301xxx)     ❌ Especificación técnica territorio
  Cadena valor       ✅ Estructura modelo red        ❌ Talleres apropiación digital
                     ⚠️ Tecnología = deuda técnica

E3 §6               ✅ Plantilla presupuesto tipo   ❌ Cotizaciones reales Arauca
  Presupuesto        ✅ CAPEX/hogar benchmark        ❌ Precios mercado local
                     ✅ Tarifas MinTIC (nac.)        ❌ Confirmar programa vigente G-01
                     ⚠️ 95% MinTIC sin identificar   ❌ Mecanismo SGR vs FUTIC

E4 §7·§8+BPIN       ✅ Plantilla VPN/TIR/B-C        ❌ Parámetros económicos Arauca
  Evaluación         ✅ Cronograma tipo 18 meses      ❌ Cargue MGA Web
  Económica          ✅ Matriz riesgos tipo           ❌ BPIN DNP
```

---

## 6. Marco conceptual consolidado — Lo que sí tenemos completo

### 6.1. Problema central (adaptable directamente)

> **Deficiente acceso a internet residencial de calidad y bajas competencias digitales en los hogares del municipio de Arauquita, departamento de Arauca, que limita el desarrollo económico, social y el aprovechamiento de las TIC como herramienta de transformación territorial.**

- **Dimensión técnica:** IBD Arauca 0.494 (puesto 25/33) — worse than Norte de Santander (0.419/15). El IBD mide 4 dimensiones: Acceso Material (31%) · Habilidades Digitales (34.7%) · Aprovechamiento (30.8%) · Motivación (3.5%).
- **Dimensión geográfica:** Arauquita es municipio de Llanos Orientales con centros poblados dispersos (Puerto Nariño, Caño Limón, Zamora) con conectividad muy limitada.
- **Dimensión económica:** Economía petrolera + agropecuaria + minería. Fibergroup como ESP local con presencia establecida.
- **Dimensión social:** Potencial comunidades étnicas (verificar Sikuani / afros) · zona de influencia ex-conflicto.

### 6.2. Objetivo general (propuesta)

> **Aumentar los niveles de acceso y uso de internet en el municipio de Arauquita del departamento de Arauca, para el fortalecimiento de la conectividad, las competencias digitales y la reducción de la brecha digital en 4.000 hogares.**

### 6.3. Alternativas a analizar en E1 (MGA §3-§4)

| Alternativa | Descripción | Pertinencia Arauquita |
|-------------|-------------|----------------------|
| **A1** | FTTH/GPON cabecera municipal + centros poblados principales | Alta · si hay backbone MinTIC cercano |
| **A2** | Radio/microondas (Point-to-Multipoint) para zonas dispersas | Alta · Llanos con baja densidad |
| **A3** | Modelo mixto GPON cabecera + 4G LTE / radio veredas | Muy alta · tecnología más realista Arauca |
| **A4** | Satélite LEO (Starlink) para zonas más remotas | Media · costo ARPU alto |
| **Seleccionada** | Deuda Técnica — definir con Frente B en E2 | — |

### 6.4. Fuentes de financiación (estructura)

| Fuente | % | Mecanismo | Estado |
|--------|:-:|-----------|--------|
| **MinTIC / FUTIC** | 95% | Programa a identificar (SOTA research) | ❌ Gap G-01 |
| **Gobernación Arauca** | 5% | Recursos propios departamento | ✅ Confirmado usuario |
| Fibergroup (OPEX operación) | 0% ppto / garantía sostenibilidad | ESP titular · modelo comercial post-proyecto | ✅ Confirmado |

---

## 7. Plan de acción para cerrar gaps

### 7.1. SOTA Research — Prioridad inmediata (antes de E1)

> **Objetivo:** Identificar el programa MinTIC vigente más afín + descargar TDR + localizar contratos SECOP II de referencia.

| Tarea | Dónde buscar | Output esperado |
|-------|-------------|-----------------|
| Identificar convocatoria MinTIC vigente 2026 para Arauca | mintic.gov.co / futic.gov.co / cpcv | Nombre programa + TDR descargado |
| Buscar contratos SECOP II ejecutados en Arauca sector 23 TIC | secop.gov.co (filtro: Arauca · TIC · 2021-2026) | 3-5 contratos referencia con estudios previos |
| Verificar vigencia Convenio 790/2023 + tipología 03 en Arauca | normativa.mintic.gov.co | Resolución + adendas 2026 |
| Atlas cobertura MinTIC Arauquita | colombiatic.mintic.gov.co · mapa | Mapa cobertura actual por vereda |
| Proyectos SUIFP sector TIC Arauca | suifp.dnp.gov.co | Proyectos BPIN similares |

### 7.2. Fuentes territoriales — Descargar antes de S1

| Documento | URL probable | Prioridad |
|-----------|-------------|-----------|
| PDM Arauquita 2024-2027 | arauquita-arauca.gov.co/plan-desarrollo | 🔴 Crítico |
| PDD Arauca 2024-2027 | arauca.gov.co o tangara.gov.co | 🔴 Crítico |
| IBD 2024 desagregado municipal | mintic.gov.co (Informe IBD oct 2025) | 🔴 Crítico |
| ENTIC Hogares DANE 2024 (Arauca) | dane.gov.co / colombiatic | 🔴 Crítico |
| DIVIPOLA Arauquita (CSV) | datos.gov.co | 🟠 Alto |
| Plan CORPORINOQUIA | corporinoquia.gov.co | 🟠 Alto |
| Resolución MinTIC 03689/2023 | normativa.mintic.gov.co | 🔴 Crítico |

---

## 8. Estado por módulo MGA

| Módulo MGA | Descripción | % Completado | Fuentes con respaldo |
|------------|-------------|:------------:|---------------------|
| **§1 Identificación** | Nombre, sector, dependencia, valor, objetivo, localización | 25% | Solo estructura, datos territoriales pendientes |
| **§2 Problema + Diagnóstico** | IBD · árbol causas/efectos · magnitud · población | 30% | IBD departamental 0.494 ✅ · municipal ❌ |
| **§3 Alternativas** | A1/A2/A3 tecnología red | 20% | Plantilla ✅ · datos Arauquita ❌ |
| **§4 Alternativa óptima** | Selección justificada | 10% | Deuda Técnica Frente B |
| **§5 Cadena de valor** | RBM-GAC + productos + cronograma + riesgos | 25% | Plantilla ✅ · especificación ❌ |
| **§6 Presupuesto** | CAPEX/OPEX · fuentes · plurianual | 15% | Benchmark ✅ · cotizaciones ❌ |
| **§7 Evaluación económica** | VPN/TIR/B-C | 10% | Plantilla ✅ · parámetros ❌ |
| **§8 Resumen + Programación** | Cronograma + BPIN | 5% | Estructura ✅ · datos ❌ |

---

## 9. Archivos de referencia para E1-E4

| Archivo | Ruta | Uso |
|---------|------|-----|
| Colombia Digital (ref) | `0--definicion/7-propuesta-colombia-digital/7-propuesta-colombia-digital.md` | Referente estructural completo |
| Problema Casa Bacana | `alma-caribe/iniciativas/1-casa-bacana-digital/concepto/01-problema.md` | Árbol de problemas adaptable |
| Tarifas MinTIC | `alma-caribe/iniciativas/1-casa-bacana-digital/concepto/02-tarifas-oficiales-MinTIC.md` | Marco tarifario tipología 03 |
| Presupuesto base tipo | `alma-caribe/iniciativas/1-casa-bacana-digital/financiero/00-presupuesto-base-tipo.md` | Plantilla CAPEX/OPEX |
| Diseño FTTH | `alma-caribe/iniciativas/1-casa-bacana-digital/diseno/01-modelo-redes-FTTH.md` | Modelo técnico (deuda técnica B) |
| Matriz riesgos | `alma-caribe/iniciativas/1-casa-bacana-digital/implementacion/matriz-riesgos/01-matriz-riesgos.md` | Riesgos tipo |
| Marco normativo | `alma-caribe/mga/99--sources/src-mga-1--referencias.md` | Normativa TIC completa |
| Índice fuentes | `alma-caribe/_meta/fuentes-verificadas/INDEX_FUENTES.md` | Modelo de qué fuentes descargar |

---

## 10. Decisiones pendientes de confirmación

| # | Decisión | Quién decide | Cuándo |
|:-:|----------|-------------|--------|
| D-01 | Programa MinTIC concreto (Casa Bacana / Conexiones Residenciales / otro) | SOTA research E0 | Antes de S1 |
| D-02 | Alcance exacto hogares (4.000 objetivo o máximo posible con presupuesto) | Usuario + Fibergroup | S1 D1 |
| D-03 | Tecnología de red (GPON / radio / mixto) | Frente B | S2 D1 |
| D-04 | Municipios/centros poblados priorizados dentro de Arauquita | Frente D campo | S1 D2-D3 |
| D-05 | Mecanismo cofinanciación Gobernación Arauca (convenio / aporte directo) | Usuario | S1 |

---

*Audit v1.0 · 2026-04-27 · CCMS · Próxima actualización: al cierre de SOTA research (G-01 a G-06)*
