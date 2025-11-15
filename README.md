Análisis de Resultados
Completa esta tabla después de ejecutar npm test:

| Formato | Tamaño Promedio | Observaciones |
|---------|-----------------|---------------|
| JSON    |  66 bytes          | Más legible pero más pesado por incluir nombres de campos en texto.|
| Protobuf|  35 bytes          | Más compacto y eficiente gracias a la codificación binaria y esquema fijo.|

Preguntas
¿Cuál formato es más compacto? ¿Por cuánto?

El protobuf es el formato mas compacto, por un 46.97% a diferencia del json

¿Por qué Protobuf es más pequeño que JSON?

Porque usa binario, identificadores numéricos y un esquema fijo, evitando nombres de campos y texto innecesario.


¿Cuándo usarías JSON?

Cuando necesitas legibilidad, compatibilidad universal y trabajar con APIs simples o abiertas.

¿Cuándo usarías Protobuf?

Cuando se trata de buscar máxima eficiencia, velocidad, bajo tamaño y trabajar con gRPC o microservicios internos.