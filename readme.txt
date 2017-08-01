mvn clean install
mvn archetype:generate
-DinteractiveMode=false
-DarchetypeGroupId=com.butchjgo
-DarchetypeArtifactId=spring-webmvc
-DgroupId=<groupId>
-Dversion=<version>
-DartifactId=<artifactId>

Ex:
mvn archetype:generate 
-DinteractiveMode=false 
-DarchetypeGroupId=com.butchjgo 
-DarchetypeArtifactId=spring-webmvc -jpa
-DgroupId=com.butchjgo 
-Dversion=1.0 
-DartifactId=spring-web-quick-start

mvn archetype:generate -DinteractiveMode=false -DarchetypeGroupId=com.butchjgo -DarchetypeArtifactId=spring-webmvc-jpa -DgroupId=com.butchjgo -Dversion=1.0 -DartifactId=spring-web-jpa-quick-start