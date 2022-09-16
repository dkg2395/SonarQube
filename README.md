# SonarQube
https://github.com/dkg2395/MavenSonarJavaInEC2.git
https://github.com/ravdy/maven

SonarQube  is an open-source platform for  continuous inspection of code with static analysis of code to detect bugs, code smells, and security vulnerabilities on 20+ programming languages. 
SonarQube offers reports on duplicated code, coding standards, unit tests, code coverage, code complexity, comments, bugs, and security vulnerabilities.
Bugs,  Security Vulnerabilities, Security Review , Maintainability(code Smells) , coverage,Duplication, Size,


https://www.sonarqube.org/downloads/

Plugin :
<plugin>
				<groupId>org.sonarsource.scanner.maven</groupId>
				<artifactId>sonar-maven-plugin</artifactId>
				<version>3.4.0.905</version>
</plugin>
		
<plugin>
			<groupId>org.jacoco</groupId>
			<artifactId>jacoco-maven-plugin</artifactId>
				<version>0.8.1</version>
/plugin>


Maven command->Maven build - goal
clean org.jacoco:jacoco-maven-plugin:prepare-agent install

Maven run command->Maven build - goal

mvn sonar:sonar
if it say credential  related error:
goto Sonarqube
===========================================

<properties>
		<java.version>11</java.version>
		<sonar.host.url>http://localhost:9020</sonar.host.url>
		<sonar.login>admin</sonar.login>
		<sonar.password>admin123</sonar.password>
	</properties>
  
  mvn package
  
  mvn sonar:sonar
  
  
