## High availability
### Control Plane High Availability
When using control plane, you are comminicate through a load balancer. \
This includes clients such as kubelet instances running on worker nodes that interact with load balancer \
#### Etcd availability
stacked etcd: control plane nodes have individual etcds
external etcd: shared etcds running on seperate nodes 
## K8s Management tools
### kubectl
official command line interface for k8s
### kubeadm
create kubernetes clusters
### Minikube
auto set up a local single-node kubernetes cluser. Greatae FOR K8S FOR DEV purposes
### Helm
provides tamplating and package management for Kubernetes objects. \
You can use it to manage your own templates. You can also download and use shared templates
### Kompose
Translate Docker compose files into Kubernetes objects
### Kustomize
A configuration management tool for managfer k8s objects configuratinons. Share and reuse templates.
