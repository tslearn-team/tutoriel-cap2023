# Machine Learning pour les séries temporelles en Python

Ceci est un document de travail pour la proposition d'un tutoriel à CAp 2023.

## Infos importantes

Mail de contact (de Romaric Gaudel, co-organisateur des aspects scientifiques de CAp, avec Charlotte Laclau) :

Premier mail :

> Bonjour Romain,
> J'espère que cette nouvelle année commence bien pour toi.
>
> Avec Charlotte Laclau nous organisons les aspects scientifiques de CAp qui se déroulera dans le cadre de la plateforme AFIA (à Strasbourg, du 3 au 5 juillet pour CAp et du 3 au 7 juillet pour PFIA). À ce titre nous sondons quelques personnes avant que l'appel à tutoriel officiel ne soit lancé.
>
> Nous avons pensé à toi qui pourrait profiter de l'occasion pour présenter tslearn à un publique large (toutes les thématiques de l'IA, y compris un certain nombre d'industriels utilisateurs d'IA). Est-ce que ça t'intéresse ?
>
> Cordialement,
> Romaric

Deuxième mail :

> Bonjour Romain,
> Merci pour ce premier retour positif.
>
> Ce dont je suis certain : un tutoriel se déroule sur une demi-journée et dure généralement 2 x 1h30.
>
> Pour ce qui est de le faire à deux avec une partie pratique ça ne devrait pas poser de problème, il y a même de fortes chances que l'idée soit très appréciée. Je demande confirmation au comité d'organisation.
>
> En revanche, PFIA prévoit de financer deux jours d'inscription à la conférence à ceux qui n'auraient pas de fonds propres pour le faire, et j'imagine qu'ils seront prêts à le faire pour une personne, mais pas pour deux.
>
> Je vous tiens au courant.
> Cordialement,
> Romaric

Troisième mail :

> Bon, en parcourant [la page web donnant les instructions de soumission de tutoriel](https://pfia23.icube.unistra.fr/tutoriels/index.html?p=soumissions.html) j'ai trouvé la réponse aux questions :
> "Un bref résumé du/des orateur(s),"
> "quelques prises de courant dans la salle, des bornes multi-prise peuvent éventuellement être installées sur demande en avance"
>
> Vous avez d'autres questions ?
>
> Si ça vous convient, vous avez jusqu'au 22 mars pour préparer ce qui est demandé sur la dite page et l'envoyer à Ahmed Samet (ahmed.samet@insa-strasbourg.fr).
> Prévenez-moi de votre décision, si vous soumettez Charlotte et moi soutiendront votre candidature.
>
> Romaric

## Format

* 3h
* tutoriel joint `tslearn` / `pyts`
* au moins moitié pratique sur les librairies
* 3 personnes pour animer : Yann Cabanes, Johann Faouzi, Romain Tavenard

## Contenu

* Partie `tslearn`
  * Mesures de similarité entre séries temporelles
  * Application à l'apprentissage de séries temporelles. Par exemple de la classification de données audio ?
  * Possibilité de se baser sur le [cours à l'ENSAI de RT](https://rtavenar.github.io/ml4ts_ensai/) et les [posts de blog](https://rtavenar.github.io/blog/) pour DTW + softDTW + kmeans-DTW + SVM-GAK + Structured prediction avec loss softDTW
    * un vrai + serait que le backend pytorch pour tslearn soit dispo d'ici là et qu'on puisse importer la softDTW comme une loss pytorch depuis tslearn

## Formulaire à remplir

Les propositions doivent être soumises dans un seul fichier PDF contenant les informations suivantes :

* Une description du tutoriel en deux phrases, à inclure dans la brochure d’inscription à la conférence.
  > Ce tutoriel se concentre sur l'utilisation des packages tslearn et pyts pour effectuer des analyses de jeux de données temporels. Les participants apprendront à manipuler et à préparer des données temporelles pour l'apprentissage automatique, ainsi qu'à mettre en œuvre des modèles de séries temporelles à l'aide de ces deux packages.

* Une description du tutoriel en deux paragraphes, pouvant être incluse dans la brochure d’inscription à la conférence.
  > Ce tutoriel de Python, machine learning et séries temporelles sera présenté en deux parties. Dans la première partie, les créateurs des packages tslearn et pyts expliqueront les principales méthodes utilisées pour l'analyse et la prédiction à partir de données temporelles. Les participants pourront ainsi acquérir une compréhension théorique approfondie des outils et techniques qui leur seront présentés.
  >
  > Dans la deuxième partie du tutoriel, les participants mettront en pratique les enseignements de la première partie. Les créateurs des packages tslearn et pyts guideront les participants dans la manipulation et la préparation de données temporelles pour l'apprentissage automatique, ainsi que dans l'implémentation de modèles de séries temporelles à l'aide de ces deux packages. Les participants pourront ainsi appliquer concrètement les connaissances acquises dans la première partie.

* Un déroulé détaillé du tutoriel sous forme de points
  >
  * **Première partie : présentation des concepts**
    + Mesures de similarités
      - TODO
      - TODO
    + Représentation par sac de mots
      * Justification de l'approche
      * Représentation d'une (sous-)série temporelle par un mot
        - Domaine temporel : Symbolic aggregate approximation
        - Domaine fréquentiel : Symbolic Fourier approximation
      * Représentation d'une série temporelle par un sac de mots et application à la classification
        - Domaine temporel : bag of patterns, symbolic aggregate approximation in vector space model
        - Domaine fréquentiel : Bag of symbolic Fourier approximation symbols, word extraction for time series classification
  * **Deuxième partie : travaux pratiques**
    + Mesures de similarités
      - possibilité : classification de séries temporelles audio (feux de bois, cascades, vents).
      - possibilité : si le backend PyTorch est intégré, faire des prévision avec softDTW comme fonction de perte (loss function).
    + Classification de séries temporelles par des approches "sac de mots"
      - Comparaison des différentes représentations pour une (sous-)série temporelle
      - Étude de l'impact de certains hyper-paramètres sur les sacs de mots obtenus
      - Classification de séries temporelles par un algorithme classique de classification à partir des sacs de mots.

* Une brève caractérisation du public cible potentiel du tutoriel, y compris les connaissances pré-requises
  > Le public cible potentiel de ce tutoriel serait principalement composé de développeurs, de data scientists, d'ingénieurs et d'étudiants intéressés par l'apprentissage automatique et l'analyse de données temporelles. Les participants devraient avoir une compréhension de base de Python et de l'apprentissage automatique, ainsi qu'une familiarité avec les concepts de base des séries temporelles. Les connaissances pré-requises comprennent notamment la manipulation de données en Python, la modélisation de données et l'utilisation d'algorithmes de machine learning de base.

* Une brève description des raisons pour lesquelles le sujet du tutoriel intéresserait une partie importante du public de PFIA, et quels sont, parmi les objectifs ci-dessus, ceux qui sont le mieux servis par le tutoriel.
  > Du fait de la plus grande disponibilité de capteurs et de l'augmentation de la collecte de données, les séries temporelles sont de plus en plus présentes dans de nombreux domaines : (cyber)sécurité, maintenance, médecine, environnement, climat, etc. L'analyse de telles données complexes nécessite des algorithmes spécifiques tenant compte de la structure de ces données. Une majeure partie du public de PFIA rencontre probablement régulièrement des séries temporelles dans leurs projets, et ce tutoriel permettra de lui présenter certaines approches pour leur analyse. Plus précisément, le tutoriel se focalisera sur deux approches. Les mesures de similarité entre séries temporelles, ainsi que leurs applications en apprentissage automatique, seront présentées. La représentation par sac de mots pour les séries temporelles, avec comme application la classification de séries temporelles, sera également présentée.

* Un bref résumé du/des orateur(s), qui doit inclure :
  * Nom, affiliation, numéro de téléphone, adresse électronique
  * Expérience dans le domaine du tutoriel, y compris une liste de publications/présentations
  * Citation d’un exemple de travail disponible dans le domaine (idéalement, un article publié ou des documents de présentation sur le sujet)
  * Éléments d’expérience d’enseignement (cours enseignés ou références)

  > Romain Tavenard (Professeur - Université de Rennes 2 - +33 2 99 14 18 04 - romain.tavenard@univ-rennes2.fr)
  >
  > Créateur de la librairie `tslearn` d'apprentissage à partir de données temporelles (3M+ téléchargements, 2k+ stars sur GitHub), mes travaux de recherche se focalisent sur l'apprentissage pour les données temporelles ([lien vers mon profil Google Scholar](https://scholar.google.com/citations?user=wn1XFWMAAAAJ&hl=fr)).
  > La librairie `tslearn` est décrite dans l'article [1] publié dans JMLR.
  > J'enseigne la programmation en Python, l'apprentissage profond, ainsi que l'apprentissage à partir de données temporelles, à l'Université de Rennes 2 et à l'ENSAI ([lien vers les notes du cours d'apprentissage sur données temporelles à l'ENSAI](https://rtavenar.github.io/ml4ts_ensai/))
  >
  > [1] R. Tavenard, J. Faouzi et al. Tslearn, a machine learning toolkit for time series data. The Journal of Machine Learning Research, 2020

  > Johann Faouzi (Enseignant-chercheur - École Nationale de la Statistique et de l'Analyse de l'Information - +33 6 76 17 92 71 - johann.faouzi@ensai.fr)
  >
  > Créateur du paquet Python `pyts` dédiée à la classification de séries temporelles (près de 2m de téléchargements, 1.4+ stars sur GitHub), une partie de mes travaux de recherche se focalisent sur l'apprentissage automatique pour les données temporelles. Un article [2] décrivant `pyts` a été publié dans JMLR en 2020. J'ai également contribué à la librairie `tslearn` [1]. Une revue de littérature sur les algorithmes et les librairies pour la classification de séries temporelles [3] a également été acceptée comme chapitre de livre.
  > J'enseigne la programmation en Python, la programmation orientée objet et la documentation du code, et je suis responsable du projet "Traitement de données" à l'ENSAI.

  
  > Yann Cabanes (Ingénieur de recherche à l'Université de Rennes 2 - +33 6 85 90 95 24 - yann.cabanes@gmail.com)
  
  > Ma mission en tant qu'ingénieur de recherche à l'Université de Rennes 2 est de maintenir la librairie tslearn [1] créée par Romain Tavenard.
  > Je travaille notamment à l'intégration du backend PyTorch à la librairie tslearn.
  > J'ai réalisé une thèse de mathématiques appliquées à l'Institut de mathématiques de Bordeaux durant laquelle j'ai donné 128 heures de cours en Licence 1 et Licence 2 à l'Université de Bordeaux. J'ai ensuite réalisé un premier ATER de 6 mois à l'Université de Bordeaux durant lequel j'ai eu l'occasion d'encadrer des travaux pratiques en Python sur des thèmes de statistiques, puis j'ai effectué un second ATER à l'IUT de Bordeaux. 
  > Pour plus de détails sur mes activités, voici un [lien vers ma page personnelle](https://ycabanes.perso.math.cnrs.fr/).
  
  
  > Références
  >
  > [1] R. Tavenard, J. Faouzi et al. Tslearn, a machine learning toolkit for time series data. The Journal of Machine Learning Research, 2020.
  >
  > [2] J. Faouzi and H. Janati. pyts: A Python Package for Time Series Classification. Journal of Machine Learning Research, 21(46):1−6, 2020.
  >
  > [3] J. Faouzi. Time Series Classification: A review of Algorithms and Implementations. To appear in: Ketan Kotecha (Ed.), Machine Learning (Emerging Trends and Applications), ISBN 978-1-8381524-1-3, 2023.
