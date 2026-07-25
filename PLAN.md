# Automatiza — Marketplace de automatización con IA para PyMEs

## La idea
Conectar dos lados:
- **Oferta**: freelancers/consultores que saben armar automatizaciones (chatbots de WhatsApp, integraciones, workflows con IA) y buscan clientes.
- **Demanda**: PyMEs que quieren digitalizar tareas repetitivas pero no saben qué es posible, ni a quién contratar, ni cuánto cuesta.

## Por qué es más difícil que Shiplog
Shiplog resuelve un dolor que el usuario ya sabe que tiene ("necesito un changelog"). Acá el problema es de **educación de mercado**: la mayoría de las PyMEs no saben que pueden automatizar X hasta que alguien se los muestra. Eso hace que la demanda no llegue sola por SEO/orgánico como en Shiplog — necesita más empuje activo al principio.

## Estrategia: no construir el marketplace todavía
Construir un marketplace completo (perfiles, matching, pagos, reviews) antes de saber si hay oferta y demanda real es la forma clásica de perder meses de trabajo en algo que nadie usa. La estrategia correcta es un **smoke test**:

1. Landing de una página, dos mensajes (uno para cada lado), cada uno con una forma de dejar sus datos (hoy: email).
2. Si freelancers escriben pidiendo sumarse Y PyMEs escriben pidiendo ayuda → hay señal, vale la pena construir el matching real.
3. Si no escribe nadie de ningún lado → se descarta rápido, sin haber perdido semanas de desarrollo.
4. Mientras no haya volumen, el "matching" se hace a mano (yo/vos conectando por email a la PyME con el freelancer que mejor encaje) — no hace falta plataforma para las primeras 5-10 conexiones.

## Lo que construí ahora
Landing en `index.html`, deployada, con dos formularios de interés (mailto, sin necesitar backend/cuenta nueva).

## Lo que necesito de vos (acá sí es central, no opcional)
A diferencia de Shiplog, este modelo depende mucho más de tu red de contactos:
- ¿Conocés 2-3 freelancers/devs que hagan este tipo de trabajo (automatizaciones, chatbots, integraciones)? Son el "lado oferta" inicial.
- ¿Conocés 2-3 dueños de PyMEs que se quejen de tareas repetitivas/manuales en su negocio? Son el "lado demanda" inicial.
- Sin esas ~5 conversaciones iniciales, no hay forma de validar esto — ninguna cantidad de código lo reemplaza.

## Presupuesto
Igual que Shiplog: prácticamente $0 para el smoke test (dominio opcional, todo lo demás gratis). Si valida, ahí sí conviene invertir en plataforma real + algo de paid ads para escalar la demanda.
