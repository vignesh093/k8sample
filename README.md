
A sample kuburnete application

Build the docker image using below command:

docker build -t %image name% .

Create pods and services. Create the db pods and service first so that the web pod can identify it when started.

kubectl create -f pod.yml
