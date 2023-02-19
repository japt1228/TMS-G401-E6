# Descripción del proyecto (Sistema POS)

Se pretende desarrollar un sistema de punto de ventas para diferentes tipos de tiendas que manejen inventario de sus productos, tales como ferreterias, tiendas de barrio (minimercados, supermercados) entre otros.

El sistema va a trabajar por modulos:

- ***Modulo de Usuarios:*** la información a requerir sera el nombre, apellidos, documento, correo o usuario, contraseña y rol

- ***Modulo de Clientes:*** la información a requerir sera nombre, apellido, documento, direccion, telefono.

- ***Modulo de productos:*** la información a requerir sera codigo, nombre, categoria, cantidad en stock, lote, fecha de vencimiento(si se requiere), costo, precio de venta, marca(si se requiere).

- ***Modulo de categoria:*** la información a requerir seria el codigo y nombre.

La aplicación constara de actores principales como el superadministrador (Posible dueño de la tienda), administrador (encargado del control de inventarios), vendedor (encargado de realizar las ventas y capturar los datos de los clientes).

El sistema funcionara de la siguiente manera, al acceder la primera pantalla sera la vista del login, donde el usuario accedera con su usuario o correo y contraseña (*Solo el usuario superadministrador puede registrar los usuarios del sistema*).

Tras haberse logueado aparecera la pantalla principal, el cual sera el modulo de venta, donde apareceran los diferentes productos que pueden ser vendidos y un filtro donde se podra buscar por nombre o categoria, aquellos productos que no cuenten con stock disponible apareceran con una marca especial para que el vendedor no pueda seleccionarlo. tambien tendra una seccion de factura de venta, donde captura la informacion del cliente al cual se le esta vendiendo, si no existe podra tener la opcion de crearlo o asignarlo a un cliente general, aqui tambien vera el precio total de venta y los productos asignados a la venta.

Dependiendo del tipo de rol tambien habra un menu donde pueda acceder a los diferentes modulos que ofrece el sistema.
