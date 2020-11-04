Lorsque l'on travaille sur un projet, nous allons avoir un tas de fonctionnalités 
ou d'idées différentes que nous allons vouloir explorer. Certaines seront matures
rapidement, et d'autres mettrons plus de temps à se consolider. 

Le concept de branches dans github existe pour nous aider à gérer ces différentes
activité

Lorsque qu'une branche est initiée dans le projet (ou un clone dans votre propre espace),
vous créez un environnement dans lequel vous pouvez essayer de nouvelles idées.
Les modifications que vous apportez à cette branche n'affectent pas la branche
principale, vous êtes donc libre d'expérimenter et de valider des modifications.

Chaque fois que l'on ajoute, modifie ou supprime un fichier, on effectue un commit
et on l'ajoute à notre branche. 

Ces commits créent également un historique transparent de votre travail que les 
autres peuvent suivre pour comprendre ce que vous avez fait et pourquoi. Chaque commit 
a un message associé, qui est une description expliquant pourquoi une 
modification particulière a été apportée. De plus, chaque commit est considéré comme 
une unité de changement distincte. Cela permet d'annuler les modifications si 
un bug est détecté ou si l'on décide de se diriger dans une direction différente.

Les Pull Requests lancent une discussion sur un ensemble de commits. N'importe qui
peut voir exactement quelles modifications seraient fusionnées s'il acceptait votre demande.

Une Pull Request peut être ouverte à tout moment au cours du processus de 
développement: lorsque l'on a peu ou pas de code mais que l'on souhaite partager 
des captures d'écran ou des idées générales, lorsque l'on est bloqué et avons 
besoin d'aide ou de conseils, ou lorsque l'on est prêt à faire revoi/relire notre 
travail. 
En utilisant le @someone dans votre message de Pull Request,
vous pouvez demander des commentaires à des personnes ou des équipes spécifiques
où qu'elles se trouvent.

Une fois qu'une Pull Request a été ouverte, la personne de l'équipe 
qui examine les modifications peut avoir des questions ou des commentaires. 
Peut-être que le style de codage ne correspond pas aux standards du projet, 
que le changement manque des tests unitaires, ou peut-être que tout est nickel.
Les Pull Requests sont conçus pour encourager et capturer ce type de conversation.

On peut continuer à pousser dans sa branche à la lumière 
des discussions et des commentaires sur les commits. 
GitHub affichera vos nouveaux commits et tout commentaire supplémentaire 
que vous pourriez recevoir dans une vue unifée de la Pull Request initiale.

Une fois la Pull request accepté elle sera déployée sur l'infrastructure GitHub 
afin d'être testée. Si les tests passent correctement alors une nouvelle version, 
sera déployée. Le numéro de version dépendra alors du commentaire laissé par le 
reviewer dans la Pull Request.
