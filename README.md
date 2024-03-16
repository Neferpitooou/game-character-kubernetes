# game-character-kubernetes

1. Setup
- Downloading the latest version of kubectl
- Replace [VERSION] with the desired version, for example 'v1.23.0'
> curl -LO "https://dl.k8s.io/release/[VERSION]/bin/linux/amd64/kubectl"

2. Change permission
- Make the binary executable
> chmod +x ./kubectl

3. Installation
- Move the binary to a directory in the PATH sudo mv ./kubectl /usr/local/bin/kubectl
- Verifying the installation kubectl version --client
- Installing Minikube, a tool that runs a Kubernetes cluster locally
- Standard command line: curl -Lo minikube "https://storage.googleapis.com/minikube/releases/[VERSION]/m inikube-linux-amd64" && chmod +x minikube
- eplace [VERSION] with the specific version of Minikube
> curl -Lo minikube "https://storage.googleapis.com/minikube/releases/latest/mini kube-linux-amd64" && chmod +x minikube

4. Start
- Starting a local Kubernetes cluster with Minikube
- Standard command line: minikube start
> minikube start

5. Check
- Verifying that kubectl is properly installed and configured # Standard command line: kubectl version --client
> kubectl version --client
