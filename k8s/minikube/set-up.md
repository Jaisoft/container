
```


brew install minikube


minikube version

Basic Commands:
  start            Starts a local Kubernetes cluster
  status           Gets the status of a local Kubernetes cluster
  stop             Stops a running local Kubernetes cluster
  delete           Deletes a local Kubernetes cluster
  dashboard        Access the Kubernetes dashboard running within the minikube cluster
  pause            pause Kubernetes
  unpause          unpause Kubernetes

minikube start --driver=virtualbox


minikube start --driver=virtualbox --nodes 2 -p multinode-demo


minikube start --driver=virtualbox --cpus 4 --memory 10240 --nodes 2 -p multinode-demo


minikube stop  -p multinode-demo
     

minikube node add


Advanced Commands:
  mount            Mounts the specified directory into minikube
  ssh              Log into the minikube environment (for debugging)
  kubectl          Run a kubectl binary matching the cluster version
  node             Add, remove, or list additional nodes
  cp               Copy the specified file into minikube

```
