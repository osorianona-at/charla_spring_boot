. Segundo ejemplo con Spring Boot: Levanta un servicio REST que devuelve un saludo y envia un mail

. Configuración con YAML y properties, personaliza la consola de Spring Boot con banner.txt

. Rellenar las propiedades mail.username, mail.password del fichero mail.properties


. mvn spring-boot:run --> Ejecutar

. mvn clean package --> Junto con el plugin de Maven genera un jar autoejecutable

    <build>
        <plugins>
            <plugin>
                <groupId>org.springframework.boot</groupId>
                <artifactId>spring-boot-maven-plugin</artifactId>
            </plugin>
        </plugins>
    </build>

  . Ejecutar el jar java -jar target/ejemplo1-spring-boot-initial-0.0.1-SNAPSHOT.jar
  
  . Acceder http://localhost:8080/hello
