# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

*Contenido por agregar.*

### 1.1.2. Perfiles de integrantes del equipo

*Contenido por agregar.*

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

*Contenido por agregar.*

### 1.2.2. Lean UX Process

En esta sección aplicamos el **Lean UX Process** (Gothelf & Seiden, 3rd Edition).
Presentamos los **Problem Statement**, **Assumptions**, **Hypothesis Statements** y el
**Lean UX Canvas**, adaptados al proyecto **Entreprenly**.

#### 1.2.2.1. Lean UX Problem Statements

**Entreprenly** se plantea como un ecosistema tecnológico de Smart Retail dirigido a
bodegas, minimarkets y puestos de mercado que necesitan sincronizar su operación diaria
con un registro digital confiable. La solución permitirá que el comerciante configure sus
productos con datos clave como peso unitario, precio, categoría, medio de venta y
ubicación dentro del negocio. A partir de ello, el sistema podrá interpretar la lectura
de las balanzas inteligentes y calcular el stock real disponible sin depender únicamente
del conteo manual.

Durante la operación del negocio, Entreprenly integrará la telemetría enviada por
sensores de peso, los eventos de venta generados en el módulo POS y los pedidos recibidos
por WhatsApp. Esta información se procesará en tiempo real para validar que cada salida
de producto coincida con el movimiento físico detectado en estantería. Cuando exista una
diferencia entre lo que el sistema registró como vendido y lo que la balanza reporte, se
generará una alerta inmediata de descuadre para que el comerciante pueda intervenir antes
de que el error escale.

Además, la solución contempla un modelo de conciliación financiera dual. Por un lado, la
**Caja Efectivo** será registrada digitalmente para apoyar el arqueo manual al cierre del
turno. Por otro lado, la **Caja Electrónica** dependerá de la confirmación de un terminal
POS físico para cerrar la venta y emitir el comprobante. De esta manera, Entreprenly
evitará registrar como completada una venta electrónica que todavía no haya sido aprobada
por el medio de pago, reduciendo el riesgo de inconsistencias entre el software y el
reporte del terminal.

Hemos identificado que muchos negocios minoristas pequeños enfrentan problemas
recurrentes: diferencias entre stock físico y stock registrado, ventas no conciliadas con
pagos electrónicos, escasa visibilidad sobre mermas o retiros no registrados y falta de
coordinación entre el canal presencial y el canal conversacional. Estos problemas generan
pérdidas económicas, decisiones tardías y desconfianza en las herramientas digitales.

**¿Cómo puede Entreprenly ayudar a los pequeños comercios minoristas a mantener su stock
físico y digital permanentemente sincronizado, y al mismo tiempo asegurar una
conciliación financiera exacta entre ventas presenciales y electrónicas, sin añadir
complejidad operativa al negocio?**

#### 1.2.2.2. Lean UX Assumptions

**Assumptions**

- Suponemos que los dueños y administradores de bodegas adoptarán Entreprenly si perciben
  que reduce pérdidas por descuadres de inventario y simplifica el cierre de caja.
- Creemos que el cálculo de stock basado en peso aportará más confianza operativa que el
  control exclusivamente manual o basado solo en registros de venta.
- Suponemos que los comerciantes estarán dispuestos a registrar el peso unitario de sus
  productos si el proceso de configuración inicial es breve y guiado.
- Creemos que las alertas en tiempo real por discrepancias entre venta y lectura física
  permitirán detectar errores, mermas o posibles robos con mayor rapidez.
- Suponemos que bloquear el cierre de ventas electrónicas hasta recibir confirmación del
  terminal POS incrementará la confiabilidad del reporte financiero.
- Creemos que la integración con WhatsApp será valiosa para negocios que ya atienden
  pedidos por chat y necesitan validar stock antes de comprometer una venta.
- Suponemos que una interfaz web simple y visual facilitará la adopción en comercios con
  baja madurez digital o con personal operativo no especializado.
- Creemos que una arquitectura asíncrona con actualizaciones en tiempo real permitirá que
  sensores, dashboard, POS y chatbot se mantengan coordinados sin frenar la operación.
- Suponemos que los comerciantes darán prioridad a tableros y notificaciones que resuman
  excepciones críticas, en lugar de reportes complejos o demasiado extensos.
- Creemos que la trazabilidad de cada evento operativo y financiero convertirá a
  Entreprenly en una solución escalable y diferenciada para el retail de pequeña escala.

**¿Quién es el usuario?**

El usuario principal de Entreprenly es el dueño, administrador o cajero de un negocio
minorista pequeño, como una bodega, minimarket o puesto de mercado, que necesita operar
con mayor control sobre su inventario y sus cobros. Se trata de personas que trabajan con
alta carga operativa, poco margen de error y recursos tecnológicos limitados, por lo que
valoran soluciones prácticas, rápidas de entender y aplicables desde el primer día.

**¿Dónde encaja nuestro producto en su trabajo o vida?**

Entreprenly se integra directamente en la operación diaria del negocio. Se utiliza al
abrir caja, registrar ventas, atender pedidos por WhatsApp, reponer productos en
estantería, revisar alertas de stock bajo y realizar el cierre financiero del turno. No
es una herramienta aislada, sino un sistema que acompaña el flujo operativo real del
comerciante durante toda la jornada.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**

- Problema: La precisión del inventario por peso depende de una correcta calibración
  inicial y de pesos unitarios bien definidos.
  Solución: Implementar un flujo guiado de configuración, calibración y validación para
  cada producto sensorizado.
- Problema: En negocios con conectividad inestable, la confirmación de sensores o pagos
  podría sufrir retrasos y generar incertidumbre operativa.
  Solución: Diseñar estados transitorios claros, reintentos automáticos y trazabilidad de
  eventos pendientes para evitar ambigüedad.
- Problema: Los comerciantes pueden percibir el sistema como complejo si reciben demasiada
  información técnica al mismo tiempo.
  Solución: Priorizar una experiencia centrada en excepciones, con alertas claras,
  indicadores resumidos y acciones sugeridas.

**¿Cuándo y cómo es usado nuestro producto?**

Entreprenly se utilizará durante momentos críticos de la operación: al iniciar el turno,
al procesar una venta presencial, al aceptar un pedido por WhatsApp, al detectar una
variación inesperada en una balanza y al cerrar caja. El uso esperado será breve, pero
recurrente y en tiempo real, con consultas rápidas al dashboard, revisión de alertas y
confirmación de transacciones.

**¿Qué características son importantes?**

- **Validación de stock en tiempo real** a partir de la relación entre peso total y peso
  unitario.
- **Alertas de descuadre** para detectar diferencias entre movimientos físicos y ventas
  registradas.
- **Conciliación financiera dual** con separación clara entre caja de efectivo y caja
  electrónica.
- **Integración omnicanal** para atender ventas presenciales y pedidos por WhatsApp con la
  misma fuente de verdad de inventario.
- **Trazabilidad operativa** de lecturas IoT, ventas, ajustes, cobros y cierres.
- **Usabilidad** con una interfaz comprensible, rápida y enfocada en decisiones operativas.

**¿Cómo debe verse nuestro producto y cómo debe comportarse?**

Entreprenly debe transmitir control, precisión y confiabilidad. La interfaz debe ser
clara, ordenada y muy visual, con estados de stock fáciles de identificar, alertas
operativas destacadas y flujos de venta simples. Su comportamiento debe ser responsivo,
consistente y orientado a tiempo real, de modo que el usuario perciba que el sistema
refleja fielmente lo que ocurre en el negocio físico.

**Business outcomes**

- Reducir los descuadres entre inventario físico y digital en negocios minoristas.
- Asegurar que las ventas electrónicas conciliadas en el sistema coincidan con el reporte
  del terminal POS.
- Disminuir el tiempo invertido por el comerciante en conteos manuales y cierres de caja.
- Mejorar la capacidad de respuesta ante quiebres de stock, mermas o anomalías operativas.
- Posicionar a Entreprenly como una solución escalable de Smart Retail para microcomercios.

**User**

Nuestro usuario central es el comerciante minorista que necesita mantener el control de
su operación sin incorporar procesos complejos ni herramientas difíciles de aprender.
Busca visibilidad inmediata sobre stock, ventas y cobros para tomar decisiones rápidas y
disminuir pérdidas.

**Users outcomes**

- Los usuarios podrán conocer el stock real disponible de sus productos sin depender solo
  del conteo manual.
- Los usuarios detectarán discrepancias operativas con mayor rapidez y podrán intervenir a
  tiempo.
- Los usuarios cerrarán su caja con mayor confianza al separar y validar correctamente los
  pagos en efectivo y electrónicos.
- Los usuarios podrán aceptar pedidos por WhatsApp con mayor seguridad al validar stock en
  tiempo real.
- Los usuarios contarán con un historial claro de eventos para auditar ventas, ajustes y
  movimientos de inventario.

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Creemos que**, si Entreprenly compara en tiempo real las ventas registradas con las
  variaciones de peso detectadas por las balanzas, entonces los comerciantes podrán
  identificar descuadres de inventario con mucha más anticipación. **Sabremos que hemos
  tenido éxito cuando** los negocios piloto reduzcan en al menos 60% sus discrepancias de
  stock al cierre del primer mes de uso.
- **Creemos que**, si el sistema exige confirmación del terminal POS antes de marcar como
  completada una venta electrónica y emitir el comprobante, entonces la conciliación de la
  caja electrónica será más precisa. **Sabremos que vamos por buen camino cuando** el
  100% de las transacciones electrónicas del piloto coincida con el reporte diario del
  terminal POS.
- **Creemos que**, si los pedidos por WhatsApp consultan stock validado por sensores antes
  de confirmar la venta, entonces disminuirán las cancelaciones por falta de inventario o
  desinformación. **Sabremos que hemos tenido éxito cuando** al menos el 90% de los
  pedidos confirmados por el chatbot se despache sin incidentes de stock.
- **Creemos que**, si el dashboard centraliza alertas de descuadre, stock bajo, movimientos
  de caja y telemetría IoT en una interfaz simple, entonces los comerciantes tomarán
  decisiones operativas más rápidas y confiables. **Sabremos que hemos tenido éxito
  cuando** el tiempo promedio de cierre de caja se reduzca en al menos 50% durante el
  piloto.

#### 1.2.2.4. Lean UX Canvas

<table>
  <tr>
    <td valign="top">
      <strong>1) Problema de negocio</strong><br><br>
      Muchos negocios minoristas pequeños operan con inventarios registrados manualmente y
      con ventas electrónicas que no siempre quedan conciliadas con precisión. Esto genera
      descuadres entre stock físico y digital, errores en el cierre de caja y poca
      visibilidad sobre mermas, robos o faltantes. En ese contexto, Entreprenly busca
      responder a la siguiente pregunta: ¿cómo digitalizar la operación de bodegas,
      minimarkets y puestos de mercado para que controlen su inventario real y concilien
      sus ventas presenciales y electrónicas sin agregar fricción al trabajo diario?
    </td>
    <td rowspan="2" valign="top">
      <strong>5) Ideas de soluciones</strong>
      <ul>
        <li>Dashboard web para monitorear stock, alertas, ventas y cierres de caja en tiempo real.</li>
        <li>Balanzas inteligentes o simuladas que envían telemetría constante para calcular stock por peso.</li>
        <li>Motor de alertas para detectar descuadres entre ventas registradas y movimientos físicos.</li>
        <li>Flujo POS que solo confirma la venta electrónica cuando el terminal físico aprueba el cobro.</li>
        <li>Canal de pedidos por WhatsApp con consulta de stock validado antes de confirmar la compra.</li>
        <li>Registro separado de caja efectivo y caja electrónica para conciliación dual.</li>
        <li>Bitácora de eventos operativos y financieros para auditoría y trazabilidad.</li>
        <li>Notificaciones en tiempo real con SignalR para cambios críticos en la operación.</li>
      </ul>
    </td>
    <td valign="top">
      <strong>2) Resultados comerciales</strong>
      <ul>
        <li>Reducir en al menos 60% los descuadres de inventario en los comercios piloto.</li>
        <li>Lograr una conciliación del 100% entre ventas electrónicas y reportes del terminal POS.</li>
        <li>Disminuir en 50% el tiempo promedio dedicado al cierre de caja diario.</li>
        <li>Alcanzar al menos 20 comercios activos durante la etapa inicial de validación.</li>
        <li>Incrementar la confianza del comerciante en el registro digital como fuente principal de control.</li>
        <li>Validar un modelo escalable de Smart Retail para microempresas del sector comercio.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <strong>3) Usuarios y clientes</strong><br><br>
      Nuestros usuarios principales son dueños, administradores y cajeros de bodegas,
      minimarkets y puestos de mercado que operan con alta presión diaria y poco margen de
      error. Necesitan controlar inventario, validar pagos y responder rápido a sus
      clientes, pero muchas veces carecen de sistemas confiables o integrados. También
      existen usuarios secundarios, como compradores que realizan pedidos por WhatsApp y
      esperan confirmaciones de stock y pago sin fricciones.
    </td>
    <td valign="top">
      <strong>4) Beneficios del usuario</strong>
      <ul>
        <li>Mayor visibilidad del stock real sin depender únicamente de conteos manuales.</li>
        <li>Detección temprana de pérdidas, mermas o inconsistencias operativas.</li>
        <li>Cierre de caja más confiable gracias a la separación y validación de medios de pago.</li>
        <li>Menor riesgo de aceptar pedidos sin stock disponible en canales digitales.</li>
        <li>Trazabilidad clara de ventas, ajustes y movimientos para tomar mejores decisiones.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <strong>6) Hipótesis</strong>
      <ul>
        <li>Creemos que, si se comparan ventas y lecturas de peso en tiempo real, los comercios detectarán antes los descuadres de inventario. Sabremos que funciona si las discrepancias de stock se reducen en al menos 60% durante el primer mes.</li>
        <li>Creemos que exigir la confirmación del terminal POS antes de cerrar la venta electrónica eliminará inconsistencias financieras. Sabremos que vamos por buen camino si el 100% de las transacciones electrónicas coincide con el reporte del terminal.</li>
        <li>Creemos que validar stock antes de aceptar pedidos por WhatsApp reducirá cancelaciones y reclamos. Sabremos que funciona si al menos el 90% de los pedidos confirmados se atiende sin incidentes de inventario.</li>
        <li>Creemos que un dashboard simple con alertas, telemetría y cajas separadas acelerará las decisiones operativas. Sabremos que hemos tenido éxito si el tiempo de cierre de caja baja en 50% durante el piloto.</li>
      </ul>
    </td>
    <td valign="top">
      <strong>7) ¿Qué es lo más importante que necesitamos aprender primero?</strong><br><br>
      Lo primero que debemos validar es si los comerciantes realmente confían en el modelo
      de inventario por peso y si están dispuestos a usarlo como fuente principal para
      tomar decisiones de venta, reposición y control. La propuesta de valor depende de
      que el usuario perciba que la lectura física del anaquel y la conciliación del pago
      electrónico representan la realidad del negocio mejor que sus procesos manuales
      actuales.
    </td>
    <td valign="top">
      <strong>8) ¿Cuál es la menor cantidad de trabajo que necesitamos hacer para resolver las dudas y para hacer lo siguiente más importante?</strong><br><br>
      El siguiente paso clave es lanzar un MVP enfocado en una operación reducida: un
      conjunto pequeño de productos sensorizados, un dashboard básico de monitoreo, un
      flujo POS con confirmación electrónica y un chatbot de WhatsApp para pedidos de ese
      catálogo. Esta versión mínima debe probarse durante 2 o 3 semanas en un grupo piloto
      de comercios para medir precisión del stock, tiempos de cierre de caja,
      cancelaciones de pedidos y percepción de confianza. Con esos resultados se podrá
      ajustar el modelo antes de ampliar el alcance funcional y comercial.
    </td>
  </tr>
</table>

## 1.3. Segmentos objetivo

*Contenido por agregar.*
