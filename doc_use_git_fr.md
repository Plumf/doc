# Propulser une contribution avec git

**Index**
 - [Création d'un compte sur github.com](#CreationCompteGithub)
 - [Forker la documentation de YunoHost dans votre dépôt personnel](#ForkerDocumentationYunoHost)
 - [Modifier les fichiers et ajouter vos contributions](#ModifAjoutContrib)
 - [Envoyer vos contributions avec une Pull Request](#EnvoyerPR)
 - [Suivre votre contribution et prendre en compte les retours des contributeurs·trices](#SuivreContributions)
 - [Faire remonter des erreurs et des souhaits en créant une issue](#RemonterIssues)
 - [Corriger et inspecter les contributions](#ReviewContrib)
 - [Aller plus loin avec Git et travailler en local sur son ordinateur](#PlusLoinGitOrdi)
 - [Quelques ressources sur le web](#LiensWeb)

Il est bien sûr possible de contribuer directement sur la documentation de YunoHost, mais ce n'est pas la manière la plus pratique de le faire tant pour le/la contributeur·trice que pour la personne qui va injecter votre contribution dans la documentation. Voici un tutoriel pour comprendre et créer une contribution à la documentation de Yunohost en utilisant l'outil [Git (en)](https://git-scm.com/) et [github.com](http://github.com/) qui est le service de forge Git qui héberge et stocke le code source de YunoHost ainsi que sa documentation.

## Création d'un compte sur github.com <a name="CreationCompteGithub"></a>
Pour pouvoir envoyer vos contributions via GitHub, il est nécessaire avoir un compte sur GitHub, pour créer le compte vous aurez besoin d'une adresse email valide à laquelle vous avez accès. GitHub est un outil puissant qui propose de nombreuses fonctionnalités, l'interface peut être un peu effrayant au début.
Vous n'êtes pas obligé·ée de donner vos noms et prénoms, vous pouvez utiliser un pseudonyme (lors de l'inscription `Username`).

*/iframe video creer compte GitHub /*


## Forker la documentation de YunoHost dans votre dépôt personel <a name="ForkerDocumentationYunoHost"></a>
Forker le code source permet de créer une nouvelle branche de développement d'un code source de logiciel ou dans le cas présent, le code source de la documentation. En créant une nouvelle branche, cela vous permet de modifier le code et d'ajouter vos contributions sans altérer le code de la branche `master` qui est le rendu public de la documentation. Ce qui vous permet de ne pas devoir tout marquer mais le faire en plusieurs étapes. (Notamment pour les contributions demandant plus de temps de travail).

Forker un projet sur GitHub est extrêmement simple, il suffit ce cliquer sur le bouton Fork, cela créera un nouveau dépôt sur votre espace de GitHub.
![Capture d'écran bouton fork GitHub](/images/dug_fork.png)
Dans le titre du nouveau dépôt, vous verrez de quelle provenance vient le dépôt, dans le cas présent `YunoHost/doc`
![Capture d'écran titre et sous-titre du dépot](/images/dug_fork_source.png)

*/iframe video forker code source github /*


> **Point de vigilance !**
> Si vous forkez le dépôt d'un autre contributeur que yunohost, vous aurez les mêmes fichiers. Sauf que quand vous enverrez vos modifications, elles seront envoyées au contributeur et non au dépôt yunohost. L'avantage est que ça vous permet de développer une autre branche créee par le contributeur et ainsi travailler avec une autre personne à une amélioration avant proposition au dépôt principal.
> Il n'est pas possible d'avoir un fork du dépot d'un contributeur et le fork dépôt d'origine au même moment dans votre propre dépôt.

## Modifier et ajouter votre contribution <a name="ModifAjoutContrib"></a>
Une fois le dépôt forker (copié), il faudra créer une nouvelle branche de développement au sein de votre dépôt. C'est à travers cette branche que vous allez modifier les fichiers et ainsi proposer des améliorations de la documentation. Le fait que ce soit une nouvelle branche vous permettra par la suite de faire une Pull Request, c'est à dire une demande d'ajout de vos contributions au sein de la branche `master` qui est la branche principale de la documentation. Les règles de développement sur GitHub change selon les développeurs de chaque dépôt, certains ont une branche testing dans laquelle il faut proposer les contributions.
Plus d'informations sur qu'est une branche sur git-scm.com : [Les branches avec Git - Ce qu'est une branche](https://git-scm.com/book/fr/v1/Les-branches-avec-Git-Ce-qu-est-une-branche).

*/iframe video modifier fichiers ajouter contribution /*

## Envoyer votre contribution par une Pull Request <a name="EnvoyerPR"></a>
Faire une Pull Request correspond au moment ou vous souahitez partager votre travaille avec le reste des contributeurs⋅trices et l'intégrer au dépot master (dépôt principale de Yunohost). Lors de la publication d'un Pull Request, couramment nommé PR, les contributeurs⋅trices pourront amender, commenter, ajouter, corriger votre contribution avant intégration complète au dépot.

## Suivre votre contribution et prendre en compte les retours des contributeurs·trices <a name="SuivreContributions"></a>
Lorsque vous avez déjà fait une PR (Pull Request), les modifications de votre branche de développement sur le dépôt Git se rajouteront automatiquement à la PR. Cela ne nécessite aucune action supplémentaire. Vous pouvez aussi intégrer les propositions de modifications de contributeurs, qui lorsqu'ils/elles auditeront le code, peuvent trouver des erreurs ou de nouvelles formulations plus adaptées.

## Faire remonter des erreurs et des souhaits par des issues <a name="RemonterIssues"></a>
YunoHost dispose d'un dépôt git spécifique pour le recueil des issues : [github.com/YunoHost/issues](https://github.com/YunoHost/issues)
Une issue aussi appelé ticket, est un problème identifié ou alors un souhait de développement ; dans le cas présent pour la documentation, mais c'est valable pour tout dépôt logiciel. Dans le cadre de la documentation de YunoHost il sera surtout proposé des issues pour le développement de la documentation, les problèmes identifiés étant facilement corrigeable.

## Aller plus loin avec git et travailler sur son poste de travail <a name="PlusLoinGitOrdi"></a>
Utiliser la puissance de git et ainsi travailler sur son ordinateur personnel, permet entre autres de ne pas avoir à créer de `commit` à chaque enregistrement intermédiaire des pages de documentations modifiées. Cela permet aussi d'utiliser des outils et logiciels qui permettent une distinction plus facile des codes utilisés dans une page de documentation.

- Ressource en ligne : [docs.microsoft.com - Configurer un référentiel Git localement pour la documentation](https://docs.microsoft.com/fr-fr/contribute/get-started-setup-local)

## Quelques ressources ailleurs sur le net pour aller plus loin <a name="LiensWeb"></a>
 - [Gérer son code avec git et github - openclassrooms.com](https://openclassrooms.com/fr/courses/2342361-gerez-votre-code-avec-git-et-github)
 - [Interface utilisateurs·trices de git - git-scm.com](https://git-scm.com/download/gui/linux)

*/ To do/*
*/Ajouter vidéos explicative - Add videos explication/*
*/Ajouter ## Corriger et inspecter les contributions /*