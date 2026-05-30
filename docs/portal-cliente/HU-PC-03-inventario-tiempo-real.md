# HU-PC-03 Consultar inventario en tiempo real

**Historia de Usuario**
Como cliente, quiero consultar la disponibilidad de productos en tiempo real, para saber si un producto está disponible antes de comprar.

**Descripción funcional**
Sistema de sincronización que conecta el Front-Office con el módulo interno de Bodega/Inventario. Evalúa el stock exacto al momento de la consulta del cliente y muestra indicadores visuales de disponibilidad para evitar quiebres de stock en la venta.

**Criterios de aceptación**
- El sistema debe mostrar disponibilidad actual del producto.
- El sistema debe actualizar la disponibilidad según el stock.
- El sistema debe indicar si el producto está disponible, bajo stock o agotado.
- El sistema debe evitar mostrar como disponible un producto sin stock.

**Atributos de calidad relacionados**
- **Interoperabilidad:** Comunicación constante y fluida con el módulo de Inventario manejado por Juan.
- **Confiabilidad:** Exactitud crítica en los datos de stock mostrados al cliente.
