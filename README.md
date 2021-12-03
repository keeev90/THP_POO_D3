# WELCOME !

## Installation et lancement

1. Ouvrir un terminal
2. Se positionner dans le répertoire du projet
3. $ bundle install
4. $ ruby app.rb
5. Enjoy !

## L'app MORPION est saucissonée ainsi : 

- run_app (c'est la chef d'orchestre !)
    - Demande le nom de chaque joueur et stocke la donnée
    - Lance une partie
    - Demande aux joueurs s'ils veulent rejouer 

- game.rb 
    - Initialise une nouvelle partie (new Board, new Player(s)) 
    - Permet de dérouler une partie avec un enchainement de rounds tant qu'il n'y ait pas une condition de fin de partir
    - Permet d'appeler la méthode pour nettoyer un tableau d'une partie

- board.rb
    - Initialise un tableau tout neuf à chaque nouvelle partie
    - Permet d'afficher le tableau à chaque round en tenant compte des choix des joueurs 
    - Permet de déterminer la fin d'une partie (tableau plein ou il y a un vainqueur)
    - Permet de nettoyer le tableau en cas de nouvelle partie

- player.rb
    - Définit les attributs de l'objet Player (nom, symbol)

- board_case.rb
    - Définit les attributs de l'objet BoardCase (id de la case, valeur de la case)

