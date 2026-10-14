# 🔑 Soluciones — Ejercicios de la Clase 04 (material docente)

No compartir este archivo con los estudiantes.

Los ejercicios son conceptuales: no hay comandos que ejecutar. Los **cerrados** tienen una sola respuesta
defendible; los **abiertos** se evalúan con los criterios indicados y admiten redacciones equivalentes. Los datos del
proyecto de canchas de pádel son los de `fidelidad.md`.

---

## 🟢 Básico 01 — Qué es (y qué no es) el refinamiento

### ✅ Respuesta o criterio

| Afirmación | Valoración | Corrección |
|---|---|---|
| a | **Falsa** | Es una actividad, no una reunión obligatoria de Scrum; la guía no fija su duración |
| b | **Verdadera** | — |
| c | **Falsa** | Estimar es una herramienta; también se divide, se aclara y se ordena |
| d | **Verdadera** | — |

| Elemento | Clasificación |
|---|---|
| 1. Retroalimentación de la revisión | **Entrada** |
| 2. Dividir una historia grande | **Herramienta** |
| 3. Historias con criterio y talla, listas para planificar | **Salida** |
| 4. Cambios del contexto | **Entrada** |
| 5. Estimar por tallas | **Herramienta** |
| 6. Criterio de aceptación «dado, cuando, entonces» | **Herramienta** |

### 🔍 Justificación

Las entradas son lo que alimenta el refinamiento, las herramientas son las técnicas del equipo y las salidas son los
elementos listos para planificar.

### 🔎 Verificación

Cuatro valoraciones correctas con corrección de una frase y seis clasificaciones correctas.

---

## 🟢 Básico 02 — Estimar por tallas

### ✅ Respuesta o criterio

| Historia | Talla | ¿Se divide? |
|---|---|---|
| R1 Ver el detalle de una receta | **S** | No |
| R2 Buscar recetas por ingrediente | **M** | No |
| R3 Armar el menú de la semana | **L** | **Sí** |
| R4 Cambiar el idioma | **S** | No |

**División de R3** (ejemplo; valen otras coherentes y pequeñas): «Asignar recetas a los días de la semana» · «Generar la
lista de compras del menú» · «Compartir el menú con otra persona».

### 🔍 Justificación

R1 y R4 son una pantalla sin reglas; R2 tiene dos pasos y una regla; R3 supera los tres pasos y abarca varias áreas, por lo
que se divide antes de planificar.

### 🔎 Verificación

Cuatro tallas correctas, R3 identificada como la única que se divide y una división en al menos tres historias que no son
grandes.

---

## 🟡 Intermedio 01 — Refinar un Product Backlog

### ✅ Respuesta o criterio

**Tallas iniciales:** «Pagar el pedido» **L** (cinco pasos, varias áreas) · «Buscar plantas por tipo» **S** (un filtro sobre el
catálogo existente) · «Gestionar mi cuenta» **L** (varias funciones).

**Ejemplo de respuesta** (valen otras historias coherentes):

| Historia | Criterio de aceptación | Talla |
|---|---|---|
| Como cliente quiero elegir la forma de pago para pagar mi pedido | Dado que tengo plantas en el carrito, cuando voy a pagar, entonces puedo elegir una forma de pago | M |
| Como cliente quiero confirmar el pago para recibir mis plantas | Dado que elegí la forma de pago, cuando confirmo, entonces el pedido queda pagado y se descuenta el stock | M |
| Como cliente quiero recibir un comprobante para tener constancia de mi compra | Dado que pagué, cuando el pago se confirma, entonces recibo un comprobante | S |
| Como cliente quiero buscar plantas por tipo para encontrar la que necesito | Dado que veo el catálogo, cuando elijo un tipo, entonces solo veo las plantas de ese tipo | S |
| Como cliente quiero registrarme para tener una cuenta | Dado que no tengo cuenta, cuando completo mis datos, entonces mi cuenta queda creada | M |
| Como cliente quiero iniciar sesión para entrar a mi cuenta | Dado que tengo cuenta, cuando ingreso mis datos, entonces accedo a mi cuenta | S |

**Orden sugerido:** elegir la forma de pago · confirmar el pago · recibir el comprobante · buscar plantas por tipo ·
registrarme · iniciar sesión. Se ordena por valor y dependencias (el pago es lo más valioso; registrarse antes de iniciar
sesión). **Listos para planificar:** los del tope, pequeños, con criterio y con talla.

### 🔍 Justificación

Los elementos grandes se dividen, cada historia tiene su criterio y su talla, y el orden respeta valor y dependencias.

### 🔎 Verificación

Tallas iniciales correctas, al menos dos historias por cada elemento grande y ninguna grande, criterios verificables y un
orden justificado.

---

## 🟡 Intermedio 02 — La revisión y la retrospectiva de un sprint

### ✅ Respuesta o criterio

**Parte A**

- **Se demuestran B1 y B2**: cumplen la definición de terminado.
- **B3 no se demuestra**: no cumple la definición de terminado, no forma parte del incremento y vuelve al Product Backlog.
- La retroalimentación (reservar un libro prestado y recibir un aviso de vencimiento) se incorpora al **Product Backlog**, no
  al sprint terminado.

**Parte B**

| Tarjeta | Columna |
|---|---|
| a. Reuniones diarias de 15 minutos | **Continuar** |
| b. Dejar las pruebas para el último día | **Detener** |
| c. Revisar el trabajo entre pares | **Comenzar** |
| d. Mantener un tablero visible | **Continuar** |
| e. Cargar más historias de las que se pueden terminar | **Detener** |
| f. Escribir el criterio antes de planificar | **Comenzar** |

**Acciones** (ejemplo): «Ana escribe las pruebas de cada historia antes de empezarla, desde el próximo sprint» · «Bruno
revisa en cada refinamiento que toda historia tenga criterio de aceptación antes de planificarla, desde el próximo
refinamiento».

### 🔍 Justificación

La revisión solo demuestra lo terminado y lo aprendido va al Product Backlog; la retrospectiva ordena lo que pasó y termina
en acciones concretas.

### 🔎 Verificación

Decisiones correctas en la Parte A, seis tarjetas ubicadas y dos acciones con responsable y plazo.

---

## 🔴 Desafío 01 — Refinar, revisar, mejorar y decidir si escalar

### ✅ Respuesta o criterio

**Cerrado:**

| Elemento | Respuesta |
|---|---|
| Tallas | «Pagar la mensualidad» **L** · «Ver los horarios» **S** · «Recibir un recordatorio» **S** |
| Qué se demuestra | «Ver los horarios» y «Reservar un lugar»; el recordatorio no, porque no cumple la definición de terminado |
| Pedido de los socios | Se agrega «Cancelar una reserva» al Product Backlog; el sprint terminado no cambia |
| Retrospectiva | «Reuniones diarias cortas» → continuar · «pruebas para el final» → detener |
| Caso A | **Escalar** (varios equipos sobre un mismo producto) |
| Caso B | **No** hace falta escalar (un equipo alcanza) |
| Revisión y retrospectiva | La revisión inspecciona el producto; la retrospectiva, la forma de trabajar |

**Abierto (criterios; ejemplo de respuesta):**

- **División de «Pagar la mensualidad»** (al menos tres historias pequeñas con criterio «dado, cuando, entonces»): «Elegir un
  plan» (S) · «Pagar la mensualidad con tarjeta» (M) · «Recibir el comprobante de pago» (S) · «Recibir un aviso cuando vence la
  mensualidad» (S).
- **Orden:** elegir un plan, pagar, comprobante, aviso (valor y dependencias).
- **Acciones:** «Bruno escribe las pruebas de cada historia antes de empezarla, desde el próximo sprint» y «Carla revisa en cada
  refinamiento que toda historia tenga criterio antes de planificarla, desde el próximo refinamiento».
- **Desafíos del caso A** (tres de): dependencias, integración, un solo Product Backlog, coordinación.

### 🔍 Justificación

Cada decisión sigue lo visto: las historias grandes se dividen, solo se demuestra lo terminado, la retroalimentación va al Product
Backlog, la retrospectiva termina en acciones y solo se escala cuando un equipo no alcanza.

### 🔎 Verificación

Se cumplen los casos de prueba del Desafío: tallas, división, qué se demuestra, pedido de los socios, retrospectiva, acciones,
caso A y caso B, desafíos y diferencia entre revisión y retrospectiva.
