Step1: Run dependency report on spring boot project

mvn project-info-reports:dependencies -DoutputDirectory=. -Ddependency.locations.enabled=false

firefox target/site/dependencies.html 
