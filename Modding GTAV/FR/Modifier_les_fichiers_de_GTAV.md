# OPENIV
Tout d'abord, afin de pouvoir modifier un fichier interne a GTAV, 
il vous faut un logiciel du nom de [OpenIV](https://openiv.com/)(site officiel), 
si vous n'aimez pas les sites russe, vous pouvez aussi le télécharger [ici](https://fr.gta5-mods.com/tools/openiv).

Par la suite, afin de ne pas casser le jeu entier, on va devoir créer un sauvegarde.
Dans la racine du jeu, créer un dossier "*mods*" et faites une copie de update dans ce dossier.

Un addon est un objet /pack d'objet qui vient s'ajouter en plus de ceux du jeu de base. Il faut donc déclarer au jeu que cet/ces objet(s) existe(nt).
Pour ça on modifie le dlclist.xml.
Ensuite il faut demander au jeu de charger cet/ces objet(s) sinon le jeu ne va pas comprendre et va crash.
On utilise un gameconfig.xml. 
Aujourd'hui, on connais qu'un seul gameconfig qui fasse le taffe : [Game Config](https://www.gta5-mods.com/misc/gta-5-gameconfig-300-cars)
Je vous conseil de prendre '0.5x traffic'
Puis, placer le dans mods > update > update.rpf > common > data *(via OpenIV)* (il faut être en edit mode)

Mais il manque un dernier truc : si on charge plus de fichiers, il faut un plus gros cache. On prend donc un [heapadjuster](https://www.gta5-mods.com/tools/heapadjuster). 
On met le *heapadjuster* dans la racine du jeu

Ensuite, pour ajouter des véhicules... vous passerez principalement par openIV mods > update > ...
