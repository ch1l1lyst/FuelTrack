# FuelTrack
Sistema de monitoreo de combustible


⚙ Escenario real: Empresa de transporte de combustible

Supón que la empresa se llama FuelTrans Guayaquil S.A.
Tiene tres tipos de usuarios:

👨‍💼 Administrador

👷‍♂ Operador logístico

🚛 Conductor

🧩 Roles y flujo operativo
🧑‍💼 1. Administrador

Responsable: Gerente o jefe de operaciones.

Qué hace:

Crea usuarios (conductores, operadores).

Revisa reportes generales: entregas, ingresos, pagos pendientes.

Autoriza pagos y verifica documentación (facturas, comprobantes).

Supervisa los estados de entrega.

En la página:

Tiene acceso total.

Puede ver todos los viajes, modificarlos o eliminarlos.

En el dashboard ve KPIs como:

Total galones transportados esta semana.

Porcentaje de entregas cumplidas a tiempo.

Total facturado vs pendiente.

👉 Ejemplo real:
El lunes, el administrador revisa el sistema y ve:

“3 entregas completadas ayer, 2 en ruta y 1 pendiente de pago”.

Decide contactar al cliente del viaje pendiente para solicitar la factura.

👷‍♂ 2. Operador logístico

Responsable: Persona de oficina o despacho que coordina los viajes.

Qué hace:

Registra los pedidos que llegan de los clientes.

Asigna un tanquero y conductor.

Actualiza el estado del viaje (“En ruta”, “Entregado”).

Carga la información del comprobante y el pago cuando el cliente paga.

En la página:

Llena el formulario con los datos del viaje:

Fecha de solicitud

Cliente

Tipo y cantidad de combustible

Tanquero

Conductor

Estado actual

Comprobante y observaciones

👉 Ejemplo real:
El operador recibe una llamada de la empresa “PetroMar”.
Registra un pedido:

4,000 galones de Av-Gas, entrega el 14/11/2025, tanquero TQ-03, conductor Luis Salazar.
Luego marca el estado como “Programado”.
Cuando Luis confirma la entrega, cambia a “Entregado” y adjunta el comprobante firmado.

🚛 3. Conductor

Responsable: Persona que transporta el combustible.

Qué hace:

Consulta sus viajes asignados (desde móvil o tablet).

Marca el inicio de viaje o entrega completada.

(Opcional) Sube foto del comprobante o firma del cliente al entregar.

En la página:

Solo puede ver los viajes asignados a su ID.

No puede editar ni eliminar datos financieros.

👉 Ejemplo real:
Luis entra a la app y ve:

“Viaje #1456 — Cliente: PetroMar — Estado: En ruta”.
Cuando entrega el combustible, cambia el estado a “Entregado” y sube una foto del comprobante.

