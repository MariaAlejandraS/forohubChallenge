# forohubChallenge.
Aplicación de backend desarrollada a partir del tercer desafío de Oracle Next Education (ONE). Esta aplicación está enfocada en la creación de un foro, un espacio donde los usuarios de la plataforma pueden publicar sus preguntas relacionadas con diversos temas.
# Funcionalidades.
1. Crear un tópico nuevo [POST]
2. Listar todos los tópicos existentes [GET]
3. Ver un tópico específico [GET POR ID]
4. Modificar un tópico [PUT]
5. Eliminar un tópico [DELETE]
6. Implementación de autenticación y autorización para restringir el acceso a la información [JWT]
# Tecnologías empleadas.
1.  Java 21
2.  Spring Boot
3.  MySQL
4.  MySQL Workbench
5.  Spring Security
6.  JWT
# Modo de uso
1. Clonar este repositorio https://github.com/MariaAlejandraS/forohubChallenge
2. Crear la base de datos en MySQL:
   2.1 Usando MySQL Workbench, crear una base de datos de nombre foro o algo similar.
   2.2 Configurar el archivo application.properties del proyecto según tus credenciales de MySQL:
   spring.application.name=ForoHub
   spring.datasource.url
   spring.datasource.username
   spring.datasource.password
   hibernate.dialect=org.hibernate.dialect.HSQLDialect
   spring.jpa.hibernate.ddl-auto=update
   api.security.secret
3. Configurar las variables de entorno en tu computadora
   DB_HOST: 
   MYSQL_USER: 
   MYSQL_PASSWORD:
   JWT_SECRET: 
4. Ejecutar la aplicación. ./mvnw spring-boot:run
