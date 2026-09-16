# node-docker-ecr-demo
project 2

Node js + Docker + ECR + Ec2 using GitHub actions.

Developer
|  git push
GitHub repository
|
GitHub actions ----
|                  |
Docker build     Aws login 
  \              /
    Amazon ECR
        |    docker pull

       Ec2
        |
     Docker run (container will start)
        |
       Nodejs application will run
         |
ec2 public :3000





