# Plan de Pruebas – Sprint 1

## Historia: Registrar Productos

| Caso | Entrada | Resultado Esperado |
|------|---------|-------------------|
| 1 | Datos correctos | Producto guardado correctamente |
| 2 | Campo vacío | Mensaje de error |
| 3 | Código duplicado | Registro rechazado |
| 4 | Precio inválido | Validación de formato |
| 5 | Cancelar operación | No se guarda información |

---

## Historia: Registrar Proveedores

| Caso | Entrada | Resultado Esperado |
|------|---------|-------------------|
| 1 | Datos completos y válidos | Proveedor registrado correctamente |
| 2 | Campo obligatorio vacío | Mensaje de error |
| 3 | NIT duplicado | Registro rechazado |
| 4 | Formato de correo inválido | Mensaje de validación |
| 5 | Cancelar registro | No se guarda información |

---

## Historia: Generar Factura de Venta

| Caso | Entrada | Resultado Esperado |
|------|---------|-------------------|
| 1 | Productos con stock disponible | Factura generada correctamente |
| 2 | Producto sin stock | Mensaje de stock insuficiente |
| 3 | Cliente no registrado | Solicitar registro previo |
| 4 | Cantidad inválida | Mensaje de validación |
| 5 | Cancelar operación | No se genera factura |

---

## Historia: Validar Stock Antes de Vender

| Caso | Entrada | Resultado Esperado |
|------|---------|-------------------|
| 1 | Stock suficiente | Permite continuar venta |
| 2 | Stock insuficiente | Bloquea la venta |
| 3 | Producto inexistente | Mensaje de error |
| 4 | Stock actualizado después de venta | Inventario se reduce correctamente |
| 5 | Consulta manual de stock | Muestra cantidad disponible |


