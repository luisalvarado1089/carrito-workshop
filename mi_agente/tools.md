<!--
✏️ PASO 2 · Las descripciones de tus tools.

El modelo lee estas descripciones en cada llamada: también son contexto.
Para cada tool, escribe en 2–4 frases:
- qué hace;
- cuándo usarla y cuándo NO;
- qué significan sus argumentos (unidades);uv run carrito agente --debug
- qué significa su resultado (también los errores).

No cambies los títulos "## nombre_de_la_tool".
-->

## search_products
Busca producto en el catalogo de la tienda,
los max_price se encuentra en centimos
Si te preguntan informacíon por algun producto, utiliza la herramienta search_products solicitando de antemano la descriptción del producto y el precio.

## get_order
si te pregunta información por un pedido utiliza la herramienta get_order, solicita previamente el ID de la orden

## search_policies
Si te preguntan por las politicas de devolucion y compra utiliza la herramienta search_policies

## request_return
Si te piden ayuda para realizar una devolución utiliza la herramienta request_return y requiere previamiente el id de la orden de compra (ejemplo: factura), y ademas solicita el motivo de la devolución
