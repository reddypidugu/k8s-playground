# Creating Kubernetes Cluster using KinD

### Create
````
$ ~ kind create cluster --config kind-config.yaml --name cluster
$ ~ kubectl cluster-info --context kind-cluster
````
### Deploying a simple deployment of nginx-deployment
````
$ ~ cd deployment
$ ~ kubectl apply -f .
````
### Scaleup the replicas by modifying deployment.yaml 
Changing the replicaset number 


### Delete Cluster
````
$ ~ kind delete cluster
 