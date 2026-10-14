# 📘 Ejemplo 04 — Flujo de un sprint

## 🧱 Situación inicial

Seguimos con la **aplicación para reservar canchas de pádel** del Ejemplo 03. Lucía, la
*Product Owner*, tiene esta lista del producto, ordenada de lo más valioso a lo menos valioso:

1. Ver qué canchas están libres.
2. Reservar un turno.
3. Pagar la seña.
4. Cancelar una reserva.
5. Recibir un recordatorio por mensaje.

El **objetivo del producto** es que cualquier jugador pueda reservar una cancha en menos de un
minuto. Los sprints del equipo duran **dos semanas**.

## 🔍 Análisis paso a paso

1. **Lista del producto.** Es el primer artefacto: una lista ordenada de lo que se necesita para
   mejorar el producto. Su compromiso es el **objetivo del producto**.
2. **Planificación del sprint 1.** El equipo se pregunta tres cosas: por qué es valioso este
   sprint (que un jugador pueda ver canchas libres y reservar un turno), qué se puede hacer
   (los elementos 1 y 2) y cómo se hará (el plan de trabajo).
3. **Lista del sprint.** Queda formada por el **objetivo del sprint** («Que un jugador pueda ver
   canchas libres y reservar un turno»), los elementos elegidos (1 y 2) y el plan para
   entregarlos. Su compromiso es el objetivo del sprint.
4. **Trabajo del sprint.** Durante dos semanas, los *Developers* construyen. Cada día se reúnen
   unos minutos para revisar cómo van hacia el objetivo del sprint y ajustar el plan.
5. **Incremento.** Al final del sprint, el equipo tiene una versión de la aplicación en la que un
   jugador puede ver canchas libres y reservar un turno. Para que cuente como terminado, cumple
   la **definición de terminado** que el equipo acordó (por ejemplo: probado, revisado por otra
   persona y funcionando en el entorno de pruebas).
6. **Revisión del sprint.** El equipo y algunos jugadores prueban el incremento. Con lo que
   aprenden, Lucía ajusta la lista del producto (por ejemplo, sube «Cancelar una reserva»).
7. **Retrospectiva.** El equipo revisa cómo trabajó y acuerda una mejora para el siguiente
   sprint.
8. **Siguiente sprint.** Empieza enseguida, con la lista del producto ya ajustada.

## ✅ Resultado esperado

```text
Lista del producto ──► Planificación ──► Sprint (2 semanas) ──► Incremento
        ▲                                   │ reunión diaria         │
        │                                                            ▼
        └──────── Retrospectiva ◄──────── Revisión del sprint ◄──────┘
```

| Artefacto | En el proyecto de canchas de pádel | Compromiso |
|---|---|---|
| Lista del producto | Los cinco elementos ordenados | Objetivo del producto: reservar en menos de un minuto |
| Lista del sprint | Objetivo del sprint 1 + elementos 1 y 2 + plan | Objetivo del sprint 1 |
| Incremento | La aplicación con ver canchas libres y reservar | Definición de terminado |

> 💡 Acá no se explica cómo se escriben, refinan ni estiman los elementos: eso es tema de un
> módulo posterior.
