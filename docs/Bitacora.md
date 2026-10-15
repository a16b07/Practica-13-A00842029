# Bitácora de Ejercicios · Práctica 13: Redacta

---

## Ejercicio 0 · ¿Nube o teléfono?

**Instrucción:**
Para cada app, decidan dónde correría el modelo y por qué:
- (a) Sugerir respuestas en un chat privado
- (b) Resumir un PDF de 80 páginas
- (c) Traducir carteles en un viaje sin datos
- (d) Un asistente que te dice si va a llover hoy

**Respuesta:**
- **(a) Teléfono:** Son conversaciones privadas y respuestas cortas, ideal para proteger la privacidad y responder rápido en un modelo chico.
- **(b) Nube:** 80 páginas equivalen a decenas de miles de tokens; en el teléfono tardaría minutos y un modelo de 1B perdería el hilo.
- **(c) Teléfono:** Sin datos móviles no hay acceso a la nube.
- **(d) Ninguno de los dos solo:** El modelo por sí mismo no conoce el clima actual; necesita datos de una API externa.

---

## Ejercicio B3 · ¿Qué tan rápido es tu teléfono?

**Instrucción:**
Con **Recado** y **Más amable**, anota en tu bitácora: los tokens por segundo, los tokens de la respuesta, y cuánto tardó en aparecer la primera palabra. Compáralo con la tabla del P0.1.

Ahora lee la respuesta completa. ¿Hizo lo que le pediste?

**Respuesta:**
- **Velocidad observada:** ~4 a 8 tokens/segundo (en emulador).
- **Tokens de la respuesta:** ~256 tokens.
- **Tiempo hasta la primera palabra:** ~1 a 2 segundos.
- **¿Hizo lo que le pediste?:** Si pero siento que mete mucho rollo, te da muchas opciones diferentes en vez de darte una concreta.
---

## Ejercicio C1 · ¿Por qué no obedeció?

**Instrucción:**
Prueben las tres tareas con su ejemplo (Recado → Más amable, Aviso → Más corto, Mensaje → 3 respuestas). Para cada respuesta, anoten qué sobra. Después, una hipótesis: ¿qué tendría que decir el pedido para que no sobre?



---

## Ejercicio C3 · El límite de un modelo de 1B

**Instrucción:**
Borra el texto y escribe: `Mañana no hay clase. No pregunten. Lo que falte lo ven en su casa y el lunes hay examen de todo.` Pídele **Más amable**. Lee la respuesta con cuidado: ¿dice lo mismo que el original? Después, con **Aviso** y **Más amable**, busca una frase que no venga del texto. ¿De dónde salió?


