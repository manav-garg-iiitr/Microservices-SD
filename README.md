# Microservices-SD

To Run the project you will need some software requirements before hand
Docker
Kubernetes

For running you will need to type the command -  skaffold run
Firt time run will take a little time about half an hour
You can see the services running by typing the command -  kubectl get pods
 after all pods start running type the command -  kubectl port-forward deployment/frontend 8080:8080
 this will run the project on your localhost
