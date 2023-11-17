# 💸 Taxes

Les taxes et prix de maintenance sont deux choses séparées. Les taxes sont gérées par l'administration d'un village et d'une nation et les prix de maintenance sont des prix à payer par villes et nations pour que ceux-ci soient maintenus. Les taxes et prix de maintenance sont prélevés tous les jours à midi par le plugin. Il y a différents types de taxes à différents niveaux.

### Prix de maintenance <a href="#prix_de_maintenance" id="prix_de_maintenance"></a>

Le prix de maintenance est de 10฿ pour les villages et 100฿ pour les nations. Ce prix sera relevé chaque jour dans les banques de villages et nations.

Si un village ne peut pas payer son prix de maintenance :

* Le village sera abandonné.
* Tous les résidents seront expulsés.
* Les constructions resteront intactes, mais non protégées.
* Si le village appartenait à une nation, cette nation perdra ce village.

Si une nation ne peut pas payer son prix de maintenance :

* La nation sera abandonnée.
* Tous les villages appartenant à cette nation resteront intactes

### Taxes <a href="#taxes" id="taxes"></a>

Les villages et nations peuvent gérer leurs taxes selon les résidents, pour le cas d'un village ou selon les villages pour le cas d'une nation. Ces taxes seront récoltées chaque jour dans les comptes bancaires des résidents ou les banques des villages taxés.

#### Résidents taxés <a href="#residents_taxes" id="residents_taxes"></a>

Les [villages](http://laboulangerie.fandom.com/fr/wiki/Villages) peuvent imposer des taxes à leurs résidents. Pour ce faire, l'administration d'un village peut choisir de taxer ses résidents avec un prix fixe ou un pourcentage de leur propre argent avec la commande `/town toggle taxpercent`, qui basculera entre les deux modes.

Pour gérer les taxes d'un village, vous pouvez taper la commande `/town set taxes <prix>`. Cela forcera tous les résidents à payer cette taxe par jour. Le prix sera prélevé du compte bancaire de tous les résidents et alimentera la banque de ce village.

Si le mode pourcentage est activé, vous pouvez définir un prix maximum à payer avec la commande `/town set taxpercentcap <prix>`.

Vous pouvez aussi taxer les résidents de votre village en fonction du nombre de [plots](http://laboulangerie.fandom.com/fr/wiki/Chunk) que celui-ci possède dans votre village avec la commande `/town set plottax <prix>`. Par exemple, si vous mettez comme prix 10฿, un résident possédant 4 chunks payera 40฿ chaque jour.

Si un résident ne peut pas payer ces taxes, il sera expulsé du village.

#### Villages taxés <a href="#villages_taxes" id="villages_taxes"></a>

Les [nations](http://laboulangerie.fandom.com/fr/wiki/Nations) peuvent imposer des taxes à leurs villages. Pour ce faire, l'administration d'une nation peut choisir de taxes ses villages avec la commande `/n set taxes <prix>`. Ce prix sera prélevé chaque jour dans les banques de tout les villages appartenant à cette nation et alimentera la banque de cette nation.
