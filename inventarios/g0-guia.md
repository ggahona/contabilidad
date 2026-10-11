---
title: Guía de la clase — El Inventario en el Ciclo Contable
curso: Inventarios NIF C-4
caso: Bicicletas del Norte, S.A. de C.V.
duración: 2 horas
puntos: 5
tags: [contabilidad, inventarios, NIF-C-4, guía, introducción]

---
## El Inventario en el Ciclo Contable
**Clase de Inventarios bajo NIF C-4**
**Caso: Bicicletas del Norte, S.A. de C.V.**
**Duración estimada:** 2 horas
**Puntos temáticos:** 5

### Bienvenida
En esta clase recorreremos el **ciclo contable completo de los inventarios** bajo la norma **NIF C-4**, aplicado a un caso real: la empresa **Bicicletas del Norte, S.A. de C.V.**
Comenzaremos por entender **qué son los inventarios** y cómo se clasifican, luego veremos **cómo se registran** las operaciones, después **cómo se les asigna un costo**, cómo se manejan las **mercancías en tránsito** y los **ajustes por recuento físico**, y finalmente cómo se presentan en los **estados financieros**.
Esta guía es el documento de referencia de la clase. Los recursos interactivos están en los archivos HTML del proyecto.

### El caso: Bicicletas del Norte, S.A. de C.V.

| Concepto               | Descripción                                                             |
| :--------------------- | :---------------------------------------------------------------------- |
| **Giro**               | Ensamble y comercialización de bicicletas de montaña, urbanas y de ruta |
| **Producto principal** | Bicicletas *Modelo Alpinista*                                           |
| **Periodo**            | Ejercicio 2026                                                          |
| **Moneda**             | Pesos mexicanos ($)                                                     |
#### Inventario inicial al 1 de enero de 2026

| Categoría NIF C-4         | Descripción                           | Unidades | Costo unit. |         Importe |
| :------------------------ | :------------------------------------ | :------: | :---------: | --------------: |
| Artículos terminados      | Bicicletas Alpinista                  |  100 u.  |  $1,000.00  |     $100,000.00 |
| Materias primas           | Cuadros, rines y pedales              |    —     |      —      |      $60,000.00 |
| Producción en proceso     | 40 cuadros en taller                  |    —     |      —      |      $40,000.00 |
| Mercancías en tránsito    | Lote de 50 bicicletas desde Monterrey |  50 u.   |  $1,000.00  |      $50,000.00 |
| Artículos en consignación | 10 bicicletas a prueba                |  10 u.   |  $1,000.00  |      $10,000.00 |
| Refacciones y suministros | Lubricantes y llantas de taller       |    —     |      —      |      $15,000.00 |
| **TOTAL**                 |                                       |          |             | **$275,000.00** |
#### Otros activos y pasivos de arranque

$$
\text{Bancos} + \text{Mobiliario} + \text{Inventarios} = \text{Activo Total}
$$
$$
\$225{,}000 + \$50{,}000 + \$275{,}000 = \$550{,}000
$$
$$
\text{Activo} = \text{Pasivo} + \text{Capital} \quad \Rightarrow \quad \$550{,}000 = \$50{,}000 + \$500{,}000
$$

### ¿Qué es el inventario?
Según la **NIF C-4**, los inventarios son:
> **Activos no monetarios** sobre los cuales la entidad tiene los **riesgos y beneficios**, adquiridos para su **venta** en el curso normal de las operaciones o para ser **consumidos en el proceso de producción** de bienes que posteriormente serán vendidos.
### Características esenciales
- **Activos circulantes:** se espera disponer de ellos en el ciclo normal de operaciones (menor a un año).
- **Naturaleza deudora:** todas las cuentas de inventario aumentan con cargos y disminuyen con abonos.
- **Control por auxiliares:** cuenta colectiva en el mayor + tarjetas auxiliares o kardex.
- **Punto de contacto:** el inventario final es una de las dos cifras que conectan el Estado de Resultados y el Balance General.

### Recorrido de la clase
#### Punto 1 — Definición, Naturaleza y Clasificación (NIF C-4)
Qué son los inventarios, por qué van en el Activo Circulante y cuáles son las 6 clases normativas.
**Archivos:**
- `g1-presentacion.html`
- `g1-complemento.html`

### Punto 2 — Procedimientos de Registro Contable
Global, Analítico y Perpetuos: tres formas de registrar compras y ventas, todas llegan al mismo resultado final.
**Archivos:**
- `g2-presentacion.html`
- `g2-complemento-simulador.html`

### Punto 3 — Fórmulas de Asignación del Costo
PEPS y Costo Promedio Móvil: cómo asignar costo cuando los precios cambian a lo largo del tiempo.
**Archivos:**
- `g3-presentacion.html`
- `g3-calculadora-kardex.html`

### Punto 4 — Mercancías en Tránsito y Ajustes por Inventario Físico
Cuenta puente para compras foráneas y regularización de mermas, faltantes y sobrantes.
**Archivos:**
- `g4-presentacion.html`
- `g4-simulador-transito-ajustes.html`

### Punto 5 — Relación con el Estado de Resultados
Los dos puntos de contacto entre el Estado de Resultados y el Balance General, y la comprobación del circuito contable.
**Archivos:**
- `g5-presentacion.html`
- `g5-conciliador-er-bg.html`

### El ciclo contable del inventario

| Etapa | Punto | Acción |
|:--|:-:|:--|
| Clasificar | 1 | Definir qué es el inventario y sus 6 clases normativas |
| Registrar | 2 | Aplicar Global, Analítico o Perpetuos |
| Costear | 3 | Asignar costo con PEPS o Costo Promedio Móvil |
| Ajustar | 4 | Manejar tránsito y regularizar el recuento físico |
| Presentar | 5 | Elaborar ER y BG, verificar los dos puntos de contacto |

$$
\text{Ciclo completo} = \text{Clasificar} \to \text{Registrar} \to \text{Costear} \to \text{Ajustar} \to \text{Presentar}
$$

### Cómo trabajaremos
#### Estructura de cada punto
Cada punto temático se compone de **dos archivos HTML**:
1. **Presentación:** conceptos, ejemplos del caso, tablas contables. Sin ejercicios.
2. **Herramienta aplicativa:** calculadora, simulador, conciliador o actividad interactiva, con botones "Cargar caso", "¿Cómo funciona?" y "Limpiar".
#### Recomendación de uso
- Lee primero la presentación del punto.
- Abre después la herramienta aplicativa para reforzar con actividades interactivas.
- Usa el botón "Cargar caso" para restaurar los datos originales.
- Verifica los dos puntos de contacto entre ER y BG al terminar el Punto 5.

### Objetivo de aprendizaje
Al concluir la clase podrás:
- **Definir** los inventarios según la NIF C-4 y clasificarlos en sus 6 clases normativas.
- **Registrar** compras y ventas con los tres procedimientos contables (Global, Analítico y Perpetuos).
- **Asignar** costo a las salidas y al inventario final con PEPS y Costo Promedio Móvil.
- **Manejar** mercancías en tránsito y aplicar ajustes por recuento físico.
- **Elaborar** el Estado de Resultados y el Balance General, verificando los dos puntos de contacto.

### Datos clave del caso (referencia rápida)
#### Operaciones del periodo

| Operación            | Unidades | Costo / Precio |     Importe |
| :------------------- | :------: | :------------: | ----------: |
| Saldo inicial 01/Ene |  100 u.  |   $1,000.00    | $100,000.00 |
| Compra 10/Ene        |  50 u.   |   $1,300.00    |  $65,000.00 |
| Venta 15/Ene         |  80 u.   |   $2,000.00    | $160,000.00 |
| Compra 20/Ene        |  30 u.   |   $1,500.00    |  $45,000.00 |
| Venta 28/Ene         |  40 u.   |   $2,200.00    |  $88,000.00 |
### Resultados PEPS

- Costo de ventas: **$126,000.00**
- Utilidad bruta: **$122,000.00**
- Inventario final: **$84,000.00**
### Resultados Costo Promedio Móvil
- Costo de ventas: **$136,800.00**
- Utilidad bruta: **$111,200.00**
- Inventario final: **$73,200.00**
### Diferencia entre métodos
$$
\Delta = \$136{,}800 - \$126{,}000 = \$10{,}800
$$
### Ajustes por recuento físico

| Tipo de ajuste           |        Importe | Cuenta de contrapartida  |
| :----------------------- | -------------: | :----------------------- |
| Merma normal             |      $1,400.00 | Gastos de venta          |
| Faltante injustificado   |      $1,400.00 | Deudores diversos        |
| Sobrante desconocido     |        $500.00 | Otros gastos y productos |
| **Saldo final ajustado** | **$81,700.00** | —                        |
### Estado de Resultados (resumen)

| Concepto                        |         Importe |
| :------------------------------ | --------------: |
| Ventas                          |     $248,000.00 |
| Costo de lo vendido             |     $126,000.00 |
| **Utilidad bruta**              | **$122,000.00** |
| Gastos de operación             |      $50,400.00 |
| **Utilidad de operación**       |  **$71,600.00** |
| Otros productos                 |         $500.00 |
| **Utilidad antes de ISR y PTU** |  **$72,100.00** |
| ISR (35%)                       |      $25,235.00 |
| PTU (10%)                       |       $7,210.00 |
| **Utilidad neta del ejercicio** |  **$39,655.00** |
### Balance General (resumen)

| Concepto                      |                       Importe |
| :---------------------------- | ----------------------------: |
| Total Activo                  |                   $622,100.00 |
| Total Pasivo                  |                    $82,445.00 |
| Total Capital                 |                   $539,655.00 |
| **Activo = Pasivo + Capital** | **$622,100.00 = $622,100.00** |

## Los dos puntos de contacto
Los únicos **dos puntos de contacto directo** entre el Estado de Resultados y el Balance General son:
1. **El inventario final de mercancías** — se deduce en el ER para calcular el costo de lo vendido, y aparece como activo circulante en el BG.
2. **La utilidad neta del ejercicio** — es la última línea del ER y se integra al Capital Contable del BG.
$$
\text{Inventario final (ER)} = \text{Inventario final (BG)}
$$
$$
\text{Utilidad neta (ER)} = \text{Utilidad neta (BG)}
$$
Si estos dos puntos de contacto no coinciden, la contabilidad está descuadrada.

## Archivos de la clase

| Archivo                              | Descripción                                     |
| :----------------------------------- | :---------------------------------------------- |
| `g0-guia.md`                         | Este documento: guía e introducción de la clase |
| `g1-presentacion.html`               | Punto 1 — Presentación                          |
| `g1-complemento.html`                | Punto 1 — Complemento (clasificador)            |
| `g2-presentacion.html`               | Punto 2 — Presentación                          |
| `g2-complemento-simulador.html`      | Punto 2 — Complemento (simulador)               |
| `g3-presentacion.html`               | Punto 3 — Presentación                          |
| `g3-calculadora-kardex.html`         | Punto 3 — Calculadora de Kardex                 |
| `g4-presentacion.html`               | Punto 4 — Presentación                          |
| `g4-simulador-transito-ajustes.html` | Punto 4 — Simulador de tránsito y ajustes       |
| `g5-presentacion.html`               | Punto 5 — Presentación                          |
| `g5-conciliador-er-bg.html`          | Punto 5 — Conciliador ER ↔ BG                   |

**Total: 10 archivos HTML + 1 Markdown (esta guía).**
