# Sprint 1 – Planificación

## Duración
2 semanas

## Historias Seleccionadas

1. Registrar productos (5 puntos)
2. Registrar proveedores (3 puntos)
3. Generar factura de venta (8 puntos)
4. Validar stock antes de vender (5 puntos)

Total Story Points: 21

## Historia 1

Como administrador,
quiero registrar nuevos productos,
para poder gestionar el inventario correctamente.

### Criterios de Aceptación

1. Dado que el administrador ingresa datos válidos,
   cuando guarda el producto,
   entonces el sistema lo almacena correctamente.

2. Dado que falta un campo obligatorio,
   cuando intenta guardar,
   entonces el sistema muestra mensaje de error.

3. Dado que el código del producto ya existe,
   cuando intenta registrarlo,
   entonces el sistema rechaza el registro.

4. Dado que el producto es guardado,
   cuando se consulta la lista,
   entonces debe aparecer en el inventario.

5. Dado que el precio es inválido,
   cuando intenta guardarlo,
   entonces el sistema valida el formato.
