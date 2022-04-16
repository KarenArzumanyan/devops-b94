# devops-b94
DevOps part B9.4 (Docker)

docker build -t devopsb94 .

docker run -p 9911:80 --name server devopsb94

docker tag devopsb94 karenarzumanyan/devopsb94:latest

docker push karenarzumanyan/devopsb94:latest

docker pull karenarzumanyan/devopsb94:latest

https://hub.docker.com/repository/docker/karenarzumanyan/devopsb94