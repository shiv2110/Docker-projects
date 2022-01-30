# Docker-projects
### Prerequisites for running angular app using docker-compose:
1)Node.js should be installed
2)Angular cli should be installed

After step (1) and (2), run the below commands:
```
   mkdir /angular [ any name of your choice ]
   cd /angular
   ng new angular-learn [ any name of your choice ]
   cd angular-learn
   --create the Dockerfile--
   cd ../
   --create the docker-compose.yml file and use 'docker-compose up'--
```

### If there are any npm ERRORS, fix it by following the below steps:
  Run the command:
  ```
    ping registry.npmjs.org
      Output:- PING registry.npmjs.org IP ## bytes of data
    vim /etc/hosts
    IP registry.npmjs.org [ add this line to the file and save it ]
  ```
   
If you are unable to run Joomla, I suggest you to remove all the containers by using 
```docker rm -f $(docker ps -a -q)``` 
and retry.

If you are using virtual machines( guest OS ) and want to access them on your host OS ( Bare Metal ) and if you are getting an error in the web browser use ```systemctl stop firewalld``` for a while and reload the web page.
NOTE:- while using 'docker-compose up' the firewall should be enabled otherwise you will get an error = ```systemctl start firewalld```
    
