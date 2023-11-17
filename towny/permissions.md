# 🤝 Permissions

Les terrains ou _plots_ sont chaque _chunk_ de votre ville et peuvent être modifiés grâce à la commande `/plot <...>`. Ils peuvent être visionnés en appuyant sur les touches F3 et G en même temps. La plus part des sections sont aussi applicables au niveau de la ville grâce à la commande `/t <...>`.

### Permissions <a href="#permissions" id="permissions"></a>

Les permission sont les accès donnés à un joueur dans un _chunk_ ou dans une ville. Pour voir les permission que les joueurs ont dans un _chunk_ il faut faire `/plot perm hud` un cadre apparaitra à droite avec toutes les spécificités du chunk. Il peut aussi être vu avec la sous-commade _perm_ qui doit être précèdé par /t ou /plot. -Build (construction) : permet aux joueurs de construire ;

\-Destroy (destruction) : permet aux joueurs de détruire ;

\-Switch : permet aux joueurs d'ouvrir les portes, les coffres, d'actionner les levier, boutons, plaques de pression, etc ;

\-Item : permet aux joueurs d'utiliser des perles de l'ender, les seaux, feux d'artifice (au sol), etc.

### Rôles <a href="#roles" id="roles"></a>

\-r: (_resident_) résidents de votre ville

\-n: (_nation_) membres de la nation

\-a: (_ally_) alliés de la nation

\-o: (_outsider_) tout le monde

### Exemple: <a href="#exemple" id="exemple"></a>

* Build: -n--
* Destroy:----

Ici le build est uniquement réservé aux membres de la nation, personne ne peux détruire, tout le monde peux ouvrir les coffres et les portes, les membre du villages et les alliés de la nation peuvent utiliser des perles de l'ender.

Pour changer les permission il y a 2 commandes

1. `/plot set perm <catégorie> on/off` (donne accès à tout le monde à cette catégorie dans le _chunk_)
2. `/plot set perm <nom complet de la lettre> <catégorie> on/off` (donne accès aux membres de la lettre la catégorie dans le _chunk_)

* remarque si vous voulez mettre la permission dans toute la ville, il suffit de changer le `/plot` par un `/t`.\


### Modification <a href="#modification" id="modification"></a>

Les modifications permettent, par leur nom, de modifier les propriétés d'un terrains ou de la ville. Ils sont changeables par la commande /`plot toggle <..>[on/off]`. Cela peut marcher au niveau de la ville en remplaçant le `/plot` par `/t`.

* « pvp » active ou désactive le PvP ;
* « mob » active ou désactive l'apparition des mobs ;
* « fire » active ou désactive la propagation du feu. Remarque : la propagation du feu n'est pas activée sur le serveur ;
* « explosion » active ou désactive les explosions.\


### Type de terrains (plot) <a href="#type_de_terrains_-plot" id="type_de_terrains_-plot"></a>

Un terrain peut avoir un status spécial définissant le type de celui-ci en permettant de modifier les permissions et les taxes. Vous pouvez changer le type de terrains en faisant /plot set \<type>. Vous pouvez restaurer leur fonction normale en faisant /plot set reset.

* « Embassy » : mets le terrain en type ambassade. Permets que quand un terrain est à vendre et est en ambassade, tout le monde peut l'acheter. Même ceux qui ne résident pas dans la ville. Permet aux maires de pouvoir mettre des taxes spéciales pour ces terrains à travers la commande /t set embassytax \<montant>
* « Shop » : mets le terrain en type magasin. Ce type permet aux maires de pouvoir mettre des taxes spéciales pour ces terrains à travers la commande /t set shoptax \<montant>.

### Attribution de terrains (plots) <a href="#attribution_de_terrains_-plots" id="attribution_de_terrains_-plots"></a>

\
Cette partie est plus difficile mais permet une meilleure organisation des terrains dans votre ville. Cette attribution permettra à la personne qui a obtenu le terrain de pouvoir modifier à leur guise les permissions vu dans les sections ci-dessus.

\
Vous pouvez attribuer un terrain (plot) à un joueur en faisant la commande `/plot forsale <prix>`, ceci mettra le terrain en vente pour n'importe qui dans la ville, au prix que vous avez mis. `/plot notforsale` enlèvera la mise en vente du terrain. Ainsi n'importe qui de la ville pourra acheter ce terrain avec la commande `/plot claim`.

Aussi vous pouvez définir des prix minimums pour certains plots comme les ambassades et les magasins grâce à la commande `/t set shopprice <prix> et /t set embassyprice <prix>`.

Un propriétaire peut à tout moment résilier son accès au terrain grâce à la commande `/plot unclaim`. Le maire peut faire pareil mais pour n'importe quel terrain avec la commande `/plot evict`.

### Groupes <a href="#groupes" id="groupes"></a>

Les groupes sont un moyen de regrouper plusieurs terrains sous une seule tutelle. Ils fonctionnent de la même façon que les permissions de terrains.

Vous pouvez créer un groupe grâce à la commande `/plot group add <nom>`. Ceci ajoutera le terrain où vous êtes dans le groupe. Pour enlever le terrain où vous êtes d'un groupe, faites `/plot group remove`. Un groupe qui ne contient aucun terrain sera automatiquement supprimé et quand un terrain est ajouté à un groupe n'existant pas, le groupe sera créé automatiquement.

Ainsi les commandes sont les mêmes que les plots :

* `/plot group toggle <...>` permet de changer les modifications du terrain tel que l'apparition des mobs, le feu, le PvP dans tout le groupe.
* `/plot group forsale <prix>` permet de vendre tout le groupe à un joueur.
* `/plot group set <...>` permet de modifier le type du groupe (ambassade, auberge, etc), le nom et modifier les permissions du groupe le nom.
