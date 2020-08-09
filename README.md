# Minikube-installation
 
 Kubectl  and Minikube installation
```
https://kubernetes.io/docs/tasks/tools/install-kubectl/
```

# Install Docker for Mac
```
brew install docker
```
# Install Hyperkit VM Manager
This is the tool which creates VMs on which minikube will be running our pods.
```
brew install hyperkit
```
Then install the most recent version of minikube's fork of the hyperkit driver:
```
curl -LO https://storage.googleapis.com/minikube/releases/latest/docker-machine-driver-hyperkit \ && 
sudo install -o root -g wheel -m 4755 docker-machine-driver-hyperkit /usr/local/bin/
```

# Install minikube
```
brew install kubernetes-cli
```

# Start your minikube
```
minikube start
```
# Stop your minikube
```
minikube stop
```
