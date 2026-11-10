# Guía de facilitación: sesión de calibración de estimación

Nov 10, 2026 · @Geovanny

## Objetivo

En 60 minutos, el equipo sale con 3 historias de referencia acordadas (una S, una M y una L) que servirán como regla de medir en cada refinamiento.

La sesión no estima trabajo nuevo. Se ordenan historias ya terminadas, que todos conocen, para construir una escala compartida sin presión.

Resultados esperados al cerrar:

- 3 historias de referencia elegidas y documentadas
- El equipo entiende la escala de tallas y su equivalencia en puntos
- Dudas y miedos sobre la estimación registrados para la retrospectiva

## Preparación

Hazla 2 o 3 días antes; la preselección de historias es lo que más tiempo toma.

**Participantes:** quienes votarán en el refinamiento (Data, Back, Front y QA) y el Product Owner. Tú facilitas y no votas. Idealmente entre 5 y 9 personas.

**Selección de historias en Azure DevOps:**

1. Filtra las Historias de usuario en estado Closed o Resolved de los últimos 2 o 3 sprints.
2. Elige entre 8 y 10 que la mayoría del equipo recuerde.
3. Busca variedad: muy pequeñas, medianas y grandes, y que en conjunto toquen Data, Back, Front y QA.
4. Evita historias atípicas: bloqueadas por terceros, con retrabajo por cambios de alcance o que nadie del equipo actual trabajó.

**Material:**

- Una tarjeta por historia: título y una línea de qué se hizo (físicas o en un pizarrón digital)
- Tres columnas o zonas rotuladas: Pequeña, Mediana, Grande
- La diapositiva 16 de la presentación (escala) visible
- Esta guía y la plantilla de registro (más abajo)

**Mensaje previo al equipo:** «Vamos a ordenar historias que ya terminamos para crear nuestra escala. No vamos a estimar nada nuevo ni hay respuestas incorrectas.»

## Agenda (60 minutos)

| Bloque | Minutos | Actividad | Resultado |
| --- | --- | --- | --- |
| 1. Apertura | 0–5 | Propósito, reglas y qué no es esta sesión | Equipo tranquilo y con contexto |
| 2. Repaso de la escala | 5–10 | Story Point = complejidad + incertidumbre + volumen; tallas XS a XL | Lenguaje común |
| 3. Ordenar historias | 10–30 | El equipo acomoda las 8–10 tarjetas de menor a mayor, sin números | Fila ordenada por tamaño |
| 4. Agrupar en tallas | 30–40 | Se marcan cortes entre XS, S, M, L y XL | Cada historia con su talla |
| 5. Elegir referencias | 40–50 | Se elige la S, la M y la L más representativas y se anota el porqué | 3 historias de referencia |
| 6. Prueba rápida | 50–55 | Se estima una historia del backlog contra las referencias | Primera práctica sin consecuencias |
| 7. Cierre | 55–60 | Dudas, sensaciones y siguientes pasos | Pendientes para la retro |

## Guion de facilitación

**1. Apertura (5 min)**

- «Hoy no vamos a estimar nada nuevo. Vamos a construir nuestra regla de medir con trabajo que ya terminamos.»
- Recuerda los acuerdos con la PMO: los puntos no evalúan a nadie, no se comparan equipos y no se convierten a horas.
- Reglas de hoy: todas las opiniones valen igual y no hay respuestas incorrectas.

**2. Repaso de la escala (5 min)**

- Muestra la diapositiva de la escala. Explica que una talla mide tamaño relativo, no tiempo.
- Pregunta clave para todo el ejercicio: «¿Esta historia es más grande o más chica que aquella?»

**3. Ordenar historias (20 min)**

- Pon la primera tarjeta al centro. Cada persona, por turnos, coloca una tarjeta a la izquierda (más chica) o a la derecha (más grande) y explica en una frase por qué.
- Cualquiera puede mover una tarjeta ya colocada, explicando su razón. Si una tarjeta se mueve más de dos veces, apártala y coméntala al final.
- Pide perspectivas cruzadas: «QA, ¿cómo fue probar esta?», «Data, ¿esta tuvo complejidad que no se vio?»
- Si alguien menciona horas o días, redirige: «¿Y comparada con esta otra, fue más o menos compleja?»

**4. Agrupar en tallas (10 min)**

- Con la fila ordenada, pregunta dónde están los cortes naturales entre tallas.
- No fuerces que todas las tallas tengan historias; es normal que XS o XL queden vacías.

**5. Elegir referencias (10 min)**

- En S, M y L, elige la historia que mejor represente la talla y que más personas conozcan.
- Anota en la plantilla por qué tiene ese tamaño, en palabras del equipo.

**6. Prueba rápida (5 min)**

- Toma una historia del backlog próximo. Cada quien vota su talla en secreto y se revela al mismo tiempo.
- Si hay diferencias, que expliquen los extremos. No importa si no se llega a acuerdo: es práctica.

**7. Cierre (5 min)**

- Ronda rápida: «En una palabra, ¿cómo te sentiste?»
- Anota dudas y miedos para revisarlos en la retrospectiva.
- Confirma que el próximo refinamiento ya usará las tallas.

## Plantilla de historias de referencia

Llénala durante el bloque 5 con las palabras del equipo. El ID es el número de la historia en Azure DevOps.

| Talla | Puntos | ID | Historia | Disciplinas involucradas | Por qué tiene este tamaño |
| --- | --- | --- | --- | --- | --- |
| S | 2 |  |  |  |  |
| M | 3 |  |  |  |  |
| L | 5 |  |  |  |  |

**Historias que generaron debate** (para la retro):

| Historia | Por qué no hubo acuerdo |
| --- | --- |
|  |  |

## Situaciones difíciles

| Situación | Cómo manejarla |
| --- | --- |
| «¿Para qué es esto? ¿Nos van a medir?» | Repite los acuerdos con la PMO y di que la velocidad es del equipo, nunca de una persona. |
| Alguien insiste en hablar de horas | Reconoce la duda y regresa a la comparación: «¿Más grande o más chica que esta?» |
| Una persona domina la conversación | Usa turnos y pide la opinión de quien no ha hablado, por nombre y con tono amable. |
| Una disciplina dice «mi parte fue fácil» | Recuerda que la talla es del trabajo completo, incluyendo Data, Back, Front y QA. |
| Nadie recuerda bien una historia | Retírala del ejercicio; no sirve como referencia. |
| El ordenamiento se atasca | Aparta la tarjeta, sigue con las demás y vuelve a ella al final. |
| Se acaba el tiempo | Prioriza elegir al menos la referencia M; las demás pueden cerrarse en el siguiente refinamiento. |

## Después de la sesión

Deja todo configurado antes del primer refinamiento con tallas.

- [ ] Etiquetar las 3 historias de referencia en Azure DevOps (por ejemplo, con el tag «referencia-S», «referencia-M», «referencia-L») para encontrarlas rápido
- [ ] Llenar el campo Story Points de esas historias con 2, 3 y 5
- [ ] Publicar la plantilla en la wiki del proyecto o fijarla en el canal del equipo
- [ ] Crear la query compartida «Historias sin estimar»: Work Item Type = User Story, Story Points vacío, Area Path del equipo
- [ ] Agregar a la Definition of Ready: «La historia tiene criterios de aceptación y Story Points»
- [ ] Agregar los widgets de Velocity y Sprint Burndown (por Story Points) al dashboard del equipo
- [ ] Llevar a la siguiente retrospectiva las dudas y las historias que generaron debate

Revisa las historias de referencia al cierre de la fase 1 (sprint 3): si el equipo ya no las recuerda o dejaron de ser representativas, cámbialas.
