# RBAC_Backend
This is a backend project built using Spring Boot. It provides login and registration functionality with JWT authentication.  Users can register with a role (USER or ADMIN), and based on that role they can access different APIs.

# Technologies Used
Java 17
Spring Boot
Spring Security
JWT
Spring Data JPA
Lombok
Maven

# Add Dependencies
Make sure Lombok is added in pom.xml
Setup Lombok (Important)

If Lombok is not working:
Install Lombok plugin in IDE
Enable Annotation Processing

If still not working:
Download Lombok jar from official site

Run command:
java -jar lombok.jar

# Database Configuration
Update application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/rbac_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update

Select your IDE location
Restart IDE

# Run Project
mvn spring-boot
