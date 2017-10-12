

Step 1: mvn


Step 2: mvn -e exec:java -Dexec.mainClass="com.hydsoft.HelloExample"





Java Command:
# If the line below in 'maven-jar-plugin' section in pom file is comment out,
        <mainClass>com.hydsoft.HelloExample</mainClass>
  please use command:
        java -classpath "./*:./lib/*" com.hydsoft.HelloExample
# Else, use command:
        java -jar log4jexample-0.0.1-SNAPSHOT.jar
