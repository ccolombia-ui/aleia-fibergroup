---
título: Datos literales para diligenciar Factura Electrónica · Hito 1
contrato: CCMS-CB-2026-001-B-v11
hito: 1 · Starting · E0 · Firma del contrato y kick-off (20%)
monto: 5.400.000 COP
fecha: 2026-04-28
sistema: Siigo Nube · prefijo DAFE
---

# Hoja de captura · Factura Electrónica · Hito 1 (Starting · E0)

> Valores literales para copiar/pegar en cada campo de Siigo. Mismo patrón que DAFE 61 (CPS-939, feb 2026).

## 1 · Adquirente (cliente)

| Campo Siigo | Valor a diligenciar |
|---|---|
| Razón social | `FIBERGROUP S.A.S. E.S.P.` |
| Tipo de identificación | `NIT` |
| Número de identificación | `901322864` |
| Dígito de verificación | `7` |
| Tipo de persona | `Persona Jurídica` |
| Régimen | `Responsable de IVA` |
| Dirección | `Calle 46 # 39-56 Cabecera del Llano` |
| Ciudad | `Bucaramanga` |
| Departamento | `Santander` |
| País | `Colombia` |
| Correo electrónico (envío DIAN) | `facturaelectronica@fibergroup.net` |
| Teléfono | `6076916069` |
| Representante legal | `Ciro Manuel González Hernández` |
| C.C. representante | `91.511.053` |

## 2 · Datos de la factura

| Campo Siigo | Valor a diligenciar |
|---|---|
| Tipo documento | `Factura electrónica de venta` |
| Prefijo | `DAFE` |
| Número | `(consecutivo siguiente disponible en Siigo)` |
| Fecha de generación | `2026-04-28` |
| Fecha de expedición | `2026-04-28` |
| Fecha de vencimiento | `2026-04-28` |
| Forma de pago | `Contado` |
| Medio de pago | `Transferencia` |
| Moneda | `COP` |

## 3 · Ítem (1 línea, idéntico patrón a DAFE 61)

| Campo Siigo | Valor a diligenciar |
|---|---|
| Producto/servicio | `procesamiento de datos,alojamientos (hosting) y actividades relacionadas` |
| Descripción | `procesamiento de datos,alojamientos (hosting) y actividades relacionadas` |
| Cantidad | `1.00` |
| Valor unitario | `5400000` |
| Descuento | `0` |
| IVA | `No aplica` |
| Valor total ítem | `5,400,000.00` |

## 4 · Observaciones

> Texto literal a pegar en el campo "Observaciones":

```
Hito 1 · Starting · E0 (20%) · 28 abril 2026 · Contrato CCMS-CB-2026-001-B-v11 · Formulación MGA Territorios Digitales Transformativos · Arauca
```

## 5 · Totales

| Campo | Valor |
|---|---|
| Total items | `1` |
| Total bruto | `5,400,000.00` |
| Total a pagar | `5,400,000.00` |
| Valor en letras | `Cinco millones cuatrocientos mil pesos m/cte` |

## 6 · Datos del emisor (ya configurados en Siigo, solo verificar)

| Campo               | Valor                                                                                |
| ------------------- | ------------------------------------------------------------------------------------ |
| Razón social        | `Carlos Camilo Madera Sepulveda`                                                     |
| NIT                 | `79.801.495-7`                                                                       |
| Dirección           | `avenida la toma 11 53`                                                              |
| Ciudad              | `Neiva - Colombia`                                                                   |
| Teléfono            | `(57) 3004724009`                                                                    |
| Correo              | `carlosmadera@soygenial.co`                                                          |
| Actividad económica | `7490 Otras actividades profesionales, científicas y técnicas n.c.p.`                |
| Tarifa ICA          | `9 * 1000`                                                                           |
| Resolución DIAN     | `18764083130105` aprobado `20241108` prefijo `DAFE` rango `1-100` vigencia `6 Meses` |

## 7 · Datos bancarios (informar a Fibergroup para el desembolso)

| Campo | Valor |
|---|---|
| Banco | `Nu Colombia Compañía de Financiamiento S.A.` |
| NIT banco | `901.658.107-2` |
| Tipo de cuenta | `Cuenta de ahorros` |
| Número de cuenta | `72991701` |
| Titular | `Carlos Camilo Madera Sepulveda` |
| C.C. titular | `79.801.495` |

## 8 · Soportes a adjuntar al envío de la factura

Ubicación: `4--ejecucion/facturacion/_shared/`

- `11--cedula.pdf`
- `12--RUT.pdf`
- `13--Cert-Bancaria.pdf` (Nu Colombia · cuenta 72991701)

Más:

- Factura electrónica DAFE-### (PDF + XML firmados DIAN) — generada en Siigo
- Contrato `3--contrato/CONTRATO-tpl--formulacion-MGA-arauca.pdf` (CCMS-CB-2026-001-B-v11)

## 9 · Envío

| Campo | Valor |
|---|---|
| Para | `Gerencia@fibergroup.net` |
| Asunto | `Factura Hito 1 (20%) · Contrato CCMS-CB-2026-001-B-v11 · Formulación MGA Arauca` |
| Cuerpo | `Adjunto factura electrónica DAFE-### por valor de $5.400.000 COP correspondiente al Hito 1 (Starting · E0 — Firma y kick-off, 20%) del contrato CCMS-CB-2026-001-B-v11. Datos bancarios para transferencia: Nu Colombia, cuenta de ahorros 72991701, titular Carlos Camilo Madera Sepúlveda CC 79.801.495.` |
