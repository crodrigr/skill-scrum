# 📘 Ejemplo 02 — Dividir y estimar una historia

## 🧱 Situación inicial

En el refinamiento del Ejemplo 01, el equipo de la **aplicación de canchas de pádel** tiene que dejar
listas dos historias grandes, y estimar todas por tallas. Usan esta **regla de tallas**:

| Talla | Regla |
|---|---|
| **Chica (S)** | Una pantalla, sin reglas especiales |
| **Mediana (M)** | Dos o tres pasos, o una regla |
| **Grande (L)** | Más de tres pasos o varias áreas: se divide antes de planificar |

La **referencia** es la historia **H2 — Reservar un turno**, que el equipo ya construyó y es **mediana**.

## 🔍 Análisis paso a paso

1. **Comparar las historias claras con la referencia.**
   - **H1 — Ver las canchas libres:** una pantalla de consulta, sin reglas especiales → **chica**.
   - **H3 — Recibir una confirmación:** un mensaje con datos de la reserva → **chica**.
   - **H4 — Filtrar canchas por tipo:** un filtro sobre una pantalla que ya existe → **chica**.
2. **Estimar «Pagar la seña».** Implica elegir el medio de pago, cargar los datos, confirmar con el medio de
   pago y emitir un comprobante: **más de tres pasos y varias áreas** → **grande**. No se puede planificar: **se
   divide**.
3. **Dividir «Pagar la seña»** en historias que sigan dando valor por sí solas, cada una con su criterio:
   - **Elegir el medio de pago** (mediana). *Dado que voy a pagar la seña, cuando veo las opciones, entonces puedo
     elegir un medio de pago.*
   - **Pagar con tarjeta** (mediana). *Dado que elegí pagar con tarjeta, cuando confirmo el pago, entonces la seña
     queda pagada.*
   - **Recibir el comprobante del pago** (chica). *Dado que pagué la seña, cuando el pago se confirma, entonces recibo
     un comprobante.*
4. **Estimar «Administrar mis reservas».** Mezcla ver, cancelar y cambiar reservas: **varias áreas** → **grande**.
   **Se divide**.
5. **Dividir «Administrar mis reservas»** (épica E3):
   - **Ver mis reservas** (chica). *Dado que tengo reservas, cuando abro mi lista, entonces las veo con día y hora.*
   - **Cancelar una reserva** (mediana). *Dado que tengo una reserva, cuando la cancelo, entonces la cancha queda libre.*
   - **Cambiar el horario de una reserva** (mediana). *Dado que tengo una reserva, cuando elijo otro horario libre,
     entonces la reserva pasa a ese horario.*
6. **Revisar el resultado.** Ninguna historia quedó grande y todas tienen criterio. Estimar fue comparar con H2, no
   medir en horas.
7. **Recordar el alcance.** Existen otras técnicas, como los puntos de historia, y herramientas de software; en esta
   clase solo se usan las tallas.

## ✅ Resultado esperado

| Historia | Talla | ¿Se divide? |
|---|---|---|
| H1 — Ver las canchas libres | S | No |
| H2 — Reservar un turno (referencia) | M | No |
| H3 — Recibir una confirmación | S | No |
| H4 — Filtrar canchas por tipo | S | No |
| «Pagar la seña» | L | **Sí** |
| «Administrar mis reservas» | L | **Sí** |

| Historia dividida | Nuevas historias |
|---|---|
| «Pagar la seña» | Elegir el medio de pago (M) · Pagar con tarjeta (M) · Recibir el comprobante del pago (S) |
| «Administrar mis reservas» | Ver mis reservas (S) · Cancelar una reserva (M) · Cambiar el horario de una reserva (M) |

![Estimación por tallas: las historias se comparan con una referencia y se ubican como chica, mediana o grande; las historias grandes se dividen antes de planificar el sprint.](../imagenes/tallas-estimacion.svg)
