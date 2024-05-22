Caso
Un grupo de amigas comenzó a realizar la venta de productos para mascotas como bandanas, correas e
identificaciones, todo esto para ayudar a una fundación sin fines de lucro, todo partió a través de las redes
sociales, pero en la actualidad es casi imposible dar abasto a la demanda a través de las redes sociales.
Por eso, a contactado a los alumnos del Duoc para que puedan ayudarles a construir una aplicación web que
permita a sus usuarios elaborar listas de compras con la intención de permitir a las amigas a ordenar sus
presupuestos, mejorar sus finanzas, realizar el aporte a la fundación sin fines de lucro y mejorar la venta y el
despacho de sus productos.
Los principales objetivos de la aplicación web son:
• Contar con una plataforma en internet para promover sus productos a usuarios registrados, que
indique el stock real de productos disponibles
• Entregar el servicio venta en línea.
• Permitir al cliente para monitorear sus compras.
• Mejorar el proceso de logística de sus productos a los clientes mediante el seguimiento del despacho.
• Permitir generar descuentos o promociones en la página principal
• Permitir subscribirse con una donación a la fundación sin fines de lucro, esta información ira
directamente a la fundación. Con el fin de motivar a sus clientes, se otorgará un 5% de descuento en
el total de la venta a todos los clientes que estén suscritos.
Funcionalidades del Sistema
• El sistema debe permitir registrar clientes para acceder a los servicios de ventas
• El sistema debe permitir a los clientes generar una compra, descontando los productos del stock una
vez creada la venta y realizar descuentos en caso de tratarse de una promoción o de un cliente suscrito.
• Para los usuarios registrados el sistema debe permitir ver un historial de ventas realizadas, además,
del estado del despacho de las ventas.
• Para el despacho de los productos, el sistema WEB debe entregar una traza de seguimiento del
despacho en el caso de los envíos a domicilio de clientes registrados, mostrando fecha y hora en que
se toma el pedido, se despacha y es recibido por el cliente, cerrando el ciclo.

DuocUC
Vicerrectoría Académica
ET3

Situación Evaluativa
Al estudiante FORMA A

Página 3 de 3
• El sistema debe permitir a los usuarios registrados poder subscribirse o des suscribirse de la donación
a la fundación sin fines de lucro.
• Se deben crear mantenedores para la información relativa a clientes, usuarios, productos,
promociones o descuentos
• El sistema debe permitir mostrar las opciones de acuerdo con los perfiles de cada usuario.
Características del producto
• La aplicación por desarrollar debe ser en ambiente web, con acceso desde internet, ya que será
necesario el registro de clientes, la publicación de productos u solicitudes de venta línea.
• El sistema debe ser construido en arquitectura web mediante modelo de capas, logrando una
separación de la interfaz gráfica, reglas de negocio y repositorio de datos.
• El sistema debe considerar acceder a servicios Rest al momento de simular la suscripción con la
fundación, se debe generar un servicio que permita registrar y eliminar las suscripciones (simulación).
• Es sistema debe considerar acceder a el servicio Rest de la fundación al momento de la venta para
validar si el cliente este o no suscrito y aplicar el descuento al total de la venta.
• Se debe crear un servicio Rest que simulé pertenecer a la fundación y proporcioné tres servicios
o Ingresar Suscriptores
o Eliminar Suscriptores
o Consultar vigencia de los suscriptores

Restricciones
• La aplicación debe utilizar la base de datos ORACLE
