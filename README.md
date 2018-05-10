Spring MVC used for Polo Trial-------------------

Demonstrates the capabilities of the Spring MVC web framework for comparison with other technologies.

Controller
 is kept simple and supports:
* Mapping Requests

* Obtaining Request Data

* Generating Responses

* Message Converters

* Rendering Views

* Type Conversion

* File Upload

* Exception Handling


* Validation

* Forms



Get the code:

---
Clone the repository:

    
$ git clone git://{{copy address}}


Run the application:

---	

From the command line with Build Tool Maven:

    
$ cd spring-mvc-showcase
    
$ mvn tomcat7:run [-Dmaven.tomcat.port=<port no.>] (In case 8080 is busy] 

or



In an IDE such as SpringSource Tool Suite (STS) or IntelliJIDEA:


* Import spring-mvc-showcase as a Maven Project

* Drag-n-drop the project onto the "SpringSource tc Server Developer Edition" or use a Servlet 2.5 or > Server to run, such as Tomcat.



Access the deployed web application at: http://localhost:8080/spring-mvc-showcase/


Note:
This trial is an adapted version of a conference presentation.
