# Atelier 3 : Scénarios stratégiques

---

1. Compromission des comptes/outils du prestataire IT par hameçonnage ciblé ou exploitation d’une vulnérabilité de son infrastructure, donnant un accès privilégié au réseau de DataSecuRetail .  
2. Utilisation des canaux d’administration à distance pour un accès discret, suivi d’une reconnaissance des segments internes et des systèmes critiques (mini‑ERP, serveurs, postes) .  
3. Escalade de privilèges et préparation de l’effet de levier en identifiant sauvegardes, contrôleurs de domaine et points de restauration .  
4. Exfiltration préalable d’un extrait de la base clients via les interconnexions autorisées afin d’augmenter la pression par menace de divulgation .  
5. Déploiement coordonné d’un chiffrement des serveurs/postes pour provoquer une rupture de service du site et de l’ERP, paralysant commandes et stocks .  
6. Double extorsion combinant restauration contre rançon et chantage à la fuite de données pour accélérer le paiement .
---

## Scénario stratégique 2 : Exploitation de l’intégration paiement

1. Repérage d’une faiblesse de l’intégration (validation de redirection insuffisante, endpoint API laxiste, gestion des retours de paiement) entre le site marchand et la plateforme tierce .  
2. Mise en place d’un mécanisme d’interception côté client ou serveur pour capter métadonnées de transaction avant transfert aux services de paiement .  
3. Injection de pages ou scripts de paiement falsifiés pour détourner une fraction des montants vers des comptes contrôlés par l’adversaire .  
4. Collecte progressive et discrète de lots de cartes sur plusieurs semaines afin d’éviter une détection immédiate par les banques .  
5. Monétisation des données volées sur des places de marché illicites et déclenchement de fraudes signalées par les établissements financiers .  
6. Suspension temporaire des paiements en ligne, notifications réglementaires, impact réputationnel majeur et insatisfaction clients .

