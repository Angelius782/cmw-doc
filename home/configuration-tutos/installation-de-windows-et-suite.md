---
description: avoir un windows propre, et installation facile et rapide
---

# installation de windows et suite

pour l'installation de Windows, vous avez plusieurs facons de faire.&#x20;

personnellement je recommande deux facons, une version simple (recuperer une iso prete a usage) ou une version "plus avancée" pour maitriser ce qui es fait\
\
Pour la version plus avancée, je vous recommande ce tuto a jour sur youtube, qui est tres claire, étape par étape: [https://www.youtube.com/watch?v=Gn76Z5K5CnI\&t=4s](https://www.youtube.com/watch?v=Gn76Z5K5CnI\&t=4s)\
\
Pour une version plus simple, je vous conseille la version ARIUM (actuellement en version Windows 11 11.5)

il vous faudra dans tout les cas une clé USB de 8Go minimum pouvant être formater entièrement.\
<br>

## Post installation Windows 11

une fois windows installé, commencez par installer vos pilotes, c'est le plus important pour que votre systeme fonctionne correctement. une fois fait, généralement il y a des logiciels a (ré)installer. pour gagner du temps, et proceder a des installations automatique, plusieurs possibilités:

(si vous avez choisi d'installer windows via l'iso windows arium, un utilitaire s'ouvrira au depart, qui contient aussi quelques logiciels)

#### ⇒ le site ninite.com

Il vous permet de choisir dans leur bibliotheque les logiciels désiré. une fois fait, vous telecharger la petite application, et il s'occupera de toute les installations, en configuration par defaut.&#x20;



#### ⇒ la commande iwr -useb https://christitus.com/win | iex

via le terminal en mode administrateur, tapez ou coller la commande " iwr -useb https://christitus.com/win | iex " et envoyez.

de la vous aurez une premiere fenetre vous permettant d'installer, mettre a jour tout les logiciels cité.

dans la partie tweak et config, vous pourrez choisir d'activer ou de desactiver des fonctions windows utile ou non, pouvant optimiser votre systeme. (attention a bien parametrer, si vous ne savez pas, laissez tel quel sur l'option. personnelement je vous recommande d'utiliser ce reglage.)



#### Mise a jour du systeme

une fois tout vos logiciels installé (avant quelquonque parametrage, réouvrez le terminal en administateur et coller cette commande: winget upgrade --all --include-unknown

cela telechargera toutes les mises a jour du pc (windows et eventuellement quelques logiciels).

cette operation peut etre reutiliser plus tard pour mettre a jour votre systeme (une partie seulement car cette commande n'inclus pas tout les logiciels fournit par internet.



apres un autre redemarrage en plus de ceux demandé avant, votre systeme windows est pret a etre utiliser et personnalisé de vos propre parametres.
