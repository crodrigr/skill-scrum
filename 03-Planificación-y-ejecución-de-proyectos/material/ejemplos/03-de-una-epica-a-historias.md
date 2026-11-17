# 📘 Ejemplo 03 — De una épica a historias

## 🧱 Situación inicial

Lucía va a trabajar la épica **E1 — Buscar y reservar canchas**. Es demasiado grande para
planificarla, así que debe dividirla en **historias de usuario** pequeñas, con criterio de
aceptación y prioridad. Además, alguien del equipo propone esta historia:

> *«Como jugador quiero administrar mis reservas.»*

## 🔍 Análisis paso a paso

1. **Identificar los valores de E1.** Un jugador necesita: ver qué canchas están libres, reservar
   un turno, recibir una confirmación y poder filtrar por tipo de cancha.
2. **Redactar cada historia** con el formato «como…, quiero…, para…».
3. **Agregar el criterio de aceptación** en formato «dado…, cuando…, entonces…», verificable.
4. **Ordenar por valor y dependencias.** No se puede reservar sin ver las canchas libres, y la
   confirmación depende de la reserva; el filtro mejora la búsqueda pero no es imprescindible.
5. **Revisar la historia del equipo.** «Administrar mis reservas» no cabe en un sprint y mezcla
   varias cosas: es una **épica disfrazada**. Se divide en tres historias (ver mis reservas,
   cancelar una reserva y cambiar el horario de una reserva), que pertenecen a la épica E3.
6. **Distinguir historia de tarea.** «Diseñar la pantalla de reserva» es una **tarea** (un paso
   del equipo), no una historia (no describe un valor para el jugador).
7. **Recordar el origen.** La historia, el formato «como, quiero, para» y el criterio de
   aceptación son prácticas habituales, no están en la Guía de Scrum.

## ✅ Resultado esperado

**Historias de E1, en orden de prioridad**

| Orden | Historia | Criterio de aceptación |
|---|---|---|
| H1 | Como jugador quiero ver las canchas libres de un día para elegir un horario | Dado que elijo una fecha, cuando consulto las canchas, entonces veo cuáles están libres y en qué horarios |
| H2 | Como jugador quiero reservar un turno en una cancha libre para asegurar mi lugar | Dado que elijo una cancha libre, cuando confirmo la reserva, entonces la cancha queda reservada a mi nombre |
| H3 | Como jugador quiero recibir una confirmación de mi reserva para tener la certeza de que quedó hecha | Dado que reservé una cancha, cuando se confirma la reserva, entonces recibo un mensaje con el día, la hora y la cancha |
| H4 | Como jugador quiero filtrar las canchas por tipo (cubierta o descubierta) para elegir según el clima | Dado que veo las canchas, cuando elijo un tipo, entonces solo veo las canchas de ese tipo |

**Historia demasiado grande, dividida (épica E3)**

| Antes | Después |
|---|---|
| «Como jugador quiero administrar mis reservas» | Ver mis reservas · Cancelar una reserva · Cambiar el horario de una reserva |

![Anatomía de una historia de usuario: título, formato como-quiero-para y criterio de aceptación en formato dado-cuando-entonces.](../imagenes/anatomia-historia.svg)
