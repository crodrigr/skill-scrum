# 📘 Ejemplo 05 — Escalar a varios equipos

## 🧱 Situación inicial

La **aplicación para reservar canchas de pádel** fue un éxito. Ahora la quieren usar **seis clubes** en una red:
cada club quiere sus canchas, sus pagos y sus mensajes, y los jugadores quieren buscar canchas en todos. Un solo
equipo ya no alcanza para construir todo a tiempo. La empresa arma **seis equipos Scrum**: Búsqueda, Reservas,
Pagos, Mensajes, Clubes y Plataforma.

Además, un club vecino pide una aplicación sencilla de reservas **solo para él**, con un equipo de cuatro
personas.

## 🔍 Análisis paso a paso

1. **Decidir si hace falta escalar.** En la red de seis clubes, un solo equipo no puede con el producto y varios
   equipos deben aportar al **mismo producto**: hace falta escalar. En el club vecino, un equipo de cuatro personas
   puede con un producto sencillo: **no hace falta escalar** y conviene seguir con un único equipo Scrum.
2. **Identificar los desafíos de la red.**
   - **Dependencias:** Pagos depende de lo que construye Reservas; si Reservas se atrasa, Pagos se frena.
   - **Integración:** lo que hace cada equipo debe funcionar junto. Cada sprint tiene que terminar con **un
     incremento integrado** de la aplicación.
   - **Un solo Product Backlog:** es un solo producto, así que hay una sola lista ordenada y una sola persona que
     decide las prioridades, aunque los equipos aporten elementos.
   - **Coordinación:** los seis equipos deben sincronizar su planificación y su avance para no pisarse.
3. **Mantener lo que Scrum ya pide.** Cada equipo sigue siendo un equipo Scrum, con sus sprints y sus reuniones.
   Lo que cambia es cómo se coordinan entre sí.
4. **Mirar el panorama de enfoques.** Existen varios enfoques de escalamiento; la clase no profundiza en
   ninguno. Algunos, con una frase tomada de su fuente oficial:
   - **LeSS:** extiende Scrum de un equipo a varios; mantiene un único Product Backlog y un único *Product Owner*.
   - **Scrum@Scale:** una extensión natural del marco Scrum para «equipos de equipos»; lo creó Jeff Sutherland.
   - **SAFe:** un modelo operativo para escalar prácticas Lean y ágiles en toda una empresa.
   - **Nexus:** otro enfoque de escalamiento; no lo describimos acá.
5. **Ver lo que comparten.** Todos giran en torno a **un producto, un Product Backlog, un incremento integrado y
   coordinación entre equipos**, que es lo que mostramos en el esquema.
6. **Recordar el orden.** Primero se domina Scrum con un equipo; recién cuando el producto lo exige se escala.

## ✅ Resultado esperado

| Caso | ¿Escalar? | Por qué |
|---|---|---|
| Red de seis clubes | **Sí** | Un solo equipo no alcanza y varios deben aportar al mismo producto |
| Club vecino, equipo de cuatro | **No** | Un equipo puede con un producto sencillo |

| Desafío | En la red de seis clubes |
|---|---|
| Dependencias | Pagos depende de Reservas |
| Integración | Un incremento integrado por sprint |
| Un solo Product Backlog | Una sola lista ordenada y una sola persona que prioriza |
| Coordinación | Sincronizar planificación y avance entre los seis equipos |

![Seis equipos Scrum que trabajan sobre un solo producto: un objetivo del producto, un solo Product Backlog y un incremento integrado en cada sprint, con coordinación entre equipos.](../imagenes/escalamiento-equipos.svg)

> 📌 Las frases sobre LeSS, Scrum@Scale y SAFe salen de sus páginas oficiales. Cada enfoque tiene reglas y roles
> propios que no vemos en esta clase.
