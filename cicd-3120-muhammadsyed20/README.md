-I installed docker by using this command sudo apt install docker.io.
-To build the container you would have to pull form the dockerhub accound resulting in pulling all the latest images.
Then check to see bu using docker image command.
-To run the container you would have to do curl localhost:8080. or use your ipaddress like curl 10.0.0.25:8080 or 
curl 3.227.190.244:8080 like in my case.
-To view the project you would have to open up a browser and write your ipaddress along with :8080.
-To creat a DockerHub public repo open docerhub, click creat repository, and give it a name along with a
description and choose for it to be public or private.
-To authernticate with dockerhub i would use the same credentials as the github.
-Went to github to set secrets and secrets name.
-Github workflow makes it easier and connects docker to github and gives github the option to login for docker.
-Yes variables to change such as repository.
-What container restart script does is that it that it restarts all the containers.
-What webhooks does is that its a form of communicating.
-I installed webhook on the server with this command sudo apt-get install webhook.
