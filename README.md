Create a NGINX docker container and build :

docker build -t NGINX dockerfile-location

if you like to run image - docker run -it -d -p 8080:80 NGINX


Minikube cluster Installation in local Mac machine :
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-darwin-amd64
sudo install minikube-darwin-amd64 /usr/local/bin/minikube

Start your cluster :
minikube start

