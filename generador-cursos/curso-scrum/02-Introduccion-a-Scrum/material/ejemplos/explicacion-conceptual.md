# 📚 Explicación conceptual — Introducción a Scrum

Esta clase asume que conocés la idea de metodología ágil de la Clase 01, aunque no es
obligatoria. No hace falta saber programar: los casos son de software descrito con poco
tecnicismo.

Resultados de aprendizaje de la clase:

- **RA-1**: explicar qué es un marco de trabajo y en qué se diferencia de una metodología
  prescriptiva.
- **RA-2**: definir qué es Scrum y para qué sirve.
- **RA-3**: enunciar los principios de Scrum (pilares y valores).
- **RA-4**: identificar los roles de Scrum y sus responsabilidades.
- **RA-5**: describir el flujo de trabajo de un sprint y sus artefactos básicos.
- **RA-6**: describir las reuniones (ceremonias) de Scrum.

## 🗒️ Glosario

Usamos los términos de Scrum en inglés, porque son los que vas a escuchar en un equipo. La
primera vez aparece su equivalente; después usamos siempre el mismo término.

| Término | Equivalente |
|---|---|
| *Sprint* | ciclo de trabajo de duración fija |
| *Product Owner* | dueño del producto |
| *Scrum Master* | facilitador del equipo |
| *Developers* | desarrolladores (antes, «equipo de desarrollo») |
| *Product Backlog* | lista del producto |
| *Sprint Backlog* | lista del sprint |
| *Increment* | incremento |
| *Definition of Done* | definición de terminado |

Las reuniones las nombramos en español: **planificación del sprint**, **reunión diaria**
(*Daily Scrum*), **revisión del sprint** y **retrospectiva**.

---

## 🧩 Marco de trabajo

_Resultados de aprendizaje: RA-1_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 01 — Marco de trabajo frente a metodología](01-marco-vs-metodologia.md): dos equipos, uno con un manual que prescribe todo y otro con un marco mínimo.

### 🌍 Contexto

En la Clase 01 vimos que una metodología organiza cómo trabaja un equipo. Pero hay metodologías
que intentan decirlo todo —qué documentos escribir, cuántas reuniones hacer, cómo programar— y
otras que dan solo una estructura mínima. Esa diferencia es la que separa una metodología
prescriptiva de un marco de trabajo.

### 💡 Concepto

Un **marco de trabajo** (*framework*) es una **estructura mínima** de reglas, roles y reuniones
que cada equipo **completa con sus propias prácticas**. Es incompleto a propósito: define qué
tiene que pasar, no cómo se hace cada cosa.

| | Metodología prescriptiva | Marco de trabajo |
|---|---|---|
| Qué define | Casi todo: pasos, documentos, prácticas | Solo lo esencial: roles, ciclos y reuniones |
| Quién completa los detalles | Ya vienen definidos | Cada equipo, según su contexto |
| Flexibilidad | Baja | Alta |
| Riesgo | Aplicar pasos que no aportan valor | Que el equipo no complete lo que falta |

### 📖 Explicación

Un marco ágil es deliberadamente incompleto porque los equipos y los productos son distintos: lo
que funciona para un equipo de cinco personas que hace una aplicación móvil puede sobrar o
faltar en otro contexto. El marco ofrece una **estructura compartida** para colaborar y deja
libres las decisiones que dependen de cada equipo.

Scrum es un marco de este tipo: dice quién tiene qué responsabilidad, cuánto dura un ciclo y qué
reuniones hay, pero **no dice cómo programar, probar ni diseñar**. Eso lo decide cada equipo.

---

## 🏉 ¿Qué es Scrum?

_Resultados de aprendizaje: RA-1, RA-2_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 01 — Marco de trabajo frente a metodología](01-marco-vs-metodologia.md): qué cubre Scrum y qué deja libre cada equipo.

### 🌍 Contexto

De los enfoques ágiles que vimos en la Clase 01 (Kanban, Lean, XP), Scrum es el más difundido en
los equipos que desarrollan productos de software. Lo crearon Ken Schwaber y Jeff Sutherland a
principios de los años noventa y lo mantienen actualizado en la **Guía de Scrum**; esta clase
usa la versión 2020.

### 💡 Concepto

**Scrum** es un **marco de trabajo ligero** que ayuda a personas, equipos y organizaciones a
generar valor a través de soluciones adaptativas para problemas complejos.

- **Ligero**: define pocas reglas y deja el resto al equipo.
- **Basado en el empirismo**: el conocimiento surge de la experiencia, y las decisiones se
  toman a partir de lo que se observa.
- **Basado en el pensamiento Lean**: reducir el desperdicio y centrarse en lo esencial.
- **Iterativo e incremental**: el trabajo avanza en ciclos cortos llamados *sprints*, y en cada
  uno se obtiene algo utilizable.

### 📖 Explicación

Scrum se usa cuando el problema es **complejo**: no se sabe de antemano todo lo que hay que
construir y se aprende a medida que se avanza, como en el desarrollo de un producto de software.
No pretende ser la solución a todo: si el trabajo es repetitivo y totalmente predecible, otras
formas de organizarlo pueden servir mejor.

Scrum no es sinónimo de «metodología ágil»: es **un** marco ágil entre otros, igual que
Kanban o XP. Y no es un manual de pasos: las prácticas técnicas las elige cada equipo.

---

## 🏛️ Principios de Scrum: pilares y valores

_Resultados de aprendizaje: RA-3_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 02 — Pilares y valores](02-pilares-y-valores.md): una situación de equipo y qué pilar y qué valor refleja cada parte.

### 🌍 Contexto

Scrum se apoya en la experiencia y en la confianza entre las personas. Esas ideas se resumen en
tres pilares y cinco valores.

### 💡 Concepto

**Los tres pilares del empirismo:**

| Pilar | Qué significa | Ejemplo |
|---|---|---|
| **Transparencia** | El proceso y el trabajo son visibles para quienes lo realizan y para quienes lo reciben | Un tablero con las tareas del sprint que ve todo el mundo |
| **Inspección** | Se revisa con frecuencia el trabajo y el progreso hacia los objetivos, para detectar desvíos | La reunión diaria, para ver el avance hacia el objetivo del sprint |
| **Adaptación** | Si algo se desvía, se ajusta el proceso o lo que se produce, lo antes posible | Cambiar lo que se construye porque los usuarios no usaron una función |

**Los cinco valores:**

| Valor | Cómo se ve en un equipo |
|---|---|
| **Compromiso** | Las personas se comprometen a lograr los objetivos del equipo y a apoyarse |
| **Enfoque** | Se concentran en el trabajo del sprint y en los objetivos del equipo |
| **Apertura** | El equipo y los interesados son abiertos con el trabajo y con los desafíos |
| **Respeto** | Se respetan como personas capaces e independientes |
| **Coraje** | Se animan a hacer lo correcto y a trabajar en problemas difíciles |

### 📖 Explicación

Los pilares funcionan juntos: sin **transparencia** no se puede **inspeccionar**, y sin
**inspección** no hay nada que **adaptar**. Los valores son los comportamientos que hacen
posible ese ciclo: no se puede ser transparente si el equipo no se anima a mostrar un problema.

> 📌 Cuidado con confundirlos con los **valores del manifiesto ágil** de la Clase 01 (individuos e
> interacciones, software funcionando, colaboración con el cliente, respuesta ante el cambio).
> Son dos listas distintas: el manifiesto orienta a todo el movimiento ágil y los pilares y
> valores de esta sección son propios de Scrum.

---

## 👥 Organización: roles y responsabilidades

_Resultados de aprendizaje: RA-4_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 03 — Roles en el proyecto](03-roles-en-el-proyecto.md): quién decide qué en una aplicación de reservas de canchas de pádel.

### 🌍 Contexto

Scrum define pocos roles, pero cada uno tiene responsabilidades muy precisas. Casi todos los
malentendidos sobre Scrum vienen de confundirlos.

### 💡 Concepto

El **equipo Scrum** está formado por **un *Scrum Master*, un *Product Owner* y los *Developers***.
Es pequeño (típicamente diez personas o menos), **autogestionado** (decide por sí mismo quién
hace qué y cómo) y **multifuncional** (reúne las habilidades necesarias para entregar valor).
No hay subequipos ni jerarquías dentro de él.

| Rol | Responsabilidad principal | Qué hace |
|---|---|---|
| ***Product Owner*** (dueño del producto) | Maximizar el valor del producto | Gestiona la lista del producto: comunica el objetivo del producto, ordena los elementos y se asegura de que sea transparente |
| ***Scrum Master*** (facilitador del equipo) | Establecer Scrum y la efectividad del equipo | Ayuda a todos a entender Scrum, quita impedimentos y asegura que las reuniones se hagan y sean productivas |
| ***Developers*** (desarrolladores) | Crear un incremento utilizable en cada sprint | Planifican el sprint, construyen con calidad, adaptan su plan cada día y se responsabilizan mutuamente |

### 📖 Explicación

**Product Owner.** Es **una sola persona**, no un comité. Puede consultar a muchas personas, pero
la decisión de qué va primero es suya, y la organización debe respetarla.

**Scrum Master.** Es un **líder que sirve**: sirve al equipo (coaching, facilitación), al
*Product Owner* (técnicas para gestionar la lista) y a la organización (ayuda a adoptar Scrum).
**No es el jefe del equipo ni su gerente de proyecto**: no asigna tareas ni controla a las
personas.

**Developers.** Son todas las personas que crean cualquier parte del incremento: programan, pero
también pueden diseñar, probar o analizar. Deciden **cómo** se hace el trabajo del sprint.

**Errores frecuentes:**

- «El *Scrum Master* es el jefe del equipo»: falso, es un facilitador.
- «El *Product Owner* es un comité»: falso, es una persona.
- «Los *Developers* son solo quienes programan»: falso, son quienes crean el incremento.

---

## 🔄 Flujo de trabajo: sprint y artefactos

_Resultados de aprendizaje: RA-5_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 04 — Flujo de un sprint](04-flujo-de-un-sprint.md): de la lista del producto al incremento, en el proyecto de canchas de pádel.

### 🌍 Contexto

Con los roles claros, falta ver cómo se mueve el trabajo: qué se hace primero, qué pasa dentro
de un ciclo y qué se obtiene al final.

### 💡 Concepto

Scrum organiza el trabajo en **sprints**: ciclos de **duración fija, de un mes o menos**. Un
sprint nuevo empieza apenas termina el anterior. El sprint es el contenedor de todas las
reuniones.

Tres **artefactos** (con un **compromiso** cada uno) dan transparencia al trabajo:

| Artefacto | Qué es | Compromiso |
|---|---|---|
| ***Product Backlog*** (lista del producto) | Lista ordenada de lo que se necesita para mejorar el producto | **Objetivo del producto**: la meta a largo plazo |
| ***Sprint Backlog*** (lista del sprint) | Objetivo del sprint, elementos elegidos y plan para entregarlos | **Objetivo del sprint**: el propósito del sprint |
| ***Increment*** (incremento) | Un paso concreto y utilizable hacia el objetivo del producto | ***Definition of Done*** (definición de terminado): cuándo algo está terminado |

### 📖 Explicación

**El flujo de un sprint, paso a paso:**

1. El *Product Owner* mantiene ordenada la lista del producto.
2. En la **planificación del sprint**, el equipo acuerda un objetivo del sprint y elige los
   elementos que entran, y arma la lista del sprint.
3. Los *Developers* **trabajan en el sprint** y se reúnen cada día para revisar el avance.
4. Al final se obtiene un **incremento utilizable**, que cumple la definición de terminado.
5. En la **revisión del sprint** se inspecciona el resultado y se ajusta la lista del producto.
6. En la **retrospectiva** el equipo revisa cómo trabajó y acuerda mejoras.
7. Empieza el siguiente sprint.

**Reglas del sprint:** el objetivo del sprint no se cambia durante el sprint; la calidad no se
reduce; el alcance se puede aclarar y renegociar con el *Product Owner* a medida que se aprende;
y **solo el *Product Owner* puede cancelar** un sprint (si el objetivo ya no tiene sentido).
Si el trabajo no alcanza, **la duración no se estira: se ajusta el alcance**.

> 💡 Cómo se refina la lista del producto, cómo se escriben los elementos o cómo se estiman es
> tema de un módulo posterior. Acá solo importa que existe y que está ordenada.

---

## 🗓️ Reuniones (ceremonias)

_Resultados de aprendizaje: RA-6_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 05 — Reuniones del sprint](05-reuniones-del-sprint.md): las cuatro reuniones de un sprint de dos semanas, con propósito, participantes, tiempo máximo y resultado.

### 🌍 Contexto

Scrum define pocas reuniones, todas con tiempo limitado y un propósito claro. La guía oficial las
llama **eventos**; en la práctica se las conoce como **ceremonias**. Son lo mismo.

### 💡 Concepto

Las cuatro reuniones, además del sprint que las contiene:

| Reunión | Propósito | Quiénes participan | Máximo (sprint de un mes) | Resultado |
|---|---|---|---|---|
| **Planificación del sprint** | Planificar el trabajo del sprint: por qué es valioso, qué se puede hacer y cómo | Todo el equipo Scrum | 8 horas | Objetivo del sprint y lista del sprint |
| **Reunión diaria** | Inspeccionar el avance hacia el objetivo del sprint y adaptar la lista del sprint | *Developers* | 15 minutos | Un plan para el día |
| **Revisión del sprint** | Inspeccionar el resultado del sprint y decidir adaptaciones futuras | Equipo Scrum e interesados clave | 4 horas | Lista del producto ajustada |
| **Retrospectiva** | Planificar formas de aumentar la calidad y la efectividad | Equipo Scrum | 3 horas | Mejoras acordadas |

> 📌 Los máximos de la tabla son para un **sprint de un mes**. En sprints más cortos, las
> reuniones son proporcionalmente más breves. En los ejemplos de esta clase usamos sprints de
> **dos semanas**.

### 📖 Explicación

- **La planificación** abre el sprint y responde tres preguntas: por qué es valioso, qué se
  puede hacer y cómo se hará.
- **La reunión diaria** es **de los *Developers* y para ellos**: su propósito es revisar el
  avance hacia el objetivo del sprint y ajustar el plan. **No es un informe de estado para un
  jefe** y dura como máximo quince minutos.
- **La revisión del sprint** no es solo una presentación: es una sesión de trabajo donde el
  equipo y los interesados miran el incremento y deciden qué sigue. Inspecciona **el producto**.
- **La retrospectiva** cierra el sprint e inspecciona **la forma de trabajar** (personas,
  interacciones, procesos, herramientas y definición de terminado).

**Malentendidos frecuentes:**

- «La reunión diaria es un informe de estado para el jefe»: falso, es de los *Developers*.
- «Si no terminamos, alargamos el sprint»: falso, la duración es fija; se ajusta el alcance.
- «Scrum dice cómo programar y probar»: falso, Scrum es un marco ligero; las prácticas técnicas
  las elige cada equipo.
- «Ceremonias y reuniones son cosas distintas»: falso, son el mismo concepto que la guía llama
  eventos.
