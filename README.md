install docker /n
1) install docker-compose

2) cd "path to your project" ChatProject

3) sudo service docker start

4) sudo docker-compose up -d --build

to enter into container symfony tap this command line:
you can use symfony command into this container  
  A) sudo docker exec -it php74-container bash 

 to execute any other container just replace the name php74-container with the other container name
  sudo docker exec -it "your-container-name" bash
  
 
  
