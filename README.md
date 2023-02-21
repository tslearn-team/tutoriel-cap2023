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
  * Application au learning
  * Possibilité de se baser sur le [cours à l'ENSAI de RT](https://rtavenar.github.io/ml4ts_ensai/) et les [posts de blog](https://rtavenar.github.io/blog/) pour DTW + softDTW + kmeans-DTW + SVM-GAK + Structured prediction avec loss softDTW
    * un vrai + serait que le backend pytorch pour tslearn soit dispo d'ici là et qu'on puisse importer la softDTW comme une loss pytorch depuis tslearn

## Formulaire à remplir

Les propositions doivent être soumises dans un seul fichier PDF contenant les informations suivantes :

* Une description du tutoriel en deux phrases, à inclure dans la brochure d’inscription à la conférence.
* Une description du tutoriel en deux paragraphes, pouvant être incluse dans la brochure d’inscription à la conférence.
* Un déroulé détaillé du tutoriel sous forme de points
* Une brève caractérisation du public cible potentiel du tutoriel, y compris les connaissances pré-requises
* Une brève description des raisons pour lesquelles le sujet du tutoriel intéresserait une partie importante du public de PFIA, et quels sont, parmi les objectifs ci-dessus, ceux qui sont le mieux servis par le tutoriel.
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
  > [1] Tslearn, a machine learning toolkit for time series data. R. Tavenard, J. Faouzi et al. The Journal of Machine Learning Research, 2020

  > Johann Faouzi (Enseignant-chercheur - École Nationale de la Statistique et de l'Analyse de l'Information - +33 6 76 17 92 71 - johann.faouzi@ensai.fr)
  >
  > Créateur du paquet Python `pyts` dédiée à la classification de séries temporelles (près de 2m de téléchargements, 1.4+ stars sur GitHub), une partie de mes travaux de recherche se focalisent sur l'apprentissage automatique pour les données temporelles. Un article [2] décrivant `pyts` a été publié dans JMLR en 2020. J'ai également contribué à la librairie `tslearn` [2]. Une revue de littérature sur les algorithmes et les librairies pour la classification de séries temporelles [3] a également été acceptée comme chapitre de livre.
  > J'enseigne la programmation en Python, la programmation orientée objet et la documentation du code, et je suis responsable du projet "Traitement de données" à l'ENSAI.

  > [1] J. Faouzi and H. Janati. pyts: A Python Package for Time Series Classification. Journal of Machine Learning Research, 21(46):1−6, 2020.
  > [2] Tslearn, a machine learning toolkit for time series data. R. Tavenard, J. Faouzi et al. The Journal of Machine Learning Research, 2020.
  > [3] J. Faouzi. Time Series Classification: A review of Algorithms and Implementations. To appear in: Ketan Kotecha (Ed.), Machine Learning (Emerging Trends and Applications), ISBN 978-1-8381524-1-3, 2023.
