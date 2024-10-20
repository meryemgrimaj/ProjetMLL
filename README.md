<h1 align='center'>Détection du mildiou de la pomme de terre par imagerie grâce aux méthodes de Machine Learning</h1>

<div align='justify'> Le mildiou de la pomme de terre, causé principalement par deux pathogènes, Alternaria solani pour le mildiou précoce et Phytophthora infestans pour le mildiou tardif, constitue un problème majeur pour les agriculteurs, provoquant chaque année des pertes importantes dans la production de pommes de terre. Ces pertes augmentent également le coût global de la gestion des cultures, notamment par l'utilisation accrue de produits phytosanitaires. L’usage intensif de ces produits entraîne des conséquences négatives pour l'environnement, affectant la santé des sols et des écosystèmes tout en contribuant à l'émergence de résistances chez les pathogènes. Dans ce contexte, une détection précoce et précise des symptômes visibles sur les feuilles des plants de pomme de terre permettrait de limiter les pertes économiques et réduire l'utilisation de fongicides. Le Machine Learning, permettant une analyse automatisée de données issues de sources diverses (texte, image, son), pourrait jouer un rôle clé dans l'optimisation des systèmes de surveillance et de diagnostic des cultures en détectant rapidement et avec précision les premiers signes du mildiou.


Dans cette étude, nous avons exploré l'application de diverses méthodes de Machine Learning pour la détection automatique du mildiou de la pomme de terre par imagerie. Nous avons utilisé un jeu de données composé d’images de plants de pomme de terre, classées en trois états distincts : plantes saines, plantes atteintes par le mildiou précoce ou plantes atteintes par le mildiou tardif. Nous avons mis en œuvre des algorithmes de classification supervisée, tels que les forêts aléatoires sur ce jeu de données et, en parallèle, nous avons testé des approches de Deep Learning, notamment les réseaux de neurones convolutionnels (CNN), qui possèdent une meilleure capacité de différenciation des états de santé des plants. L'objectif principal de cette recherche est de comparer l'efficacité des méthodes classiques de Machine Learning avec celle des algorithmes de Deep Learning. En effet les algorithmes de Machine Learning traditionnels, bien que moins gourmands en ressources que les modèles de Deep Learning, sont en général moins précis, ce qui soulève la question d’un compromis entre précision de prédiction et coût de cette prédiction.

D’après les premiers résultats de cette étude, les méthodes de Deep Learning ont une précision élevée dans la prédiction de l'état de santé des plants. Toutefois, les méthodes de classification supervisée, telles que les forêts aléatoires, ont également produit des résultats convaincants, avec une "accuracy" élevée, suggérant que ces méthodes pourraient suffire pour la détection du mildiou chez la pomme de terre, en particulier pour une détection à grande échelle, où les ressources numériques sont limitées.</div>

Mots-clés : Végétal, Mildiou, Agriculture, Imagerie, Prédiction 



<h1> Structure du repository </h1>
Ce repository comprend plusieurs dossiers : </br>
<ul>
  <li>codes : regroupe l'ensemble des scripts. Ces scripts sont indépendants et présentent des méthodes de Machine Learning différents. Il est conseillé de lancer ces scripts depuis google colab.</li>
  <li>PlantVillage : il s'agit du jeu de données. Ce dossier est présent à titre indicatif. L'importation du jeu de données se fait directement par l'url dans les scripts </li>
  <li>images : regroupe l'ensemble des images issues des scripts : Ce dossier est présent à titre indicatif, les images étant affichées dans les scripts.</li>
</ul>

Le repository contient également d'autres documents comme advanced-potato-disease-detection-efficientnetb3.ipynb utilisé comme référence pour la construction des codes, une présentation générale sous format pdf de l'ensemble des méthodes et résultats et une présentation officielle format pdf pour la conférence.

P.S. Il est possible que l'une des méthodes présentes dans la présentation officielle soit retirée avant la conférence par manque de temps à l'oral.

