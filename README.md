# Préambule
Dans le cadre de l'exament d'évalution de nos acquis du cours de datavisualisation, il nous ai demandé de choisir un thème et de trouver des jeux de données pour illustrer le travail. Nous avons le choix de données à utiliser et du lieux ou nous pouvons choisir nos données. Nous avons choisi de travailler pour notre part sur l'évolution des entrées en salles de Cinéma.En effet depuis deux années les salles de cinema ont souffert des fermeture dans le cadre des mesures de sanitaires contre la covid 19. Nous avons voulu savoir en premier l'evolution depuis quelques années en france, et ensuite de relever les baises de fréquentation des dernières années. Il est a noté que les résultats que nous cherchons à voir peuvent être différente puisque pluisieurs facteurs peeuvent être à l'origine de la baisse de la fréquentation des salles de cinéma.

# Introduction
Selon wikipédia, "une salle de cinéma ou un cinéma est un lieu où est organisée la projection de films. Ce terme peut désigner aussi le regroupement dans un même endroit de plusieurs salles, qui projettent généralement des films différents à plusieurs horaires et dans ce cas le terme de « multiplexe » peut être également employé".
Avant d'arriver à ces années glorieuses, les salles de cinémas ont eu du mal à décoler. La naissance des salles de cinema a été le fruit d'un long processus tout au lon du 19 ème siècle dans laquelle la technologie et la culture de masse ont joué un grand rôle. La première projection publique et payante à Paris a eu lieu au salon indien le 28 décembre 1895.

![This is an image](https://github.com/DedeKANGNI/Exament_Dataviz_DEFI/blob/main/cine.jpg)

#### Affiche de la première projection payante à cinématographique à Paris

Cette belle aventure a continué avec ces hauts et bas jusqu'en 2020 dernier où tout à basculer. En effet avec la pandémie à coronavirus, les autorité ont du fermé les établissement recevant du public et les salles de cinéma ainsi d'autres lieux de cultures ont payé un lourd tribu. Même après la réouverture les salles ont eu du mal à reprendre du public. Nous avons donc pris les données sur le site https://data.culture.gouv.fr/explore/dataset/frequentation-dans-les-salles-de-cinema/table/?disjunctive.annee, le site opendata du ministère de la culture.

# Présentation du jeux de données

<iframe src="https://data.culture.gouv.fr/explore/embed/dataset/frequentation-dans-les-salles-de-cinema/table/?disjunctive.annee&static=false&datasetcard=false" width="800" height="400" frameborder="0"></iframe>
Ce jeu de donnée est mis à disposition par le site du ministère de la culture. Il présente les fréquentations dans les salles de cinéma depuis les années 1980 à 2020.On a également dans ce jeu de donnée la recette que les ces entrées ont générés pour chaque année. Il est important de noter que les données ont été mis à jour en novembre 2021.

Pour montrer cette évolution,nous avons choisi de faire un graphique ci-dessous.
<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJ0aW1lc2NhbGUiOiIiLCJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJsaW5lIiwiZnVuYyI6IlNVTSIsInlBeGlzIjoiZW50cmVlc19taWxsaW9ucyIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiMwMDAwODAifV0sInhBeGlzIjoiYW5uZWUiLCJtYXhwb2ludHMiOjUwLCJzb3J0IjoiIiwiY29uZmlnIjp7ImRhdGFzZXQiOiJmcmVxdWVudGF0aW9uLWRhbnMtbGVzLXNhbGxlcy1kZS1jaW5lbWFAY3VsdHVyZSIsIm9wdGlvbnMiOnt9fX1dLCJhbGlnbk1vbnRoIjp0cnVlLCJkaXNwbGF5TGVnZW5kIjp0cnVlfQ%3D%3D&static=false&datasetcard=false" width="800" height="300" frameborder="0"></iframe>
  #### graphique de l'évolution des entrées depuis 1980 à 2020.
Comme on si attendait, on remarque grosse montée en 2019 avant d'avoir une chute vertigineuse en 2020. Il est important de marquer aussi que après un bon décollage dans les années 80 il y a une baisse autour des années 90 et 95. Cette baisse peut être expliquée par l'avancée de la télévision dans les foyers et la programmation des émissions de divertissement.
Cette tendance se confirme dans d'autres pays de l'europe comme l'espagne, l'allemagne selon nos recherches.
Pour continuer notre decouverte sur les salles de cinéma nous avons voulus savoir quelle est la repartition des salles de cinéma sur toute l'étendue du territoire, nous avons choist un jeu de donné que nous avons trouver sur le site Opendatasoft et dont voici le lien https://data.opendatasoft.com/explore/dataset/etablissements-cinematographiques%40culture/table/.

<iframe src="https://data.opendatasoft.com/explore/embed/dataset/etablissements-cinematographiques@culture/table/?&static=false&datasetcard=false" width="800" height="300" frameborder="0"></iframe>
Avec ce jeu nous avons donc créer une carte pour mieux les visualiser. 

<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/geolocalisation_des_cinema_actifs_en_france/?&static=false&scrollWheelZoom=false"></iframe>

Le résultat de cette carte nous montre que la région de l'ile de france est celle dans laquellle se concentre la majorité des salles de cinéma. Lors de cet travaille nous avons remarqué différents groupes possèdes les salles de cinéma sur le territoire et à coté de ceux on a également de petit groupe et des salles associatifs.
Alors nous nous sommes demandés comment ils ont fait pour survivre à la fermeture lors de cette pandémie. lors de nos lecture nis avons donc appris que certains a mis la clef à la porte puisqu'ils étaient déjà en grande souffrance et la situation sanitaire n'a pas aidé. Nous avons cherché à savoir combien étaient ils en tout mais nous n'avons pas pu trouver de jeux de données sur ce sujet qui à notre avis est très importante pour vraiment voir l'impact que la covid -19 a eu sur les fréquentations. Nous avons imaginé qu'il y aurais des jeux de données qui ont recensé les salles de cinéma avant et après la grande vague de 2020.

## Visualisation des données des salles de cinéma.
Nous habitons le departement des yvelines dans lequel nous avons en pleine pandémie. Et avec mon conjoint on adorait se faire plaisir en allant regarder un film au cinéma. Mais depuis le debut du covid étant une vraie trouillarde, je n'ais pas remis les pieds dans une salle de cinéma. De plus je ne connais pas où se trouve les salle de cinéma dans les yvelines. C'est donc une bonne occasion de visualiser les salles de cinnéma dans les yvelines et dans l'île de france pour les future sorties.
Nous avons pu réaliser ce souhait grâce à un jeu de donner trouver sur opendatasoft: https://data.opendatasoft.com/explore/dataset/salle_de_cinema_ile-de-francedatailedefrance%40cinema-public/table/

<iframe src="https://data.opendatasoft.com/explore/embed/dataset/salle_de_cinema_ile-de-francedatailedefrance@cinema-public/table/?&static=false&datasetcard=false" width="400" height="300" frameborder="0"></iframe>
<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/les_salles_de_cinema_en_ile_de_france/?&static=true&scrollWheelZoom=true"></iframe>
Comme on pouvait le deviner la petite courronne de Paris est encore en tête en concentration de salles de cinéma.
# Conclusion.
Cette expérience et cette question de connaître l'effet de la pandémie sur les salles de cinéma ont révélés que toutes les questions n'ont pas encore de réponse. Qand bien même opendata continue de faire son chemin il reste encore du travail à faire pour pouvoir répondre à des questions que peuvent se poser des citoyzns dans leur coin.
