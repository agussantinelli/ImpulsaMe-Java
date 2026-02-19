<h1>🚀 ImpulsaMe - Plataforma de Crowdfunding en Java</h1>

<div align="center">
    <a href="https://github.com/martin-ratti/ProyectoJava-Crowdfunding" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/💻%20Repo%20Principal-ImpulsaMe-0b7285?style=for-the-badge&logo=github&logoColor=white" alt="Repo ImpulsaMe"/>
    </a>
    <a href="https://drive.google.com/drive/folders/1-iHSWlcJdVT-4DLdjdrMbCkB9aubQ5DZ?usp=sharing" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/📄%20Documentación%20Completa-Google%20Drive-34a853?style=for-the-badge&logo=googledrive&logoColor=white" alt="Docs Drive"/>
    </a>
</div>

<p align="center">
    <a href="https://github.com/agussantinelli" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/👤%20Agustín%20Santinelli-agussantinelli-000000?style=for-the-badge&logo=github&logoColor=white" alt="Agus"/>
    </a>
    <a href="https://github.com/juaquin11" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/👤%20Joaquín%20Peralta-juaquin11-000000?style=for-the-badge&logo=github&logoColor=white" alt="Joaquin"/>
    </a>
    <a href="https://github.com/martin-ratti" target="_blank" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/👤%20Martín%20Ratti-martin--ratti-000000?style=for-the-badge&logo=github&logoColor=white" alt="Martin"/>
    </a>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Java-Servlets%20%7C%20JSP-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java Badge"/>
    <img src="https://img.shields.io/badge/Eclipse-IDE-2C2255?style=for-the-badge&logo=eclipse&logoColor=white" alt="Eclipse Badge"/>
    <img src="https://img.shields.io/badge/Web-Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black" alt="Tomcat Badge"/>
    <img src="https://img.shields.io/badge/DB-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL Badge"/>
    <img src="https://img.shields.io/badge/Build-Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven Badge"/>
    <img src="https://img.shields.io/badge/Payments-Stripe-626CD9?style=for-the-badge&logo=stripe&logoColor=white" alt="Stripe Badge"/>
</p>
<p align="center">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge"/>
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge"/>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript Badge"/>
</p>
<div align="center">
    <a href="https://opensource.org/licenses/MIT">
        <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License: MIT"/>
    </a>
</div>
<hr>

<h2>🎯 Objetivo y Alcance</h2>

<p>
    <strong>ImpulsaMe</strong> es una plataforma web de <strong>crowdfunding</strong> desarrollada en Java (Servlets + JSP)
    que permite crear, explorar y financiar proyectos mediante donaciones.
</p>

<p>
    El sistema implementa un flujo completo de moderación y roles, donde cada proyecto pasa por estados
    (<code>Pendiente → Activo → Cancelado/Borrado</code>) y sólo los proyectos aprobados son visibles
    para recibir donaciones.
</p>

<ul>
    <li><strong>Creadores de proyectos</strong>: publican proyectos que quedan en estado pendiente hasta ser moderados.</li>
    <li><strong>Usuarios registrados</strong>: donan a proyectos activos y pueden comentar sólo si han donado.</li>
    <li><strong>Administradores</strong>: aprueban/rechazan proyectos y moderan comentarios.</li>
    <li><strong>Visitantes anónimos</strong>: navegan proyectos activos sin necesidad de autenticarse.</li>
</ul>

<p>
    Toda la documentación extendida (diagramas, casos de uso, modelo de dominio, etc.) se encuentra en:
    <a href="https://drive.google.com/drive/folders/1-iHSWlcJdVT-4DLdjdrMbCkB9aubQ5DZ?usp=sharing" target="_blank">
        Google Drive – ImpulsaMe
    </a>.
</p>

<hr>

<h2>⚙️ Stack Tecnológico</h2>

 <table>
  <thead>
   <tr>
    <th>Componente</th>
    <th>Tecnología</th>
    <th>Versión / Detalles</th>
   </tr>
  </thead>
  <tbody>
   <tr>
    <td><strong>Backend Web</strong></td>
    <td>Jakarta EE (Servlets + JSP)</td>
    <td>v10 (Servlet 6.0, JSP 3.0)</td>
   </tr>
   <tr>
    <td><strong>Servidor de Aplicaciones</strong></td>
    <td>Apache Tomcat</td>
    <td>v10.1+ (Soporte Jakarta EE 10)</td>
   </tr>
   <tr>
    <td><strong>Base de datos</strong></td>
    <td>MySQL</td>
    <td>v8.0.33 (Connector/J)</td>
   </tr>
   <tr>
    <td><strong>Persistencia</strong></td>
    <td>JDBC + DAO Pattern</td>
    <td>Acceso nativo optimizado sin ORM pesado.</td>
   </tr>
   <tr>
    <td><strong>Seguridad</strong></td>
    <td>JBCrypt</td>
    <td>Hashing seguro de contraseñas.</td>
   </tr>
   <tr>
    <td><strong>Pagos</strong></td>
    <td>Stripe API</td>
    <td>v24.8.0 (Checkout Sessions)</td>
   </tr>
   <tr>
    <td><strong>Procesamiento JSON</strong></td>
    <td>Gson</td>
    <td>v2.10.1 (API REST y AJAX)</td>
   </tr>
   <tr>
    <td><strong>Build Tool</strong></td>
    <td>Maven</td>
    <td>Gestión de dependencias y ciclo de vida.</td>
   </tr>
  </tbody>
 </table>

<hr>

<h2>🏗️ Arquitectura de la Solución</h2>

 <p>ImpulsaMe sigue un patrón <strong>MVC (Modelo-Vista-Controlador)</strong> estricto implementado con tecnologías estándar de Java:</p>

 <ul>
     <li><strong>Controlador (Servlets & Filters):</strong>
         <ul>
             <li><code>AuthFilter</code>: Interceptor central de seguridad que valida sesiones y roles (RBAC) antes de llegar a los servlets.</li>
             <li><strong>Servlets de Negocio:</strong> Procesan lógica específica (ej. <code>CreateProjectServlet</code>, <code>DonationSuccessServlet</code>).</li>
             <li><strong>Manejo de Errores:</strong> Redirecciones controladas a páginas de advertencia (<code>warning.jsp</code>) o prohibido (<code>forbidden.jsp</code>).</li>
         </ul>
     </li>
     <li><strong>Modelo (DAOs & Entidades):</strong>
         <ul>
             <li><strong>Entidades (POJOs):</strong> Clases puras como <code>Usuario</code>, <code>Proyecto</code>, <code>Donacion</code>.</li>
             <li><strong>Data Access Objects (DAOs):</strong> Abstracción total de SQL. Cada entidad tiene su DAO (<code>UsuarioDAO</code>, <code>ProyectoDAO</code>) para operaciones CRUD.</li>
         </ul>
     </li>
     <li><strong>Vista (JSP + JSTL):</strong>
         <ul>
             <li>Páginas renderizadas en servidor (SSR).</li>
             <li>Uso extensivo de JSTL para lógica de presentación limpia (sin scriptlets Java).</li>
             <li>Componentes reutilizables en <code>/views/common/</code> (header, footer, cards).</li>
         </ul>
     </li>
 </ul>

<hr>

<h2>📂 Estructura del Proyecto</h2>

<pre><code>ProyectoJava-Crowdfunding/
├── src/
│   └── main/
│       ├── java/                    # Código Fuente Java
│       │   ├── modelo/              # Clases del Dominio (Entidades POJO)
│       │   ├── repositorio/         # Capa de Acceso a Datos (DAOs)
│       │   ├── servlet/             # Controladores (Servlets & Filtros)
│       │   ├── interfaces/          # Contratos de interfaz para DAOs
│       │   ├── db/                  # Gestor de conexiones JDBC
│       │   └── utils/               # Utilidades y configuración
│       └── webapp/                  # Recursos Web (Frontend)
│           ├── assets/              # Imágenes y estáticos
│           ├── views/               # Vistas JSP organizadas por módulo
│           │   ├── common/          # Páginas públicas (Home, Error, etc.)
│           │   ├── fragments/       # Partials (Header, Footer)
│           │   ├── auth/            # Login y Registro
│           │   ├── admin/           # Panel de Control
│           │   └── user/            # Gestión de proyectos de usuario
│           └── WEB-INF/             # Configuración privada
│               └── web.xml          # Descriptor de despliegue
├── .settings/                       # Configuraciones del entorno (Eclipse/VSCode)
├── target/                          # Builds y compilados (.class, .war)
├── pom.xml                          # Dependencias Maven
└── README.md                        # Documentación principal
</code></pre>

<hr>

<h2>🧩 Entidades de Dominio Clave</h2>

<ul>
    <li><strong>Usuario</strong>
        <ul>
            <li>Campo <code>telefono</code>:
                <ul>
                    <li><code>NULL</code> → usuario administrador.</li>
                    <li><code>NO NULL</code> → usuario regular.</li>
                </ul>
            </li>
        </ul>
    </li>
    <li><strong>Proyecto</strong>
        <ul>
            <li>Estados: <code>Pendiente</code>, <code>Activo</code>, <code>Cancelado</code>, <code>Borrado</code>.</li>
            <li>Campo <code>foto</code>: nombre de archivo UUID, con imágenes en <code>uploads/</code>.</li>
            <li>Relación con el creador (<code>idCreador</code>) para identificar al dueño del proyecto.</li>
        </ul>
    </li>
    <li><strong>Donación</strong>
        <ul>
            <li>Relaciona usuario ↔ proyecto + monto donado.</li>
            <li>Integra con Stripe mediante <code>paymentAttemptId</code> (UUID) para evitar duplicados.</li>
        </ul>
    </li>
    <li><strong>Comentario</strong>
        <ul>
            <li>Campo <code>estado</code> con valores como <code>Activo</code> / <code>Ignorado</code>.</li>
            <li>Soft delete: comentarios ignorados no se muestran, pero quedan en BD.</li>
        </ul>
    </li>
    <li><strong>Cancelación de Proyecto</strong>
        <ul>
            <li>Tabla opcional (<code>cancelacion_proyecto</code>) con información cuando un proyecto es cancelado por su dueño.</li>
        </ul>
    </li>
    <li><strong>Avance de Proyecto</strong>
        <ul>
            <li>Representa actualizaciones o hitos del proyecto publicados por el creador.</li>
            <li>Incluye descripción, fecha y una foto opcional para mostrar progreso a los donantes.</li>
        </ul>
    </li>
    <li><strong>Categoría</strong>
        <ul>
            <li>Permite clasificar los proyectos en áreas temáticas (ej. Tecnología, Arte, Solidaridad).</li>
            <li>Facilita el filtrado y búsqueda de proyectos activos.</li>
        </ul>
    </li>
    <li><strong>País</strong>
        <ul>
            <li>Referencia geográfica para la ubicación del proyecto o del usuario.</li>
        </ul>
    </li>
    <li><strong>Contacto</strong>
        <ul>
            <li>Almacena los mensajes enviados por visitantes o usuarios a través del formulario de contacto.</li>
            <li>Contiene nombre, email, asunto y mensaje.</li>
        </ul>
    </li>
</ul>

<hr>

<h2>👤 Roles y Reglas de Negocio</h2>

 <h3>Control de Acceso (RBAC)</h3>
 <p>El sistema identifica 3 niveles de acceso gestionados por el <code>AuthFilter</code>:</p>
 
 <table>
     <thead>
       <tr>
         <th>Rol</th>
         <th>Condición</th>
         <th>Capacidades Principales</th>
       </tr>
     </thead>
     <tbody>
       <tr>
         <td><strong>Visitante</strong></td>
         <td>Sesión no iniciada</td>
         <td>Ver proyectos activos, buscar por categorías, contactar soporte, registrarse/login.</td>
       </tr>
       <tr>
         <td><strong>Usuario (Inversor/Creador)</strong></td>
         <td><code>telefono != null</code></td>
         <td>Crear proyectos, donar, comentar, publicar avances, ver historial de donaciones.</td>
       </tr>
       <tr>
         <td><strong>Administrador</strong></td>
         <td><code>telefono == null</code></td>
         <td>Moderar proyectos (aprobar/rechazar), ver mensajes de contacto, moderar comentarios.</td>
       </tr>
     </tbody>
 </table>
 
 <h3>Reglas de Negocio Críticas</h3>
 <ul>
     <li><strong>Validación de Donaciones:</strong>
         <ul>
             <li>Monto mínimo: <strong>$1,000 ARS</strong>.</li>
             <li>Monto máximo: <strong>$999,999.99 ARS</strong>.</li>
             <li><strong>Restricción de Auto-donación:</strong> Un creador NO puede donar a su propio proyecto.</li>
         </ul>
     </li>
     <li><strong>Moderación de Proyectos:</strong>
         <ul>
              <li>Todo proyecto nace en estado <code>Pendiente</code>.</li>
              <li>Solo un <strong>Administrador</strong> puede transcionarlo a <code>Activo</code> (visible) o rechazarlo (eliminación lógica).</li>
         </ul>
     </li>
      <li><strong>Comentarios:</strong>
         <ul>
              <li>Solo usuarios que <strong>han donado</strong> previamente a un proyecto pueden comentar en él.</li>
              <li>Los comentarios pueden ser deshabilitados (soft delete) por administradores.</li>
         </ul>
     </li>
 </ul>

<hr>

<h2>📈 Flujo de Proyectos y Donaciones</h2>

 <h3>Ciclo de Vida del Proyecto</h3>
 <ol>
     <li><strong>Alta:</strong> Usuario completa formulario en <code>/createProject</code>. Se valida imagen y datos. Estado inicial: <strong>PENDIENTE</strong>.</li>
     <li><strong>Revisión:</strong> El proyecto aparece en el panel admin (<code>/pendingProjects</code>).</li>
     <li><strong>Decisión:</strong>
         <ul>
             <li><strong>Aprobar:</strong> <code>ApproveProjectServlet</code> cambia estado a <strong>ACTIVO</strong>. Se vuelve público.</li>
             <li><strong>Rechazar:</strong> <code>RejectProjectServlet</code> elimina lógicamente el proyecto.</li>
         </ul>
     </li>
     <li><strong>Evolución:</strong> El creador sube actualizaciones mediante <code>/addAdvance</code> (aparecen en la pestaña "Avances").</li>
 </ol>
 
 <h3>Flujo de Donación (Stripe Checkout)</h3>
 <ol>
     <li><strong>Inicio:</strong> Usuario elige monto en <code>donation.jsp</code>.</li>
     <li><strong>Sesión de Pago:</strong> <code>CreateCheckoutSessionServlet</code> valida montos y contacta a la API de Stripe para crear una sesión.
         <ul>
             <li>Se genera un <code>paymentAttemptId</code> único para idempotencia.</li>
         </ul>
     </li>
     <li><strong>Redirección:</strong> Usuario es llevado a la página segura de Stripe.</li>
     <li><strong>Retorno Exitoso:</strong> Stripe redirige a <code>/donation-success</code>.</li>
     <li><strong>Confirmación:</strong>
         <ul>
             <li>El servlet verifica la sesión y el monto.</li>
             <li>Se inserta el registro en la tabla <code>Donaciones</code>.</li>
             <li>Se actualiza el <code>montoRecaudado</code> del proyecto de forma atómica.</li>
             <li>Usuario ve pantalla de agradecimiento y su donación reflejada.</li>
         </ul>
     </li>
 </ol>

<hr>

<h2>🛠️ Archivos de Configuración Clave</h2>

<table>
    <thead>
      <tr>
        <th>Archivo</th>
        <th>Rol</th>
        <th>Propiedades destacadas</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>config.properties</code></td>
        <td>Configuración general de la app</td>
        <td>
          <ul>
            <li><code>upload.dir</code> – ruta física donde se guardan las imágenes de proyectos.</li>
            <li><code>stripe.secret.key</code> – clave secreta de Stripe.</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td><code>database.properties</code></td>
        <td>Conexión a MySQL</td>
        <td>
          Contiene el URL JDBC, usuario, contraseña y driver para la base MySQL.
        </td>
      </tr>
      <tr>
        <td><code>web.xml</code></td>
        <td>Descriptor de despliegue</td>
        <td>
          Define mapeos de servlets, filtros (incluyendo <code>AuthFilter</code>) y páginas de bienvenida.
        </td>
      </tr>
    </tbody>
</table>

<hr>

<h2>🧭 Puntos de Navegación</h2>

 <h3>Público</h3>
 <ul>
     <li><code>/home</code> : Landing page principal.</li>
     <li><code>/activeProjects</code> : Catálogo de proyectos financiables.</li>
     <li><code>/categories</code> : Exploración por categorías.</li>
     <li><code>/how-it-works</code> : Guía de uso.</li>
     <li><code>/contact</code> : Formulario de contacto para soporte.</li>
 </ul>
 
 <h3>Usuario Registrado</h3>
 <ul>
     <li><code>/createProject</code> : Formulario de alta de proyecto.</li>
     <li><code>/myProjects</code> : Dashboard de mis proyectos (creados).</li>
     <li><code>/supportedProjects</code> : Historial de proyectos apoyados.</li>
     <li><code>/addAdvance</code> : Publicar novedad en un proyecto propio.</li>
     <li><code>/editProject</code> : Modificar datos de un proyecto propio.</li>
 </ul>
 
 <h3>Administrador</h3>
 <ul>
     <li><code>/pendingProjects</code> : Bandeja de revisión de proyectos.</li>
     <li><code>/showMessages</code> : Bandeja de entrada de mensajes de contacto.</li>
     <li><code>/approveProject</code> / <code>/rejectProject</code> : Acciones de moderación.</li>
     <li><code>/disableComment</code> : Moderación de contenido social.</li>
 </ul>

<hr>

<h2>🚀 Puesta en Marcha (Setup Local)</h2>

<h3>1. Requisitos</h3>
<ul>
    <li><strong>JDK</strong> (por ejemplo Java 17+).</li>
    <li><strong>Maven</strong> instalado y en el <code>PATH</code>.</li>
    <li><strong>MySQL</strong> en ejecución (local o remoto).</li>
    <li><strong>Apache Tomcat</strong> (u otro contenedor de Servlets compatible).</li>
    <li>Cuenta de <strong>Stripe</strong> y clave de prueba (test key).</li>
</ul>

<h3>2. Configuración</h3>

<ol>
    <li>Clonar el repositorio:
        <pre><code>git clone https://github.com/martin-ratti/ProyectoJava-Crowdfunding.git
</code></pre>
    </li>
    <li>Crear la base de datos MySQL (por ejemplo <code>impulsame</code>) e importar el esquema/tablas según los scripts o documentación del proyecto.</li>
    <li>Configurar <code>database.properties</code> con el JDBC URL, usuario y contraseña de tu instancia MySQL.</li>
    <li>Configurar <code>config.properties</code> con:
        <ul>
            <li><code>upload.dir</code> apuntando a una carpeta válida para subir imágenes.</li>
            <li><code>stripe.secret.key</code> con tu clave de prueba o producción de Stripe.</li>
        </ul>
    </li>
    <li>Construir el proyecto:
        <pre><code>mvn clean package</code></pre>
    </li>
    <li>Desplegar el <code>.war</code> generado en tu instancia de Tomcat (o ejecutar desde tu IDE apuntando al servidor).</li>
    <li>Acceder a la app en el navegador (ejemplo):
        <pre><code>http://localhost:8080</code></pre>
    </li>
</ol>

<p>
    Para comandos específicos, scripts SQL y diagramas, ver la carpeta de documentación en Google Drive:
    <a href="https://drive.google.com/drive/folders/1-iHSWlcJdVT-4DLdjdrMbCkB9aubQ5DZ?usp=sharing" target="_blank">
        Documentación ImpulsaMe
    </a>.
</p>

<hr>

<h2>📚 Documentación Adicional</h2>

<p>La documentación completa del proyecto (en español) incluye:</p>

<ul>
    <li>Diagramas de arquitectura del sistema.</li>
    <li>Modelo de dominio y diagrama entidad-relación.</li>
    <li>Flujos de navegación y diagramas de secuencia.</li>
    <li>Detalles del modelo de seguridad y control de acceso.</li>
    <li>Descripción detallada de endpoints, casos de uso y decisiones de diseño.</li>
</ul>

<p>
    Todo esto está disponible en:
    <a href="https://drive.google.com/drive/folders/1-iHSWlcJdVT-4DLdjdrMbCkB9aubQ5DZ?usp=sharing" target="_blank">
        Google Drive – ImpulsaMe
    </a>.
</p>

<hr>

<h2>👥 Equipo</h2>

<ul>
    <li><strong>Agustín Santinelli</strong> – <a href="https://github.com/agussantinelli" target="_blank">@agussantinelli</a></li>
    <li><strong>Joaquín Peralta</strong> – <a href="https://github.com/juaquin11" target="_blank">@juaquin11</a></li>
    <li><strong>Martín Ratti</strong> – <a href="https://github.com/martin-ratti" target="_blank">@martin-ratti</a></li>
</ul>

<p>Proyecto académico desarrollado en equipo para la UTN FRRO (Catedra Lenguaje de Programación Java).</p>

<hr />

<h2 align="left">⚖️ Licencia</h2>

<p align="left">
  Este proyecto está bajo la <b>Licencia GNU General Public License v3.0 (GPLv3)</b>. Puedes consultar los términos legales completos en el archivo 
  <a href="LICENSE"><code>LICENSE</code></a> incluido en la raíz de este repositorio.
</p>

<p align="left">
  <i>
    🤝 <b>Compromiso Copyleft:</b> La GPLv3 permite el uso, estudio, modificación y distribución de este software. Sin embargo, cualquier obra derivada o modificación distribuida debe ser publicada bajo esta misma licencia, garantizando que el software permanezca libre y accesible para todos.
  </i>
</p>

<hr>

<p><em>ImpulsaMe – Plataforma de crowdfunding en Java con moderación, pagos y control de acceso por roles.</em></p>
