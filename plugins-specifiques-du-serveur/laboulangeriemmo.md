# 🆙 LaBoulangerieMmo

LaBoulangerieMmo est un plugin Paper développé par nos soins (merci à TheHunter, Grooble\_ et Pikachuz3).

Le plugin propose différents métiers appelés talents qui donnent accès à différentes habilités au fur et à mesure que l'on monte de niveau dans un talent. Vous n'avez pas à choisir un seul talent vous avez accès à tous, à vous de choisir le quel vous voulez améliorer en ce moment. Le niveau maximum pour chaque talent est de 100.

#### Monter de niveau <a href="#monter_de_niveau" id="monter_de_niveau"></a>

Il y a plusieurs moyens pour augmenter de niveau selon le talent, vous pouvez gagner de l'xp en cassant des blocs, en fabriquant des objets (table de craft), en fabriquant des objets pour la première fois ou en tuant des monstres. Afin de ne pas spammer votre chat, vous recevez un total de l'xp gagné dans chaque talent quand vous arrêtez d'en gagner pendant un certain temps.

À chaque fois que vous augmentez de niveau vous recevez en argent, 1,25% de l'xp que vous avez récolté depuis le niveau précédent.

Vous pouvez voir votre progression grâce à la commande `/stats`

#### Talents <a href="#talents" id="talents"></a>

**Mineur**

**Habilités**

| Description                                                                           | Tiers I                                                  | Tiers II                                                  | Tiers III                                                       | Cooldown   | Déclenchement                                             |
| ------------------------------------------------------------------------------------- | -------------------------------------------------------- | --------------------------------------------------------- | --------------------------------------------------------------- | ---------- | --------------------------------------------------------- |
| <p>Brossage minutieux:</p><p>Multiplie l'xp vanilla gagné en cassant des minerais</p> | <p>Niveau: 5</p><p>Multiplicateur 1.25</p>               | <p>Niveau: 25</p><p>Multiplicateur 2</p>                  | <p>Niveau: 55</p><p>Multiplicateur 5</p>                        | Permanent  | Casser un minerai                                         |
| <p>Pioche aiguisée:</p><p>Donne un effet de haste</p>                                 | <p>Niveau: 15</p><p>Haste II</p><p>Durée 20 secondes</p> | <p>Niveau: 45</p><p>Haste III</p><p>Durée 1 minute</p>    | <p>Niveau 75</p><p>Haste IV</p><p>Durée 5 minutes</p>           | 15 minutes | Left + Right + Left                                       |
| <p>Champ magnétique:</p><p>Permet de voir les minerais à travers les murs</p>         | <p>Niveau 35</p><p>Rayon: 5 blocs</p><p>Sans couleur</p> | <p>Niveau 65</p><p>Rayon: 10 blocs</p><p>Sans couleur</p> | <p>Niveau 95</p><p>Rayon: 20 blocs</p><p>En couleurs</p>        | 30 minutes | Shift+Clique droit dans le vide avec une boussole en main |
| <p>Fonte instantanée:</p><p>Cuit instantanément le contenu d'un haut-fourneau</p>     | Niveau 85                                                | 1 heure                                                   | Clique gauche sur un haut-fourneau avec un charbon dans la main |            |                                                           |

**Expérience**

Il y a différentes manières d'augmenter don niveau en temps que mineur mais la principale est en cassant des blocs, plus la valeur du bloc est haute plus la récompense sera haute.

**Farmer**

**Habilités**

| Description                                                                                                                                                                                                                                                                                                                                                                              | Tiers I                                                                         | Tiers II                                                          | Tiers III                                                      | Cooldown   | Déclenchement                                                                                                                                                                             |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | ----------------------------------------------------------------- | -------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Jeunes Pousses:</p><p>Vous avez la possibilité d'automatiquement replanter quand vous cassez une pousse arrivée à maturité</p>                                                                                                                                                                                                                                                        | <p>Niveau: 5</p><p>10% de chance de replanter</p>                               | <p>Niveau: 30</p><p>40% de chance de replanter</p>                | <p>Niveau: 70</p><p>100% de chance de replanter</p>            | Passif     | Casser une pousse arrivée à maturité                                                                                                                                                      |
| <p>Engrais Naturel:</p><p>Applique de la bonemeal sur les plantes autour de vous.</p>                                                                                                                                                                                                                                                                                                    | <p>Niveau: 15</p><p>rayon de 5 blocks avec 1 intensité</p>                      | <p>Niveau: 45</p><p>rayon de 10 blocks avec 2 d'intensité</p>     | <p>Niveau: 100</p><p>rayon de 30 blocks avec 3 d'intensité</p> | 15 minutes | Sneak + Click droit avec bonemeal dans la main                                                                                                                                            |
| <p>Jumeaux Permanents:</p><p>Vou avez une probabilité d'avoir des jumeaux en faisant se reproduire des animaux</p>                                                                                                                                                                                                                                                                       | <p>Niveau: 20</p><p>10% de chance d'avoir des jumeaux</p>                       | <p>Niveau: 55</p><p>40% de chance d'avoir des jumeaux</p>         | <p>Niveau: 80</p><p>100% de chance d'avoir des jumeaux</p>     | Passif     | Se faire se reproduire des animaux                                                                                                                                                        |
| <p>Pain Apétissant:</p><p>Quand vou tenez un pain dans la main, les entités passives vous suivent</p><p>(Axolotl, Bee, Cat, ChestedHorse, Chicken, Cow, Donkey, Fox, Frog, Goat, Hoglin, Horse, Llama, Mule, MushroomCow, Ocelot, Panda, Parrot, Pig, PolarBear, Rabbit, Sheep, SkeletonHorse, Strider, Tameable, TraderLlama, Turtle, Villager, WanderingTrader, Wolf, ZombieHorse)</p> | <p>Niveau: 5</p><p>Attire seulement les vaches, moutons, cochons et poulets</p> | <p>Niveau: 60</p><p>Attire tout les entitées passives listées</p> |                                                                | Passif     | <p>Tenir un pain dans sa main, l'entité ira a votre position</p><p>Pour encore la déplacer, changez de slot votre hotbar a un autre item, et après revenez sur le slot hotbar du pain</p> |

**Hunter**

**Habilités**

| Description                                                                                                                               | Tiers I                                                               | Tiers II                                                          | Tiers III                                                                  | Cooldown   | Déclenchement                                          |
| ----------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- | ----------------------------------------------------------------- | -------------------------------------------------------------------------- | ---------- | ------------------------------------------------------ |
| <p>Bélier/Esquive:</p><p>Vous propulse en avant et inflige des dégâts et du knockback aux entités touchées.</p>                           | Niveau: 25                                                            | <p>Niveau: 60</p><p>Augmente le knockback légèrement</p>          | <p>Niveau: 95</p><p>Augmente les dégâtes légèrement</p>                    | 5 minutes  | Gauche + Gauche + Droite                               |
| <p>Flèche Enflammées:</p><p>Néçessite un arc enchanté avec Flame.</p><p>La prochaine flèche que vous tirerez provoquera une explosion</p> | <p>Niveau: 15</p><p>Met en feu les blocks que la flèche a touché.</p> | <p>Niveau: 30</p><p>Provoque une explosion enflammée.</p>         | <p>Niveau: 70</p><p>Provoque une explosion moyenne enflammée.</p>          | 15 minutes | Droite + Gauche + Gauche                               |
| <p>Mise en Bouteille:</p><p>Permet de mettre de l'exp en bouteille. Néçessite des bouteilles vides dans la main.</p>                      | <p>Niveau: 5</p><p>100 pts d'xp dans la bouteille</p>                 | <p>Niveau: 30</p><p>200 pts d'xp dans la bouteille</p>            | <p>Niveau: 40</p><p>300 pts d'xp dans la bouteille</p>                     | 0 secondes | Sneak + clique droit avec bouteilles vide dans sa main |
| <p>Camouflage:</p><p>Vous devenez invisible.</p><p>Vous redeviendrez visible si vous prenez des dégâts.</p>                               | <p>Niveau: 50</p><p>Invisible sans particules pendant 2 minutes.</p>  | <p>Niveau: 85</p><p>Armure invisible aussi pendant 5 minutes.</p> | <p>Niveau: 100</p><p>Traces de pas enlevées aussi, pendant 10 minutes.</p> | 25 minutes | Gauche + Droite + Droite                               |

\


**Bûcheron**

**Habilités**

| Description                                                                                                                                                                    | Tiers I                                                                       | Tiers II                                                  | Tiers III                                                              | Cooldown  | Déclenchement                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- | --------------------------------------------------------- | ---------------------------------------------------------------------- | --------- | --------------------------------------- |
| <p>Strip:</p><p>Enlève l'écore de toutes les bûches de l'arbre visé.</p>                                                                                                       | <p>Niveau: 50:</p><p>Enlève l'écore de toutes les bûches de l'arbre visé.</p> | 10 minutes                                                | Gauche + Gache + Droite                                                |           |                                         |
| <p>Timber:</p><p>Casse automatiquement tout l'abre relié à cette bûche.</p><p>Ne marche que sur les arbres naturels</p>                                                        | <p>Niveau: 35</p><p>Rayon de propagation de 3 blocks</p>                      | <p>Niveau: 65</p><p>Rayon de propagation de 8 blocks.</p> | <p>Niveau: 95</p><p>Rayon de propagation de 15 blocks.</p>             | 5 minutes | Casser une bûche d'un arbre naturel     |
| <p>Chance du bûcheron:</p><p>Vous avez plus de chance d'obtenir des pommes en cassant des feuillages, et vous avez une chance d'obtenir 2 bûches en minant une seule bûche</p> | <p>Niveau: 5</p><p>10% de chance.</p>                                         | <p>Niveau: 40</p><p>40% de chance.</p>                    | <p>Niveau: 75</p><p>80% de chance.</p>                                 | Passif    | Casser un feuillage d'oak ou une bûche. |
| <p>Haricot Magique:</p><p>Vous pouvez faire pousser un quadruple arbre avec une seule pousse au lieu de 4.</p>                                                                 | <p>Niveau: 10</p><p>Utilisable sur jungle, spruce et dark oak.</p>            | 15 minutes                                                | Droite + Droite + Gauche sur une pousse de l'un des arbres mentionnés. |           |                                         |