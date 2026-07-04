# models

> Estado: 🔴 | Última actualización: 2026-06-16
> Autor: Por definir | Equipo: Por definir

# Modelo de datos

## Relaciones principales

### Producto - Venta

Un producto puede aparecer en varias ventas.

Relación:
Producto 1 ---- N Venta


### Cliente - Fiado

Un cliente puede tener varias cuentas pendientes.

Relación:
Cliente 1 ---- N Fiado


### Usuario - Venta

Un usuario puede registrar muchas ventas.

Relación:
Usuario 1 ---- N Venta


### Proveedor - Pedido

Un proveedor puede recibir varios pedidos.

Relación:
Proveedor 1 ---- N Pedido