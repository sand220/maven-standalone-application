<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>

	<groupId>com.mt</groupId>
	<artifactId>maven-stanalone-application</artifactId>
	<version>0.0.1-SNAPSHOT</version>
	<packaging>jar</packaging>

	<name>maven-stanalone-application</name>
	<url>http://mithuntechnologies.com</url>

	<organization>
		<name>Mithun Technologies</name>
		<url>http://mithuntechnologies.com/</url>
	</organization>
	
	<description>Maven Standalone Application</description>

	<properties>
		<maven.compiler.source>11</maven.compiler.source>
		<maven.compiler.target>11</maven.compiler.target>
		<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
		<sonar.host.url>http://13.233.59.26:9000/</sonar.host.url>
		<sonar.login>192b57b9731490e4c6c4a9c9d464f0a7cf099e4a</sonar.login>
	</properties>

	<dependencies>
		<dependency>
			<groupId>junit</groupId>
			<artifactId>junit</artifactId>
			<version>4.13.2</version>
			<scope>test</scope>
		</dependency>
	</dependencies>

	<distributionManagement>
	    <repository>
	      <id>nexus</id>
	      <name>Mithun Technologies Releases Nexus Repository</name>
	      <url>http://3.111.23.14:8081/repository/maven-releases/</url>
	    </repository>
	    
	    <snapshotRepository>
	      <id>nexus</id>
	      <name>Mithun Technologies Snapshot Nexus Repository</name>
	      <url>http://3.111.23.14:8081/repository/Walmart-snapshot/</url>
	    </snapshotRepository>
	</distributionManagement>
	
	<build>
	  <plugins>
	    <!-- Maven Compiler Plugin -->
	    <plugin>
	      <groupId>org.apache.maven.plugins</groupId>
	      <artifactId>maven-compiler-plugin</artifactId>
	      <version>3.8.1</version>
	      <configuration>
	        <source>${maven.compiler.source}</source>
	        <target>${maven.compiler.target}</target>
	      </configuration>
	    </plugin>

	    <!-- Maven JAR Plugin -->
	    <plugin>
	      <groupId>org.apache.maven.plugins</groupId>
	      <artifactId>maven-jar-plugin</artifactId>
	      <version>3.2.0</version>
	      <configuration>
	        <archive>
	          <manifest>
	            <addClasspath>true</addClasspath>
	            <classpathPrefix>lib/</classpathPrefix>
	            <mainClass>com.mt.sample.HelloWorld</mainClass>
	          </manifest>
	        </archive>
	      </configuration>
	    </plugin>
	  </plugins>
	</build>
</project>
