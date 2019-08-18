# flyway

## Download jasypt
* https://sourceforge.net/projects/jasypt/
* ./encrypt.sh  input=<db_password> password=<secret>

## command line
mvn -Djasypt.encryptor.password=<secret> clean spring-boot:run
