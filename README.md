Bienvenidos, acontinuación podran encontrar información acerca de este proyecto.

**Datos de integrandes del grupo.**

| nombre | telefono | correo |  Rol |
| --------------- | --------------------- | ---------------- | ---------------- |
| Eisenhawer Valencia D. | 3043571169 | eisenhawer.valencia@cun.edu.co | LIDER -  backend - Fronend |
| Dayron Ferney Lopez R. | 3013846294 | dayron.lopezr@cun.edu.co |  Backend |
| kevin Steven Ortiz. | 3132429983 | kevin.ortizc@cun.edu.co |  Fronend | 
| Joan Sebastian Bohorquez. | 3144517854 | joan.bohorquez@cun.edu.co |  Base de datos |

**Credenciales**

| Credencial para:| Usuario | Contraseña |
| --------------- | ---------- | --------|
| Git Hub | sigloxxicafeteria075@gmail.com | 123456789dke |
| CLOUD | sigloxxicafeteria075@gmail.com | |
| Gmail | sigloxxicafeteria075@gmail.com | 123456789DKE |

#
## 1 . problema 
El problema principal por el cual se va a implementar el software a desarrollar es el deficis que tiene la cafetería siglo XXI al momento de sistematizar todo el tema administrativo de la empresa, funciones como  gestión de inventario, recursos humanos, clientes, facturación y estudios de mercado.  Ya que la empresa no solo cuenta con una sucursal si no que tiene varias sucursales en diferentes puntos ofreciendo diferentes productos y teniendo diferente cantidad de empleados 

## 2 . solucion del problema
Ya que se encontro el problema principal vamos a dividir el problema principal en sub problemas 

Gestión de inventario

Ya que la cafetería siglo XXI  tiene varias sucursales lo que el grupo de desarrollo plante es lo siguiente implementar la gestión de inventario para cada sucursal por independiente que cada sucursal lleve su inventario dependiendo de la cantidad de pedidos y de ventas que se realice en cada una de las sucursales de esta manera cada sucursal se encarga de su inventario sin tener que depender de otra o perjudicando el inventario de otra sucursal

Por otra parte en la cuestión de como se va a almacenar los diferentes productos en el inventario lo que se plante es que para poder almacenar en el inventario se requiere el nombre del producto, al ingresar dicho nombre de manera instantánea se le va a asignar un ID  que sera único para ese producto luego de eso se requiere la cantidad que se encuentra disponible para la venta de dicho producto y se va a colocar otra casilla para registrar la cantidad de pedidos que se hagan para abastecer  ese producto en especifico , en otra casilla el valor de venta y el valor de compra al proveedor del producto y para el tema de como se va a hacer para registrar las ventas y ir disminuyendo el numero de la cantidad disponible del producto ya entraríamos a otro sub problema el cual nos ayudaría con el anterior problema que seria facturación 


Facturacion 

En el tema de la facturación el equipo de desarrollo plantea tomar un ítem de la gestión de inventario para ser mas específicos los ID de los productos  ya que al momento de registrar una venta solo se necesitaría el ID de dicho producto y la cantidad a vender pero para este caso necesitamos la opinión del cliente para lo siguiente, si tomamos el ID de manera manual o lo temamos de la manera de código de barras, tengamos en cuenta que si lo hacemos de manera manual seria mas demorado el proceso de registrar la venta, ya que si contamos con una gran variedad de productos van haber productos que tiene un ID demasiado largo, Por otra parte si lo realizamos con código de barras haríamos que el proceso sea de manera mas rápida y efectiva 


También el equipo piensa  colocar un ID  único a cada factura, ¿Como lo haríamos? al momento de realizar el registro de los productos con su cantidad correspondiente a vender se enviaría  la orden de generar factura al hacer eso el software le asignaría de manera instantánea un ID a la factura para poder llevar un adecuado registro en cuestiones contables y financieras 


Estudio de mercado 

Para el problema de estudio de mercado el equipo de desarrollo plantea lo siguiente para poder generar un estudio de mercado de manera eficiente necesitaríamos el uso de una o varias APIs, ¿para qué esas APIs? Bueno el uso de esas APIs seria para tomar datos externos a  nuestro datos como precios de otras cafeterías, productos fuertes de esas cafeterías etc, también se propone implementar una serie de encuestas a nuestros clientes ya que con esas encuestas prodigamos saber cuál es nuestro producto fuerte, que les gustaría probar a nuestros cliente, si se sienten cómodos etc.
También se propone integrar de manera gráfica cual fue nuestro mes fuerte y comprar con otras cafeterías cercanas, mirar que tan bien distribuidas están nuestras sucursales con respecto a otras cafeterías y temas que nos ayuden a mejorar nuestra atención y nuestros números a nivel económicos y de clientes 

Cliente 

Para el problema de clientes la cafetería quiere llevar un registro de clientes, para dicho registro necesitamos el documento del cliente ese documento nos sirve como ID para ese cliente ya que cada documento es único para cada persona el registro de clientes se quiere implementar para poder tener en cuenta que clientes son los que más compran o cosas similares para poder tener un descuento especial, promociones etc. 

Recursos humanos 

Para el problema de recursos humanos el equipo de desarrollo plantea que se tenga un registro de los empleados de la empresa con ciertos niveles geraragico esto ya que no todos lo empleados van a cumplir la misma función ni van a tener los mismos permisos 
Para el registros de los empleados de manera eficiente se requiere el nombre del empleado necesitamos un ID y para eso utilizaríamos el documento de identificación, el cargo por el cual fue contratado,  ya entraríamos a dialogar con el cliente si también agregamos el sueldo del empleado, la sucursal en donde va a trabajar el empleados este registro si se aria de manera general y se le asignaría una sucursal al empleado después de ya estar contratado, este registro se le agrega una función para saber cual fue el empleado del mes o quien vendió más, para a si mismo por ejemplo poder darle una bonificación 


Por otra parte, después de asignarle una sucursal a dicho empleado también se le asignara los permisos requeridos para poder cumplir sus funciones de buena manera como ejemplo al cajero se la diría el permiso de la caja con las funciones de facturación y cliente 
 

## 3 . *Definicion  los roles y responsabilidades:*
### Es importante que cada miembro del equipo entienda qué se espera de ellos y cuáles son sus responsabilidades específicas en el proyecto.

| encargado | Rol | responsabilidades | tiempo de entrega |
| ------ | ---- | ---------------- | ---------------- | 
| Eisenhawer Díaz | Lider del proyecto | ayudar en el backend y frontend, estar atento de que las tareas asignadas se realicen en el tiempo correspondiente| |
| Dayron lopez  | Desarrollador Backend | Diseñar el backend del proyecto (models, controllers), realizar pruebas unitarias y su integracion | |
| kevin Ortiz | Desarrollador  frontend | Diseñar la interfaz del usuario, realizar el desarrollo en HTML5/CSS3/JavaScript, integrarlo | |
| sebastián bohorquez |  Desarrollador de la base de datos | diseñar  el esquema de la BD, realizar consultas, y dejar documentado | |


## 4. modelo ER

## 5 .*herramientas de gestión de proyectos posibles a usar:* 
### Se Considera utilizar clickup para asignar tareas, hacer seguimiento del progreso y facilitar la colaboración.


## **Caracteristicas* tecnicas.**

*-Requisitos de software:*
Los requisitos de este proyecto incluyen la gestión de diversos procesos empresariales, control de inventario, gestión de recursos humanos, gestión de clientes, facturación y análisis de estudios de mercado.

*-Arquitectura del software:*
La arquitectura deberá ser escalable y flexible para adaptarse a las necesidades cambiantes del cliente y del mercado. La aplicación web centralizada propuesta servirá como componente principal.

*-Lenguaje de programación:*
Se utilizará PHP con el framework de laravel 10 para el back y se esta pensando en utilizar React.

*-Base de datos:*
Se necesitará una base de datos para almacenar y gestionar la información de la empresa, incluyendo inventario, clientes, etc. Se utilizará Oracle.

*-Interfaces de usuario (UI) y Experiencia de Usuario (UX):*
la importancia de una interfaz de usuario intuitiva y atractiva para garantizar una experiencia óptima para los usuarios finales.

*-Escalabilidad y rendimiento:*
La arquitectura y la implementación en la nube con Google Cloud Platform (GCP) deben garantizar la escalabilidad y el rendimiento del sistema, especialmente a medida que la empresa crece.

*-Mantenibilidad:*
Se debe proporcionar documentación completa del software y del diseño en la nube para facilitar su mantenimiento futuro.

*-Pruebas y calidad del software:*
Se menciona la importancia de garantizar estándares de calidad tanto en la interfaz de usuario como en los procesos de automatización en la nube. Se deben realizar pruebas exhaustivas para asegurar el funcionamiento correcto del sistema.


## 6 . **Servicios que se van a usar en el CLOUD.**

| Tipo de servicio| Servicio |
| --------------- | -------- | 
| Administración | APIs y servicios |
| Administración | Facturación |
| Administración | IAM y administración |
| Procesamiento  | Compute engine |
| Procesamiento  | Kubernetes engine |
| Análisis       | Pub/Sub |
| Análisis       | Composer |
| Herramientas de redes  | Conectividad de red |
| Bases de datos | SQL |

Servicios cloud
Servicios de APIs de Google Cloud
APIs y servicios
los servicios de APIs y servicios de Google Cloud ofrecen una serie de herramientas y funcionalidades que permiten a los desarrolladores crear, implementar y gestionar aplicaciones en la nube de Google de manera eficiente.

Los servicios de APIs de Google Cloud proporcionan interfaces de programación de aplicaciones (APIs) que permiten a los desarrolladores interactuar con una amplia gama de servicios y recursos de Google Cloud Platform (GCP). Estas APIs permiten realizar tareas como almacenar y recuperar datos en Cloud Storage, ejecutar consultas en BigQuery, enviar y recibir correos electrónicos a través de Gmail, realizar análisis de texto con Natural Language API, entre muchas otras funcionalidades.

Nos sirven para: 
•	Facilitan la integración de servicios de Google Cloud en aplicaciones y sistemas existentes.
•	Permiten automatizar tareas y procesos utilizando la funcionalidad proporcionada por Google Cloud.
•	Posibilitan el desarrollo de aplicaciones personalizadas y soluciones empresariales utilizando los servicios de Google Cloud de manera programática.
Facturación

¿Qué es?
El servicio de facturación de Google Cloud es una herramienta que permite a los usuarios administrar y controlar los costos asociados con el uso de los servicios de Google Cloud Platform (GCP). Proporciona una interfaz para ver y entender el gasto en la nube, así como para establecer límites de presupuesto, generar informes detallados y administrar métodos de pago.
Funcionalidades claves
1.	Visualización de costos: Permite ver de manera detallada el consumo de recursos y los costos asociados con cada servicio de Google Cloud utilizado.
2.	Establecimiento de presupuestos: Permite establecer límites de presupuesto para evitar gastos inesperados y recibir alertas cuando se alcanzan ciertos umbrales de gasto.
3.	Generación de informes: Proporciona informes detallados sobre el uso y los costos, que pueden ser útiles para el seguimiento financiero, la planificación y la optimización de costos.
4.	Administración de métodos de pago: Permite agregar, editar y eliminar métodos de pago asociados con la cuenta de facturación, como tarjetas de crédito, cuentas bancarias, etc.
5.	Facturación consolidada: Para organizaciones con múltiples proyectos en Google Cloud, ofrece la posibilidad de consolidar la facturación en una sola cuenta centralizada, lo que facilita la gestión y el seguimiento del gasto.
¿Qué importancia tiene?
-	Control de costos: Permite a las organizaciones controlar y optimizar sus costos en la nube, lo que es crucial para mantener la eficiencia financiera y evitar sorpresas en la factura.
-	Transparencia y visibilidad: Proporciona una visión clara y detallada del gasto en la nube, lo que ayuda a los usuarios a comprender dónde se están utilizando los recursos y dónde se pueden realizar ajustes para optimizar el costo.
-	Gestión financiera: Facilita la planificación financiera al proporcionar informes y herramientas que ayudan a prever y administrar los costos relacionados con la nube.

IAM (Identity and Access Management) y administración

¿Qué es?
El servicio de IAM en Google Cloud es una herramienta que permite a los administradores definir quién tiene acceso a los recursos de Google Cloud y qué acciones pueden realizar. IAM se encarga de autenticar y autorizar a los usuarios y servicios para acceder a los recursos de GCP de manera segura y controlada.
Funcionalidades claves
1.	Gestión de identidades: Permite crear y administrar identidades de usuario, grupos y servicios, lo que facilita la asignación de roles y permisos.
2.	Definición de roles: Proporciona una amplia variedad de roles predefinidos que especifican conjuntos de permisos comunes, así como la capacidad de crear roles personalizados para necesidades específicas.
3.	Asignación de roles: Permite asignar roles a usuarios, grupos o servicios a nivel de proyecto, carpeta u organización para controlar el acceso a los recursos.
4.	Control de acceso granular: Ofrece la posibilidad de especificar permisos detallados a nivel de recurso, como lectura, escritura, eliminación, etc., para cada rol asignado.
5.	Herencia de permisos: Los permisos se heredan en la jerarquía de recursos de Google Cloud, lo que significa que los permisos asignados a un nivel superior (por ejemplo, proyecto) se aplican automáticamente a los niveles inferiores (por ejemplo, instancias de Compute Engine).
6.	Auditoría y registro de actividades: Proporciona registros detallados de las acciones realizadas por los usuarios y servicios, lo que permite realizar un seguimiento de los cambios y actividades en el entorno de Google Cloud.


Importancia.
Seguridad: IAM proporciona un mecanismo robusto para controlar el acceso a los recursos de Google Cloud, lo que ayuda a proteger los datos y aplicaciones contra accesos no autorizados y ataques.
Cumplimiento normativo: Permite a las organizaciones cumplir con requisitos de cumplimiento normativo al garantizar que solo las personas autorizadas tengan acceso a datos y recursos sensibles.
Gestión centralizada: Facilita la gestión centralizada de permisos y accesos en entornos complejos con múltiples proyectos, equipos y servicios.
Colaboración segura: Permite a los equipos colaborar de manera segura en proyectos compartidos al definir roles y permisos adecuados para cada usuario o grupo.
Compute engine
¿Qué es?
Compute Engine es un servicio de cómputo en la nube que ofrece Google Cloud. Permite a los usuarios crear y administrar máquinas virtuales en el entorno de la nube de Google. Estas máquinas virtuales pueden ejecutar una variedad de sistemas operativos, incluidas varias distribuciones de Linux y Windows Server.
Funcionalidades claves
1.	Creación y gestión de VMs: Permite lanzar y administrar máquinas virtuales en la nube de Google Cloud de manera rápida y sencilla.
2.	Escalabilidad: Ofrece la capacidad de escalar verticalmente (añadiendo más recursos a una VM existente) y horizontalmente (lanzando más VMs) según las necesidades de carga de trabajo.
3.	Variedad de tipos de máquinas: Proporciona una amplia variedad de tipos de máquinas virtuales con diferentes combinaciones de CPU, memoria y capacidad de almacenamiento para adaptarse a diferentes casos de uso y cargas de trabajo.
4.	Almacenamiento persistente: Ofrece opciones de almacenamiento persistente, como discos persistentes y discos locales de estado sólido (SSD), para almacenar datos de manera duradera y confiable.
5.	Redes avanzadas: Proporciona capacidades avanzadas de redes, incluyendo redes virtuales personalizadas, equilibradores de carga, y opciones de configuración de firewall para asegurar y optimizar la conectividad de las VMs.
6.	Integración con otros servicios de Google Cloud: Se integra estrechamente con otros servicios de Google Cloud Platform, como Cloud Storage, BigQuery y Kubernetes Engine, para facilitar el desarrollo y despliegue de aplicaciones en la nube.




Kubernetes Engine en Google Cloud
¿Qué es?
Kubernetes Engine es un servicio de Google Cloud que permite a los usuarios implementar y administrar clústeres de Kubernetes en la infraestructura global de Google. Kubernetes es una plataforma de código abierto desarrollada por Google que automatiza la implementación, escalado y operación de aplicaciones en contenedores.
Funcionalidades clave
1.	Implementación de clústeres de Kubernetes: Permite a los usuarios crear y administrar clústeres de Kubernetes de manera rápida y sencilla en la infraestructura de Google Cloud.
2.	Orquestación de contenedores: Ofrece capacidades avanzadas de orquestación de contenedores utilizando Kubernetes, lo que permite ejecutar aplicaciones en contenedores de manera eficiente y escalable.
3.	Escalado automático: Permite escalar automáticamente los recursos del clúster en función de la carga de trabajo, lo que garantiza un rendimiento óptimo y una alta disponibilidad de las aplicaciones.
4.	Actualizaciones sin tiempo de inactividad: Facilita las actualizaciones de las aplicaciones y del sistema operativo del clúster sin tiempo de inactividad, lo que garantiza una disponibilidad continua de las aplicaciones.
5.	Seguridad avanzada: Ofrece características de seguridad avanzadas, como la autenticación basada en IAM, la autorización basada en roles y la encriptación de datos en reposo y en tránsito, para garantizar la seguridad de las aplicaciones y los datos en el clúster.
Pub/Sub en Google Cloud
¿Qué es?
Pub/Sub es un servicio de mensajería en la nube que permite la comunicación asíncrona entre componentes de aplicaciones distribuidas. Permite a los productores de mensajes enviar mensajes a un tema (topic) y a los consumidores de mensajes suscribirse a esos temas para recibir y procesar los mensajes.
Funcionalidades clave
Tópicos y suscripciones: Los mensajes se publican en tópicos y los consumidores se suscriben a esos tópicos para recibir mensajes. Los tópicos actúan como canales de comunicación entre productores y consumidores.
Escalabilidad y fiabilidad: Pub/Sub es altamente escalable y puede manejar grandes volúmenes de mensajes con latencias bajas y alta disponibilidad. Además, garantiza la entrega de mensajes incluso en condiciones de alta carga o interrupciones de red.
Retención de mensajes: Los mensajes publicados en un tópico se retienen durante un período configurable, lo que permite a los consumidores recuperar mensajes antiguos o perdidos.
Modelo de entrega garantizada: Pub/Sub admite tanto la entrega al menos una vez como la entrega exactamente una vez de los mensajes, lo que garantiza que los mensajes sean procesados de manera confiable por los consumidores.
Casos de uso
Procesamiento de eventos en tiempo real: Captura de eventos en tiempo real, como registros de aplicaciones, clics de usuarios o datos de dispositivos IoT, y procesamiento de estos eventos de manera escalable y eficiente.
Integración de sistemas distribuidos: Facilita la integración entre sistemas distribuidos y aplicaciones en la nube, permitiendo la comunicación asíncrona y la sincronización de datos entre diferentes componentes.
Implementación de sistemas de mensajería: Desarrollo de sistemas de mensajería y colas de trabajo para la coordinación de procesos y la gestión de flujos de trabajo complejos.
Streaming de datos: Transferencia de datos en tiempo real entre aplicaciones y sistemas utilizando flujos de mensajes, lo que permite la construcción de aplicaciones de streaming de datos y análisis en tiempo real.

Composer
¿Qué es? 
Cloud Composer es un servicio de orquestación de flujos de trabajo basado en Apache Airflow, que permite a los usuarios programar, monitorear y gestionar flujos de trabajo complejos en la nube. Utiliza el concepto de DAGs (Directed Acyclic Graphs, o Grafos Dirigidos Acíclicos) para definir la secuencia de tareas y dependencias entre ellas.
Funcionalidades clave
Orquestación de flujos de trabajo: Permite definir flujos de trabajo complejos utilizando DAGs, donde cada tarea puede ser un script de Python, una tarea de Bash, una operación de GCP, entre otros.
Escalabilidad y alta disponibilidad: Cloud Composer es completamente gestionado por Google Cloud, lo que significa que escala automáticamente para manejar flujos de trabajo de cualquier tamaño y garantiza una alta disponibilidad de los servicios.
Monitoreo y registro: Ofrece herramientas de monitoreo y registro integradas que permiten visualizar el estado y el rendimiento de los flujos de trabajo, así como diagnosticar y solucionar problemas de manera eficiente.

Casos de uso
Procesamiento de datos ETL (Extract, Transform, Load): Orquestación de flujos de trabajo para la extracción, transformación y carga de datos entre diferentes sistemas y fuentes de datos.
Automatización de procesos empresariales: Programación de flujos de trabajo para la automatización de procesos empresariales, como la generación de informes, la gestión de inventario o la facturación.
Despliegue de aplicaciones y microservicios: Orquestación de flujos de trabajo para el despliegue y la gestión de aplicaciones y microservicios en la nube, facilitando la implementación y escalado de infraestructura.

servicio de Conectividad de red en Google Cloud
¿Qué es?
En Google Cloud, el servicio de conectividad de red engloba una variedad de herramientas y servicios diseñados para gestionar y optimizar la comunicación entre los recursos de la nube, tanto dentro como fuera del entorno de Google Cloud Platform (GCP).
¿Qué incluye?
Redes Virtuales (VPC): Las redes virtuales permiten crear y administrar redes privadas virtuales en la nube de Google Cloud, lo que permite a los usuarios aislar y segmentar sus recursos de manera segura.
Subredes: Dentro de una red virtual, las subredes permiten dividir el espacio de direcciones IP en segmentos más pequeños para organizar y controlar la conectividad entre los recursos de la red.
Firewall: El servicio de firewall de Google Cloud permite definir reglas de filtrado de red para controlar el tráfico de entrada y salida en las redes virtuales, lo que garantiza la seguridad de los recursos de la nube.
Interconexión y VPN: Google Cloud proporciona opciones de interconexión directa y VPN (Virtual Private Network) para establecer conexiones seguras y confiables entre la infraestructura de Google Cloud y las redes locales o de otros proveedores de servicios en la nube.

SQL
En Google Cloud, el servicio de SQL engloba varias soluciones de bases de datos gestionadas que permiten a los usuarios implementar, administrar y escalar bases de datos relacionales de manera fácil y eficiente en la nube.

![WhatsApp Image 2024-05-07 at 4 17 14 PM](https://github.com/cafeteriasigloXXI/cafeteriasigloXXI/assets/100285494/a6fbd17e-a724-43f4-b162-90a117852e56)


