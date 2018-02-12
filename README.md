Step2: fix jackson databind warning

		<dependency>
		    <groupId>com.fasterxml.jackson.core</groupId>
		    <artifactId>jackson-databind</artifactId>
		    <version>2.8.11.1</version>
		</dependency>


mvn dependency-check:check

firefox target/dependency-check-report.html 
