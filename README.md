#spring-boot-demo

1、pom.xml
默认应用打成jar，可通过java -jar spring-boot-demo.jar运行
http://localhost:8080访问

2、pom-jetty.xml
mvn package -f pom-jetty.xml  打成jar中web容器为jetty

3、pom-war.xml
mvn package -f pom-war.xml  打成war包形式的spring-boot应用，可放入tomcat中运行
http://localhost:8080/spring-boot-demo访问
