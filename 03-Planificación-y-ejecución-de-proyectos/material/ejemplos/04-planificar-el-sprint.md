# 📘 Ejemplo 04 — Planificar el sprint

## 🧱 Situación inicial

El equipo de la **aplicación para reservar canchas de pádel** va a planificar el **sprint 1**, de
dos semanas. El Product Backlog, ordenado, empieza así:

| Orden | Elemento |
|---|---|
| 1 | H1 — Ver las canchas libres de un día |
| 2 | H2 — Reservar un turno |
| 3 | H3 — Recibir una confirmación de la reserva |
| 4 | H4 — Filtrar canchas por tipo |
| 5 | Pagar la seña (épica E2) |

La **capacidad** del equipo es de **cuatro historias pequeñas** por sprint de dos semanas.

## 🔍 Análisis paso a paso

1. **Formular el objetivo del sprint.** Lo primero es el *por qué*: que un jugador pueda **ver las
   canchas libres y reservar un turno**. Es lo mínimo que da valor real.
2. **Mirar la capacidad.** El equipo puede completar hasta cuatro historias pequeñas.
3. **Seleccionar según el objetivo.** H1 permite ver las canchas, H2 permite reservar y H3 da la
   confirmación de la reserva: las tres contribuyen al objetivo y son las de mayor prioridad.
4. **Decidir sobre H4.** Entraría por capacidad (sería la cuarta), pero **filtrar por tipo no
   contribuye al objetivo**: mejora la búsqueda, no es necesario para reservar. Queda **fuera**,
   en el Product Backlog. Se elige por objetivo, no solo por lugar disponible.
5. **Descomponer en tareas.** Cada historia se parte en pasos concretos y breves (ver la tabla).
6. **Formar el Sprint Backlog**, con sus tres partes: el objetivo del sprint, las historias
   elegidas y el plan de tareas.
7. **Confirmar que cabe.** Son tres historias, por debajo de la capacidad de cuatro: hay margen
   para imprevistos.

## ✅ Resultado esperado

**Sprint Backlog del sprint 1**

| Parte | Contenido |
|---|---|
| **Objetivo del sprint** | Que un jugador pueda ver las canchas libres y reservar un turno |
| **Historias elegidas** | H1, H2 y H3 |
| **Fuera del sprint** | H4 (queda en el Product Backlog: no contribuye al objetivo) |

**Plan de tareas**

| Historia | Tareas |
|---|---|
| H1 | Diseñar la pantalla de canchas · construir la consulta de canchas libres · probar con el criterio y revisar |
| H2 | Diseñar la pantalla de reserva · construir la función de reservar · guardar la reserva · probar los casos del criterio · revisar con otra persona |
| H3 | Construir el mensaje de confirmación · probar el criterio |

> 📌 El Sprint Backlog es un concepto de la Guía de Scrum; las historias y las tareas son
> prácticas habituales con las que se completa.
