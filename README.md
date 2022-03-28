# Kubernetes

Prerequisites - Install Docker 

## Installation

minikube installation 

```bash
wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 

#copy to /usr/bin
sudo cp minikube-linux-amd64 /usr/local/bin/minikube

#chmod 
sudo chmod 755 /usr/local/bin/minikube

echo $(minikube version)
```

Kubectl download
```bash
curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl

chmod +x ./kubectl

sudo mv ./kubectl /usr/local/bin/kubectl

echo $(kubectl version -o json)


#run minikube using no driver
sudo minikube start --driver=none

 
#you will be prompt to do the below
 - sudo mv /root/.kube /root/.minikube $HOME
 - sudo chown -R $USER $HOME/.kube $HOME/.minikube
 
 
 #run kubectl cmd as sudo user
 
 
 ```
 
 
 

 
 


```
