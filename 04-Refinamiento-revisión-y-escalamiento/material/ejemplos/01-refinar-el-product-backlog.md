# 📘 Ejemplo 01 — Refinar el Product Backlog

## 🧱 Situación inicial

El sprint 1 de la **aplicación para reservar canchas de pádel** terminó: H1 y H2 quedaron terminadas y
H3 volvió al Product Backlog (Clase 03). Lucía, la *Product Owner*, y el equipo se juntan a refinar el
Product Backlog antes de planificar el sprint 2.

El Product Backlog tiene hoy estos elementos:

| Elemento | Estado |
|---|---|
| H3 — Recibir una confirmación de la reserva | Casi lista: volvió con una tarea pendiente |
| H4 — Filtrar canchas por tipo | Clara, sin talla |
| «Pagar la seña» | Grande y ambigua |
| «Administrar mis reservas» | Grande y ambigua |

## 🔍 Análisis paso a paso

1. **Reunir las entradas.** El equipo junta lo que alimenta el refinamiento:
   - el **Product Backlog ordenado** (la tabla de arriba);
   - el **objetivo del producto**: que cualquier jugador pueda reservar una cancha en menos de un minuto;
   - la **retroalimentación de la revisión del sprint 1** (se ve en el Ejemplo 03): los jugadores piden pagar la
     seña desde la aplicación, quieren ver canchas de otros clubes y el botón de reservar es confuso;
   - un **cambio del contexto**: el club abre dos canchas nuevas.
2. **Detectar qué no está listo.** «Pagar la seña» y «Administrar mis reservas» son grandes y ambiguas: no se
   pueden planificar tal cual.
3. **Usar las herramientas.**
   - **Dividir:** «Pagar la seña» y «Administrar mis reservas» se dividen (el detalle está en el Ejemplo 02).
   - **Aclarar:** cada historia nueva recibe su criterio de aceptación «dado, cuando, entonces».
   - **Estimar por tallas**, comparando con H2, que es mediana.
4. **Incorporar la retroalimentación.** Se agrega «Mejorar el botón de reservar» (chica) y «Ver canchas de otros
   clubes» queda como idea, sin refinar, al final.
5. **Ordenar.** El orden refleja el valor y las dependencias: primero lo que ya casi está (H3), luego lo que más
   pidieron los jugadores (el pago, que sube de lugar), con «Elegir el medio de pago» antes de «Pagar con
   tarjeta», porque la segunda depende de la primera.
6. **Comprobar que está listo para planificar.** Los elementos del tope son pequeños, claros, con criterio y con
   talla. Los de más abajo pueden seguir siendo vagos.
7. **Cuidar el tiempo.** El refinamiento es una actividad continua y no un evento: no se hizo «todo» de una vez.
   El equipo refinó solo lo que va a planificar pronto, para no refinar de más.

## ✅ Resultado esperado

**Product Backlog refinado, en orden**

| Orden | Elemento | Talla |
|---|---|---|
| 1 | H3 — Recibir una confirmación de la reserva | S |
| 2 | Mejorar el botón de reservar | S |
| 3 | Elegir el medio de pago | M |
| 4 | Pagar con tarjeta | M |
| 5 | Recibir el comprobante del pago | S |
| 6 | H4 — Filtrar canchas por tipo | S |
| 7 | Ver mis reservas | S |
| 8 | Cancelar una reserva | M |
| 9 | Cambiar el horario de una reserva | M |
| 10 | Ver canchas de otros clubes | Idea, sin refinar |

| | Qué se usó |
|---|---|
| **Entradas** | Product Backlog ordenado · objetivo del producto · retroalimentación de la revisión · cambio del contexto |
| **Herramientas** | Dividir · criterio de aceptación · tallas |
| **Salidas** | Elementos pequeños, claros, con criterio y talla, ordenados y listos para planificar |

![El refinamiento recibe como entradas el Product Backlog ordenado, el objetivo del producto, la retroalimentación de la revisión y los cambios del contexto; usa herramientas como dividir, criterio de aceptación y tallas; y produce elementos pequeños, claros y listos para planificar.](../imagenes/refinamiento-entradas-salidas.svg)

> 📌 El refinamiento es de la Guía de Scrum; el esquema de entradas, herramientas y salidas y las tallas son
> prácticas habituales.
