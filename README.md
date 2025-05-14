🛡️ Dossier d'Architecture Technique (DAT) – Sécurisation Réseau

Ce dépôt contient un dossier d’architecture technique orienté cybersécurité, réalisé dans le cadre d’un projet pédagogique. Il vise à proposer une architecture réseau sécurisée pour une PME sous-traitante d’Airbus, en tenant compte des exigences spécifiques du secteur aéronautique.

🏢 Contexte
L’entreprise concernée est une PME française du secteur aéronautique, répartie sur deux sites physiques :
  - Site 1 : Services technique et commercial.
  - Site 2 : Services Finance/RH et Direction.
Chaque site compte 50 utilisateurs, soit un total de 100 utilisateurs.

Infrastructure existante
   - 3 serveurs internes sur le site 1 :
      - Serveur de fichiers
      - Serveur de messagerie
      - Serveur de base de données
  - 1 serveur web hébergé sur le site 1, accessible depuis l’extérieur en HTTPS.
  - Connexion Internet par site : fibre optique 100 Mb/s symétrique.
  - Locaux techniques sur chaque site, équipés de baies réseau et de l’arrivée du lien Internet.

🎯 Objectifs du projet
  - Assurer la communication sécurisée entre les deux sites sans intervention sur les postes clients.
  - Permettre aux utilisateurs nomades d’accéder au réseau de l’entreprise de manière sécurisée depuis n’importe où.
  - Sécuriser les accès LAN filaires sur chaque site.
  - Mettre en place deux réseaux Wi-Fi distincts sur chaque site :
      - Wi-Fi collaborateurs
      - Wi-Fi invités
  - Optimiser le nombre d’équipements pour éviter les dépenses inutiles, tout en garantissant un haut niveau de sécurité.
  - Assurer que le serveur web soit accessible depuis l’extérieur en HTTPS et puisse accéder au serveur de base de données.

📄 Contenu du dépôt
  - DAT.pdf : Dossier complet comprenant :
      - Étude de risque
      - Schéma réseau proposé
      - Plan d’adressage
      - Préconisations de sécurité
- Technical_diagram_Rev2.png : Schéma réseau détaillé.

🔐 Approche de sécurisation
Le projet adopte une approche basée sur les bonnes pratiques en matière de cybersécurité, notamment :
  - VPN site-à-site pour la communication inter-sites.
  - VPN nomade pour les utilisateurs distants.
  - Contrôle d’accès réseau (NAC) pour sécuriser les accès LAN filaires.
  - Segmentation réseau pour isoler les différents services et limiter la propagation des menaces.
  - Pare-feu pour filtrer le trafic entrant et sortant.
  - Systèmes de détection/prévention d’intrusion (IDS/IPS) pour surveiller les activités suspectes.
  - Authentification forte pour l’accès aux ressources critiques.
  - Sauvegardes régulières et plan de reprise d’activité (PRA) pour assurer la continuité des services.
