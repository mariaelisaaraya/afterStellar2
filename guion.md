# Guion — ¿Para qué Stellar?

23 slides, uno a uno, en el mismo orden que `ppt1.html` / `ppt2.html`. Duración total ~65 min.

---

## Slide 1 — Título

**Tiempo:** 0 min (solo visual, no leer nada)

---

## Slide 2 — ¿Quién soy?

**Tiempo:** 2 min

Buenas noches, gente. Antes de arrancar, un repaso rápido de quién les habla, aunque ya me conozcan de otras clases.

Soy Eli. Vengo de Ethereum, trabajo con Solidity y seguridad de smart contracts en una empresa de Canadá, y también construyo productos Web2, sobre todo educativos, para una empresa en Argentina que trabaja con toda Latinoamérica y parte de Europa.

Desde el año pasado me metí fuerte en Stellar. Gané varias hackathons a lo largo del 2025, y este año mi foco fue construir productos.

Soy fundadora de Buen Día Builders, y tengo un podcast llamado Agarrá una Silla y Vení.

Bueno, ahora sí, vamos a lo de hoy.

---

## Slide 3 — Si le saco Stellar, ¿deja de funcionar? / "No."

**Tiempo:** 4 min

Hoy quiero arrancar con algo medio raro. No con una definición de Stellar. No con una slide de "qué es blockchain". No vamos a hacer eso.

Quiero arrancar con una pregunta que me hice yo misma ayer, revisando proyectos con ustedes.

La pregunta fue: si yo agarro este proyecto y le saco Stellar, ¿deja de funcionar?

[Pausa]

Y en varios casos, la respuesta honesta era: no. Seguía funcionando exactamente igual.

Y ojo: esto no significa que el proyecto esté mal. Es algo que pasa muchísimo cuando uno empieza a construir sobre una blockchain. Primero aparece la idea: "quiero hacer esto." Después armamos la pantalla. Después conectamos alguna cosa. Y en algún momento aparece: "ah, cierto, tenemos que usar Stellar." Entonces Stellar queda medio pegado arriba, como una capa.

Y ahí es donde aparece el problema que quiero que resolvamos hoy. Porque mañana no quiero que el jurado les pregunte "¿y por qué Stellar?" y ustedes tengan que improvisar. Quiero que esa pregunta ya se la hayan hecho ustedes hoy.

---

## Slide 4 — ¿Qué cambia en tu producto porque existe Stellar?

**Tiempo:** 10 min

Vamos a hacer un ejercicio. Quiero que cada equipo piense en su proyecto. Y no me digan todavía qué tecnología usan. No quiero escuchar "usamos Soroban", "tenemos smart contracts", "porque Stellar es rápida". Eso viene después.

Quiero saber: ¿qué cambia en su producto porque existe Stellar?

[Pausa]

No me digan qué hace Stellar. Díganme qué puede hacer su producto gracias a Stellar que de otra manera sería distinto, más difícil, o directamente no tendría sentido hacerlo de la misma forma.

Pregunta al equipo: ¿qué pasaría si mañana les saco Stellar? Y ustedes me dicen: "bueno, podría seguir funcionando, pero…" Perfecto. Ese "pero" es donde quiero entrar.

¿Qué perdemos? ¿Una propiedad del producto? ¿Una forma de pagar? ¿Una forma de verificar algo? ¿Una interacción entre usuarios? ¿Una propiedad de los datos? ¿Una posibilidad de que dos partes que no confían entre sí hagan algo? ¿Una forma de mover valor?

Ahí empieza a aparecer la respuesta.

---

## Slide 5 — "Porque usamos blockchain." No alcanza.

**Tiempo:** 5 min

Yo pregunto "¿por qué Stellar?" y me responden "porque usamos blockchain." No. Eso no responde la pregunta.

Es como si yo te preguntara "¿por qué usás una base de datos?" y me dijeras "porque tenemos datos." Bueno… sí.

[Pausa]

Pero contame qué problema estás resolviendo con eso. Con Stellar pasa lo mismo. "Usamos smart contracts" tampoco responde. Porque la pregunta siguiente sería: ¿y para qué? ¿Qué hace ese smart contract? ¿Qué regla está ejecutando? ¿Qué cosa necesitás que ocurra de manera verificable? ¿Qué cambia para el usuario? Eso es lo que me interesa.

---

## Slide 6 — Completá la frase

**Tiempo:** 2 min

Quiero que cada equipo complete mentalmente esta frase: "Nuestro proyecto necesita Stellar porque ______."

No pueden poner "blockchain". Tampoco "smart contracts". Tampoco "descentralización" si después no me pueden explicar qué cambia gracias a eso.

[Pausa] ¿Qué pusieron?

*(Nota: acá ya no está la slide del "test de sacar Stellar" — la sacamos porque repetía la misma idea de la slide 3. Si querés retomar el gancho antes de pasar a la transacción, podés decir de memoria, sin slide: "Y este mismo test — sacale Stellar mentalmente al proyecto — es el que le vamos a aplicar ahora a la demo.")*

---

## Slide 7 — "Transaction successful."

**Tiempo:** 6 min

Segundo ejercicio. Este lo aprendí mirando demos, no solamente las de ustedes, de un montón.

Cuando algo cuesta mucho conectar (una wallet, una firma, una transacción real) pasa algo completamente lógico: lo simulamos. Ponemos un botón, el usuario hace click, aparece "transaction successful", y listo.

[Pausa]

Funciona perfecto. En el frontend.

---

## Slide 8 — Se ven exactamente iguales en pantalla

**Tiempo:** 4 min

El problema es que una transacción simulada y una transacción real pueden verse exactamente iguales en pantalla. Ese es el problema. Porque yo puedo mirar la pantalla y pensar "ah, perfecto, pagó". Pero… ¿pagó de verdad?

---

## Slide 9 — "¿Dónde?"

**Tiempo:** 2 min

Si ustedes me dicen "acá el usuario paga", yo les voy a preguntar "¿dónde?" Y quiero que puedan mostrarme. No solamente el mensaje verde del frontend. Quiero poder abrir el explorador. Quiero ver la cuenta. Quiero ver la transacción. Quiero ver que eso ocurrió realmente.

---

## Slide 10 — "Dice que pasó" ≠ "Puedo verificar que pasó"

**Tiempo:** 3 min

Porque ahí hay una diferencia enorme entre "mi aplicación dice que pasó" y "puedo verificar que pasó". Y esto no es para complicarles la vida, es justamente lo contrario: porque si funciona de verdad, demuéstrenlo. No necesito que me lo expliquen durante cinco minutos. Abrimos Stellar Expert, buscamos, y listo.

---

## Slide 11 — ¿Qué funciona de verdad y qué todavía no?

**Tiempo:** 2 min

Con las wallets pasa exactamente lo mismo. Si tienen una wallet conectada de verdad, perfecto. Si todavía está simulada, también está bien. Pero sepan qué está simulado.

---

## Slide 12 — "No necesito una demo perfecta"

**Tiempo:** 3 min

Porque mañana no quiero que una demo parezca que hace algo que en realidad todavía no hace. Eso es lo que quiero evitar. No necesito una demo perfecta. Necesito saber qué funciona de verdad y qué todavía no. Porque eso me permite evaluar el producto que construyeron, no una ilusión del producto.

---

## Slide 13 — Ensayo, no examen

**Tiempo:** 1 min

Ahora les toca a ustedes. Esto es un ensayo, no un examen. Así que voy a hacerles preguntas. Y si no saben responder, mejor: encontramos algo para trabajar.

---

## Slide 14 — Pregunta 1/5

**Tiempo:** 1.5 min

En una frase: ¿qué hace su proyecto? Una frase. No me cuenten la arquitectura. No me cuenten cómo lo programaron. ¿Qué hace?

---

## Slide 15 — Pregunta 2/5

**Tiempo:** 1.5 min

¿Quién tiene el problema que están resolviendo? No "los usuarios". ¿Quién? Una persona, una empresa, un productor, un desarrollador. ¿Quién?

---

## Slide 16 — Pregunta 3/5

**Tiempo:** 1.5 min

¿Qué cambia gracias a Stellar? Esta es la importante. Y recuerden: no vale responder "porque usamos blockchain".

---

## Slide 17 — Pregunta 4/5

**Tiempo:** 1.5 min

¿Qué parte de su proyecto ocurre realmente on-chain? Muéstrenme. ¿Qué cuenta? ¿Qué transacción? ¿Qué contrato? ¿Qué dato?

---

## Slide 18 — Pregunta 5/5

**Tiempo:** 1.5 min

¿Qué parte todavía está simulada? Acá no quiero que escondan nada. Si algo está mockeado, díganme que está mockeado. No pasa nada. Lo que sí pasa es que tenemos que saberlo.

*(Nota: la pregunta que sacamos, "si te dicen sacale Stellar, ¿qué se rompe?", quedá tuya para el cierre si algún equipo se queda corto de respuesta — no hace falta decirla a todos, solo si hace falta destrabar a alguien.)*

---

## Slide 19 — Checkpoint #2

**Tiempo:** 3 min

Che, un cambio de tema. Esto ya no es conceptual, es agenda pura, así que se los tiro rápido y seguimos.

Mañana jueves es Checkpoint #2. Tres cosas van a pasar: feature freeze, deploy en testnet, y guion de pitch.

Feature freeze quiere decir esto: a partir de mañana, dejan de sumar funcionalidades nuevas. La pregunta ya no es "¿qué más le agrego?". Es "¿lo que tengo, funciona y lo puedo mostrar?"

[Pausa]

Si tenían pensado meter algo grande esta semana, háganse esta pregunta ahora, no mañana a la mañana: ¿es indispensable para demostrar lo que hoy trabajamos, el "para qué Stellar", o es roadmap? Si es roadmap, no lo tocan. Lo anotan como próximo paso y siguen.

---

## Slide 20 — El README, en orden

**Tiempo:** 4 min

Segunda cosa: el README. El orden que tiene que tener:

1. Problema.
2. Solución.
3. Flujo de uso, paso a paso.
4. Por qué Stellar: la respuesta que armamos hoy.
5. Stack técnico. Al final, no arriba.

Si el proyecto es non-custodial, dígalo explícito ahí. No dejen que se confunda con "privado".

Y la demo: lo que ensayamos hoy. Se muestra la transacción real, no el mensaje verde del frontend.

---

## Slide 21 — Lo que viene

**Tiempo:** 3 min

Últimas fechas, para que tengan el mapa completo:

- Jueves 24/09 → Checkpoint #2.
- Domingo 27/09, 23:59 → cierre de submission final.
- 28/09 al 1/10 → evaluación del jurado.
- Viernes 2/10, 17:00 → anuncio de resultados en vivo.

Eso es todo lo administrativo. Ahora sí, volvemos a lo importante.

---

## Slide 22 — Si saco Stellar, ¿qué pierdo?

**Tiempo:** 2 min

Con esto quiero que se queden hoy. No necesito que esta noche reescriban todo el proyecto. No necesito que agreguen cinco smart contracts porque sí. Y definitivamente no quiero que se pongan a programar desesperados solamente porque mañana hay demo.

Primero piensen. Miren el proyecto. Y háganse estas preguntas: ¿qué problema estamos resolviendo? ¿Qué cambia gracias a Stellar? ¿Qué parte funciona realmente? ¿Qué parte todavía estamos simulando?

Y sobre todo: si saco Stellar, ¿qué pierdo?

Si la respuesta es "todo esto deja de funcionar porque necesitamos esta propiedad concreta", perfecto, tenemos algo. Si la respuesta es "y… en realidad podría funcionar igual", también perfecto, porque lo descubrimos hoy. Y eso se puede arreglar pensando. No necesariamente programando.

---

## Slide 23 — "Vení, mostrame qué construiste"

**Tiempo:** 1 min

Así que nada. Agarran su proyecto, se sientan con su equipo y hacemos una última pasada. Vení, mostrame qué construiste. Y vemos juntos dónde está Stellar de verdad.
