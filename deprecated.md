# Les trucs obsolètes, pour le meilleur ou pour le pire
## Choix de son niveau de difficultés
A chaque jets, les joueurs pouvaient décider de la difficultés qu'ils voulaient donner à celui-ci, sans pouvoir aller en dessous de la difficulté minimale donné par leur niveau de maîtrise ou l'action qu'ils voulaient effectuer.

Prenons un exemple : Imaginons que Tania la voleuse se batte contre un gobelins des égouts. Elle tente de lui donner un coup de poignard. Même si son seuil de réussite était 13, le joueur de Tania pouvait décider de tenter un jet difficile, à par exemple un seuil de réussite de 17 en espérant que le gobelin n'y arriverait pas.

## Longueur des actions
Dans les versions précédentes du Simon Système, chaque action avait une durée précise comptabilisé en instant. Donner un coup de dague prenait 2 instants, incanter une boule de feu 15 instants, etc etc. L'ordre dans les combats évoluait donc tout le temps en fonction des choses faites par les joueurs. Imaginons que Urlk le nain, à l'instant 0 donne un coup de hache (8 instants), il ne rejouerait donc qu'à l'instant 8. Si Iltir le mage lui commençait à incanter une boule de feu améliorée et multicible à l'instant 4, il ne pourrait faire une nouvelle action qu'à l'instant 34, soit à la fin de l'invocation de sa boule de feu améliorée et multicible. Le système était très intéressant et très dynamique mais avait deux problèmes :
- gérer un combat a 15 protagonistes (7 PJ et 8 monstres) tenait de la quasi-impossibilité et nécessitait un support informatique quelconque (excel ou mini app django maison)
- pour que le système soit intéressant, il fallait avoir des vraies différence de durée. Par exemple avoir des sorts longs à incanter mais puissants. Le problème était que les joueurs
- qui avaient des personnages utilisant des actions longues, même si celles-ci étaient puissantes, avaient souvent l'impression de ne rien faire et de passer leur temps à attendre, pendant que les joueurs utilisant des dagues ou des petits sorts faiblard eux, passaient leur temps à lancer les dés.

Ne trouvant pas de solution (pour l'instant), je suis parti sur un découpage beaucoup plus simple et classique à base d'actions par round.

## Caractéristiques chiffrées
Les caractéristiques devaient être chiffrées, pour calculer la valeur d'une compétence on faisait compétence + caractéristiques.

Les caractéristiques n'évoluaient pas du tout après création du perso.

## École de magie
Il y avait, dans une précédente version des règles, cinq écoles de magies qui définissaient les sorts que l'on était capable de lancer. Les écoles de magies étaient les suivantes :
- Nécromancie
- Magie du combat
- Magie des éléments
- Soins, lumière et magie mentale
- Magie des esprits.

Pour pouvoir lancer un sort, un personnage devait avoir un niveau de compétence supérieur au égal au niveau du sort dans l'école de magie auquel le sort était rattaché. J'ai changé tout cela pour un mécanisme plus libre et qui me semblait proposer plus de liberté et convenir plus au monde que je voulais créer pour le Simon Système.

## Magie
Précédemment il n'y avait que 2 compétences qui entraient en compte pour lancer un sort, la compétence concernant l'école de magie pour lancer le sort en lui même et la concentration en cas de sort long.

## Combat
Il y avait une compétence de parade concernant le combat, détaché de la compétence attaque en mélée
