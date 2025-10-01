# Projet de Fin d'Études : Plateforme Cloud Sécurisée et Automatisée

**Statut du projet : Terminé**

## Avis de confidentialité

Ce projet a été réalisé dans un cadre académique. Conformément aux règles de confidentialité, **le code source complet (Terraform, Ansible, CI/CD, etc.) est privé et ne peut être partagé publiquement.**

Les diagrammes ci-dessous présentent l'architecture et les concepts clés mis en œuvre. Je suis entièrement disponible pour discuter en détail de chaque aspect de ce projet, de mes choix techniques et des défis rencontrés lors d'un entretien.

---

## Vue d’ensemble de l’architecture

### 1. Vision globale du projet (Flux DevSecOps complet)
Cette vue d'ensemble illustre le parcours complet, du code poussé par le développeur jusqu'au déploiement sur les différents environnements Kubernetes, en intégrant la sécurité, le monitoring et le logging.

<img width="100%" alt="Vision globale du projet" src="https://github.com/user-attachments/assets/b8eb3011-84f0-42ca-a2bf-185b0304167a" />

### 2. Infrastructure déployée sur AWS
Ce diagramme détaille l'infrastructure réseau et de calcul mise en place sur AWS pour héberger le cluster EKS et ses dépendances, en suivant les meilleures pratiques de sécurité et de haute disponibilité.

<img width="100%" alt="Infrastructure AWS" src="https://github.com/user-attachments/assets/b638c870-d0eb-482d-ae96-a0606ff0ed6a" />

### 3. Répartition de l’application 3-tiers dans Kubernetes
Voici comment l'application (frontend, backend, base de données ) est déployée et exposée au sein du cluster Kubernetes, en utilisant des services, des ingresses et des volumes persistants.

<img width="100%" alt="Architecture Kubernetes" src="https://github.com/user-attachments/assets/1e643135-69c7-44f7-895d-04e56914c4c8" />

### 4. Architecture des pipelines CI/CD
Les trois schémas suivants montrent l'architecture détaillée des pipelines d'intégration et de déploiement continu pour les environnements de **développement**, de **test** et de **production**.

**Pipeline de Développement :**
<img width="100%" alt="Pipeline de Développement" src="https://github.com/user-attachments/assets/c2495215-2b15-4e9d-b5fb-dd5c6ec28d6d" />

**Pipeline de Test :**
<img width="100%" alt="Pipeline de Test" src="https://github.com/user-attachments/assets/da1ce181-9c90-4f97-97e1-2aeb38678ad2" />

**Pipeline de Production :**
<img width="100%" alt="Pipeline de Production" src="https://github.com/user-attachments/assets/13fb1ca1-c7d0-455f-a5f5-1fec8bc3537e" />

