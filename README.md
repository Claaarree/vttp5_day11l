# Maven Commands

In project root folder

1) mvn clean
2) mvn package (packages compiled bytecode classes into jar/war file)

Below command deletes, target folder, redownload dependencies, recompile class files, package to war/jar <br/>
mvn clean package

run the application in the embedded localhost server<br/>
mvn spring-boot:run