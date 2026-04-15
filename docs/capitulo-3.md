# Capítulo III: Requirements Specification

## 3.1. User Stories

<!-- Epics-->
<table>
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>

  <!-- EPIC 01 -->
  <tr>
    <td><strong>Epic-01</strong></td>
    <td><strong>Gestión de inventario</strong></td>
    <td>Como usuario quiero gestionar mi inventario (lotes y productos) para visualizar los datos con mayor claridad.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 01 -->
  <tr>
    <td>US-01</td>
    <td>Agregar productos</td>
    <td>Como usuario quiero agregar productos para gestionar mi inventario de manera eficiente.</td>
    <td>
      <strong>Scenario 1: Agregar producto correctamente</strong><br>
      Dado que el usuario está en el formulario de productos, cuando ingrese los datos correctamente y presione "Guardar", entonces el producto se registrará exitosamente.<br><br>
      <strong>Scenario 2: Validación de datos</strong><br>
      Dado que el usuario está en el formulario de productos, cuando deje campos obligatorios vacíos y presione "Guardar", entonces el sistema mostrará mensajes de error.
    </td>
    <td>Epic-01</td>
  </tr>

  <!-- US 02 -->
  <tr>
    <td>US-02</td>
    <td>Editar lotes</td>
    <td>Como usuario quiero editar los lotes para actualizar los datos del inventario.</td>
    <td>
      <strong>Scenario 1: Editar lote correctamente</strong><br>
      Dado que el usuario está en la sección de lotes y selecciona un lote existente, cuando modifique los datos correctamente y presione "Guardar", entonces los cambios del lote se actualizarán exitosamente.<br><br>
      <strong>Scenario 2: Validación al editar lote</strong><br>
      Dado que el usuario está editando un lote, cuando ingrese datos inválidos o deje campos obligatorios vacíos y presione "Guardar", entonces el sistema mostrará mensajes de error y no guardará los cambios.
    </td>
    <td>Epic-01</td>
  </tr>

  <!-- US 03 -->
  <tr>
    <td>US-03</td>
    <td>Agregar lotes</td>
    <td>Como usuario quiero agregar lotes para gestionar correctamente las cantidades y fechas de vencimiento.</td>
    <td>
      <strong>Scenario 1: Agregar lote correctamente</strong><br>
      Dado que el usuario está en la sección de lotes y selecciona un lote existente, cuando ingrese una cantidad y fecha válida y presione "Agregar", entonces el nuevo lote se agregará exitosamente.<br><br>
      <strong>Scenario 2: Validación al agregar lote</strong><br>
      Dado que el usuario está en la sección de lotes, cuando ingrese datos inválidos y presione "Agregar", entonces saldrá un mensaje de error por campo inválido.
    </td>
    <td>Epic-01</td>
  </tr>

  <!-- US 04 -->
  <tr>
    <td>US-04</td>
    <td>Eliminar lotes</td>
    <td>Como usuario quiero eliminar lotes para deshacerme de los lotes que no me sirvan.</td>
    <td>
      <strong>Scenario 1: Eliminar lote correctamente</strong><br>
      Dado que el usuario está en la sección de lotes y selecciona un lote existente, cuando presione "Eliminar", entonces el lote se eliminará exitosamente.<br><br>
      <strong>Scenario 2: Validación al eliminar lote</strong><br>
      Dado que el usuario está en la sección de lotes y no selecciona un lote existente, cuando presione "Eliminar", entonces saldrá un mensaje de error de no haber seleccionado un lote.
    </td>
    <td>Epic-01</td>
  </tr>

  <!-- US 05 -->
  <tr>
    <td>US-05</td>
    <td>Editar productos</td>
    <td>Como usuario quiero editar productos para actualizar los datos en el inventario.</td>
    <td>
      <strong>Scenario 1: Producto editado correctamente</strong><br>
      Dado que el usuario está en la sección de productos y selecciona un producto existente, cuando presione "Editar", entonces el producto se actualizará exitosamente.<br><br>
      <strong>Scenario 2: Validación al editar productos</strong><br>
      Dado que el usuario está en la sección de productos y no selecciona un producto existente, cuando presione "Editar", entonces el sistema mostrará mensajes de error.
    </td>
    <td>Epic-01</td>
  </tr>

  <!-- US 06 -->
  <tr>
    <td>US-06</td>
    <td>Visualizar detalles de lotes</td>
    <td>Como usuario quiero visualizar los detalles de los lotes para poder gestionar mejor el inventario.</td>
    <td>
      <strong>Scenario 1: Detalles de lote mostrados correctamente</strong><br>
      Dado que el usuario está en la sección de lotes y selecciona un lote existente, cuando presione "Ver Detalles", entonces los detalles se mostrarán exitosamente.<br><br>
      <strong>Scenario 2: Validación al visualizar detalles de lote</strong><br>
      Dado que el usuario está en la sección de lotes y no selecciona un lote existente, cuando presione "Ver Detalles", entonces saldrá un mensaje de error.
    </td>
    <td>Epic-01</td>
  </tr>

  <!-- US 10 -->
  <tr>
    <td>US-10</td>
    <td>Visualizar detalles de producto</td>
    <td>Como usuario quiero visualizar la información detallada de cada producto en el listado para conocer rápidamente sus características, stock disponible y precio sin necesidad de ingresar a otra pantalla.</td>
    <td>
      <strong>Scenario 1: Visualización de información del producto</strong><br>
      Dado que el usuario accede al listado de productos, cuando se carga la información, entonces cada producto debe mostrar: tipo, nombre, descripción, código QR, stock total y precio.<br><br>
      <strong>Scenario 2: Manejo de información incompleta del producto</strong><br>
      Dado que un producto no cuenta con algún dato, cuando se carga la información, entonces el sistema muestra los datos disponibles y los campos faltantes aparecen como "-".
    </td>
    <td>Epic-01</td>
  </tr>

  <!-- US 12 -->
  <tr>
    <td>US-12</td>
    <td>Buscar productos</td>
    <td>Como usuario quiero tener un buscador de productos para perder menos tiempo buscando en el inventario.</td>
    <td>
      <strong>Scenario 1: Búsqueda de productos por nombre</strong><br>
      Dado que el usuario está en el listado de productos, cuando ingresa el nombre de un producto en el campo de búsqueda, entonces el sistema filtra y muestra los productos que coincidan.<br><br>
      <strong>Scenario 2: Búsqueda de productos por categoría</strong><br>
      Dado que el usuario está en el listado de productos, cuando selecciona o ingresa una categoría, entonces el sistema filtra y muestra los productos de esa categoría.
    </td>
    <td>Epic-01</td>
  </tr>

  <!-- US 23 -->
  <tr>
    <td>US-23</td>
    <td>Crear lotes</td>
    <td>Como usuario quiero crear lotes de productos para controlar mejor el stock y la caducidad en el inventario.</td>
    <td>
      <strong>Scenario 1: Creación de lote exitosa</strong><br>
      Dado que el usuario está en la sección de productos, cuando presiona "Crear Lote", selecciona un producto y completa los datos correctamente, entonces el sistema registra el nuevo lote y lo muestra en la lista.<br><br>
      <strong>Scenario 2: Validación al crear lote</strong><br>
      Dado que el usuario no selecciona un producto o ingresa datos incompletos, entonces el sistema muestra mensajes de error y no permite la creación del lote.
    </td>
    <td>Epic-01</td>
  </tr>

  <!-- EPIC 02 -->
  <tr>
    <td><strong>Epic-02</strong></td>
    <td><strong>Notificaciones de inventario</strong></td>
    <td>Como usuario quiero que el sistema me notifique el estado de mis lotes para organizarme mejor.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 07 -->
  <tr>
    <td>US-07</td>
    <td>Detectar stock agotado</td>
    <td>Como usuario quiero ser notificado cuando tengo bajo/nada de stock.</td>
    <td>
      <strong>Scenario 1: Alerta de stock próximo a agotarse</strong><br>
      Dado que uno o más lotes tienen stock por debajo del umbral definido, cuando el usuario accede al dashboard de lotes, entonces se muestra una alerta visible indicando los lotes próximos a agotarse.<br><br>
      <strong>Scenario 2: Alerta de stock agotado</strong><br>
      Dado que uno o más lotes están agotados, cuando el usuario accede al dashboard, entonces se muestra una alerta indicando los lotes agotados.
    </td>
    <td>Epic-02</td>
  </tr>

  <!-- US 08 -->
  <tr>
    <td>US-08</td>
    <td>Mostrar alertas de estado al visualizar detalles</td>
    <td>Como usuario quiero visualizar alertas de estado al ver el detalle de un lote para identificar rápidamente si tiene stock bajo, está agotado o próximo a vencer.</td>
    <td>
      <strong>Scenario 1: Alerta de estado mostrada</strong><br>
      Dado que el lote tiene stock bajo, está agotado o próximo a vencer, cuando presiona "Ver Detalles", entonces se mostrarán los detalles del lote con alertas de estado.<br><br>
      <strong>Scenario 2: Sin alertas si el estado es normal</strong><br>
      Dado que el lote no tiene condiciones críticas, cuando presiona "Ver Detalles", entonces se muestran los detalles sin alertas.
    </td>
    <td>Epic-02</td>
  </tr>

  <!-- US 09 -->
  <tr>
    <td>US-09</td>
    <td>Visualizar dashboard de lotes</td>
    <td>Como usuario quiero visualizar un dashboard de lotes con indicadores y alertas para conocer rápidamente el estado de mi inventario al ingresar al módulo de lotes.</td>
    <td>
      <strong>Scenario 1: Visualización de resumen de lotes</strong><br>
      Dado que el usuario ingresa al módulo de lotes, cuando se carga la pantalla, entonces se muestra un resumen con indicadores clave sobre los estados de los lotes.<br><br>
      <strong>Scenario 2: Sin alertas si no hay condiciones críticas</strong><br>
      Dado que no existen lotes vencidos ni próximos a vencer, cuando se carga el dashboard, entonces no se muestra el banner de alertas.
    </td>
    <td>Epic-02</td>
  </tr>

  <!-- US 11 -->
  <tr>
    <td>US-11</td>
    <td>Recibir alerta de caducidad de lote</td>
    <td>Como usuario quiero ser notificado cuando un lote esté próximo a vencer o ya haya vencido para poder tomar acciones como priorizar su uso o descartarlo.</td>
    <td>
      <strong>Scenario 1: Alerta de lote próximo a vencer</strong><br>
      Dado que uno o más lotes tienen fecha de caducidad dentro del rango próximo definido, cuando el usuario accede al dashboard de lotes, entonces se muestra una alerta indicando los lotes próximos a vencer.<br><br>
      <strong>Scenario 2: Alerta de lote vencido</strong><br>
      Dado que uno o más lotes tienen fecha de caducidad menor a la fecha actual, cuando el usuario accede al dashboard, entonces se muestra una alerta indicando los lotes vencidos.
    </td>
    <td>Epic-02</td>
  </tr>

  <!-- EPIC 03 -->
  <tr>
    <td><strong>Epic-03</strong></td>
    <td><strong>Proceso de suscripción</strong></td>
    <td>Como usuario quiero completar el proceso de suscripción para acceder a las funcionalidades de la plataforma según el plan elegido.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 13 -->
  <tr>
    <td>US-13</td>
    <td>Seleccionar plan de suscripción</td>
    <td>Como usuario quiero seleccionar un plan de suscripción para definir el tipo de acceso y beneficios que tendré dentro de la plataforma.</td>
    <td>
      <strong>Scenario 1: Selección de plan realizada correctamente</strong><br>
      Dado que el usuario visualiza los planes disponibles, cuando selecciona uno, entonces el sistema registra el plan y permite continuar con el proceso.<br><br>
      <strong>Scenario 2: Intento de continuar sin seleccionar un plan</strong><br>
      Dado que el usuario no selecciona ningún plan, cuando intenta continuar, entonces el sistema no permite avanzar y muestra un mensaje indicando que debe seleccionar un plan.
    </td>
    <td>Epic-03</td>
  </tr>

  <!-- US 14 -->
  <tr>
    <td>US-14</td>
    <td>Iniciar proceso de suscripción</td>
    <td>Como usuario quiero iniciar el proceso de suscripción para comenzar formalmente la contratación del plan previamente elegido.</td>
    <td>
      <strong>Scenario 1: Proceso de suscripción iniciado correctamente</strong><br>
      Dado que el usuario ya seleccionó un plan, cuando presiona la opción para iniciar la suscripción, entonces el sistema registra el inicio y habilita el formulario de facturación.<br><br>
      <strong>Scenario 2: Intento sin plan seleccionado</strong><br>
      Dado que el usuario no ha seleccionado un plan, cuando intenta iniciar el proceso, entonces el sistema no permite iniciar y muestra un mensaje solicitando seleccionar un plan primero.
    </td>
    <td>Epic-03</td>
  </tr>

  <!-- US 15 -->
  <tr>
    <td>US-15</td>
    <td>Registrar datos de facturación</td>
    <td>Como usuario quiero ingresar mis datos de facturación para que el sistema pueda procesar el cobro correspondiente a la suscripción.</td>
    <td>
      <strong>Scenario 1: Datos de facturación registrados correctamente</strong><br>
      Dado que el usuario completa correctamente los datos de facturación, cuando confirma el formulario, entonces el sistema registra los datos y permite continuar al paso de cobro.<br><br>
      <strong>Scenario 2: Datos de facturación inválidos</strong><br>
      Dado que el usuario completa incorrectamente los datos, cuando intenta confirmar, entonces el sistema no registra los datos y muestra un mensaje de datos inválidos.
    </td>
    <td>Epic-03</td>
  </tr>

  <!-- US 16 -->
  <tr>
    <td>US-16</td>
    <td>Procesar cobro de suscripción</td>
    <td>Como usuario quiero que el sistema procese el cobro de la suscripción para validar el pago del plan seleccionado.</td>
    <td>
      <strong>Scenario 1: Cobro procesado exitosamente</strong><br>
      Dado que el usuario ha registrado correctamente sus datos de facturación, cuando el sistema procesa el cobro, entonces el cobro es procesado exitosamente y se permite activar la suscripción.<br><br>
      <strong>Scenario 2: Error durante el procesamiento del cobro</strong><br>
      Dado que el usuario ha iniciado el proceso de pago, cuando ocurre un error (tarjeta rechazada, datos inválidos), entonces el sistema no activa la suscripción y muestra el motivo del error.
    </td>
    <td>Epic-03</td>
  </tr>

  <!-- US 17 -->
  <tr>
    <td>US-17</td>
    <td>Activar suscripción</td>
    <td>Como usuario quiero que mi suscripción sea activada una vez confirmado el cobro para acceder a las funcionalidades de la plataforma según el plan contratado.</td>
    <td>
      <strong>Scenario 1: Activación de suscripción exitosa</strong><br>
      Dado que el cobro fue procesado correctamente, cuando el sistema confirma el pago, entonces la suscripción se activa y el usuario obtiene acceso a las funcionalidades correspondientes.<br><br>
      <strong>Scenario 2: Suscripción no activada por pago no confirmado</strong><br>
      Dado que el cobro no fue confirmado, cuando el sistema intenta activar la suscripción, entonces permanece en estado pendiente y el usuario no accede a funcionalidades premium.
    </td>
    <td>Epic-03</td>
  </tr>

  <!-- EPIC 04 -->
  <tr>
    <td><strong>Epic-04</strong></td>
    <td><strong>Configuración de suscripción</strong></td>
    <td>Como usuario quiero visualizar y gestionar la configuración de mi suscripción para consultar su estado, renovarla o cancelarla según mis necesidades.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 18 -->
  <tr>
    <td>US-18</td>
    <td>Visualizar panel de suscripción</td>
    <td>Como usuario quiero visualizar el panel de suscripción para consultar de forma clara la información general relacionada con mi plan actual.</td>
    <td>
      <strong>Scenario 1: Panel de suscripción mostrado correctamente</strong><br>
      Dado que el usuario accede a la sección de suscripción, cuando el sistema carga la vista, entonces se muestra el panel con los datos generales de la suscripción.<br><br>
      <strong>Scenario 2: Usuario sin suscripción registrada</strong><br>
      Dado que el usuario no tiene una suscripción activa, cuando carga la vista, entonces el panel indica que no existe una suscripción disponible.
    </td>
    <td>Epic-04</td>
  </tr>

  <!-- US 19 -->
  <tr>
    <td>US-19</td>
    <td>Consultar estado de suscripción</td>
    <td>Como usuario quiero consultar el estado de mi suscripción para saber si se encuentra activa, vencida o cancelada.</td>
    <td>
      <strong>Scenario 1: Estado activa mostrado correctamente</strong><br>
      Dado que el usuario tiene una suscripción vigente, cuando consulta el estado, entonces el sistema muestra que la suscripción se encuentra activa.<br><br>
      <strong>Scenario 2: Estado vencida o cancelada mostrado correctamente</strong><br>
      Dado que el usuario tiene una suscripción vencida o cancelada, cuando consulta el estado, entonces el sistema muestra el estado correspondiente.
    </td>
    <td>Epic-04</td>
  </tr>

  <!-- US 20 -->
  <tr>
    <td>US-20</td>
    <td>Renovar suscripción</td>
    <td>Como usuario quiero renovar mi suscripción para extender la vigencia de mi acceso a la plataforma.</td>
    <td>
      <strong>Scenario 1: Renovación realizada correctamente</strong><br>
      Dado que el usuario tiene una suscripción activa o próxima a vencer, cuando selecciona la opción de renovar, entonces el sistema registra la renovación y actualiza la nueva fecha de vencimiento.<br><br>
      <strong>Scenario 2: Renovación no permitida</strong><br>
      Dado que el usuario no cuenta con una suscripción válida para renovación, cuando intenta renovar, entonces el sistema muestra un mensaje indicando que la renovación no puede realizarse.
    </td>
    <td>Epic-04</td>
  </tr>

  <!-- US 21 -->
  <tr>
    <td>US-21</td>
    <td>Solicitar cancelación de suscripción</td>
    <td>Como usuario quiero solicitar la cancelación de mi suscripción para detener su continuidad al finalizar el periodo vigente.</td>
    <td>
      <strong>Scenario 1: Solicitud de cancelación registrada correctamente</strong><br>
      Dado que el usuario tiene una suscripción activa, cuando solicita la cancelación, entonces el sistema registra la solicitud y mantiene el acceso hasta la fecha de vencimiento.<br><br>
      <strong>Scenario 2: Usuario cancela la operación antes de confirmar</strong><br>
      Dado que el usuario inició el proceso de cancelación, cuando decide no confirmar, entonces el sistema no registra la cancelación y la suscripción continúa sin cambios.
    </td>
    <td>Epic-04</td>
  </tr>

  <!-- US 22 -->
  <tr>
    <td>US-22</td>
    <td>Cancelar suscripción</td>
    <td>Como sistema quiero cancelar la suscripción al finalizar su periodo vigente para retirar el acceso del usuario a las funcionalidades premium.</td>
    <td>
      <strong>Scenario 1: Cancelación ejecutada correctamente</strong><br>
      Dado que existe una solicitud de cancelación registrada y la fecha de vencimiento ha sido alcanzada, cuando el sistema procesa el fin del periodo, entonces la suscripción es cancelada y el acceso premium es retirado.<br><br>
      <strong>Scenario 2: Suscripción aún dentro del periodo vigente</strong><br>
      Dado que la fecha de vencimiento aún no ha llegado, cuando el sistema verifica el estado, entonces la suscripción continúa activa hasta el final del periodo.
    </td>
    <td>Epic-04</td>
  </tr>

  <!-- EPIC 05 -->
  <tr>
    <td><strong>Epic-05</strong></td>
    <td><strong>Gestión de Transacciones y Operaciones de Venta</strong></td>
    <td>Como comerciante, quiero gestionar el proceso completo de registro de ventas, desde la selección de productos hasta la emisión del comprobante, para asegurar una operación ágil y sin errores.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 24 -->
  <tr>
    <td>US-24</td>
    <td>Buscar productos en el inventario y validar su tipo de medida</td>
    <td>Como cajero, quiero buscar productos del inventario para que el sistema valide si son por cantidad o peso y abrir la interfaz de ingreso correspondiente.</td>
    <td>
      <strong>Scenario 1: Búsqueda y validación de producto por peso</strong><br>
      Dado que el cajero ingresa un producto medido en Kg, cuando lo selecciona, entonces el sistema despliega el modal "Registrar Peso".<br><br>
      <strong>Scenario 2: Búsqueda y validación de producto por cantidad</strong><br>
      Dado que el cajero selecciona un producto registrado por unidades, entonces el sistema despliega el modal "Registrar Cantidad".<br><br>
      <strong>Scenario 3: Producto no encontrado</strong><br>
      Dado que el término ingresado no coincide con el inventario, cuando se ejecuta la búsqueda, entonces el sistema muestra "Producto no encontrado".
    </td>
    <td>Epic-05</td>
  </tr>

  <!-- US 25 -->
  <tr>
    <td>US-25</td>
    <td>Registrar la cantidad de unidades en el Ticket de Venta</td>
    <td>Como cajero, quiero ingresar el número de unidades de un producto seleccionado para añadirlo al detalle de la venta.</td>
    <td>
      <strong>Scenario 1: Confirmación de cantidad unitaria</strong><br>
      Dado que el modal "Registrar Cantidad" está abierto, cuando el cajero ingresa un número entero y presiona "Confirmar cantidad", entonces el sistema calcula el subtotal y añade el ítem al detalle.<br><br>
      <strong>Scenario 2: Validación de stock insuficiente por cantidad</strong><br>
      Dado que la cantidad solicitada es mayor al stock disponible, cuando el usuario intenta confirmar, entonces el sistema muestra "Stock insuficiente" y no permite añadir el producto al ticket.
    </td>
    <td>Epic-05</td>
  </tr>

  <!-- US 26 -->
  <tr>
    <td>US-26</td>
    <td>Capturar el peso mediante balanza IoT o ingreso manual</td>
    <td>Como cajero, quiero obtener el peso del producto automáticamente o por teclado para procesar la venta de productos al granel.</td>
    <td>
      <strong>Scenario 1: Captura automática</strong><br>
      Dado que el sistema detecta una balanza IoT conectada, cuando el cajero coloca el producto y el hardware envía la lectura, entonces el valor se carga automáticamente en el campo de peso.<br><br>
      <strong>Scenario 2: Registro de peso manual</strong><br>
      Dado que el sistema no detecta una balanza, cuando el cajero digita el peso y presiona "Confirmar Peso", entonces el sistema registra el dato y añade el producto al ticket.<br><br>
      <strong>Scenario 3: Validación de stock insuficiente por peso</strong><br>
      Dado que el peso solicitado es mayor al stock disponible, cuando el usuario intenta confirmar, entonces el sistema muestra "Stock insuficiente" y no permite añadir el producto.
    </td>
    <td>Epic-05</td>
  </tr>

  <!-- US 27 -->
  <tr>
    <td>US-27</td>
    <td>Gestionar el desglose y cálculo del Ticket de Venta</td>
    <td>Como cajero, quiero visualizar el desglose de productos (nombre, cantidad/peso, precio unitario y subtotal) para verificar que la información sea correcta antes de proceder al pago.</td>
    <td>
      <strong>Scenario 1: Actualización del detalle y monto total</strong><br>
      Dado que se han añadido productos al ticket, cuando el sistema procesa cada ítem, entonces muestra el desglose detallado y el monto total acumulado.<br><br>
      <strong>Scenario 2: Edición o eliminación de un ítem del detalle</strong><br>
      Dado que un producto ya está registrado en el detalle, cuando el cajero selecciona eliminarlo y el sistema confirma la acción, entonces actualiza la lista y recalcula el monto total inmediatamente.
    </td>
    <td>Epic-05</td>
  </tr>

  <!-- US 28 -->
  <tr>
    <td>US-28</td>
    <td>Seleccionar el método de pago para la transacción</td>
    <td>Como cajero, quiero elegir el medio por el cual está pagando el cliente (Efectivo o Tarjeta/Yape/Plin) para que el ingreso se registre en la categoría contable correcta.</td>
    <td>
      <strong>Scenario 1: Selección de método de pago exitosa</strong><br>
      Dado que el ticket tiene el monto calculado, cuando el cajero hace clic sobre "Efectivo" o "Tarjeta/Yape/Plin", entonces el sistema habilita el botón "Finalizar Venta y Emitir Boleta".<br><br>
      <strong>Scenario 2: Intento de finalización sin método de pago</strong><br>
      Dado que el cajero no ha marcado una opción de pago, cuando intenta finalizar la venta, entonces el sistema muestra "Por favor, seleccione un método de pago" y bloquea la emisión de la boleta.
    </td>
    <td>Epic-05</td>
  </tr>

  <!-- US 29 -->
  <tr>
    <td>US-29</td>
    <td>Finalizar la venta y emitir el comprobante de pago</td>
    <td>Como cajero, quiero procesar el pago y finalizar la venta en un solo paso para entregar el comprobante al cliente de forma inmediata.</td>
    <td>
      <strong>Scenario 1: Procesamiento exitoso del cierre de venta</strong><br>
      Dado que el ticket tiene productos y método de pago seleccionado, cuando el cajero presiona "Finalizar Venta y Emitir Boleta", entonces el sistema registra la información, genera el comprobante y limpia la interfaz para una nueva venta.<br><br>
      <strong>Scenario 2: Bloqueo de finalización por datos incompletos</strong><br>
      Dado que no hay productos en el ticket o falta el método de pago, cuando el cajero intenta finalizar, entonces el sistema muestra "No hay productos en el ticket" y mantiene la interfaz activa.
    </td>
    <td>Epic-05</td>
  </tr>

  <!-- EPIC 06 -->
  <tr>
    <td><strong>Epic-06</strong></td>
    <td><strong>Control de Ingresos y Monitoreo de Caja</strong></td>
    <td>Como dueño del negocio, quiero supervisar los flujos de dinero entrante en tiempo real, para tener visibilidad total sobre la liquidez y los métodos de pago utilizados durante el día.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 30 -->
  <tr>
    <td>US-30</td>
    <td>Clasificar automáticamente los ingresos según el medio de pago</td>
    <td>Como comerciante, quiero que cada venta finalizada sume su monto al acumulado del método correspondiente para tener visibilidad inmediata de cuánto dinero hay en efectivo y cuánto en digital.</td>
    <td>
      <strong>Scenario 1: Actualización del acumulado por método de pago</strong><br>
      Dado que se ha finalizado una venta, cuando el sistema detecta el método de pago utilizado, entonces actualiza visualmente el "Resumen de Caja" con los nuevos montos acumulados.<br><br>
      <strong>Scenario 2: Visualización del total general de ingresos</strong><br>
      Dado que los saldos por categoría han sido actualizados, cuando el comerciante visualiza el "Resumen de Caja", entonces el sistema muestra el "Total del Día" como la suma consolidada de todos los medios de pago.
    </td>
    <td>Epic-06</td>
  </tr>

  <!-- US 31 -->
  <tr>
    <td>US-31</td>
    <td>Monitorear el Resumen de Caja en tiempo real dentro del panel de ventas</td>
    <td>Como cajero, quiero visualizar de forma centralizada los ingresos acumulados por método de pago para tener un control inmediato de los saldos del día sin salir de la interfaz principal.</td>
    <td>
      <strong>Scenario 1: Visualización dinámica de ingresos operativos</strong><br>
      Dado que el cajero finaliza transacciones de forma sucesiva, cuando el sistema procesa los nuevos montos, entonces actualiza automáticamente los contadores de "Efectivo", "Tarjeta/Yape/Plin" y "Total del Día".<br><br>
      <strong>Scenario 2: Persistencia de saldos al cambiar de sección</strong><br>
      Dado que el cajero tiene un saldo acumulado y navega a otra sección, cuando regresa a "Ventas", entonces el sistema muestra los saldos actualizados tal como estaban antes de salir.
    </td>
    <td>Epic-06</td>
  </tr>

  <!-- EPIC 07 -->
  <tr>
    <td><strong>Epic-07</strong></td>
    <td><strong>Configurar Chatbot de WhatsApp Business</strong></td>
    <td>Como comerciante, quiero configurar y vincular el chatbot de WhatsApp Business desde el dashboard para activar la atención automatizada de clientes.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 32 -->
  <tr>
    <td>US-32</td>
    <td>Vincular cuenta de WhatsApp Business mediante código QR</td>
    <td>Como comerciante, quiero conectar mi cuenta de WhatsApp Business escaneando un código QR para activar el chatbot de atención a clientes desde el dashboard.</td>
    <td>
      <strong>Scenario 1: Mostrar código QR en primer acceso</strong><br>
      Dado que el comerciante no tiene ninguna cuenta vinculada, cuando accede a la sección de chatbot, entonces el sistema genera y muestra un código QR válido para iniciar la vinculación.<br><br>
      <strong>Scenario 2: Vinculación exitosa tras escaneo</strong><br>
      Dado que el comerciante escanea el código QR desde su WhatsApp Business, cuando el sistema confirma la conexión, entonces registra la vinculación, activa el chatbot y habilita la visualización de conversaciones.
    </td>
    <td>Epic-07</td>
  </tr>

  <!-- US 33 -->
  <tr>
    <td>US-33</td>
    <td>Consultar estado de vinculación del chatbot</td>
    <td>Como comerciante, quiero conocer el estado de conexión de mi WhatsApp Business para saber si el chatbot se encuentra activo o requiere reconexión.</td>
    <td>
      <strong>Scenario 1: Estado activo cuando la cuenta está vinculada</strong><br>
      Dado que el comerciante tiene una cuenta vinculada, cuando accede a la sección de chatbot, entonces el sistema muestra el estado como activo junto al número vinculado.<br><br>
      <strong>Scenario 2: Estado desconectado cuando la sesión expiró</strong><br>
      Dado que la sesión ha expirado o fue cerrada externamente, cuando el comerciante accede a la sección de chatbot, entonces el sistema muestra el estado como desconectado y habilita la opción de volver a vincular.
    </td>
    <td>Epic-07</td>
  </tr>

  <!-- EPIC 08 -->
  <tr>
    <td><strong>Epic-08</strong></td>
    <td><strong>Gestionar Conversaciones desde el Dashboard</strong></td>
    <td>Como comerciante, quiero visualizar y gestionar los chats de mis clientes directamente desde el dashboard para atenderlos sin salir de la plataforma.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 34 -->
  <tr>
    <td>US-34</td>
    <td>Visualizar conversaciones de clientes en el dashboard</td>
    <td>Como comerciante, quiero ver los chats que el bot ha tenido con mis clientes dentro del dashboard para tener visibilidad de todas las conversaciones activas sin usar WhatsApp directamente.</td>
    <td>
      <strong>Scenario 1: Conversaciones cargadas cuando existe actividad</strong><br>
      Dado que el comerciante tiene su WhatsApp Business vinculado, cuando accede a la sección de chatbot, entonces el sistema muestra la lista de conversaciones ordenada por la más reciente con el último mensaje visible.<br><br>
      <strong>Scenario 2: Mensaje informativo cuando no hay conversaciones</strong><br>
      Dado que ningún cliente ha iniciado una conversación con el bot, cuando el comerciante accede a la sección, entonces el sistema indica que aún no existen conversaciones registradas.
    </td>
    <td>Epic-08</td>
  </tr>

  <!-- US 35 -->
  <tr>
    <td>US-35</td>
    <td>Responder mensajes de clientes desde el dashboard</td>
    <td>Como comerciante, quiero enviar mensajes a mis clientes directamente desde el dashboard para gestionar conversaciones sin necesitar abrir WhatsApp.</td>
    <td>
      <strong>Scenario 1: Mensaje enviado correctamente al cliente</strong><br>
      Dado que el comerciante selecciona una conversación activa y redacta un mensaje, cuando confirma el envío, entonces el sistema envía el mensaje al cliente a través de WhatsApp y lo registra en el hilo de conversación.<br><br>
      <strong>Scenario 2: Envío bloqueado cuando el mensaje está vacío</strong><br>
      Dado que el comerciante intenta confirmar el envío sin haber redactado ningún contenido, entonces el sistema no procesa el envío y mantiene el estado de la conversación sin cambios.
    </td>
    <td>Epic-08</td>
  </tr>

  <!-- EPIC 09 -->
  <tr>
    <td><strong>Epic-09</strong></td>
    <td><strong>Procesar Pedidos mediante Bot Automático</strong></td>
    <td>Como sistema, quiero que el chatbot responda automáticamente a los clientes según el stock disponible del negocio para facilitar el proceso de pedido sin intervención manual del comerciante.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 36 -->
  <tr>
    <td>US-36</td>
    <td>Responder consulta de producto disponible</td>
    <td>Como sistema, quiero que el chatbot responda automáticamente al cliente con la información del producto solicitado cuando este existe en el inventario para iniciar el proceso de pedido sin intervención del comerciante.</td>
    <td>
      <strong>Scenario 1: Bot informa disponibilidad del producto solicitado</strong><br>
      Dado que el cliente envía el nombre de un producto y el sistema lo encuentra con stock mayor a cero, entonces el bot responde con nombre, precio y stock disponible, y ofrece al cliente agregarlo al pedido.<br><br>
      <strong>Scenario 2: Bot registra selección confirmada por el cliente</strong><br>
      Dado que el bot informó la disponibilidad y el cliente confirma la cantidad deseada, entonces el sistema registra la selección en el pedido en curso y consulta si desea agregar más productos.
    </td>
    <td>Epic-09</td>
  </tr>

  <!-- US 37 -->
  <tr>
    <td>US-37</td>
    <td>Sugerir alternativas ante producto no disponible</td>
    <td>Como sistema, quiero que el chatbot informe al cliente cuando un producto no está disponible y le sugiera otros productos del inventario para evitar que la conversación quede sin respuesta útil.</td>
    <td>
      <strong>Scenario 1: Bot sugiere alternativas cuando el producto no existe</strong><br>
      Dado que el producto solicitado no se encuentra o tiene stock igual a cero, cuando el sistema verifica la disponibilidad, entonces el bot informa que no está disponible y presenta alternativas con stock.<br><br>
      <strong>Scenario 2: Bot notifica cuando el inventario completo está agotado</strong><br>
      Dado que todos los productos tienen stock igual a cero, cuando el sistema verifica la disponibilidad general, entonces el bot informa que no hay productos disponibles e invita al cliente a intentarlo más tarde.
    </td>
    <td>Epic-09</td>
  </tr>

  <!-- US 38 -->
  <tr>
    <td>US-38</td>
    <td>Confirmar pedido con el cliente</td>
    <td>Como sistema, quiero que el chatbot presente un resumen del pedido al cliente y solicite confirmación antes de proceder al pago para asegurar que los productos y cantidades sean correctos.</td>
    <td>
      <strong>Scenario 1: Bot envía resumen y solicita confirmación</strong><br>
      Dado que el cliente indicó todos los productos y su dirección de entrega, cuando indica que no desea agregar más, entonces el sistema genera un resumen con productos, cantidades, total y dirección, y solicita confirmación.<br><br>
      <strong>Scenario 2: Sistema registra pedido tras confirmación del cliente</strong><br>
      Dado que el bot envió el resumen y el cliente confirma que el pedido es correcto, entonces el sistema registra el pedido con estado pendiente y envía las instrucciones de pago.
    </td>
    <td>Epic-09</td>
  </tr>

  <!-- EPIC 10 -->
  <tr>
    <td><strong>Epic-10</strong></td>
    <td><strong>Gestionar Pago Digital P2P</strong></td>
    <td>Como cliente y comerciante, queremos gestionar el envío y la validación de comprobantes de pago digitales (Yape/Plin) a través de WhatsApp y el dashboard, para garantizar una transacción segura y confirmada antes de finalizar la venta.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 39 -->
  <tr>
    <td>US-39</td>
    <td>Recibir instrucciones de pago por WhatsApp</td>
    <td>Como cliente, quiero recibir las instrucciones de pago a través del chatbot para saber cómo realizar la transferencia y completar mi pedido.</td>
    <td>
      <strong>Scenario 1: Bot envía instrucciones tras confirmación del pedido</strong><br>
      Dado que el cliente confirmó su pedido y el stock fue validado, cuando el sistema procesa la confirmación, entonces el bot envía el número Yape/Plin del comerciante, el monto total y el número de pedido como referencia.<br><br>
      <strong>Scenario 2: Sistema registra el evento de instrucción enviada</strong><br>
      Dado que el bot entrega las instrucciones de pago, cuando el sistema confirma la entrega del mensaje, entonces registra el evento con marca de tiempo para trazabilidad.
    </td>
    <td>Epic-10</td>
  </tr>

  <!-- US 40 -->
  <tr>
    <td>US-40</td>
    <td>Reportar comprobante de pago digital</td>
    <td>Como cliente, quiero enviar el comprobante de mi pago al chatbot para que el comerciante pueda verificarlo y confirmar mi pedido.</td>
    <td>
      <strong>Scenario 1: Sistema registra comprobante recibido y notifica al comerciante</strong><br>
      Dado que el cliente realizó el pago por Yape o Plin, cuando envía el comprobante al chatbot, entonces el sistema lo registra, actualiza el estado del pedido a pendiente de validación y notifica al comerciante.<br><br>
      <strong>Scenario 2: Bot envía recordatorio ante ausencia de reporte</strong><br>
      Dado que el cliente recibió las instrucciones de pago, cuando transcurren treinta minutos sin que reporte el comprobante, entonces el sistema envía un recordatorio y mantiene el pedido en estado esperando pago.
    </td>
    <td>Epic-10</td>
  </tr>

  <!-- US 41 -->
  <tr>
    <td>US-41</td>
    <td>Validar comprobante de pago desde el dashboard</td>
    <td>Como comerciante, quiero revisar el comprobante reportado por el cliente y aprobarlo o rechazarlo desde el dashboard para confirmar que el dinero fue recibido correctamente.</td>
    <td>
      <strong>Scenario 1: Comerciante visualiza comprobante y detalles del pedido</strong><br>
      Dado que el cliente reportó su comprobante, cuando el comerciante revisa el pedido, entonces el sistema muestra el comprobante, el monto y los detalles del pedido asociado.<br><br>
      <strong>Scenario 2: Sistema registra validación manual al aprobar el pago</strong><br>
      Dado que el comerciante verifica que el comprobante es correcto, cuando aprueba el pago, entonces el sistema registra la validación con marca de tiempo y continúa el flujo de confirmación.<br><br>
      <strong>Scenario 3: Sistema notifica al cliente al rechazar el pago</strong><br>
      Dado que el comerciante detecta que el comprobante es incorrecto, cuando lo rechaza indicando el motivo, entonces el sistema registra el rechazo y el bot notifica al cliente con los pasos a seguir.
    </td>
    <td>Epic-10</td>
  </tr>

  <!-- US 42 -->
  <tr>
    <td>US-42</td>
    <td>Notificar resultado de validación al cliente</td>
    <td>Como cliente, quiero recibir una notificación sobre el resultado de la validación de mi pago para saber si mi pedido fue confirmado o si debo realizar alguna acción adicional.</td>
    <td>
      <strong>Scenario 1: Bot confirma al cliente que el pago fue aprobado</strong><br>
      Dado que el comerciante aprueba el comprobante, cuando el sistema actualiza el estado del pedido, entonces el bot envía al cliente un mensaje confirmando que el pago fue recibido y el pedido está en proceso.<br><br>
      <strong>Scenario 2: Bot informa al cliente que el pago fue rechazado</strong><br>
      Dado que el comerciante rechaza el comprobante, cuando el sistema actualiza el estado, entonces el bot informa al cliente que el pago no fue validado, indica el motivo y solicita que reintente.
    </td>
    <td>Epic-10</td>
  </tr>

  <!-- EPIC 11 -->
  <tr>
    <td><strong>Epic-11</strong></td>
    <td><strong>Confirmar Venta y Emitir Comprobante</strong></td>
    <td>Como dueño de negocio, quiero que el sistema confirme el pedido tras la validación del pago, descuente el stock y emita un comprobante digital, para mantener el control financiero y brindar un respaldo de la compra al cliente.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 43 -->
  <tr>
    <td>US-43</td>
    <td>Confirmar pedido y descontar stock</td>
    <td>Como sistema, quiero confirmar el pedido automáticamente al aprobar el pago para actualizar el inventario en tiempo real y reflejar el consumo de stock.</td>
    <td>
      <strong>Scenario 1: Sistema actualiza inventario al confirmar el pedido</strong><br>
      Dado que el comerciante aprueba el comprobante de pago, cuando el sistema confirma el pedido, entonces actualiza el estado a confirmado y descuenta la cantidad correspondiente del stock de cada producto.<br><br>
      <strong>Scenario 2: Sistema sincroniza peso con balanza IoT para productos por peso</strong><br>
      Dado que el pedido incluye productos vendidos por peso, cuando el sistema descuenta el stock, entonces actualiza el peso disponible registrado en la balanza IoT.
    </td>
    <td>Epic-11</td>
  </tr>

  <!-- US 44 -->
  <tr>
    <td>US-44</td>
    <td>Registrar venta en el sistema</td>
    <td>Como comerciante, quiero que cada pedido confirmado quede registrado como venta en el sistema para mantener un control financiero preciso y trazable.</td>
    <td>
      <strong>Scenario 1: Sistema crea registro de venta al confirmar pedido</strong><br>
      Dado que el pedido ha sido confirmado tras la validación del pago, cuando el sistema procesa el cierre de la transacción, entonces crea un registro de venta con monto total, método de pago, productos vendidos y marca de tiempo.<br><br>
      <strong>Scenario 2: Sistema separa ingresos digitales de los ingresos en efectivo</strong><br>
      Dado que el método de pago fue Yape o Plin, cuando el sistema registra la venta, entonces asocia el monto al canal de pagos digitales, manteniéndolo separado del efectivo en caja.
    </td>
    <td>Epic-11</td>
  </tr>

  <!-- US 45 -->
  <tr>
    <td>US-45</td>
    <td>Emitir comprobante digital al cliente</td>
    <td>Como cliente, quiero recibir un comprobante de mi compra a través del chatbot para tener un respaldo de la transacción realizada.</td>
    <td>
      <strong>Scenario 1: Bot envía comprobante al cliente tras registrar la venta</strong><br>
      Dado que la venta ha sido registrada correctamente, cuando el sistema genera el comprobante, entonces el bot envía al cliente un resumen con número de pedido, productos, cantidades, monto total y fecha.<br><br>
      <strong>Scenario 2: Sistema marca el pedido como completado al emitir el comprobante</strong><br>
      Dado que el comprobante fue generado y enviado, cuando el sistema confirma la entrega, entonces registra el evento con marca de tiempo y actualiza el estado del pedido a completado.
    </td>
    <td>Epic-11</td>
  </tr>

  <!-- EPIC 12 -->
  <tr>
    <td><strong>Epic-12</strong></td>
    <td><strong>Manejar Flujos Alternativos y Restricciones</strong></td>
    <td>Como sistema de gestión, quiero manejar escenarios de excepción como falta de stock, tiempos de espera agotados y rechazos de pago, para proteger la integridad del inventario y evitar pérdidas económicas.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 46 -->
  <tr>
    <td>US-46</td>
    <td>Manejar stock insuficiente en pedido</td>
    <td>Como cliente, quiero ser notificado cuando un producto no tiene stock suficiente para poder ajustar mi pedido antes de proceder al pago.</td>
    <td>
      <strong>Scenario 1: Bot notifica al cliente sobre stock insuficiente</strong><br>
      Dado que el cliente solicita una cantidad mayor al stock disponible, cuando el sistema valida el inventario, entonces el bot informa qué producto no tiene stock suficiente y ofrece ajustar la cantidad o eliminarlo del pedido.<br><br>
      <strong>Scenario 2: Sistema actualiza el pedido con la nueva cantidad</strong><br>
      Dado que el bot informó al cliente sobre el stock insuficiente, cuando el cliente confirma una nueva cantidad menor o igual al stock disponible, entonces el sistema actualiza el pedido y continúa el flujo de forma normal.
    </td>
    <td>Epic-12</td>
  </tr>

  <!-- US 47 -->
  <tr>
    <td>US-47</td>
    <td>Cancelar pedido por expiración de tiempo de pago</td>
    <td>Como sistema, quiero cancelar automáticamente un pedido cuando el cliente no reporta el comprobante de pago en el tiempo establecido para liberar el stock reservado.</td>
    <td>
      <strong>Scenario 1: Sistema cancela el pedido y libera el stock al expirar el tiempo</strong><br>
      Dado que el cliente recibió las instrucciones de pago, cuando transcurren sesenta minutos sin que reporte el comprobante, entonces el sistema cancela el pedido, libera el stock reservado y notifica al cliente.<br><br>
      <strong>Scenario 2: Sistema registra el evento de cancelación para trazabilidad</strong><br>
      Dado que el pedido es cancelado por expiración, cuando el sistema actualiza el estado, entonces registra el evento de cancelación con el motivo y marca de tiempo correspondientes.
    </td>
    <td>Epic-12</td>
  </tr>

  <!-- US 48 -->
  <tr>
    <td>US-48</td>
    <td>Rechazar comprobante de pago inválido</td>
    <td>Como comerciante, quiero poder rechazar un comprobante de pago cuando sea incorrecto o sospechoso para proteger el negocio de transacciones fraudulentas.</td>
    <td>
      <strong>Scenario 1: Sistema revierte el estado del pedido al rechazar el comprobante</strong><br>
      Dado que el comerciante identifica un comprobante sospechoso o incorrecto, cuando lo rechaza indicando el motivo, entonces el sistema devuelve el pedido al estado "esperando pago" y el bot notifica al cliente.<br><br>
      <strong>Scenario 2: Sistema alerta al comerciante ante rechazos repetidos del mismo cliente</strong><br>
      Dado que el mismo cliente presenta comprobantes rechazados en dos ocasiones consecutivas, cuando el sistema detecta el patrón, entonces alerta al comerciante y bloquea el pedido para revisión manual.
    </td>
    <td>Epic-12</td>
  </tr>

  <!-- EPIC 13 -->
  <tr>
    <td><strong>Epic-13</strong></td>
    <td><strong>Technical Stories – Implementar RESTful API</strong></td>
    <td>Como equipo de desarrollo, queremos implementar una arquitectura de servicios RESTful segura y escalable para que todos los componentes de la plataforma intercambien datos de manera consistente.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 49 -->
  <tr>
    <td>US-49</td>
    <td>Conocer propuesta de valor en landing page</td>
    <td>Como visitante, quiero entender qué hace Entreprenly y cómo puede beneficiar a mi negocio para decidir si me interesa adquirirlo.</td>
    <td>
      <strong>Scenario 1: Visitante visualiza la propuesta de valor al cargar la página</strong><br>
      Dado que el visitante accede a la landing page, cuando la página termina de cargar, entonces el sistema muestra el headline principal, la propuesta de valor y los beneficios clave del producto.<br><br>
      <strong>Scenario 2: Visitante accede a la sección de funcionalidades</strong><br>
      Dado que el visitante navega por la landing page, cuando llega a la sección de funcionalidades, entonces el sistema presenta las características principales: chatbot WhatsApp, inventario, balanza IoT y dashboard financiero.
    </td>
    <td>Epic-13</td>
  </tr>

  <!-- US 50 -->
  <tr>
    <td>US-50</td>
    <td>Gestionar ciclo de vida de pedidos mediante API</td>
    <td>Como developer, quiero endpoints para crear y actualizar pedidos para que el chatbot y el dashboard intercambien información del pedido de forma automática y consistente.</td>
    <td>
      <strong>Scenario 1: Creación exitosa de pedido</strong><br>
      Dado que el developer envía una solicitud de creación con datos válidos, cuando el servidor valida el cuerpo, entonces el sistema responde con HTTP 201, retorna el ID del pedido, el estado pendiente y la marca de tiempo.<br><br>
      <strong>Scenario 2: Actualización de estado de pedido existente</strong><br>
      Dado que el developer envía una solicitud de actualización con estado válido, cuando el servidor procesa la solicitud, entonces el sistema responde con HTTP 200 y retorna el objeto del pedido actualizado.<br><br>
      <strong>Scenario 3: Solicitud sobre pedido inexistente</strong><br>
      Dado que el developer referencia un ID de pedido que no existe, cuando el servidor busca el recurso, entonces el sistema responde con HTTP 404 indicando que el pedido no fue encontrado.
    </td>
    <td>Epic-13</td>
  </tr>

  <!-- US 51 -->
  <tr>
    <td>US-51</td>
    <td>Validar y registrar pagos mediante API</td>
    <td>Como developer, quiero un endpoint para aprobar o rechazar pagos desde el dashboard para que el sistema actualice el inventario y notifique al cliente de forma automática.</td>
    <td>
      <strong>Scenario 1: Aprobación de pago con descuento de stock</strong><br>
      Dado que el developer envía una solicitud de aprobación con estado aprobado, cuando el servidor procesa la validación, entonces el sistema responde con HTTP 200, actualiza el pedido a confirmado y descuenta el stock correspondiente.<br><br>
      <strong>Scenario 2: Rechazo de pago con registro de motivo</strong><br>
      Dado que el developer envía una solicitud de rechazo con motivo especificado, cuando el servidor procesa el rechazo, entonces el sistema responde con HTTP 200 y registra el motivo en el historial del pago.<br><br>
      <strong>Scenario 3: Solicitud sobre pago inexistente</strong><br>
      Dado que el developer referencia un ID de pago que no existe, cuando el servidor busca el recurso, entonces el sistema responde con HTTP 404 indicando que el pago no fue encontrado.
    </td>
    <td>Epic-13</td>
  </tr>

  <!-- EPIC 14 -->
  <tr>
    <td><strong>Epic-14</strong></td>
    <td><strong>Inicio de sesión y registro</strong></td>
    <td>Como usuario quiero poder registrarme, verificar mi cuenta, iniciar sesión y recuperar mi contraseña para acceder de forma segura a la plataforma.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 52 -->
  <tr>
    <td>US-52</td>
    <td>Registrar cuenta con email</td>
    <td>Como usuario anónimo, quiero registrarme con mi email y contraseña para crear una cuenta en Entreprenly.</td>
    <td>
      <strong>Scenario 1: Registro exitoso</strong><br>
      Dado que el usuario ingresa un email no registrado y una contraseña válida, cuando envía el formulario, entonces el sistema crea la cuenta, envía un email de verificación y muestra un mensaje de confirmación.<br><br>
      <strong>Scenario 2: Email ya registrado</strong><br>
      Dado que el usuario ingresa un email que ya existe, cuando envía el formulario, entonces el sistema muestra un mensaje de error indicando que el email ya está en uso.<br><br>
      <strong>Scenario 3: Datos inválidos</strong><br>
      Dado que la contraseña no cumple los requisitos mínimos, cuando envía el formulario, entonces el sistema muestra los errores de validación sin crear la cuenta.
    </td>
    <td>Epic-14</td>
  </tr>

  <!-- US 53 -->
  <tr>
    <td>US-53</td>
    <td>Verificar email</td>
    <td>Como usuario registrado, quiero verificar mi email mediante el enlace enviado a mi correo para activar mi cuenta.</td>
    <td>
      <strong>Scenario 1: Verificación exitosa</strong><br>
      Dado que el usuario hace clic en el enlace de verificación válido, cuando el sistema valida el token, entonces la cuenta queda activa y el usuario es redirigido al dashboard principal.<br><br>
      <strong>Scenario 2: Token expirado</strong><br>
      Dado que el token ha expirado, cuando el sistema intenta validarlo, entonces muestra un mensaje de error y ofrece la opción de reenviar el email de verificación.<br><br>
      <strong>Scenario 3: Token inválido</strong><br>
      Dado que el token está malformado, cuando el sistema intenta procesarlo, entonces muestra un mensaje de error indicando que el enlace no es válido.
    </td>
    <td>Epic-14</td>
  </tr>

  <!-- US 54 -->
  <tr>
    <td>US-54</td>
    <td>Iniciar sesión con credenciales</td>
    <td>Como usuario registrado, quiero iniciar sesión con mi email y contraseña para acceder al dashboard de Entreprenly.</td>
    <td>
      <strong>Scenario 1: Inicio de sesión exitoso</strong><br>
      Dado que el usuario ingresa credenciales válidas, cuando envía el formulario, entonces el sistema genera un JWT, inicia la sesión y redirige al dashboard principal.<br><br>
      <strong>Scenario 2: Credenciales inválidas</strong><br>
      Dado que el usuario ingresa una contraseña incorrecta, cuando envía el formulario, entonces el sistema muestra un mensaje de error sin revelar cuál campo es incorrecto.<br><br>
      <strong>Scenario 3: Cuenta bloqueada por intentos fallidos</strong><br>
      Dado que el usuario ha fallado 5 intentos consecutivos, cuando intenta iniciar sesión nuevamente, entonces el sistema bloquea la cuenta y notifica al usuario por email.
    </td>
    <td>Epic-14</td>
  </tr>

  <!-- US 55 -->
  <tr>
    <td>US-55</td>
    <td>Iniciar sesión con Google OAuth</td>
    <td>Como usuario anónimo, quiero iniciar sesión con mi cuenta de Google para acceder a Entreprenly sin necesidad de crear credenciales nuevas.</td>
    <td>
      <strong>Scenario 1: OAuth exitoso con cuenta nueva</strong><br>
      Dado que el usuario inicia el flujo OAuth con una cuenta de Google no registrada previamente, cuando Google autoriza el acceso, entonces el sistema crea una nueva cuenta vinculada al proveedor e inicia la sesión.<br><br>
      <strong>Scenario 2: OAuth exitoso con cuenta existente</strong><br>
      Dado que el usuario inicia el flujo OAuth con un email ya registrado, cuando Google devuelve el token, entonces el sistema vincula el proveedor a la cuenta existente e inicia la sesión.<br><br>
      <strong>Scenario 3: OAuth denegado por el usuario</strong><br>
      Dado que el usuario cancela la autorización en la pantalla de Google, cuando el flujo es interrumpido, entonces el sistema redirige al usuario a la pantalla de login sin crear ninguna cuenta.
    </td>
    <td>Epic-14</td>
  </tr>

  <!-- US 56 -->
  <tr>
    <td>US-56</td>
    <td>Recuperar contraseña</td>
    <td>Como usuario registrado, quiero recuperar el acceso a mi cuenta mediante un enlace enviado a mi email para restablecer mi contraseña.</td>
    <td>
      <strong>Scenario 1: Reset exitoso</strong><br>
      Dado que el usuario solicita el reset con un email registrado y confirma la nueva contraseña desde el enlace recibido, cuando el sistema procesa la solicitud, entonces actualiza la contraseña, invalida todas las sesiones anteriores y redirige al login.<br><br>
      <strong>Scenario 2: Token de reset expirado</strong><br>
      Dado que el usuario accede al enlace después de que el token ha expirado, cuando el sistema intenta validarlo, entonces muestra un mensaje de error y solicita generar un nuevo enlace.<br><br>
      <strong>Scenario 3: Email no registrado</strong><br>
      Dado que el usuario solicita el reset con un email que no existe, cuando envía el formulario, entonces el sistema responde con un mensaje genérico sin confirmar ni negar la existencia del email.
    </td>
    <td>Epic-14</td>
  </tr>

  <!-- US 57 -->
  <tr>
    <td>US-57</td>
    <td>Cerrar sesión</td>
    <td>Como usuario autenticado, quiero cerrar mi sesión para que el sistema revoque mi token y me redirija a la pantalla de login.</td>
    <td>
      <strong>Scenario 1: Cierre de sesión exitoso</strong><br>
      Dado que el usuario hace clic en la opción de cerrar sesión, cuando el sistema procesa la solicitud, entonces revoca el JWT activo y redirige al usuario a la pantalla de login.<br><br>
      <strong>Scenario 2: Intento de acceso tras cerrar sesión</strong><br>
      Dado que el usuario ha cerrado su sesión y el token ha sido revocado, cuando intenta acceder a una ruta protegida, entonces el sistema rechaza la solicitud y redirige al login.
    </td>
    <td>Epic-14</td>
  </tr>

  <!-- EPIC 15 -->
  <tr>
    <td><strong>Epic-15</strong></td>
    <td><strong>Perfil y configuración</strong></td>
    <td>Como usuario quiero gestionar mi perfil y preferencias personales para personalizar mi experiencia dentro de la plataforma.</td>
    <td></td>
    <td></td>
  </tr>

  <!-- US 58 -->
  <tr>
    <td>US-58</td>
    <td>Visualizar perfil actual</td>
    <td>Como usuario autenticado, quiero visualizar mi perfil actual para revisar mis datos registrados en la plataforma.</td>
    <td>
      <strong>Scenario 1: Visualización exitosa</strong><br>
      Dado que el usuario navega a la sección de perfil, cuando el sistema carga los datos, entonces muestra nombre, bio, foto de perfil, email y preferencias actuales del usuario.<br><br>
      <strong>Scenario 2: Sesión expirada</strong><br>
      Dado que la sesión del usuario ha expirado, cuando intenta acceder a la sección de perfil, entonces el sistema redirige al login.
    </td>
    <td>Epic-15</td>
  </tr>

  <!-- US 59 -->
  <tr>
    <td>US-59</td>
    <td>Actualizar nombre y biografía</td>
    <td>Como usuario autenticado, quiero actualizar mi nombre y biografía para mantener mi perfil al día.</td>
    <td>
      <strong>Scenario 1: Actualización exitosa</strong><br>
      Dado que el usuario edita su nombre y/o bio con datos válidos, cuando guarda los cambios, entonces el sistema actualiza los datos y muestra el perfil con la información nueva.<br><br>
      <strong>Scenario 2: Campo obligatorio vacío</strong><br>
      Dado que el usuario deja el campo de nombre vacío, cuando intenta guardar, entonces el sistema muestra un error de validación sin guardar los cambios.
    </td>
    <td>Epic-15</td>
  </tr>

  <!-- US 60 -->
  <tr>
    <td>US-60</td>
    <td>Subir foto de perfil</td>
    <td>Como usuario autenticado, quiero subir una foto de perfil para personalizar mi cuenta en la plataforma.</td>
    <td>
      <strong>Scenario 1: Subida exitosa</strong><br>
      Dado que el usuario selecciona una imagen con formato y tamaño permitidos, cuando la sube al sistema, entonces el servicio de almacenamiento guarda el archivo, actualiza la URL del avatar y muestra la nueva foto en el perfil.<br><br>
      <strong>Scenario 2: Formato de imagen no permitido</strong><br>
      Dado que el usuario intenta subir un archivo con formato no soportado, cuando el sistema valida el archivo, entonces muestra un mensaje de error indicando los formatos aceptados sin guardar el archivo.<br><br>
      <strong>Scenario 3: Tamaño de archivo excedido</strong><br>
      Dado que el usuario intenta subir una imagen que supera el tamaño máximo, cuando el sistema valida el archivo, entonces muestra un mensaje de error indicando el límite de tamaño.
    </td>
    <td>Epic-15</td>
  </tr>

  <!-- US 61 -->
  <tr>
    <td>US-61</td>
    <td>Cambiar email con re-verificación</td>
    <td>Como usuario autenticado, quiero cambiar mi email y verificarlo para mantener mis datos de contacto actualizados.</td>
    <td>
      <strong>Scenario 1: Cambio de email exitoso</strong><br>
      Dado que el usuario solicita cambiar su email a uno no registrado previamente y confirma desde el enlace enviado, entonces el sistema actualiza el email y lo marca como verificado.<br><br>
      <strong>Scenario 2: Nuevo email ya en uso</strong><br>
      Dado que el usuario ingresa un email que ya pertenece a otra cuenta, cuando intenta guardar el cambio, entonces el sistema muestra un mensaje de error sin actualizar el email.<br><br>
      <strong>Scenario 3: Confirmación desde enlace expirado</strong><br>
      Dado que el usuario hace clic en el enlace de confirmación después de que ha expirado, cuando el sistema valida el token, entonces muestra un mensaje de error y ofrece reenviar el email de confirmación.
    </td>
    <td>Epic-15</td>
  </tr>

  <!-- US 62 -->
  <tr>
    <td>US-62</td>
    <td>Cambiar contraseña</td>
    <td>Como usuario autenticado, quiero cambiar mi contraseña para mantener la seguridad de mi cuenta.</td>
    <td>
      <strong>Scenario 1: Cambio exitoso</strong><br>
      Dado que el usuario ingresa su contraseña actual correcta y una nueva contraseña válida, cuando guarda el cambio, entonces el sistema actualiza la contraseña e invalida todas las sesiones activas excepto la actual.<br><br>
      <strong>Scenario 2: Contraseña actual incorrecta</strong><br>
      Dado que el usuario ingresa una contraseña actual incorrecta, cuando intenta guardar, entonces el sistema muestra un error de validación sin actualizar la contraseña.<br><br>
      <strong>Scenario 3: Nueva contraseña no cumple requisitos</strong><br>
      Dado que el usuario ingresa una nueva contraseña que no cumple los requisitos mínimos, cuando intenta guardar, entonces el sistema muestra los requisitos incumplidos sin aplicar el cambio.
    </td>
    <td>Epic-15</td>
  </tr>

  <!-- US 63 -->
  <tr>
    <td>US-63</td>
    <td>Configurar preferencias de idioma, zona horaria y tema</td>
    <td>Como usuario autenticado, quiero configurar mi idioma, zona horaria y tema visual para adaptar la plataforma a mis preferencias.</td>
    <td>
      <strong>Scenario 1: Cambio de idioma exitoso</strong><br>
      Dado que el usuario selecciona un idioma disponible, cuando guarda la preferencia, entonces el sistema actualiza el idioma de la interfaz de forma inmediata.<br><br>
      <strong>Scenario 2: Cambio de zona horaria exitoso</strong><br>
      Dado que el usuario selecciona una zona horaria de la lista disponible, cuando guarda la preferencia, entonces el sistema la almacena y la aplica en las fechas mostradas.<br><br>
      <strong>Scenario 3: Cambio de tema exitoso</strong><br>
      Dado que el usuario selecciona el tema claro u oscuro, cuando guarda la preferencia, entonces el sistema aplica el tema de forma inmediata y lo persiste para futuras sesiones.
    </td>
    <td>Epic-15</td>
  </tr>

  <!-- US 64 -->
  <tr>
    <td>US-64</td>
    <td>Configurar notificaciones</td>
    <td>Como usuario autenticado, quiero configurar mis preferencias de notificación para recibir solo los avisos que me sean relevantes.</td>
    <td>
      <strong>Scenario 1: Guardado exitoso de preferencias</strong><br>
      Dado que el usuario activa o desactiva tipos de notificación disponibles, cuando guarda los cambios, entonces el sistema almacena las preferencias y las aplica en los envíos futuros.<br><br>
      <strong>Scenario 2: Sin cambios realizados</strong><br>
      Dado que el usuario accede a la sección de notificaciones sin modificar nada, cuando sale de la sección, entonces el sistema mantiene las preferencias anteriores sin alteración.
    </td>
    <td>Epic-15</td>
  </tr>

  </tbody>
</table>

## 3.2. Impact Mapping

_Contenido por agregar._

## 3.3. Product Backlog

_Contenido por agregar._