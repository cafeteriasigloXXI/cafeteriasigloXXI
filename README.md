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

| Tipo de servicio| Servicio | para que nos sirve |
| --------------- | -------- | ------------------- |
| Administración | APIs y servicios |
| Administración | Facturación |
| Administración | IAM y administración | (IAM) Control de acceso de nivel empresarial para que los adm autoricen quienes pueden realizar acciones sobre recursos especificos |
| Procesamiento  | Compute engine |
| Procesamiento  | Kubernetes engine |
| Análisis       | Pub/Sub |
| Análisis       | Composer |
| Herramientas de redes  | Conectividad de red |
| Bases de datos | SQL |

