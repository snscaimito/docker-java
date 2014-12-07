## Java with Ubuntu 14.04 LTS

This is docker images of Ubuntu 14.04 LTS with different versions of java

### Loading different versions of java

The different version is determined with the TAG 

The available version are 

* latest - currently OpenJDK Java version 7 JRE
* openjdk-7-jdk - OpenJDK Java version 7 JDK
* openjdk-7-jre - OpenJDK Java version 7 JRE
* openjdk-7-jre-headless - OpenJDK Java version 7 JRE headless

Example to run a container with OpenJDK version 7 JDK

	docker run -ti nimmis/java:openjdk-7-jdk


