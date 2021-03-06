# Remuneration_system_proposal
Remuneration system proposal / Calcul de rémunération par Somme de tributs 


```
@release	13/10/2015
@version	0.1
@authors
	tixlegeek 	<tixlegeek@whoarehackers.com>	http://www.tixlegeek.com

```

La rémunération par somme de tribut est un système de calcul d'une rémunération en fonction d'une somme de tributs %, multiplié par un facteur K.
Le but de ce système est de mettre en place une reconnaissance effective du travail fourni, de répartir équitablement toute richesse générée, et d'approcher une méritocratie partielle.

L'idée de base, c'est que toute personne oeuvrant dans le sens de la communauté (de façon contractuelle ou non) à droit à un salaire (voir salaire unique), et qu'aucun travail, quel qu'il soit, ne peut permettre de prétendre à un salaire dépassant un certain niveau. Dans le cas ou la moyenne du cumul des rémunérations soit supérieur à l'équivalent des rémunérations maximales, alors un impot est prélevé, puis la rémunération plafonnée. Un facteur "K" permet de donner une dimension aux tributs. L'indexation correcte de tous les tributs permet de garantir une rémunération savante, prenant en compte le potentiel général de toute personne donnant de son temps à une quelconque activité allant dans le sens de la communauté.

Il est possible de dresser des profils type pour certaines taches, dans le cas ou le cadre dans lequel l'activité se déroule, ne permette pas de calculer au mieux chaque tribut. Ainsi, en fonction de parametres plus pertinents, il sera possible de coller au mieux au salaire mérité par la personne. 

Ceci est une ébauche. Je vous encourage à me dire ce que vous en pensez, et à développer l'idée. Le but est d'explorer d'autres voies au système de rémunération courant.
## Principe
Chaque tribut représente un pourcentage de charge d'une personne, dans une catégorie standard. Par exemple:

* Tribut physique (p)
* Tribut psychique (m)
* Temps passé à la tache (sur une journée) (t)
* Spécialité (s)
* Polyvalence (P)
* Qualité (q)

Le calcul se présentera donc comme ceci:
```R = K( p+m+t+s+P+q )```
Cette méthode de calcul, en plus de son extrême simplicité présente bon nombre propriétés intéressante :

* Définition d'une rémunération maximale fixe
* Prise en compte des travaux « non contractuels » (maternité/paternité, projets culturels, recherches...
* Régulation des abus par arbitrage claire, et limitation des dérives.
* Valorisation continuelle de toute activité ayant une importance pour la société (études, éducation, direction, travaux, entre-aide...)
* Entre-évaluation des collaborateurs.

La vocation de ce système est de valoriser au mieux le travail en fonction de critères précis. La rémunération peut venir d'un employeur, de l'état, ou d'une organisation.

L'ensemble des revenus (en cas de cumul) est normalisé. Ainsi, si une rémunération totale normalisée venait à dépasser l'équivalent de la somme de tous les tributs fixés au maximum, cette dernière devient la cible d'un impôt spécifique visant à limiter tout type d'abus, partant du principe qu'aucun corps de métier ne peut prétendre à un tel score dans le cadre d'un calcul de bonne foi.

## Les tributs
### Le tribut physique.
Le tribut physique doit être calculé de manière à représenter au mieux le coût physique d'un travail. On peu la définir en fonction de critères plus spécifiques, comme le poid de l'équipement, la solicitation musculaire, les risques encourrus. Un corps de métier peut tout à fait atteindre et dépasser les 100%, au jugé des deux parties.

### Tribut psychique.
Le tribut psychique est un peu plus arbitraire, mais peut être standardisé en fonction de critères plus spécifiques, comme la production de contenu non matériel, la popularité soutenue par le travailleur. Ce tribut peut aussi etre fixé en fonction de paramètres globaux et standardisés, comme l'exposition à la violence, l'exposition personnelle...

### Le temps passé à la tache

Tout simplement le pourcentage de temps passé à effectuer un travail (au sens large). Pourrait être évalué de manière flexible. Le temps réel total de la période de "contrat" (au sens large) Tc, et le temps effectif passé à effectuer un travail Tt donne t selon la formule: t = ((Tc – Tt)/Tc). Cet indice ne peut en aucun cas dépasser 100 %.

### Spécialité

La Spécialité peut être standardisé par corps de métier, et être incrémenté d'un taux global en fonction de l'ancienneté du travailleur. Il peut aussi être indexé sur les qualifications effective du travailleur (certifications, expérience, jugé...). Comme presque tous les tributs, il peut atteindre, et dépasser 100%.

### Polyvalence

La polyvalence représente l'arsenal intellectuel nécessaire à la réalisation du travail. Il peut être calculé en fonction de parametres standards, ou déduit d'un ratio spécifique.

### Qualité

La qualité du travail effectué. Ce parametre doit être soumis à une certaine inertie, car la fluctuation de la qualité du travail revient à un travail de qualité médiocre. Ainsi le calcul doit être effectué à l'année, en fonction d'une appréciation du travail effectué. Ce tribut n'est valorisé qu'apres 1an de travail, et permet de fluctuer en fonction de divers paramêtres. 


## Le facteur K
Le facteur K est fixé globalement en fonction de la conjoncture économique et d'autre facteurs. Il permet de donner la base de rémunération (au pourcentage) de chaque tribut. Bien entendu, si la somme des tributs dépasse l'équivalent de tous les tributs fixés au maximum, un impôt particulier est ponctionné.
