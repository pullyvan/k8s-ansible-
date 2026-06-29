# k8s-ansible

## Pré-requis
pour ce projet k8s Il faut :
´´´
virtualbox
4 Worker node (1 front-end and worker node )
3 Control plain
vagrant
ansible
´´´
## Objectif
Le but est de crée un cluster dans le but de pouvoir faire tourner un container avec ton site web qui affichera ton cv sur son réseau interne.

Il faut pouvoir déployer et ça doit être scalable.
1. un script vagrant pour générer les vms
2. Une fois les vms déployer un script ansible doit être exécuter pour configurer les vms avec Kubernetes. Tu peux t'inspirer de kubespray
3. le cluster doit avoir accès au réseau externe uniquement via le front-end(2 interfaces) 
