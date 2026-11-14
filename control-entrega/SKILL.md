---
name: control-entrega
description: >
  Úsala antes de que algo llegue a un cliente o a otra persona: «revisa esto
  antes de enviarlo», «¿está listo para entregar?», «control de calidad», «voy a
  mandarle el informe», «última revisión». También cuando hay que revisar como
  una sola entrega varias piezas hechas por separado. Recorre seis bloques de
  comprobación y termina con un veredicto explícito.
license: MIT
metadata:
  author: Joan Medina (https://joanmedina.es)
  version: "1.0.0"
---

# Control de entrega

**Nada llega al cliente sin pasar por aquí.**

Cada pieza de trabajo suele tener su propia revisión: quien escribe el texto lo
relee, quien monta la web la prueba. Eso verifica que cada pieza está bien **por
dentro**. Esta skill verifica lo que ninguna revisión parcial puede ver: que el
conjunto es coherente, que responde a lo que se pidió y que no deja al cliente
peor de lo que estaba.

Sirve para cualquier entregable: un informe, una propuesta, una web, una
campaña, un correo importante. Si no hay carpeta de proyecto, entrega la lista
de comprobación en la conversación.

## Entregable

`cliente/03-control-entrega-<fecha>.md`: corto. Es una lista de comprobación con
veredicto, no un informe.

## Bloque 1: ¿Responde a lo que se pidió?

- [ ] ¿Esto resuelve la petición original o resuelve lo que era cómodo hacer?
- [ ] ¿Está dentro del alcance acordado? Si se ha ampliado, ¿está registrado?
- [ ] ¿Falta algo que se prometió? Si falta, ¿está dicho por qué?
- [ ] ¿Hay algo entregado que **no** se pidió? No siempre es bueno: puede leerse como desvío o como factura futura.

## Bloque 2: ¿Es verdad?

El bloque más importante:

- [ ] **Cero datos inventados.** Cifras, nombres, testimonios, casos y logos: todos verificados contra fuente del cliente.
- [ ] Cada afirmación relevante lleva su fuente. Lo no verificado va marcado `(por confirmar)` o `(estimación)`.
- [ ] Las estimaciones muestran la aritmética y usan el extremo conservador.
- [ ] Ningún resultado se presenta como causal si no vino de un test controlado.
- [ ] Lo no concluyente está declarado como no concluyente.
- [ ] Los huecos de datos están **declarados, no rellenados**.

Una cifra inventada descubierta por el cliente cuesta más que todo el proyecto.

## Bloque 3: coherencia entre piezas

Lo que ninguna revisión individual puede ver:

- [ ] ¿El texto de la web, el de los anuncios y el de los correos **dicen lo mismo**? Tres personas (o tres herramientas) escribiendo por separado producen tres propuestas de valor distintas.
- [ ] ¿La promesa del anuncio se cumple en la página a la que lleva?
- [ ] ¿El recurso descargable promete lo que entregan los correos que vienen después?
- [ ] ¿Los indicadores de un informe y los de otro cuadran, o al menos está explicado por qué no?
- [ ] ¿El nivel de consciencia del tráfico casa con el de la página de destino?
- [ ] ¿Se está usando la marca correcta: colores, logo, tono, nombres?

## Bloque 4: ¿Se puede medir?

- [ ] ¿Hay una métrica definida para saber si esto ha funcionado?
- [ ] ¿Esa métrica se puede medir **hoy**? Si no, ¿hay tarea creada?
- [ ] ¿Está registrada la fecha del cambio para poder comparar antes y después?
- [ ] Si se ha tocado la web, ¿sigue funcionando la medición? (los rediseños rompen la analítica en silencio)

## Bloque 5: ¿Está listo para un humano?

- [ ] ¿Se entiende sin conocer la jerga? Un cliente que no entiende el entregable no lo aprueba, lo pospone.
- [ ] ¿Empieza por la conclusión o por la metodología? Debe empezar por la conclusión.
- [ ] ¿Hay una acción clara para el cliente, con fecha?
- [ ] ¿Está en español correcto, sin errores, sin restos de plantilla ni marcadores `<placeholder>`?
- [ ] ¿Los enlaces funcionan? ¿Los archivos abren?
- [ ] ¿Las malas noticias están en la primera página, no escondidas?

## Bloque 6: ¿Y después?

Lo que separa entregar de terminar:

- [ ] ¿Quién implementa esto y cuándo?
- [ ] Si lo implementa el cliente, ¿tiene instrucciones suficientes para hacerlo solo?
- [ ] ¿Cuándo se revisa si se implementó de verdad?
- [ ] ¿Cuándo se mide el resultado?
- [ ] ¿Queda algo que mantener, y sabe el cliente cómo? (correos automáticos, campañas, medición)

Un entregable aprobado que nadie implementa no ha producido nada, y a los tres
meses el cliente recordará que pagó por algo que «no sirvió».

## Veredicto

Uno de tres, explícito:

| Veredicto | Significa |
|---|---|
| **Listo** | Se envía |
| **Listo con salvedades** | Se envía **diciendo** las salvedades, no callándolas |
| **No listo** | Qué falta y cuánto se tarda |

Nunca enviar con salvedades sin nombrarlas. El cliente las encontrará, y entonces
el problema deja de ser el entregable y pasa a ser la confianza.

## Cuándo está terminado

1. Los seis bloques recorridos, no en prosa sino punto por punto.
2. Cero datos sin verificar en lo que sale.
3. La coherencia entre piezas comprobada explícitamente.
4. Hay métrica y fecha de revisión definidas.
5. Está claro quién implementa y cuándo se comprueba.
6. Veredicto explícito, y las salvedades comunicadas si las hay.
