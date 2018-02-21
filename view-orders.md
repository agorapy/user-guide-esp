# Ver pedidos

Puede interactuar con pedidos a través de dos páginas dentro de la Red Ágora, la página Listado de Pedidos y la página de Gestión de Pedidos Masivos. Las características de estas dos páginas se analizarán a continuación.

## Listado de Pedidos

La página de orden de listado muestra una vista de lista de todos los pedidos realizados a través de su(s) tienda(s). Desde aquí puede acceder a detalles de pedidos individuales, editar pedidos y rastrear el estado de su pago y envío. Para detalles sobre cómo crear un nuevo pedido, vea [aquí](/create-an-order.md).

La página tiene filtros que le permiten seleccionar qué pedidos desea ver. Puede filtrar por fecha, estado o el correo electrónico y el nombre del cliente.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Listing-Orders1.png "Listado de Pedidos")

**Distribuidor:** Esta es la empresa desde cuya tienda se realizó el pedido.

**Completado el:** Esta es la fecha en que se realizó el pedido.

**Código:** este es un número de orden asignado arbitrariamente.

**Estado:**

* Completo: el cliente finalizó la compra
* Cancelado: si el administrador edita el pedido y elige 'cancelarlo'
* Carro: El cliente está en proceso de compra, pero no se confirmado aún.

Se mostrará un símbolo de exclamación si el cliente incluyó una nota con su pedido al momento del pago. Pase el mouse sobre el signo de exclamación para ver la nota.

**Estado de Pago:**

* Pago Pendiente: si se trata de efectivo, o transferencia bancaria o EFTPOS, el pedido será 'saldo adeudado' por defecto, hasta que el administrador indique que se ha recibido el pago.
* Pagado: si se paga mediante algún medio de pago electrónico, esto se actualizará automáticamente a 'pagado' después del pago. Si el pago se ha indicado manualmente como si hubiera ocurrido, el estado también será 'pagado'.
* Crédito adeudado: si alguien ha pagado su pedido, pero luego edita su pedido y elimina un artículo, el costo de ese artículo se convierte en "crédito adeudado".

**Estado de entrega:**

* Pendiente: cuando el estado de pago es 'Pago pendiente', el estado de envío estará pendiente, lo que significa que hasta que se reciba el pago, el envío no debe comenzar.
* Listo: cuando se ha recibido el pago (estado pagado o acreditado), el estado de envío se convierte en "listo".
* Enviado: cuando el producto ha sido editado y se ha hecho clic en el botón 'enviar', el estado se vuelve "Enviado".

> Nota: No puede configurar un pedido para 'enviado' a menos que el estado de pago del pedido sea 'Pagado'.

**Correo electrónico del cliente:** el correo electrónico de contacto del cliente. Se puede extraer una lista completa de los correos electrónicos de los clientes en el informe de la [lista de correo](/reports.md).

**Total:** el valor total de la orden del cliente

#### Cambiar el estado de pago y envío de un pedido

En el lado derecho de la vista de listado puede actualizar el estado de pago/envío de un pedido.

Haga clic en el ícono de marcar para indicar que se recibió el pago \(![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Tick.png "Pagado")\).  
Haga clic en el ícono de la carretera para indicar que la orden se envió \(![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Shipped.png "Botón de Entrega")\).  
Haga clic en el ícono editar \([![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Edit-order.png "Botón de editar pedido")](https://openfoodnetwork.org/wp-content/uploads/2015/05/Edit-order.png)\) para editar un pedido y ver información más detallada al respecto (ver más abajo).

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/tracking-orders.png "Seguimiento y edición de pedidos")

#### Editar un pedido

Después de hacer clic en el botón de edición en el lado derecho de un pedido (ver imagen arriba) se le dirigirá a una vista detallada del pedido (abajo). Las funcionalidades dentro de esta página serán discutidas a continuación.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/View-Order.png "Ver Pedido")

**Agregar y eliminar productos de un pedido**

You can select a product to add to the order. To remove a product click the rubbish bin icon on the right hand side of a product. You can also change the quantity ordered. Remember to click the **update and recalculate fees **button to save changes.
Puede seleccionar un producto para agregar al pedido. Para eliminar un producto, haga clic en el icono de cubo de basura en el lado derecho de un producto. También puede cambiar la cantidad ordenada. Recuerde hacer clic en el botón **actualizar y recalcular tarifas** para guardar los cambios.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Order-actions.png "Acciones de Pedidos")

**Reenviar el correo electrónico de confirmación**

Si realiza cambios en el pedido de un cliente, es posible que desee volver a enviar un correo electrónico de confirmación de pedido actualizado al cliente.

**Imprimir factura**

Al hacer clic en esto, tendrá la opción de imprimir una factura en formato PDF o enviarla a una impresora.

**Enviará la factura**

Para enviar una factura al cliente, haga clic en el botón 'enviar factura'. Esto enviará un correo electrónico al cliente con un archivo PDF adjunto. El diseño de la factura se muestra a continuación.

**Cancelar una orden**

Haga clic en el botón cancelar para cancelar un pedido.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Invoice-example.png "Ejemplo de factura")

**Marcar una orden como pagada**

Para marcar un pedido como pagado, haga clic en el ícono de marcar en la página de lista de pedidos. O haga clic en 'Pagos' en el menú a la derecha y luego haga clic en el ícono de marcar \(![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Tick.png "paid")\).

**Marque un pedido como enviado**

Una vez recibido el pago, el botón Enviar estará visible en la parte superior de la página \(![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Ship.png "Entrega")\). Haga clic para registrar que el envío ha ocurrido.

**Ver detalles del cliente**

Al hacer clic en los detalles del cliente \([![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Customer-details.png "Detalles del cliente")](https://openfoodnetwork.org/wp-content/uploads/2015/05/Customer-details.png)\) en el menú de la derecha, accederá a una vista completa de los detalles del cliente.

**Sumar o restar del saldo de la orden**

Al hacer clic en los ajustes \([![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Adjustments.png "Ajustes")](https://openfoodnetwork.org/wp-content/uploads/2015/05/Adjustments.png)\). Desde aquí puede eliminar las tarifas que ya están en un pedido, o sumar/restar del total del pedido haciendo clic en + Nuevo ajuste. También tiene la capacidad de seleccionar la configuración de impuestos del ajuste. Recuerde, para que una tarifa incluya impuestos, la empresa debe estar configurada para cobrar impuestos en su configuración de perfil.

#### Vista del cliente

Sus clientes pueden ver una lista de sus pedidos cuando inician sesión en la Red Ágora, y hacen clic en su cuenta (ver a continuación).

[![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Account-login.png "Login de la cuenta del cliente")](https://openfoodnetwork.org/wp-content/uploads/2015/05/Account-login.png)

Aquí sus clientes podrán ver los pedidos y pagos pasados, así como un saldo corriente en su tienda. Esto debe mantenerse actualizado para que los clientes puedan ver un balance preciso.

[![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Orders.png "Cuenta del cliente")](https://openfoodnetwork.org/wp-content/uploads/2015/05/Orders.png)

## Bulk order management

While the listing view shows you orders, and details about who the customer is and when the order was placed etc, the bulk order management page shows you all items that were purchased in your orders. In bulk order management you can view all items ordered and make changes to the quantities of products ordered, or to delete certain products from orders. This functionality is useful for adjusting orders when there are stock shortages and you need to allocate a limited amount of stock.

Access Bulk Oder Management by clicking **Orders **in the blue horizontal menu, and **Bulk Order Management **in the horizontal green menu.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Bulk-Order-Management.png "Accessing bulk order management")

Within Bulk Order Management, you can apply filters, so that only the orders that you are interested in will display.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Filter-Bulk-order-man.png "Filtering within bulk order management")

**Start Date and End Date:** You can filter to display all orders that were placed within a given window of time.

**Producer:** You can filter for a given producer. This can narrow down the display, if you’re only interested in one product, supplied by one proudcer.

**Hub: **You can filter according to the hub at which the order was placed.

**Order Cycle:** Perhaps the most useful filter, the order cycle filter, will display only those orders which were placed within a selected order cycle.

**Quick Search:** Before or after applying filters, you can narrow your search down even further by searching for a key word. This could be a name, product, hub, producer, date, order number…

**Actions: **You can select the checkboxes of multiple orders, to perform a function to all of them, such as delete.

**Columns:** You can select which fields you do or do not want to be displayed \(see below\)

[![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Bulk-Order-Man-Columns.png "Bulk Order Management Columns")](https://openfoodnetwork.org/wp-content/uploads/2015/05/Bulk-Order-Man-Columns.png)

You can also sort the rows according to the contents of a column. For example, if you click on the Order Date column title, the table will be arranged in chronological order, according to the value in this field. Clicking the Name column heading will arrange the table in alphabetical order of the customer’s name.

\*Note: The price column lists prices exclusive of fees, but will include GST if the product is set as GST inclusive. Fees will re-calculate if you edit orders.

### Examples of using Bulk Order Management:

#### Example 1: You have a stock shortage, and must reduce customer order quantities for a certain product.

In your current order cycle, customers placed orders for 20kg of tomatoes. Unfortunately there was a storm, and you were only able to harvest 10kg. You need to identify all customers who ordered tomatoes, and half their orders for tomatoes.

This can be done in bulk order management, as follows:

1. You would filter according to the date range, or order cycle.
2. Search for ‘tomatoes’. All orders for tomatoes within the date range/order cycle you selected will now display.
3. Click on the product ‘Tomatoes’ in the Product:Unit column.
4. A box will appear at the top of the page, showing the total quantity ordered \(across the date range/order cycle you’ve selected\).

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/BOM-1.png "Bulk Order Management")

You can then adjust the quantity of each unique order in the Quantity column. The Total Quantitiy Ordered in the box at the top will update automatically as you adjust orders, in this case going down, as you reduce each order for the tomatoes.

You could also then see the emails of these customers, and send them an alert._An alert is not automatically generated when adjustments are made in bulk order management._

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/BOM-2.png "Bulk Order Management")

##### **The ‘Shared Resource’ checkbox**

In the screenshot above you will see a checkbox called ‘shared resource’ in the top right hand corner of the blue, producer order totals box. When you select this checkbox, the total displayed will be inlcusive of all product variants that fall under the master product. By not checking it, you can see the total for a single product variant. In the example below, you can see that when the shared resource box is selected, the total includes orders for both my 1kg apple variant and my 3kg apple variant. So I know that in total, I need 5kg of apples. If I just want to know how many 3kg bags to pack, I can uncheck the shared resource box, and click on the 3kg variant in the Product:Unit column.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Shared-Resource.png "Shared Resource checked")

#### Example 2: Updating the final weight of products.

When selling indivisible products such as legs of lamb, or whole pumpkins, you may not know the final weight and price of the product until after the customer has placed their order. You can use Bulk Order Management to update the item’s exact weight once you have the product in front of you.

Check out Pricing irregular, indivisible meat items for more information about pricing products such as this.

We’ll use an example of a leg of lamb to illustrate. In this case the producer charges all customers for a 2kg leg of lamb, and then adjusts their orders after slaughter, when he knows the exact weight of the product assigned to each customer. To make such adjustments the producer would do the following:

1. Filter for the order cycle or date range of interest.
2. Search for the leg of lamb product to view all customer orders for the product.
3. Make the
   **Weight/Volume**
   and
   **Price**
   columns visible.
4. Enter the actual weight of the leg of lamb that each customer will receive in the weight/volume column. The price will automatically recalculate based on this weight.
5. Click update.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Meat-BOMM.png "Bulk Order Management example")

_Have a suggestion for how we could improve this feature? Send us an email or join the conversation on our community forum._

