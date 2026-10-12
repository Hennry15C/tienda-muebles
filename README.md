# 🪑 Madera Viva — Tienda de muebles online

Tienda online de muebles con compra completa y entrega a domicilio, hecha con **HTML, CSS y JavaScript puro** (sin librerías ni servidor). Proyecto de portafolio.

## Qué hace

- Catálogo de 12 muebles con búsqueda, filtro por categoría y orden por precio
- Detalle de producto con selección de color y cantidad
- Carrito con cantidades, código de descuento (`BIENVENIDO10`) y totales en bolivianos (Bs)
- **Checkout en 3 pasos:** datos de entrega → método de pago → confirmación
- **Entrega a domicilio** en 5 ciudades, con costo por ciudad y envío gratis desde Bs 3.000
- Elección de fecha y horario de entrega
- Tres métodos de pago: QR bancario, tarjeta (validada con el algoritmo de Luhn) y contra entrega
- Número de pedido e historial en "Mis pedidos"
- Validación de formularios (celular boliviano, correo, dirección, fecha)
- Diseño responsive para celular y computadora

## Importante

El pago es una **simulación** para demostrar el flujo de compra. No se cobra dinero real y **no se guardan datos de tarjeta**. El carrito y los pedidos se guardan solo en el navegador (`localStorage`).

## Cómo ejecutarlo

1. Descarga o clona el repositorio
2. Abre `index.html` en tu navegador

## Personalización

- Productos: edita el arreglo `P` en `index.html`
- Ciudades y costos de envío: edita el objeto `CITIES`
- Monto de envío gratis: constante `FREE`

## Próximos pasos

- Backend con Node.js y base de datos para guardar pedidos
- Pasarela de pago real
- Panel de administración de productos

## Tecnologías

HTML5 · CSS3 · JavaScript (ES6) · localStorage

## Autor

Hennry — estudiante de ingeniería de sistemas, UDABOL.
