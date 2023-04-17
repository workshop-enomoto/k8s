# Workshop Mão na Massa Introdução ao Kubernetes

**Pré Requisitos:**

**1. Instalação e configuração do Docker Desktop**
- Windows 11: https://www.docker.com/products/docker-desktop
- Ubuntu Jellyfish 22.04 (LTS): https://docs.docker.com/desktop/install/ubuntu/
- MacOS: https://docs.docker.com/desktop/install/mac-install/

**2. Habilitar o Kubernetes no Docker Desktop**
- Windows, Ubuntu e Mac: https://docs.docker.com/desktop/kubernetes/

**3. Instalar o kubectl**
- Windows: choco install kubernetes-cli. É necessário ter o chocolatey instalado. Caso não tenha instalado: https://chocolatey.org/install. Realizar a instalação via Windows Terminal com permissão de Administrador. 
- Ubuntu https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/#install-using-native-package-management
- MacOS: https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/#install-with-homebrew-on-macos

**4. Teste do Kubernetes**
- Abrir um terminal e executar o seguinte comando: kubectl get nodes. Deverá aparecer a seguinte saída:

NAME             STATUS   ROLES           AGE   VERSION\
docker-desktop   Ready    control-plane   2d    v1.25.4

**5. Instalação do AWS CLI**
- https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html. Depois de instalar executar o comando: aws --version. Deverá aparecer a seguinte saída: 
aws-cli/2.11.2 Python/3.11.2 Linux/5.10.16.3-microsoft-standard-WSL2 exe/x86_64.ubuntu.22 prompt/off

**6. Instalação do AWS eksctl**
- https://docs.aws.amazon.com/eks/latest/userguide/eksctl.html. Depois de instalar executar o comando: eksctl version. Deverá aparecer a seguinte saída:
0.137.0

**7. Criar uma nova conta na Amazon Web Services ou utilizar um já existente. Para criação de uma nova conta é necessário o cartão de crédito internacional para realização da criação de um cluster AWS Elastic Kubernetes Services (EKS). O período de utilização do cluster e gasto será de inteira responsabilidade do Aluno.**
- https://portal.aws.amazon.com/billing/signup#/start/email

**8. Durante o workshop será utiliza o VSCode**
- https://code.visualstudio.com/

