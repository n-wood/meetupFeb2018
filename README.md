Step5: jenkins integration

			<plugin>
			    <groupId>org.owasp</groupId>
			    <artifactId>dependency-check-maven</artifactId>
			    <version>3.0.2</version>
			    <configuration>
					<suppressionFile>${basedir}/supression.xml</suppressionFile>
					<format>xml</format>
				</configuration>
			</plugin>

http://localhost:8080/
