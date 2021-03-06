<img src="readme/img/simplon.jpg" width="400">

----------------------

# Diagramme de Use-Case

Ce chapitre s'inscrit dans le module [Diagramme UML](https://github.com/simplonco/Diagrammes-UML).

1. [x] [Diagramme Use-Case](https://github.com/simplonco/UML-Use-Case)
	
2. [ ] [Diagramme de Séquence](https://github.com/simplonco/UML-Sequence)
	
3. [ ] [Diagramme d'Intéraction](https://github.com/simplonco/UML-Interaction)
	
4. [ ] [Diagramme de Classe](https://github.com/simplonco/UML-Class)

Vous pouvez trouver ce module dans les parcours suivants :

+ Développeur Web Fullstack

------------

Le plus basique, et celui qui doit constituer la **première étape** du montage de votre cahier des charges est le **use-case**.

Le diagramme doit être le plus simple possible et a un but unique : **lister les différentes utilisations de mon produit**. Chaque type d'utilisateur est représenté par un stickman et chaque actions liées à un ou plusieurs type d'utilisateur.

Prenons l'exemple de notre application :

+ Notre application doit permettre à chaque utilisateur de créer un profil avec ses coordonnées bancaires.
+ Mais seul le cycliste doit pouvoir créer un profil pour son vélo et ses caractéristiques.
+ Seul le réparateur aura une interface pour prendre en charge une réparation.
+ Les deux auront une interface pour laisser un avis sur leur expérience.

![Diagramme de use-case](readme/img/use-case.jpg)

##Les outils
Pour faire un use case avec StarUML c'est très simple :

Step 1 : Créer un model de use-case.

![Diagramme de use-case](readme/img/starUML-create.png)

Step 2 : Récupérer les éléments dans mon toolbox.

![Diagramme de use-case](readme/img/starUML-Actor.png)
