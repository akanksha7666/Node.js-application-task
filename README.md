1. creating 3 docker file for admin, clinet-streaming and clinetlicent
then build images
git clone https://github.com/resolutedeveloper/docker-task.git
 New repo git clone https://github.com/akanksha7666/Node.js-application-task.git
-  sudo -i
-  ls
-  mv docker-task/* Node.js-application-task/
-  cd Node.js-application-task
- ls
- cd admin
- vim dockerfile
- docker build . -t admin
- cd clinet-steraming
- vim dockerfile
- docker build . -t clinet-streaming
- cd clinetlinet
- vim dockerfile
- docker build . -t clinetlicent
- docker images

2. images created then create docker compose file that definging variable .env 
     
-  vim docker-compose.yaml
- docker compose up --build -d
- docker ps 




