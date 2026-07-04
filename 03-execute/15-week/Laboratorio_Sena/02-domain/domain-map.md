# domain-map

> Estado: 🔴 | Última actualización: 2026-06-16
> Autor: Por definir | Equipo: Por definir

# Mapa del dominio

El sistema del Supermercado La Esquina está compuesto por las siguientes áreas:

## Ventas
Permite registrar compras realizadas por los clientes y actualizar inventario.

## Inventario
Controla los productos disponibles, cantidades y alertas de stock.

## Clientes
Administra la información de los clientes y sus cuentas pendientes.

## Proveedores
Permite registrar pedidos y seguimiento de productos solicitados.

## Usuarios
Gestiona los permisos de administrador y cajero.

Relaciones:

Cliente → realiza → Venta

Venta → contiene → Productos

Producto → pertenece a → Inventario

Proveedor → recibe → Pedido

Cliente → tiene → Fiado