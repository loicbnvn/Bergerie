BERGERIE – Prototype PWA local
================================

Ce dossier contient une première version fonctionnelle de Bergerie.

Fonctionnalités incluses :
- Fiches animaux : brebis, béliers, agneaux
- Numéro de boucle visuelle et identifiant RFID saisis manuellement
- Date de naissance, sexe, mère et notes
- Lots de lutte : nom, bélier, dates, sélection individuelle des brebis
- Agnelages : brebis, date, total nés, vivants, morts, assistance et notes
- Recherche et filtres
- Sauvegarde JSON et restauration
- Stockage local IndexedDB
- Cache hors connexion après le premier chargement

IMPORTANT :
Une PWA doit être publiée sur une adresse HTTPS pour être installable et permettre
le fonctionnement hors connexion via le service worker. Ouvrir index.html directement
depuis le dossier ne suffit pas pour l'installation PWA.

Aucune donnée n'est envoyée à un serveur par ce prototype. Les données restent
dans le navigateur de l'appareil. Exportez régulièrement une sauvegarde JSON.

Cette version est un prototype de départ : testez-la avec quelques animaux fictifs
et une sauvegarde avant d'y saisir toutes les données réelles de l'élevage.
