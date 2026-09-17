# Entrevista con el Cliente

---

## Tabla de Contenidos

- [Eventos y mesas](#eventos-y-mesas)
- [Menu y productos](#menu-y-productos)
- [Flujo de comandas](#flujo-de-comandas)
- [Cobros y pagos](#cobros-y-pagos)
- [Roles y permisos](#roles-y-permisos)
- [Reportes](#reportes)
- [Operacion y escalabilidad](#operacion-y-escalabilidad)

---

Documento de trabajo para levantar los requerimientos del primer cliente del sistema de comandas: un salon de eventos. Las respuestas capturadas aqui se vaciaron despues en `docs/LaTeX/Secciones/CasoDeEstudio.tex`.

## Eventos y mesas

- ¿El salón atiende uno o varios eventos simultáneamente?
  - **R:**
- ¿Cuántas mesas suelen usar por evento?
  - **R:**
- ¿Esa cantidad varía entre eventos?
  - **R:**
- ¿Las mesas están numeradas?
  - **R:**
- ¿Todos los meseros atienden todas las mesas o se le asigna a cada mesero un número de mesas?
  - **R:**

## Menu y productos

- ¿El menú es un todo incluido por evento o se atiende a la carta?
  - **R:**
- ¿Qué categorías de productos manejan?
  - **R:**
- ¿Los productos tienen precio fijo?
  - **R:**
- ¿Se manejan variantes de platillos?
  - **R:**
- ¿Se necesitan registrar ingredientes o alérgenos por producto, o solo nombre y precio?
  - **R:**
- ¿El menú cambia por temporada o es fijo todo el año?
  - **R:**

## Flujo de comandas

- ¿Cómo levantan hoy en día una comanda? (papel, apps sueltas, ninguno)
  - **R:**
- ¿Quién toma la orden: el mesero en la mesa o se centraliza en un punto?
  - **R:**
- ¿La comanda va directo a cocina o bar, o pasa por un supervisor?
  - **R:**
- ¿Se necesita un estado para la comida? (pendiente, en preparación, lista, entregada, cancelada)
  - **R:**
- ¿Puede una mesa hacer varias rondas de pedidos durante un evento?
  - **R:**
- ¿Se registran notas especiales por pedido?
  - **R:**
- ¿Quién puede cancelar o modificar una comanda ya enviada a cocina o bar?
  - **R:**

## Cobros y pagos

- ¿El cobro se hace al organizador del evento en una sola cuenta, o se divide por mesa, por invitado o por grupo de invitados?
  - **R:**
- ¿Manejan anticipos o depósitos antes del evento?
  - **R:**
- ¿Qué formas de pago se aceptan y necesitan quedar registradas?
  - **R:**
- ¿Se requiere factura fiscal (CFDI) o solo un recibo interno?
  - **R:**
- ¿Hay productos incluidos en el paquete que no se cobren aparte?
  - **R:**
- De ser así, ¿el consumo extra sí se cobra?
  - **R:**

## Roles y permisos

- ¿Qué roles existen y qué debe poder hacer cada uno en el sistema? (mesero, cocina, bar, cajero, administrador)
  - **R:**
- ¿Se necesita saber qué mesero levantó cada comanda?
  - **R:**

## Reportes

- ¿Qué reportes necesita el negocio? (ventas por evento, estadísticas por producto, tiempo promedio de preparación, ingresos por periodo)
  - **R:**
- ¿Necesita comparar el consumo real contra lo presupuestado en el paquete del evento?
  - **R:**
- ¿Con qué frecuencia se consultan estos reportes? (durante el evento en vivo o solo en el cierre)
  - **R:**

## Operacion y escalabilidad

- ¿Cuántos eventos atienden en promedio al mes y cuántas comandas por evento?
  - **R:**
- ¿El sistema debe funcionar sin internet dentro del salón, o siempre tienen conexión?
  - **R:**
- ¿Planean usar el sistema en otra sucursal a futuro?
  - **R:**
