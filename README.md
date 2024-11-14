# Maven Commands

In project root folder

1) mvnw.cmd clean
2) mvnw.cmd package (packages compiled bytecode classes into jar/war file)

Below command deletes, target folder, redownload dependencies, recompile class files, package to war/jar <br/>
mvnw.cmd clean package

run the application in the embedded localhost server
mvnw.cmd spring-boot:run