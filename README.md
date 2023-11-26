 simple node.js application dockerized with docker file. 

 docker build -t node-app:1.0 .
 docker images
 docker run -d -p 3000:3000 node-app:1.0
 docker ps
 docker logs dfa05c946c8d <-container id