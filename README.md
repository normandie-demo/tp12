# TP numéro 12

## Objectif:

Exécuter une commande contenant un secret et éviter son affichage

## Besoin:

- Créer un Playbook *init.yaml* tel que:
  - S’exécute sur les hosts *back*
  - S’appuie sur une variable **mysql_root_password**
  - Exécute l’initialisation du password root mariadb en assurant de ne pas logguer la commande (prévoir le *ignore_errors* en cas de nouveau lancement)
  - Exécuter le Playbook en mode **Verbose**



> La commande pour initialiser le mot de passe root est: `/usr/bin/mysqladmin -u root password '<mot de passe>'`
