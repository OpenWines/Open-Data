# Mise à disposition des données des AOC/IGP du département 44

# Geojson files set for IGP/AOC within French "Loire-Atlantique" department (Loire vineyards, France)

## Introduction

Dans le cadre du [hackgriculture](http://cantine.atlantic2.org/evenements/hackgriculture-les-technologies-au-service-de-la-production-agricole-en-milieu-urbain/), nous avons généré les aires communales des AOC et IGP qui sont présentes dans le département du 44 en incluant toutes les communes de l'AOC. Cela implique que l'aire AOC peut dépasser le département. Par ailleurs, nous avons considéré qu'il n'y avait pas nécessité de n'inclure que les AOC/IGP vins et qu'il était plus intéressant de mettre à disposition toutes les données.

# Méthodes et sources de données

Nous avons utilisé des codes basés sur le type (AOC ou IGP) et sur le code IDA provenant des données INAO.

Les données viennent du site <http://data.gouv.fr> et en particulier de l'INAO (Institut National pour les Appelations d'Origine) pour la liste des communes (Licence Ouverte sur cette partie mais toutes les données INAO ne sont pas ouvertes)
Nous les avons croisées avec le COG (code officiel géographique) pour corriger des erreurs sur des codes INSEE obsolètes.
Nous avons utilisés les données OpenStreetMap communales édition 2015 (licence ODBL) pour pouvoir avoir les contours communaux.

La donnée résultante est une donnée cartographique. Le GeoJSON est un format qui permet de représenter des données cartographiques sur le web.

Pour un aperçu, vous pouvez utiliser [Umap](http://umap.openstreetmap.fr) ou [GeoJSON.io](http://geojson.io). Il est aussi possible d'utiliser un outil cartographique assez ergonomique (on pourrait dire l'équivalent du traitement de texte pour la cartographie) appelé [QGIS](http://qgis.org/fr/)

# Licence

La licence de la donnée ainsi produite est à notre sens de type ODBL. N'hésitez pas à revenir vers nous si cette interprétation vous parait erronnée.

Si vous utilisez la donnée, vous devez mentionner obligatoirement la licence et les crédits par exemple sous cette forme HTML `© Openstreetmap France | Données <a href="http://www.openstreetmap.org/copyright">© les contributeurs OpenStreetMap</a>, INAO (<a href="https://www.etalab.gouv.fr/licence-ouverte-open-licence">Licence Ouverte</a>, INSEE (<a href="http://www.insee.fr/fr/methodes/nomenclatures/cog/">COG</a>), <a href="https://github.com/OpenWines">OpenWines</a>)`

Si c'est dans le cadre d'une carte, il est conseillé de faire apparaitre dans les crédits de la carte (et pas sur une autre page) `© Openstreetmap France | Données <a href="http://www.openstreetmap.org/copyright">© les contributeurs OpenStreetMap</a>`. En effet, votre application risquera d'avoir une très mauvaise publicité grâce à <https://twitter.com/mapviolations> qui dénonce les usages abusifs (sans mention de licence) de OpenStreetMap.

# Tableau des correspondances

|    Nom fichier   |   Nom appelation |
| ---------------- | ------------- |
| [igp_1553.geojson](igp_1553.geojson) | Volailles d’Ancenis |
| [aoc_2335.geojson](aoc_2335.geojson) | Muscadet Sèvre et Maine Le Pallet |
| [aoc_2171.geojson](aoc_2171.geojson) | Gros Plant du Pays nantais |
| [aoc_1449.geojson](aoc_1449.geojson) | Eau-de-vie de cidre de Bretagne |
| [igp_1557.geojson](igp_1557.geojson) | Volailles de Cholet |
| [igp_1560.geojson](igp_1560.geojson) | Volailles de Janzé |
| [aoc_1609.geojson](aoc_1609.geojson) | Maine-Anjou |
| [igp_1566.geojson](igp_1566.geojson) | Volailles de Vendée |
| [aoc_195.geojson](aoc_195.geojson)  | Muscadet Sèvre et Maine |
| [aoc_2334.geojson](aoc_2334.geojson) | Muscadet Sèvre et Maine Gorges |
| [aoc_2332.geojson](aoc_2332.geojson) | Muscadet Sèvre et Maine Clisson |
| [igp_1556.geojson](.geojson) | Volailles de Challans |
| [igp_1582.geojson](igp_1556.geojson) | Cidre de Bretagne |
| [aoc_2342.geojson](aoc_2342.geojson) | Muscadet Coteaux de la Loire |
| [igp_1555.geojson](igp_1555.geojson) | Volailles de Bretagne |
| [igp_1949.geojson](igp_1949.geojson) | Farine de blé noir de Bretagne - Gwinizh du Breizh |
| [aoc_194.geojson](aoc_194.geojson)  | Muscadet Côtes de Grandlieu |
| [aoc_2341.geojson](aoc_2341.geojson) | Muscadet |
| [igp_1970.geojson](igp_1970.geojson) | Val de Loire |
| [igp_1525.geojson](igp_1525.geojson) | Bœuf du Maine |
| [igp_1544.geojson](igp_1544.geojson) | Porc de Vendée |
| [igp_2122.geojson](igp_2122.geojson) | Mogette de Vendée |
| [igp_1536.geojson](igp_1536.geojson) | Mâche nantaise |
| [aoc_2367.geojson](aoc_2367.geojson) | Pommeau de Bretagne |
| [igp_1608.geojson](igp_1608.geojson) | Brioche vendéenne |
| [aoc_1488.geojson](aoc_1488.geojson) | Beurre Charentes-Poitou |
| [igp_1660.geojson](igp_1660.geojson) | Bœuf de Vendée |
| [aoc_2175.geojson](aoc_2175.geojson) | Coteaux d'Ancenis |
| [igp_2139.geojson](igp_2139.geojson) | Oie d'Anjou |
