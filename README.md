# kafka-manager-kubernetes-deploy

we create namespace

 ```
 kubectl create ns kafka-manager
 ```

 'values.yaml' can edit the  file. Setup;

 ```
 kubectl apply -f values.yaml -n kafka-manager
 ```
 
  'ingress.yaml' can edit the  file. Setup;

 ```
 kubectl apply -f ingress.yaml -n kafka-manager
 ```
