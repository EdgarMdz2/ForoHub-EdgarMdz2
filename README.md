# ForoHub-EdgarMdz2

Challenge final de la formación Backend del programa Oracle Next Generation.

Desarrollo de una API RESTful para un foro médico.

Es necesario crear una base de datos llamada foro_med_TU_NOMBRE en MySQL, por ejemplo:
```
CREATE DATABASE foro_med_TU_NOMBRE;
```

Enseguida se deben configurar las credenciales de acceso a MySQL en application.properties:
```
spring.datasource.url=jdbc:mysql://localhost:3306/foro_medico
spring.datasource.username=root
spring.datasource.password=your_password
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

api.security.secret={$JWT_SECRET}
```
Ejecutar el script de migraciones de base de datos proporcionado para crear las tablas necesarias.
