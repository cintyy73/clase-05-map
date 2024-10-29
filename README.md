# Ejercicio: Lista de Productos

## Objetivo
Construir una lista de productos utilizando el método `.map()` y aplicar renderizado condicional para destacar los productos en oferta.

## Requisitos
1. Crear un array de objetos llamado `productos`, donde cada objeto contenga:
   - `id`: identificador único del producto
   - `nombre`: nombre del producto
   - `descripcion`: breve descripción del producto
   - `precio`: precio del producto
   - `enOferta`: un booleano que indica si el producto está en oferta o no.

2. Usar `.map()` para iterar sobre el array `productos` y renderizar un componente `Producto` para cada uno.

3. Dentro del componente `Producto`, implementar el siguiente renderizado condicional:
   - Si `enOferta` es `true`, mostrar un mensaje de **"¡En oferta!"** junto con un precio rebajado (puedes aplicar un descuento, por ejemplo, del 20%).
   - Si `enOferta` es `false`, mostrar el precio original sin mensaje adicional.

## Ejemplo de Array de Productos
```javascript
const productos = [
  { id: 1, nombre: "Laptop", descripcion: "Laptop potente para trabajar y jugar", precio: 1200, enOferta: true },
  { id: 2, nombre: "Teléfono", descripcion: "Teléfono de última generación con gran cámara", precio: 800, enOferta: false },
  { id: 3, nombre: "Auriculares", descripcion: "Auriculares con cancelación de ruido", precio: 150, enOferta: true },
  { id: 4, nombre: "Monitor", descripcion: "Monitor 4K de 27 pulgadas", precio: 400, enOferta: false },
  { id: 5, nombre: "Teclado", descripcion: "Teclado mecánico retroiluminado", precio: 100, enOferta: true },
  { id: 6, nombre: "Ratón", descripcion: "Ratón ergonómico inalámbrico", precio: 50, enOferta: false }
];
