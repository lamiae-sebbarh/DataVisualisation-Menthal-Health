# DataVisualisation-Menthal-Health

<h2>Description de projet :</h2>
Ce projet est composé de 3 sélections de données, 4 affichages numériques et 9 graphiques, créés à l'aide de Javascript, Crossfilter js, HTML,CSS  et D3.</br>
La conception de ce projet  a été utilisée pour fournir à l'utilisateur un moyen pratique et pragmatique d'étudier les tendances des statistiques sur la santé mentale.

<h2>La Dataset :</h2>
La source de l'ensemble de données est disponible publiquement sur kaggle .</br>
Cet ensemble de données provient d'une enquête de 2014 qui mesure les attitudes à l'égard de la santé mentale et la fréquence des troubles de santé mentale dans le milieu de travail technologique. Nous visualisons les résultats de cette enquête pour plus de 1 200 employés partout dans le monde et principalement dans le secteur des technologies. Ces données sont principalement catégoriques, comprenant 27 variables mais peuvent être regroupées en trois sections: les antécédents des employés, les attitudes à l'égard de la santé mentale et les avantages / outils de l'entreprise. Chacune de ces sections comprend plusieurs variables que nous visons à visualiser en utilisant un tracé bin 2d et plusieurs filtres pour visualiser les interactions. En outre, nous dériverons des variables de classement global sur des groupements spécifiques pour mieux résumer les données et fournir des informations utiles.

<h2>Fonctioctionnalité : </h2>
Il existe trois sélecteurs de données dans la section d'introduction qui permettent aux utilisateurs de filtrer facilement les données par type d'entreprise, sexe ou date.
Il existe 4 affichages numériques qui s'ajustent en fonction des filtres appliqués et montrent le nombre total d'enregistrements filtrés, l'âge moyen des hommes et des femmes interrogés et également le nombre d'entreprises technologiques dans le filtre actuel. Si aucun filtre n'est sélectionné, ces nombres seront les nombres globaux pour l'ensemble de données.
Dans la section de ventilation, il y a deux graphiques à secteurs pour afficher les ventilations par sexe et par pays. En outre, un graphique à barres de données dérivées montre les groupes d'âge.
La section de traitement est composée de trois graphiques. «Traitement par sexe» montre les différents degrés de traitement par groupe de genre. «Niveaux de traitement» indique le nombre total de personnes qui ont déjà demandé un traitement pour des problèmes de santé mentale et qui n'en ont pas eu. «Antécédents familiaux» montre les niveaux de problèmes de santé mentale que les répondants avaient dans leur histoire familiale.
La section sur l'impact utilise deux graphiques à barres empilées pour illustrer les attitudes face à la discussion des problèmes de santé avec les employeurs.


<h2>Technologies utilisées :</h2>
HTML CSS Bootstrap (version 4.7.0) </br>
D3.js (version 3.5.17)</br>
 JavaScript Dc.js (version 2.1.8) </br>
<h2> Resultats:</h2>
La fonction d'âge moyen a renvoyé 32 pour les hommes et les femmes comme prévu.</br>
Le décompte des répondants a renvoyé 1259 comme prévu.</br>
Le nombre de sociétés technologiques a renvoyé 1031 comme prévu.</br>
Le bouton de réinitialisation réinitialise tous les filtres sur le tableau de bord comme prévu.</br>
Tous les affichages numériques s'ajustent dynamiquement aux filtres supplémentaires.</br>



![image](https://user-images.githubusercontent.com/58346874/103141074-7fc9ed00-46ef-11eb-9033-dc13a87d237d.png)
![image](https://user-images.githubusercontent.com/58346874/103141077-835d7400-46ef-11eb-8b28-409b4cee47bd.png)
![image](https://user-images.githubusercontent.com/58346874/103141080-87899180-46ef-11eb-8ab8-d64fab0cf2fc.png)
![image](https://user-images.githubusercontent.com/58346874/103141083-8b1d1880-46ef-11eb-8eb7-f84a0fd81f06.png)
