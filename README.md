# projetrte

# 1) Objectifs a atteindre
L’objectif générale visé dans ce projet est de pouvoir mettre en place un système de téléphonie IP en utilisant la solution libre Asterisk. Pour un premier temps l’implémentation ce fera sur nos ordinateurs physique qui ferons office de serveur mais l’objectif final sera de déployer la solution final fonctionnel sur un Raspberry Pi sur lequel on vas faire tourné le système d’exploitation Raspbian.

# 2)Fonctionnalités du système à implémenter
Notre système de téléphonie devra disposé du minimum des fonctionnalités ci-dessous :
• Appel vocale et vidéo
• Messagerie Vocale
• Serveur vocal interactif
• File d’attente
• Transferts d’appels
• Renvoi d’appel
• Conférence téléphonique
• Centre d’appel
• Mise en attente

Il sera également question de faire fonctionné le système via internet via. Pour cela, nous allons utiliser ngrok (Utilitaire utile pour créer des tunnels sécurisés vers des applications hébergées localement à l’aide d’un proxy inverse. C’est un utilitaire pour exposer n’importe
quelle application hébergée localement sur le Web.) pour pouvoir avoir une adresse IP publique. Il n’est pas exclus que des idées d’amélioration puise s’ajouter en fonction des besoins. Mais la plus value de notre système est qu’il devra être en mesure d’attribuer des extensions automatiquement aux nouveaux équipements détectés sur le réseau (un peu comme le service DHCP qui attribut les adresses IP de façons automatique dans un réseau ).

# 3) Fonctionnalités à implémenter pour chacune des équipes
Pour faciliter l’évolution dans le travail, nous allons travailler en petit équipe ( 03 équipes) et chaque équipe travaillera sur quelques unes des fonctionnalités réparti comme suit:

Equipe 1: Conférence téléphonique, Serveur vocal interactif, Mise en attente.

Equipe 2: Appel vocale et vidéo, Messagerie Vocale, Transferts d’appels, Configuration automatique.

Equipe 3: Renvoi d’appel, Centre d’appel, File d’attente.

# NB
La branche dev est celle sur laquelle seront faite les Merges Request(MR). donc pour chacune des équipes, une fois créer vos branches respective(equipe1, equipe2, equipe3), toutes vos commit seront faites sur ces branches là et les MR sur celle ci(dev) et seul moi (Owner ou scrum master) a le droit de faire des Merge Request sur la branche main. 
