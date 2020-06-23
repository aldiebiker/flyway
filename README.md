# flyway

## Download jasypt
* https://sourceforge.net/projects/jasypt/
* ./encrypt.sh  input=<db_password> password= <secret>

## command line
mvn -Djasypt.encryptor.password=<secret> clean spring-boot:run

## Demo use cases

-  Wrong file version in dev
        - Migration already done (clean disabled)
        - Migration already done (clean enabled)



