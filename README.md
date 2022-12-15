# Kafka manager Kubernetes Installation

> In case of need , you can change image in values file.

### First of all , we create the Namespace.

 ```
 kubectl create ns kafka-manager
 ```

### Then , we edit the our ‘values.yaml’ file.

 ```
 kubectl apply -f values.yaml -n kafka-manager
 ```
 
### And we deploy the ‘ingress.yaml’ file.

 ```
 kubectl apply -f ingress.yaml -n kafka-manager
 ```
 
 
 

