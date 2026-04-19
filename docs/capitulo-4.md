# Capítulo IV: Product Design

## 4.1. Style Guidelines

Esta sección define los lineamientos de estilo que aseguran una identidad visual consistente, accesible y escalable en todas las interfaces del proyecto (web y móvil). Aquí se establecen los criterios de marca (logo, tono), tipografía, paleta de colores, espaciado y grid, así como estados e interacción (focus, hover, error) con enfoque en WCAG. Además, se especifican tokens de diseño y reglas responsive para facilitar la implementación y el mantenimiento entre equipos de diseño y desarrollo. Estos lineamientos actúan como fuente única de verdad, garantizando coherencia y calidad a medida que el producto evoluciona.

---

### 4.1.1. General Style Guidelines.

**Paleta de Colores**

- **Colores Primarios**

<table>
  <thead>
    <tr>
      <th><strong>Código HEX</strong></th>
      <th><strong>Color</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>#F38313</strong></td>
      <td><img src="images/_F38313.png" alt="#F38313" width="60" height="40" style="border-radius:4px;display:block;"></td>
      <td>Es un tono vibrante y enérgico que comunica dinamismo y acción. <br>
      Se utiliza como color de acento principal para botones de llamada a la acción (CTA) y elementos críticos de la marca, asegurando una alta visibilidad.</td>
    </tr>
    <tr>
      <td><strong>#FCE0D4</strong></td>
      <td><img src="images/_FCE0D4.png" alt="#FCE0D4" width="60" height="40" style="border-radius:4px;display:block;border:1px solid #ccc;"></td>
      <td>Tono melocotón claro que aporta calidez y cercanía.
      <br> Se emplea en fondos de tarjetas y estados de selección suave, proporcionando un contraste armonioso con el naranja principal sin saturar la interfaz.</td>
    </tr>
    <tr>
      <td><strong>#0C0F12</strong></td>
      <td><img src="images/_0C0F12.png" alt="#0C0F12" width="60" height="40" style="border-radius:4px;display:block;"></td>
      <td>Color sólido y profundo utilizado para la tipografía principal y encabezados.
      <br> Garantiza el cumplimiento de las normas de accesibilidad (WCAG) al ofrecer un contraste máximo sobre fondos claros.</td>
    </tr>
    <tr>
      <td><strong>#F6F4F4</strong></td>
      <td><img src="images/_F6F4F4.png" alt="#F6F4F4" width="60" height="40" style="border-radius:4px;display:block;border:1px solid #ccc;"></td>
      <td>Un tono blanco con una mínima calidez que sirve como lienzo principal para la aplicación, evitando el deslumbramiento y proporcionando una sensación de orden y amplitud.</td>
    </tr>
  </tbody>
</table>

- **Colores Secundarios**

<table>
  <thead>
    <tr>
      <th><strong>Código HEX</strong></th>
      <th><strong>Color</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>#7679DE</strong></td>
      <td><img src="images/_7679DE.png" alt="#7679DE" width="60" height="40" style="border-radius:4px;display:block;"></td>
      <td>Representa la vertiente tecnológica del proyecto.
      <br> Es un tono azulado con matices lavanda que transmite confianza y modernidad, ideal para enlaces, iconos de navegación y elementos interactivos web.</td>
    </tr>
    <tr>
      <td><strong>#C2CDFC</strong></td>
      <td><img src="images/_C2CDFC.png" alt="#C2CDFC" width="60" height="40" style="border-radius:4px;display:block;border:1px solid #ccc;"></td>
      <td>Variante clara y relajada del azul principal.
      <br> Se utiliza para resaltar componentes secundarios y áreas de información técnica, manteniendo una estética limpia y profesional.</td>
    </tr>
    <tr>
      <td><strong>#C9C9C9</strong></td>
      <td><img src="images/_C9C9C9.png" alt="#C9C9C9" width="60" height="40" style="border-radius:4px;display:block;"></td>
      <td>Tono neutro destinado a bordes, divisores y estados inactivos. 
      <br> Su función es estructurar la interfaz de manera sutil sin distraer al usuario de las tareas principales.</td>
    </tr>
    <tr>
      <td><strong>#666666</strong></td>
      <td><img src="images/_666666.png" alt="#666666" width="60" height="40" style="border-radius:4px;display:block;"></td>
      <td>Tono neutro destinado a bordes, divisores y estados inactivos.<br> 
      Su función es estructurar la interfaz de manera sutil sin distraer al usuario de las tareas principales.</td>
    </tr>
    <tr>
      <td><strong>#F1F1F1</strong></td>
      <td><img src="images/_F1F1F1.png" alt="#F1F1F1" width="60" height="40" style="border-radius:4px;display:block;border:1px solid #ccc;"></td>
      <td>Gris muy claro utilizado en fondos de secciones y contenedores de datos (como tablas de productos) para separar visualmente diferentes bloques de contenido.</td>
    </tr>
    <tr>
      <td><strong>#FD4444</strong></td>
      <td><img src="images/_FD4444.png" alt="#FD4444" width="60" height="40" style="border-radius:4px;display:block;"></td>
      <td>Color de alta intensidad para estados de alerta. 
      <br>Comunica urgencia y se reserva exclusivamente para mensajes de error, eliminación de registros o indicadores de stock crítico.</td>
    </tr>
    <tr>
      <td><strong>#70D399</strong></td>
      <td><img src="images/_70D399.png" alt="#70D399" width="60" height="40" style="border-radius:4px;display:block;"></td>
      <td>Tono orgánico que representa éxito y crecimiento. <br>
      Se utiliza en notificaciones de confirmación, transacciones finalizadas y estados positivos del inventario.</td>
    </tr>
    <tr>
      <td><strong>#FFF7E1</strong></td>
      <td><img src="images/_FFF7E1.png" alt="#FFF7E1" width="60" height="40" style="border-radius:4px;display:block;border:1px solid #ccc;"></td>
      <td>Tono suave y luminoso similar al <em>Lemon Chiffon</em>, que comunica amabilidad y optimismo. <br>
      Se recomienda como fondo para banners informativos o etiquetas de ayuda, cuidando el contraste con textos oscuros.</td>
    </tr>
    <tr>
      <td><strong>#C79D08</strong></td>
      <td><img src="images/_C79D08.png" alt="#C79D08" width="60" height="40" style="border-radius:4px;display:block;"></td>
      <td>Color mostaza oscuro utilizado para advertencias preventivas que requieren atención moderada sin llegar a ser una alerta de error.</td>
    </tr>
  </tbody>
</table>

---

**Fonts**

Hemos seleccionado cuidadosamente estas tipografías para Entreprenly, buscando un equilibrio armónico entre claridad, profesionalismo y modernidad que refuerce nuestros valores de eficiencia, gestión inteligente y apoyo al micro-emprendedor. La combinación de Reddit Sans para títulos y Roboto para textos técnicos potencia la legibilidad en web y móvil, proyecta una identidad tecnológica y accesible, y acompaña con coherencia los flujos clave de inventario, ventas y soporte, asegurando una experiencia consistente, robusta y fácil de usar en toda la plataforma.

<p align="center">
  <img src="images/Jerarquia_Tipografica.png" alt="Jerarquia_Tipografica" width="500"/>
</p>


- Reddit Sans fue elegida para los títulos por su estilo contemporáneo y geométrico, aportando una presencia clara y profesional que resalta el carácter innovador y eficiente de Entreprenly.

- Reddit Sans (Semibold - 40 px) asegura jerarquías nítidas en los encabezados principales (H1), permitiendo que el usuario identifique rápidamente la sección en la que se encuentra sin sacrificar legibilidad en dispositivos de escritorio.

- Reddit Sans (Bold - 24 px / 20 px) se utiliza en títulos de botones, encabezados secundarios y textos de énfasis por su equilibrio entre personalidad y orden visual, facilitando una lectura rápida en tarjetas de productos, formularios de ventas y menús de navegación.

- Roboto se escogió para textos extensos y datos técnicos por su alta legibilidad y versatilidad en entornos de desarrollo, garantizando una lectura fluida y cómoda en párrafos, tablas de lotes y microcopy, ideal para mejorar la precisión operativa del usuario en la interfaz.

---

**Espaciado y márgenes**

**Márgenes generales y contenedores:** Se establece un margen estándar de **16 px** para las separaciones internas de los contenedores de productos y lotes, optimizando el aprovechamiento del espacio en la interfaz web.

**Márgenes alrededor de elementos interactivos:** Se mantienen entre **16 px y 20 px** (según el breakpoint) en botones y controles de formularios para asegurar un área de clic adecuada y evitar toques accidentales.

**Interlineado en textos:** Se aplica un valor de **1.5×** el tamaño de la fuente (mínimo **1.55** para párrafos extensos) para garantizar una lectura cómoda de las descripciones y reportes.

**Separación ícono–texto:** Se define un espaciado fijo de **8 px** para mantener la proximidad visual entre el símbolo gráfico y su etiqueta correspondiente en menús y botones.

**Ritmo 8-pt recomendado:** Se utiliza un sistema de espaciado basado en múltiplos de **8 (8/16/24/32 px)** entre bloques de contenido y secciones principales para mantener la coherencia visual y un orden matemático en todo el layout.

---

**Branding y logo**

El diseño visual de **Entreprenly** se ha desarrollado para proyectar una imagen sólida y profesional, alineada con los estándares del sector empresarial y tecnológico. Sus elementos se definen de la siguiente manera:

- **Símbolo de Crecimiento (Isotipo):** El icono situado a la derecha del nombre utiliza formas ascendentes y modulares que evocan conceptos de **crecimiento progresivo, constancia y seguridad**. Su estructura geométrica refuerza la identidad empresarial del proyecto, simbolizando la evolución y solidez que un emprendedor busca alcanzar mediante el uso de la plataforma.

- **Identidad Cromática:** La paleta se limita estrictamente a los tonos **Naranja (#F38313)**, **Negro (#0C0F12)** y **Blanco (#F6F4F4)**. Esta combinación ha sido elegida para representar un **nivel señorial y de prestigio**; el naranja aporta la energía de la innovación, mientras que el negro otorga la seriedad y autoridad necesaria en un entorno de gestión de negocios.

- **Naming y Tipografía:** El nombre **"Entreprenly"** establece una relación directa con el ámbito empresarial y el emprendimiento moderno. Se presenta en una tipografía clara y robusta que garantiza legibilidad, transmitiendo una imagen de software confiable y de alta gama.

<p align="center">
  <img src="images/entrepenly.png" alt="entrepenly.png" width="500"/>
</p>

---

### 4.1.2. Web Style Guidelines.

Esta sección establece los estándares visuales y de interacción que rigen la experiencia de escritorio de Entreprenly. Partiendo del sistema de diseño definido en las General Style Guidelines, aquí se especifica cómo cada decisión de color, tipografía, iconografía y componente se traduce en patrones concretos y reproducibles para la interfaz web responsiva. El objetivo es garantizar coherencia entre los equipos de diseño y desarrollo, así como una experiencia profesional, accesible y alineada con la identidad de la plataforma en todos los puntos de contacto digitales.

---

**Estructura de la página**

La interfaz web de Entreprenly se articula en tres zonas funcionales: un encabezado fijo (Header), un área de contenido central (Body) y un pie de página informativo (Footer). Esta distribución garantiza orientación permanente del usuario, acceso inmediato a las acciones prioritarias y coherencia estructural entre el Landing Page y la Web Application.

<table>
  <thead>
    <tr>
      <th><strong>Ubicación</strong></th>
      <th><strong>Contenido</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Parte superior fija (sticky)</strong></td>
      <td>
        <strong> Logotipo Entreprenly:</strong> posicionado a la izquierda; enlace directo al Dashboard principal.<br>
        <strong>Búsqueda global:</strong> campo centralizado con autocompletado por nombre de producto, categoría o módulo de microlearning.<br>
        <strong>Menú principal:</strong> enlaces a Inicio, Productos, Lotes, Ventas, Pedidos, Suscripción, Chatbot, Ayuda.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th><strong>Ubicación</strong></th>
      <th><strong>Contenido</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Zona central de mayor ancho</strong></td>
      <td>
        <strong>Dashboard de indicadores:</strong> KPIs de ventas diarias, stock crítico y lotes próximos a vencer en tarjetas de resumen.<br>
        <strong>Catálogo de productos:</strong> grilla de tarjetas con imagen, nombre, stock, precio y acceso rápido a edición.<br>
        <strong>Panel lateral de filtros:</strong> categoría, estado de stock, tipo de medición, rango de fechas.<br>
        <strong>Espaciado entre bloques:</strong> separación de 16–32 px entre secciones para evitar saturación visual.
      </td>
    </tr>
  </tbody>
</table>

---

**Tipografía**

En la interfaz web de escritorio, la jerarquía tipográfica de Entreprenly se aplica con valores de tamaño fijos para resoluciones de escritorio (≥ 1025 px). Reddit Sans lidera las jerarquías de título por su carácter contemporáneo y profesional; Roboto asegura la máxima legibilidad en cuerpos de texto extensos, tablas de datos y microcopy operativo.

<table>
  <thead>
    <tr>
      <th><strong>Uso</strong></th>
      <th><strong>Fuente</strong></th>
      <th><strong>Tamaño / Peso</strong></th>
      <th><strong>Responsive (clamp)</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Título H1</strong></td>
      <td>Reddit Sans</td>
      <td>40 px / Semibold</td>
      <td>clamp(28px, 2.5vw + 12px, 40px)</td>
    </tr>
    <tr>
      <td><strong>Título H2</strong></td>
      <td>Reddit Sans</td>
      <td>32 px / Semibold</td>
      <td>clamp(22px, 2vw + 10px, 32px)</td>
    </tr>
    <tr>
      <td><strong>Título H3 / Botón</strong></td>
      <td>Reddit Sans</td>
      <td>24 px / Bold</td>
      <td>clamp(18px, 1.5vw + 8px, 24px)</td>
    </tr>
    <tr>
      <td><strong>Subtítulo / Énfasis</strong></td>
      <td>Reddit Sans</td>
      <td>20 px / Bold</td>
      <td>clamp(17px, 1.2vw + 7px, 20px)</td>
    </tr>
    <tr>
      <td><strong>Cuerpo de texto</strong></td>
      <td>Roboto</td>
      <td>16 px / Regular · lh 1.55</td>
      <td>clamp(15px, 0.6vw + 12px, 16px)</td>
    </tr>
    <tr>
      <td><strong>Texto de apoyo</strong></td>
      <td>Roboto</td>
      <td>15 px / Regular · lh 1.50</td>
      <td>clamp(14px, 0.5vw + 11px, 15px)</td>
    </tr>
    <tr>
      <td><strong>Microcopy / Badge</strong></td>
      <td>Reddit Sans</td>
      <td>10 px / Bold · uppercase</td>
      <td>Fijo — no escala</td>
    </tr>
  </tbody>
</table>

---

**Colores (paleta y contraste)**

La aplicación cromática en la interfaz web de Entreprenly sigue una distribución semántica estricta que refuerza la identidad de marca, la accesibilidad WCAG 2.1 AA y la claridad operativa del micro-emprendedor. El Naranja (#F38313) concentra toda la energía de la acción, mientras que el Negro (#0C0F12) aporta la seriedad y el peso visual necesarios en una plataforma de gestión de negocios.

<table>
  <thead>
    <tr>
      <th><strong>Uso en interfaz web</strong></th>
      <th><strong>Color / HEX</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Botón CTA principal, ícono activo, borde de enfoque</strong></td>
      <td><img src="images/_F38313.png" alt="#F38313" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;"><code>#F38313</code></td>
      <td><strong>Naranja principal de Entreprenly:</strong> concentra la llamada a la acción en botones 'Registrar venta', 'Agregar producto' y 'Guardar lote'. Garantiza contraste ≥ 4.5:1 sobre fondo blanco.</td>
    </tr>
    <tr>
      <td><strong>Fondo de tarjeta seleccionada, hover suave, chip de categoría</strong></td>
      <td><img src="images/_FCE0D4.png" alt="#FCE0D4" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;border:1px solid #ccc;"><code>#FCE0D4</code></td>
      <td><strong>Naranja tenue:</strong> estado de selección activa en tarjetas de producto y microlearning. Comunica proximidad sin la intensidad del naranja primario.</td>
    </tr>
    <tr>
      <td><strong>Tipografía principal, fondo de sidebar, elementos de autoridad</strong></td>
      <td><img src="images/_0C0F12.png" alt="#0C0F12" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;"><code>#0C0F12</code></td>
      <td><strong>Negro profundo de Entreprenly:</strong> utilizado en la barra lateral de navegación, encabezados de módulo y texto principal. Máximo contraste sobre fondos claros; transmite seriedad y profesionalismo.</td>
    </tr>
    <tr>
      <td><strong>Fondo general de la aplicación, superficies de tarjeta</strong></td>
      <td><img src="images/_F6F4F4.png" alt="#F6F4F4" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;border:1px solid #ccc;"><code>#F6F4F4</code></td>
      <td><strong>Blanco cálido:</strong> lienzo principal de la interfaz. Evita el deslumbramiento de un blanco puro y proporciona una sensación de amplitud y orden en el dashboard.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th><strong>Uso en interfaz web</strong></th>
      <th><strong>Color / HEX</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Fondos de sección, contenedores de tabla</strong></td>
      <td><img src="images/_F1F1F1.png" alt="#F1F1F1" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;border:1px solid #ccc;"><code>#F1F1F1</code></td>
      <td><strong>Gris claro:</strong> fondo alternado en tablas de lotes y ventas. Separa bloques de contenido sin introducir ruido visual.</td>
    </tr>
    <tr>
      <td><strong>Bordes de tarjeta, divisores, líneas de tabla</strong></td>
      <td><img src="images/_C9C9C9.png" alt="#C9C9C9" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;"><code>#C9C9C9</code></td>
      <td><strong>Gris de estructura:</strong> delimita tarjetas, campos de formulario y filas de tabla con sutileza. No compite con los elementos de acción.</td>
    </tr>
    <tr>
      <td><strong>Texto secundario, metadatos, placeholders</strong></td>
      <td><img src="images/_666666.png" alt="#666666" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;"><code>#666666</code></td>
      <td><strong>Gris medio:</strong> fechas de vencimiento, nombres de marca en catálogo, descripciones breves. Cumple el mínimo de contraste 4.5:1 sobre #F6F4F4.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th><strong>Estado / Uso</strong></th>
      <th><strong>Color / HEX</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Error, stock crítico, alerta de eliminación</strong></td>
      <td><img src="images/_FD4444.png" alt="#FD4444" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;"><code>#FD4444</code></td>
      <td><strong>Rojo de alerta:</strong> exclusivo para mensajes de error en formularios, indicadores de stock en cero y confirmación de eliminación de registros.</td>
    </tr>
    <tr>
      <td><strong>Éxito, venta confirmada, stock saludable</strong></td>
      <td><img src="images/_70D399.png" alt="#70D399" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;"><code>#70D399</code></td>
      <td><strong>Verde de confirmación:</strong> notificaciones de venta registrada, lote creado y módulo de microlearning completado.</td>
    </tr>
    <tr>
      <td><strong>Advertencia, lote próximo a vencer</strong></td>
      <td><img src="images/_C79D08.png" alt="#C79D08" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;"><code>#C79D08</code></td>
      <td><strong>Amarillo-mostaza:</strong> alertas de vencimiento próximo y situaciones que requieren atención moderada sin llegar al nivel de error crítico.</td>
    </tr>
    <tr>
      <td><strong>Información, enlaces, estados focus</strong></td>
      <td><img src="images/_7679DE.png" alt="#7679DE" width="60" height="36" style="border-radius:4px;display:block;margin-bottom:4px;"><code>#7679DE</code></td>
      <td><strong>Azul-lavanda:</strong> hipervínculos, indicadores de focus en inputs y botones secundarios de naturaleza informativa.</td>
    </tr>
  </tbody>
</table>

---

**Iconografía**

La iconografía de Entreprenly en la interfaz web sigue un estilo de trazo lineal (outline) coherente con la tipografía Reddit Sans. Los íconos apoyan visualmente cada acción del micro-emprendedor: registrar ventas, gestionar lotes, acceder a módulos de aprendizaje y navegar entre secciones.

<table>
  <thead>
    <tr>
      <th><strong>Aspecto</strong></th>
      <th><strong>Especificación</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Estilo</strong></td>
      <td>Trazo lineal (outline), esquinas levemente redondeadas, peso de trazo uniforme de 1.5 px. Familia recomendada: Material Symbols Outlined o equivalente de trazo abierto.</td>
    </tr>
    <tr>
      <td><strong>Tamaños</strong></td>
      <td>Base de 24 px en navegación y botones; 20 px en campos de formulario; 16 px en microcopy; 32 px en encabezados de módulo y KPIs del dashboard.</td>
    </tr>
    <tr>
      <td><strong>Color según estado</strong></td>
      <td>#F38313 en acciones primarias activas; #0C0F12 en navegación general; #666666 en estados inactivos; #FD4444 en alerta; #70D399 en confirmación; #C79D08 en advertencia.</td>
    </tr>
    <tr>
      <td><strong>Accesibilidad</strong></td>
      <td>Cada ícono interactivo debe incluir aria-label descriptivo o texto visible acompañante. Ningún estado o acción puede depender exclusivamente del ícono sin etiqueta.</td>
    </tr>
    <tr>
      <td><strong>Espaciado ícono–texto</strong></td>
      <td>Separación fija de 8 px entre el ícono y su etiqueta de texto en botones y ítems de menú, conforme al ritmo 8-pt del sistema general.</td>
    </tr>
  </tbody>
</table>

---

**Componentes clave (web)**

Los siguientes componentes conforman el vocabulario visual interactivo de la interfaz web de Entreprenly. Cada especificación define el estilo base, los estados de interacción y el uso semántico del Naranja (#F38313) y el Negro (#0C0F12) como ejes cromáticos de la plataforma.

<table>
  <thead>
    <tr>
      <th><strong>Componente</strong></th>
      <th><strong>Estilo base</strong></th>
      <th><strong>Variantes / Estados</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="3" style="background-color:#0C0F12;color:#ffffff;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">BOTONES</td>
    </tr>
    <tr>
      <td><strong>Botón primario (CTA)</strong></td>
      <td> Fondo #F38313<br>  texto #F6F4F4 <br> Reddit Sans 24 px Bold <br> border-radius 8 px <br> padding 12 px 24 px.</td>
      <td><strong>Hover:</strong> fondo oscurecido al 8% (#D97210). <br> <strong>Focus:</strong> outline 3 px #7679DE.<br> <strong>Disabled:</strong> fondo #C9C9C9 · texto #666666 · no interactivo.</td>
    </tr>
    <tr>
      <td><strong>Botón secundario</strong></td>
      <td>Borde 1.5 px #F38313 <br> fondo transparente <br> texto #F38313 <br> Reddit Sans 20 px Bold <br> border-radius 8 px.</td>
      <td><strong>Hover:</strong> fondo #FCE0D4 (naranja tenue). <br> <strong>Focus:</strong> outline 3 px #7679DE. <br> <strong>Disabled:</strong> borde y texto #C9C9C9.</td>
    </tr>
    <tr>
      <td><strong>Botón destructivo</strong></td>
      <td>Fondo #FD4444 <br> texto #F6F4F4 <br> Reddit Sans 20 px Bold <br> border-radius 8 px.</td>
      <td>Requiere confirmación modal antes de ejecutar.<br> <strong>Hover:</strong> #C73535. Solo visible en acciones de eliminación.</td>
    </tr>
    <tr>
      <td colspan="3" style="background-color:#0C0F12;color:#ffffff;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">FORMULARIOS E INPUTS</td>
    </tr>
    <tr>
      <td><strong>Campo de texto (Input)</strong></td>
      <td>Borde 1 px #C9C9C9 <br> fondo #F6F4F4 <br> Roboto 16 px Regular <br> border-radius 6 px <br> padding 10 px 16 px.</td>
      <td><strong>Focus:</strong> borde 2 px #F38313 + glow sutil rgba(243,131,19,0.15).<br> <strong>Error:</strong> borde #FD4444 + mensaje Roboto 13 px bajo el campo. <br> <strong>Éxito:</strong> borde #70D399.</td>
    </tr>
    <tr>
      <td><strong>Selector / Dropdown</strong></td>
      <td>Mismo estilo que Input<br> ícono chevron 16 px #666666 a la derecha.</td>
      <td><strong>Abierto:</strong> fondo #F6F4F4 · sombra 0 4px 12px rgba(12,15,18,0.12).<br><strong>Ítem hover:</strong> fondo #FCE0D4.</td>
    </tr>
    <tr>
      <td colspan="3" style="background-color:#0C0F12;color:#ffffff;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">TARJETAS</td>
    </tr>
    <tr>
      <td><strong>Tarjeta de producto / lote</strong></td>
      <td>Fondo #F6F4F4 <br> borde 1 px #C9C9C9 <br> border-radius 12 px <br> sombra 0 2px 8px rgba(12,15,18,0.06) <br> padding 16 px.</td><br>
      <td><strong>Hover:</strong> sombra 0 4px 16px rgba(12,15,18,0.12) + borde superior 3 px #F38313. Badge de estado en esquina superior derecha (verde/rojo/amarillo).</td>
    </tr>
    <tr>
      <td><strong>Tarjeta KPI (dashboard)</strong></td>
      <td>Fondo #F6F4F4 <br> cifra en Reddit Sans 32 px Bold #0C0F12 <br> etiqueta Roboto 14 px #666666 <br> ícono 32 px #F38313.</td>
      <td><strong>Estado crítico:</strong> borde izquierdo 4 px #FD4444. <br><strong>Estado advertencia:</strong> borde izquierdo 4 px #C79D08. <strong><br>Estado positivo:</strong> borde izquierdo 4 px #70D399.</td>
    </tr>
    <tr>
      <td colspan="3" style="background-color:#0C0F12;color:#ffffff;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">NAVEGACIÓN</td>
    </tr>
    <tr>
      <td><strong>Sidebar de navegación</strong></td>
      <td>Fondo #0C0F12 <br>ancho fijo 220 px <br> ítems Roboto 15 px Medium #F6F4F4 <br> ícono 20 px por ítem <br> padding ítem 12 px 16 px.</td>
      <td><strong>Ítem activo:</strong> fondo #F38313 · texto #0C0F12 Bold · borde-radius 8 px. <br><strong>Hover:</strong> fondo rgba(243,131,19,0.15).</td>
    </tr>
    <tr>
      <td><strong>Breadcrumb</strong></td>
      <td>Roboto 14 px Regular #666666 <br> último ítem #0C0F12 Bold.</td>
      <td>Máximo 4 niveles visibles. El nivel activo no es enlace. Separación 8 px entre ítems.</td>
    </tr>
    <tr>
      <td colspan="3" style="background-color:#0C0F12;color:#ffffff;font-weight:bold;text-align:center;padding:8px 12px;letter-spacing:0.05em;">NOTIFICACIONES Y ALERTAS</td>
    </tr>
    <tr>
      <td><strong>Toast / Snackbar</strong></td>
      <td>Fondo según estado: #70D399 (éxito), #FD4444 (error), #C79D08 (advertencia) <br> texto #F6F4F4 Roboto 15 px <br> border-radius 8 px <br> padding 12 px 20 px.</td>
      <td><strong>Posición:</strong> esquina inferior derecha. <br><strong>Duración:</strong> 3–5 s con opción de cierre manual. <br><strong>Ícono:</strong> 20 px a la izquierda del texto.</td>
    </tr>
    <tr>
      <td><strong>Banner de alerta inline</strong></td>
      <td>Fondo #FFF7E1 <br> borde izquierdo 4 px #C79D08 <br> texto Roboto 14 px #473723 <br> border-radius 4 px <br> padding 12 px 16 px.</td>
      <td>Usado en alertas de lote próximo a vencer. Ícono de advertencia 20 px #C79D08 a la izquierda.</td>
    </tr>
  </tbody>
</table>

---

**Diseño responsivo**

Entreprenly adopta un enfoque de diseño responsivo que asegura una experiencia óptima en escritorio, tableta y dispositivos móviles. El sistema de grilla y los breakpoints definidos a continuación permiten que el contenido de gestión —catálogos de productos, tablas de lotes, formularios de ventas y módulos de microlearning— se adapte de forma fluida y sin pérdida de funcionalidad a cualquier ancho de pantalla.

**Principio general:** La plataforma es completamente responsiva. Toda funcionalidad disponible en escritorio debe ser accesible y operable en tableta y móvil. Los objetivos táctiles mínimos son de 48 × 48 px, y la separación entre controles interactivos no será inferior a 16 px en ningún breakpoint.



<table>
  <thead>
    <tr>
      <th><strong>Dispositivo</strong></th>
      <th><strong>Ancho</strong></th>
      <th><strong>Columnas</strong></th>
      <th><strong>Gutter</strong></th>
      <th><strong>Especificaciones</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Mobile</strong></td>
      <td>≤ 640 px</td>
      <td>4</td>
      <td>16 px</td>
      <td>Header compacto con menú hamburguesa. Sidebar colapsado. CTA de acción fijo en parte inferior. Tablas de datos con scroll horizontal.</td>
    </tr>
    <tr>
      <td><strong>Tablet</strong></td>
      <td>641–1024 px</td>
      <td>8</td>
      <td>20 px</td>
      <td>Sidebar colapsable en overlay. Grilla de productos en 2–3 columnas. Filtros en panel desplegable lateral.</td>
    </tr>
    <tr>
      <td><strong>Desktop</strong></td>
      <td>≥ 1025 px</td>
      <td>12</td>
      <td>24 px</td>
      <td>Max-width de contenedor: 1280 px, centrado. Sidebar visible y fijo. Grilla de productos en 3–4 columnas. Dashboard KPI en fila de 4 tarjetas.</td>
    </tr>
  </tbody>
</table>



<table>
  <thead>
    <tr>
      <th><strong>Requisito</strong></th>
      <th><strong>Valor recomendado / Especificación</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Objetivos táctiles mínimos</strong></td>
      <td>48 × 48 px en todos los breakpoints inferiores a 1025 px.</td>
    </tr>
    <tr>
      <td><strong>Separación entre controles</strong></td>
      <td>Mínimo 16 px entre botones, campos y elementos interactivos adyacentes.</td>
    </tr>
    <tr>
      <td><strong>Indicador de focus visible</strong></td>
      <td>Outline de 2–3 px en #F38313 para elementos nativos; en #7679DE para campos de formulario.</td>
    </tr>
  </tbody>
</table>

Los estándares aquí establecidos constituyen la referencia normativa para la implementación del Landing Page y la Web Application de Entreprenly. Cualquier componente nuevo que se incorpore al sistema deberá respetar las especificaciones de color, tipografía, espaciado e interacción definidas en esta sección, asegurando la coherencia visual y funcional de la plataforma en cada entrega del ciclo de vida del proyecto.

## 4.2. Information Architecture

### 4.2.1. Organization Systems

*Contenido por agregar.*

### 4.2.2. Labeling Systems

*Contenido por agregar.*

### 4.2.3. SEO Tags and Meta Tags

*Contenido por agregar.*

### 4.2.4. Searching Systems

*Contenido por agregar.*

### 4.2.5. Navigation Systems

*Contenido por agregar.*

## 4.3. Landing Page UI Design

La Landing Page de Entreprenly está diseñada como el primer punto de contacto para comerciantes interesados en digitalizar su operación diaria. Su estructura prioriza una comunicación clara del problema, la propuesta de valor, los beneficios operativos y la conversión hacia el registro o la consulta de planes. El diseño mantiene una navegación lineal, secciones de lectura rápida y llamados a la acción visibles para reducir fricción en usuarios no técnicos.

### 4.3.1. Landing Page Wireframe

Los wireframes de la Landing Page representan la distribución base de cada sección antes de aplicar el acabado visual final. Estos esquemas permiten validar la jerarquía de información, el orden del contenido, la ubicación de los llamados a la acción y la consistencia del recorrido desde la presentación del producto hasta el siguiente paso comercial.

- **Header (Navbar)**

  <p align="center">
    <img src="images/wireframe-header-navbar.png" alt="Wireframe Header Navbar" width="800"/>
  </p>

- **Hero section**

  <p align="center">
    <img src="images/wireframe-hero-section.png" alt="Wireframe Hero Section" width="800"/>
  </p>

- **Problem section**

  <p align="center">
    <img src="images/wireframe-problem-section.png" alt="Wireframe Problem Section" width="800"/>
  </p>

- **Main features section**

  <p align="center">
    <img src="images/wireframe-main-features-section.png" alt="Wireframe Main Features Section" width="800"/>
  </p>

- **How it works section**

  <p align="center">
    <img src="images/wireframe-how-works-section.png" alt="Wireframe How It Works Section" width="800"/>
  </p>

- **Merchant benefits section**

  <p align="center">
    <img src="images/wireframe-merchant-benefits-section.png" alt="Wireframe Merchant Benefits Section" width="800"/>
  </p>

- **Client trust section**

  <p align="center">
    <img src="images/wireframe-client-trust-section.png" alt="Wireframe Client Trust Section" width="800"/>
  </p>

- **Comparativa breve section**

  <p align="center">
    <img src="images/wireframe-comparativa-breve-section.png" alt="Wireframe Comparativa Breve Section" width="800"/>
  </p>

- **Planes section**

  <p align="center">
    <img src="images/wireframe-planes-section.png" alt="Wireframe Planes Section" width="800"/>
  </p>

- **FAQ section**

  <p align="center">
    <img src="images/wireframe-faq-section.png" alt="Wireframe FAQ Section" width="800"/>
  </p>

- **Next step section**

  <p align="center">
    <img src="images/wireframe-next-step-section.png" alt="Wireframe Next Step Section" width="800"/>
  </p>

- **Footer section**

  <p align="center">
    <img src="images/wireframe-footer-section.png" alt="Wireframe Footer Section" width="800"/>
  </p>

### 4.3.2. Landing Page Mock-up

Los mockups de la Landing Page muestran la propuesta visual aplicada sobre la estructura validada en los wireframes. En esta versión se integran colores, tipografía, espaciado, jerarquía visual, componentes y estilo de marca para representar cómo se verá la página final antes de su implementación.

- **Header (Navbar)**

  <p align="center">
    <img src="images/mockup-header-navbar.png" alt="Mockup Header Navbar" width="800"/>
  </p>

- **Hero section**

  <p align="center">
    <img src="images/mockup-hero-section.png" alt="Mockup Hero Section" width="800"/>
  </p>

- **Problem section**

  <p align="center">
    <img src="images/mockup-problem-section.png" alt="Mockup Problem Section" width="800"/>
  </p>

- **Main features section**

  <p align="center">
    <img src="images/mockup-main-features-section.png" alt="Mockup Main Features Section" width="800"/>
  </p>

- **How it works section**

  <p align="center">
    <img src="images/mockup-how-works-section.png" alt="Mockup How It Works Section" width="800"/>
  </p>

- **Merchant benefits section**

  <p align="center">
    <img src="images/mockup-merchant-benefits-section.png" alt="Mockup Merchant Benefits Section" width="800"/>
  </p>

- **Client trust section**

  <p align="center">
    <img src="images/mockup-client-trust-section.png" alt="Mockup Client Trust Section" width="800"/>
  </p>

- **Comparativa breve section**

  <p align="center">
    <img src="images/mockup-comparativa-breve-section.png" alt="Mockup Comparativa Breve Section" width="800"/>
  </p>

- **Planes section**

  <p align="center">
    <img src="images/mockup-planes-section.png" alt="Mockup Planes Section" width="800"/>
  </p>

- **FAQ section**

  <p align="center">
    <img src="images/mockup-faq-section.png" alt="Mockup FAQ Section" width="800"/>
  </p>

- **Next step section**

  <p align="center">
    <img src="images/mockup-next-step-section.png" alt="Mockup Next Step Section" width="800"/>
  </p>

- **Footer section**

  <p align="center">
    <img src="images/mockup-footer-section.png" alt="Mockup Footer Section" width="800"/>
  </p>

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

*Contenido por agregar.*

### 4.4.2. Web Applications Wireflow Diagrams

*Contenido por agregar.*

### 4.4.3. Web Applications Mock-ups

*Contenido por agregar.*

### 4.4.4. Web Applications User Flow Diagrams

*Contenido por agregar.*

## 4.5. Web Applications Prototyping

*Contenido por agregar.*

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

*Contenido por agregar.*

### 4.6.2. Software Architecture Context Diagram

*Contenido por agregar.*

### 4.6.3. Software Architecture Container Diagrams

*Contenido por agregar.*

### 4.6.4. Software Architecture Components Diagrams

*Contenido por agregar.*

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

*Contenido por agregar.*

## 4.8. Database Design
El diseño de base de datos de Entreprenly está implementado en MySQL 8.0 y organizado en seis categorías. El esquema aplica normalización hasta la Tercera Forma Normal (3FN), eliminando redundancias y garantizando la integridad referencial en toda la operación del negocio.

El sistema distingue dos actores con responsabilidades distintas: los **Comerciantes**, quienes administran el negocio y tienen suscripción activa, y los **Clientes**, cuyos datos se registran únicamente para boletas y pedidos por WhatsApp, sin acceso al sistema.

Los productos se clasifican en tipo `unidad` (precio por unidad) y tipo `peso`o (precio por kilogramo), lo que determina cómo se interpreta el `stock_total` en cada caso.

La balanza IoT se integra mediante `LecturasBalanza`, que registra cada pesaje y se vincula a una venta al confirmar la transacción, descontando el stock automáticamente.

El arqueo de caja diario se gestiona en `ResumenDiario`, cuyo campo `total_general` es una columna calculada con `GENERATED ALWAYS AS` para evitar inconsistencias.

Los pagos digitales (Yape y Plin) operan bajo un modelo P2P con validación manual del comerciante desde el dashboard.

El chatbot de WhatsApp se integra mediante `ConexionesWhatsApp`, que persiste la sesión del número vinculado por QR, y `Conversaciones`, que registra cada mensaje del chat.

### 4.8.1. Database Diagrams

<div align="center">

![Database Diagram Entreprenly](images/Entreprendly_database_diagram.svg)
</div>

El esquema se organiza en las siguientes tablas por categoría:

**Identidad y Acceso:** 
- `Comerciantes` (datos de acceso y rol).
- `PreferenciasComercio` (idioma, tema y notificaciones).
- `SesionesActivas` (JWTs activos para revocación de sesiones).
- `TokensVerificacion` (tokens de un solo uso para verificar email y recuperar contraseña). 
- `Clientes` (datos para boletas).

**Suscripciones:** 
- `Suscripciones` (plan y ciclo de vida: pendiente → activa → cancelada → vencida).
- `BoletoSuscripcion` (datos del cobro, guarda solo los últimos 4 dígitos de la tarjeta por seguridad).

**Inventario:** 
- `Categorias` (tabla de referencia normalizada).
- `Productos` (catálogo con tipo unidad o peso, precio y stock). 
- `Lotes` (trazabilidad por fecha de vencimiento para productos perecederos).

**Ventas e IoT:** 
- `LecturasBalanza` (pesajes con snapshot histórico de precio).
- `Ventas` (encabezado de transacción presencial). 
- `DetalleVenta` (líneas de cada venta). 
- `ResumenDiario` (cierre de caja con total_general calculado automáticamente).

**Chatbot WhatsApp:** 
- `ConexionesWhatsApp` (sesión delnúmero vinculado por QR, relación 1:1 con el comerciante).
- `Conversaciones` (historial de mensajes entre bot, cliente y comerciante).

**Pedidos y Pagos:** 
- `Pedidos` (ciclo pendiente → esperando_pago → confirmado → completado). 
- `DetallePedido` (líneas del pedido).
- `Pagos` (validación manual del comprobante Yape/Plin, relación 1:1 con el pedido).

La normalización aplicada se resume en tres puntos. La **1FN** se cumple con valores atómicos en todas las columnas usando ENUM para campos de valores controlados. La **2FN** se cumple con claves primarias simples en todas las tablas. La **3FN** se evidencia en la separación de `PreferenciasComercio`, `BoletoSuscripcion` y `Categorias` para eliminar dependencias transitivas, la eliminación del campo `subtotal` en los detalles por ser valor derivado, y la separación de `Clientes` y `Comerciantes` por pertenecer a entidades de negocio distintas.



