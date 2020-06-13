# Présentation de GITHUB 
GitHub est une plate-forme web de contrôle de version et de collaboration pour les développeurs de logiciels. GitHub a été lancé en 2008 et a été fondé sur Git, un système de gestion de code source ouvert créé par Linus Torvalds pour accélérer la construction de logiciels.

Git est utilisé pour stocker le code source d'un projet et suivre l'historique complet de toutes les modifications apportées à ce code. Il permet aux développeurs de collaborer plus efficacement sur un projet en fournissant des outils pour gérer les changements éventuellement conflictuels de plusieurs développeurs. GitHub permet aux développeurs de changer, d'adapter et d'améliorer les logiciels de ses dépôts publics gratuitement, mais il est nécessaire de payer pour les dépôts privés. Chaque dépôt public ou privé contient tous les fichiers d'un projet, ainsi que l'historique des révisions de chaque fichier.

GitHub facilite le travail en équipe en fournissant une interface web afin d'accéder au dépôt de code Git et des outils de gestion pour la collaboration. Les membres peuvent se suivre les uns les autres, évaluer le travail des autres, recevoir des mises à jour pour des projets spécifiques et communiquer publiquement ou en privé.

Trois termes importants utilisés par les développeurs dans GitHub sont fork, pull request et merge.

- Un fork, est simplement un dépôt qui a été copié du compte d'un membre vers le compte d'un autre membre.
- Les pull requests (demandes de modifications de code) sont très partiques sur GitHub, elles permettent a une communauté de soumettre leur correction de bug, ajout de fonctionnalitée ou optimisation a un code. Elles seront ensuite "review" par le/les propriétaire(s) du dépot qui ensuite va vérifier si ces modifications pour être sur qu'il peut les "merge" sans problème dans son code.
- Merge veut dire fusionner deux branches (voir ci dessous) pour par exemple ajouter les fonctionnalités mise a jour sur la branche B a la branche A. Mais il peut arriver que vous vous retrouviez face a un conflit et nous allons aussi voir comment les résoudres.

## Fork

Créer un fork est très simple, il vous suffit de vous rendre sur un dépôt et de cliquer sur le bouton fork.
![Fork1](https://imgur.com/YAS4zPo.png)
![Fork2](https://imgur.com/ZxsZw5A.png)

## Pull requests

Pour créer une pull request vous avez plusieurs possibilitée.

- Vous avez peu de modifications à faire.
- Vous avez de grosses modifications à faire.

Dans le cas ou vous avez peu de modifications à faire vous avez juste a vous rendre sur le fichier que vous voulez editer et cliquer sur le bouton prévu a cet effet.

![PR1](https://imgur.com/9mgNj8X.png)
![PR2](https://imgur.com/xAEMOsZ.png)

Vous arriverez sur une page comme celle ci.

![PR3](https://imgur.com/k0bPEKJ.png)

Ajoutez simplement vos modifications.
Ensuite allez tout en bas de la page, vous y trouverez deux zones de textes, elles vous permettent de résumer ce que vous venez de faire sur le code, pour permettre au(x) propriétaire(s) de mieux comprendre vos modifications.

![PR4](https://imgur.com/C4xTj9y.png)

Cliquez sur propose changes.

![PR5](https://imgur.com/Man1z6T.png)

Cliquez sur create pull request. Cela va automatiquement créer un fork du dépôt sur votre compte et soumettre la modification.

**Et voila votre première pull request est maintenant créée, vous n'avez plus qu'a attendre que votre code soit vérifié et validé.**

![PR6](https://imgur.com/89i28tY.png)

# Merge 

Pour merge une pull request il vous suffit de vous rendre sur la partie des pull request (logique) et de cliquer sur celle que vous voulez merge.

![MERGE1](https://imgur.com/89i28tY.png)

Sur cette page vous pouvez accepter la pull request, donc la merge sur une branche. Vous pouvez aussi commenter les modifications ou poser des questions a celui qui l'a proposé. Ou tout simplement la fermer car vous ne voulez pas de ces modifications ou parce qu'elles ne sont pas correctes.

![MERGE2](https://imgur.com/rUoj0Gr.png)

![MERGE3](https://imgur.com/heSFezh.png)

Pour voir les modifications il vous suffit de cliquer sur le bouton "files changed". Vous obtiendrez alors une liste de tous les fichiers qui ont été modifié.

![MERGE4](https://imgur.com/0kACVye.png)

> Surligné en Rouge = Ce qui a été Suprimmé

> Surligné en Vert = Ce qui a été Ajouté

Et finalement pour l'accepter, il vous suffit de cliquer sur le bouton "merge pull request".

![MERGE5](https://imgur.com/8DjuHNC.png)

Editez les informations si besoin.

![MERGE6](https://imgur.com/9AuLYMm.png)

Bravo ! Vous avez accepté votre première pull request.
