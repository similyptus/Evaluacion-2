# HU-INV-04: Gestionar niveles de stock y alertas críticas

### Historia de Usuario
Como administrador de compras, quiero definir parámetros de stock mínimo y máximo por producto, para recibir alertas automáticas antes de quedar sin existencias.

### Criterios de Aceptación
- El sistema debe permitir ingresar valores numéricos para stock mínimo, máximo y punto de reposición por cada bodega.
- Se debe desplegar un panel visual de criticidad (Semáforo: Rojo para quiebre, Amarillo para reposición, Verde para óptimo).
- El sistema debe bloquear la creación de notas de venta si el producto está en stock cero o quiebre absoluto.

### Atributos de Calidad Relacionados (ISO/IEC 25010)
- **Fiabilidad (Tolerancia a fallos):** Garantiza que la operación comercial nacional de Seguridad LTDA no sufra interrupciones por falta de insumos.
- **Usabilidad:** Alertas visuales intuitivas que facilitan la toma de decisiones al equipo de adquisiciones.
