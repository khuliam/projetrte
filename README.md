# projetrte

# Objectif:
Cette branche est mis en place pour faire appliqué la première utilisation de git par chacun des membres afin de voir quel sera la procédure a suivre tout au long du projet pour commiter les modifications apporter au projet. Il est donc question que chacun clone le dépôt du projet sur sa machine, modifie le contenu du fichier LISTE_DES_MEMBRES.txt pour y ajouter son non suivant la nomenclature du fichier et par la suite envoyer les modifications apportées au fichier sur github.

# La méthodologie a suivre
1) Cloné le dépôt : *git clone https://github.com/khuliam/projetrte.git
2) Se deplacer dans le dossier projetrte: *cd projetrte
3) Se positionner sur la brancher de travail avec: *git checkout List_of_memebers
4) Se mettre a jour avec *git pull ou *git pull https://github.com/khuliam/projetrte.git List_of_memebers
5) Modifier le fichier LISTE_DES_MEMBRES.txt et y ajouter son Nom
6) Ajouter le fichier modifier dans la liste des fichier a envoyer sur github avec: *git add LISTE_DES_MEMBRES.txt
7) Commiter le travail avec: *git commit -m "ton message"
8) Envoyer le travail dans le dépôt distant github: *git push https://github.com/khuliam/projetrte.git List_of_memebers

Une fois tout cela fait, se rendre sur github, retrouver projetrte et faire un *pull request

# NB
Les merges Request ou pull request ce ferons de la branche *List_of_memebers vers la branche nommé *test
