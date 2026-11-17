# 📘 Ejemplo 05 — Ejecutar el sprint con el tablero

## 🧱 Situación inicial

El sprint 1 de la **aplicación para reservar canchas de pádel** ya empezó. Su Sprint Backlog es el
del Ejemplo 04: objetivo del sprint «que un jugador pueda ver las canchas libres y reservar un
turno», con las historias H1, H2 y H3 y sus diez tareas. El equipo usa un tablero de tarjetas con
tres columnas: **por hacer**, **en curso** y **hecho**.

La **definición de terminado** del equipo: una historia está terminada cuando se probó con su
criterio de aceptación, la revisó otra persona y funciona en el entorno de pruebas.

## 🔍 Análisis paso a paso

1. **Día 1.** Las diez tareas están en «por hacer». Cada *Developer* toma una y la pasa a «en
   curso».
2. **Día 4: aparece un problema de flujo.** El tablero muestra **cinco tareas en curso** (H1
   construir, H2 diseñar, H2 construir, H2 guardar y H3 construir) y solo una en «hecho». En la
   reunión diaria el equipo ve que **empezó mucho y cerró poco**. Decide **terminar antes de
   empezar**: cerrar las tareas abiertas antes de tomar otras.
3. **Día 6: llega un cambio.** La dueña del negocio pide agregar el **pago de la seña**. Lucía, la
   *Product Owner*, responde que el **objetivo del sprint no cambia**: el pedido se ubica en el
   Product Backlog, en la épica E2, para un sprint futuro. Mateo no impone nada: conversan y
   Lucía decide.
4. **Día 7.** Seis tareas hechas, dos en curso y dos por hacer (ver la imagen). El equipo va a
   buen ritmo hacia el objetivo del sprint.
5. **Día 10: cierre del sprint.** Todas las tareas de H1 y H2 están hechas, y de H3 solo la
   construcción del mensaje; **falta probar el criterio de H3**.
6. **Aplicar la definición de terminado.**
   - **H1**: tareas hechas, criterio comprobado, revisada y funcionando en pruebas → **terminada**.
   - **H2**: tareas hechas, criterio comprobado, revisada y funcionando en pruebas → **terminada**.
   - **H3**: queda una tarea sin hacer y el criterio no se comprobó → **no terminada**.
7. **Decidir qué hacer con H3.** No se cuenta como terminada y **no se alarga el sprint**: **vuelve
   al Product Backlog** y Lucía decide su lugar (probablemente, arriba).
8. **El incremento.** Con H1 y H2 terminadas, hay un incremento utilizable: un jugador puede ver
   las canchas libres y reservar un turno. El objetivo del sprint se cumplió en lo esencial.
9. **Cierre.** En la revisión se muestra el incremento; en la retrospectiva el equipo acuerda
   trabajar con menos tareas en curso a la vez.

## ✅ Resultado esperado

**Tablero a lo largo del sprint**

| Día | Por hacer | En curso | Hecho |
|---|---|---|---|
| 1 | 8 | 2 | 0 |
| 4 | 4 | 5 | 1 |
| 7 | 2 | 2 | 6 |
| 10 | 0 | 1 | 9 |

**Decisión de cierre**

| Historia | ¿Terminada? | Qué pasa |
|---|---|---|
| H1 | Sí | Entra en el incremento |
| H2 | Sí | Entra en el incremento |
| H3 | No | Vuelve al Product Backlog; el sprint no se alarga |

![Tablero del sprint 1 en el día 7, con las columnas por hacer, en curso y hecho, y las tareas de las historias H1, H2 y H3.](../imagenes/tablero-sprint.svg)

> 📌 La definición de terminado, el incremento y la regla de que el objetivo del sprint no cambia
> son de la Guía de Scrum; el tablero es una práctica habitual.
