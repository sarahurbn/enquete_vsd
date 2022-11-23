---
layout: page
title: Comment la base de données est-elle organisée ?
subtitle: Il convient de s'interroger sur les catégories utilisées par Francis Lefebvre pour représenter les données juridiques.
---

Concernant la partie technique de notre enquête, Heloïse Eloi-Hammer nous a expliqué qu'il allait être difficile, voire **impossible d'accéder aux algorithmes internes des grands éditeurs juridiques, notamment en matière de "ranking"** : le classement des résultats obtenus selon leur importance.  
*Voici la partie de son interview consacrée aux algorithmes qui alimentent l'accès aux bases de données juridiques* : [Lien vers la partie de l'interview d'Heloïse Eloi-Hammer sur les algorithmes](https://drive.google.com/file/d/1AHTusoP4iFacLxFLUWxg-H3TtVhB97Aj/view?usp=sharing)

Cependant, Heloïse Eloi-Hammer nous a expliqué que ce qui différenciait également les éditeurs, en dehors des critères de ranking, c'étaient aussi les modalités proposées sur le site. Ces modalités regroupent le **fonctionnement des filtres, la présence d'abstracts, du surlignage etc**. En effet, selon la doctorante, les critères de ranking, bien que confidentiels dans leur "recette" exacte, seraient en réalité souvent assez similaires : caractère récent de la décision, degré de la juridiction (Cour de Cassation versus 1ère instance par exemple), et le nombre de commentaires de la décision. Comme nous ne pouvions pas avoir accès aux algorithmes précis, nous nous sommes focalisés surtout sur la partie accessible à l'utilisateur, les modalités de l'accès à la base de données par le biais du moteur Navis créé par Francis Lefebvre. Cet accès sera analysé sous le point de vue de la catégorisation. 


## Les enjeux de la catégorisation juridique

**“Décidément, on ne devrait jamais parler de “données” mais d’“obtenues” (Bruno Latour)** 

Dans son étude sur le topofil, Bruno Latour explique que les difficultés de l’étude de la forêt se situent dans le fait que pour les étudier on détache les choses de leur milieu naturel, et “il arrive aux plantes des choses qui ne sont jamais arrivées depuis que le monde est monde”. On comprend alors que ce ne sont pas des “données”, mais des “obtenues”, puisque l’on extrait l’information d’un monde dans lequel elle existe normalement sans interférence. 

Par opposition à la forêt, le droit est un ensemble de règles créées par l’homme. Si l’on met de côté les théoriciens du droit naturel, selon lesquels existe un droit en dehors de toute construction humaine, le droit (entendu au sens de droit positif, qui est en vigueur), est par définition construit et structuré par l’humain. **Les catégories font donc en quelque sorte partie de l’essence du droit** : ces catégories existent au moment de la création du droit, même si elles sont susceptibles d’évoluer, par exemple par réformes.  

Les bases de données juridiques, outil créé principalement au service des juristes, recueillent le droit positif, le droit en vigueur. La catégorisation des bases de données est particulièrement importante car la recherche du texte juridique adéquat peut prendre un temps conséquent. Il s'agit donc d'offrir une base de données efficace et complète. Pour ce faire, il faut d'abord **catégoriser les données**, afin d'organiser la base de données et de faciliter son utilisation.

## La catégorisation choisie par Francis Lefebvre 

Cependant, en examinant la catégorisation opérée par Francis Lefebvre, on constate que, si le droit est catégorisé, étant codifié par nature, il n'y a pas qu'une seule forme de catégorisation possible. La base de données a donc un fonctionnement relativement complexe, que nous avons tenté d'élucider.

Le droit est codifié par nature. Par exemple, ce qui est dans le Code du Commerce relève du droit commercial. En parallèle, on distingue aussi différents types de sources du droit, puisque le droit existe en dehors des codes. Ainsi, la jurisprudence et la doctrine sont aussi des sources du droit majeures, utilisées par les juristes dans leur travail. Ainsi, on peut imaginer que les données soient organisées par **spécialisation juridique** (droit commercial, droit fiscal etc.), ou par **sources du droit** (loi, jurisprudence, doctrine). En réalité, on peut opérer une catégorisation en deux dimensions, ce qui correspond à ce que fait Francis Lefebvre. Cette **catégorisation bidimensionnelle** est intéressante car elle révèle certains parti-pris de l'éditeur.

## A - Une catégorisation selon le type de source du droit : 

Dans notre partie sur les utilisateurs, nous avons déjà montré un schéma expliquant le fonctionnement d'une recherche sur Francis Lefebvre : [Lien vers la page Utilisateurs](https://sarahurbn.github.io/enquete_vsd/utilisateurs/).

On voit d'abord que les données sont caractérisées par type de texte : lois, jurisprudence, etc. Ce sont les **mémentos** qui semblent être au coeur du moteur de recherches de Francis Lefebvre. En effet, nous avons représenté ici un schéma de la page "biens à partager" du Mémento Droit commercial. C'est le mémento qui référence les autres textes : 
![schéma micro](/images/schema_micro.png)

En naviguant avec Navis, le moteur de recherches de Francis Lefebvre, on peut voir que cette catégorisation par type est intéressante, car les différents types de données sont **interconnectés**. 

De plus, à un niveau plus macro, ces différents types de données ne sont pas accessibles de la même manière. Voici un schéma qui illustre, comment sont interconnectés Mementos créés par Francis Lefebvre, textes de loi et données jurisprudentielles: 

![Schéma donnée](/images/schema_donnees.png)

Ce schéma met en évidence le fait qu'il s'agisse d'une sorte de **réseau** : on voit bien qu'il y a une interconnexion importante, et l'organisation de la base de données, ou du moins l'organisation de son accès n'est pas linéaire. Cependant, comme en attestent les flèches bleues (hyperlien) et noires (pas de lien, simple mention), les **connexions ne sont pas toutes aussi fortes les unes que les autres**. En particulier, on identifie le fait que la jurisprudence ne soit pas accessible directement par l'utilisateur : au lieu de chercher parmi une liste de jurisprudences, comme c'est le cas dans d'autres moteurs de recherche comme Lexis Nexis et Dalloz, les jurisprudences ne sont accessibles que si elles sont mentionnées dans un mémento *(ou un texte de doctrine par exemple, mais nous ne l'avons pas pris en compte ici pour avoir un schéma plus clair et simplifié)*.

Ainsi, la façon dont Francis Lefebvre a organisé l'accès aux données révèle une forme de **philosophie du droit** : la jurisprudence vient agrémenter un argument juridique, dont la véritable substance se trouve ailleurs. C'est intéressant à noter, puisque nous avons vu plus tard dans notre enquête que la justice prédictive mettait la jurisprudence au centre, étant donné qu'elle utilise des cas passés pour prévoir les cas futurs.

La "hiérarchisation" des sources opérée par Francis Lefebvre, connu d'ailleurs dans le monde du droit pour ses mémentos, est étroitement liée à un deuxième type de catégorisation : la catégorisation selon la discipline juridique. En effet, chaque mémento est thématique, selon la pratique visée (B). 

# B - Une catégorisation selon la discipline juridique :

Comme évoqué dans notre partie sur les utilisateurs susmentionnée, Francis Lefebvre propose un certain nombre de matières : Comptabilité, Social, Droit des affaires, Immobilier, Fiscal, Civil-Patrimoine, Gestion Finance, Particulier, Association, International. La catégorisation par sources du droit reste clairement dominante, car c'est elle qui est utilisée en priorité pour filtrer. Cependant, étant donné que **les mémentos sont le coeur du moteur et que ceux-ci sont catégorisés par discipline**, cette catégorisation-ci est importante aussi. 

![screen disciplines](/images/disciplines.png/)

Cette capture d'écran de la page de Francis Lefbebvre montre (en jaune) l'importance des mémentos sur le site, et le fait que ceux ci soient classés par discipline : sociétés commerciales, sociétés civiles, droit commercial, transmission d'entreprise, concurrence consommation. Il s'agit probablement des mémentos les plus populaires mis en exergue sur la première page, s'agissant de pratiques très importantes dans la plupart des cabinets d'affaires. On voit ici que Francis Lefebvre a un **fort tropisme vers le droit des affaires**, ce qui destine l'éditeur à une clientèle particulière. On voit également que l'on peut sélectionner en haut (en rouge) la matière : Affaires, Associations, Comptable, Fiscal, Immobilier, Patrimoine, Social. Ici les domaines sont classés par ordre alphabétique. 

Cette catégorisation est donc indissociable de la forte importance des mémentos chez Francis Lefebvre. De surcroît, elle révèle l'inclinaison de Francis Lefebvre envers le **droit des affaires**. 

En dehors de ces grandes catégorisations, les juristes savent souvent ce qu'ils cherchent et naviguent rarement sans objectif précis. C'est là qu'interviennent les mots clé (C). 

# C - Les mots-clés 

La recherche de mots-clés sur Francis Lefebvre suit un format sophistiqué. Ainsi, on peut voir que l'éditeur a organisé les mots clés sous forme d'**arbre logique**. Cette recherche s'appuie sur des connecteurs logiques permettant de combiner intelligemment les termes que l'on souhaite trouver ou éliminer. 
Concrètement, voici à quoi ressemble la recherche par mots-clés : 

![screen mots clé](/images/motcle.png/)

*Voici un exemple de combination de mots-clé :*

![screen mots clé](/images/motcleillustre.png/)

On obtient à la fin une expression logique, affichée sur le site, qui sera évaluée par un **algorithme sachant interpréter ces expressions booléennes**, pour trouver les résultats pertinents :

<span style = "color:orange">( (exception de nullité) ET (litispendance) )</span> OU <span style = "color:blue"> ( (fin de non recevoir) SAUF (prescription) )<span>

Ici, nous aurons tous les résultats qui regroupent soit <span style = "color:orange"> l'exception de nullité avec obligatoirement la litispendance</span>, soit <span style = "color:blue">la fin de non recevoir en excluant la prescription</span>, qui est l'une des fins de non recevoir. Ce système de filtrage par expressions booléennes est utile car cela permet une grande flexibilité dans les recherches, notamment lorsque l'on n'est pas certain de l'orientation d'une affaire. 

L'exemple des mots-clés illustre à quel point la numérisation des bases de données juridiques peut être un outil extrêmement utile pour des juristes, car ce genre de combinations dans les recherches n'est possible que grâce aux algorithmes et à la numérisation des données. Ainsi, les recherches ne sont pas seulement plus rapides, mais aussi plus précises, et peut-être complètes. On pourrait aussi argumenter, qu'au contraire, le fait de se reposer sur des algorithmes pourrait peut-être faire perdre quelques informations, surtout que l'on dépend des choix de design et d'agrégation des données d'un éditeur. En réalité, cela dépend probablement de l'utilisation que chacun en fait, et **utilisées à bon escient, ces bases de données peuvent être un outil redoutable, et d'ailleurs très peu de juristes s'en passent**. 

# Conclusion de la partie 

Notre partie technique a été relativement limitée car **nous n'avons pas eu accès aux algorithmes de Francis Lefebvre**, ni même eu la chance de parler à une personne en interne qui aurait pu nous donner des grandes lignes sur les techniques employées. Nous nous sommes donc limités à analyser les données  disponibles publiquement, pour tenter de **comprendre la philosophie de l'éditeur** dans la mise à disposition des données juridiques pour les utilisateurs. Cette partie nous donc également appris, que, comme nous l'a bien indiqué Héloïse Eloi-Hammer dans son interview, les algorithmes de ranking ne font pas tout : il y a plein d'autres choix à faire dans la création d'une base de données juridiques, des choix évidents au premier abord puisque le droit est codifié par nature, mais qui ne sont pas si évidents que cela en réalité puisque différents éditeurs ont différentes approches. 

Suite à d'autres prises de contact pour notre projet, nous avons ensuite **orienté notre enquête vers le besoin d'innovation des bases de données juridiques**. En effet, comme dans la plupart des domaines aujourd'hui l'émergence de l'Intelligence Artificielle, et plus particulièrement du Machine Learning ont grandement changé la donne, et l'agrégation des données ne suffit plus. Nous sommes donc allés analyser [la justice prédictive](https://sarahurbn.github.io/enquete_vsd/justice_predictive/), [l'innovation au sein de Francis Lefebvre](https://sarahurbn.github.io/enquete_vsd/innov/) et enfin [la coopération de l'éditeur avec la start-up Oppus](https://sarahurbn.github.io/enquete_vsd/startups/).






