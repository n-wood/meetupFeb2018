Step2: Add OWASP DC:


			<plugin>
			    <groupId>org.owasp</groupId>
			    <artifactId>dependency-check-maven</artifactId>
			    <version>3.0.2</version>
			</plugin>

mvn dependency-check:check

firefox target/dependency-check-report.html 
