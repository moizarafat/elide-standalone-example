release: java -jar target/dependency/liquibase.jar --changeLogFile=src/main/resources/db/changelog/changelog.xml --url=$JDBC_DATABASE_URL --classpath=target/dependency/postgres.jar update
web: java -Xmx224m -jar target/elide-heroku-example.jar
