# overview

> Estado: 🔴 | Última actualización: 2026-06-16
> Autor: Por definir | Equipo: Por definir

# Overview de Arquitectura

## Descripción

El sistema de gestión del Supermercado La Esquina será una aplicación web diseñada para controlar los procesos principales del negocio como ventas, inventario, clientes, fiados y pedidos a proveedores.

## Arquitectura general

El sistema estará organizado en capas:

### Capa de presentación

Permite la interacción del usuario con el sistema.

Usuarios:
- Administrador
- Cajero

Funciones:
- Registrar ventas.
- Consultar productos.
- Gestionar información.


### Capa de lógica de negocio

Procesa las operaciones del sistema.

Funciones:
- Validar usuarios.
- Calcular ventas.
- Actualizar inventario.
- Controlar fiados.


### Capa de datos

Almacena la información del sistema.

Datos:
- Productos.
- Ventas.
- Clientes.
- Usuarios.
- Pedidos.
- Fiados.