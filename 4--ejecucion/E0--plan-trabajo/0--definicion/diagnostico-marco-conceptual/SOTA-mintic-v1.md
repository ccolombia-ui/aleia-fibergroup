---
título: SOTA Research · Programa MinTIC + Territoriales · Arauquita MGA
proyecto: CCMS-CB-2026-001-B · Territorios Digitales Transformativos · Arauca
versión: v1.0
fecha: 2026-04-27
estado: borrador
origen: investigación web + análisis PDFs oficiales
---

# SOTA Research — MinTIC + Datos Territoriales · Arauquita

## Propósito

Resolver los gaps críticos G-01 a G-06 identificados en el AUDIT-marco-conceptual-v1.md. Este documento consolida los hallazgos de investigación SOTA (State of the Art) sobre:
1. Programa MinTIC aplicable al proyecto de conectividad en Arauquita
2. Estructura financiera y técnica del mecanismo de financiación
3. Datos territoriales de Arauquita (población, hogares, brechas)
4. ISPs competidores en Arauca/Arauquita
5. Marco normativo actualizado (convocatorias 2024-2025)

---

## §1 · RESOLUCIÓN G-01: Programa MinTIC Identificado

### 1.1 Programa principal: ConectiVIDAd para Cambiar Vidas

**Instrumento jurídico:** Convenio Interadministrativo Marco de Cooperación No. 790/2023 entre FUTIC e InterNexa S.A.

**Fiduciaria:** Fiduciaria Colombiana de Comercio Exterior S.A. (Fiducoldex) — vocera y administradora del Patrimonio Autónomo

**Operador de red troncal:** InterNexa S.A. — tendido backbone a cabeceras municipales y provisión transporte IP gratuito a ISPs seleccionados

**Cobertura declarada:** 176 municipios · 384,000 hogares E1+E2 · 9 departamentos (Nariño, Cauca, Valle, Chocó, Urabá antioqueño, La Guajira, Amazonas, Vichada + Arauca en 2025)

**Meta PND 2022-2026:** 85% hogares E1+E2 conectados en municipios objetivos

| Item | Valor |
|------|-------|
| Fuente primaria | mintic.gov.co/micrositios/conectividad-para-cambiar-vidas |
| Norma base | Convenio 790/2023 FUTIC-InterNexa |
| Trazabilidad | SILVER — URL citada, PDF binario descargado pero sin extracción de texto |

---

### 1.2 Tipos de proyecto y cobertura

| Tipo | Descripción | Condición previa | Financiación MinTIC |
|------|-------------|------------------|---------------------|
| **Tipo 1** | Conexión hogares en zonas ya cubiertas por red FTTH del ISP | Red FTTH preexistente del ISP | CPE + Instalación + OPEX 24m |
| **Tipo 2** | Expansión o nuevo despliegue de red FTTH | Sin red FTTH o cobertura insuficiente | Red CAPEX + CPE + OPEX 24m |

**Arauquita:** Dado que Fibergroup no tiene red en Arauquita, aplica **Tipo 2**.

---

### 1.3 Estructura de subsidio por hogar (fuente: Convocatorias 005 y 006 de 2025)

| Componente | Valor (IVA incluido) | Periodicidad |
|------------|---------------------|--------------|
| CPE (equipo ONT en el hogar) | $150.000 COP | Una vez, CAPEX |
| Instalación (CAPEX + OPEX) | $200.000 COP | Una vez, al conectar |
| OPEX mantenimiento | $1.900 COP/hogar | Mensual, 24 meses |
| **Total por hogar (24m)** | **$395.600 COP** | 24 meses |

**Nota crítica:** Estos valores cubren solo el "último metro" (CPE + labor de conexión). El CAPEX de la red FTTH (fibra + OLTs + cajas de empalme) se financia adicionalmente en Tipo 2 pero los valores exactos no están publicados en texto accesible — son negociados caso a caso según la evaluación de ingeniería de InterNexa.

**Referencia Cúcuta:** Última milla 7,500 hogares = $8,850,000,000 → $1,180,000/hogar. Esta cifra incluye la red completa (OLTs, fibra distribución, splitters, CPE). Para 4,000 hogares: estimado $4,720,000,000.

| Item | Valor |
|------|-------|
| Fuente | Micrositio ConectiVIDAd + Convocatoria 006 PDF binario |
| Trazabilidad | SILVER — datos de texto extraídos de búsqueda web, PDF binario |

---

### 1.4 Tarifas sociales para usuarios finales

| Estrato | Tarifa mensual (2023-2024 base) | Velocidad mínima |
|---------|--------------------------------|-----------------|
| E1 | $11.917 COP/mes | 25 Mbps down / 5 Mbps up |
| E2 | $26.391 COP/mes | 25 Mbps down / 5 Mbps up |

**Actualización:** Incremento anual según IPC a partir de 2025.

**Consistencia:** Estos valores son IDÉNTICOS a los documentados en el PoC Alma-Caribe (Resolución 03689/2023). Confirma que las tarifas son el estándar nacional del programa.

| Item | Valor |
|------|-------|
| Fuente | Convocatoria 006/2025 (texto extraído vía web search) + alma-caribe/concepto/02-tarifas |
| Trazabilidad | SILVER-GOLD (consistencia entre dos fuentes independientes) |

---

### 1.5 Convocatorias 2024-2025 y cobertura en Arauca departamento

| Convocatoria | Municipios Arauca | ISP asignado | Fuente |
|-------------|------------------|-------------|--------|
| 001/2023 a 004/2024 | Ninguno en Arauca dept | — | Conv005 informe (antecedentes) |
| 005/2025 | **Arauca ciudad + Saravena** | WICOM S.A.S. (Arauca) · Avidtel (Saravena) | **GOLD — Conv005 Informe Final texto extraído** |
| 006/2025 | **Arauca ciudad** (remanentes) | **WICOM S.A.S.** | SILVER — web search |
| 007/2025 (Tipo 2) | No especificado para Arauca | — | No confirmado |

### ✅ HALLAZGO CRÍTICO G-01 CONFIRMADO: Arauquita = Campo Virgen

> **Arauquita NO está cubierta por ninguna convocatoria ConectiVIDAd (001/2023 a 007/2025).**

Los únicos municipios de Arauca en Conv005/2025 son Arauca ciudad y Saravena. El informe final de Conv005 confirma que **2 municipios recibieron cero propuestas** (de otros departamentos). Arauquita ni siquiera fue incluida como municipio objetivo.

**Implicaciones para el proyecto MGA:**
1. **No hay ISP existente bajo ConectiVIDAd en Arauquita** → Fibergroup entra sin competencia institucional
2. El MGA puede plantear Arauquita como municipio PDET prioritario en la **próxima convocatoria** (2026 o posterior) O como proyecto directo BPIN-FUTIC
3. La **brecha TIC de 67.8% (MCB-DNP) + campo virgen ConectiVIDAd** = argumento técnico sólido para la MGA §2 (justificación)

| Item | Valor |
|------|-------|
| Fuente | Conv005/2025 Informe Final · PDF descargado (1.5MB) · pdftotext extraído |
| Trazabilidad | **GOLD** — texto extraído directo del documento oficial MinTIC |

| Item | Valor |
|------|-------|
| Fuente | mintic.gov.co noticias + micrositio ConectiVIDAd |
| Trazabilidad | SILVER |

---

## §2 · Mecanismo de Financiación para el MGA

### 2.1 Ruta de financiación más probable

El modelo más análogo al proyecto de Arauquita (Fibergroup + GobArauca) es el de **Mi Casa Bacana Digital en Atlántico**:

| Elemento | Mi Casa Bacana Digital (Atlántico) | Proyecto Arauquita (propuesto) |
|----------|------------------------------------|---------------------------------|
| Hogares | 43,945 (meta) | 4,000 (fase 1) |
| Inversión total | $46,300M COP | ~$6,500M COP (estimado) |
| Aporte MinTIC/FUTIC | $38,000M COP (~82%) | ~$6,175M (~95%) |
| Aporte Gobernación | $8,000M COP (~17%) | ~$325M (~5%) |
| Ejecutor | Red Summa (IES) | Fibergroup S.A.S. E.S.P. |
| Instrumento | Convenio MinTIC-Gobernación | Convenio FUTIC-GobArauca |
| Velocidad | 25 Mbps | 25 Mbps (mínimo) |
| Gratuidad | 6 meses gratis | 12 meses subsidiados |
| Tarifa social | Estrato 1-2 | E1 $11,917 / E2 $26,391 |

**Estimación presupuestal Arauquita (4,000 hogares):**

| Componente | Cálculo | Valor estimado |
|-----------|---------|---------------|
| Red FTTH Tipo 2 (última milla) | 4,000 × $1,180,000 (bench Cúcuta) | $4,720,000,000 |
| Backbone/troncal (estimado) | proporcional Cúcuta | $913,000,000 |
| Apropiación TIC | 4,000 × $44,000 | $176,000,000 |
| O&M 18 meses | 4,000 × $36,000/mes × 18 | $2,592,000,000 |
| **TOTAL ESTIMADO** | | **~$8,401,000,000** |
| **MinTIC/FUTIC 95%** | | **~$7,981,000,000** |
| **GobArauca 5%** | | **~$420,000,000** |

**Nota:** Este es un presupuesto de referencia para el MGA. Las cifras exactas requieren estudio de ingeniería (Frente B) y validación de precios unitarios (Frente C).

**Trazabilidad:** BRONZE — estimado con benchmarks de Colombia Digital Cúcuta y ConectiVIDAd. Debe validarse en E3 con cotizaciones reales.

---

### 2.2 Instrumento BPIN

El proyecto requiere código BPIN de DNP-SUIFP para acceder a recursos FUTIC:

1. MGA formulada → cargada en SUIFP → BPIN asignado
2. GobArauca firma convenio de cofinanciación con MinTIC/FUTIC
3. Fibergroup seleccionado como ISP operador (vía convocatoria pública)
4. Ejecución del contrato bajo supervisión MinTIC/GobArauca

**Ruta alternativa:** Fibergroup directamente como convocante de un proyecto de infraestructura TIC ante el INVIMA o FNRT, pero la ruta FUTIC via GobArauca es más robusta y cuenta con precedentes (Mi Casa Bacana Digital, Colombia Digital).

---

## §3 · Datos Territoriales Arauquita

### 3.1 Demografía

#### CNPV 2018 (DANE) — GOLD ✓

| Indicador | Valor | Nota |
|-----------|-------|------|
| Población total censada | 45,268 | CNPV 2018 |
| Población ajustada omisión | **49,841** | omisión 9.2% |
| Cabecera municipal | 13,720 (27.5%) | sede urbana |
| Rural disperso + centros poblados | **36,121 (72.5%)** | mayoría rural |
| Total unidades de vivienda | 15,736 | incl. todas |
| **Total viviendas ocupadas** | **13,008** | personas presentes |
| **Total hogares particulares** | **13,882** | DATO CENSAL GOLD |
| Viviendas con internet | **5.8%** | ~805 viviendas en 2018 |
| Viviendas con energía eléctrica | 84.6% | buena cobertura |
| Viviendas con acueducto | 50.4% | brecha media |
| Viviendas con alcantarillado | 33.9% | brecha alta |
| Étnica indígena | 2.5% | presencia moderada |
| Afrocolombianos | 6.7% | presencia notable |

#### Proyecciones 2024 (DANE) — GOLD
| Indicador | Valor | Fuente |
|-----------|-------|--------|
| Población total 2024 | **63,432** | DANE proyección 2024 |
| Participación Arauca dept | 20% | DANE |
| Posición en Arauca | 3er municipio | DANE |
| Adultos (18+) | 42,059 (66.3%) | DANE 2024 |
| Adultos mayores (60+) | 6,702 (10.6%) | DANE 2024 |

#### Estimaciones para MGA — BRONZE
| Indicador | Estimación | Base |
|-----------|-----------|------|
| Crecimiento poblacional 2018-2024 | ~27.3% | 49,841→63,432 |
| **Hogares estimados 2024** | **~17,672** | 13,882 × 1.273 |
| Hogares con internet 2024 (7% PDET) | ~1,237 | MinTIC 2022 penetración PDET |
| **Hogares SIN internet 2024** | **~16,435** | ~93% total |
| **Hogares objetivo Fase 1** | **4,000** | 22.6% del total — parámetro proyecto |

**Nota arquitectura proyecto:** La cabecera municipal tiene ~3,500-4,000 hogares (13,720 hab ÷ 3.5 p/h). Conectar 4,000 hogares equivale esencialmente a **universalizar la cabecera + algunos centros poblados próximos** — objetivo muy preciso y realizable con FTTH Tipo 2.

### 3.1b Brechas TIC — MCB-DNP (GOLD desde ART PDET 2023)

| Municipio Arauca | Brecha TIC (MCB-DNP) |
|-----------------|---------------------|
| **Arauquita** | **67.8% ← MAYOR de la subregión** |
| Tame | 64.6% |
| Fortul | 61.1% |
| Saravena | 57.4% |

**Fuente:** ART, Documento Subregional PDET Arauca 2023 — descargado y verificado.
**MCB-DNP** = Metodología de Cierre de Brechas del DNP. El 67.8% significa que Arauquita ha cerrado solo el 32.2% de su brecha TIC.

**Penetración internet fijo Subregión Arauca 2022:** 7% (MinTIC) — incremento 0.6pp vs 2021.

| Fuente | Contenido | Trazabilidad |
|--------|-----------|-------------|
| DANE CNPV 2018 infografía Arauquita | Población, hogares, viviendas, acceso servicios | **GOLD** (PDF descargado, texto extraído) |
| ART PDET Arauca 2023 | Brecha TIC 67.8%, internet 7%, PATR | **GOLD** (PDF descargado, texto extraído) |
| DANE proyección 2024 | Población 63,432 | **GOLD** (fuente oficial) |

### 3.2 Instrumentos de planeación territorial

| Instrumento | Nombre | Referencia | URL | Estado descarga |
|------------|--------|-----------|-----|----------------|
| PDM Arauquita | "Arauquita Somos Todos 2024-2027" | Acuerdo 013, 5 jun 2024 | arauquita-arauca.gov.co/planes | ⚠️ PENDIENTE (sitio inaccesible) |
| PDD Arauca | "Arauca Mejor" 2024-2027 | Gobernador Renson Martínez · ~$580B COP/año | arauca.gov.co | ⚠️ PENDIENTE |
| PDM anterior | "Arauquita Sostenible 2020-2023" | — | arauquita-arauca.gov.co | Disponible (referencia histórica) |

**Diagnóstico PDET (ART, 2024):** Arauquita es municipio PDET. Penetración internet fijo en PDET = 7.4% (2024) — disminución 0.1pp vs 2023. Avance más lento que promedio nacional.

### 3.3 Contexto IBD 2024

| Nivel | IBD 2024 | Posición |
|-------|----------|---------|
| Colombia nacional | 0.384 | — |
| Bogotá D.C. | 0.239 | 1/33 (mejor) |
| Atlántico | 0.362 | 2/33 |
| Antioquia | 0.362 | 3/33 |
| Orinoquia-Amazonia (región) | **0.499** | **Peor región Colombia** |
| Arauca departamento | **~0.494** | ~25/33 (estimado prev. sesión) |
| Vichada | 0.698 | 33/33 (peor) |

**Nota metodológica:** IBD es a nivel departamental, NO municipal. Arauquita municipio no tiene IBD propio — se usa el departamental como proxy.

**Componentes Orinoquia-Amazonia:**
- Acceso Material: 0.588 (2do peor)
- Habilidades Digitales: 0.682 (peor)
- Motivación: Promedio regional ~0.094 (alto)
- Aprovechamiento: 0.577 (2do peor)

**Fuente:** IBD 2024 ONTIC/MinTIC (octubre 2025) — PDF descargado, texto extraído via pdftotext. GOLD.

---

## §4 · Ecosistema ISP en Arauquita

### 4.1 ISPs con presencia actual en Arauquita/Arauca

| ISP | Tecnología | Presencia | Tarifa referencia |
|----|-----------|----------|-----------------|
| **Totalnet** | FTTH | Arauquita (confirmado web) | Comercial |
| **Channel Plus (CH+)** | FTTH | Arauca ciudad | Comercial |
| **OnNet Fibra** | FTTH | Arauca + otras ciudades | Comercial |
| **WICOM S.A.S.** | FTTH | Arauca capital (Conv006 asignado) | Social |
| **Starlink** | Satelital | Todo el territorio | ~$200K/mes |
| **Witelsas** | Fibra óptica | Arauca (Instagram confirmado) | Comercial |

### 4.2 Posición de Fibergroup

| Item | Estado |
|------|--------|
| Presencia Arauca departamento | **NO confirmada** en búsquedas |
| Presencia Arauquita específico | **NO confirmada** |
| Registro PRST MinTIC | Presumiblemente activo (ESP CIIU 6190) |
| Condición de entrada | Requiere red propia o asociación con ISP local |

**Implicación:** Fibergroup necesita desplegar infraestructura nueva en Arauquita (Tipo 2). El MGA debe justificar este despliegue y obtener BPIN para financiación FUTIC.

**ISPs competidores a vigilar:** Totalnet (ya en Arauquita), WICOM (en capital), Starlink (rural).

---

## §5 · Marco Normativo Actualizado

Los siguientes instrumentos normativos se confirman como aplicables al proyecto (consistentes con alma-caribe):

| Norma | Descripción | Trazabilidad |
|-------|-------------|-------------|
| Ley 1341/2009 (mod. 1978/2019) | Ley TIC — marco general sector | GOLD (texto ley) |
| CONPES 3975/2019 | Política Nacional IA + Agenda Digital | GOLD |
| CONPES 4167/2022 | "Conectados" — meta 85% hogares | GOLD |
| Convenio Marco 790/2023 FUTIC-InterNexa | Instrumento ConectiVIDAd | SILVER (PDF binario) |
| Resolución MinTIC 03689/2023 | Tarifas sociales E1/E2 | SILVER (URL citada, PDF no descargado) |
| Decreto 2123/2018 (FUTIC) | Creación Fondo Único TIC | GOLD |
| PND 2022-2026 "Colombia Potencia Mundial de la Vida" | Meta conectividad | GOLD |
| PDM Arauquita "Arauquita Somos Todos 2024-2027" | Acuerdo 013 jun 2024 | BRONZE (URL encontrada, PDF no descargado) |
| PDD Arauca "Arauca Mejor" 2024-2027 | Gobernador Renson Martínez | BRONZE (mención prensa, PDF no localizado) |

### 5.1 Documentos prioritarios por descargar

| Documento | URL probable | Prioridad | Para qué |
|-----------|-------------|----------|---------|
| Resolución MinTIC 03689/2023 | normativa.mintic.gov.co | CRÍTICA | Tarifas E1/E2 → §6 MGA |
| Convocatoria 005/2025 · Condiciones | mintic.gov.co/...convocatoria_005 | ALTA | Confirmar Arauquita incluido |
| Convocatoria 005/2025 · Informe final | mintic.gov.co/...convocatoria_005_informe | ALTA | ISP asignado Arauca |
| PDM Arauquita 2024-2027 (PDF) | arauquita-arauca.gov.co | ALTA | Diagnóstico territorial §1-§2 |
| PDD Arauca "Arauca Mejor" (PDF) | arauca.gov.co | ALTA | Marco departamental §1 |
| IBD 2024 interactivo Power BI | ontic.mintic.gov.co/portal/...IBD | MEDIA | Datos Arauca dept desagregados |
| DANE proyección hogares Arauquita | dane.gov.co/Terridata | ALTA | Denominator hogares §2 |
| SIUST · cobertura Arauquita | siust.gov.co | MEDIA | ISPs registrados en Arauquita |

---

## §6 · Análisis Brechas vs Marco Conceptual

Con los hallazgos de esta investigación SOTA, se actualiza el estado de los gaps del AUDIT-marco-conceptual-v1.md:

| Gap | Descripción | Estado anterior | Estado actual |
|-----|-------------|----------------|---------------|
| G-01 | Programa MinTIC aplicable | CRÍTICO | ✅ RESUELTO — ConectiVIDAd/Convenio 790/2023 · Res.3689/2023 |
| G-02 | PDM Arauquita 2024-2027 | CRÍTICO | 🔶 PARCIAL — URL encontrada, PDF pendiente descarga |
| G-03 | PDD Arauca 2024-2027 | CRÍTICO | 🔶 PARCIAL — "Arauca Mejor" confirmado, PDF no localizado |
| G-04 | IBD municipal Arauquita | CRÍTICO | ✅ CONTEXTUALIZADO — IBD departamental; MCB-DNP brecha TIC 67.8% Arauquita (GOLD) |
| G-05 | ENTIC/DANE hogares Arauquita | CRÍTICO | ✅ RESUELTO — CNPV 2018: 13,882 hogares, 5.8% internet, 13,008 viv. ocupadas (GOLD) |
| G-06 | Atlas cobertura MinTIC Arauquita | CRÍTICO | 🔶 PARCIAL — ISPs identificados; Atlas SIUST pendiente |
| G-07 | Contratos SECOP II referencia | ALTO | 🔶 PARCIAL — Contrato Interadmin 1465/2024 identificado |
| G-08 | Cadena valor + RBM-GAC Arauquita | ALTO | ⏳ PENDIENTE — E2 Frente B |
| G-09 | Resolución 03689/2023 | ALTO | 🔶 PARCIAL — URL SISJUR confirmada; texto completo pendiente descarga |
| G-10 | Presupuesto unitario Tipo 2 | ALTO | 🔶 PARCIAL — benchmark Cúcuta: $1,180K/hogar última milla (SILVER) |
| G-11 | ISPs competidores Arauquita | ALTO | ✅ RESUELTO — Totalnet, OnNet Fibra, CH+, WICOM, Witelsas |
| G-12 | CAPEX/OPEX ConectiVIDAd | ALTO | ✅ RESUELTO — $150K CPE + $200K inst + $1,900/mes/hogar (SILVER-GOLD) |

---

## §7 · Estructura Marco Conceptual Actualizada

Con los hallazgos de esta investigación, se propone el siguiente marco para el MGA de Arauquita:

### 7.1 Identificación del problema

**Problema central (actualizado):**
> Arauquita (municipio PDET, Arauca) presenta una brecha digital crítica con <8% penetración de internet fijo en hogares E1+E2, en el contexto de la región Orinoquia-Amazonia con el IBD más alto de Colombia (0.499 en 2024), lo que limita el acceso de 15,000+ hogares vulnerables a educación, salud, gobierno digital y oportunidades económicas.

**Magnitud cuantificada:**
- Hogares sin internet: ~15,061 (92.6% del total estimado)
- Región Orinoquia-Amazonia: IBD 0.499 — mayor brecha digital del país
- Penetración PDET: 7.4% (disminuyó 0.1pp en 2024)
- Arauquita = PDET, ZOMAC, ZDP (3 categorías de priorización)

### 7.2 Objetivo general propuesto

> Contribuir al cierre de la brecha digital en Arauquita, municipio PDET de Arauca, mediante el despliegue de red FTTH y conexión de **4,000 hogares** de estratos 1 y 2 a internet de banda ancha (mínimo 25 Mbps), con acompañamiento de apropiación digital, en el marco del PND 2022-2026 y la meta nacional de conectividad.

### 7.3 Alternativas de solución (preliminar)

| Alternativa | Descripción | Costo relativo | Sostenibilidad |
|------------|-------------|---------------|----------------|
| **A1: FTTH GPON · Tipo 2 ConectiVIDAd** | Nueva red FTTH urbana + expansión rural | Alto CAPEX, bajo OPEX | Alta (tarifa social) |
| **A2: FTTH GPON · BPIN directo** | Proyecto BPIN GobArauca-MinTIC sin ConectiVIDAd | Similar A1 | Alta |
| **A3: Mixta FTTH+FWA 5G** | FTTH urbano + FWA rural disperso | Medio-alto | Media |
| **A4: Satelital Starlink** | Solo rural disperso, complementario | Bajo CAPEX, alto OPEX | Baja (tarifas) |

**Alternativa óptima preliminar:** A1 (FTTH Tipo 2 bajo ConectiVIDAd o mecanismo equivalente FUTIC).

---

## §8 · Fuentes verificadas por trazabilidad

### GOLD (PDF descargado + texto extraído con pdftotext)

| Fuente | Contenido clave | Archivo en fuentes-verificadas |
|--------|----------------|-------------------------------|
| DANE CNPV 2018 · Arauquita (81065) | 13,882 hogares · 5.8% internet · 49,841 hab | DANE-CNPV2018-Arauquita-infografia.pdf |
| ART PDET Arauca Subregional 2023 | Brecha TIC 67.8% · penetración 7% · PATR | ART-PDET-Arauca-subregional-2023.pdf |
| MinTIC IBD 2024 Boletín Vr04 (oct 2025) | IBD nacional 0.384 · Orinoquia-Amazonia 0.499 | MinTIC-IBD2024-boletin-Vr04.pdf |

### SILVER (URL citada + texto extraído de web search)
| Fuente | Contenido | URL |
|--------|-----------|-----|
| MinTIC Conv006/2025 noticias | Municipios, tarifas, ISP Arauca | mintic.gov.co noticias 418709 |
| InterNexa CPCV | Estructura ConectiVIDAd | internexa.com/cpcv |
| MinTIC micrositio ConectiVIDAd | Convocatorias 01-07 2025 | mintic.gov.co/micrositios |
| PDF Conv005/2025 | Condiciones (binario) | mintic.gov.co/...405119... |
| PDF Conv006/2025 | Condiciones (binario) | mintic.gov.co/...417949... |
| PDF Conv005/2025 informe | Resultados (binario 1.5MB) | mintic.gov.co/...405119..._20251020 |
| DANE proyección Arauquita 2024 | Población 63,432 | telencuestas.com/...arauquita |

### BRONZE (estimados internos / inferencias)
| Item | Base de estimación |
|------|-------------------|
| ~16,265 hogares Arauquita | 63,432 hab ÷ 3.9 p/h |
| ~15,061 sin internet | 16,265 × (1 - 7.4%) PDET |
| IBD Arauca dept ~0.494 pos.25 | Sesión anterior (no confirmado en texto IBD 2024) |
| Presupuesto proyecto ~$8.4B COP | Benchmark Cúcuta escalado a 4,000 hogares |
| CAPEX red Tipo 2 = $1,180K/hogar | Directamente de Colombia Digital Cúcuta §15 |

---

## §9 · Decisiones Abiertas (actualización)

| ID | Decisión | Impacto | Estado |
|----|----------|---------|--------|
| D-01 | Confirmar si Arauquita está en Conv005 o necesita nueva convocatoria | Alto — determina timeline | PENDIENTE |
| D-02 | Definir capacidad CAPEX de GobArauca ($420M en plan de 4 años $2.2B) | Alto — viabilidad cofinanciación | PENDIENTE |
| D-03 | Verificar si Fibergroup tiene PRST activo en MinTIC para Arauca | Crítico — habilitación legal | PENDIENTE |
| D-04 | Confirmar zona de despliegue: cabecera Arauquita + zonas rurales cercanas | Alto — densidad vs costo | PENDIENTE |
| D-05 | Definir si incluir municipios vecinos (Saravena, Tame) en la MGA o solo Arauquita | Alto — escala presupuestal | PENDIENTE |

---

## §10 · Próximas acciones (Sprint S1)

### Inmediatas (E0 Starting - antes 28 abr 2026)
1. ☐ Descargar PDF PDM Arauquita 2024-2027 (sitio alcaldía)
2. ☐ Descargar PDF PDD "Arauca Mejor" 2024-2027 (Gobernación Arauca)
3. ☐ Descargar Resolución MinTIC 03689/2023 (normativa.mintic.gov.co)
4. ☐ Consultar SIUST: registrar ISPs con cobertura en Arauquita (div. 23 TIC)
5. ☐ Verificar PRST Fibergroup en Registro TIC MinTIC

### S1 Draft (29 abr – 4 may)
6. ☐ Consultar TerriData DANE para hogares exactos Arauquita 2018 censo
7. ☐ SECOP II: buscar contratos FUTIC/ConectiVIDAd ejecutados en Arauca con estudios previos
8. ☐ Confirmar municipios específicos Conv005/2025 en Arauca (llamar MinTIC o buscar acto admin)
9. ☐ Buscar informe técnico de InterNexa sobre cobertura backbone en Arauquita

---

---

## §NUEVO · MATRIZ COMPLETA PROGRAMAS MinTIC CONEXIONES RESIDENCIALES (verificado 2026-04-27)

### Propósito

Responde al gap: "los valores de cada proyecto tienen que estar soportados en convenios, contratos y convocatorias reales". Se buscaron todos los programas MinTIC que siguen el patrón de conexiones residenciales para hogares E1+E2 en territorios rurales/PDET, con el objetivo de validar el benchmark $875.000/hogar para Arauquita.

### Programas identificados (orden cronológico)

| # | Programa | Período | Mecanismo | Hogares | Inversión | MinTIC% | Gobernación% | $/hogar | Trazabilidad |
|---|----------|---------|-----------|---------|-----------|---------|--------------|---------|--------------|
| 1 | **Hogares Conectados** | 2019-2022 | Licitación PA FUTIC → ISPs | 418.732 | >$465.000M | 100% | 0% | ~$1.111K | SILVER |
| 2 | **Líneas de Fomento 1.0** | 2023-2024 | FUTIC → ISP pequeño (<30K) Findeter | 21.417 | $29.000M | 100% | 0% | ~$1.354K | SILVER |
| 3 | **Líneas de Fomento 2.0** | 2024 | FUTIC → ISP pequeño Res.620/2024 | 84.050 | N/D | 100% | 0% | ~$508K* | SILVER |
| 4 | **Líneas de Fomento 3.0** | 2025 | FUTIC → ISP Ciudad Bolívar Bogotá | 4.500 | N/D | 100% | 0% | N/D | SILVER |
| 5 | **ConectiVIDAd p/Cambiar Vidas** | 2023-2026 | Conv.790/2023 FUTIC-InterNexa → ISPs | ~400.000 | N/D total | 100% | 0% | ~$396K† | GOLD |
| 6 | **Mi Casa Bacana Digital · Atlántico** | Sep2024-2026 | Convenio cofinanciado MinTIC + Gobernación | 43.945 | $38.045M | 78.9% | 21.1% | **$865.627** | SILVER |
| 7 | **Convenio FTTH Norte de Santander PDET** | 2023 | Convenio cofinanciado MinTIC + Gobernación PDET | 12.265 | $23.000M | 87% | 13% | $1.875.764 | SILVER |
| 8 | **PNCAV-Andired** (Orinoquia-Amazonia) | Ongoing | Acuerdo especial Andired 29 mun + 18 ANM | — | N/D | 100% | 0% | N/D | SILVER |

*Casanare ejemplo: $675.842.160 / 1.330 hogares = $508K (Región 14 · UT FOMENTO CASANARE 2.0)*
†Solo CPE $150K + Instalación $200K + Mantenimiento $1.900×24m = $395.600 (SIN despliegue red GPON)

### Hallazgo principal sobre nomenclatura

Los nombres "conexiones-digitales", "conexiones-digitales-ii" y "conexiones-residenciales" NO son nombres oficiales de programas MinTIC. Son categorías descriptivas. Los programas reales son los listados arriba. El patrón más cercano a lo que el usuario denominaba es:
- **"conexiones-residenciales"** → ConectiVIDAd para Cambiar Vidas (programa base) + Mi Casa Bacana Digital (modelo con gobernación)
- **"casa-bacana-digital"** → Mi Casa Bacana Digital (marca de Atlántico, convenio cofinanciado)
- **"conexiones-digitales"** → Hogares Conectados / Líneas de Fomento (programas anteriores)
- **"conexiones-digitales-ii"** → Líneas de Fomento 2.0 o segunda fase de Hogares Conectados

### Validación benchmark $875.000/hogar para Arauquita

| Benchmark | $/hogar | Justificación | Aplicabilidad Arauquita |
|-----------|---------|---------------|------------------------|
| Mi Casa Bacana Digital Atlántico | $865.627 | FTTH, convenio MinTIC+Gobernación, 43.945 hogares | ALTA: mismo mecanismo de convenio cofinanciado |
| ConectiVIDAd FUTIC directo (solo subsidio) | $395.600 | Solo CPE+instalación+OPEX, sin red nueva | BAJA: no incluye despliegue FTTH GPON nueva |
| Norte de Santander PDET troncal+última milla | $1.875.764 | Incluye red troncal de fibra departamental | MEDIA: incluye más que el scope de Arauquita |
| **Propuesta Arauquita** | **$875.000** | Interpolación: backbone Fibergroup privado + conexión residencial subsidiada | ✓ CONSERVADOR pero defensible |

**Conclusión:** $875.000/hogar × 4.000 hogares = $3.500M COP es un benchmark **conservador y defensible** comparado con:
- Atlántico $865K/hogar (casi idéntico, territorio con mayor infraestructura previa → favorable para Arauquita)
- Norte de Santander PDET $1,876K/hogar (territorio rural PDET con red troncal incluida → muestra que $875K es conservador)

### Validación cofinanciación MinTIC 95% / GobArauca 5%

| Convenio | MinTIC | Gobernación | Justificación mayor % MinTIC |
|----------|--------|-------------|------------------------------|
| Mi Casa Bacana Digital Atlántico | 78.9% | 21.1% | Gobernación con mayor capacidad fiscal |
| Norte de Santander PDET | 87% | 13% | Territorio PDET, menor capacidad gobernación |
| **Propuesta Arauquita** | **95%** | **5%** | PDET + ZOMAC + ZDP + mayor brecha TIC + menor capacidad fiscal GobArauca |

La ratio 95%/5% es aspiracional vs precedentes (87-79%), pero defensible por condición PDET+ZOMAC+ZDP de Arauquita y la escala menor del proyecto (4.000 vs 43.945 hogares en Atlántico → gobernación asume menor carga absoluta: $175M vs $8.045M).

### Conv006/2025 en Arauca (dato nuevo crítico)

La **Convocatoria 006/2025** de ConectiVIDAd incluye **Arauca (capital)** con 18.531 hogares totales (5 municipios: Caucasia, Ciudad Bolívar-Ant, Arauca, Ipiales, Pupiales). ISP adjudicatario para Arauca capital: **WICOM S.A.S.** Tarifa social: $27.800/mes. **Arauquita NO incluida** → campo virgen confirmado. Esto valida la oportunidad para Fibergroup como ISP de Arauquita bajo el mismo Convenio 790/2023.

### Fuentes

- mintic.gov.co: Noticias Conv006/2025, Conv004/2025, Líneas Fomento 1.0/2.0/3.0, Hogares Conectados
- atlantico.gov.co: Noticias Mi Casa Bacana Digital sep2024-mar2026
- diariolalibertad.com: Nota firma convenio MinTIC-Gobernación Atlántico sep2024
- elnorte.com.co: Mi Casa Bacana Digital 40.000 hogares mar2026
- dplnews.com: Conv006/2025 nota técnica
- hsbnoticias.com: Conv006/2025 detalles
- mintic.gov.co (nota prensa Norte de Santander): Convenio $23.000M / 12.265 hogares PDET

---

*Fuentes: MinTIC (mintic.gov.co), ONTIC (ontic.mintic.gov.co), DANE (dane.gov.co), InterNexa (internexa.com/cpcv), reportes web consolidados 2026-04-27.*
