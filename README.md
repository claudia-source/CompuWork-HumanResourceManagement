# CompuWork HRM

## Descripción
CompuWork es un sistema de gestión de recursos humanos que permite a las empresas gestionar eficientemente la información de sus empleados, departamentos y proyectos. 

## Características
- Gestión de empleados
- Generación de reportes de desempeño
- Asignación de tareas a proyectos
- Integración con PostgreSQL

## Tecnologías Utilizadas
- Java
- Spring Boot
- PostgreSQL
- Maven

## Requisitos Previos
- JDK 11 o superior
- PostgreSQL instalado
- Maven

## Instalación
1. Clona el repositorio:
   ```bash
   git clone https://github.com/claudia-source/CompuWorkHRM.git
Configura la base de datos en src/main/resources/application.properties:
properties
Copiar código
spring.datasource.url=jdbc:postgresql://localhost:5432/compuwork_db
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
Uso
Para ejecutar la aplicación, utiliza Maven:

bash
Copiar código
mvn spring-boot:run
Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un issue o envía un pull request.

Licencia
Este proyecto está licenciado bajo la Nombre de la Licencia.

markdown
Copiar código

### Revisión del Proyecto

Además del `README.md`, revisa los siguientes aspectos en tu proyecto:

- **Documentación del Código**: Asegúrate de que tu código esté bien comentado y que las clases y métodos tengan descripciones claras.
- **Pruebas Unitarias**: Si has implementado pruebas, asegúrate de que estén incluidas y que se puedan ejecutar fácilmente.
- **Archivos de Configuración**: Verifica que tu archivo `application.properties` y otros archivos de configuración estén correctamente configurados y explicados.







