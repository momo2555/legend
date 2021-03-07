# Legend

Projet initié par Momo dans le but de développer un buzzer connecté.

# Ajout des sous modules

Pour ajouter un sous module, il faut :
- Avoir le lien du repo déjà existant (`https://github.com/exemple/exemple`)
- Cloner le repo principal
    `git clone https://github.com/momo2555/legend.git`

- A partir de ce dossier, il faut executer la commande suivante pour ajouter le sous-module :
    `git submodule add https://github.com/exemple/exemple`

Maintenant le repo principale a un lien vers le sous-module.

:warning: Le sous module est lié à un commit. Donc si le sous module est modifié, il faut aussi comit les changements sur ce repo. En développement, on peut commit à chaques nouvelles fonctionnalités ajoutées.

