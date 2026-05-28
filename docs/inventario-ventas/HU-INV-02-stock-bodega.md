# HU-INV-02: Consultar stock por bodega

### Historia de Usuario
Como administrador de inventario, quiero consultar el stock disponible por bodega, para conocer la disponibilidad real de los productos.

### Criterios de Aceptación
- El sistema debe mostrar el stock total por cada producto consultado.
- El sistema debe desplegar el stock separado por bodega física de forma clara.
- El inventario disponible debe actualizarse de forma automática inmediatamente después de registrarse cualquier transacción de entrada o salida.
- El sistema debe emitir una notificación o alerta visual restrictiva cuando los niveles caigan por debajo del stock mínimo parametrizado.

### Atributos de Calidad Relacionados (ISO/IEC 25010)
- **Eficiencia de Rendimiento:** El tiempo de respuesta al consultar el stock por bodega en tiempo real debe ser inferior a 2 segundos para asegurar la agilidad de los despachos.
- **Fiabilidad (Tolerancia a fallos):** Integridad total de los datos consolidados entre movimientos físicos y la base de datos centralizada.
