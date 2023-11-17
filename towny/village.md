# 🏘 Village

Les villages constituent le centre du jeu de La Boulangerie, c'est ici que les joueurs s'assemblent en communauté pour avancer ensemble. Appartenir à un village permet de participer au Rôle-Play Géopolitique, mais également de protéger vos constructions avec un système de permission très développé.

Un village peut à son tour créer ou rejoindre une [nation](http://laboulangerie.fandom.com/fr/wiki/Nations), cela permet de fédérer plusieurs villages sous une bannière commune si elles partagent des valeurs et principes proches.

_Lorsque vous débutez dans La Boulangerie, il vous est conseillé de rejoindre un village rapidement pour profiter de sa protection._

Quand vous êtes assez riche et stuffé, vous pourrez enfin créer votre ville en faisant `/t new <nom>`, la renommer en faisant `/t set name <nom>` et la détruire en faisant `/t delete`.

### Création d'un village <a href="#creation_dun_village" id="creation_dun_village"></a>

Un village peut être créé par n'importe quel joueur de La Boulangerie. Cependant, nous vous recommandons activement de commencer par rejoindre une ville, puis, une fois que vous serez assez établi et si potentiellement avec un autre joueur, de créer une nouvelle ville. Pour créer un village, il vous faut impérativement deux choses :

1. 1024฿, prix de création d'un village,
2. et un endroit ou le créer.

#### Étapes de création : <a href="#etapes_de_creation_" id="etapes_de_creation_"></a>

1. Pour lancer la création de votre village, faites `/t new`` `_`<nom>`_. Par exemple, pour créer le village « Block-village », faites `/t new`` `_`Block-village`_. Attention cependant, le nom d'un village ne doit comporter ni de caractères spéciaux (accents, diacritiques, etc) ni d'espaces (remplacez-les par des « \_ », le plugin l'affichera par la suite comme un espace même s'il est conseillé, pour la citation de votre village, d'utiliser des tirets).
2. Un message s'affichera dans le chat pour vous demander de confirmer la dépense de 1024฿ pour la création de votre village, cliquez sur \[/confirm] ou faites `/confirm` pour confirmer.
3. Un message s'affichera dans le tchat pour vous confirmer la création de votre village et vous donner des informations sur celui-ci, à noter qu'un autre message « _\[Towny] \<pseudo> a créé une nouvelle village appelée \<nom>_ » s'affiche dans le tchat pour tous les joueurs connectés. Parmi les informations du premier messages vous avez le coût d'entretien quotidien (3฿ × nombre de chunks claims ; donc 3฿ dans votre cas)
4. Pour créer une banque vous devez prendre un coffre dans un claim sur lequel vous mettez _\[town vault]_ sur la première ligne. S'il n'y a plus assez d'argent, un avertissement vous sera donné à votre connection : « Sans argent pour payé le coût d'entretien quotidien, votre village sera supprimée » et le temps restant avant le prochain paiement. La première action à faire une fois votre village créé est donc d'y déposer de l'argent ; l'argent dans la banque de votre village va servir à payer le coût d'entretien quotidien à payer le claim d'un nouveau chunk mais également à payer l'éventuelle taxe de votre nation.

### Banque de la ville <a href="#banque_de_la_ville" id="banque_de_la_ville"></a>

Les villes ont besoin d'argent pour survivre car le serveur leur emprunte 3฿ tous les jours par chunk que vous avez claims. Il est important de réapprovisionner votre ville régulièrement.

La banque est un coffre simple ou double avec un panneau sur lequel le maire a écrit \[town vault]. Il se transformera en banque. Vous pouvez en mettre deux par ville tant qu'il est dans un claim d'une ville. C'est là-dedans qu'il vous faudra mettre votre argent pour subvenir aux taxes du serveur et/ou aux taxes de nation.

### Terrains et résidents <a href="#terrains_et_residents" id="terrains_et_residents"></a>

Pour qu'une ville grandisse, il faut que des nouvelles personne la rejoigne. Le maire et ses assistants peuvent inviter de nouveaux joueurs grâce à la commande `/t add <joueur>`, le joueur devra cliquer sur le message qu'il reçoit. (Vous pouvez l'expulser en faisant `/t kick <joueur>`).

Il est conseillé de construire tous vos bâtiments dans les claims de la ville. Ces claims peuvent être créés avec la commande `/t claim`, ils coûteront 25฿. Vous ne pouvez que claim des tronçons déjà juxtaposés à d'autres de vos villes. Ainsi pour déclaim vos tronçons vous devrez faire `/t unclaim`. Cela déclaimera le chunks où vous êtes mais ne vous rendra pas votre argent dépensé juste avant. Pour claim des tronçons non-juxtaposés à ceux de votre ville, vous pouvez faire `/t claim outpost`. Cela créera un claim « avant-poste ». Vous devrez ensuite, pour continuer à claim, faire la commande `/t claim`. Les résidents de votre ville peuvent se téléporter aux avant-postes en exécutant la commande `/t outpost <numéro de l'avant-poste>`.

Les villes et villages ont plusieurs niveaux. Ces niveaux affectent le nombre de claims, le titre de la ville et le titre du maire. Il y a huit niveaux de villes :



| Titre de la ville | En anglais | Nbre de résidents | Avant-postes | Titre du maire |
| ----------------- | ---------- | ----------------- | ------------ | -------------- |
| Lieu-dit          | Settlement | 1-3               | 2            | Doyen          |
| Hameau de         | Hamlet     | 4-7               | 3            | Chef           |
| Village de        | Village    | 8-11              | 4            | Maire          |
| Bourg de          | Town       | 12-17             | 5            | Maire          |
| Ville de          | Large Town | 18-23             | 6            | Maire          |
| Commune de        | City       | 24-29             | 7            | Maire          |
| Agglomération de  | Large City | 30-34             | 8            | Maire          |
| Métropole de      | Metropolis | 35+               | 9            | Maire          |

À chaque niveau, il y a une augmentation exponentielles des claims et des avant-postes suivant le nombre de joueurs dans la ville : vous aurez 16 claims par résident. Si la ville n'a plus de claim, il y deux autres façons pour quelle en ait plus : les nations et le bonus. Les nations donnent un bonus de claim exponentiel suivant le nombre de villes à l'intérieur. Ces claims sont affichés comme « bonus » dans le tableau de bord de la ville.

### Lexique <a href="#lexique" id="lexique"></a>

_Chunk :_ Terrain de 16 ×16 blocs allant de la couche 0 à 255 ; le monde de Minecraft est composé de chunks qui se suivent.

_Claim :_ Acte de protéger un chunk.

_Plot :_ Chunk claim mis à disposition aux joueurs.

_Homeblock :_ Chunk principal de votre village ; il agit comme un centre-village et le spawn ne peut qu'être placé dans celui-ci.

_Outpost :_ Avant-postes agissant comme un homeblock à la différence que le `/t spawn` ne peut y être mis dans ce cas-là usez de la commande `/t set outpost` pour définir le spawn de votre outpost (utiliser `/t outpost` à la place).

_Townblock :_ chunk claim par un village.

_Résidents :_ joueur dans votre ville.

### Les dérivés du /town set <...> <a href="#les_derives_du_-town_set_less-than...greater-than" id="les_derives_du_-town_set_less-than...greater-than"></a>

Forme d'une commande : `/commande sous-commande`` `_`<VARIABLE OBLIGATOIRE>`_ _`(VARIABLE OPTIONELLE)`._

#### Commandes des villages <a href="#commandes_des_villages" id="commandes_des_villages"></a>

Les commandes en gras ne sont accessibles qu'à partir d'un certain rang dans votre village, voir [permission](http://laboulangerie.fandom.com/fr/wiki/Village#Permissions).

* `/town ou /t`` `_`(NOM)`_ - Affiche les informations de votre village ou du village spécifié.
  * `/t add`` `_`<PSEUDO>`_ - Invite un joueur dans votre village.
  * `/t bankhistory` - Affiche un livre avec l'historique des actions sur la banque de votre village.
  * `/t claim` - Claim un chunk.
    * `/t claim outpost` - Claim un chunk isolé de vos autres claims, créer un outpost.
  * `/t delete` - Supprime votre village.
  * `/t deposit`` `_`<MONTANT>`_ - Dépose de l'argent dans votre village.
  * `/t here` - Affiche les informations de votre village
  * `/t invite` - Affiche un récapitulatif de vos invitations reçues et envoyées.
    * `/t invite`` `_`<NOM>`_ - Invite un joueur dans votre village.
    * `/t invite -`_`<NOM>`_ - Annule l'invitation d'un joueur dans votre village.
    * `/t invite sent` - Affiche les invitations envoyées.
    * `/t invite received` - Affiche les invitations reçues.
    * `/t invite accept`` `_`<NATION>`_ - Accepte l'invitation à rejoindre une nation.
    * `/t invite deny`` `_`<NATION>`_ - Refuse l'invitation à rejoindre une nation.
  * `/t join`` `_`<NOM>`_ - Vous fait rejoindre une village si elle est ouverte.
  * `/t kick`` `_`<PSEUDO>`_ - Exclu un joueur de votre village.
  * `/t leave` - Vous fait quitter votre village (si vous êtes maire, vous devez donner votre place avant).
  * `/t list` - Liste les villages du serveur triés par le nombre de résidents.
    * `/t list by ...` - Liste les villages du serveur triés par ...
      * `balance` - l'argent en banque.
      * `name` - l'ordre alphabétique.
      * `online` - le nombre de joueur en ligne.
      * `open` - son ouverture.
      * `public` - l'accessibilité de son spawn.
      * `residents` - le nombre de résidents.
      * `townblocks` - le nombre chunks claims.
  * `/t mayor` - Liste les commandes inaccessibles aux résidents sans rank.
  * `/t merge`` `_`<NOM>`_ - Lance une procédure de fusion avec un autre village.
  * `/t new`` `_`<NOM>`_ - Créer un nouveau village.
  * `/t online`` `_`(NOM)`_ - Affiche les résidents en ligne de votre village ou du village spécifié.
  * `/t outlaw` - Affiche les commandes liés aux hors-la-loi.
    * `/t outlaw add`` `_`<PSEUDO>`_ - Ajoute un joueur dans votre liste d'hors-la-loi.
    * `/t outlaw remove`` `_`<PSEUDO>`_ - Retire un joueur de votre liste d'hors-la-loi.
  * `/t outlawlist`` `_`(NOM)`_ - Affiche la liste d'hors-la-loi de votre village ou du village spécifié.
  * `/t outpost`` `_`(NUMERO)`_ - Vous téléporte au premier avant-poste de votre village ou à l'avant-poste du numéro spécifié.
    * `/t outpost list` - Affiche la liste des avant-postes de votre village.
  * `/t plots` - Affiche un récapitulatif des plots de votre village.
  * `/t rank` - Affiche les commandes liés aux rangs.
    * `/t rank add`` `_`<PSEUDO> <RANK>`_ - Ajoute le rang spécifié au joueur spécifié.
    * `/t rank remove`` `_`<PSEUDO> <RANK>`_ - Supprime le rang spécifié au joueur spécifié.
  * `/t ranklist` - Affiche un récapitulatif des rangs de votre village.
  * `/t reclaim` - Récupère votre village si il est tombé en ruine.
  * `/t reslist` - Affiche un récapitulatif des résidents de votre village ou du village spécifié.
  * `/t say`` `_`<MESSAGE>`_ - Affiche un message aux résidents de votre village.
  * `/t set` - Affiche les commandes liée au /t set.
    * `/t set board`` `_`<TEXTE>`_ - Modifie la description de votre village.
    * `/t set embassyprice`` `_`<MONTANT>`_ - Modifie le prix par défaut des ambassades.
    * `/t set embassytax`` `_`<MONTANT>`_ - Modifie la taxe journalière des ambassades.
    * `/t set homeblock` - Déplace le centre-ville sur le chunk ou vous êtes.
    * `/t set jail` - Déplace le spawn de la cellule.
    * `/t set mayor`` `_`<PSEUDO>`_ - Donne le rôle de maire au joueur spécifié.
    * `/t set name`` `_`<TEXTE>`_ - Modifie le nom du village.
    * `/t set outpost` - Transforme le chunk ou vous êtes en outpost.
    * `/t set perm` - Modifie les permissions par défaut de votre village, voir [permission](http://laboulangerie.fandom.com/fr/wiki/Village#Permissions).
    * `/t set plotprice`` `_`<MONTANT>`_ - Modifie le prix par défaut des plots.
    * `/t set plottax`` `_`<MONTANT>`_ - Modifie la taxe journalière des propriétaires.
    * `/t set shopprice`` `_`<MONTANT>`_ - Modifie le prix par défaut d'un commerce.
    * `/t set shoptax`` `_`<MONTANT>`_ - Modifie la taxe journalière des commerçants.
    * `/t set spawn` - Déplace le spawn du village ou vous êtes (ne fonctionne que sur le homeblock).
    * `/t set spawncost`` `_`<MONTANT>`_ - Modifie le coût du spawn de votre village.
    * `/t set surname`` `_`<PSEUDO> <TEXTE>`_ - Modifie le surnom du résident spécifié.
    * `/t set tag`` `_`<TEXTE>`_ - Modifie le tag de votre village.
    * `/t set taxes`` `_`<MONTANT>`_ - Modifie la taxe journalière des résidents.
    * `/t set taxpercentcap`` `_`<MONTANT>`_ - Modifie le montant maximum de taxe journalière si elle est calculée en pourcentage.
    * `/t set title`` `_`<PSEUDO> <TEXTE>`_ - Modifie le titre d'un de vos résident.
  * `/t spawn`` `_`(NOM)`_ - Vous téléporte au spawn de votre village ou du village spécifié.
  * `/t toggle` - Affiche les commandes liées au /t toggle.
    * `/t toggle explosion` - Active/Désactive les explosions dans votre village.
    * `/t toggle fire` - Active/Désactive le feu dans votre village.
    * `/t toggle jail`` `_`<NUMERO> <PSEUDO> (NOMBREJOUR)`_ - Emprisonne le joueur spécifié dans la cellule spécifiée à vie ou le nombre de jours spécifié (jour IRL).
    * `/t toggle mobs` - Active/Désactive le spawn de mobs dans votre village.
    * `/t toggle neutral` - Active/Désactive le statut de paix de votre village (délai de 5 jours, annulable).
    * `/t toggle open` - Active/Désactive l'ouverture de votre village.
    * `/t toggle peaceful` - Active/Désactive le statut de paix de votre village (délai de 5 jours, annulable).
    * `/t toggle public` - Active/Désactive l'accès à tous les joueurs du spawn de votre village.
    * `/t toggle pvp` - Active/Désactive le PVP dans votre village.
    * `/t toggle taxpercent` - Active/Désactive le calcul des taxes journalières en pourcent.
  * `/t unclaim` - Unclaim le chunk sur lequel vous êtes.
  * `/t withdraw`` `_`<MONTANT>`_ - Retire de l'argent de votre village.

#### Commandes des plots <a href="#commandes_des_plots" id="commandes_des_plots"></a>

Les commandes en gras ne sont accessibles qu'à partir d'un certain rang dans votre village et les commandes soulignées ne sont accessibles qu'au propriétaire du plot, voir [permission](http://laboulangerie.fandom.com/fr/wiki/Permission).

* `/plot`
  * `/plot claim` - Achète la plot si elle est en vente.
  * `/plot clear` - Retire les panneaux du plot.
  * `/plot evict` - Retire la propriété du plot.
  * `/plot forsale ou fs`` `_`(MONTANT)`_ - Met en la plot en vente pour le montant par défaut ou pour le montant spécifié.
  * `/plot group` - Affiche les commandes liées aux groupes de plots.
    * `/plot group add`` `_`<NOMGROUPE>`_ - Ajoute la plot au groupe spécifié.
    * `/plot group remove` - Retire la plot de son groupe.
    * `/plot group rename`` `_`<NOMGROUPE>`_ - Renomme le groupe du plot.
    * `/plot group set ...` - Pareil que /plot set à l'échelle du groupe.
    * `/plot group toggle ...` - Pareil que /plot toggle à l'échelle du groupe.
    * `/plot group forsale ou fs`` `_`(MONTANT)`_ - Pareil que /plot forsale ou fs à l'échelle du groupe.
    * `/plot group notforsale ou nfs` - Pareil que /plot notforsale ou nfs à l'échelle du groupe.
  * `/plot notforsale ou nfs` - Retire la plot de la vente.
  * _/plot perm_ - Affiche les permission du plot.
    * /plot perm hud - Active un HUD qui affiche les permission du plot.
  * _/plot set_ - Affiche les commandes liées au /plot set (voir [gestion des plots](http://laboulangerie.fandom.com/fr/wiki/Village#Plots) pour plus d'information sur les spécialités).
    * _/plot set arena_ - Transforme la plot en arène.
    * _/plot set bank_ - Transforme la plot en banque.
    * _/plot set embassy_ - Transforme la plot en ambassade.
    * _/plot set farm_ - Transforme la plot en ferme.
    * _/plot set inn_ - Transforme la plot en auberge.
    * _/plot set jail_ - Transforme la plot en cellule.
    * _/plot set name `<TEXTE>`_ - Modifie le nom du plot.
    * _/plot set outpost_ - Transforme la plot en avant-poste.
    * _/plot set perm_ - Modifie les permissions du plot, voir [permission](http://laboulangerie.fandom.com/fr/wiki/Village#Permissions).
    * _/plot set reset_ - Retire la spécialité du plot.
    * _/plot set shop_ - Transforme la plot en commerce.
    * _/plot set wilds_ - Transforme la plot en terrain sauvage.
  * _/plot toggle_
    * _/plot toggle explosion_ - Active/Désactive les explosions dans la parcelle.
    * _/plot toggle fire_ - Active/Désactive le feu dans la parcelle.
    * _/plot toggle mobs_ - Active/Désactive le spawn de mobs dans la parcelle.
    * _/plot toggle pvp_ - Active/Désactive le pvp dans la parcelle.
  * _/plot unclaim_ - Relâche la propriété de la parcelle.
