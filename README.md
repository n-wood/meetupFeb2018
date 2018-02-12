Step2: suppress tomcat warning

<configuration>
	<suppressionFile>${basedir}/supression.xml</suppressionFile>
</configuration>


mvn dependency-check:check

firefox target/dependency-check-report.html 
