# kafka-manager-kubernetes-deploy

we create namespace

 ```
 kubectl create ns kafka-manager
 ```

 'values.you' can edit the yaml file. Setup;

 ```
 kubectl apply -f values.yaml -n kafka-manager
 ```