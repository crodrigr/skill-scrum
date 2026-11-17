# 🔑 Soluciones — Ejercicios de la Clase 01 (material docente)

No compartir este archivo con los estudiantes.

Los ejercicios de esta clase son conceptuales: no hay comandos que ejecutar. Para cada uno se
indica la **respuesta o el criterio**, la **justificación** y cómo **verificar** la respuesta
de una persona. Donde la respuesta es abierta, se lista lo que debe aparecer.

---

## 🟢 Básico 01 — Definir metodología y metodología ágil

### ✅ Respuesta o criterio

Una respuesta correcta contiene:

- **Metodología**: un conjunto organizado de fases o ciclos, roles, prácticas y entregables
  que guía cómo un equipo planifica, construye y entrega software.
- **Elementos con ejemplo** (valen otros ejemplos coherentes):

| Elemento | Ejemplo válido |
|---|---|
| Fases o ciclos | Primero definir qué se hace, luego construir y probar |
| Roles | Quien decide prioridades; quien programa; quien prueba |
| Prácticas | Reuniones breves de coordinación; pruebas automáticas |
| Entregables | Versiones del producto; documentos necesarios |

- **Ágil**: entregas pequeñas y frecuentes, colaboración con el cliente y adaptación al
  cambio, en lugar de un plan rígido definido de una vez.
- **Ejemplo concreto**: por ejemplo, ante un cambio de requisitos el equipo lo prioriza con el
  cliente y lo incorpora en el siguiente ciclo.

### 🔍 Justificación

Se verifica que la persona distinga la metodología (organización del trabajo) de una
herramienta o un lenguaje, y que no reduzca lo ágil a "sin planificar".

### 🔎 Verificación

La respuesta cumple la restricción de no afirmar que ágil significa "sin planificar ni
documentar" y menciona al menos dos de las tres ideas de lo ágil.

---

## 🟢 Básico 02 — Valores, principios y ventajas del enfoque ágil

### ✅ Respuesta o criterio

**Situaciones** (valor y tema esperados):

| Situación | Valor | Tema de principios |
|---|---|---|
| S1 (cambio del medio de pago) | 4. Respuesta ante el cambio sobre seguir un plan | Cambio y cliente |
| S2 (entrega cada dos semanas) | 2. Software funcionando sobre documentación extensiva | Entrega de valor |
| S3 (trabajo diario con negocio) | 3. Colaboración con el cliente sobre negociación contractual | Cambio y cliente |
| S4 (conversación sin tickets) | 1. Individuos e interacciones sobre procesos y herramientas | Personas y equipo |
| S5 (ritmo sostenible) | 1. Individuos e interacciones sobre procesos y herramientas | Personas y equipo |

**Frases**:

| Frase | Clasificación |
|---|---|
| a | Ventaja |
| b | Desventaja |
| c | Ventaja |
| d | Desventaja |
| e | Ventaja |
| f | Desventaja |

### 🔍 Justificación

- S1 aplica el principio 2 (aceptar cambios); S3, el principio 4 (trabajo diario conjunto).
- S2 aplica los principios 3 y 7 (entrega frecuente, software funcionando como medida de
  progreso).
- S4 aplica el principio 6 (conversación cara a cara); S5, el principio 8 (ritmo sostenible).
- Las justificaciones deben aclarar que lo de la derecha del valor no se descarta.

### 🔎 Verificación

Cada situación tiene un solo valor y un solo tema, y las seis frases quedan clasificadas como
se indica. Si alguien asigna otro valor en S4 o S5, debe justificarlo con el texto de la
situación; la respuesta de referencia es la de la tabla.

---

## 🟡 Intermedio 01 — Clasificar proyectos: Cascada, Prototipado o Espiral

### ✅ Respuesta o criterio

| Proyecto | Metodología | Rasgos | Limitación típica |
|---|---|---|---|
| P1 | Cascada | Requisitos completos y firmados; fases consecutivas con documento aprobado | Los errores de requisitos se descubren tarde y corregirlos es caro |
| P2 | Prototipado | El cliente no sabe qué quiere; maquetas navegables que prueba y ajusta | Confundir el prototipo con el producto final |
| P3 | Espiral | Riesgos técnicos muy altos; vueltas que empiezan evaluando riesgos | Complejidad y costo; exige experiencia en análisis de riesgos |

### 🔍 Justificación

Cada descripción contiene los rasgos distintivos de una sola metodología: fases secuenciales
(Cascada), maquetas para aclarar requisitos (Prototipado), vueltas guiadas por el riesgo
(Espiral).

### 🔎 Verificación

Cada metodología aparece exactamente una vez, los rasgos se citan de la descripción y las
limitaciones corresponden a la metodología elegida.

---

## 🟡 Intermedio 02 — Reconocer Kanban, Lean y XP

### ✅ Respuesta o criterio

| Equipo | Enfoque | Práctica o principio | Tipo |
|---|---|---|---|
| E1 | Kanban | Tablero con columnas y límite de trabajo en curso | Método de gestión del flujo |
| E2 | Lean | Eliminar desperdicios (esperas y funciones que nadie usa) | Filosofía |
| E3 | XP | Programación en parejas, pruebas antes del código, integración continua | Conjunto de prácticas de ingeniería |

### 🔍 Justificación

El tablero con límite es el sello de Kanban; eliminar desperdicio es el primer principio de
Lean; las parejas, las pruebas primero y la integración frecuente son prácticas de XP.

### 🔎 Verificación

Cada enfoque aparece una vez, sin atribuciones cruzadas y sin otros enfoques agregados.

---

## 🔴 Desafío 01 — Elegir y justificar un enfoque

### ✅ Respuesta o criterio

| | Caso A (aplicación de turnos para gimnasios) | Caso B (software de laboratorio) |
|---|---|---|
| Requisitos | Inciertos y cambiantes | Completos y firmados |
| Cliente | Disponible varias veces por semana | Participa en revisiones formales |
| Contrato y regulación | Sin normas | Norma que exige documentación y contrato de alcance fijo |
| Riesgo | De mercado (¿se usará?) | De cumplimiento normativo |
| Entregas | Valor temprano | Entrega final tras la aprobación |
| **Enfoque** | **Ágil** (por ejemplo, Kanban o XP con ciclos cortos) | **Tradicional** (Cascada; Espiral si hay riesgos técnicos altos) |

**Ventajas y desventajas esperadas** (al menos dos de cada una; valen otras coherentes):

- Caso A, ventajas: entrega de valor temprano; adaptación al cambio. Desventajas: costo y
  fecha menos previsibles; requiere cliente disponible.
- Caso B, ventajas: previsibilidad de costo y plazo; documentación para la norma.
  Desventajas: cambio tardío costoso; el usuario ve el sistema al final.

**Riesgo y mitigación** (ejemplos): Caso A, crecimiento del alcance → priorizar con el
cliente en cada ciclo. Caso B, error de requisitos detectado tarde → revisiones formales
tempranas o prototipos puntuales.

**Descarte**: el enfoque ágil no encaja en B porque la norma y el contrato exigen documentación
y alcance cerrados antes de empezar; el tradicional no encaja en A porque los requisitos
cambiarán y se necesita valor temprano.

### 🔍 Justificación

Los criterios de cada caso apuntan de forma clara a un enfoque distinto; la persona debe
ligar cada decisión a las características del caso, no a una preferencia.

### 🔎 Verificación

Se cumplen los casos de prueba del Desafío: Caso A ágil; Caso B tradicional; criterios
correctos; al menos dos ventajas y dos desventajas coherentes; un riesgo con mitigación por
caso; y justificación del descarte.
