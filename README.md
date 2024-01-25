# Tp-Minikube

## Explications
### Docker  
Notion d'image : un conteneur est un ensemble de fichiers sur lequel on exécute un processus.

Ces images sont donc des archives qui peuvent être échangées entre plusieurs hôtes, mais aussi être
réutilisées. Cette réutilisation est rendue possible par une seconde innovation, l'organisation en
couches.

Un Dockerfile est un script qui décrit les étapes nécessaires pour créer une image Docker. Il spécifie les dépendances, la configuration et les commandes d'exécution

### Minikube 

Minikube est une solution qui permet de créer un cluster Kubernetes local sur votre machine. Kubernetes est un système open-source pour automatiser le déploiement, la mise à l'échelle et la gestion des applications conteneurisées.

### Kubernetes

Pods : Les pods sont la plus petite unité déployable dans Kubernetes. Ils représentent un ensemble d'un ou plusieurs conteneurs qui partagent le même espace de réseau et de stockage.

Déploiements : Les déploiements permettent de déclarer l'état souhaité d'une application dans Kubernetes. Ils gèrent le déploiement, la mise à l'échelle et la mise à jour des applications.

Services : Les services Kubernetes offrent un moyen abstrait de définir un ensemble de pods et de les exposer à l'intérieur ou à l'extérieur du cluster.
