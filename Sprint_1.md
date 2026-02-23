# Sprint 1 – Planificación

## 1. Información General del Sprint

Duración del Sprint: 2 semanas  
Objetivo del Sprint: Implementar las funcionalidades básicas del sistema relacionadas con inventario, proveedores y facturación para lograr un primer incremento funcional del SmartMarket ERP.

---

## 2. Historias de Usuario Seleccionadas

Las siguientes historias fueron seleccionadas del Product Backlog considerando su prioridad y valor de negocio:

| Historia | Descripción | Story Points |
|----------|------------|--------------|
| HU-01 | Registrar productos | 5 |
| HU-02 | Registrar proveedores | 3 |
| HU-03 | Generar factura de venta | 8 |
| HU-04 | Validar stock antes de vender | 5 |

Total Story Points comprometidos en el Sprint: 21

---

## 3. Justificación de Selección

Las historias seleccionadas corresponden a funcionalidades críticas para el funcionamiento básico del sistema, ya que permiten:

- Registrar y gestionar productos.
- Administrar proveedores.
- Ejecutar ventas.
- Garantizar control de inventario.

Estas funcionalidades representan el núcleo operativo del supermercado.

---

## 4. Detalle de Historia de Usuario – HU-01

### Título
Registrar productos

### Descripción
Como administrador,  
quiero registrar nuevos productos en el sistema,  
para poder gestionar el inventario de manera organizada y eficiente.

### Criterios de Aceptación

1. Dado que el administrador ingresa datos válidos,  
   cuando guarda el producto,  
   entonces el sistema lo almacena correctamente en la base de datos.

2. Dado que falta un campo obligatorio,  
   cuando intenta guardar el producto,  
   entonces el sistema muestra un mensaje de error indicando el campo requerido.

3. Dado que el código del producto ya existe,  
   cuando intenta registrarlo nuevamente,  
   entonces el sistema rechaza el registro y notifica duplicidad.

4. Dado que el producto es guardado correctamente,  
   cuando se consulta la lista de productos,  
   entonces debe aparecer en el inventario.

5. Dado que el precio ingresado es inválido o negativo,  
   cuando intenta guardar el producto,  
   entonces el sistema valida el formato y bloquea el registro.

---

## 5. Resultado Esperado del Sprint

Al finalizar el Sprint 1 se espera contar con:

- Registro funcional de productos.
- Registro funcional de proveedores.
- Generación básica de facturas de venta.
- Validación automática de stock antes de realizar una venta.

Este incremento permitirá realizar operaciones esenciales del supermercado dentro del sistema.
