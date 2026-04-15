# Capítulo III: Requirements Specification

## 3.1. User Stories

<!-- Epics-->
<div align="center">
<table>
  <tr>
    <th>Epic-01</th>
    <th>Gestión de inventario</th>
  </tr>

  <tr>
    <td colspan="2" >
      <strong >Descripción:</strong>
      Como usuario quiero gestionar mi inventario (lotes y productos) para visualizar los datos con mayor claridad.
    </td>
  </tr>

  <tr>
    <td align="center">1</td>
    <td align="center">Agregar productos</td>
  </tr>
  <tr>
    <td align="center">2</td>
    <td align="center">Editar lotes</td>
  </tr>
  <tr>
    <td align="center">3</td>
    <td align="center">Agregar lotes</td>
  </tr>
  <tr>
    <td align="center">4</td>
    <td align="center">Eliminar lotes</td>
  </tr>
  <tr>
    <td align="center">10</td>
    <td align="center">Visualizar detalles de producto</td>
  </tr>
  <tr>
    <td align="center">5</td>
    <td align="center">Editar productos</td>
  </tr>
  <tr>
    <td align="center">6</td>
    <td align="center">Visualizar detalles de lotes</td>
  </tr>
  <tr>
    <td align="center">12</td>
    <td align="center">Buscar productos</td>
  </tr>
  <tr>
    <td align="center">23</td>
    <td align="center">Crear lotes</td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>Epic-02</th>
    <th>
      Notificaciones de inventario
    </th>
  </tr>

  <tr>
    <td colspan="2">
      <strong>Descripción:</strong>
      Como usuario quiero que el sistema me notifique el estado de mis lotes para organizarme mejor.
    </td>
  </tr>

  <tr>
    <td align="center">7</td>
    <td align="center">Detectar stock agotado</td>
  </tr>
  <tr>
    <td align="center">8</td>
    <td align="center">Mostrar alertas de estado al visualizar detalles</td>
  </tr>
  
  <tr>
    <td align="center">9</td>
    <td align="center">Visualizar dashboard de lotes</td>
  </tr>

  <tr>
    <td align="center">11</td>
    <td align="center">Recibir alerta de caducidad de lote</td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>Epic-03</th>
    <th>Proceso de suscripción</th>
  </tr>

  <tr>
    <td colspan="2">
      <strong>Descripción:</strong>
      Como usuario quiero completar el proceso de suscripción para acceder a las funcionalidades de la plataforma según el plan elegido.
    </td>
  </tr>

  <tr>
    <td align="center">13</td>
    <td align="center">Seleccionar plan de suscripción</td>
  </tr>
  <tr>
    <td align="center">14</td>
    <td align="center">Iniciar proceso de suscripción</td>
  </tr>
  <tr>
    <td align="center">15</td>
    <td align="center">Registrar datos de facturación</td>
  </tr>
  <tr>
    <td align="center">16</td>
    <td align="center">Procesar cobro de suscripción</td>
  </tr>
  <tr>
    <td align="center">17</td>
    <td align="center">Activar suscripción</td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>Epic-04</th>
    <th>Configuración de suscripción</th>
  </tr>

  <tr>
    <td colspan="2">
      <strong>Descripción:</strong>
      Como usuario quiero visualizar y gestionar la configuración de mi suscripción para consultar su estado, renovarla o cancelarla según mis necesidades.
    </td>
  </tr>

  <tr>
    <td align="center">18</td>
    <td align="center">Visualizar panel de suscripción</td>
  </tr>
  <tr>
    <td align="center">19</td>
    <td align="center">Consultar estado de suscripción</td>
  </tr>
  <tr>
    <td align="center">20</td>
    <td align="center">Renovar suscripción</td>
  </tr>
  <tr>
    <td align="center">21</td>
    <td align="center">Solicitar cancelación de suscripción</td>
  </tr>
  <tr>
    <td align="center">22</td>
    <td align="center">Cancelar suscripción</td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>Epic-05</th>
    <th>Gestión de Transacciones y Operaciones de Venta</th>
  </tr>

  <tr>
    <td colspan="2">
      <strong>Descripción:</strong>
      Como comerciante, quiero gestionar el proceso completo de registro de ventas, desde la selección de productos hasta la emisión del comprobante, para asegurar una operación ágil y sin errores.
    </td>
  </tr>

  <tr>
    <td align="center">24</td>
    <td align="center">Buscar productos en el inventario y validar su tipo de medida</td>
  </tr>
  <tr>
    <td align="center">25</td>
    <td align="center">Registrar la cantidad de unidades en el Ticket de Venta</td>
  </tr>
  <tr>
    <td align="center">26</td>
    <td align="center">Capturar el peso mediante balanza IoT o ingreso manual</td>
  </tr>
  <tr>
    <td align="center">27</td>
    <td align="center">Gestionar el desglose y cálculo del Ticket de Venta</td>
  </tr>

  <tr>
    <td align="center">28</td>
    <td align="center">Seleccionar el método de pago para la transacción</td>
  </tr>

  <tr>
    <td align="center">29</td>
    <td align="center">Finalizar la venta, registrar la transacción y emitir el comprobante</td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>Epic-06</th>
    <th>Control de Ingresos y Monitoreo de Caja</th>
  </tr>

  <tr>
    <td colspan="2">
      <strong>Descripción:</strong>
      Como dueño del negocio, quiero supervisar los flujos de dinero entrante en tiempo real, para tener visibilidad total sobre la liquidez y los métodos de pago utilizados durante el día.
    </td>
  </tr>

  <tr>
    <td align="center">30</td>
    <td align="center">Clasificar automáticamente los ingresos según el medio de pago</td>
  </tr>

  <tr>
    <td align="center">31</td>
    <td align="center">Monitorear el Resumen de Caja en tiempo real dentro del panel de ventas</td>
  </tr>
  
</table>
<br><br>
 
<table>
  <tr>
    <th>Epic-07</th>
    <th>Configurar Chatbot de WhatsApp Business</th>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Descripción:</strong><br></br>
      Como comerciante, quiero configurar y vincular el chatbot de WhatsApp Business desde el dashboard para activar la atención automatizada de clientes.
    </td>
  </tr>
  <tr>
    <td align="center">32</td>
    <td align="center">Vincular cuenta de WhatsApp Business mediante código QR</td>
  </tr>
  <tr>
    <td align="center">33</td>
    <td align="center">Consultar estado de vinculación del chatbot</td>
  </tr>
</table>
<br></br>

<table>
  <tr>
    <th>Epic-08</th>
    <th>Gestionar Conversaciones desde el Dashboard</th>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Descripción:</strong><br></br>
      Como comerciante, quiero visualizar y gestionar los chats de mis clientes directamente desde el dashboard para atenderlos sin salir de la plataforma.
    </td>
  </tr>
  <tr>
    <td align="center">34</td>
    <td align="center">Visualizar conversaciones de clientes en el dashboard</td>
  </tr>
  <tr>
    <td align="center">35</td>
    <td align="center">Responder mensajes de clientes desde el dashboard</td>
  </tr>
</table>
<br></br>

<table>
  <tr>
    <th>Epic-09</th>
    <th>Procesar Pedidos mediante Bot Automático</th>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Descripción:</strong><br></br>
      Como sistema, quiero que el chatbot responda automáticamente a los clientes según el stock disponible del negocio para facilitar el proceso de pedido sin intervención manual del comerciante.
    </td>
  </tr>
  <tr>
    <td align="center">36</td>
    <td align="center">Responder consulta de producto disponible</td>
  </tr>
  <tr>
    <td align="center">37</td>
    <td align="center">Sugerir alternativas ante producto no disponible</td>
  </tr>
  <tr>
    <td align="center">38</td>
    <td align="center">Confirmar pedido con el cliente</td>
  </tr>
</table>
<br></br>

<table>
  <tr>
    <th>Epic-10</th>
    <th>Gestionar Pago Digital P2P</th>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Descripción:</strong><br></br>
      Como cliente y comerciante, queremos gestionar el envío y la validación de comprobantes de pago digitales (Yape/Plin) a través de WhatsApp y el dashboard, para garantizar una transacción segura y confirmada antes de finalizar la venta.
    </td>
  </tr>
  <tr>
    <td align="center">39</td>
    <td align="center">Recibir instrucciones de pago por WhatsApp</td>
  </tr>
  <tr>
    <td align="center">40</td>
    <td align="center">Reportar comprobante de pago digital</td>
  </tr>
  <tr>
    <td align="center">41</td>
    <td align="center">Validar comprobante de pago desde el dashboard</td>
  </tr>
  <tr>
    <td align="center">42</td>
    <td align="center">Notificar resultado de validación al cliente</td>
  </tr>
</table>
<br></br>

<table>
  <tr>
    <th>Epic-11</th>
    <th>Confirmar Venta y Emitir Comprobante</th>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Descripción:</strong><br></br>
      Como dueño de negocio, quiero que el sistema confirme el pedido tras la validación del pago, descuente el stock y emita un comprobante digital, para mantener el control financiero y brindar un respaldo de la compra al cliente.
    </td>
  </tr>
  <tr>
    <td align="center">43</td>
    <td align="center">Confirmar pedido y descontar stock</td>
  </tr>
  <tr>
    <td align="center">44</td>
    <td align="center">Registrar venta en el sistema</td>
  </tr>
  <tr>
    <td align="center">45</td>
    <td align="center">Emitir comprobante digital al cliente</td>
  </tr>
</table>
<br></br>

<table>
  <tr>
    <th>Epic-12</th>
    <th>Manejar Flujos Alternativos y Restricciones</th>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Descripción:</strong><br></br>
      Como sistema de gestión, quiero manejar escenarios de excepción como falta de stock, tiempos de espera agotados y rechazos de pago, para proteger la integridad del inventario y evitar pérdidas económicas.
    </td>
  </tr>
  <tr>
    <td align="center">46</td>
    <td align="center">Manejar stock insuficiente en pedido</td>
  </tr>
  <tr>
    <td align="center">47</td>
    <td align="center">Cancelar pedido por expiración de tiempo de pago</td>
  </tr>
  <tr>
    <td align="center">48</td>
    <td align="center">Rechazar comprobante de pago inválido</td>
  </tr>
</table>
<br></br>

<table>
  <tr>
    <th>Epic-13</th>
    <th>Technical Stories – Implementar RESTful API</th>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Descripción:</strong><br></br>
      Como equipo de desarrollo, queremos implementar una arquitectura de servicios RESTful segura y escalable para que todos los componentes de la plataforma intercambien datos de manera consistente.
    </td>
  </tr>
  <tr>
    <td align="center">49</td>
    <td align="center">Conocer propuesta de valor en landing page</td>
  </tr>
  <tr>
    <td align="center">50</td>
    <td align="center">Gestionar ciclo de vida de pedidos mediante API</td>
  </tr>
  <tr>
    <td align="center">51</td>
    <td align="center">Validar y registrar pagos mediante API</td>
  </tr>
</table>
<br></br>

<table>
  <tr>
    <th>Epic-14</th>
    <th>Inicio de sesión y registro</th>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Descripción:</strong>
      Como usuario quiero poder registrarme, verificar mi cuenta, iniciar sesión y recuperar mi contraseña para acceder de forma segura a la plataforma.
    </td>
  </tr>
  <tr>
    <td align="center">52</td>
    <td align="center">Registrar cuenta con email</td>
  </tr>
  <tr>
    <td align="center">53</td>
    <td align="center">Verificar email</td>
  </tr>
  <tr>
    <td align="center">54</td>
    <td align="center">Iniciar sesión con credenciales</td>
  </tr>
  <tr>
    <td align="center">55</td>
    <td align="center">Iniciar sesión con Google OAuth</td>
  </tr>
  <tr>
    <td align="center">56</td>
    <td align="center">Recuperar contraseña</td>
  </tr>
  <tr>
    <td align="center">57</td>
    <td align="center">Cerrar sesión</td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>Epic-15</th>
    <th>Perfil y configuración</th>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Descripción:</strong>
      Como usuario quiero gestionar mi perfil y preferencias personales para personalizar mi experiencia dentro de la plataforma.
    </td>
  </tr>
  <tr>
    <td align="center">58</td>
    <td align="center">Visualizar perfil actual</td>
  </tr>
  <tr>
    <td align="center">59</td>
    <td align="center">Actualizar nombre y biografía</td>
  </tr>
  <tr>
    <td align="center">60</td>
    <td align="center">Subir foto de perfil</td>
  </tr>
  <tr>
    <td align="center">61</td>
    <td align="center">Cambiar email con re-verificación</td>
  </tr>
  <tr>
    <td align="center">62</td>
    <td align="center">Cambiar contraseña</td>
  </tr>
  <tr>
    <td align="center">63</td>
    <td align="center">Configurar preferencias de idioma, zona horaria y tema</td>
  </tr>
  <tr>
    <td align="center">64</td>
    <td align="center">Configurar notificaciones</td>
  </tr>
</table>

<!-- US-->

<br><br>

<table>
<tr>
<th>User Story</th>
<th>01</th>
<th>Epic ID</th>
<th>01</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Agregar productos</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero agregar productos para gestionar mi inventario de manera eficiente.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Agregar producto correctamente</strong><br>
Dado que el usuario está en el formulario de productos<br>
Cuando ingrese los datos correctamente<br>
Y presione el botón “Guardar”<br>
Entonces el producto se registrará exitosamente<br><br>

<strong>Scenario 2: Validación de datos</strong><br>
Dado que el usuario está en el formulario de productos<br>
Cuando deje campos obligatorios vacíos<br>
Y presione el botón “Guardar”<br>
Entonces el sistema mostrará mensajes de error

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>02</th>
<th>Epic ID</th>
<th>01</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Editar lotes</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero editar los lotes para actualizar los datos del inventario.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Editar lote correctamente</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y selecciona un lote existente<br>
Cuando modifique los datos correctamente<br>
Y presione el botón “Guardar”<br>
Entonces los cambios del lote se actualizarán exitosamente<br><br>

<strong>Scenario 2: Validación al editar lote</strong><br>
Dado que el usuario está editando un lote<br>
Cuando ingrese datos inválidos o deje campos obligatorios vacíos<br>
Y presione el botón “Guardar”<br>
Entonces el sistema mostrará mensajes de error y no guardará los cambios

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>03</th>
<th>Epic ID</th>
<th>01</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Agregar lotes</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero agregar lotes para gestionar correctamente las cantidades, fechas de vencimiento
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Agregar lote correctamente</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y selecciona un lote existente<br>
Cuando ingrese una cantidad, fecha válida<br>
Y presione el botón “Agregar”<br>
Entonces el nuevo lote se agregará exitosamente.<br><br>

<strong>Scenario 2: Validación al agregar lote</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y selecciona un lote existente<br>
Cuando ingrese una cantidad, fecha válida<br>
Y presione el botón “Agregar”<br>
Entonces saldrá un mensaje de error por campo inválido

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>04</th>
<th>Epic ID</th>
<th>01</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Eliminar lotes</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero eliminar lotes para deshacerme de los lotes que no me sirvan
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Eliminar lote correctamente</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y selecciona un lote existente<br>
Cuando presione el botón “Eliminar”<br>
Entonces el lote se eliminará exitosamente<br><br>

<strong>Scenario 2: Validación al eliminar lote</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y selecciona un lote existente<br>
Cuando presione el botón “Eliminar”<br>
Entonces saldrá un mensaje de error de no haber seleccionado un lote

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>05</th>
<th>Epic ID</th>
<th>01</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Editar productos</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero editar productos para actualizar los datos en el inventario
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Producto editado correctamente</strong><br>
Dado que el usuario está en la sección de productos<br>
Y selecciona un producto existente<br>
Cuando presione el botón “Editar”<br>
Entonces el producto se actualizará exitosamente<br><br>

<strong>Scenario 2: Validación al editar productos</strong><br>
Dado que el usuario está en la sección de productos<br>
Y no selecciona un producto existente<br>
Cuando presione el botón “Editar”<br>
Entonces el sistema mostrará mensajes de error<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>06</th>
<th>Epic ID</th>
<th>01</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Visualizar detalles de lotes</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero visualizar los detalles de los lotes para poder gestionar mejor el inventario
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Detalles de lote mostrados correctamente</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y selecciona un lote existente<br>
Cuando presione el botón “Ver Detalles”<br>
Entonces los detalles se mostraran exitosamente<br><br>

<strong>Scenario 2: Validación al visualizar detalles de lote</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y no selecciona un lote existente<br>
Cuando presione el botón “Ver Detalles”<br>
Entonces los detalles saldrá un mensaje de error<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>07</th>
<th>Epic ID</th>
<th>02</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Detectar stock agotado</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero ser notificado cuando tengo bajo/nada de stock
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Alerta de stock próximo a agotarse mostrada correctamente</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y uno o más lotes tienen stock por debajo del umbral definido<br>
Cuando el usuario accede al dashboard de lotes<br>
Entonces se debe mostrar una alerta visible indicando los lotes próximos a agotarse<br><br>

<strong>Scenario 2: Alerta de stock agotado mostrada correctamente</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y uno o más de sus lotes estan agotados<br>
Cuando el usuario accede al dashboard de lotes<br>
Entonces se debe mostrar una alerta indicando los lotes agotados<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>08</th>
<th>Epic ID</th>
<th>02</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Mostrar alertas de estado al visualizar detalles</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero visualizar alertas de estado al ver el detalle de un lote para identificar rápidamente si tiene stock bajo, está agotado o próximo a vencer.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Alerta de stock próximo a agotarse mostrada correctamente</strong><br>
Dado que el usuario selecciona un lote<br>
Y el lote no tiene stock bajo, está agotado o próximo a vencer.<br>
Cuando presiona "Ver Detalles"<br>
Entonces se mostrarán los detalles del lote con alertas de estado<br><br>

<strong>Scenario 2: No mostrar alertas si el estado es normal</strong><br>
Dado que el usuario selecciona un lote<br>
Y el lote tiene stock bajo, está agotado o próximo a vencer.<br>
Cuando presiona "Ver Detalles"<br>
Entonces se mostrarán los detalles del lote sin alertas<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>09</th>
<th>Epic ID</th>
<th>02</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Visualizar dashboard de lotes</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero visualizar un dashboard de lotes con indicadores y alertas para conocer rápidamente el estado de mi inventario al ingresar al módulo de lotes.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Visualización de resumen de lotes</strong><br>
Dado que el usuario ingresa al módulo de lotes<br>
Cuando se carga la pantalla<br>
Entonces se debe mostrar un resumen con indicadores clave sobre los estados de los lotes<br>

<strong>Scenario 2: No mostrar alertas si no existen condiciones críticas</strong><br>
Dado que el usuario ingresa al módulo de lotes<br>
Y no existen lotes vencidos ni próximos a vencer<br>
Cuando se carga el dashboard<br>
Entonces no se debe mostrar el banner de alertas<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>10</th>
<th>Epic ID</th>
<th>01</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Visualizar detalles de producto</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero visualizar la información detallada de cada producto en el listado para conocer rápidamente sus características, stock disponible y precio sin necesidad de ingresar a otra pantalla.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Visualización de información del producto</strong><br>
Dado que el usuario accede al listado de productos<br>
Cuando se carga la información<br>
Entonces cada producto debe mostrar sus datos principales<br>
Y debe incluir: tipo, nombre, descripción,codigo QR, stock total y precio<br><br>

<strong>Scenario 2: Manejo de información incompleta del producto</strong><br>
Dado que el usuario accede al listado de productos<br>
Y un producto no cuenta con algún dato (descripción o código QR)<br>
Cuando se carga la información<br>
Entonces el sistema debe mostrar los demás datos disponibles correctamente<br>
Y los campos faltantes deben mostrarse como vacíos("-")<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>11</th>
<th>Epic ID</th>
<th>02</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Recibir alerta de caducidad de lote</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero ser notificado cuando un lote esté próximo a vencer o ya haya vencido
para poder tomar acciones como priorizar su uso o descartarlo.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Alerta de lote próximo a vencer mostrada correctamente</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y uno o más lotes tienen una fecha de caducidad dentro del rango próximo definido<br>
Cuando el usuario accede al dashboard de lotes<br>
Entonces se debe mostrar una alerta indicando los lotes próximos a vencer<br><br>

<strong>Scenario 2: Alerta de lote vencido mostrada correctamente</strong><br>
Dado que el usuario está en la sección de lotes<br>
Y uno o más lotes tienen una fecha de caducidad menor a la fecha actual<br>
Cuando el usuario accede al dashboard de lotes<br>
Entonces se debe mostrar una alerta indicando los lotes vencidos<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>12</th>
<th>Epic ID</th>
<th>01</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Buscar productos</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero tener un buscador de productos para perder menos tiempo buscando en el inventario.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Búsqueda de productos por nombre</strong><br>
Dado que el usuario está en el listado de productos<br>
Cuando ingresa el nombre de un producto en el campo de búsqueda<br>
Entonces el sistema debe filtrar y mostrar los productos que coincidan con el nombre ingresado<br><br>

<strong>Scenario 2: Búsqueda de productos por categoría</strong><br>
Dado que el usuario está en el listado de productos<br>
Cuando selecciona o ingresa una categoría en el buscador<br>
Entonces el sistema debe filtrar y mostrar los productos que pertenecen a esa categoría<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>13</th>
<th>Epic ID</th>
<th>03</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Seleccionar plan de suscripción</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero seleccionar un plan de suscripción para definir el tipo de acceso y beneficios que tendré dentro de la plataforma.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Selección de plan realizada correctamente</strong><br>
Dado que el usuario visualiza los planes de suscripción disponibles<br>
Cuando selecciona uno de los planes mostrados<br>
Entonces el sistema registrará el plan seleccionado<br>
Y permitirá continuar con el proceso de suscripción<br><br>

<strong>Scenario 2: Intento de continuar sin seleccionar un plan</strong><br>
Dado que el usuario visualiza los planes de suscripción disponibles<br>
Y no selecciona ningún plan<br>
Cuando intenta continuar con el proceso<br>
Entonces el sistema no permitirá avanzar<br>
Y mostrará un mensaje indicando que debe seleccionar un plan<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>14</th>
<th>Epic ID</th>
<th>03</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Iniciar proceso de suscripción</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero iniciar el proceso de suscripción para comenzar formalmente la contratación del plan previamente elegido.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Proceso de suscripción iniciado correctamente</strong><br>
Dado que el usuario ya seleccionó un plan de suscripción<br>
Cuando presiona la opción para iniciar la suscripción<br>
Entonces el sistema registrará el inicio del proceso de suscripción<br>
Y habilitará el formulario de facturación<br><br>

<strong>Scenario 2: Intento de iniciar suscripción sin plan seleccionado</strong><br>
Dado que el usuario no ha seleccionado un plan de suscripción<br>
Cuando intenta iniciar el proceso de suscripción<br>
Entonces el sistema no permitirá iniciar el proceso<br>
Y mostrará un mensaje solicitando seleccionar un plan primero<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>15</th>
<th>Epic ID</th>
<th>03</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Registrar datos de facturación</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero ingresar mis datos de facturación para que el sistema pueda procesar el cobro correspondiente a la suscripción.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Datos de facturación registrados correctamente</strong><br>
Dado que el usuario se encuentra en el proceso de suscripción<br>
Y completa correctamente los datos de facturación<br>
Cuando confirma el formulario<br>
Entonces el sistema registrará los datos ingresados<br>
Y permitirá continuar al paso de cobro<br><br>

<strong>Scenario 2: Datos de facturación inválidos</strong><br>
Dado que el usuario se encuentra en el proceso de suscripción<br>
Y completa incorrectamente los datos de facturación<br>
Cuando intenta confirmar el formulario<br>
Entonces el sistema no registrará los datos<br>
Y mostrará un mensaje indicando que existen datos inválidos<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>16</th>
<th>Epic ID</th>
<th>03</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Procesar cobro de suscripción</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero que el sistema procese el cobro de la suscripción para validar el pago del plan seleccionado.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Cobro procesado exitosamente</strong><br>
Dado que el usuario ha registrado correctamente sus datos de facturación<br>
Cuando el sistema procesa el cobro de la suscripción<br>
Entonces el cobro será procesado exitosamente<br>
Y el sistema permitirá activar la suscripción<br><br>

<strong>Scenario 2: Error durante el procesamiento del cobro</strong><br>
Dado que el usuario ha iniciado el proceso de pago<br>
Cuando ocurre un error como tarjeta rechazada, datos inválidos o cobro fallido<br>
Entonces el sistema no activará la suscripción<br>
Y mostrará un mensaje indicando el motivo del error<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>17</th>
<th>Epic ID</th>
<th>03</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Activar suscripción</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero que mi suscripción sea activada una vez confirmado el cobro para acceder a las funcionalidades de la plataforma según el plan contratado.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Activación de suscripción exitosa</strong><br>
Dado que el cobro de la suscripción fue procesado correctamente<br>
Cuando el sistema confirma el pago<br>
Entonces la suscripción será activada<br>
Y el usuario obtendrá acceso a las funcionalidades correspondientes<br><br>

<strong>Scenario 2: Suscripción no activada por pago no confirmado</strong><br>
Dado que el cobro de la suscripción no fue confirmado<br>
Cuando el sistema intenta activar la suscripción<br>
Entonces la suscripción permanecerá en estado pendiente<br>
Y el usuario no podrá acceder a las funcionalidades premium<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>18</th>
<th>Epic ID</th>
<th>04</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Visualizar panel de suscripción</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero visualizar el panel de suscripción para consultar de forma clara la información general relacionada con mi plan actual.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Panel de suscripción mostrado correctamente</strong><br>
Dado que el usuario accede a la sección de suscripción<br>
Cuando el sistema carga la vista correspondiente<br>
Entonces se mostrará el panel de suscripción<br>
Y se visualizarán los datos generales de la suscripción del usuario<br><br>

<strong>Scenario 2: Usuario sin suscripción registrada</strong><br>
Dado que el usuario accede a la sección de suscripción<br>
Y no tiene una suscripción activa o registrada<br>
Cuando el sistema carga la vista correspondiente<br>
Entonces se mostrará el panel sin información activa<br>
Y se indicará que no existe una suscripción disponible<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>19</th>
<th>Epic ID</th>
<th>04</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Consultar estado de suscripción</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero consultar el estado de mi suscripción para saber si se encuentra activa, vencida o cancelada.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Estado de suscripción activa mostrado correctamente</strong><br>
Dado que el usuario tiene una suscripción vigente<br>
Cuando consulta el estado de su suscripción<br>
Entonces el sistema mostrará que la suscripción se encuentra activa<br><br>

<strong>Scenario 2: Estado de suscripción vencida o cancelada mostrado correctamente</strong><br>
Dado que el usuario tiene una suscripción vencida o cancelada<br>
Cuando consulta el estado de su suscripción<br>
Entonces el sistema mostrará el estado correspondiente<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>20</th>
<th>Epic ID</th>
<th>04</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Renovar suscripción</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero renovar mi suscripción para extender la vigencia de mi acceso a la plataforma.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Renovación realizada correctamente</strong><br>
Dado que el usuario tiene una suscripción activa o próxima a vencer<br>
Cuando selecciona la opción de renovar suscripción<br>
Entonces el sistema registrará la renovación<br>
Y actualizará la nueva fecha de vencimiento<br><br>

<strong>Scenario 2: Renovación no permitida</strong><br>
Dado que el usuario no cuenta con una suscripción válida para renovación<br>
Cuando intenta renovar su suscripción<br>
Entonces el sistema no permitirá la acción<br>
Y mostrará un mensaje indicando que la renovación no puede realizarse<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>21</th>
<th>Epic ID</th>
<th>04</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Solicitar cancelación de suscripción</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero solicitar la cancelación de mi suscripción para detener su continuidad al finalizar el periodo vigente.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Solicitud de cancelación registrada correctamente</strong><br>
Dado que el usuario tiene una suscripción activa<br>
Cuando solicita la cancelación de su suscripción<br>
Entonces el sistema registrará la solicitud de cancelación<br>
Y mantendrá el acceso hasta la fecha de vencimiento<br><br>

<strong>Scenario 2: Usuario cancela la operación antes de confirmar</strong><br>
Dado que el usuario inició el proceso de cancelación<br>
Cuando decide no confirmar la solicitud<br>
Entonces el sistema no registrará la cancelación<br>
Y la suscripción continuará sin cambios<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>22</th>
<th>Epic ID</th>
<th>04</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Cancelar suscripción</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como sistema quiero cancelar la suscripción al finalizar su periodo vigente para retirar el acceso del usuario a las funcionalidades premium.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Cancelación ejecutada correctamente</strong><br>
Dado que existe una solicitud de cancelación registrada<br>
Y la fecha de vencimiento ha sido alcanzada<br>
Cuando el sistema procesa el fin del periodo<br>
Entonces la suscripción será cancelada<br>
Y el acceso a funcionalidades premium será retirado<br><br>

<strong>Scenario 2: Suscripción aún dentro del periodo vigente</strong><br>
Dado que existe una solicitud de cancelación registrada<br>
Pero la fecha de vencimiento aún no ha llegado<br>
Cuando el sistema verifica el estado de la suscripción<br>
Entonces la suscripción continuará activa<br>
Y el acceso permanecerá habilitado hasta el final del periodo<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>23</th>
<th>Epic ID</th>
<th>01</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Crear lotes</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como usuario quiero crear lotes de productos para controlar mejor el stock y la caducidad en el inventario.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Creación de lote exitosa</strong><br>
Dado que el usuario está en la sección de productos<br>
Cuando presiona el botón “Crear Lote”<br>
Y selecciona un producto existente<br>
Y completa los datos requeridos correctamente<br>
Entonces el sistema debe registrar el nuevo lote<br>
Y mostrarlo en la lista de lotes<br><br>

<strong>Scenario 2: Validación al crear lote</strong><br>
Dado que el usuario está en la sección de productos<br>
Cuando presiona el botón “Crear Lote”<br>
Y no selecciona un producto o ingresa datos incompletos o inválidos<br>
Entonces el sistema debe mostrar mensajes de error<br>
Y no permitir la creación del lote<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>24</th>
<th>Epic ID</th>
<th>05</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Buscar productos en el inventario y validar su tipo de medida.</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cajero, quiero buscar productos del inventario para que el sistema valide si son por cantidad o peso, para abrir la interfaz de ingreso correspondiente.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Búsqueda y validación de producto por peso</strong><br>
Dado que el cajero ingresa “Manzana” en el buscador,<br>
Cuando selecciona el producto de la lista,<br>
Y el sistema verifica que el producto está registrado con medida en "Kg",<br>
Entonces el sistema despliega el modal "Registrar Peso".<br><br>

<strong>Scenario 2: Búsqueda y validación de producto por cantidad</strong><br>
Dado que el cajero realiza una búsqueda,<br>
Cuando selecciona “Coca Cola” del inventario,<br>
Y el sistema verifica que el producto está registrado por unidades,<br>
Entonces el sistema despliega el modal "Registrar Cantidad".<br><br>

<strong>Scenario 3: Producto no encontrado</strong><br>
Dado que el término ingresado no coincide con el inventario,<br>
Cuando se ejecuta la búsqueda,<br>
Entonces el sistema muestra un mensaje indicando "Producto no encontrado".<br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>25</th>
<th>Epic ID</th>
<th>05</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Registrar la cantidad de unidades en el Ticket de Venta.</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cajero, quiero ingresar el número de unidades de un producto seleccionado, para añadirlo al detalle de la venta.

</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Confirmación de cantidad unitaria </strong><br>
Dado que el modal "Registrar Cantidad" está abierto,<br>
Cuando el cajero ingresa el número entero "3" en el teclado numérico,<br>
Y presiona el botón "Confirmar cantidad",<br>
Entonces el sistema calcula el subtotal y añade el ítem al detalle de la venta.<br><br>

<strong>Scenario 2: Validación de stock insuficiente por cantidad</strong><br>
Dado que el cajero ha ingresado una cantidad en el modal,<br>
Cuando el sistema verifica que la cantidad solicitada es mayor al stock disponible en el inventario,<br>
Y el usuario intenta confirmar la acción,<br>
Entonces el sistema muestra una alerta indicando "Stock insuficiente" y no permite añadir el producto al ticket.<br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>26</th>
<th>Epic ID</th>
<th>05</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Capturar el peso mediante balanza IoT o ingreso manual.</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cajero, quiero obtener el peso del producto automáticamente o por teclado, para procesar la venta de productos al granel.

</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Captura automática</strong><br>
Dado que el modal "Registrar Peso" está abierto,<br>
Cuando el sistema detecta una balanza IoT conectada,<br>
Y el cajero coloca el producto sobre la balanza física,<br>
Y el hardware envía la lectura de peso al sistema,<br>
Entonces el valor se carga automáticamente en el campo de peso.<br><br>

<strong>Scenario 2: Registro de peso manual</strong><br>
Dado que el sistema no detecta una balanza,<br>
Y el modal "Registrar Peso" está abierto,<br>
Cuando el cajero digita el peso observado físicamente en el teclado decimal,<br>
Y presiona el botón "Confirmar Peso",<br>
Entonces el sistema registra el dato y añade el producto al ticket de venta.<br><br>

<strong>Scenario 3: Validación de stock insuficiente por peso</strong><br>
Dado que el cajero ha ingresado el peso en el modal,<br>
Cuando el sistema verifica que el peso solicitado es mayor al stock disponible en el inventario,<br>
Y el usuario intenta confirmar la acción,<br>
Entonces el sistema muestra una alerta indicando "Stock insuficiente" y no permite añadir el producto al ticket.<br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>27</th>
<th>Epic ID</th>
<th>05</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Gestionar el desglose y cálculo del Ticket de Venta.</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cajero, quiero visualizar el desglose de productos (nombre, cantidad/peso, precio unitario y subtotal), para verificar que la información sea correcta antes de proceder al pago.

</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Actualización del detalle y monto total</strong><br>
Dado que se han añadido productos (por unidad o peso) al ticket de venta,<br>
Cuando el sistema procesa cada ítem de la lista,<br>
Y calcula automáticamente el subtotal multiplicando el precio por la cantidad o peso,<br>
Y suma todos los subtotales de la lista,<br>
Entonces el sistema muestra el desglose detallado y el monto total acumulado de la venta en la interfaz.<br><br>


<strong>Scenario 2: Edición o eliminación de un ítem del detalle</strong><br>
Dado que un producto ya se encuentra registrado en el detalle de la venta,<br>
Cuando el cajero selecciona la opción de eliminar,<br>
Y el sistema confirma la acción del usuario,<br>
Entonces el sistema actualiza la lista del detalle y recalcula el monto total de la venta inmediatamente.<br><br>

<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>28</th>
<th>Epic ID</th>
<th>05</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Seleccionar el método de pago para la transacción.</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cajero, quiero elegir el medio por el cual está pagando el cliente (Efectivo o Tarjeta/Yape/Plin), para que el ingreso se registre en la categoría contable correcta.

</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Selección de método de pago exitosa</strong><br>
Dado que el ticket de venta tiene el monto total calculado,<br>
Cuando el cajero hace clic sobre el ícono de "Efectivo" o "Tarjeta Yape/Plin",<br>
Y el sistema marca visualmente la opción seleccionada como activa,<br>
Y registra la categoría del método de pago internamente,<br>
Entonces el sistema habilita el botón "Finalizar Venta y Emitir Boleta".<br><br>

<strong>Scenario 2: Intento de finalización sin método de pago</strong><br>
Dado que el cajero ha terminado de agregar productos al ticket,<br>
Cuando intenta presionar el botón de finalizar la venta sin haber marcado una opción de pago,<br>
Y el sistema valida que no hay un método asignado para la transacción actual,<br>
Entonces el sistema muestra un mensaje de advertencia indicando "Por favor, seleccione un método de pago" y bloquea la emisión de la boleta.<br><br>

</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>29</th>
<th>Epic ID</th>
<th>05</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Finalizar la venta y emitir el comprobante de pago.

</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cajero, quiero procesar el pago y finalizar la venta en un solo paso, para entregar el comprobante al cliente de forma inmediata.

</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Procesamiento exitoso del cierre de venta</strong><br>
Dado que el ticket de venta tiene productos añadidos y el método de pago ha sido seleccionado,<br>
Cuando el cajero presiona el botón "Finalizar Venta y Emitir Boleta",<br>

Y el sistema registra la información en la base de datos actualizando saldos y stock,<br>
Entonces el sistema genera el comprobante de pago, muestra un mensaje de éxito y limpia la interfaz para una nueva venta.<br><br>

<strong>Scenario 2: Bloqueo de finalización por datos incompletos</strong><br>
Dado que el cajero se encuentra en la pantalla de ventas,<br>
Cuando intenta presionar el botón de finalizar venta sin productos en el ticket o sin método de pago,<br>
Y el sistema detecta la ausencia de estos datos obligatorios,<br>
Entonces el sistema muestra un mensaje “No hay productos en el ticket” manteniendo la interfaz de venta activa hasta que se completen los campos requeridos.<br>


</td>
</tr>
</table>
<br><br>
<table>
<tr>
<th>User Story</th>
<th>30</th>
<th>Epic ID</th>
<th>06</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Clasificar automáticamente los ingresos según el medio de pago.

</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como comerciante, quiero que cada venta finalizada sume su monto al acumulado del método correspondiente, para tener visibilidad inmediata de cuánto dinero hay en efectivo y cuánto en digital.

</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Actualización del acumulado por método de pago</strong><br>
Dado que se ha finalizado una venta exitosamente,<br>
Cuando el sistema procesa el registro de la transacción,<br>
Y detecta el método de pago utilizado (Efectivo o Tarjeta/Digital),<br>
Y suma el monto de la venta al saldo anterior de esa categoría,<br>
Entonces el sistema actualiza visualmente el "Resumen de Caja" con los nuevos montos acumulados.<br><br>


<strong>Scenario 2: Visualización del total general de ingresos</strong><br>
Dado que los saldos por categoría (Efectivo y Digital) han sido actualizados,<br>
Cuando el comerciante visualiza el panel de "Resumen de Caja",<br>
Y el sistema suma ambos acumulados de forma automática,<br>
Entonces el sistema muestra el "Total del Día" como la suma consolidada de todos los medios de pago.<br><br>

</td>
</tr>
</table>

<br><br>
<table>
<tr>
<th>User Story</th>
<th>31</th>
<th>Epic ID</th>
<th>06</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Monitorear el Resumen de Caja en tiempo real dentro del panel de ventas.

</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cajero, quiero visualizar de forma centralizada los ingresos acumulados por método de pago, para tener un control inmediato de los saldos del día sin salir de la interfaz principal.

</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Visualización dinámica de ingresos operativos</strong><br>
Dado que el cajero se encuentra en la sección de "Ventas",<br>
Cuando finaliza transacciones de forma sucesiva,<br>
Y el sistema procesa los nuevos montos registrados,<br>
Entonces el sistema actualiza automáticamente los contadores de "Efectivo", "Tarjeta Yape/Plin" y el "Total del Día" en la parte inferior de la pantalla.<br><br>


<strong>Scenario 2: Persistencia de saldos al cambiar de sección</strong><br>
Dado que el cajero tiene un saldo acumulado en el Resumen de Caja,<br>
Cuando navega hacia otra sección (ej. "Productos" o "Lotes") y regresa nuevamente a "Ventas",<br>
Y el sistema recupera los datos almacenados en la sesión,<br>
Entonces el sistema muestra los saldos actualizados tal como estaban antes de salir de la pestaña, evitando que la información se pierda o se reinicie.<br><br>


</td>
</tr>
</table>
<table>
<tr>
<th>User Story</th>
<th>32</th>
<th>Epic ID</th>
<th>07</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Vincular cuenta de WhatsApp Business mediante código QR</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como comerciante, quiero conectar mi cuenta de WhatsApp Business escaneando un código QR para activar el chatbot de atención a clientes desde el dashboard.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Mostrar código QR en primer acceso</strong><br>
Dado que el comerciante no tiene ninguna cuenta de WhatsApp Business vinculada,<br>
Cuando accede a la sección de chatbot del dashboard,<br>
Entonces el sistema genera y muestra un código QR válido para iniciar la vinculación.<br><br>

<strong>Scenario 2: Vinculación exitosa tras escaneo</strong><br>
Dado que el comerciante escanea el código QR desde su WhatsApp Business,<br>
Cuando el sistema confirma la conexión con la cuenta,<br>
Entonces el sistema registra la vinculación, activa el chatbot y habilita la visualización de conversaciones.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>33</th>
<th>Epic ID</th>
<th>07</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Consultar estado de vinculación del chatbot</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como comerciante, quiero conocer el estado de conexión de mi WhatsApp Business para saber si el chatbot se encuentra activo o requiere reconexión.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Estado activo cuando la cuenta está vinculada</strong><br>
Dado que el comerciante tiene una cuenta de WhatsApp Business vinculada,<br>
Cuando accede a la sección de chatbot,<br>
Entonces el sistema muestra el estado de conexión como activo junto al número vinculado.<br><br>

<strong>Scenario 2: Estado desconectado cuando la sesión expiró</strong><br>
Dado que la sesión de WhatsApp Business ha expirado o fue cerrada externamente,<br>
Cuando el comerciante accede a la sección de chatbot,<br>
Entonces el sistema muestra el estado como desconectado y habilita la opción de volver a vincular.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>34</th>
<th>Epic ID</th>
<th>08</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Visualizar conversaciones de clientes en el dashboard</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como comerciante, quiero ver los chats que el bot ha tenido con mis clientes dentro del dashboard para tener visibilidad de todas las conversaciones activas sin usar WhatsApp directamente.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Conversaciones cargadas cuando existe actividad</strong><br>
Dado que el comerciante tiene su WhatsApp Business vinculado,<br>
Cuando accede a la sección de chatbot,<br>
Entonces el sistema muestra la lista de conversaciones con clientes ordenada por la más reciente, con el último mensaje visible.<br><br>

<strong>Scenario 2: Mensaje informativo cuando no hay conversaciones</strong><br>
Dado que ningún cliente ha iniciado una conversación con el bot,<br>
Cuando el comerciante accede a la sección de chatbot,<br>
Entonces el sistema indica que aún no existen conversaciones registradas.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>35</th>
<th>Epic ID</th>
<th>08</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Responder mensajes de clientes desde el dashboard</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como comerciante, quiero enviar mensajes a mis clientes directamente desde el dashboard para gestionar conversaciones sin necesitar abrir WhatsApp.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Mensaje enviado correctamente al cliente</strong><br>
Dado que el comerciante selecciona una conversación activa y redacta un mensaje,<br>
Cuando confirma el envío,<br>
Entonces el sistema envía el mensaje al cliente a través de WhatsApp y lo registra en el hilo de conversación.<br><br>

<strong>Scenario 2: Envío bloqueado cuando el mensaje está vacío</strong><br>
Dado que el comerciante selecciona una conversación activa,<br>
Cuando intenta confirmar el envío sin haber redactado ningún contenido,<br>
Entonces el sistema no procesa el envío y mantiene el estado de la conversación sin cambios.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>36</th>
<th>Epic ID</th>
<th>09</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Responder consulta de producto disponible</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como sistema, quiero que el chatbot responda automáticamente al cliente con la información del producto solicitado cuando este existe en el inventario para iniciar el proceso de pedido sin intervención del comerciante.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Bot informa disponibilidad del producto solicitado</strong><br>
Dado que el cliente envía el nombre de un producto al chatbot,<br>
Cuando el sistema consulta el inventario y encuentra el producto con stock mayor a cero,<br>
Entonces el bot responde con el nombre, precio y stock disponible, y ofrece al cliente agregarlo al pedido.<br><br>

<strong>Scenario 2: Bot registra selección confirmada por el cliente</strong><br>
Dado que el bot informó la disponibilidad del producto,<br>
Cuando el cliente confirma que desea pedirlo e indica la cantidad,<br>
Entonces el sistema registra la selección en el pedido en curso y consulta al cliente si desea agregar más productos.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>37</th>
<th>Epic ID</th>
<th>09</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Sugerir alternativas ante producto no disponible</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como sistema, quiero que el chatbot informe al cliente cuando un producto no está disponible y le sugiera otros productos del inventario para evitar que la conversación quede sin respuesta útil.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Bot sugiere alternativas cuando el producto no existe</strong><br>
Dado que el cliente solicita un producto que no se encuentra en el inventario o tiene stock igual a cero,<br>
Cuando el sistema verifica la disponibilidad,<br>
Entonces el bot informa que el producto no está disponible y presenta una lista de productos alternativos con stock.<br><br>

<strong>Scenario 2: Bot notifica cuando el inventario completo está agotado</strong><br>
Dado que el cliente solicita un producto y todos los productos del inventario tienen stock igual a cero,<br>
Cuando el sistema verifica la disponibilidad general,<br>
Entonces el bot informa que no hay productos disponibles en ese momento e invita al cliente a intentarlo más tarde.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>38</th>
<th>Epic ID</th>
<th>09</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Confirmar pedido con el cliente</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como sistema, quiero que el chatbot presente un resumen del pedido al cliente y solicite confirmación antes de proceder al pago para asegurar que los productos y cantidades sean correctos.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Bot envía resumen y solicita confirmación</strong><br>
Dado que el cliente indicó todos los productos que desea y su dirección de entrega,<br>
Cuando el cliente indica que no desea agregar más productos,<br>
Entonces el sistema genera un resumen con productos, cantidades, total y dirección, y lo envía al cliente solicitando confirmación.<br><br>

<strong>Scenario 2: Sistema registra pedido tras confirmación del cliente</strong><br>
Dado que el bot envió el resumen del pedido al cliente,<br>
Cuando el cliente confirma que el pedido es correcto,<br>
Entonces el sistema registra el pedido con estado pendiente y envía las instrucciones de pago al cliente.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>39</th>
<th>Epic ID</th>
<th>10</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Recibir instrucciones de pago por WhatsApp</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cliente, quiero recibir las instrucciones de pago a través del chatbot para saber cómo realizar la transferencia y completar mi pedido.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Bot envía instrucciones tras confirmación del pedido</strong><br>
Dado que el cliente confirmó su pedido y el stock fue validado exitosamente,<br>
Cuando el sistema procesa la confirmación,<br>
Entonces el bot envía al cliente el número Yape/Plin del comerciante, el monto total y el número de pedido como referencia.<br><br>

<strong>Scenario 2: Sistema registra el evento de instrucción enviada</strong><br>
Dado que el bot entrega las instrucciones de pago al cliente,<br>
Cuando el sistema confirma la entrega del mensaje,<br>
Entonces registra el evento con marca de tiempo para trazabilidad del proceso.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>40</th>
<th>Epic ID</th>
<th>10</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Reportar comprobante de pago digital</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cliente, quiero enviar el comprobante de mi pago al chatbot para que el comerciante pueda verificarlo y confirmar mi pedido.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Sistema registra comprobante recibido y notifica al comerciante</strong><br>
Dado que el cliente realizó el pago por Yape o Plin,<br>
Cuando envía el comprobante al chatbot,<br>
Entonces el sistema registra el comprobante, actualiza el estado del pedido a pendiente de validación y notifica al comerciante.<br><br>

<strong>Scenario 2: Bot envía recordatorio ante ausencia de reporte</strong><br>
Dado que el cliente recibió las instrucciones de pago,<br>
Cuando transcurren treinta minutos sin que el cliente reporte el comprobante,<br>
Entonces el sistema envía un recordatorio al cliente y mantiene el pedido en estado esperando pago.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>41</th>
<th>Epic ID</th>
<th>10</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Validar comprobante de pago desde el dashboard</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como comerciante, quiero revisar el comprobante reportado por el cliente y aprobarlo o rechazarlo desde el dashboard para confirmar que el dinero fue recibido correctamente.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Comerciante visualiza comprobante y detalles del pedido</strong><br>
Dado que el cliente reportó su comprobante de pago,<br>
Cuando el comerciante revisa el pedido,<br>
Entonces el sistema muestra el comprobante, el monto y los detalles del pedido asociado.<br><br>

<strong>Scenario 2: Sistema registra validación manual al aprobar el pago</strong><br>
Dado que el comerciante verifica que el comprobante es correcto,<br>
Cuando aprueba el pago,<br>
Entonces el sistema registra la validación manual con marca de tiempo y continúa el flujo de confirmación del pedido.<br><br>

<strong>Scenario 3: Sistema notifica al cliente al rechazar el pago</strong><br>
Dado que el comerciante detecta que el comprobante es incorrecto,<br>
Cuando lo rechaza indicando el motivo,<br>
Entonces el sistema registra el rechazo y el bot notifica al cliente indicando los pasos a seguir.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>42</th>
<th>Epic ID</th>
<th>10</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Notificar resultado de validación al cliente</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cliente, quiero recibir una notificación sobre el resultado de la validación de mi pago para saber si mi pedido fue confirmado o si debo realizar alguna acción adicional.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Bot confirma al cliente que el pago fue aprobado</strong><br>
Dado que el comerciante aprueba el comprobante de pago,<br>
Cuando el sistema actualiza el estado del pedido,<br>
Entonces el bot envía al cliente un mensaje confirmando que el pago fue recibido y el pedido está en proceso.<br><br>

<strong>Scenario 2: Bot informa al cliente que el pago fue rechazado</strong><br>
Dado que el comerciante rechaza el comprobante de pago,<br>
Cuando el sistema actualiza el estado del pedido,<br>
Entonces el bot informa al cliente que el pago no fue validado, indica el motivo y solicita que reintente el proceso.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>43</th>
<th>Epic ID</th>
<th>11</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Confirmar pedido y descontar stock</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como sistema, quiero confirmar el pedido automáticamente al aprobar el pago para actualizar el inventario en tiempo real y reflejar el consumo de stock.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Sistema actualiza inventario al confirmar el pedido</strong><br>
Dado que el comerciante aprueba el comprobante de pago,<br>
Cuando el sistema confirma el pedido,<br>
Entonces actualiza el estado del pedido a confirmado y descuenta la cantidad correspondiente del stock de cada producto.<br><br>

<strong>Scenario 2: Sistema sincroniza peso con balanza IoT para productos por peso</strong><br>
Dado que el pedido confirmado incluye productos vendidos por peso,<br>
Cuando el sistema descuenta el stock,<br>
Entonces actualiza el peso disponible registrado en la balanza IoT.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>44</th>
<th>Epic ID</th>
<th>11</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Registrar venta en el sistema</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como comerciante, quiero que cada pedido confirmado quede registrado como venta en el sistema para mantener un control financiero preciso y trazable.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Sistema crea registro de venta al confirmar pedido</strong><br>
Dado que el pedido ha sido confirmado tras la validación del pago,<br>
Cuando el sistema procesa el cierre de la transacción,<br>
Entonces crea un registro de venta con monto total, método de pago, productos vendidos y marca de tiempo.<br><br>

<strong>Scenario 2: Sistema separa ingresos digitales de los ingresos en efectivo</strong><br>
Dado que el método de pago utilizado fue Yape o Plin,<br>
Cuando el sistema registra la venta,<br>
Entonces asocia el monto al canal de pagos digitales, manteniéndolo separado del efectivo en caja.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>45</th>
<th>Epic ID</th>
<th>11</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Emitir comprobante digital al cliente</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cliente, quiero recibir un comprobante de mi compra a través del chatbot para tener un respaldo de la transacción realizada.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Bot envía comprobante al cliente tras registrar la venta</strong><br>
Dado que la venta ha sido registrada correctamente en el sistema,<br>
Cuando el sistema genera el comprobante,<br>
Entonces el bot envía al cliente un resumen con número de pedido, productos, cantidades, monto total y fecha.<br><br>

<strong>Scenario 2: Sistema marca el pedido como completado al emitir el comprobante</strong><br>
Dado que el comprobante fue generado y enviado al cliente,<br>
Cuando el sistema confirma la entrega,<br>
Entonces registra el evento de emisión con marca de tiempo y actualiza el estado del pedido a completado.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>46</th>
<th>Epic ID</th>
<th>12</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Manejar stock insuficiente en pedido</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como cliente, quiero ser notificado cuando un producto no tiene stock suficiente para poder ajustar mi pedido antes de proceder al pago.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Bot notifica al cliente sobre stock insuficiente</strong><br>
Dado que el cliente solicita una cantidad mayor al stock disponible de un producto,<br>
Cuando el sistema valida el inventario,<br>
Entonces el bot informa qué producto no tiene stock suficiente y ofrece al cliente ajustar la cantidad o eliminarlo del pedido.<br><br>

<strong>Scenario 2: Sistema actualiza el pedido con la nueva cantidad</strong><br>
Dado que el bot informó al cliente sobre el stock insuficiente,<br>
Cuando el cliente confirma una nueva cantidad menor o igual al stock disponible,<br>
Entonces el sistema actualiza el pedido y continúa el flujo de forma normal.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>47</th>
<th>Epic ID</th>
<th>12</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Cancelar pedido por expiración de tiempo de pago</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como sistema, quiero cancelar automáticamente un pedido cuando el cliente no reporta el comprobante de pago en el tiempo establecido para liberar el stock reservado.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Sistema cancela el pedido y libera el stock al expirar el tiempo</strong><br>
Dado que el cliente recibió las instrucciones de pago,<br>
Cuando transcurren sesenta minutos sin que el cliente reporte el comprobante,<br>
Entonces el sistema cancela el pedido, libera el stock reservado y notifica al cliente.<br><br>

<strong>Scenario 2: Sistema registra el evento de cancelación para trazabilidad</strong><br>
Dado que el pedido es cancelado por expiración del tiempo de espera,<br>
Cuando el sistema actualiza el estado,<br>
Entonces registra el evento de cancelación con el motivo y marca de tiempo correspondientes.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>48</th>
<th>Epic ID</th>
<th>12</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Rechazar comprobante de pago inválido</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como comerciante, quiero poder rechazar un comprobante de pago cuando sea incorrecto o sospechoso para proteger el negocio de transacciones fraudulentas.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Sistema revierte el estado del pedido al rechazar el comprobante</strong><br>
Dado que el comerciante identifica un comprobante sospechoso o incorrecto,<br>
Cuando lo rechaza indicando el motivo,<br>
Entonces el sistema devuelve el pedido al estado esperando pago y el bot notifica al cliente.<br><br>

<strong>Scenario 2: Sistema alerta al comerciante ante rechazos repetidos del mismo cliente</strong><br>
Dado que el mismo cliente presenta comprobantes rechazados en dos ocasiones consecutivas,<br>
Cuando el sistema detecta el patrón,<br>
Entonces alerta al comerciante y bloquea el pedido para revisión manual.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>49</th>
<th>Epic ID</th>
<th>13</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Conocer propuesta de valor en landing page</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como visitante, quiero entender qué hace Entreprenly y cómo puede beneficiar a mi negocio para decidir si me interesa adquirirlo.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Visitante visualiza la propuesta de valor al cargar la página</strong><br>
Dado que el visitante accede a la landing page,<br>
Cuando la página termina de cargar,<br>
Entonces el sistema muestra el headline principal, la propuesta de valor y los beneficios clave del producto.<br><br>

<strong>Scenario 2: Visitante accede a la sección de funcionalidades</strong><br>
Dado que el visitante navega por la landing page,<br>
Cuando llega a la sección de funcionalidades,<br>
Entonces el sistema presenta las características principales: chatbot WhatsApp, inventario, balanza IoT y dashboard financiero.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>50</th>
<th>Epic ID</th>
<th>13</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Gestionar ciclo de vida de pedidos mediante API</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como developer, quiero endpoints para crear y actualizar pedidos para que el chatbot y el dashboard intercambien información del pedido de forma automática y consistente.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Creación exitosa de pedido</strong><br>
Dado que el developer envía una solicitud de creación de pedido con datos válidos,<br>
Cuando el servidor valida el cuerpo de la solicitud,<br>
Entonces el sistema responde con código HTTP 201, retorna el identificador del pedido, el estado pendiente y la marca de tiempo de creación.<br><br>

<strong>Scenario 2: Actualización de estado de pedido existente</strong><br>
Dado que el developer envía una solicitud de actualización con un estado válido para un pedido existente,<br>
Cuando el servidor procesa la solicitud,<br>
Entonces el sistema responde con código HTTP 200 y retorna el objeto del pedido con el estado actualizado.<br><br>

<strong>Scenario 3: Solicitud sobre pedido inexistente</strong><br>
Dado que el developer envía una solicitud referenciando un identificador de pedido que no existe,<br>
Cuando el servidor busca el recurso,<br>
Entonces el sistema responde con código HTTP 404 indicando que el pedido no fue encontrado.

</td>
</tr>
</table>
<br></br>

<table>
<tr>
<th>User Story</th>
<th>51</th>
<th>Epic ID</th>
<th>13</th>
</tr>
<tr>
<td><strong>Title</strong></td>
<td colspan="3">Validar y registrar pagos mediante API</td>
</tr>
<tr>
<td><strong>Description</strong></td>
<td colspan="3">
Como developer, quiero un endpoint para aprobar o rechazar pagos desde el dashboard para que el sistema actualice el inventario y notifique al cliente de forma automática.
</td>
</tr>
<tr>
<td><strong>Acceptance Criteria</strong></td>
<td colspan="3">

<strong>Scenario 1: Aprobación de pago con descuento de stock</strong><br>
Dado que el developer envía una solicitud de aprobación de pago con estado aprobado,<br>
Cuando el servidor procesa la validación,<br>
Entonces el sistema responde con código HTTP 200, actualiza el pedido a confirmado y descuenta el stock correspondiente.<br><br>

<strong>Scenario 2: Rechazo de pago con registro de motivo</strong><br>
Dado que el developer envía una solicitud de rechazo con motivo especificado,<br>
Cuando el servidor procesa el rechazo,<br>
Entonces el sistema responde con código HTTP 200 y registra el motivo en el historial del pago.<br><br>

<strong>Scenario 3: Solicitud sobre pago inexistente</strong><br>
Dado que el developer envía una solicitud referenciando un identificador de pago que no existe,<br>
Cuando el servidor busca el recurso,<br>
Entonces el sistema responde con código HTTP 404 indicando que el pago no fue encontrado.

</td>
</tr>
</table>
<br></br>
<br><br>
<table>
  <tr>
    <th>User Story</th>
    <th>52</th>
    <th>Epic ID</th>
    <th>14</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Registrar cuenta con email</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario anónimo, quiero registrarme con mi email y contraseña para crear una cuenta en Entreprenly.
    </td>
  </tr>
  <br><br>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Registro exitoso</strong><br>
      Dado que el usuario ingresa un email no registrado y una contraseña válida,<br>
      Cuando envía el formulario de registro,<br>
      Entonces el sistema crea la cuenta, envía un email de verificación y muestra un mensaje de confirmación.<br><br>
      <strong>Scenario 2: Email ya registrado</strong><br>
      Dado que el usuario ingresa un email que ya existe en el sistema,<br>
      Cuando envía el formulario de registro,<br>
      Entonces el sistema muestra un mensaje de error indicando que el email ya está en uso.<br><br>
      <strong>Scenario 3: Datos inválidos</strong><br>
      Dado que el usuario ingresa una contraseña que no cumple los requisitos mínimos,<br>
      Cuando envía el formulario,<br>
      Entonces el sistema muestra los errores de validación correspondientes sin crear la cuenta.
    </td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>User Story</th>
    <th>53</th>
    <th>Epic ID</th>
    <th>14</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Verificar email</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario registrado, quiero verificar mi email mediante el enlace enviado a mi correo para activar mi cuenta.
    </td>
  </tr>
  <br><br>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Verificación exitosa</strong><br>
      Dado que el usuario hace clic en el enlace de verificación válido,<br>
      Cuando el sistema valida el token,<br>
      Entonces la cuenta queda activa y el usuario es redirigido al dashboard principal.<br><br>
      <strong>Scenario 2: Token expirado</strong><br>
      Dado que el usuario hace clic en un enlace de verificación cuyo token ha expirado,<br>
      Cuando el sistema intenta validarlo,<br>
      Entonces muestra un mensaje de error y ofrece la opción de reenviar el email de verificación.<br><br>
      <strong>Scenario 3: Token inválido</strong><br>
      Dado que el usuario accede a un enlace de verificación con un token malformado,<br>
      Cuando el sistema intenta procesarlo,<br>
      Entonces muestra un mensaje de error indicando que el enlace no es válido.
    </td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>User Story</th>
    <th>54</th>
    <th>Epic ID</th>
    <th>14</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Iniciar sesión con credenciales</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario registrado, quiero iniciar sesión con mi email y contraseña para acceder al dashboard de Entreprenly.
    </td>
  </tr>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Inicio de sesión exitoso</strong><br>
      Dado que el usuario ingresa credenciales válidas,<br>
      Cuando envía el formulario de login,<br>
      Entonces el sistema genera un JWT, inicia la sesión y redirige al dashboard principal.<br><br>
      <strong>Scenario 2: Credenciales inválidas</strong><br>
      Dado que el usuario ingresa una contraseña incorrecta,<br>
      Cuando envía el formulario de login,<br>
      Entonces el sistema muestra un mensaje de error sin revelar cuál campo es incorrecto.<br><br>
      <strong>Scenario 3: Cuenta bloqueada por intentos fallidos</strong><br>
      Dado que el usuario ha fallado 5 intentos consecutivos de inicio de sesión,<br>
      Cuando intenta iniciar sesión nuevamente,<br>
      Entonces el sistema bloquea la cuenta y notifica al usuario por email.
    </td>
  </tr>
</table>

<table>
  <tr>
    <th>User Story</th>
    <th>55</th>
    <th>Epic ID</th>
    <th>14</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Iniciar sesión con Google OAuth</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario anónimo, quiero iniciar sesión con mi cuenta de Google para acceder a Entreprenly sin necesidad de crear credenciales nuevas.
    </td>
  </tr>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: OAuth exitoso con cuenta nueva</strong><br>
      Dado que el usuario inicia el flujo OAuth con una cuenta de Google no registrada previamente,<br>
      Cuando Google autoriza el acceso y devuelve el token,<br>
      Entonces el sistema crea una nueva cuenta vinculada al proveedor e inicia la sesión.<br><br>
      <strong>Scenario 2: OAuth exitoso con cuenta existente</strong><br>
      Dado que el usuario inicia el flujo OAuth con un email ya registrado en el sistema,<br>
      Cuando Google devuelve el token,<br>
      Entonces el sistema vincula el proveedor a la cuenta existente e inicia la sesión.<br><br>
      <strong>Scenario 3: OAuth denegado por el usuario</strong><br>
      Dado que el usuario cancela la autorización en la pantalla de Google,<br>
      Cuando el flujo OAuth es interrumpido,<br>
      Entonces el sistema redirige al usuario a la pantalla de login sin crear ninguna cuenta.
    </td>
  </tr>
</table>

<table>
  <tr>
    <th>User Story</th>
    <th>56</th>
    <th>Epic ID</th>
    <th>14</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Recuperar contraseña</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario registrado, quiero recuperar el acceso a mi cuenta mediante un enlace enviado a mi email para restablecer mi contraseña.
    </td>
  </tr>
  <br><br>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Reset exitoso</strong><br>
      Dado que el usuario solicita el reset con un email registrado y confirma la nueva contraseña desde el enlace recibido,<br>
      Cuando el sistema procesa la solicitud,<br>
      Entonces actualiza la contraseña, invalida todas las sesiones anteriores y redirige al login.<br><br>
      <strong>Scenario 2: Token de reset expirado</strong><br>
      Dado que el usuario accede al enlace de reset después de que el token ha expirado,<br>
      Cuando el sistema intenta validarlo,<br>
      Entonces muestra un mensaje de error y solicita generar un nuevo enlace.<br><br>
      <strong>Scenario 3: Email no registrado</strong><br>
      Dado que el usuario solicita el reset con un email que no existe en el sistema,<br>
      Cuando envía el formulario,<br>
      Entonces el sistema responde con un mensaje genérico sin confirmar ni negar la existencia del email.
    </td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>User Story</th>
    <th>57</th>
    <th>Epic ID</th>
    <th>14</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Cerrar sesión</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario autenticado, quiero cerrar mi sesión para que el sistema revoque mi token y me redirija a la pantalla de login.
    </td>
  </tr>
  <br><br>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Cierre de sesión exitoso</strong><br>
      Dado que el usuario hace clic en la opción de cerrar sesión,<br>
      Cuando el sistema procesa la solicitud,<br>
      Entonces revoca el JWT activo y redirige al usuario a la pantalla de login.<br><br>
      <strong>Scenario 2: Intento de acceso tras cerrar sesión</strong><br>
      Dado que el usuario ha cerrado su sesión y el token ha sido revocado,<br>
      Cuando intenta acceder a una ruta protegida,<br>
      Entonces el sistema rechaza la solicitud y redirige al login.
    </td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>User Story</th>
    <th>58</th>
    <th>Epic ID</th>
    <th>15</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Visualizar perfil actual</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario autenticado, quiero visualizar mi perfil actual para revisar mis datos registrados en la plataforma.
    </td>
  </tr>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Visualización exitosa</strong><br>
      Dado que el usuario navega a la sección de perfil,<br>
      Cuando el sistema carga los datos,<br>
      Entonces muestra nombre, bio, foto de perfil, email y preferencias actuales del usuario.<br><br>
      <strong>Scenario 2: Sesión expirada</strong><br>
      Dado que la sesión del usuario ha expirado,<br>
      Cuando intenta acceder a la sección de perfil,<br>
      Entonces el sistema redirige al login.
    </td>
  </tr>
</table>

<table>
  <tr>
    <th>User Story</th>
    <th>59</th>
    <th>Epic ID</th>
    <th>15</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Actualizar nombre y biografía</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario autenticado, quiero actualizar mi nombre y biografía para mantener mi perfil al día.
    </td>
  </tr>
  <br><br>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Actualización exitosa</strong><br>
      Dado que el usuario edita su nombre y/o bio con datos válidos,<br>
      Cuando guarda los cambios,<br>
      Entonces el sistema actualiza los datos y muestra el perfil con la información nueva.<br><br>
      <strong>Scenario 2: Campo obligatorio vacío</strong><br>
      Dado que el usuario deja el campo de nombre vacío,<br>
      Cuando intenta guardar,<br>
      Entonces el sistema muestra un error de validación sin guardar los cambios.
    </td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>User Story</th>
    <th>60</th>
    <th>Epic ID</th>
    <th>15</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Subir foto de perfil</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario autenticado, quiero subir una foto de perfil para personalizar mi cuenta en la plataforma.
    </td>
  </tr>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Subida exitosa</strong><br>
      Dado que el usuario selecciona una imagen con formato y tamaño permitidos,<br>
      Cuando la sube al sistema,<br>
      Entonces el servicio de almacenamiento guarda el archivo, actualiza la URL del avatar y muestra la nueva foto en el perfil.<br><br>
      <strong>Scenario 2: Formato de imagen no permitido</strong><br>
      Dado que el usuario intenta subir un archivo con formato no soportado,<br>
      Cuando el sistema valida el archivo,<br>
      Entonces muestra un mensaje de error indicando los formatos aceptados sin guardar el archivo.<br><br>
      <strong>Scenario 3: Tamaño de archivo excedido</strong><br>
      Dado que el usuario intenta subir una imagen que supera el tamaño máximo permitido,<br>
      Cuando el sistema valida el archivo,<br>
      Entonces muestra un mensaje de error indicando el límite de tamaño.
    </td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>User Story</th>
    <th>61</th>
    <th>Epic ID</th>
    <th>15</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Cambiar email con re-verificación</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario autenticado, quiero cambiar mi email y verificarlo para mantener mis datos de contacto actualizados.
    </td>
  </tr>
<br><br>

  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Cambio de email exitoso</strong><br>
      Dado que el usuario solicita cambiar su email a uno no registrado previamente,<br>
      Cuando confirma el nuevo email desde el enlace enviado,<br>
      Entonces el sistema actualiza el email y lo marca como verificado.<br><br>
      <strong>Scenario 2: Nuevo email ya en uso</strong><br>
      Dado que el usuario ingresa un email que ya pertenece a otra cuenta,<br>
      Cuando intenta guardar el cambio,<br>
      Entonces el sistema muestra un mensaje de error sin actualizar el email.<br><br>
      <strong>Scenario 3: Confirmación desde enlace expirado</strong><br>
      Dado que el usuario hace clic en el enlace de confirmación después de que ha expirado,<br>
      Cuando el sistema valida el token,<br>
      Entonces muestra un mensaje de error y ofrece reenviar el email de confirmación.
    </td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>User Story</th>
    <th>62</th>
    <th>Epic ID</th>
    <th>15</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Cambiar contraseña</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario autenticado, quiero cambiar mi contraseña para mantener la seguridad de mi cuenta.
    </td>
  </tr>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Cambio exitoso</strong><br>
      Dado que el usuario ingresa su contraseña actual correcta y una nueva contraseña válida,<br>
      Cuando guarda el cambio,<br>
      Entonces el sistema actualiza la contraseña e invalida todas las sesiones activas excepto la actual.<br><br>
      <strong>Scenario 2: Contraseña actual incorrecta</strong><br>
      Dado que el usuario ingresa una contraseña actual incorrecta,<br>
      Cuando intenta guardar el cambio,<br>
      Entonces el sistema muestra un error de validación sin actualizar la contraseña.<br><br>
      <strong>Scenario 3: Nueva contraseña no cumple requisitos</strong><br>
      Dado que el usuario ingresa una nueva contraseña que no cumple los requisitos mínimos,<br>
      Cuando intenta guardar,<br>
      Entonces el sistema muestra los requisitos incumplidos sin aplicar el cambio.
    </td>
  </tr>
</table>

<table>
  <tr>
    <th>User Story</th>
    <th>63</th>
    <th>Epic ID</th>
    <th>15</th>
  </tr>
  <br><br>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Configurar preferencias de idioma, zona horaria y tema</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario autenticado, quiero configurar mi idioma, zona horaria y tema visual para adaptar la plataforma a mis preferencias.
    </td>
  </tr>
  <br><br>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Cambio de idioma exitoso</strong><br>
      Dado que el usuario selecciona un idioma disponible,<br>
      Cuando guarda la preferencia,<br>
      Entonces el sistema actualiza el idioma de la interfaz de forma inmediata.<br><br>
      <strong>Scenario 2: Cambio de zona horaria exitoso</strong><br>
      Dado que el usuario selecciona una zona horaria de la lista disponible,<br>
      Cuando guarda la preferencia,<br>
      Entonces el sistema almacena la zona horaria y la aplica en las fechas mostradas.<br><br>
      <strong>Scenario 3: Cambio de tema exitoso</strong><br>
      Dado que el usuario selecciona el tema claro u oscuro,<br>
      Cuando guarda la preferencia,<br>
      Entonces el sistema aplica el tema seleccionado de forma inmediata y lo persiste para futuras sesiones.
    </td>
  </tr>
</table>
<br><br>
<table>
  <tr>
    <th>User Story</th>
    <th>64</th>
    <th>Epic ID</th>
    <th>15</th>
  </tr>
  <tr>
    <td><strong>Title</strong></td>
    <td colspan="3">Configurar notificaciones</td>
  </tr>
  <tr>
    <td><strong>Description</strong></td>
    <td colspan="3">
      Como usuario autenticado, quiero configurar mis preferencias de notificación para recibir solo los avisos que me sean relevantes.
    </td>
  </tr>
  <tr>
    <td><strong>Acceptance Criteria</strong></td>
    <td colspan="3">
      <strong>Scenario 1: Guardado exitoso de preferencias</strong><br>
      Dado que el usuario activa o desactiva tipos de notificación disponibles,<br>
      Cuando guarda los cambios,<br>
      Entonces el sistema almacena las preferencias y las aplica en los envíos futuros.<br><br>
      <strong>Scenario 2: Sin cambios realizados</strong><br>
      Dado que el usuario accede a la sección de notificaciones sin modificar nada,<br>
      Cuando sale de la sección,<br>
      Entonces el sistema mantiene las preferencias anteriores sin alteración.
    </td>
  </tr>
</table>

## 3.2. Impact Mapping

_Contenido por agregar._

## 3.3. Product Backlog

_Contenido por agregar._