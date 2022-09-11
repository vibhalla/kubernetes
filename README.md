# kubernetes
This repository is used to check in the code used for Kubernetes testing. 

The first test is to get a prebuild Application and deploy it on Kubernetes

### Prerequisite
Kubernetes is installed and running

### Steps

kubectl apply -f ./helloappdeploy.yaml

kubectl create -f https://bit.ly/k4k8s

kubectl apply -f kong_proxy.yaml
