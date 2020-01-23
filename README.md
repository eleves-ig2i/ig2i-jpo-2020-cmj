# Avant tout
Ce projet a été fait pour être utilisé sur Ubuntu.
123) Placez vous dans le répertoire tournoi ;

# Pour jouer un tournoi
4) Ouvrez deux terminaux. Dans chacun d'eux, exécutez 'source dyn.sh'. 
Cela exécute les commandes du fichier dyn.sh dans le shell courant, ce qui permet d'ajouter une variable d'environnement (LD_LIBRARY_PATH) pour indiquer le chemin des librairies externes.
5) Dans le premier terminal, exécutez ./bin/moteur.exe 1 (1 s/coup) ;
6) Dans le second terminal, exécutez ./genJoueurs.sh 5, ce qui inscrit 5 joueurs au tournoi ;
7) Ouvrez le répertoire tournoi/web avec votre explorateur de fichiers... et double-cliquez sur avalam-tournoi.html.
8) Appuyez sur ENTREE dans le terminal exécutant moteur.exe ;

# Pour jouer un duel
4) Ouvrez trois terminaux. Dans chacun d'eux, exécutez 'source dyn.sh' ;
5) Dans le premier terminal, exécutez ./duel.exe ; 
6) Dans le second terminal, exécutez un premier joueur ; 
7) Dans le second terminal, exécutez un second joueur.

Si vous désirez jouer contre un moteur de jeu, vous pouvez choisir les joueurs 'humain1.exe' (saisie des indices des coups) ou 'humain2.exe' (saisie des cases de départ et d'arrivée du coup).

8) Appuyez sur ENTREE dans le terminal exécutant duel.exe ;
9) Indiquez les temps de réflexion de chaque joueur au clavier ;
10) Appuyez à nouveau sur ENTREE pour démarrer la première partie du duel ;
11) Ouvrez le répertoire tournoi/web avec votre explorateur de fichiers... et double-cliquez sur avalam-tournoi.html ;
12) Après chaque partie du duel, vous pourrez indiquer si vous voulez poursuivre le duel ou non.


Si jamais vous tuez le process moteur ou duel, il se peut que des process joueurs continuent de s'exécuter. 
Il faut alors invoquer ./killjoueurs.sh avant de recommencer un tournoi


