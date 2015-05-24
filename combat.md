# Régles de Combat
On l'a déja vu, les personnages (ainsi que les pnj ou les montres) possédent des caractéristiques leur permettant d'évaluer leur capacité à combattre.

Ce sont tout d'abord les compétences de combats qui décrivent de manière grossière les compétences martiales des personnages  :
- Attaque en mêlée
- Attaque à distance
- Esquive (relié à Agilité)

Les classes de spécialisations d'armes permettent de gagner en granularité. Elles sont au nombres de onze :

```
1. Fléau et Marteau, F  
2. Petite lame, AG
3. Moyenne lame, AG
4. Grande lame, F  
5. Hache, F  
6. Arme d'hast, F  
7. Bâton, AG
8. Arc, DEX
9. Arbalète, DEX  
10. Arme de Jet, DEX  
11. Corps à Corps, F ou AG
```

Ceux sont c'est deux ensembles de valeurs qui vont nous permettre de résoudres tout les combats du Simon Système et savoir qui blesse qui (voir qui tue qui) lorsqu'on en viendra à tirer l'épée (ou l'arc ou le sabre ou la hache)

## Déroulement d'un combat
Un combat se découpe en Round. Lors d'un round tout les participants du combat pourront réaliser un certain nombre d'action. Une fois que tout les participants ont effectués leur actions, on passe au round suivant.

### Déroulement d'un Round
C'est le joueur avec le plus haut niveau d'initiative qui commence. On commence par appliquer les effets persistants si il y en a (par exemple si le personnage a été empoisonné et qu'il perd des points de vie à chaque tour ou si il doit consommer des points de mana pour garder actif un sort)  Il annonce ensuite le style de combat qu'il souhaite utiliser (ou s'il souhaite garder celui qu'il a utilisé jusqu'à présent) et si il retarte son round ou pas. S'il retarte son round, on passe au joueur suivant dans l'ordre d'initiative, s'il décide de jouer tout de suite il déclare alors ses actions. On les résout immédiatement, dans l'ordre qu'il décide. On applique ensuite les effets de fin de round si il y en a puis on passe au joueur suivant.

## Définition de l'ordre d'action
Définir l'ordre d'action est assez simple. Il suffit de calculer ce que l'on appelle l'initiative pour chaque participant au combat. L'initiative se calcule ainsi, on lance un D20 auquel on ajoute le modificateur d'AG ainsi que tout les autres modificateurs s'appliquant.

Sauf circonstances exceptionnelles, qui seront dans ce cas là précisé, l'initiative reste la même tout au long d'un combat.

Il est possible pour un personnage de retarder son action. Il faut qu'il déclare au tout début de son tour qu'il souhaite jouer à la fin du tour d'un personnage précis (en le nommant). Il doit déclarer sa volonté de retarder son action avant d'avoir effectué toute autre action. Si il fait une action qu'elle qu'elle soit, il ne peut plus retarder son tour.

Une fois la décision de retarder son tour prise et déclarée, elle ne peut plus être modifier, même pour retarder encore plus son tour.

## Que faire pendant son round
Pendant son round, un personnage peut faire 3 actions. Il peut faire :

```
* une action simple
* une action de mouvement
* une action rapide
```

### Les actions simples
Lancer un sort, Donner un coup avec son arme de mélée, tirer avec une arme à distance, voila des exemples d'actions simples

### les actions de mouvement
A chaque round un personnage peut se déplacer. Il peut se déplacer d'autant de mêtre que sa valeur de déplacement. Cette valeur se calcule en divisant par dix la valeur de vélocité de la race des personnages auquel on a appliqué les modificateurs potentiels ( le modificateur de caractéristique agilité, celui d'armure etc... ) .

Race      | valeur de vélocité
:-------- | :-----------------
Humain    | 30
Elfe      | 40
Demi-Elfe | 30
Nain      | 24

### Les actions rapides
Dérouler un parchemin, jeter son arme à terre pour en dégainer une nouvelle, recharger son arc, déboucher et boire une potion, voila quelques exemples des actions rapides.

## Déroulement d'une passe d'arme
L'attaquant choisit et annonce sa cible. Il annonce ensuite avec quelle arme il attaque et si il utilise une botte spéciale ou pas.

On calcule ensuite la valeur de difficulté de l'attaque ainsi que de la défense. L'attaquant et le défenseur effectue leur jet.

Pour savoir qui gagne la passe d'arme, on utilise le mécanisme de résolution d'un jet en opposition. Si c'est l'attaquant, il blesse son adversaire, si c'est le défenseur, il repousse l'attaque (et peu blesser son adversaire par la même occasion).

Si nécessaire on calcule ensuite les dégats reçus par chacun des personnages. Cette valeur de dégats correspond à la valeur des dégats de l'arme à laquel on applique les modificateurs de caractéristiques (relié à la classe de l'arme utilisée), tout les modificateurs s'appliquant dans la situation de la passe d'armet. On déduit également de cette valeur de dégats la valeur de protection de l'armure de celui qui reçoit les dégats. Il peut donc arriver qu'un personnage qui pourtant vient d'être touché ne reçoive aucun dégat.

### Calcul des valeurs de difficultés
#### Cas d'une attaque en mélée
L'attaquant prend sa valeur d'attaque à laquelle il ajoute sa valeur de compétence d'arme et si nécessaire le modificateur de caractéristique qui en découle. Il applique ensuite le modificateur de style de combat ainsi que celui rattaché à la botte qu'il peut tenter de vouloir placer. Une foi ces quelques calculs fait, il obtient sa valeur d'expertise finale.

Le défenseur prend sa valeur d'attaque à laquelle il ajoute sa valeur de compétence d'arme et si nécessaire le modificateur de caractéristique qui en découle. Il applique ensuite le modificateur de style de combat ainsi que celui rattaché à la botte qu'il peut tenter de vouloir placer. Une foi ces quelques calculs fait, il obtient sa valeur quasi finale. En effet, il peut arriver qu'au cours d'un même round, un même personnage se retrouve à devoir se défendre plusieurs fois.

.. note:: Par Exemple si Olgur se retrouve face à face avec quatre gobelins, il va, à chaque round, devoir se protéger des assauts des quatre gobelins. Il devra participer à quatre passe d'arme défensive par round. Et cela, même pour un héros, cela peut être difficile.

Au fil des passes d'armes défensive du même round, il devient plus difficile au personnage qui doit y participer d'être concentré et réactif. Après avoir participé à Valeur de la classe de spécialisation divisé par deux, passes d'armes défensive, le personnage qui doit encore participé à de nouvelle passe d'arme reçoit un malus cumulatif de 2.

.. note:: Pour affronter les quatre gobelins, Olgur brandit sa fidèle épée à deux mains (classe de spécialisation 4 Grande Lame). Sa valeur de classe de spécialisation 4 est de 7. Il peut donc participer aux trois premières passes d'arme défensive sans malus. Par contre il devra affronter la dernière passe d'arme avec un malus de -2. Et si par malheur pour lui il y avait eu cinq gobelins, il aurait alors du tenter de résister en ayant un malus de -4 lors de la cinquième passe d'arme de chaque round. Autant dire qu'il faut espérer pour Olgur qui occisse rapidement un ou deux gobelins pour soulager la pression qu'il subit.

#### Cas d'une attaque à distance
L'attaquant prend sa valeur d'attaque à laquelle il ajoute sa valeur de compétence d'arme et si nécessaire le modificateur de caractéristique qui en découle. Il applique enfin les modificateurs concernant la luminosité, la taille de la cible et la distance. Une fois cela fait, il obtient sa valeur d'expertise finale.

Pour le défenseur, la valeur de défense est en fait une valeur d'esquive du projectile. Il lui faut donc prendre sa valeur d'esquive, y ajouter le modificateur d'agilité, appliquer les modificateurs d'activité qui peuvent faire sens en fonction de la situation et retrancher à cela la vitesse du projectile qui le vise. Il obtient alors sa valeur de défense finale.

### Le combat sur la durée
Un combat peut durer un certain temps. Et certaines armes ne sont pas taillées pour de longs combats et deviennent plus des handicaps que des avantages au bout d'un certain temps.

Si vous n'êtes pas de force au dessus de la normale, l'utilisation d'une arme de classe 4 , 5 (hormis la hachette), 6, ou 1 (sauf les gourdins), pendant plus de 10 rounds vous fatiguera tellement que vous écoperez d'un malus de 2 sur les jets de combats (attaque, mêlée, esquive, dégâts). Ce malus ne s'effacera qu'après une période de repos (nuit ou demi journée tranquille). La fatigue vous tombera également dessus à la fin du quatrième combat s'enchaînant sans période de repos (nuit, demi journée tranquille)
