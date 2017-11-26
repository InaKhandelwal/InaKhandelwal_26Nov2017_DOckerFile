# InaKhandelwal_26Nov2017_DockerFile

For building the image use the below command
docker build -t inakdwl/inakhandelwal_26nov2017_dockerfile .

For running the docker image in order to access the apache tomcat on port 7080 use the below command:
docker run --name apache -p 7080:8080 inakdwl/inakhandelwal_26nov2017_dockerfile:latest
