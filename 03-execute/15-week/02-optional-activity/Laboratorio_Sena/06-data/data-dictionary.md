# data-dictionary

> Estado: 🔴 | Última actualización: 2026-06-16
> Autor: Por definir | Equipo: Por definir

# Diccionario de datos

## Tabla: Producto

| Campo        | Tipo   | Descripción                |
|---           |---     |---                         |
| id_producto  | Entero | Identificador del producto |
| nombre       | Texto  | Nombre del producto        |
| categoria    | Texto  | Tipo de producto           |
| precio       | Decimal| Valor de venta             |
| cantidad     | Entero | Cantidad disponible        |
| stock_minimo | Entero | Cantidad mínima permitida  |


## Tabla: Cliente

| Campo      | Tipo  | Descripción               |
|---         |---    |---                        |
| id_cliente | Entero| Identificador del cliente |
| nombre     | Texto | Nombre del cliente        |
| telefono   | Texto | Número de contacto        |


## Tabla: Venta

| Campo      |   Tipo  | Descripción                  |
|    ---     |   ---   |        ---                   |
| id_venta   | Entero  | Identificador de venta       |
| fecha      | Fecha   | Fecha de realización         |
| total      | Decimal | Valor total de la venta      |
| id_usuario | Entero  | Usuario que realizó la venta |


## Tabla: Usuario

| Campo      | Tipo  | Descripción               |
|---         |---    |---                        |
| id_usuario | Entero| Identificador del usuario |
| nombre     | Texto | Nombre del usuario        |
| contraseña | Texto | Clave de acceso           |
| rol        | Texto | Administrador o cajero    |


## Tabla: Fiado

| Campo      | Tipo   | Descripción             |
|---         |---     |---                      | 
| id_fiado   | Entero | Identificador del fiado |
| id_cliente | Entero | Cliente asociado        |
| fecha      | Fecha  | Fecha del registro      |
| monto      | Decimal| Valor pendiente         |
| estado     | Texto  | Pendiente o pagado      |