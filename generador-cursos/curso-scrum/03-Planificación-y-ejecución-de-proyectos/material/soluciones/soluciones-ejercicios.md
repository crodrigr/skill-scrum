# 🔑 Soluciones — Ejercicios de la Clase 03 (material docente)

No compartir este archivo con los estudiantes.

Los ejercicios son conceptuales: no hay comandos que ejecutar. Los ejercicios **cerrados** tienen una
sola respuesta defendible; los **abiertos** se evalúan con los criterios indicados y admiten
redacciones equivalentes. Los datos del proyecto de canchas de pádel son los de `fidelidad.md`.

---

## 🟢 Básico 01 — Las cuatro etapas del flujo de un sprint

### ✅ Respuesta o criterio

**Orden:** d → b → c → a.

| Etapa | Qué se obtiene |
|---|---|
| d. Objetivo del producto y épicas | 2. Épicas |
| b. Dividir las épicas en historias | 3. Historias ordenadas, con criterio de aceptación |
| c. Planificar el sprint y formar el Sprint Backlog | 4. La lista del sprint |
| a. Ejecución con el tablero | 1. Un incremento utilizable |

**Dos cosas que no cambian durante un sprint** (cualquiera de estas): la duración del sprint; el objetivo
del sprint.

### 🔍 Justificación

Las etapas siguen el flujo: primero se define qué se quiere (épicas), luego se detalla (historias), se
planifica y por último se ejecuta.

### 🔎 Verificación

Cuatro parejas sin repetir, orden correcto y dos elementos fijos válidos.

---

## 🟢 Básico 02 — Épica, historia o tarea

### ✅ Respuesta o criterio

| Elemento | Clasificación |
|---|---|
| 1. Gestionar mis recetas favoritas | **Épica** |
| 2. Buscar recetas por ingrediente (formato «como, quiero, para») | **Historia de usuario** |
| 3. Diseñar la pantalla de resultados | **Tarea** |
| 4. Planificar el menú de la semana | **Épica** |
| 5. Guardar una receta como favorita (formato «como, quiero, para») | **Historia de usuario** |
| 6. Probar el guardado sin conexión | **Tarea** |
| 7. Ver la lista de compras de una receta (formato «como, quiero, para») | **Historia de usuario** |
| 8. Compartir recetas con otras personas | **Épica** |

**Justificaciones:** el 2 es historia porque describe un valor para quien usa el producto con el
formato «como, quiero, para»; el 3 es tarea porque es un paso del equipo, no un valor para el usuario; el
4 es épica porque es un bloque grande que se dividiría en varias historias.

**Objetivo del producto** (ejemplo): «Que cualquier persona pueda decidir qué cocinar y encontrar la
receta en menos de un minuto». Criterios: expresa el valor, se puede comprobar y no es una lista de
funciones.

### 🔍 Justificación

Se distingue por tamaño y punto de vista: la épica es grande, la historia describe valor para el
usuario y la tarea es un paso del equipo.

### 🔎 Verificación

Ocho clasificaciones correctas, tres justificaciones de una frase y un objetivo comprobable.

---

## 🟡 Intermedio 01 — Redactar historias y dividir una historia grande

### ✅ Respuesta o criterio

**Ejemplo de respuesta** (valen otras historias coherentes con la épica):

| Prioridad | Historia | Criterio de aceptación |
|---|---|---|
| 1 | Como cliente quiero ver el catálogo de plantas para elegir cuáles comprar | Dado que entro a la tienda, cuando abro el catálogo, entonces veo las plantas con su precio |
| 2 | Como cliente quiero agregar una planta al carrito para juntar lo que voy a comprar | Dado que veo una planta, cuando la agrego, entonces aparece en mi carrito con su precio |
| 3 | Como cliente quiero pagar mi pedido para recibir las plantas | Dado que tengo plantas en el carrito, cuando confirmo el pago, entonces el pedido queda registrado y recibo un comprobante |

**Orden:** primero ver el catálogo, luego el carrito y por último el pago, por dependencias (no se
puede pagar sin haber elegido).

**«Gestionar mis pedidos»**: es demasiado grande, mezcla varias cosas y no cabe en un sprint (una
épica disfrazada). División posible: ver mis pedidos · cancelar un pedido · repetir un pedido anterior.

### 🔍 Justificación

Cada historia describe un valor para el cliente, es pequeña y tiene un criterio verificable.

### 🔎 Verificación

Tres historias con quién, qué y por qué; criterios con «dado, cuando, entonces» concretos; un orden
justificado; y una división en al menos tres historias pequeñas.

---

## 🟡 Intermedio 02 — Planificar un sprint y actualizar el tablero

### ✅ Respuesta o criterio

**Parte A**

- **Objetivo del sprint** (ejemplo): «Que un cliente pueda elegir plantas y comprarlas».
- **Selección:** **P1, P2 y P4**.
- **Queda fuera P3** (buscar plantas por tipo): entraría por capacidad (es la tercera en el orden), pero
  **no contribuye al objetivo**; se elige por objetivo y no solo por lugar.
- **Tareas de P2** (ejemplo): diseñar el carrito · construir «agregar al carrito» · probar con el
  criterio y revisar.

**Parte B — tablero**

| Día | Por hacer | En curso | Hecho |
|---|---|---|---|
| 3 | e, g, h | b, c, d, f | a |
| 6 | h | e, f, g | a, b, c, d |
| 10 | — | h | a, b, c, d, e, f, g |

**Decisión de cierre (día 10)**

| Historia | ¿Terminada? | Qué pasa |
|---|---|---|
| P1 | Sí | Entra en el incremento |
| P2 | Sí | Entra en el incremento |
| P4 | **No** (falta h: probar el pago) | Vuelve al Product Backlog; el sprint no se alarga |

### 🔍 Justificación

Una historia está terminada cuando todas sus tareas están hechas y cumple la definición de terminado.
Al P4 le falta la prueba con su criterio, así que no se cuenta como terminada.

### 🔎 Verificación

Selección P1, P2 y P4; explicación de P3; tableros fieles al registro; decisión de cierre correcta; sin
puntos de estimación.

---

## 🔴 Desafío 01 — Del Product Backlog al sprint ejecutado

### ✅ Respuesta o criterio

**Partes abiertas (criterios; ejemplo de respuesta):**

- **Objetivo del producto:** «Que cualquier estudiante pueda encontrar un libro y pedirlo prestado sin
  hacer fila».
- **Épicas:** «Buscar libros» (encontrar y ver disponibilidad) y «Préstamos y devoluciones» (pedir
  prestado, devolver, avisos y reservas). La administración de carnés puede quedar como épica aparte o
  dentro de la segunda.
- **Tres historias de «Buscar libros»** (ejemplo): «Como estudiante quiero buscar un libro por título para
  saber si la biblioteca lo tiene» (Dado que escribo un título, cuando busco, entonces veo los libros que
  coinciden) · «Como estudiante quiero ver si un libro está disponible para saber si puedo pedirlo»
  (Dado que veo un libro, cuando consulto su estado, entonces veo si está disponible o prestado) · «Como
  estudiante quiero ver los datos de un libro para elegir el que necesito» (Dado que elijo un libro,
  cuando abro su ficha, entonces veo título, autor y ubicación).

**Partes cerradas:**

| Elemento | Respuesta |
|---|---|
| Objetivo del sprint (ejemplo) | Que un estudiante pueda encontrar un libro y pedirlo prestado |
| Selección | **B1, B2 y B4** |
| Queda fuera | **B3** (aviso de vencimiento): es de alta prioridad, pero no contribuye al objetivo |
| Día 6: pedido de la bibliotecaria | El objetivo del sprint no cambia; el aviso queda en el Product Backlog y la *Product Owner* decide su lugar |
| B1 y B2 | **Terminadas** |
| B4 | **No terminada** (falta i): vuelve al Product Backlog; el sprint no se alarga |
| Historia frente a tarea | La historia describe un valor para quien usa el producto; la tarea es un paso del equipo |

**Tableros**

| Día | Por hacer | En curso | Hecho |
|---|---|---|---|
| 7 | i | e, h | a, b, c, d, f, g |
| 10 | — | i | a, b, c, d, e, f, g, h |

### 🔍 Justificación

El objetivo del sprint guía la selección: B3 se deja fuera aunque sea prioritaria. La decisión de cierre
sigue la definición de terminado: B4 tiene una tarea sin hacer y no comprobó su criterio.

### 🔎 Verificación

Se cumplen los casos de prueba del Desafío: selección B1, B2 y B4; tableros de los días 7 y 10; pedido del
día 6 sin cambiar el objetivo; B1 y B2 terminadas y B4 devuelta al Product Backlog; historia frente a
tarea; y ausencia de puntos de estimación.
