# 📘 Ejemplo 05 — Comparar y elegir un enfoque

## 🧱 Situación inicial

Una consultora recibe dos pedidos.

- **Caso A — Aplicación de reparto de comidas.** Una empresa nueva quiere lanzar su
  aplicación lo antes posible. No sabe aún qué funciones usarán los clientes. Espera cambiar
  prioridades cada mes y puede reunirse con el equipo varias veces por semana.
- **Caso B — Software de control de un laboratorio.** Un laboratorio debe cumplir una norma
  que exige documentar cada requisito y cada prueba antes de usar el sistema. El contrato fija
  alcance, precio y plazo, y los requisitos están completos y firmados.

## 🔍 Análisis paso a paso

**Paso 1. Describir cada caso con los criterios.**

| Criterio | Caso A | Caso B |
|---|---|---|
| Requisitos | Inciertos y cambiantes | Completos y firmados |
| Cliente | Disponible con frecuencia | Participa al inicio y en las revisiones formales |
| Contrato y regulación | Flexible | Alcance, precio y documentación cerrados por norma |
| Riesgo | De mercado (¿lo usarán?) | De cumplimiento normativo |
| Entregas | Se necesita valor temprano | Se entrega al final tras la aprobación |

**Paso 2. Elegir para el Caso A.** Tiene requisitos cambiantes, un cliente disponible y
necesidad de valor temprano: encaja un **enfoque ágil**. Por ejemplo, ciclos cortos con un
tablero Kanban para ordenar el trabajo.

- _Ventajas_: entrega temprana y adaptación al cambio.
- _Desventajas_: costo y fecha finales menos previsibles; necesita al cliente disponible.
- _Riesgo_: que el alcance crezca sin control si no se prioriza.

**Paso 3. Elegir para el Caso B.** Tiene requisitos cerrados, una norma que exige
documentación previa y un contrato de alcance fijo: encaja un **enfoque tradicional**, por
ejemplo Cascada, con fases y documentos aprobados. Si hubiera riesgos técnicos altos,
Espiral sería una alternativa.

- _Ventajas_: previsibilidad de costo y plazo, y documentación para la norma.
- _Desventajas_: cambiar algo tarde es caro; el usuario ve el sistema al final.
- _Riesgo_: descubrir un error de requisitos tarde.

**Paso 4. Evitar el error de "siempre ágil".** El Caso B no es "peor": la regulación y el
contrato hacen que el enfoque tradicional sea adecuado.

## ✅ Resultado esperado

| | Caso A | Caso B |
|---|---|---|
| Enfoque elegido | Ágil (por ejemplo, ciclos cortos con Kanban) | Tradicional (por ejemplo, Cascada) |
| Justificación | Requisitos cambiantes, cliente disponible, valor temprano | Requisitos cerrados, norma y contrato de alcance fijo |
| Ventajas | Entrega temprana; adaptación | Previsibilidad; documentación |
| Desventajas | Costo y fecha menos previsibles | Cambio tardío caro |
| Riesgo | Crecimiento del alcance | Error de requisitos detectado tarde |
