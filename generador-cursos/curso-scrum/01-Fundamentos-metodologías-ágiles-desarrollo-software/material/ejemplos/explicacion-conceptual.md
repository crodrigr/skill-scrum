# 📚 Explicación conceptual — Fundamentos de metodologías ágiles en el desarrollo de software

Esta clase no necesita conocimientos previos ni saber programar. Todos los casos son de
software descrito con poco tecnicismo: una tienda en línea, una aplicación móvil, un sistema
de turnos.

Resultados de aprendizaje de la clase:

- **RA-1**: explicar qué es una metodología y qué es una metodología ágil.
- **RA-2**: enunciar el manifiesto ágil, sus valores y sus principios.
- **RA-3**: identificar las ventajas y desventajas de las metodologías ágiles.
- **RA-4**: describir Cascada, Prototipado y Espiral.
- **RA-5**: describir Kanban, Lean y Programación Extrema (XP).
- **RA-6**: comparar metodologías tradicionales y ágiles y justificar cuál conviene.

---

## 🧭 Metodología y primera noción ágil

_Resultados de aprendizaje: RA-1_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 01 — El valor de una metodología](01-valor-de-una-metodologia.md): El valor de una metodología en una tienda en línea.

### 🌍 Contexto

Construir software es un trabajo de equipo: hay que decidir qué se hace, en qué orden, quién
lo hace, cómo se prueba y cuándo se entrega. Un equipo que lo resuelve improvisando cada vez
suele perder tiempo, repetir errores y entregar algo distinto de lo que el cliente esperaba.

### 💡 Concepto

Una **metodología de desarrollo de software** es un conjunto organizado de **fases o ciclos,
roles, prácticas y entregables** que guía cómo un equipo planifica, construye y entrega
software.

| Elemento | Qué responde | Ejemplo |
|---|---|---|
| Fases o ciclos | ¿En qué orden se trabaja? | Primero se definen requisitos, después se diseña |
| Roles | ¿Quién hace qué? | Quien decide prioridades, quien programa, quien prueba |
| Prácticas | ¿Cómo se trabaja? | Reuniones breves, pruebas automáticas |
| Entregables | ¿Qué se produce? | Documentos, versiones del producto |

### 📖 Explicación

Las metodologías se agrupan en dos grandes familias: las **tradicionales** (planifican casi
todo al inicio y avanzan por fases) y las **ágiles** (trabajan en ciclos cortos, entregan
software funcionando con frecuencia y se adaptan al cambio). Más adelante las estudiamos una
por una.

**Primera noción de metodología ágil.** Una metodología ágil es una forma de trabajar que
prefiere **entregas pequeñas y frecuentes, colaboración con el cliente y adaptación al
cambio** antes que un plan rígido definido de una sola vez. Todavía no es la definición
formal: la completamos después de conocer las tradicionales, para poder contrastarlas.

---

## 📜 Manifiesto ágil

_Resultados de aprendizaje: RA-2_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 02 — El manifiesto ágil en acción](02-manifiesto-en-accion.md): Valores y temas de principios ante un cambio de requisitos.

### 🌍 Contexto

A fines de los años noventa, muchos equipos sufrían proyectos que llegaban tarde, costaban
más de lo previsto y entregaban software que ya no servía cuando por fin estaba listo.
En febrero de 2001, un grupo de profesionales del desarrollo de software se reunió en Utah
(Estados Unidos) y redactó el **Manifiesto por el Desarrollo Ágil de Software**.

### 💡 Concepto

El manifiesto declara **cuatro valores** —los "pilares" ágiles— y se desarrolla en **doce
principios**.

**Los cuatro valores.** Cada uno se lee «A sobre B»: se valora más A, **sin descartar** B.

| Se valora más… | …sobre |
|---|---|
| **Individuos e interacciones** | procesos y herramientas |
| **Software funcionando** | documentación extensiva |
| **Colaboración con el cliente** | negociación contractual |
| **Respuesta ante el cambio** | seguir un plan |

> 📌 El propio manifiesto aclara: "aunque valoramos los elementos de la derecha, valoramos
> más los de la izquierda". No dice que no haya procesos, documentación, contratos ni
> planes: dice qué pesa más cuando hay que decidir.

### 📖 Explicación

**Los doce principios**, agrupados en cinco temas (con una frase por principio):

**1. Entrega de valor** (principios 1, 3 y 7)

- (1) La mayor prioridad es satisfacer al cliente con entregas tempranas y continuas de
  software con valor.
- (3) Se entrega software funcionando con frecuencia, de dos semanas a dos meses, con
  preferencia por el período más corto.
- (7) El software funcionando es la medida principal de progreso.

_Ejemplo_: una tienda en línea publica cada dos semanas una mejora que los clientes ya
pueden usar, en vez de esperar un año para mostrar todo junto.

**2. Cambio y cliente** (principios 2 y 4)

- (2) Se aceptan cambios de requisitos, incluso en etapas tardías; los procesos ágiles
  aprovechan el cambio como ventaja competitiva del cliente.
- (4) Las personas de negocio y los desarrolladores trabajan juntas todos los días durante
  el proyecto.

_Ejemplo_: si el cliente pide incorporar un nuevo medio de pago a mitad del proyecto, el
equipo lo incorpora en el siguiente ciclo en lugar de rechazarlo por "no estar en el
contrato".

**3. Personas y equipo** (principios 5, 6, 8 y 11)

- (5) Los proyectos se construyen en torno a personas motivadas, a quienes se les da el
  entorno y el apoyo que necesitan y se les confía el trabajo.
- (6) La conversación cara a cara es el método más eficiente y efectivo de comunicar
  información al equipo y dentro de él.
- (8) Los procesos ágiles promueven un ritmo sostenible: se debe poder mantener un ritmo
  constante de forma indefinida.
- (11) Las mejores arquitecturas, requisitos y diseños surgen de equipos autoorganizados.

_Ejemplo_: el equipo decide cómo repartirse las tareas y resuelve las dudas hablando, sin
esperar a que un informe circule por tres áreas.

**4. Calidad y simplicidad** (principios 9 y 10)

- (9) La atención continua a la excelencia técnica y al buen diseño mejora la agilidad.
- (10) La simplicidad —el arte de maximizar la cantidad de trabajo no realizado— es
  esencial.

_Ejemplo_: el equipo no construye una función "por si acaso": primero la más simple que
resuelve el problema, y revisa el diseño para que siga siendo fácil de cambiar.

**5. Mejora continua** (principio 12)

- (12) A intervalos regulares, el equipo reflexiona sobre cómo ser más efectivo y ajusta su
  forma de trabajar.

_Ejemplo_: al terminar cada ciclo, el equipo se reúne a revisar qué salió bien y qué
cambiaría.

---

## ⚖️ Ventajas y desventajas de las metodologías ágiles

_Resultados de aprendizaje: RA-3_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 02 — El manifiesto ágil en acción](02-manifiesto-en-accion.md): Ventajas y desventajas que se materializan en un equipo.
> - [Ejemplo 05 — Comparar y elegir un enfoque](05-comparar-y-elegir.md): Ventajas y desventajas al elegir un enfoque.

### 🌍 Contexto

Ninguna metodología es buena en todos los casos. Antes de elegir, hay que saber qué se gana y
qué se arriesga.

### 💡 Concepto

| Ventajas | Cuándo se nota | Desventajas | Cuándo se nota |
|---|---|---|---|
| Entrega de valor temprana | El cliente usa algo útil en las primeras semanas | Menos previsibilidad del costo y la fecha del alcance completo | Un contrato pide precio y plazo cerrados para todo el proyecto |
| Adaptación al cambio | Cambian las prioridades del mercado | Requiere un cliente disponible | El cliente no puede dedicar tiempo regular al equipo |
| Visibilidad del avance | En cada ciclo se ve software que funciona | Riesgo de documentación insuficiente | El equipo cambia y nadie recuerda por qué se decidió algo |
| Calidad por retroalimentación frecuente | Los errores se detectan en ciclos cortos | Exige disciplina y madurez del equipo | Un equipo nuevo "es ágil" sin acordar prácticas |
| Participación y motivación del equipo | Las personas deciden cómo trabajar | Puede crecer el alcance sin control | Se aceptan cambios sin priorizar |

### 📖 Explicación

Las desventajas no son un defecto del enfoque: son el precio de lo que se gana. Por eso la
elección depende del contexto (lo vemos en la última sección). Y ojo con un malentendido
común: **ágil no significa "sin planificación ni documentación"**. Se planifica en ciclos
cortos y se documenta lo necesario; lo que cambia es qué pesa más cuando hay que decidir.

---

## 🏛️ Metodologías tradicionales

_Resultados de aprendizaje: RA-4_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 03 — Un mismo proyecto con metodologías tradicionales](03-metodologias-tradicionales.md): Cascada, Prototipado y Espiral aplicados a un mismo proyecto.

### 🌍 Contexto

Antes del manifiesto ágil, la forma dominante de organizar proyectos de software era
planificar casi todo al inicio y ejecutar el plan por fases. Conocerla permite entender por
qué surgieron las ágiles y cuándo todavía conviene usarla.

### 💡 Concepto

Las **metodologías tradicionales** (también llamadas predictivas o en cascada en sentido
amplio) comparten estas ideas:

- **Planificación al inicio**: se definen requisitos, alcance y plazos antes de construir.
- **Fases definidas**: cada fase produce un entregable y se pasa a la siguiente.
- **Documentación extensa**: los documentos son la forma principal de comunicar y controlar.
- **Cambio costoso**: modificar algo ya decidido es difícil y caro.

### 📖 Explicación

**Cascada.** Las fases se suceden una tras otra, como una caída de agua:
requisitos → diseño → implementación → pruebas → despliegue y mantenimiento. No se pasa a
la fase siguiente hasta terminar la anterior.

- _Conviene_ cuando los requisitos son estables y están bien entendidos (por ejemplo, un
  sistema con normas estrictas y alcance cerrado).
- _Limitaciones_: los errores de requisitos se descubren tarde, cuando corregirlos es caro;
  el cliente ve el software funcionando al final.
- _Dato histórico_: el modelo suele atribuirse a un artículo de Winston Royce (1970), que
  presentaba el esquema secuencial como arriesgado y proponía iterar; la versión rígida se
  popularizó después.

**Prototipado.** Se construyen **prototipos** —versiones simples de partes del sistema—
para que el cliente los pruebe y aclare lo que realmente necesita, antes de construir el
producto final.

- _Prototipo desechable_: sirve para aprender y se descarta.
- _Prototipo evolutivo_: se mejora hasta convertirse en el producto.
- _Conviene_ cuando los requisitos son poco claros, sobre todo en la interfaz de usuario.
- _Limitaciones_: el cliente puede creer que el prototipo ya es el producto; puede
  descuidarse la calidad técnica si el prototipo evoluciona sin orden.

**Espiral.** Propuesto por Barry Boehm (1986), organiza el proyecto en **vueltas**. En cada
vuelta se repiten cuatro actividades:

1. determinar los objetivos y alternativas;
2. **evaluar y reducir los riesgos**;
3. desarrollar y verificar una versión;
4. planificar la siguiente vuelta.

- _Conviene_ en proyectos grandes y con riesgos técnicos o de negocio importantes.
- _Limitaciones_: exige experiencia en análisis de riesgos y puede resultar costoso o
  complejo para proyectos pequeños.

| | Cascada | Prototipado | Espiral |
|---|---|---|---|
| Idea central | Fases secuenciales | Aclarar requisitos con prototipos | Vueltas guiadas por el riesgo |
| Cuándo conviene | Requisitos estables | Requisitos poco claros | Riesgos altos y proyecto grande |
| Limitación típica | Cambio tardío costoso | Confundir prototipo con producto | Complejidad y costo |

---

## ⚡ Metodologías ágiles

_Resultados de aprendizaje: RA-5_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 04 — El mismo proyecto con metodologías ágiles](04-metodologias-agiles.md): Kanban, Lean y XP aplicados al mismo proyecto.

### 🌍 Contexto

Con las tradicionales a la vista, podemos definir las ágiles con precisión y ver por qué
surgieron.

### 💡 Concepto

Una **metodología ágil** es un enfoque de desarrollo **iterativo e incremental** que se
apoya en los valores y principios del manifiesto: entrega software funcionando en ciclos
cortos, trabaja en estrecha colaboración con el cliente y se adapta al cambio.

| | Tradicional | Ágil |
|---|---|---|
| Planificación | Casi toda al inicio | En ciclos cortos, ajustada continuamente |
| Entregas | Una grande, al final | Pequeñas y frecuentes |
| Cambio | Costoso | Esperado y bienvenido |
| Cliente | Participa al inicio y al final | Participa durante todo el proyecto |

### 📖 Explicación

Existen varios enfoques ágiles. Aquí vemos tres; otros marcos se estudian más adelante.

**Kanban.** Nació en la manufactura (Toyota) y se aplica al software para gestionar el flujo
del trabajo. Sus prácticas centrales:

1. **Visualizar** el trabajo en un tablero con columnas (por ejemplo, "Por hacer", "En
   curso", "Hecho").
2. **Limitar el trabajo en curso**: no se abren más tareas que el límite de cada columna.
3. **Gestionar el flujo**: detectar dónde se acumula el trabajo (cuellos de botella).
4. **Hacer explícitas las políticas**: se acuerda qué significa que una tarea esté "hecha".
5. **Mejorar de forma continua**.

- _Conviene_ cuando el trabajo llega de manera continua e impredecible (por ejemplo, soporte
  o mantenimiento).
- _Limitaciones_: sin ciclos fijos, no da por sí solo un ritmo de planificación y entrega.

**Lean.** Es una **filosofía** de gestión, heredada del sistema de producción de Toyota y
adaptada al software por Mary y Tom Poppendieck. No es un método con prácticas propias: es
un conjunto de **siete principios** que inspiran a otros enfoques, entre ellos Kanban:

1. eliminar desperdicios;
2. amplificar el aprendizaje;
3. decidir lo más tarde posible;
4. entregar lo más rápido posible;
5. dar poder al equipo;
6. integrar la calidad;
7. ver el todo.

- _Desperdicio_: todo lo que no aporta valor al cliente (esperas, funciones que nadie usa,
  trabajo repetido).
- _Limitaciones_: al ser una filosofía, necesita traducirse en prácticas concretas.

**Programación Extrema (XP).** Creada por Kent Beck, se centra en la **calidad técnica** y
la colaboración. Sus valores son comunicación, simplicidad, retroalimentación, coraje y
respeto. Prácticas distintivas:

- programación en parejas;
- desarrollo guiado por pruebas (escribir la prueba antes del código);
- integración continua (unir el trabajo varias veces al día);
- refactorización (mejorar el diseño sin cambiar lo que hace);
- entregas pequeñas y juego de planificación con el cliente.

- _Conviene_ con requisitos cambiantes y equipos pequeños, con acceso al cliente.
- _Limitaciones_: exige mucha disciplina técnica y compromiso del equipo.

> 💡 Cuidado con mezclar las atribuciones: el tablero con límites es de Kanban; eliminar desperdicio
> es de Lean; programar en parejas y escribir pruebas primero es de XP.

---

## 🔀 Comparar y elegir

_Resultados de aprendizaje: RA-6_

> 🔗 **Ejemplos de este concepto**
>
> - [Ejemplo 05 — Comparar y elegir un enfoque](05-comparar-y-elegir.md): Dos casos, una tabla de criterios y una decisión.

### 🌍 Contexto

Conocer los enfoques sirve para decidir con criterio. La pregunta no es "cuál es mejor", sino
"cuál encaja con este proyecto".

### 💡 Concepto

| Criterio | Si pesa más… | Tiende a convenir |
|---|---|---|
| Requisitos | Cambian con frecuencia o son inciertos | Ágil |
| Requisitos | Estables, completos y firmados | Tradicional |
| Cliente | Puede colaborar a menudo | Ágil |
| Contrato y regulación | Alcance, precio y documentación cerrados por norma | Tradicional |
| Riesgo | Alto y técnico | Espiral (tradicional) o ciclos cortos con revisión de riesgos |
| Entregas | Se necesita valor temprano | Ágil |
| Equipo | Pequeño, con autonomía y disciplina | Ágil |

### 📖 Explicación

Para elegir, seguí tres pasos: **(1)** describí las características del proyecto (requisitos,
cambios esperados, riesgos, cliente, regulación); **(2)** contrastalas con la tabla de
criterios; **(3)** elegí el enfoque, justificalo con al menos dos ventajas y dos desventajas
y señalá un riesgo. Es válido combinar elementos: muchos equipos adoptan lo mejor de cada
enfoque según su contexto.

**Malentendidos frecuentes:**

- "Ágil significa no planificar ni documentar": falso, se planifica en ciclos cortos.
- "Las tradicionales son malas": falso, siguen siendo adecuadas con requisitos estables o
  regulación estricta.
- "Lean es lo mismo que Kanban": falso, Lean es una filosofía y Kanban una forma de gestionar
  el flujo; se complementan.
- "Ágil es lo mismo que Scrum": falso, Scrum es un marco ágil entre otros.

**Adelanto de Scrum.** Scrum es un **marco ágil** muy usado que organiza el trabajo en ciclos
cortos llamados *sprints*, con roles, eventos y artefactos definidos. Es uno de los enfoques
que nacen del manifiesto ágil, igual que Kanban o XP. Lo estudiamos en detalle en el módulo
siguiente.
