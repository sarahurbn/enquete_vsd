---
layout: page
title: Comment la base de données est-elle organisée ?
subtitle: Il convient de s'interroger sur les catégories utilisées par Francis Lefebvre pour représenter les données juridiques.
---

Concernant la partie technique de notre enquête, Heloïse Eloi-Hammer nous a expliqué qu'il allait être difficile, voire impossible d'accéder aux algorithmes internes des grands éditeurs juridiques, notamment en matière de "ranking" : le classement des résultats obtenus selon leur importance.  
*Voici la partie de son interview consacrée aux algorithmes qui alimentent l'accès aux bases de données juridiques* : [Lien vers la partie de l'interview d'Heloïse Eloi-Hammer sur les algorithmes](https://drive.google.com/file/d/1AHTusoP4iFacLxFLUWxg-H3TtVhB97Aj/view?usp=sharing)

Cependant, Heloïse Eloi-Hammer nous a expliqué que ce qui différenciait également les éditeurs, en dehors des critères de ranking, c'étaient aussi les modalités proposées sur le site. Ces modalités regroupent le fonctionnement des filtres, la présence d'abstracts, du surlignage etc. En effet, selon la doctorante, les critères de ranking, bien que confidentiels dans leur "recette" exacte, seraient en réalité souvent assez similaires : caractère récent de la décision, degré de la juridiction (Cour de Cassation versus 1ère instance par exemple), et le nombre de commentaires de la décision. Comme nous ne pouvions pas avoir accès aux algorithmes précis, nous nous sommes focalisés surtout sur la partie accessible à l'utilisateur, les modalités de l'accès à la base de données par le biais du moteur Navis créé par Francis Lefebvre. Cet accès sera analysé sous le point de vue de la catégorisation. 


## Les enjeux de la catégorisation juridique

**“Décidément, on ne devrait jamais parler de “données” mais d’“obtenues” (Bruno Latour)** 

Dans son étude sur le topofil, Bruno Latour explique que les difficultés de l’étude de la forêt se situent dans le fait que pour les étudier on détache les choses de leur milieu naturel, et “il arrive aux plantes des choses qui ne sont jamais arrivées depuis que le monde est monde”. On comprend alors que ce ne sont pas des “données”, mais des “obtenues”, puisque l’on extrait l’information d’un monde dans lequel elle existe normalement sans interférence. 

Par opposition à la forêt, le droit est un ensemble de règles créées par l’homme. Si l’on met de côté les théoriciens du droit naturel, selon lesquels existe un droit en dehors de toute construction humaine, le droit (entendu au sens de droit positif, qui est en vigueur), est par définition construit et structuré par l’humain. Les catégories font donc en quelque sorte partie de l’essence du droit : ces catégories existent au moment de la création du droit, même si elles sont susceptibles d’évoluer : par exemple avec la création d’un nouveau code etc. 

Les bases de données juridiques, outil créé principalement au service des juristes, recueillent le droit positif, en vigueur. Leur objectif est de servir au travail des juristes. La catégorisation des bases de données est particulièrement importante car la recherche du texte juridique adéquat peut prendre un temps conséquent. L'enjeu est donc économique pour les juristes, une bonne base de données peut permettre de gagner du temps et de l'argent. 

## La catégorisation choisie par Francis Lefebvre 

Cependant, en examinant la catégorisation opérée par Francis Lefebvre, on constate que, si le droit est catégorisé, étant codifié par nature, il n'y a pas qu'une seule forme de catégorisation possible. La base de données a donc un fonctionnement relativement complexe, que nous avons tenté d'élucider.

Le droit est codifié par nature. Par exemple, ce qui est dans le Code du Commerce relève du droit commercial. En parallèle, on distingue aussi différents types de sources du droit : le droit existe en dehors des codes. Ainsi, la jurisprudence et la doctrine sont aussi des sources du droit majeures, utilisées par les juristes dans leur travail. Ainsi, on peut imaginer que les données soient organisées par spécialisation juridique (droit commercial, droit fiscal etc.), ou par sources du droit (loi, jurisprudence, doctrine. En réalité, on peut opérer une catégorisation en deux dimensions, ce qui est environ ce que fait Francis Lefebvre. Cette catégorisation bidimensionnelle est intéressante car elle révèle certains parti-pris de l'éditeur.

## A - Une catégorisation selon le type de texte : 

Dans notre partie sur les utilisateurs, nous avons déjà montré un schéma expliquant le fonctionnement d'une recherche sur Francis Lefebvre : [Lien vers la page Utilisateurs](https://sarahurbn.github.io/enquete_vsd/utilisateurs/).

On voit d'abord que les données sont caractérisées par type de texte : lois, jurisprudence, etc. Ce sont les mémentos qui semblent être au coeur du moteur de recherches de Francis Lefebvre. En effet, nous avons représenté ici un schéma de la page "biens à partager" du Mémento Droit commercial. C'est le mémento qui référence les autres textes : 
![schéma micro](/images/schema_micro.png)

En naviguant avec Navis, le moteur de recherches de Francis Lefebvre, on peut voir que cette catégorisation par type est intéressante, car les différents types de données sont interconnectés. 

De plus, à un niveau plus macro, ces différents types de données ne sont pas accessibles de la même manière. Voici un schéma qui illustre, comment sont interconnectés Mementos créés par Francis Lefebvre, textes de loi et données jurisprudentielles. 

![Schéma donnée](/images/schema_donnees.png)

Ce schéma met en évidence le fait qu'il s'agisse d'une sorte de **réseau** : on voit bien qu'il y a une interconnexion importante, et l'organisation de la base de données, ou du moins l'organisation de son accès n'est pas linéaire. Cependant, comme en attestent les flèches bleues (hyperlien) et noires (pas de lien, simple mention), les connexions ne sont pas toutes aussi fortes les unes que les autres. En particulier, on identifie le fait que la jurisprudence ne soit pas accessible directement par l'utilisateur : au lieu de chercher parmi une liste de jurisprudences, comme c'est le cas dans d'autres moteurs de recherche comme Lexis Nexis et Dalloz, les jurisprudences ne sont accessiblles que si elles sont accessibles dans un mémento (ou un texte de doctrine par exemple, mais nous ne l'avons pas pris en compte ici pour avoir un schéma plus clair et simplifié).

Etant donné que nous n'avions accès qu'à l'interface publique, il nous a été difficile d'analyser l'infrastructure de la base de données. En revanche, nous avons bien pu voir en inspectant le site, comment étaient liées les données. Dans cet exemple par exemple, nous avons inspecté le lien sur un article dans le Code Civil dans le mémento sur les sociétés commerciales : 

![screen lien](/images/screen_lien.png)

'<a class="link" href="/EFL2/convert/id/?id=CCIV171653" onclick="documentLink('CCIV171653');return false">C. civ. art. 388-1-1</a>'

Ainsi, la façon dont Francis Lefebvre a organisé l'accès aux données révèle une perception possible du droit : la jurisprudence vient agrémenter un argument juridique, dont la véritable substance se trouve ailleurs. C'est intéressant à note, puisque nous avons vu plus tard dans notre enquête que la justice prédictive mettait la jurisprudence au centre, étant donné qu'elle utilise des cas passés pour prévoir les cas futurs.

D'ailleurs, la "hiérarchisation" des sources opérée par Francis Lefebvre sur, connu d'ailleurs dans le monde du droit pour ses mémentos, est étroitement liée à un deuxième type de catégorisation : la catégorisation selon la discipline juridique. En effet, chaque mémento est thématique, selon la pratoque visée (B). 

# B - Une catégorisation selon la discipline juridique :

D'autre part, 
le droit commercial inclut les dispositions 




D'ailleurs, il est intéressant de voir que la jurisprudence n'est pas accessible par accès direct alors que c'est elle qui fonde la justice prédictive = REFORMULER




