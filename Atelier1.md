# Atelier 1 : Cadrage et socle de sécurité  
## 1. Périmètre et mission

L’analyse couvre l’ensemble du système d’information de **DataSecuRetail**, PME de e-commerce spécialisée dans la vente d’objets technologiques via son site marchand.  
Le périmètre comprend :
- L’infrastructure interne  
- Le site web marchand  
- La base de données clients hébergée sur un cloud externe  
- Les échanges avec les prestataires (hébergeur, plateforme de paiement, transporteur, prestataire IT)

La mission principale est d’assurer la **vente en ligne continue et sécurisée d’objets technologiques**, en protégeant les données clients et en garantissant la disponibilité du site.  
Les processus critiques identifiés sont : la **prise de commande**, la **gestion des données clients** et la **logistique des livraisons**.

---

## 2. Valeurs métier et événements redoutés

| Valeur métier | Événement redouté | Gravité (1–4) | Justification |
|----------------|------------------|----------------|----------------|
| Disponibilité du site e-commerce | Panne ou attaque rendant le site inaccessible pendant plusieurs heures | 4 – Critique | Perte directe de chiffre d’affaires et d’image |
| Intégrité de la base clients | Altération ou perte des données clients | 3 – Grave | Erreurs de commande et perte de confiance des clients |
| Confidentialité des données personnelles | Fuite ou vol des données hébergées sur le cloud | 4 – Critique | Risques juridiques (RGPD) et atteinte réputationnelle |
| Disponibilité du mini-ERP | Indisponibilité du logiciel de gestion des commandes et stocks | 3 – Grave | Retards et perturbations de livraison |
| Intégrité du réseau interne | Infection par un ransomware bloquant les serveurs et postes | 4 – Critique | Blocage complet de l’activité et pertes financières |

---

## 3. Socle de sécurité – Exigences et mise en œuvre actuelle

| Exigences ou bonnes pratiques (référentielles) | Observations dans l’entreprise |
|------------------------------------------------|--------------------------------|
| Authentification forte et politique de mots de passe sécurisés | Mots de passe simples, aucune double authentification |
| Sauvegardes régulières et tests de restauration | Sauvegardes hebdomadaires, pas de vérification de restauration |
| Segmentation réseau et mise à jour des systèmes | Réseau plat, mises à jour irrégulières |
| Supervision et détection d’incidents | Aucune supervision ni système d’alerte en place |
| Sensibilisation des employés à la cybersécurité | Absence de formation, risque d’hameçonnage élevé |

---
