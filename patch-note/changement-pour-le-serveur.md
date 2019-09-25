---
description: >-
  Ce texte n'est pas complet, ni contractuel. Et le staff LakoyaRP se réserve le
  droit d'apporter toute modification à ce document quand il le souhaite, et
  sans avertissement.
---

# Changement pour le serveur

## 📌 Organisation

Afin de faire revivre le serveur Lakoya, plusieurs choix ont été pris dans le but de redorer l'image de LakoyaRP. En effet pour le moment, elle se limite à un fantastique serveur, mais ruiné par les lags et l'abscence des administrateurs

#### Candidature

Désormais, le processus de candidature sera totalement changé, des modérateurs entiérement dédiés à cette tâche seront recrutés dans le but d'accélerer le recrutement de joueurs. Ces modérateurs "spéciaux" auront donc la possibilité d'accepter ou de refuser des candidatures suivant des critères précis définis par l'administration actuel de LakoyaRP. Ils pourront aussi faire passer les oraux qui ne sont que de simples étapes de vérification avec le joueur. 

Ces modérateurs suivront une formation initiale leur présentant le système actuellement utilisé par LakoyaRP. Ensuite, les critères leurs seront présentés. Dernièrement, ils feront passer des oraux sous la surveillance d'un staff LakoyaRP. Après cette période probatoire, les modérateurs candidature pourront parfaitement remplir leur tâche en toute autonomie. Un contrôle régulier sera fait par le staff sans les oppresser. Si le travail est correctement fait, un passage à l'échelon supplémentaire pourra être envisagé.

#### Rôles du Discord

Comme vous avez pu le voir, nous avons modifié les rôles sur le Discord. Certains ont été supprimés, d'autres modifiés, et certains rajoutés. On espère donc qu'en faisant cela, une clarification pour les joueurs sera de mise. Et qu'il sera plus facilement possible de contacter le bon staff qui saura répondre à la demande. Cela évité les nombreuses redirections qui sont faites quand un joueur essaye de contacter un staff.

#### Staff

Une mauvaise organisation s'est faite au sein du staff LakoyaRP. En effet, nous sommes désorganisés sur une multitude de points qui font que nous avons beaucoup de difficultés à analyser des logs, résoudre des conflits, ainsi que transmettre des idées identiques aux joueurs.

Pour remédier à cela, nous avons crée un trello \(panneau sous forme de tuile utilisé par les entreprises dans le but de clarifier leur roadmap de développement\) qui nous permet d'avoir d'une façon claire ce qui nous reste à développer, les bugs à résoudre et ce qui peut être ajouté au serveur.

Secondement, nous allons bientôt utiliser un nouveau système de warn et de remarque. Il sera totalement transparent pour vous, et seul le staff y aura accès. Il nous permettra d'avoir un meilleur suivi des joueurs dans le but d'améliorer la résolution de conflit.

Aussi, nous aimerions fortement simplifier la gestion de notre backend. En effet, nous avons souvent plusieurs développeurs qui travaillent sur des projets en parralèle, mais nous avons beaucoup de mal à communiquer sur cela. Nous allons donc essayer d'instaurer le logiciel de gestion GIT qui permet d'avoir du versionning ainsi qu'une synchronisation des différents travaux réalisés.

Dernièrement, nous comptons clarifier le travail des différents membres du staff afin de pouvoir simplifier la prise de contact avec un staff.

#### Candidature Staff

Pour le moment, nous n'avons pas encore répondu car nous ne savons pas encore comment accueillir ce flux de nouvelles personnes. Si vous en avez fait une, mais que vous n'avez toujours pas de réponse, ne vous inquiétez, elle n'est pas refusée.

#### Dons

Comme vous le savez, LakoyaRP a besoin de dons. L'hébergeur nous coûte cher \(20.62€ par mois\), et nous avons de plus en plus de difficultés à financer le serveur. Malgré plusieurs promesses de don, nous en avons reçu qu'une de 7€. Nous remercions complétement ce contributeur, mais nous ne pouvons pas survir avec qu'un seul don. Nous faisons une nouvelle fois appel à votre générosité pour permettre à Lakoya de survivre. 

Nous avons aussi envisagé d'offrir des services contre de l'argent à l'instar d'autres serveurs. Cette solution est envisageable même si elle ne serait pas tout de suite disponible : hébergement de serveurs Unturned, création de bots, modélisation, service, etc.

#### Github

Cela fait près d'un mois que nous avons crée un GitHub. Nous ne pensons pas que beaucoup de personnes sont au courant, ni savent ce que c'est. GitHub est une plateforme dédiée aux développeurs qui permet d'utiliser GIT cité plus haut, mais aussi fournir une plateforme Open Source. En effet, malgré l'utilisation importante de système exclusif dédié à Lakoya, nous aspirons à publier sous Open Source, certains de nos programmes afin de faire avancer la communauté Unturned FR.

#### Référencement

Nous faisons tout pour qu'un maximum de joueurs soit sur le serveur. Nous continuons le travail de référencement du site sur Google, nous essayons de le placer au plus haut sur les plateformes de Top. Et nous allons bientôt utiliser Youtube pour avoir toujours plus de joueurs !

## 📌 Serveur

#### Lags

Nous avons remarqué que les lags sur le serveur se font de plus en plus ressentir au point où le serveur en devient injouable. Les images par seconde sont divisées par 4, et les joueurs se téléportent en permanence, aucune action Rp n'est possible dans ces conditions

Malheuresement, ces lags sont totalement involontaires de notre part, et les enlever est un travail très dur. Ils ne viennent pas de notre hébergeur "RoxServers" car après analyse des logs d'utilisation du CPU et de la RAM, nous n'avons observé aucune modification suspecte.

Pourtant, des téléportations \(rollback\) ont lieu. Le problème vient donc du côté "client" \(le jeu Unturned\) qui entraîne d'importante chute de FPS, mais aussi du côté serveur avec une mauvaise synchronisation de la position du joueur entre le client et le serveur.

Nous suspectons donc que les nombreuses barricades et structures entraînent la présence de ces lags. C'est un problème connu, et qui est causé par la mauvaise optimisation du jeu. 

Nous allons donc essayer de limiter un maximum la pose de ces barricades et structures. Nous ne pouvons enlever toutes les structures du serveur, puis rembourser les joueurs un par un car cela demanderait un important travail de modération que nous ne sommes pas capables d'assurer. Nous comptons donc, avec l'aide de l'équipe de modération, faire du cas par cas pour réduire ces structures. Secondement, nous allons renforcer la répréhension du freebuild sur les véhicules. Unturned est un des seuls jeux où l'on peut découvrir des véhicules qui possèdent plus d'armoires que de carrosserie .

Les nombreux lockers posés dans les maisons sont là car les stockages sur Unturned sont très limités, et laisse peu de place au rangement d'items. Nous allons donc créer de nouveaux storages plus cher, mais qui contiennent plus d'espaces ce qui permettra de réduire une grande partie des structures superflues.

Nous comptons, par ailleurs, optimiser les bâtiments qui sont présents sur le serveur. Les bâtiments tels que le McDonald, la banque de Nyasa, ou le musée d'Astria vont soit être abandonné, soit être complétement remodélisé à l'aide de logiciel tel que Blender au lieu d'utiliser l'éditeur qui est une usine à gaz dans la conception de bâtiments crées avec la réutilisation d'assets.

Dernièrement, nous avons désormais, depuis le Discord, un salon qui nous permet d'avoir accès à tous les builds qui sont faits sur le serveur. Ce qui nous permet de savoir rapidement si un joueur freebuild dans le but de ralentir le serveur.

#### Illégal

D'importants changements vont avoir lieu sur l'illégal qui est trop simple du point de vue de certains joueurs, mais trop dur du point de vue d'autres.

En effet, l'illégal est trop simple pour certains joueurs qui farment de la drogue à des heures tardives dans le but d'agir dans l'illégalité sans aucun risque. Nous trouvons ça trop simple, et comptons empêcher le farm de cette façon. Nous n'allons pas le faire à la manière des braquages de banques ou supérette qui sont basés sur la présence des policiers. Or, l'abscence de policier sur le serveur empêche un nombre incalculable d'actions RP. Nous n'avons pas clairement défini comment, nous attendons donc vos suggestions à ce sujet, nous avions pensé à limiter les spawns de drogues à des heure précises. Et justifier en RP une tempête en mer. Cela serait faisable à l'aide de plugins RocketMod.

Nous allons aussi limiter le braquage des superrettes car certains joueurs abusent des macros pour générer un maximum d'argent. Un retravail de son implémentation sera fait

#### Argent Sale

Lorsque nous évoquions le système d'argent sale exclusif à Lakoya, énormément de jouers étaient pressés de découvrir cela sur Unturned, mais une grande partie était aussi médisant à ce sujet làn et avait peur de son implication au sein de Lakoya. C'est pourquoi nous en avons parlé à la réunion, et nous avons défini en quoi il consisterait.

Au début, nous comptions faire un compte en banque avec une UI présentant l'argent sale que vous possédez. Celle-ci, est illégal, mais comment justifier que la police puisse vous inculper d'en avoir si elle est stockée sur une base de données distante. 

Le staff a donc suggéré qu'elle serait stockée sous forme d'item. Les items seront justifiés en RP par une monnaie étrangère servant uniquement à de l'illégal, et donc en posséder est contraire à la loi.

Vous aurez ensuite un revendeur \(nous ne savons pas encore si nous utiliserons un NPC, ou un plugin crée par nos soins\) qui vous échangera cela contre de l'argent utilisable. Il serait intéressant si ce revendeur puisse changer d'emplacement, et être disponible à des heures distinctes, tout en s'adaptant au nombre de joueurs présents. Cela imposerait la présence d'un plugin qui demanderait du travail, mais qui serait révolutionnaire ainsi qu'exclusif sur Unturned.

#### Dir

Nous avons bien remarqué que la DIR n'était pas totalement organisée sur certains points, et qu'elle rentrait souvent en conflit avec d'autres joueurs. Nous allons donc apporter plusieurs changements à cette entité. 

Premièrement, à la prochaine mise à jour du serveur, nous allons rendre fonctionnelle la dépanneuse. Cela va permettre de rendre le travail de la DIR utile car pour le moment, il se réserver à la réparation de véhicule

Secondement, nous allons enfin instaurer le système de plaques d'immatriculation. Mais contrairement à l'instar de beaucoup de serveurs Unturned, nous comptons développer nous même ce système pour une plus grande flexibilité et contrôle de ce service. Notre infrastructure se baserait sur une base de données MySQL qui serait en lecture/écriture avec le serveur Unturned. Ensuite, le bot discord Lakoya RP aurait accès aux droits de lecture de la base de données afin de générer des statistiques sur les véhicules et simplifier la gestion de la DIR. Une collaboration entre la Gendarmerie et la DIR serait donc possible !

Dernièrement, plusieurs joueurs nous ont rapporté qu'il était dur d'entretenir son véhicule en l'abscence de la DIR. A travers un plugin \(développé par nos soins\), nous allons créer un garage automatique qui fonctionne seulement en l'abscence de DIR. Il ne faut pas s'inquiéter quant à son intégration car nous comptons instaurer une limite d'utilisation ainsi qu'un prix plutôt élevé.

#### Samu

Pour le moment, le travail de Samu sur le serveur est plutôt ennuyant. Et la plupart des joueurs se soignent directement en pharmacie. Prochainement, à la manière d'autres serveurs Unturned, nous allons introduire un système de coma. Contrairement aux autres, nous n'avons pas acheté le plugin d'Imperial, mais nous l'avons crée nous même. L'hôpital deviendra payant, et seule une carte vitale vous fera payer une franchise.

Par ailleurs, à l'image de la DIR, les pharmacies seront sûrement fermées lorsque le Samu sera connecté. Et nous pensons aussi à interdire les bandages qui permettent de se soigner. Ils seront réservés aux crafts.

#### Permis

Beaucoup de problèmes au sujet des permis nous ont été rapportés. En effet, ils comportent une multitude de bugs qui les rend impossible à utiliser. Entre les dispawns et les pertes, ce n'est plus possible de les utiliser de cette manière.

Nous avons donc suggéré, lors d'une réunion, un sytème de permis fonctionnant sur une base de données. La gendarmerie n'aurait donc plus qu'à accéder aux registres afin d'avoir accès aux informations. Mais cela pose problème pour les doubles identités. La création d'un plugin étant capable de gérer cela est possible. Le prix serait élevé, mais permettrait d'éviter la gendarmerie.

#### HRP

Afin d'éviter le HRP, nous allons prochainement investir dans un plugin permettant de cacher le nom des joueurs. Nous allons aussi souvent rappeler des principes de bases afin d'éviter la divulgation d'informations RP. Dernièrement, nous allons demander aux personnes souhaitant de faire des vidéos sur le serveur d'attendre un délai d'1 à 2 semaines pour éviter tout métagaming.

#### Elections

Les dernières éléctions ont été organisées trop rapidement, et ont été baclées. Les prochaines seront donc mieux organisées.

#### Economie

Nous n'avons pas encore complétement défini les changements de l'économie, mais il est sûr que des changements vont avoir lieu.

#### Vote

Nous réfléchissons encore à des récompenses pour les joueurs qui votent. En effet, nous souhaitons récompenser ces joueurs qui soutiennent le serveur. Néanmoins, nous ne souhaitons pas que le serveur devienne un "vote to win". Il est donc nécessaire de trouver le juste milieu. Cette fonctionnalité ne sera donc pas présent prochainement.

## 📌 Suggestions 

{% hint style="info" %}
Toutes les informations données au sein de ce paragraphe n'ont pas encore été complétement définies
{% endhint %}

Changement de l'économie à cause d'un trop déséquilibre sur certains points.

Changement des règles de la DIR, du Samu, et de la Gendarmerie

Changement des capacités des métiers, et de leur complexité.





## 📌 Statistiques

Pour ceux qui pensent que la Whitelist est un frein trop important au serveur voici quelques statistiques :

{% hint style="info" %}
Ces valeurs ne sont valables qu'à la date d'écriture de cette article, soit le 25/09/2019
{% endhint %}

{% tabs %}
{% tab title="Membres" %}
Membres Discord : 480 membres
{% endtab %}

{% tab title="Lakoyien" %}
208 lakoyiens
{% endtab %}

{% tab title="Oral" %}
46 personnes doivent passer leur oral
{% endtab %}

{% tab title="Site internet" %}
371 visites du site ce mois-ci
{% endtab %}

{% tab title="Documentation" %}
210 visites de la documentation en 1 mois !
{% endtab %}
{% endtabs %}

