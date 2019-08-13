# PRÁCTICA n° 1
# SISTEMAS EMPRESARIALES

| Carrera: | INGENIERIA DE SISTEMAS |   
| --- | :--- | 
| Materia: | TECNOLOGIAS EMERGENTES II | 
| Apellidos y nombres: | RODRIGO LECOÑA QUISPE |  
| C.I: | 10028685 L.P. | 
| Lugar y fecha: | EL ALTO 13 DE AGOSTO |   


### 1) 	Explique que son los sistemas empresariales ###
Es un sistema que tiene un impacto muy importante en el funcionamiento de la organización o negocio que ofrece una alta calidad de servicio, gestiona grandes volúmenes de datos, disponible de forma continua.
En el desarrollo de aplicaciones de misión crítica se consideran:
* Plataforma tecnológica 
* Alta disponibilidad
* Escalabilidad
*	Seguridad
*	Mantenimiento
### 2)	Describa cuales son las características más importantes de una aplicación empresarial ###
*	Acceso a la Base de Datos usualmente a bases de datos relacionales
*	Operaciones transaccionales, cumple las propiedades ACID
*	Escalables, permiten escalabilidad vertical y horizontal
*	Disponibles, idealmente prestan servicios de forma continua
*	Seguras, no todos los usuarios acceden con la misma funcionalidad
*	Permiten integración con otras tecnologías
*	Arquitectura multicapa
### 3)	Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta ###
#### Es importante tener en cuenta puntos esenciales al momento de desarrollar aplicación de misión crítica:
*	*Plataforma tecnológica*
*	*Flexibilidad*
*	*Escalabilidad*
*	*Seguridad*
*	*Pruebas (Testing)*
#### Las instituciones que requerirían misión  crítica son:
*	__Institución educativa (Colegios)__
*	__EDUCATIC BOLIVIA (TIC)__
*	__Universidades Privadas__
*	__La Fundación Redes para el Desarrollo Sostenible (REDES)__ 
*	__Fundación PROINPA__

La lista de instituciones listado anteriormente requerirían de misión critica por que necesitan seguridad, escalabilidad (por que día a día va ir creciendo la institución), una plataforma entendible y practica hacer el testeo de red que tiene cada institución.

### 4)	Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical ###
La escalabilidad horizontal se refiere a aumentar el número de componentes y la escalabilidad vertical  se refiere a las actualizaciones o modernización de componentes existentes
### 5)	Que es un servidor Web y que es un servidor de aplicaciones ###
Un servidor Web es una computadora que forma parte de una red que provee servicios.
El servidor de aplicaciones es un dispositivo de software gestiona la mayor parte de las funciones lógicas  y acceso a los datos de la aplicación. 

### 6)	Con un gráfico explique cómo funciona el protocolo HTTP ###
![IMAGEN](http://www.hermosaprogramacion.com/wp-content/uploads/2015/01/http-protocolo-peticion.png)
### 7)	Explique los elementos importantes de REQUEST en HTTP ###
Método HTTP (la acción a realizar)
La página puede acceder (a URL)
Parámetros de forma (como argumentos de un método)
Permite enviar todo tipo de petición HTTP a un URL específico y procesar la respuesta del servidor HTTP. 

### 8)	Explique los elementos importantes de RESPONSE en HTTP ###
Un código de estatus (para saber si la solicitud fue exitosa)
Tipo de contenido (texto, imagen, HTML, etc.)
El contenido (el HTML real, la imagen, etc.)

### 9)	Describa con un gráfico la arquitectura Java EE ###
![IMAGEN](https://image.slidesharecdn.com/jatunandjavaee-110905104600-phpapp02/95/desarrollo-de-aplicaciones-empresariales-con-java-ee-4-728.jpg?cb=1316098712)
### 10)	Explique cuáles son los contenedores, componentes y servicios de Java EE ###
Los contenedores son:
1. Un contenedor es un entorno de ejecución que provee al componente una serie de servicios
2.  Java EE define los siguientes tipos de contenedores:
-	Contenedor web
-	Contenedor de negocio (o de EJBs)

### 11)	Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo. ###
1. ***HttpServlet:*** 
Es la clase de la cual se debe extender para crear un servlet HTTP. De la clase que extiende obtiene los métodos ya definidos además de los cuales define:
*	_doGet(HttpServletRequest req, HttpServletResponse resp):_ Es el método llamado para procesar información que haya sido enviado con el método GET. Este método es llamado concurrentemente para cada cliente por lo que hay que estar atento por posibles variables compartidas que causen problemas.
*	_doPost(HttpServletRequest req, HttpServletResponse resp):_ Ídem al anterior pero para el método POST, en general se implementa sólo un método y el otro lo referencia.
2. ***HttpServletRequest:***
Permite obtener del cliente la información que es dependiente del protocolo, en este caso HTTP. Entre sus métodos están:
*	_getHeader(String name):_ Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.
*	_getCookies():_ Retorna un arreglo que contiene todas las cookies que el cliente envía al servlet.
*	_getSession():_ Retorna la sesión en la cual se encuentra el cliente.
3. ***HttpServletResponse:***
Permite enviar al cliente respuestas específicas del protocolo HTTP.
*	_addCookie(Cookie cookie):_ Para definir nuevas cookies en el cliente.
*	_setHeader(String name, String value):_ Para definir un header HTTP a enviar al cliente.
*	_sendRedirect(String location):_ Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada.

[TODOS LOS EJEMPLOS DE LAS CLASES: HttpServlet, HttpServletRequest y HttpServletResponse](https://emerodry2.blogspot.com)
