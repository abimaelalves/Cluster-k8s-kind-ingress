## Criando cluster kubernetes simples com ingress utilizando o kind

### Instalação do kind + documentação
https://kind.sigs.k8s.io/

### Criar cluster
kind create cluster --name k8s --config kind.yaml

### Instalar ingress controller
kubectl apply -f ingress-controller.yaml