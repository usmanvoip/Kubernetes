# Basics of Kubernetes

## Defination
**Kubernetes** (also known as k8s or "kube") is an open source container orchestration platform that automates many of the manual processes involved in deploying, managing, and scaling containerized applications.

### What Elasticbeans do for us in AWS
![2021-05-10_13-08](https://user-images.githubusercontent.com/78042886/117626948-1bd12e00-b191-11eb-9920-161400b159f8.png)

### What we actually wana do
![2021-05-10_13-11](https://user-images.githubusercontent.com/78042886/117627134-491ddc00-b191-11eb-8260-6a9497688979.png)

### What and Why k8s

![image](https://user-images.githubusercontent.com/78042886/117804285-08958f80-b271-11eb-93e1-0a5700cb826c.png)

### How to work with k8s.

![image](https://user-images.githubusercontent.com/78042886/117804377-23680400-b271-11eb-9d0f-26af9139be32.png)


### minikube is local Kubernetes, focusing on making it easy to learn and develop for Kubernetes.
 

![image](https://user-images.githubusercontent.com/78042886/117804765-9a9d9800-b271-11eb-99db-38918ed57ca1.png)


### K8s use config and command to create objects.
![image](https://user-images.githubusercontent.com/78042886/117804930-d0db1780-b271-11eb-85b7-2449eea75620.png)


### Example Object Types
![image](https://user-images.githubusercontent.com/78042886/117805013-e8b29b80-b271-11eb-898c-7771a0536cb1.png)
![image](https://user-images.githubusercontent.com/78042886/117817539-22d76980-b281-11eb-896f-5c32f55165bb.png)


### minikube to container networking
![image](https://user-images.githubusercontent.com/78042886/117818069-b0b35480-b281-11eb-8396-8df023f39138.png)


### Pod with closely related container
![image](https://user-images.githubusercontent.com/78042886/117805113-07189700-b272-11eb-95c1-45417cd806bb.png)


### Some Explaination of config file 

#### versions of config file
![image](https://user-images.githubusercontent.com/78042886/117805162-1566b300-b272-11eb-86fb-9c754366ce7e.png)

#### Metadata
![image](https://user-images.githubusercontent.com/78042886/117819640-2f5cc180-b283-11eb-9e35-efe3b8fe057e.png)

#### Labels
![image](https://user-images.githubusercontent.com/78042886/117819834-5f0bc980-b283-11eb-9a4b-04d80d7e1ad9.png)

#### NodePort
![image](https://user-images.githubusercontent.com/78042886/117819944-7f3b8880-b283-11eb-9e90-c6d9dc5515b2.png)

![image](https://user-images.githubusercontent.com/78042886/117820053-99756680-b283-11eb-9c1c-caf5ba230421.png)




### Some Definations
#### Custer:
A Kubernetes cluster is a set of node machines for running containerized applications. If you’re running Kubernetes, you’re running a cluster.

#### Control plane: 
The collection of processes that control Kubernetes nodes. This is where all task assignments originate.

#### Nodes: 
These machines perform the requested tasks assigned by the control plane.

#### Pod: 
A set of 1 or more containers deployed to a single node. A pod is the smallest and simplest Kubernetes object.

#### Service: 
A way to expose an application running on a set of pods as a network service. This decouples work definitions from the pods.

#### Volume: 
A directory containing data, accessible to the containers in a pod. A Kubernetes volume has the same lifetime as the pod that encloses it. A volume outlives any containers that run within the pod, and data is preserved when a container restarts.

#### Namespace: 
A virtual cluster. Namespaces allow Kubernetes to manage multiple clusters (for multiple teams or projects) within the same physical cluster.




