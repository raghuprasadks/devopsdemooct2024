docker commands

docker build -t demoflaskapp1 .

docker run 5000:5000 demoflaskapp1

docker ps

docker stop <container_id_or_name>

docker login

docker tag demoflaskapp1 raghuprasadkonandur/demoflaskapp1

docker images

docker push raghuprasadkonandur/demoflaskapp1

docker pull raghuprasadkonandur/demoflaskapp1

docker images

docker rmi <imadocker run -d -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home --name jenkins jenkins/jenkins:ltsge_id_or_repository:tag>

run in detached mode

docker run -d -p 5000:5000 raghuprasadkonandur/demoflaskapp1


jenkins

pull jenkins

docker pull jenkins/jenkins:lts




a8eeb911385944a1a5b7e6faac28c31e

adminuser/adminuser

http://localhost:8080/

stop and remove jenkins

docker stop jenkins

docker rm jenkins
