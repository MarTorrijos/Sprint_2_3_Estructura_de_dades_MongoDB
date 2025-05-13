# Sprint_2_3_Estructura_de_dades_MongoDB
IT Academy: Sprint 2 - Tasca 3 - Estructura de dades MongoDB


## Descripción

El objectivo de este ejercicio es aprender a utilizar las bases de datos MongoDB.


### Tecnologias usadas

- MongoDB

- MongoDB Compass

- Editor de texto

***

## Nivel 1

Una óptica, llamada “Culo de Botella”, quiere informatizar la gestión de clientes y ventas de gafas.

En primer lugar, la óptica quiere saber quién es el proveedor de cada uno de las gafas. En concreto, quiere saber de cada proveedor: El nombre, la dirección (calle, número, piso, puerta, ciudad, código postal y país), teléfono, fax, NIF.

De las gafas se quiere saber: La marca, la graduación de cada uno de los cristales, el tipo de montura (flotante, pasta o metálica), el color de la montura, el color de cada cristal y el precio.

De los clientes se quiere almacenar: El nombre, la dirección postal, el teléfono, el correo electrónico, la fecha de registro. Cuando llega un nuevo cliente, almacenar el cliente que le ha recomendado el establecimiento (siempre que alguien le haya recomendado). Nuestro sistema tendrá que indicar quién ha sido el empleado que ha vendido cada gafa. Definir qué día/hora se realiza la venta.

- Diseña una base de datos desde el punto de vista del cliente
- Diseña una base de datos desde el punto de vista de las gafas

<br>


***

## Nivel 2

Te han contratado para diseñar una web que permita hacer pedidos de comida a domicilio por Internet.

Toma en cuenta las siguientes indicaciones para modelar cómo sería la base de datos del proyecto:

Para cada cliente se almacena un identificador único: Nombre, apellidos, dirección, código postal, localidad, provincia, número de teléfono.

Una persona puede realizar muchas órdenes, pero una única orden solo puede ser realizada por una única persona. De cada orden se almacena un identificador único: Fecha/hora de realización, si la orden es para reparto a domicilio o para recoger en tienda, la cantidad de productos que se han seleccionado de cada tipo, el precio total además de una nota con información adicional.

Una orden puede constar de uno o varios productos.

Los productos pueden ser pizzas, hamburguesas y bebidas. De cada producto se almacena un identificador único: Nombre, descripción, imagen, precio. En el caso de las pizzas existen diversas categorías que pueden ir cambiando de nombre a lo largo del año.

Una orden es gestionada por una única tienda y una tienda puede gestionar muchas órdenes. De cada tienda se almacena un identificador único: Dirección, código postal, localidad, provincia.

En una tienda pueden trabajar muchos empleados y un empleado solo puede trabajar en una tienda. De cada empleado, se almacena un identificador único: Nombre, apellidos, NIF, Teléfono, si trabaja como cocinero o repartidor. Para las órdenes de reparto a domicilio interesa guardar quién es el repartidor que hace la entrega de la orden y la fecha/hora del momento de la entrega.

- Diseña una base de datos desde el punto de vista del pedido

<br>


***


## Cómo ejecutarlo
Clona el repositorio o descarga el archivo zip, luego ábrelo en tu entorno de desarrollo integrado (IDE) preferido.
