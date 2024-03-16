# GLOSSAIRE

- [Général](#général)
- [Front-end](#front-end)
- [UX / UI](#ux-ui)
- [Architecture](#architecture)
- [Programmation Orientée Objet](#programmation-orientée-objet)
- [Modélisation / Base de données](#modélisation---base-de-données)
- [Symfony](#symfony)
- [Sécurité](#sécurité)
- [RGPD](#rgpd)
- [SEO](#seo)
- [Gestion de projets / DevOps](#gestion-de-projets---devops)
- [English](#english)

## Général 🌟
🔵 1.  Quel est l’environnement à installer pour exécuter un script PHP ? Citer 2 exemples de logiciels permettant ce contexte.
- Laragon et XAMPP.

🔴 2.  Qu’est-ce qu’un algorithme ?
- C'est un ensemble d'instructions et d'opérations pour résoudre un problème ou accomplir une tâche. Un programme c'est l'ensemble des instructions qui représentent un algorithme.

🔵 3.  Qu’est-ce qu’une variable ? Par quel symbole est préfixée une variable en PHP ?
- Une variable est un élément qui associe un nom (identifiant) à une valeur. Elle peut avoir des natures différentes telles que : nombres (int, float), texte (string), booléen (bool), tableau (array), objet (Object), NULL (NULL) ou ressource (resource). Elle est précédée par le préfixe "$".

🔴 4.  Qu’est-ce que la portée d’une variable ?
- La portée d'une variable détermine l'endroit où la variable va être accessible et utilisable :
  - La portée de la variable est globale lorsqu'elle est définie en dehors d'une fonction et est donc accessible dans l'ensemble du script : variable globale,
  - La portée de la variable est locale lorsqu'elle est définie à l'intérieur d'une fonction, elle est donc limitée à celle-ci : variable locale.

🔵 5.  Qu’est-ce qu’une constante ? Quelle est la différence avec une variable ?
- Une constante est une variable comportant une valeur définie qui ne peux être modifiée.

🔴 6.  Qu’est-ce qu’une superglobale, combien en existent-ils et donner un exemple d’utilisation 

🔵 7.  Quels sont les différents types (primitifs) que l’on peut associer à une variable en PHP ? Les citer et en donner des exemples (ne pas oublier le type d’une variable sans valeur)
- String : chaîne de caractère : $chaine = " Elan Formation ";
- Integer(int) : entier : un nombre sans virgule : $entier : 100; 
- Float : décimal : un nombre avec virgule (les virgules sont toujours représentées par des ".") : $decimal : 15.50;
- Boolean(bool) : booléen : utilisé pour exprimer une valeur de vérité : "true" ou "false" : $boolean = true / $boolean = false;
- Array : tableau : utilisé pour réaliser des listes, collections qui associent une (1) clé a une (1) valeur, il prend un nombre illimité de paramètres, chacun séparé par une virgule : $tableau = ["Kevin" => "29", "Léa" => "25", "Ewan" => "24"];
- Object : objet : 
- NULL : nul : une variable qui n'a pas de valeur assignée : $vide = NULL;
- Resource : ressource : variable particulière qui contient une référence vers uen ressource externe au PHP

🔴 8.  Existe-t-il plusieurs types de tableaux en PHP, si oui lesquels ?
- Il existe 3 types de tableaux différents en PHP :
  - Les tableaux numérotés/indexés (les clefs vont être des nombres),
  - Les tableaux associatifs (nous définissons la valeur que l'on souhaite poru chaque clef),
  - Les tableaux multidimensionnels (tableaux qui stockent d'autres tableaux en valeur). 

🔵 9.  Quelles sont les différentes structures de contrôles qu’il existe en algorithmie ? Donner un exemple pour chacune d’entre elles

🔴 10. Quelle est la fonction PHP permettant de demander la longueur d’une chaîne de caractères ?
- La fonction est : "strlen(string $string): int", elle retourne la taille de la chaîne string en int.

🔵 11. Qu’est-ce qu’une session ? Quelle fonction permet de démarrer une session en PHP ? Donner un exemple d’utilisation en PHP

🔴 12. Qu’est-ce qu’un cookie ? Donner un exemple d’utilisation en PHP
- Un cookie appelé aussi témoin de connexion ou témoin, est une petite quantité de données échangées entre un serveur HTTP et un client HTTP, et qui permet de créer une session avec état lors de la visite d'un site Web. 

🔵 13. Quelle est la différence entre les instructions « require » et « include » en PHP
- La différence est que " require " provoque une erreur bloquante (fatal error) (E_COMPILE_ERROR) et arrêtera le script, tandis que " include " provoque un avertissement (warning) (E_WARNING) mais le script continue de fonctionner.

🔴 14. Comment effectuer une redirection en PHP ?

🔵 15. Définir la partie « front-end » et « back-end » d’une application
- La partie " front-end " (côté client) d'une application fait référence à ce que voient les utilisatuers : texte, images, boutons... et avec lesquels les utilisateurs peuvent intéragir (menus de navigation...), on utilise le HTML, le CSS ou encore le JavaScript pour contrôler la structure, le visuel ou encore le responsive d'une page internet.
- La partie " back-end " (côté serveur) d'une application fait référence aux fonctionnalités générales qu'elle comporte. Elle traite les demandes dues aux interactions des utilisateurs (remplir un champ de texte avec des données personnelles ...).

🔴 16. Définir le contrôle de version ? Qu’est-ce que Git ?

🔵 17. Qu’est-ce qu’un CMS ? Citer au moins 2 exemples
- C'est un Système de Gestion de Contenu (Content Management System), cela permet de créer, modifier facilement un site internet (blog, site de vente en ligne...).
  - Il existe par exemple : WordPress, TYPO3, Drupal, PrestaShop...


## Front-end 🌟
🔴 18. Définir HTML
- Le HyperText Markup Language (langage de balises pour l'hypertexte) est le langage de balisage conçu pour représenter une page internet et sa structure.

🔵 19. Définir CSS
- Les Cascading Style Sheets (feuilles de style en cascade) forment un langage qui décrit la présentation des documents HTML et XML, elles permettent de donner du visuel et de la personnalité à une page internet afin de la rendre attractive. Le CSS est également utilisé afin de rendre une page web responsive.

🔴 20. Définir Javascript
- Le JavaScript est un langage de programmation " orienté objet " de scripts principalement employé dans les pages web interactives.

🔵 21. Définir JSON. Dans quel contexte ce format est-il utilisé ? 
- JSON : JavaScript Object Notation, est un format de données textuel dérivé de la notation des objets du langage JavaScript. C'est basé sur des paires nom/valeur et des listes ordonnées.

🔴 22. Peut-on interpréter du Javascript côté serveur ? Si oui, comment ?

🔵 23. Qu’est-ce qu’un sélecteur CSS ?
- Les sélecteurs CSS définissent les éléments sur lesquelles s'applique un ensemble de règles CSS, voici les 3 plus utilisés :
  - Les sélecteurs de types : input {};
  - Les sélecteurs de classes : .classe {};
  - Les sélecteurs d'identifiants : #id {} (l'ID est unique).

🔴 24. Quelle balise HTML permet de créer un lien hypertexte ?
- La balise "<a href="> description du lien </ a>.

🔵 25. Qu’est-ce qu’une requête AJAX ?
- C'est utilisé pour la communication asynchrone : envoyer des requêtes vers le serveur et déclencher des opérations lors de la réception de réponses de celui-ci.

🔴 26. Quel sélecteur CSS permet de sélectionner tous les éléments d’une classe spécifique ? D’un identifiant spécifique ?
- C'est le sélecteur de classe : ".nomclasse {}" ; ou le sélecteur d'identifiant : "#valeurid {}".

🔵 27. Définir le responsive design
- C'est un ensemble de pratique qui permet d'offrir une consultation confortable sur des écrans de tailles très différentes.

🔴 28. Qu’est-ce que le templating ?
- C'est l'utilisation de modèle ou de patron qui permettent une organisation du code plus ordonnée afin d'être mieux organisé et de gagner en efficience.

🔵 29. Qu’est-ce qu’une fonction anonyme en Javascript ?

🔴 30. Quelle méthode JavaScript est utilisée pour ajouter un élément à la fin d'un tableau ?
- La classe "Array" fournit les méthodes pour traiter les tableaux et la méthode "push()" permet d'ajouter un élément à la fin d'un tableau.

🔵 31. Qu’est-ce qu’un « media query » ?
- Les requêtes média (media queries) permettent de modifier l'apparence d'un site ou d'une application en fonction du type d'appareil (impression, écran, ...) et de ses caractéristiques (la résolution d'écran ou la largeur de la zone d'affichage (viewport) par exemple). Les media queries permettent d’appliquer certains styles de manière conditionnelle avec le CSS grâce aux règles @media et @import.

🔴 32. Qu’est-ce qu’un pseudo élément en CSS ?
- Mot-clé ajouté à un sélecteur qui permet de mettre en forme certaines parties de l'élément ciblé par la règle. Ainsi, le pseudo-élément "::first-line" permettra de ne cibler que la première ligne d'un élément visé par le sélecteur : "p ::first-line { color: blue; text-transform: uppercase; }".

🔵 33. Qu’est-ce que Bootstrap ? Donner d’autres exemples équivalent
- C'est une collection d'outils utiles à la création du design de site et d'applications web. Il contient des codes HTML et CSS, des formulaires, boutons... Il existe de nombreux équivalent, notamment :
  - Tailwind CSS,
  - Bulma,
  - Materialize,
  - Foundation by Zurb,
  - Skeleton...

🔴 34. Quand un formulaire HTML est créé, quelles sont les 2 méthodes qui peuvent lui être associées ? Donner la différence entre ces 2 méthodes.
- L'attribut "method" définit la méthode HTTP qui sera utilisée pour envoyer les données au serveur, il peut prendre les valeurs suivantes :
  - post : la méthode POST, utilisée pour envoyer des données au serveur ; les paramètres (données saisies par l'utilisateur) sont passés dans la requête elle-même.
  - get : la méthode GET, utilisée pour récupérer les données, qui après passent par l'URL.

## UX UI 🌟
🔵 35. Quelle est la différence entre UX Design et UI Design ?
- L'UX Design : User eXperience Design (UXD) est une méthode de conception centré sur l'utilisateur afin de lui proposer une expérience unique où l'ergonomie et la navigation sont adaptées à une cible définie. Les 3 pilliers de l'UX sont : contenter l'utilisateur, écouter l'entreprise et maîtriser la technologie.
- L'UI Design : User Interface (UID) est l'étape de conception de l'interface utilisateur : l'expérience utilisateur (UX) est liée au design graphique de l'interface (UI). Le but est de créer une interface agréable et pratique, facile à prendre en main. L'UI s'attaque plus particulièrement aux éléments perceptibles : éléments graphiques, boutons, navigation, typographie...

🔴 36. Qu’est-ce qu’un wireframe ? 
- C'est une représentation visuelle d'une maquette dite, "fil de fer", en niveau de gris. Elle représente la structure et la fonctionnalité d'une seule page web ou d'un écran d'application mobile.

🔵 37. Qu’est-ce qu’un prototype ? 

🔴 38. Qu’est-ce que la hiérarchie visuelle en UI Design ?

🔵 39. Qu’est-ce que l’accessibilité en UX Design ? 

🔴 40. Qu’est-ce qu’une grille de mise en page ?

🔵 41. Qu’est-ce que la notion d’affordance en UX Design ?

🔴 42. Qu’est-ce qu’un « mobile first design » ?
- C'est un concept de web design optimisé pour le mobile qui va au-delà du responsive web design. Il consiste à concevoir un site en mettant la priorité sur la version mobile et en adaptant progressivment le web design pour les écrans plus large.

## Programmation orientée objet (POO) 🌟

🔵 43. Donner une définition de la programmation orientée objet
- C'est un modèle de programmation qui repose sur le concept de classes et d'objets. C'est utilisé pour structurer un programme logiciel en éléments de code simples et réutilisables, généralement appelés classes, qui sont utilisés pour créer des instances individuelles d'objets. 

🔴 44. Qu’est-ce qu’une classe ? Comment la déclare-t-on ?
- C'est un ensemble de code contenant des variables et des fonctions permettant de créer des objets. Elle peut contenir plusieurs objets. On la déclare avec le mot-clé "class" suivi du nom de la classe et des {} ; on déclare ensuite ses attributs et méthodes.

🔵 45. Qu’est-ce qu’un objet ?
- On peut prendre une classe concrète au moyen d'uns intance de classe (1 objet) : on instancie la classe. Un objet est un exemple concret de la classe. En PHP, on instancie une classe avec le mot-clé new (puis le nom de la classe derrière, ex : "new Voiture()"), c'est à dire que l'on qu’on crée 1 objet.

🔴 46. Définir la notion de propriété / attribut / méthode

🔵 47. Qu’est-ce que la visibilité d’une propriété ou d’une méthode ? Citer les différents types de visibilité

🔴 48. Quelle est la méthode spécifique utilisée pour créer un nouvel objet à partir d’une classe ?

🔵 49. Qu’est-ce que l’encapsulation ?

🔴 50. Que signifie « étendre une classe » ? Quelle est le concept clé mis en œuvre ? Donner un exemple

🔵 51. Définir l’opérateur de résolution de portée

🔴 52. Définir une méthode / propriété statique

🔵 53. Définir le polymorphisme en POO

🔴 54. Définir une méthode / classe abstraite ?

🔵 55. Définir le chaînage de méthodes

🔴 56. Qu’est-ce que la méthode __toString() ? Existe-t-il d’autres méthodes « magiques »

🔵 57. Qu’est-ce qu’un « autoload » ?

🔴 58. Comment appelle-t-on en français les « getters » et les « setters » ?

🔵 59. Qu’est-ce que la sérialisation en PHP ? 

## Architecture 🌟
🔴 60. Qu’est-ce que l’architecture client / serveur ? Grâce à quel type de requête peut-on interroger le serveur. Définir l’acronyme de ce type de requête. Si on ajoute un « S » à cet acronyme, expliquer la différence

🔵 61. Donner la définition d’un design pattern. Citer au moins 3 exemples de design pattern

🔴 62. Qu’est-ce que l’architecture MVC ?

🔵 63. Quel est le rôle de chaque couche du design pattern MVC : Model, View, Controller ?

🔴 64. Quels sont les avantages de l’architecture MVC ?

🔵 65. Existe-t-il des variantes à l’architecture MVC ?

🔴 66. Qu’est-ce qu’une API ? Définir l’architecture REST

## Modélisation - Base de données 🌟
🔵 67. Qu’est-ce que la modélisation de données ? Définir la méthode Merise

🔴 68. Quelles sont les 3 étapes principales de la méthode Merise ? 

a.  Analyse, conception et réalisation

b.  Planification, exécution et contrôle

c.  Création, modification et suppression

🔵 69. Qu’est-ce qu’un modèle conceptuel de données (MCD) en Merise ?

🔴 70. Qu’est-ce qu’un modèle logique de données (MLD) en Merise ?

🔵 71. Donner la définition des mots suivants :

a.  Entité

b.  Relation

c.  Cardinalité

d.  Clé primaire / clé étrangère

🔴 72. Que devient une relation de type « Many To Many » dans le modèle logique de données ?

🔵 73. Qu’est-ce qu’une base de données ?

🔴 74. Définir les notions suivantes : 

a.  SQL

b.  MySQL

c.  SGBD (donner 2 exemples de SGBD)

🔵 75. Dans une base de données, les données sont stockées dans des ___. Celles-ci sont constituées de lignes appelées ___ et de colonnes appelées ___

🔴 76. Quelle est la différence entre une base de données relationnelle et non relationnelle ?

🔵 77. Qu’est-ce qu’une jointure dans une base de données ? En existe-t-il plusieurs ? Si oui lesquelles ?

🔴 78. A quoi sert une vue dans une base de données ?

🔵 79. Qu’est-ce que l’intégrité référentielle dans une base de données ?

🔴 80. Quelles sont les fonctions d’agrégation en SQL ?

🔵 81. Qu’est-ce qu’un CRUD dans le contexte d’une base de données ?

🔴 82. Quelles sont les clauses qui permettent de :

a.  Insérer un nouvel enregistrement dans une table

b.  Modifier un enregistrement dans une table

c.  Supprimer un enregistrement dans une table

d.  Supprimer la base de données

e.  Filtrer les résultats d’une requête SQL

f.  Trier les résultats d’une requête SELECT

g.  Regrouper les résultats d'une requête SELECT en fonction d'une colonne spécifique

h.  Concaténer 2 chaînes de caractères 

🔵 83. Comment se connecter à une base de données en PHP ? Quelle est la classe native utilisée ?

## Symfony 🌟
🔴 84. Qu’est-ce que Symfony ?

🔵 85. Sur quel langage de programmation et design pattern repose Symfony ? 

🔴 86. Quelle est la dernière version en date de Symfony ?

🔵 87. Qu’est-ce qu’un bundle ? 

🔴 88. Quel est le moteur de template utilisé par défaut dans Symfony ?

🔵 89. Qu’est-ce qu’un ORM ? Quel est son utilité et comment s’appelle-t-il au sein de Symfony ?

🔴 90. Qu’est-ce que l’injection de dépendances ? Quel est l’outil utilisé dans ce contexte et quel fichier contient l’intégralité des dépendances du projet ?

🔵 91. Que permet le bundle Maker au sein de Symfony ? 

🔴 92. Quel est le langage de requêtage exploité au sein d’un projet Symfony ?

🔵 93. Quel est le composant qui garantit l’authentification et l’autorisation des utilisateurs ?

## Sécurité 🌟
🔴 94. Qu’est-ce que l’injection SQL ? Comment s’en prémunir ?

🔵 95. Qu’est-ce que la faille XSS ? Comment s’en prémunir ?

🔴 96. Qu’est-ce que la faille CSRF ? Comment s’en prémunir ?

🔵 97. Définir l’attaque par force brute et l’attaque par dictionnaire

🔴 98. Existe-t-il d’autres failles de sécurité ? Citer celles-ci et expliquer simplement leur comportement

🔵 99. A quoi servent l’authentification et l’autorisation dans un contexte d’application web ?

🔴 100.    Définir la notion de hachage d’un mot de passe et citer des algorithmes de hachage

🔵 101.    Qu’est-ce qu’une politique de mots de passe forts ?

🔴 102.    Qu’est-ce que l’hameçonnage ?

🔵 103.    Définir la « validation des entrées »

## RGPD 🌟
🔴 104.    Qu’est-ce que le RGPD ?

🔵 105.    Quel est son objectif principal ?

🔴 106.    Quelle est la date d’entrée en vigueur du RGPD ?

🔵 107.    Quelles sont les sanctions possibles en cas de non-respect du RGPD ?

🔴 108.    En France, quel est l’autorité administrative qui s’occupe de faire appliquer le RGPD ?

🔵 109.    Quel est le consentement valide selon le RPGD ?

🔴 110.    Qu’est-ce qu’une politique de confidentialité ?

🔵 111.    Quelle est la durée de conservation maximale des données personnelles selon le RGPD ?

🔴 112.    Quels sont les droits des utilisateurs selon le RGPD ?

🔵 113.    Qu’est-ce que le principe de minimisation des données selon le RGPD ?

## SEO 🌟
🔴 114.    Qu’est-ce que le SEO ? 

🔵 115.    Quel est l’objectif principal du SEO ?

🔴 116.    Existe-t-il plusieurs types de référencement ? Lesquels ?

🔵 117.    Qu’est-ce que la densité de mots-clés en SEO ?

🔴 118.    Qu’est-ce qu’une balise « alt » ?

🔵 119.    Qu’est-ce que la balise « meta description » ?

🔴 120.    Qu’est-ce que le « nofollow » en SEO ?

🔵 121.    Quelle est l'importance du contenu de qualité pour le référencement d'un site web ?

🔴 122.    Pourquoi est-il important d'utiliser des balises de titre (h1, h2, h3, etc.) de manière structurée ?

🔵 123.    Quelle est la recommandation pour les URL d'un site web bien référencé ?

🔴 124.    Qu'est-ce que le maillage interne et pourquoi est-il important pour le référencement ?

🔵 125.    Qu'est-ce que l'optimisation des images pour le référencement ?

🔴 126.    Qu'est-ce qu'un plan de site (sitemap) et pourquoi est-il important pour le référencement ?

## Gestion de projets - DevOps 🌟
🔵 127.    Qu’est-ce que la gestion de projet ?    

🔴 128.    Qu’est-ce qu’une méthode Agile de gestion de projet ? 

🔵 129.    Expliquer la méthode MoSCoW en quelques lignes et citer ses avantages

🔴 130.    A quoi sert la méthodologie MVP ? Citer les caractéristiques clés

🔵 131.    Qu’est-ce que la planification itérative ?

🔴 132.    Citer 3 méthodes Agiles dans le cadre d’un projet informatique

🔵 133.    Qu’est-ce qu’une réunion de revue de projet ?

🔴 134.    Qu’est-ce qu’un livrable dans un projet ? 

🔵 135.    Quels sont les 3 piliers SCRUM ? Définir chacun d’entre eux

🔴 136.    Qu’est-ce que le DevOps et quel est son objectif principal ?

🔵 137.    Qu’est-ce que l’intégration continue ? 

🔴 138.    Qu’est-ce que Docker ? Et en quoi est-il utile dans le cadre du DevOps ?

🔵 139.    Qu’est-ce qu’un test unitaire ? 

🔴 140.    Quelle est l'unité de code testée lors d'un test unitaire ?

🔵 141.    Quelles sont les caractéristiques d'un bon test unitaire ?

🔴 142.    Qu'est-ce qu'une assertion dans un test unitaire ?

## English 🌟
1)  What does JavaScript enable you to do on a website ?

a.  Add interactive behavior and dynamic content

b.  Define the layout and design of web pages

c.  Handle server-side operations

2)  Which programming language is primarily used for server-side web development ?

a.  PHP

b.  JavaScript

c.  HTML

3)  What is the purpose of a web browser ?

a.  To render and display web pages

b.  To execute serve-side code

c.  To manage databases

4)  What is the difference between GET and POST methods in HTTP ?

a.  GET retrieves data from a server, while POST submits data to a server

b.  GET submits data to a server, while POST retrieves data from a server

c.  GET and POST methods are interchangeable

5)  What is the purpose of version control systems (e.g., Git) in web development ?

a.  To track changes and manage collaborative development

b.  To optimize website loading speed

c.  To handle server-side scripting

6)  What is the purpose of a framework in web development ?

a.  To provide a structured environment for building web applications

b.  To handle network protocols and data transfer

c.  To create visual designs and layouts for websites

7)  What does NoSQL stand for ?

a.  Not Only SQL

b.  Non-Structured Query Language

c.  New Object-Oriented Language

8)  Which of the following is a characteristic of NoSQL databases ?

a.  Strict schema enforcement
b.  Support for complex transactions
c.  Scalability and flexible data models
