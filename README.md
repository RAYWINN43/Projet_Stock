# Site Gestion de Stock

> **MEMBRES DU GROUPE :**
> - **BLAIN Antoine**
> - **PECONTAL Corentin** 
> - **MARTIN Evan**

---

## 1. Présentation du Projet
Dans ce projet, nous allons créer un site site de gestion de stock, permettant de suivre les mouvements d’entrée et de sortie de produits, tout en répartissant les équipes et les missions associées. Le modèle repose sur plusieurs entités principales telles que les produits, les utilisateurs, les stocks, les équipes et les missions, ainsi que les mouvements d’entrée/sortie qui permettent de tracer les quantités manipulées. Chaque utilisateur possède un niveau de permission (utilisateur, manager ou administrateur) afin de contrôler les accès et responsabilités, notamment pour la gestion des équipes et la désignation des chefs de mission. Le système intègre également une organisation des produits par catégorie et par rayon, facilitant leur localisation et leur gestion.

**Fonctionnalités principales :**
* Authentification utilisateur
* Créer / modifier / supprimer un compte
* Créer / modifier / supprimer un mouvement
* Voir historique des mouvements
* Voir les stocks
* Rechercher des mouvements
* Rechercher des produits (stockés ou non)
* Envoyer des notifications à certains seuils de stockage
* Planifier des notifications lorsqu'un certain produit devient disponible ou indisponible
* Répartir les utilisateurs entre différentes équipes
* Répartir les équipes entre différentes missions
* Répartir les missions entre différents rayons
* Créer / modifier / supprimer une équipe 
* Créer / modifier / supprimer une mission
* Créer / modifier / supprimer un rayon


## 2. Architecture Technique

### Schéma d'infrastructure
![Architecture du Projet](//www.plantuml.com/plantuml/png/TPDDRjim48NtFCL0onO6scqMHGp4Q0tOGH0X1s2aiJqmVnnowA0jUg5UenShAKeXBK0RcIO_lZTlDBhtB1q7hOG_axb89pLqIdg_PdRq6XYtdJKj_KBuKY7-97lxJkO81way2e4cQ7X2fybxicQ7LrJmMm2yj9ld-BDVFww_3wlrmtxxAFu8CTX0ixVXYXeD-mQaXurXXzXQnuI3mEUTZJRKfsNBBdbsLgSBaXnce9FgGJ927n-RQpnAsrl3U4G7Rq4Q9iRY-SAao4Ssk2KBr99KzVyIxxrRr_-G_fIsvr5LUXQ79sVxGBoaRgmUYMhp83KfXNLE6HDOHrNfBTlkV2DRpZPlWIxpffK-cA3HsGoLI_kSOgbIblvSu6VvSncDeH9vymARJmsiLj-W-TfyzEGEEciwT0Q5o77IgLsj8ZsZeeJX0cMf2DKUaTGV8oJ4b2SxPpf5JXmEYuAKukgHIDOdF0YHxnMbEQLHlpgCdhajKu4BAKHzEN7p4RhBGrJ9ZMfZlK8OomYEZYS6UnXZYHtwgHBeBQNfXtz_sQ7euquefXvCF9KXVv9eUaXwSzN9R8T35vBaf1TCBJUfvI-x5hoFow3LVm00)
