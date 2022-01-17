# Workshop Mão na Massa Introdução ao Kubernetes

**Pré Requisitos:**

**1. Instalação e configuração do Docker Desktop**
- Windows: https://www.docker.com/products/docker-desktop
- Ubuntu 20.04: https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04-pt
- MacOS: https://hub.docker.com/editions/community/docker-ce-desktop-mac

**2. Habilitar o Kubernetes no Docker Desktop**
- Windows e Mac: https://docs.docker.com/desktop/kubernetes/
- Ubuntu 20.04, vamos utilizar o microk8s: https://linuxhint.com/install-kubernetes-ubuntu-single-node/ e https://microk8s.io

**3. Instalar o kubectl**
- Windows: choco install kubernetes-cli. É necessário ter o chocolatey instalado. Caso não tenha instalado: https://chocolatey.org/install. Realizar a instalação via Windows Terminal com permissão de Administrador. 
- Ubuntu https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/#install-using-native-package-management
- MacOS: https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/#install-with-homebrew-on-macos

**4. Teste do Kubernetes**
- Abrir um terminal e executar o seguinte comando: kubectl get nodes. Deverá aparecer a seguinte saída:
➜ kubectl get nodes

NAME.            STATUS.        ROLES.              AGE.  VERSION
docker-desktop.   Ready.   control-plane,master.    19d.  v1.22.4 
