# projetrte

# Avant de commencer, faite ceci
Configurez votre installation locale de Git pour utiliser vos informations d'identification GitHub en saisissant les informations suivantes :

1) git config --global user.name "github_username"
2) git config --global user.email "email_address"

email_address est votre adresse mail et github_username est votre nom d'utilisateur github (qui s'affiche génerallement en haut, a l'extrême droite dans github)

# pour des raison de sécurité, l'authentification est desormais valider que via les tokens. donc vous devez vous rendre dans votre compte github et créer un token. 
# vous devez également consulté votre boite de mail pour accepter l'invitation qui vous a été envoyer pour devenir colaborateur du projet sinon tous vos push sérons réjeter. 

# Objectif:
Cette branche est mis en place pour faire appliqué la première utilisation de git par chacun des membres afin de voir quel sera la procédure a suivre tout au long du projet pour commiter les modifications apporter au projet. Il est donc question que chacun clone le dépôt du projet sur sa machine, modifie le contenu du fichier LISTE_DES_MEMBRES.txt pour y ajouter son non suivant la nomenclature du fichier et par la suite envoyer les modifications apportées au fichier sur github.

# La méthodologie a suivre
1) Cloné le dépôt : git clone https://github.com/khuliam/projetrte.git
2) Se deplacer dans le dossier projetrte: cd projetrte
3) Se positionner sur la brancher de travail avec: git checkout List_of_memebers
4) Se mettre a jour avec *git pull ou git pull https://github.com/khuliam/projetrte.git List_of_memebers
5) Modifier le fichier LISTE_DES_MEMBRES.txt et y ajouter son Nom
6) Ajouter le fichier modifier dans la liste des fichier a envoyer sur github avec: git add LISTE_DES_MEMBRES.txt
7) Commiter le travail avec: git commit -m "ton message"
8) Envoyer le travail dans le dépôt distant github: git push https://github.com/khuliam/projetrte.git List_of_memebers

Une fois tout cela fait, se rendre sur github, retrouver projetrte et faire un *pull request

# NB
Les merges Request ou pull request ce ferons de la branche List_of_memebers vers la branche nommé test.

