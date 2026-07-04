# entities-and-rules

> Estado: 🔴 | Última actualización: 2026-06-16
> Autor: Por definir | Equipo: Por definir

# Entidades y reglas del negocio

## Entidades principales

### Producto
Representa los artículos que vende el supermercado.

Atributos:
- id_producto
- nombre
- categoría
- precio
- cantidad disponible
- stock mínimo

Reglas:
- Un producto debe tener nombre, precio y cantidad.
- El inventario debe actualizarse después de una venta.
- Si la cantidad llega al mínimo debe generar una alerta.


### Cliente
Representa las personas que realizan compras.

Atributos:
- id_cliente
- nombre
- teléfono

Reglas:
- Un cliente puede tener cuentas por cobrar.
- La información del cliente debe estar registrada para crear un fiado.


### Venta
Representa una compra realizada por un cliente.

Atributos:
- id_venta
- fecha
- productos
- cantidad
- total

Reglas:
- Toda venta debe guardar fecha y valor total.
- Una venta debe descontar productos del inventario.


### Usuario
Representa las personas que usan el sistema.

Atributos:
- id_usuario
- nombre
- contraseña
- rol

Reglas:
- El administrador tiene acceso completo.
- El cajero tiene permisos limitados.


### Proveedor
Representa las personas o empresas que suministran productos.

Atributos:
- id_proveedor
- nombre
- contacto

Reglas:
- Los proveedores pueden tener pedidos registrados.


### Pedido
Representa solicitudes de productos a proveedores.

Atributos:
- id_pedido
- fecha
- proveedor
- estado

Reglas:
- Un pedido puede estar pendiente, recibido o cancelado.


### Fiado
Representa una compra pendiente de pago.

Atributos:
- id_fiado
- cliente
- fecha
- monto
- estado

Reglas:
- Debe tener un cliente asociado.
- Puede estar pendiente o pagado.
