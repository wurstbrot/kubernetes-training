# kubernetes-training
Minimum Kubernetes version 1.16

# Preparation
## Preparation of k3s
```shell
curl -sfL https://get.k3s.io | sh -s - --docker

# to use kubectl and not k3s kubectl
sudo chmod 755 /etc/rancher/k3s/k3s.yaml 
export KUBECONFIG=/etc/rancher/k3s/k3s.yaml
```