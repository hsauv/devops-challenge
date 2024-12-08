Day2: Réduire la taille des images Docker avec des multi-stage builds:

Une image Docker contient tout ce qui est nécessaire pour exécuter une application, mais lors du processus de build, des fichiers inutiles 
(outils de développement, dépendances, logs, etc.) peuvent être inclus, ce qui augmente la taille de l'image.

Avec multi-stage builds, On peut séparer la construction en plusieurs étapes, ce qui permet de n'inclure que les fichiers nécessaires dans l'image finale.
