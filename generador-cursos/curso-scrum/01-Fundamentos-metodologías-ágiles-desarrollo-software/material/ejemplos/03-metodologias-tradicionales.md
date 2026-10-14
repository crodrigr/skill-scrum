# 📘 Ejemplo 03 — Un mismo proyecto con metodologías tradicionales

## 🧱 Situación inicial

Una clínica pide un **sistema de turnos**: los pacientes piden un turno, recepción lo
confirma y los médicos ven su agenda del día. El equipo analiza cómo organizaría el proyecto
con cada metodología tradicional. Este mismo proyecto se retoma en el Ejemplo 04 con
metodologías ágiles, para poder contrastarlas.

## 🔍 Análisis paso a paso

1. **Con Cascada.**
   - Fases: requisitos (se escriben todos los requisitos de la clínica) → diseño →
     implementación → pruebas → despliegue y mantenimiento.
   - La clínica ve el sistema funcionando recién al final.
   - Si en las pruebas se descubre que recepción necesitaba un campo que nadie pidió,
     corregirlo obliga a volver a fases anteriores: es caro.
   - _Encaja_ si la clínica ya tiene todos sus procesos definidos y no cambiarán.
2. **Con Prototipado.**
   - El equipo arma una maqueta de las pantallas de pedido de turno y de agenda médica.
   - Recepción y médicos la prueban y dicen qué les falta o les molesta.
   - Con esa información, se decide si el prototipo se descarta (desechable) o se mejora hasta
     ser el sistema (evolutivo).
   - _Encaja_ si no está claro cómo quiere trabajar la clínica con las pantallas.
   - _Cuidado_: la clínica puede pensar que la maqueta ya es el sistema terminado.
3. **Con Espiral.**
   - Vuelta 1: objetivos (permitir pedir turnos), riesgos (¿se integra con el sistema de
     historias clínicas de la clínica?), una versión básica, y planificación de la siguiente.
   - Vuelta 2: objetivos (agenda médica), riesgos (privacidad de los datos), una versión más
     completa, y así sucesivamente.
   - _Encaja_ si hay riesgos técnicos o de privacidad importantes.
   - _Cuidado_: exige experiencia en evaluar riesgos y puede resultar costoso.
4. **Qué tienen en común.** Planifican bastante al inicio, trabajan por fases o vueltas
   definidas, y son más cómodas cuando el cambio es poco frecuente.

## ✅ Resultado esperado

| | Cascada | Prototipado | Espiral |
|---|---|---|---|
| Cómo se organiza el sistema de turnos | Todo secuencial por fases | Maquetas que el personal prueba | Vueltas que empiezan por los riesgos |
| Cuándo ve la clínica algo | Al final | Pronto, pero solo un prototipo | En cada vuelta, con versiones cada vez más completas |
| Cuándo encaja | Procesos definidos y estables | Requisitos poco claros | Riesgos técnicos o de privacidad altos |
| Riesgo principal | Descubrir errores tarde | Confundir prototipo con producto | Complejidad y costo |
