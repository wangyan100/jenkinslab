# jenkins image
docker pull jenkins/jenkins

docker-compose up -d # create service based on compose yml file
docker-compose start / stop
docker-compose restart jenkins  # restart jenkins service which created by compose yml
docker-compose down # delete service

jenkins password 
c7fc78f999bb4e36af106d31ea60c098

docker exec -ti jenkins bash  # enter jenkins docker image with bash shell
docker exec -it -u root jenkins /bin/bash