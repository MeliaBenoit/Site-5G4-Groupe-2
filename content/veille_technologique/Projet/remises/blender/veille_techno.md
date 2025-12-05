+++
title = "Veille technologique"
weight = 1
+++

## Recherche par l'IA
J'ai utilisé [chatgpt](https://chatgpt.com/?utm_source=google&utm_medium=paidsearch_brand&utm_campaign=GOOG_C_SEM_GBR_Core_CHT_BAU_ACQ_PER_MIX_ALL_NAMER_CA_EN_032525&utm_term=chat%20gpt%20chatbot&utm_content=175413815685&utm_ad=744952426781&utm_match=p&gad_source=1&gad_campaignid=22376911868&gclid=EAIaIQobChMIrJTu0IGekQMVE2VHAR3kPikpEAAYASAAEgIoTvD_BwE), la version gratuite et sans compte la plus récente en date du 2025-12-01.

### Question posée à l'IA (chatgpt):
> Dans quel contexte est-il préférable d'utiliser les nœuds géométriques dans blender?

### Réponse
Les *Geometry Nodes* de Blender sont particulièrement utiles lorsque tu veux créer, modifier ou générer des formes **de manière procédurale**, c'est-à-dire avec des règles et des paramètres plutôt qu'en modélisant tout à la main. Voici les contextes où leur usage est le plus pertinent:

---

#### 1. Quand tu veux créer des objets paramétriques et facilement modifiables
Si tu dois ajuster souvent la forme d'un objet (nombre de divisions, taille, densité, motifs...), les Geometry Nodes permettent d'éviter de tout refaire manuellement.

**Exemples:**
- Clôtures, routes, câbles, tuyaux
- Barrières, grilles, motifs répétitifs
- Bâtiments générés automatiquement
- Objets qui doivent s'adapter à une courbe

--- 

#### 2. Pour générer de grandes quantités d'objets automatiquement (scattering)
Quand tu dois peupler une scène avec beaucoup d'éléments:

[Video YouTube](https://www.youtube.com/watch?v=iNU-1ORXw74) /
[Communauté Blender](https://blender.stackexchange.com/questions/255511/simple-scatter-for-geometry-nodes-breaks-when-using-a-collection)

**Exemples:**
- Forêts (arbres, pierres, herbe)
- Débris, particules, feuilles, foules simple
- Distribution d'objets sur une surface

Tu contrôles densité, taille, orientation, aléatoire... tout est procédurales.

---

#### 3. Pour automatiser des tâches répétitives
Dès qu'une tâche implique de répéter des actions, des variations ou des motifs, les Geometry Nodes peuvent la simplifier.

**Exemples:**
- Répéter un motif sur un mur
- Générer un réseau de câbles
- Creuser automatiquement un chemin dans un terrain

---

#### 4. Pour créer des effets complexes difficiles à modéliser manuellement
Les Geometry Nodes sont parfaits dès que les formes deviennent trop complexes ou chaotiques.

[Vidéo YouTube](https://www.youtube.com/watch?v=X1ePZ_U5t6Q) /
[Communauté Blender](https://blenderartists.org/t/procedural-buildings-made-with-geometry-nodes-in-blender-2-93-alpha/1287371)

**Exemples:**
- Motifs organiques (cecllules, fractales)
- Terrains procéduraux
- Végétation paramétrique
- Déformations complexes contrôlées

---

#### 5. Pour rendre certaines opérations non destructives
Tu peux créer des outils personnalisés:
- un profil d'extrusion modifiable,
- un arrangement automatiquement mis à jour,
- un système de génération utilisable dans plusieurs projets.

Cela évite d'altérer définitivement la géométrie.

---

#### Quand il n'est pas nécessaire d'utiliser les Geometry Nodes
Ils ne sont pas utiles pour:
- Modéliser **un objet simple** (chaise, tasse, couteau) à la main
- Faire des retopo classiques
- Faire de l'animation simple (sauf si procédurale)
- De petites modifications de mesh
- Créer une forme très spécifique qui ne se répète pas

---

#### En résumé
Tu devrais utiliser les Geometry Nodes surtout si tu veux:
- Automatiser
- Répéter
- Paramétrer
- Générer
- Éviter le travail manuel répétitif
- Garder un workflow non destructif

Si tu veux, je peux aussi:
- te donner des exemples pratiques selon ton niveau,
- t'expliquer quand *NE PAS* les utiliser,
- ou même te préparer un mini-projet GN étape par étape.

### Analyse de la réponse fournie par l'IA
La réponse fournie par chatgpt est complète répond à nos besoins. Nous avons pu découvrir quand et même quand ne pas utiliser les nœuds géométriques et des exemples ont même été fournis. Mais utiliser l'IA en valait-il la peine, et aurions-nous pu obtenir des réponses similaires en effectuant une simple recherche dans un navigateur classique?

En copiant/collant exactement la même question dans un moteur de recherche, nous obtenons beaucoup de réponses, mais pas à la question posée. Nous obtenons beaucoup d'explications sur **qu**'est-ce que sont les *Geometry Nodes* et sur **comment** les utiliser (Quoi/Comment). Cependant, nous cherchons le Quand.

Même en modifiant ma requête pour "Quand utiliser les *Geometry Nodes* blender, les résultats restent similaires. Cependant, en posant la question en anglais ("When should I use geometry nodes blender"), les résultats deviennet plus intéressant. Le premier résultat obtenu est une question posée sur [reddit](https://www.reddit.com/r/blenderhelp/comments/18ix5gk/what_do_you_guys_use_geometry_nodes_for/) où différentes personnes ont inscrit les cas d'utilisations typiques (*scattering*, animations procédurales, génération de choses abstraites, adaptation à une courbe, etc.)

Ce que nous pouvons déduire de cela, c'est que le résultat final est assez similaire, mais le temps que ça a pris afin d'arriver à ce résultat a été beaucoup plus long lors de la recherche dans un navigateur comparativement à la recherche par IA. De plus, la réponse fournie par chatgpt fournissait plus d'informations et de cas de figures. 

## Choix des sources
La majorité de mes sources viennent de **Youtube** et **Reddit**. Si nous avions été dans le contexte de contenu purement théorique, par exemple l'apprentissage d'un concept mathématique, ces sources n'auraient pas été fiables puisque nous n'avons pas d'informations sur les auteurs ni sur leur expertise.

Cependant, nous nous trouvons ici dans un contexte d'apprentissage performatif, c'est-à-dire que nous cherchons comment faire une chose. Pour savoir si l'information est bonne ou non, il suffit de l'essayer!

En ce qui concerne la vente de produits, il n'y a pas de risques de s'informer directement auprès du **site Blender** puisque leur logiciel est *open source*. On sait donc qu'ils n'essayent pas de nous vendre un produit. **Les *YouTubers***, quant-à-eux, peuvent essayer de nous vendre des formations plus poussées ou essayer de nous inciter à nous abonner afin de leur générer plus de revenus. Cependant, essayer de nous vendre de tutoriel ne rend pas leurs informations moins bonnes: ils ne sont pas biaisés par rapport à notre sujet car ce qu'ils essaient de vendre n'est pas directement lié à Blender, mais bien aux connaissances. S'ils nous donnaient de mauvaises informations, cela nous découragerait d'acheter leurs formations. On peut donc supposer que l'information partagée par les *YouTubers* par rapport à Blender est véridique, seulement pas nécessairement complète.

Finalement, en ce qui concerne le fonctionnement d'un logiciel et son application, il est rare de trouver une source impeccable. Pour s'assurer de la validité et de la fiabilité des informations transmises, il est préférable de consulter plusieurs sources pour une même information. C'est ce que j'ai fait en validant mes informations auprès de Wikipedia et d'un professionnel.

## Est-ce d'actualité?
Pourquoi devrions-nous parler de Blender en 2025? D'abord, avec la forte croissance du nombre d'objets créés par imprimantes 3D, le besoin de modéliser des objets 3D est très actuel. De plus, dans le monde des jeux vidéos, Blender ne cesse d'accroître en popularité. Il est utilisé dans de grandes boîtes informatiques telles que **Epic Games**, **Ubisoft** et **NVIDIA**. 

Il y a une panoplie de projets qui sont possibles à réaliser grâce à Blender, que ce soit du montage vidéo, de l'animation (2D/3D), des films, des jeux vidéos, des plans pour impression 3D ou même pour l'architecture. 