# Questions de compétences

## Ralph Dion

Les questions suivantes essaient de cibler quels sont exactement vos compétences dans les abilités requises par le poste de Directeur informatique à la Coméul. Bien qu'il y ai des bonnes et mauvaises réponses aux questions, il n'y a aucun problème à avoir des mauvaises réponses, où même ne pas connaître la réponse: _ce test ne cherches pas à vous disqualifier sur la base de vos réponses_, nous cherchons simplemement à voir où vous êtes dans votre parcours professionnel!

Pour réponse à ce test, veuillez vous ouvrir un compte sur Github.com (si vous n'en avez pas déjà un), faire un *fork* de ce repo, répondre aux questions dans un nouveau document sur votre repo et effectuer un *pull request* pour nous soumettre les réponses. (Soyez assurés, les réponses ne resteront pas en ligne très longtemps, et vous pourrez détruire votre *fork* une fois la *pull request* acceptée!). Considérant le temps alloué, je vous suggère d'utiliser l'interface web de Github plutôt que d'aller en ligne de commande! 😉

Celà va de soi, vous avez doit à Internet, ceci étant dit, le temps alloué est relativement court, donc utilisez le avec parcimonie! Toujours en raison du temps, ne cherchez pas à donner la réponse la plus longue, mais tenez-vous en au minimum requis!

Bonne chance! 💪🔥

### Généralités

#### Le responsive design… C’est quoi?
Le responsive design est une façon de faire les interface afin qu'elles soient lisible et esthétiques dans plusieurs résolutions (mobiles, écran HD, 4k, etc). Actuellement, la tendance veut que le design principal soit celui pour mobile, puis adapté pour écrans larges. 

#### Pourriez-vous me donner trois moyens de réduire le temps de chargement d’une page?
Minifier les feuilles de styles, insérer les scripts à la fin et optimiser les images pour la résolution utilisée du site.

#### Seriez-vous capable de m’expliquer l’avantage principal de HTTP2 sur HTTP1.1 ?
L'objectif de HTTP2 est d'améliorer la performence des sites et de diminuer les temps de latences du end-user. 

#### Quels sont les différentes _methods_ en HTTP, et quelle est leur fonction?
Get: Aller chercher l'information entrée par l'utilisateur en les passant par l'URL
Post: Aller chercher l'information entrée par l'utilisateur directement
Head: 
Delete:Efface les données spécifiées
Trace:
Connect:
Option: Afficher les options disponibles

#### Qu'est-ce que le MVC?

#### Sapristi! Un de nos sites WordPress a été hacké. Il affiche des publicités de médicament louches, en russe! Que faire?
Du code à probablement été injecté dans le site. J'identifierais s'il y a eu des pushs sur le git (s'ils sont passés par quelque par d'aussi évident). Peut-être que revenir à une version précédente du site permettrait d'éliminer le problème. Ensuite, il faudrait réviser la sécurité de l'infrastructure. 

### CSS / HTML
#### Quels sont le ou les framework que vous avez utilisez en CSS dernièrement? Quel critique pourriez-vous leur faire?
Actuellement je vois beaucoup le framework SASS dans divers milieux. J'aime beaucoup cette façon de travailler avec CSS, qui regroupe plusieurs éléments en plus de donner des options supplémentaires. Cependant, il peut être difficile à lire par moment à cause des arborescence parfois longue. 

#### Quelle est la différence entre un class et un id en CSS.
Le ID est appelé à l'aide de '#', à une importance beaucoup plus grande au niveau de l'application des styles(100 unités ou 1000?). Les classes ont un certain poid pour l'application de style, mais beaucoup moindre que les ID (équivaux à 10 unités).

### Javascript

#### Qu'est-ce que ce code affiche?

```javascript
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```
(dans la console)
one
two
three

### PHP

#### Quelle est la différence entre `==` et `===`?
le '==' compare les deux valeurs, alors que '===' compare la valeur et le type de valeur.

#### Quelle est la différence entre une classe et une interface?
Les interfaces permettent de créer des templates pour ensuite passer ces propriétés aux classes. 

#### Quelle est la valeur de `$resultat` dans le code suivant?

```php
<?php

$jour = [
	'nom' => "Mercredi",
	'valeur' => 3
];

$resultat = ($jour['valeur'] == 3) ? "Nous sommes {$jour['nom']}" : "'Nous ne sommes pas {$jour['nom']}";
```
Nous sommes Mercredi
### Humour louche de programmeur

#### Si vous avez écouté *Sillicon Valley*, au sujet des indentaions... Espaces ou tabulations?
Je n'ai pas écouté Sillicon Valley, mais TABULATION. Cependant, des études ont prouvées que les programmeurs utilisant des espaces plutôt que des tabulations ont des salaires plus élevés en moyenne. Terrible. 
