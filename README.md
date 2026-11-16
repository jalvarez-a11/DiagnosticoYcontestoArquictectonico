# DiagnosticoYcontestoArquictectonico

Resumen ejecutivo
Nombre del producto: Plataforma Centralizada de Gestión de Entregas (PCGE).
Problema principal: la empresa recibe pedidos por varios canales, administra inventarios distribuidos y coordina entregas con distintas rutas y repartidores, pero no tiene una vista centralizada del estado real de cada pedido. Esto produce duplicación de información, inconsistencias, retrasos, errores operativos y poca trazabilidad.
Usuarios y actores: clientes, operadores de tienda, administradores de almacén, repartidores, soporte al cliente y sistemas externos de pagos, geolocalización, notificaciones y ERP/CRM.
Objetivo: centralizar la información de los pedidos y facilitar la validación de inventario, asignación de rutas, seguimiento de entregas y gestión de incidencias.
Alcance inicial: registrar y consultar pedidos, gestionar estados, consultar inventario, coordinar rutas y repartidores, registrar entregas e incidencias. No se seleccionarán todavía frameworks ni se implementará software.

Análisis del problema
¿Qué ocurre hoy?
La información de pedidos, inventario y entregas está distribuida entre distintos canales, ubicaciones y responsables. No hay una vista única y actualizada que permita conocer el estado real de cada pedido.
¿Por qué es un problema?
Cuando las áreas trabajan con datos distintos o desactualizados, pueden duplicar pedidos, prometer productos agotados, asignar mal una entrega o comunicar información incorrecta al cliente. Soporte también pierde tiempo consultando varias fuentes.

¿Qué consecuencias tiene?
• Retrasos y entregas fallidas.
• Errores de inventario y preparación.
• Duplicación de registros y trabajo manual.
• Dificultad para reconstruir el historial del pedido.
• Más reclamaciones y menor satisfacción del cliente.
• Dificultad para crecer sin aumentar el desorden operativo.

¿Qué variables importan?
• Cantidad de pedidos por canal y por día.
• Exactitud y frecuencia de actualización del inventario.
• Tiempo entre la compra y la asignación de ruta.
• Porcentaje de entregas a tiempo y entregas fallidas.
• Tiempo para localizar un pedido o resolver una incidencia.
• Calidad y disponibilidad de los datos entre sistemas.

Actores y responsabilidades

Actor

Responsabilidad

Cliente:

Realiza compras, consulta el estado y recibe notificaciones.

Operador de tienda/comercio:

Revisa y gestiona pedidos recibidos por los canales de venta.

Administrador de almacén:

Confirma disponibilidad, preparación y salida de productos.

Repartidor:

Consulta asignaciones, reporta avances y registra el resultado de la entrega.

Soporte al cliente:

Consulta la trazabilidad y atiende incidencias.

Sistema de pagos:

Proporciona el estado del pago; no es reemplazado por la plataforma.

Servicio de geolocalización:

Proporciona ubicación o información útil para coordinar rutas.

Sistema de notificaciones:

Envía avisos a clientes o responsables.

ERP/CRM interno:

Intercambia datos comerciales, de clientes u operativos.
