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

une fois Windows installé, commencez par installer vos pilotes, c'est le plus important pour que votre système fonctionne correctement. (si vous ne trouvez plus le pilote, le site de l'assembleur (dell, HP, acer... ) ou bien du constructeur (MSI, NVidia...) et en 3e point driverscloud vous aidera a les retrouver.

Une fois fait, généralement il y a des logiciels a (ré)installer. pour gagner du temps, et procéder a des installations automatique, plusieurs possibilités:

(si vous avez choisi d'installer Windows via l'iso windows arium, un utilitaire s'ouvrira au depart, qui contient aussi quelques logiciels)

#### ⇒ le site ninite.com

Il vous permet de choisir dans leur bibliothèque les logiciels désiré. une fois fait, vous telecharger la petite application, et il s'occupera de toute les installations, en configuration par defaut.&#x20;



#### ⇒ la commande iwr -useb https://christitus.com/win | iex

via le terminal en mode administrateur, tapez ou coller la commande " iwr -useb https://christitus.com/win | iex " et envoyez.

de la vous aurez une première fenetre vous permettant d'installer, mettre a jour tout les logiciels cité.

dans la partie tweaks et config, vous pourrez choisir d'activer ou de désactiver des fonctions Windows utile ou non, pouvant optimiser votre système. (attention a bien paramétrer, si vous ne savez pas, laissez tel quel sur l'option. personnellement je vous recommande d'utiliser ce réglage.)



## Mise a jour du système

une fois tout vos logiciels installé (avant quoiqu'onques parametrage, réouvrez le terminal en administrateur et coller cette commande: winget upgrade --all --include-unknown

cela téléchargera toutes les mises a jour du pc (Windows et éventuellement quelques logiciels).

cette opération peut être réutiliser plus tard pour mettre a jour votre systeme (une partie seulement car cette commande n'inclus pas tout les logiciels fournit par internet.



Après un dernier redémarrage en plus de ceux demandé avant, votre système Windows est prêt à être utiliser et personnalisé de vos propre paramètres et personnalisations.
