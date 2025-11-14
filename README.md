# FuelTrack  
**Sistema de monitoreo y control de transporte de combustible**

---

## ⚙ Escenario Real  
**Empresa objetivo:** *FuelTrans Guayaquil S.A.*  
**Sector:** Transporte y distribución de combustibles.  

El sistema opera con tres roles principales:  
- 👨‍💼 **Administrador**  
- 👷‍♂ **Operador Logístico**  
- 🚛 **Conductor**

Cada rol ejecuta acciones específicas dentro del flujo operativo.

---

## 🧩 Roles y Flujo Operativo

---

## 👨‍💼 1. Administrador  
**Responsable:** Gerente o Jefe de Operaciones  
**Acceso:** Total

### Funciones principales
- Crear usuarios (conductores y operadores).  
- Supervisar reportes globales:  
  - Entregas completadas  
  - Ingresos generados  
  - Pagos pendientes  
- Autorizar pagos y validar documentación (facturas, comprobantes).  
- Control total sobre todos los viajes (visualizar, modificar, eliminar).  
- Supervisar estados de entrega en tiempo real.

### Dashboard del Administrador
Incluye KPIs estratégicos:
- Total de galones transportados esta semana.  
- Porcentaje de entregas cumplidas a tiempo.  
- Total facturado vs total pendiente de cobro.  

### Ejemplo real
El lunes, el administrador revisa el sistema y ve:  
- “3 entregas completadas ayer”  
- “2 viajes en ruta”  
- “1 viaje pendiente de pago”  

Acción inmediata: contacta al cliente del viaje pendiente para solicitar el comprobante o factura.

---

## 👷‍♂ 2. Operador Logístico  
**Responsable:** Personal de oficina o despacho  
**Acceso:** Gestión operativa completa (solo sus operaciones)

### Funciones principales
- Registrar pedidos de clientes.  
- Asignar tanquero y conductor.  
- Actualizar estados del viaje:  
  - *Programado*  
  - *En ruta*  
  - *Entregado*  
- Subir comprobantes (firma del cliente, documentos de entrega).  
- Registrar información de pago cuando el cliente realiza la transferencia.

### Formulario de registro del viaje
- Fecha de solicitud  
- Cliente  
- Tipo de combustible  
- Cantidad (galones)  
- Tanquero asignado  
- Conductor asignado  
- Estado actual  
- Comprobante (PDF/JPG)  
- Observaciones internas

### Ejemplo real
El operador recibe un pedido de *PetroMar*.  
Registra lo siguiente:

- 4,000 galones de Av-Gas  
- Entrega: **14/11/2025**  
- Tanquero: **TQ-03**  
- Conductor: **Luis Salazar**  
- Estado inicial: *Programado*

Más tarde, al confirmarse la entrega, actualiza el estado a *Entregado* y adjunta el comprobante firmado.

---

## 🚛 3. Conductor  
**Responsable:** Transportista asignado  
**Acceso:** Viajes individuales asignados a su ID

### Funciones principales
- Consultar viajes programados desde móvil o tablet.  
- Marcar “Inicio de viaje” y “Entrega completada”.  
- (Opcional) Subir foto del comprobante o firma del cliente.  
- No puede modificar datos financieros.

### Pantalla del conductor
Solo ve viajes asignados. Para cada viaje:
- Cliente  
- Fecha  
- Tipo de combustible  
- Cantidad  
- Estado actual  
- Ubicación de entrega (si aplica)

### Ejemplo real
Luis ingresa a la app y visualiza:

**Viaje #1456 – Cliente: PetroMar – Estado: En ruta**

Tras entregar el combustible:
- Cambia el estado a *Entregado*.  
- Sube fotografía del comprobante.

