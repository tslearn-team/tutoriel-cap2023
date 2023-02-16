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

