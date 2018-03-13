# Ciclos de pedidos para Centros de Venta

 > Si no eres un vendedor/a sino un productor/a ve a [Ciclo de Pedidos para productores](/order-cycles-for-producers.md).

Usted abre su tienda al público creando un Ciclo de Pedido. Cuando realiza un Ciclo de Pedido, selecciona cuándo está abierto (desde y hasta), qué productos estarán disponibles para la venta y las tarifas que aplicarán.

**Por qué Ciclos de Pedidos?**

Algunos centros pueden desear tener una tienda en línea que esté abierta permanentemente, y cumplir pedidos uno a uno a medida que se reciben. Sin embargo, muchas tiendas operan en un sistema de pedidos periódico, lo que les permite procesar pedidos en grupos, haciendo que sus actividades de empaque y distribución sean más eficientes. Usemos un ejemplo para ilustrar una estructura de ciclo de ordenamiento periódico común.

Por ejemplo, cada lunes por la mañana una tienda podría evaluar el stock de sus productos para la semana. En base a esta información, crearán un ciclo de pedido para el lunes por la tarde y abrirán su tienda. Los clientes pueden hacer pedidos en su tienda en línea hasta que el ciclo de pedidos se cierre el miércoles a la medianoche. El jueves, todos los pedidos pueden ser empacados por la tienda y preparados para la entrega el viernes. La semana siguiente el ciclo comenzará de nuevo y con la creación de un nuevo Ciclo de Pedidos. Al estructurar los ciclos de pedidos de esta manera, y al tratar con pedidos en grupos, las tiendas pueden hacer que sus actividades de ordenamiento, clasificación, embalaje y transporte sean mucho más eficientes que si procesaran las órdenes individualmente a medida que se solicitan.

## 1. Acceder a Ciclos de Pedidos

Puede crear un ciclo de pedido y ver ciclos de pedido anteriores haciendo clic en **Administrar ciclos de pedido** en su panel principal.

![](/assets/gestionar_ciclos.JPG)

O desde el menú horizontal en la parte superior de la página.

![](/assets/nuevo_ciclo.JPG)

## 2. Crear un nuevo Ciclo de Pedido

A continuación se muestra la primera etapa para crear un ciclo de pedido.

* Recuerde, no puede crear un ciclo de pedido hasta que haya configurado los métodos de [entrega](/shipping-methods.md) y [pago](/payment-methods-2.md).

![![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Set-coordinator.png "Establecer el Coordinador del Ciclo de Pedido")](/assets/seleccionar_coord_ciclo.JPG)

Seleccione el coordinador del ciclo de pedido. El negocio que coordina un ciclo de pedido tiene plenos poderes y permisos para editar y administrar un ciclo de pedido. Otros negocios involucrados (como productores o distribuidores) tienen capacidades restringidas para editar un ciclo de pedido (para obtener más información, haga clic [aquí](/permissions-in-multi-enterprise-order-cycles.md)). Después de seleccionar al coordinador, el ciclo de pedido se restringirá según quién haya otorgado permiso a este coordinador para agregarlos a un ciclo (P-OC). Para obtener más información sobre los permisos del Negocio vaya a [aquí](/enterprise-to-enterprise-permissions-e2es.md).

**Nombre:** Escriba un nombre para el ciclo de pedido que sea significativo para usted. Le recomendamos que siga un protocolo de nombres consistente, por ejemplo, MiTienda_Semana27_2018. También le recomendamos que incluya el nombre de su tienda en el nombre del ciclo de pedido, de modo que la asistencia de Red Ágora pueda identificar sus ciclos de pedido si necesita ayuda.

**Apertura de los pedidos:** Esta es la fecha en la que su tienda en Red Ágora estará abierta, visible y comenzará a aceptar pedidos de clientes.

**Cierre de los pedidos:** Esta es la fecha en que su tienda en Red Ágora se cerrará y dejará de aceptar pedidos. Si tiene la intención de tener un ciclo de pedido que esté continuamente abierto, seleccione una fecha de cierre que esté bien en el futuro.

**Añadir cargos de coordinador:** Como tienda en línea, lo más probable es que usted sea el coordinador. Aquí puede aplicar tarifas que guarden relación con la coordinación. La tarifa adicional se obtendrá de acuerdo con la calculadora seleccionada en [Tarifas de Empresa](/enterprise-fees.md).

> Solo puede aplicar una tarifa del negocio que se haya creado previamente.



### Entrante: seleccione productor y productos

La sección **Entrante** es donde puede seleccionar los productores y sus productos, que estarán disponibles en este ciclo de pedido. En el menú desplegable, verá a todos los productores que le han otorgado permiso para agregar sus productos a su ciclo de pedido (consulte la sección _Relaciones con productores_ para obtener más información). Después de seleccionar un productor y hacer clic en **Agregar productor**, todos los productos asociados con ese productor estarán visibles. Verifique los productos que desea agregar a la tienda o haga clic en **Seleccionar Todo**. 

> Nota: Los productos que tienen un valor "a mano" de cero (sin stock disponible) seguirán siendo visibles, por lo que debe asegurarse de tener un inventario adecuado de los productos seleccionados.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Incomiing.png "Entrante")

Los campos **Detalles de recepción** son opcionales. Si desea utilizar el botón **Notificar a Productores**, para enviar pedidos a sus productores proveedores, debe escribir sus instrucciones de recibo de stock aquí (más información en la sección **Notificar Productores** en la parte inferior de esta página).

El botón **Agregar tarifa** es donde puede aplicar una tarifa del negocio, perteneciente a ese productor. Seleccione el nombre del negocio en el primer cuadro desplegable y luego haga clic en el nombre de la tarifa de negocio en el segundo cuadro desplegable. En el siguiente ejemplo, se aplica una tarifa de negocio llamada OrdenAdministrador al Productor de Fruta.

Esta tarifa se aplicará a todos los productos de este Productor. La tarifa se obtiene de acuerdo con la calculadora de tarifas que se seleccionó cuando la creó en [Tarifa de Empresa](/enterprise-fees.md).

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Enterprise-Fee.png "Aplicar tarifas del negocio a productores proveedores entrantes")

### 4. Saliente: seleccionar distribuidor

Los distribuidores seleccionados en la sección **Saliente** tendrán una tienda virtual creada a partir de este ciclo de pedido. Los productos que son seleccionados serán visibles para el público y podrán hacerse pedidos desde su tienda en línea. En modelos de tiendas simples, solo hay un distribuidor, la tienda en sí. Por lo tanto, seleccione la tienda en la columna del distribuidor y luego seleccione todos los productos que deberían estar visibles en la tienda en línea durante este ciclo de pedido. Los modelos de tiendas más complejos pueden tener varios distribuidores, en cuyo caso cada uno se selecciona como distribuidor y, en consecuencia, en cada uno se creará un tienda virtual con los productos seleccionados que estarán visibles para recibir pedidos.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Outoging-New.png "Sección Saliente")

La columna de **etiquetas** es donde puede etiquetar el ciclo de su pedido (consulte [Cuentas de clientes y Etiquetado](/customer-accounts-and-tagging.md)). El cuadro **Listo para (fecha / hora)** le informa al cliente cuándo su pedido estará listo para la recolección o la entrega. Si su ciclo de pedido es perpetuo, lo que cumple órdenes de manera individual en lugar de a granel, debe ingresar algo así como '24hs después de la recepción del pedido'. El siguiente ejemplo muestra cómo se muestra 'Viernes 9' en una tienda.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Ready-for.png "Campo 'Listo para'")

La nota también se muestra al momento de confirmar el pedido, cuando el cliente selecciona su método de envío (ver a continuación) y se incluye en el correo electrónico de confirmación del pedido.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/shipping-info.png "'Listo para' en email")

El mensaje **Instrucciones de recogida** se incluirá en el correo electrónico de confirmación del pedido del cliente, debajo del mensaje que corresponde al método de envío elegido (ver más abajo). Esta nota está diseñada para que solo sea visible para los clientes, por lo que puede incluir información más sensible, como direcciones o números de teléfono, etc. Ver más abajo para un ejemplo del correo electrónico de confirmación de pedido.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/Collection-details.png "Mensaje de los detalles de recogida")

**Agregar tarifa:** Nuevamente, se puede asignar una tarifa de negocio previamente creada a este distribuidor.

### 5. Abra su tienda en línea

Haga clic en Crear para guardar este ciclo de orden.

![](http://openfoodfoundation.org/sites/default/files/create.png).

> Cuando crea un ciclo de pedido, y el rango de fechas de apertura y cierre incluyen la fecha actual, se abrirá una tienda en línea en la página de inicio de la tienda. Si no está listo para abrir su tienda, coloque temporalmente las fechas de apertura y cierre en el pasado (esto se puede editar cuando esté listo para abrir).

Para ciclos de pedidos periódicos y repetitivos, puede copiar un ciclo de pedido existente y cambiar las fechas para agilizar el proceso. Vea abajo.

![](https://openfoodnetwork.org/wp-content/uploads/2015/05/copy-order-cycle.png "Duplicar Ciclo de Pedido")

Los ciclos de pedido se mostrarán en verde cuando estén activos, amarillos cuando se programen para una fecha futura y gris cuando se hayan cerrado. Cuando un ciclo de pedido se cierra hace más de un mes, ya no aparecerá en esta lista. Para ver todos sus ciclos de pedidos pasados, haga clic en 'mostrar más' en la parte superior de la lista.

#### Botón 'Notificar Productores'

Algunos centros de venta utilizan esta herramienta como una forma de notificar a sus productores proveedores qué artículos se han pedido, en qué cantidades y también para darles instrucciones de recepción. Al hacer clic en este botón, se enviará el siguiente correo electrónico al correo electrónico de contacto del perfil del productor. Se envía a todos los productores incluidos en este ciclo de pedido y sumará todos los pedidos realizados en ese ciclo de pedido.

```
Estimado <Nombre del Proveedor>,

Ahora tenemos todos los pedidos de los consumidores para este periodo.

Instrucciones de entrega/recogida: **Instrucciones**.

Resumen de pedidos
==================

Aquí hay un resumen de los pedidos de sus productos:

<Total de pedidos de productos en este ciclo de pedidos (ejemplo a continuación)> 
- Productor de hortalizas - Zanahoria (500 g) (CANT .: 3) @ Gs 3.000 = Gs 9.000 
- Productor de lácteos - Queso Py (500 g) (CANT .: 1 ) @ Gs 20.000 = Gs 10.000

Gracias y mis mejores deseos

<Nombre del Centro de Venta, dirección, número de teléfono, correo electrónico>
```

##### Configuraciones avanzadas

Estas configuraciones son relevantes para ciclos de pedido de múltiples distribuidores. Ver [Inventario](/inventory.md) para detalles de estas configuraciones.

#### Funciones avanzadas relacionadas:

* [Creación de ciclos de pedido de "solo visualización"](/creating-display-only-order-cycles.md)
* [Permisos en ciclos de orden multi-negocio](/permissions-in-multi-enterprise-order-cycles.md)