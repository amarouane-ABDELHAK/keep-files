# keep-files
# keep-files
systemd-run --scope --user -p "Delegate=yes" kind create cluster --name ray-cluster --config kind-cluster-conf.yml

 kind get clusters
 # install ingress
 kubectl apply -f /home/amarouane/workstation/github/keep-files/deploy-ingress-nginx.yaml
 # Install rayoperator
 kubectl create -k "github.com/ray-project/kuberay/ray-operator/config/default?ref=v1.3.0"
# Install service
 k apply -f /home/amarouane/workstation/github/keep-files/ray-service.sample.yaml
 
 kubectl get rayservice

 k apply -f /home/amarouane/workstation/github/keep-files/ingress.yml

HELLO
HELLO 2
HELLO 3
HELLO 4
WORLD
WORLD 2
Universe
More Universe
