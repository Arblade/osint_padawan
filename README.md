# OSINT Padawan Training
Repo centralisant ma progression en OSINT

## GEOSINT

1. Exercice n°1 : Exploitation de ce [tuto](https://towardsdatascience.com/how-to-use-open-source-satellite-data-for-your-investigative-reporting-d662cb1f9f90) Geosint :

[![Generic badge](https://img.shields.io/badge/Progression-95/100-blue.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/Bloqué-erreur_code-red.svg)](https://shields.io/)

Ressources : 
- [sentinel-hub.com](https://apps.sentinel-hub.com/eo-browser/?zoom=10&lat=41.9&lng=12.5&themeId=DEFAULT-THEME) : site d'images satelites du monde entier sur plusieurs années.
- [librairie eo-learn](https://medium.com/sentinel-hub/introducing-eo-learn-ab37f2869f5c) : librairie python pour converser avec l'api sentinel-hub.

Progression :
Difficulté à mettre en application la première étape : les feux de forêt son masqués par des nuages / ou ne sont plus accessibles (seules des tranches géographiques sint disponibles).
L'utilisation de l'api sentinel-hub via python marche très bien, mais il y a des difficultés pour finir le dernier tp. Il apparaît que l'objet `VectorToRaster` est mal initialisé (peut-être que le code de eolearn a changé entre temps). De plus, le repo source n'est plus disponible. Bref après plusieurs tentatives infructueuses, je repasse sur un autre projet dans la même veine. Le code corrigé est dispo sous la version v3.

2. Exercice n°2 via ce [tuto](https://towardsdatascience.com/whats-growing-there-a5618a2e6933)

3. Exercice n°3 : regarder également ce [tuto](https://medium.com/sentinel-hub/land-cover-classification-with-eo-learn-part-1-2471e8098195)

## TheHarvester


Exercice : ce [tuto](https://null-byte.wonderhowto.com/how-to/scrape-target-email-addresses-with-theharvester-0176307/)


[![Generic badge](https://img.shields.io/badge/Progression-Terminé-green.svg)](https://shields.io/)

Utilisation simple de recherche sur différentes plateformes et possibilité de retourner les résulats dans un .txt ou html. Utilisation également de recherche dns.
Problèmes rencontrés : TheHarvester est blocké par google (*Google is blocking your ip and the workaround*) et il faut des clefs d'api pour bing, github, shodan..

## Infoga

[![Generic badge](https://img.shields.io/badge/Progression-Terminé-green.svg)](https://shields.io/)

Outil plus puissant semble il que TheHarvester mais accomplit la même tâche tout en cherchant en plus sur les sites de leaks.

## Maltego

[![Generic badge](https://img.shields.io/badge/Progression-Terminé-green.svg)](https://shields.io/)

Outil puissant mais payant pour devenir intéressant dans la recherche de personne. Pour le reste et notamment la recherche réseau cea permet d'avoir une vue graphique efficace de scans menés automatiquements. Attention, bien veiller à rajouter les extensions après l'installation.

## Spiderfoot

[![Generic badge](https://img.shields.io/badge/Progression-Terminé-green.svg)](https://shields.io/)

Fonctionne via une page web créée en local. L'interface est bien faite, mais les focntionnailités et les résultats restent limités par rapport à la version gratuite de maltego, même si certains résultats sont uniques par raport à cette dernière plateforme. L'utilisation est aussi plus simple et plus directe.

## Suite : regader ce [lien](https://www.lemondeinformatique.fr/actualites/lire-8-outils-osint-pour-le-cyber-renseignement-80484.html)

A creuser : recon-ng, maltego, metagoofil, spiderfoot et babelx
