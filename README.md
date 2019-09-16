**Project Manager Application - IIHT Certification Use Case**

_Prerequisite_
1. MySQL Server should be up and running in port 3636 and should have database named projectmanager
2. Should have JRE installed

_Running the Application_

1. Use command `java -jar project-manager-app.jar`
2. Application will be running in 8000 port
3. Access the application by hitting `http://localhost:8000` 

_Other Details_

1. `mvn clean install sonar:sonar` - Can be used to analyse the code and find Junit Coverage in sonar dashboard
2. Sonar will be running in `http://localhost:9000`
3. npm goal is added to maven hence UI will be packaged in to same application as that of service
