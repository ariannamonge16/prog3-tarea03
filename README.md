Las líneas que acceden directamente a precioBase e items no compilan desde App porque ambos atributos son private. Sí compilarían dentro de sus propias clases, ItemMenu y Pedido, porque una clase puede acceder a sus propios atributos privados.

El método getPrecioBase() es protected. La llamada casado.getPrecioBase() sí compila desde App porque App pertenece al mismo paquete uam.prog3.tarea03, y protected permite acceso desde clases del mismo paquete.# prog3-tarea03
Tarea 3 de la clase de programación
