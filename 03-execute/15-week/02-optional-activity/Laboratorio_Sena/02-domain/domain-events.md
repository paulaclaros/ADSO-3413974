# domain-events

> Estado: 🔴 | Última actualización: 2026-06-16
> Autor: Por definir | Equipo: Por definir

# Eventos del dominio

## Venta registrada

Cuando el cajero confirma una venta:
- Se guarda la información de la venta.
- Se descuenta el inventario.
- Se actualiza el historial.


## Producto actualizado

Cuando el administrador modifica un producto:
- Se actualiza la información.
- Se guarda el cambio.


## Stock mínimo alcanzado

Cuando un producto llega al límite:
- El sistema genera una alerta.


## Fiado registrado

Cuando se crea una cuenta por cobrar:
- Se guarda el cliente.
- Se registra la deuda.
- Se actualiza el inventario.