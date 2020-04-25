# Docker-projects
Prerequisites for running angular app using docker-compose:
1)Node.js should be installed
2)Angular cli should be installed

docker-compose.yml should not be included inside the angular app directory (create it outside the angular app directory),
instead add the Dockerfile to it.

if there are any npm ERRORS, fix it by following the below steps:
  Run the command:
   -> ping registry.npmjs.org
      Output:- PING registry.npmjs.org <IP> ## bytes of data
   -> vim /etc/hosts
   -> <IP> registry.npmjs.org [ add this line to the file and save it ]
    
