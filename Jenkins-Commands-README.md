1. java -jar jenkins-cli.jar -s 
http://localhost:8080/ help – Show CLI help

2. java -jar jenkins-cli.jar -s 
http://localhost:8080/ list-jobs – List all
jobs

3. java -jar jenkins-cli.jar -s 
http://localhost:8080/ build job_name – Trigger
a job

4. java -jar jenkins-cli.jar -s 
http://localhost:8080/ console job_name – View
job console output

5. java -jar jenkins-cli.jar -s 
http://localhost:8080/ delete-job job_name – Delete
a job

6. java -jar jenkins-cli.jar -s 
http://localhost:8080/ disable-job job_name –
Disable a job

7. java -jar jenkins-cli.jar -s 
http://localhost:8080/ enable-job job_name – Enable
a job

8. java -jar jenkins-cli.jar -s
http://localhost:8080/ safe-restart – Restart Jenkins
safely

9. java -jar jenkins-cli.jar -s 
http://localhost:8080/ set-build-description 
job_name 1 "Updated Description" – Update
build description

10. java -jar jenkins-cli.jar -s 
http://localhost:8080/ version – Show Jenkins
version

11. java -jar jenkins-cli.jar -s 
http://localhost:8080/ who-am-i – Check
authenticated user

12. java -jar jenkins-cli.jar -s 
http://localhost:8080/ get-job job_name – Get
job config

13. java -jar jenkins-cli.jar -s 
http://localhost:8080/ set-job job_name <
config.xml – Set job config

14. java -jar jenkins-cli.jar -s 
http://localhost:8080/ shutdown – Shutdown
Jenkins

15. java -jar jenkins-cli.jar -s
http://localhost:8080/ reload-configuration – 
Reload Jenkins configuration

16. java -jar jenkins-cli.jar -s 
http://localhost:8080/ install-plugin plugin-name
– Install a plugin

17. java -jar jenkins-cli.jar -s 
http://localhost:8080/ list-plugins – List
installed plugins

18. java -jar jenkins-cli.jar -s 
http://localhost:8080/ delete-plugin plugin-name
– Delete a plugin

19. java -jar jenkins-cli.jar -s 
http://localhost:8080/ update-job job_name <
config.xml – Update job configuration

20. java -jar jenkins-cli.jar -s 
http://localhost:8080/ build job_name -p 
PARAM=value – Trigger job with parameters

21. java -jar jenkins-cli.jar -s 
http://localhost:8080/ safe-exit – Gracefully
stop Jenkins

22. java -jar jenkins-cli.jar -s 
http://localhost:8080/ disconnect-node node_name
– Disconnect a node

23. java -jar jenkins-cli.jar -s 
http://localhost:8080/ install-plugin plugin.hpi
– Install plugin from file

24. java -jar jenkins-cli.jar -s 
http://localhost:8080/ get-view view_name –
Get view configuration

25. java -jar jenkins-cli.jar -s 
http://localhost:8080/ create-view view_name <
config.xml – Create a new view

