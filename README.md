# EmpleadosApp

## _Aplicación para la gestión de empleados_
#
### Descripción del Proyecto
Esta aplicación, desarrollada en Spring Boot utilizando Spring Data JPA, JSP, MySQL y Bootstrap, está diseñada para la gestión de empleados.
Aquí están los aspectos más destacados:


### Funcionalidades Principales:
**CRUD para Empleados**
- **Registro** de empleados con los campos de nombre, departamento, y sueldo.
- **Modificación** y **Eliminación** de empleados.
- **Panel** gráfico, desarrollado con Bootstrap, con el listado de los empleados y opciones para administrarlos.


### Tech
Esta aplicación se ha creado usando las siguientes tecnologias:
- [Java] - Lenguaje de programación principal.
- [Spring Boot] - Framework que simplifica el desarrollo de aplicaciones Java.
- [Spring Data JPA] - Facilita el acceso a bases de datos relacionales mediante el uso de JPA.
- [Hibernate] - Framework de mapeo objeto-relacional integrado con JPA.
- [Maven]- Herramienta de gestión de proyectos para la construcción y gestión de dependencias en el desarrollo de software Java.
- [MySQL] - El sistema de gestión de bases de datos relacional utilizado para almacenar y recuperar datos.
- [JSP] - JavaServer Pages, tecnología utilizada para desarrollar vistas en aplicaciones web Java.
- [Bootstrap] - Framework front-end que simplifica el desarrollo de interfaces de usuario web modernas y receptivas.

### Instrucciones de uso
**Configuración del proyecto:**
- Asegúrese de tener instalado Java y un IDE compatible con Maven como [IntelliJ] o [NetBeans].
- Clone este proyecto en su repositorio local: 
```sh
git clone https://github.com/seruax/EmpleadosApp.git
```
- Importe el proyecto en su IDE compatible con Maven.

**Configuración de la base de datos**:
- Configure las propiedades de conexión a su base de datos en 'application.properties'.
- La creación automática de la base de datos y las tablas está habilitada por defecto para facilitar la configuración. Éstas se crearán la primera vez quen ejecute la aplicación.

**Ejecución del Proyecto**:
- Ejecute la aplicación desde su IDE o mediante Maven:
```sh
mvn spring-boot:run
```

**Exploración de la APP**:
- Acceda la aplicación:
```sh
http://localhost:8080/empleados
```
- Registre un nuevo empleado con los datos necesarios.
- Si necesita editar, o eliminar el empleado, seleccione la opción correspondiente.



   [Java]: <https://www.oracle.com/es/java/technologies/downloads/>
   [Spring Boot]: <https://spring.io/projects/spring-boot>
   [Spring Data JPA]: <https://spring.io/projects/spring-data-jpa>
   [Hibernate]: <https://hibernate.org>
   [MySQL]: <https://www.mysql.com>
   [Maven]: <https://maven.apache.org>
   [IntelliJ]: <https://www.jetbrains.com/es-es/idea/>
   [NetBeans]: <https://netbeans.apache.org/front/main/>
   [JSP]: <https://www.oracle.com/java/technologies/jspt.html>
   [Bootstrap]: <https://getbootstrap.com>


