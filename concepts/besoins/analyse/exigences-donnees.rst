Les données : incréments
========================


I1 - LesSpectacles
------------------

* (I1_01) Un spectacle est identifiée par un numéro et on connaît son nom, son prix debase, sa durée, le public cible (1-5 ans, jeune public, tout public ou adultes) et le type de spectacle (opéra, drame, humoristique, musical ou cirque). 
* (I1_02) Sur les spectacles du type opéra, on indique s’il intègre une orchestre. 
* (I1_03) Sur les spectacles du type humoristique on indique s’il s’agit d’un OneWo-men(Men)Show.
* (I1_04) Un spectacle fait généralement l’objet de plusieurs représentations proposées à des moments différents. 
* (I1_05) Une représentation débute à un moment donné exprimé à la granularité de la minute (par exemple 28/11/2007 20H30).


I2 - LesPlaces
--------------

* (I2_01) La seule salle du thêatre est partitionnée en zones numérotées, regroupant chacune un ensemble de places.
* (I2_02) Une place a un numéro et se situe dans un rang (ce rang est unique dans la salle).
* (I2_03) Une zone est associée à une seule catégorie tarifaire (orchestre, balcon, poulailler, etc).
* (I2_04) Une  catégorie  peut  être  associé  à  plusieurs  zones.
* (I2_05) Toutes  les  places  de  la  même  zone  sont dans la même catégorie.
* (I2_06) Un taux entre 0.5 et 1 par rapport au prix de base est associé à chaque catégorie (ex. 0.6 pour le poulailler, 0.75 pour l’orchestre et 1 pour le balcon).
* (I2_07) Ce taux est fixé pour l’ensemble des spectacles.


I3 - LesTickets
---------------

* (I3_01)  Chaque  place  vendue  par  représentation  fait  l’objet  de  l’émission  d’un  ticket identifié  par  un  numéro  de  série  et  estampillé  par  la  date  au  moment  de  l’emission  (instant  à  la granularité  de  la  seconde).
* (I3_02)  Un  achat  concerne  un  ou  plusieurs  places  (i.e.,  plusieurs  tickets)  se traduisant par la création d’un dossier achat (identifié par un numéro) auquel est associé le prix global des places.
* (I3_03) Un suivi du nombre de places disponibles pour chaque représentation programmée pour un spectacle est envisagé.


I4 - LesRéductions
------------------

* (I4_01) Pour certaines représentations, le prix des places fait l’objet d’une promo-tion.
* (I4_02) Ainsi, à chaque représentation est associé un taux de promotion (1 : pas de promotion, 0,5 :promotion de 50%, etc.).
* (I4_03) Les personnes qui achètent des places peuvent être des spectateurs ordinaires ou des adhérents et bénéficier d’un tarif réduit.
* (I4_04) Certaines personnes (étudiants, handicapés et séniors) bénéficient aussi d’une réduction.
* (I4_05) Un taux de réduction est associé a chacun de ces types(1 pour le tarif sans réduction, 0.8 pour le tarif réduit de 20%, etc.).
* (I4_06) Le cas échéant, la réduction vient s’ajouter à la promotion associée à la représentation et éventuellement à d’autres promotions(ex. un adhérent avec 20% qui est aussi étudiant avec 10% de réduction, il aura 30% de réduction).


I5 - LesUtilisateurs
--------------------

* (I5_01) L’application doit être mise en ligne afin de permettre à des utilisateurs identifiés  d’acheter  des  places.
* (I5_02) Les  utilisateurs  sont  identifiés  par  leur login.
* (I5_03) Ils  sont  décrits par  leur  nom,  leur  prénom,  leur  adresse électronique  et  leur  mot  de  passe.
* (I5_04) Un  utilisateur  peut réserver des places avant de procéder à leur achat.
* (I5_05) Une place réservée ne peut être achetée que par l’utilisateur qui a effectué la réservation.
* (I5_06) Une réservation pourrait être ensuite rendue disponible par le client qui l’a réservée.

I6 - LesConfigurations
----------------------

* (I6_01) Selon les spectacles, certaines places sont retirées de la vente : en effet, dans certaines mises en scène, une partie des tribunes est occupée pour toutes les représentations d’un même spectacle.