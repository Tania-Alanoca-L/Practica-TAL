# PRACTICA N° #1
 ***1.Explique que son los sistemas empresariales***
 
**U**n sistema empresarial es un sistema central de la organización, que garantiza que la información se constituya el conjunto de recursos de la empresa que sirven como soporte para el proceso básico de captación, transformación, comunicación de la información y que se pueda transmitir atraves de todas las funciones empresariales, y todos los niveles de gestión, para soportar la operación y administración de una empresa. 

<span style="color:red">Texto *11111111* normal</span>

***2.Describa cuales son las características mas importantes de una aplicación empresarial***
 
**E** n esencia una aplicación empresarial es aquella destinada a resolver las necesidades internas de una empresa u organización, en vez de las de personas aisladas las cuales deben ser:  
Flexible y escalable.- **P**ara que una aplicación crezca según las necesidades de la empresa. Es decir, se trata de que el software sea capaz de adaptarse a las funciones y necesidades que vayan surgiendo en la organización.
Sencillo.- **P**ara no perder tiempo con programas informáticos complicados. Lo ideal es que las herramientas sean muy intuitivas y fáciles de usar. Es importante también contar con un buen soporte por si surge cualquier tipo de problema.
Ágil y multidispositivo.- **L**os usuarios deben poder acceder a los datos desde cualquier lugar de forma segura y fiable.


***3.Investigue y proponga cinco instituciones que requerirían aplicaciones de misión crítica.***

•	CLINICAS EN EL AREA DE EMERGENCIA 

•	ASOCIACIONES DE APOYO 

•	INSTITUCIONES DE GUARDERIAS 

•	ALDEAS INFANTILES SOS 

•	INSTITUCIONES JUDICIALES 

•	VICEMINISTERIO DE POLITICA TRIBUTARIA 

•	INSTITUCION DE LA AGENCIA DE TELECOMUNICACIONES Y TRANSPORTE

Estas instituciones requieren de esta aplicación ya que manejan información importante que deben darse a conocer para ser comprendidas y tener una fluidez al momento de seguimientos según cada caso.


***4.Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical***

**S**e entiende escalabilidad a la capacidad de adaptación y respuesta de un sistema con respecto al rendimiento del mismo a medida que aumentan de forma significativa el número de usuarios del mismo, aunque parezca un concepto claro, la escalabilidad de un sistema es un aspecto complejo e importante del diseño.

***Escalabilidad vertical.-***

**S**e refiere a actualizaciones o modernización de componentes existentes. Un sistema escala verticalmente o hacia arriba, cuando al añadir más recursos a un nodo particular del sistema, este mejora en conjunto. Por ejemplo, añadir memoria o un disco duro más rápido a una computadora puede mejorar el rendimiento del sistema global.


***Escalabilidad horizontal.-*** **A**punta en aumentar el número de componentes, un sistema escala horizontalmente si al agregar más nodos al mismo, el rendimiento de éste mejora. Por ejemplo, al añadir una computadora nueva a un sistema que balancee la carga entre la antigua y la nueva puede mejorar el rendimiento de todo el sistema.


**C**onsiste en potenciar el rendimiento del sistema desde un aspecto de mejora global, a diferencia de aumentar la potencia de una única parte del mismo. Este tipo de escalabilidad se basa en la modularidad de su funcionalidad. Por ello suele estar conformado por una agrupación de equipos que dan soporte a la funcionalidad completa. Normalmente, en una escalabilidad horizontal se añaden equipos para dar más potencia a la red de trabajo.



***5. Qué es un servidor web y que es un servidor de aplicación***


***SERVIDOR WEB***


**U**n servidor web o servidor HTTP es un programa informático que procesa una aplicación del lado del servidor, realizando conexiones bidireccionales o unidireccionales y síncronas o asíncronas con el cliente y generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente. El código recibido por el cliente es renderizado por un navegador web. Para la transmisión de todos estos datos suele utilizarse algún protocolo. Generalmente se usa el protocolo HTTP para estas comunicaciones, perteneciente a la capa de aplicación del modelo OSI. El término también se emplea para referirse al ordenador.


Los servidores Web a menudo forman parte de un paquete más amplio de programas relacionados con internet e intranet para servir correo electrónico, descargar solicitudes de archivos de protocolo de transferencia de archivos (FTP) y crear y publicar páginas Web.


***SERVIDOR DE APLICACIONES***


En informática, se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.
Usualmente se trata de un dispositivo de software que proporciona servicios de aplicación a las computadoras cliente. Un servidor de aplicaciones generalmente gestiona la mayor parte (o la totalidad) de las funciones de lógica de negociación y de acceso a los datos de las aplicaciones. Los principales beneficios de la aplicación de la tecnología de servidores de aplicación son la centralización y la disminución de la complejidad en el desarrollo de aplicaciones.



***6.Con un gráfico explique cómo funciona el protocolo HTTP***
![](pictures/001.png)

 


***7. Explique los elementos importantes de REQUEST en HTTP***


**U**n simple mensaje de request de un cliente tiene los siguientes componentes:

1.	Una línea de request para obtener el recurso, por ejemplo un request con el método GET /content/page1.html está requiriendo el recurso llamado /content/page1.html del servidor

2.	Encabezados. Indican cosas como el lenguaje, codificación, tipo de datos (XML,JSON, etc). (Por ejemplo– Accept-Language: EN).

3.	Una línea vacía.

4.	Un cuerpo del mensaje que es opcional. Entre aplicaciones esta es la parte mas importante. Por ejemplo, yo puedo enviar un XML o un JSON a otra máquina, y el servidor web interpretara la información que yo le mando.
HTTP Request Structure from Client, todas las líneas terminan con un retorno de carro y nueva línea. La línea vacía sólo contiene el retorno de carro y la nueva línea sin espacios.


***8. Explique los elementos importantes de RESPONSE en HTTP***

**U**n simple response del servidor web contiene lo siguiente:

1.	HTTP Status Code (Por ejemplo HTTP/1.1 301 Movido Permanentemente, significa que el recurso requerido fue movido permanentemente y redirigido a otro recurso).

2.	Un cuerpo de mensaje, que es opcional. Cuando trabajamos con aplicaciones, aquí puede venir la respuesta en XML u otro formato. Cuando es una página del navegador, contiene el código HTML que forma nuestra página.

3.	Encabezados. Igual que en el request, describen el contenido del response (Example – Content-Type: html)

4.	Una línea vacía.

HTTP Response Structure from Web Server, no hay mayor ciencia en la comunicación bajo el protocolo HTTP. Pero es poderoso y flexible porque permite desde visualizar páginas web, hasta intercambiar datos entre aplicaciones.

***9. Describa con un gráfico la arquitectura Java EE***

 
***10.Explique cuáles son los contenedores, componentes y servicios de Java EE.***

***CONTENEDORES***

***Java EE Server:*** La porción de tiempo de ejecución de un producto Java EE. Provee los contenedores web y de ejb.


***Contenedor EJB:*** Maneja la ejecución de los enterprise beans.


***Contenedor Web:*** Maneja la ejecución de las páginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.


***Contenedor de aplicación cliente:*** Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.


**Contenedor Applet:*** Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java

***COMPONENTES***

**U**na aplicación Java EE esta creada de componentes. Un componente es una unidad autónoma de software funcional que se ensambla en una aplicación Java EE con sus clases y archivos relacionados y que se comunica con otros componentes.
SERVICIOS

**L**a especificación Servicios web para Java™ EE (Java Platform, Enterprise Edition) define el modelo de programación y la arquitectura de tiempo de ejecución para implementar servicios web basados en el lenguaje Java. Otro nombre para la especificación Servicios web para Java EE es la especificación JSR (Java Specification Requirements) 109. La especificación incluye estándares abiertos para desarrollar e implementar servicios web.

•	Nombre de puerto

•	Implementación del servicio de puerto

•	Interfaz de punto final de servicio de puerto

•	Definición WSDL de puerto

•	QName de puerto

•	Soporte MTOM/XOP para servicios web JAX-WS

•	Enlace de protocolo para servicios web JAX-WS

•	Correlación JAX-RPC

•	Manejadores (opcional)

•	Correlación de servlet (opcional)

***11. Investique los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse***

**MÉTODOS DE HTTPSERVLET***

public abstract class HttpServlet extends GenericServlet: Es la clase de la cual se debe extender para crear un servlet HTTP. De la clase que extiende obtiene los métodos ya definidos además de los cuales define:

1.	doGet(HttpServletRequest req, HttpServletResponse resp): Es el método llamado para procesar información que haya sido enviado con el método GET. Este método es llamado concurrentemente para cada cliente por lo que hay que estar atento por posibles variables compartidas que causen problemas.

2.	doPost(HttpServletRequest req, HttpServletResponse resp): Ídem al anterior pero para el método POST, en general se implementa sólo un método y el otro lo referencia

***MÉTODOS DE HTTPSERVLETREQUEST***


public abstract interface HttpServletRequest extends ServletRequest: Permite obtener del cliente la información que es dependiente del protocolo, en este caso HTTP. Entre sus métodos están:

1. getHeader(String name): Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.

2. getCookies(): Retorna un arreglo que contiene todas las cookies que el cliente envía al servlet.

3. getSession(): Retorna la sesión en la cual se encuentra el cliente.

***MÉTODOS DE HTTPSERVLETRESPONSE***

public abstract interface HttpServletResponse extends ServletResponse: Permite enviar al cliente respuestas específicas del protocolo HTTP.

1. addCookie(Cookie cookie): Para definir nuevas cookies en el cliente.

2. setHeader(String name, String value): Para definir un header HTTP a enviar al cliente.

3. sendRedirect(String location): Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada.


