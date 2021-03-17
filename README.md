# Data Visualisation Portfolio

This repository showcases a variety of data visualisations I have created for different purposes. The charts themselves are all made in R, but the underlying data gathering and manipulation tends to be done Excel or Python or both.

## Cycle Lanes in Europe
Source Code: https://github.com/Jonathan-Vincent/CycleLanes

Data Source: OpenStreetMaps, queried using the [Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API)

![Cycle Lanes](https://raw.githubusercontent.com/Jonathan-Vincent/CycleLanes/main/CycleChart.png)

## Twin Cities of Europe
Data Source: Wikidata Query Service, collected using this [query](https://query.wikidata.org/#SELECT%20%3Fcity%20%3Fcountry%20%3Fcity_population%20%3Fcity_coordinate%20%3Fsister%20%3Fsister_country%20%3Fsister_population%20%3Fsister_coordinate_location%20WHERE%20%7B%0A%20%20%20%20%20%20%3Fcity%20wdt%3AP31%2Fwdt%3AP279%3F%20wd%3AQ486972.%0A%20%20%20%20%20%20%3Fcity%20wdt%3AP17%20%3Fcountry.%0A%20%20%20%20%20%20%3Fcity%20wdt%3AP625%20%3Fcity_coordinate.%0A%20%20%20%20%20%20%3Fcity%20wdt%3AP1082%20%3Fcity_population.%0A%20%20%20%20%20%20%3Fcity%20wdt%3AP190%20%3Fsister.%0A%20%20%20%20%20%20%3Fsister%20wdt%3AP17%20%3Fsister_country.%0A%20%20%20%20%20%20%3Fsister%20wdt%3AP1082%20%3Fsister_population.%0A%20%20%20%20%20%20%3Fsister%20wdt%3AP625%20%3Fsister_coordinate_location.%0A%7D)

![Twin Map](https://raw.githubusercontent.com/Jonathan-Vincent/DataVisualisationPortfolio/main/twinMap.png)

## The Growth of Motorways in Europe
Source Code: https://github.com/Jonathan-Vincent/EuropeanHighways

Data Sources: Wikipedia, ADAC

![The Growth of Motorways in Europe](https://raw.githubusercontent.com/Jonathan-Vincent/DataVisualisationPortfolio/main/European%20Motorways.png)

## How Difficult Is Each Country In GeoGuessr?
Source Code: https://github.com/Jonathan-Vincent/GeoGuessrStreaks

Data Sources: GeoGuessr Challenge HTML files

![GeoGuessr](https://raw.githubusercontent.com/Jonathan-Vincent/GeoGuessrStreaks/master/barplot%20long.png)


## How Has British Trade Changed Over the Last Twenty Years?
Source Code: https://github.com/Jonathan-Vincent/UKtrade

Data Sources: [UN GDP growth data](https://unstats.un.org/unsd/amaapi/api/file/24), [UK ONS trade data](https://www.ons.gov.uk/businessindustryandtrade/internationaltrade/datasets/uktotaltradeallcountriesnonseasonallyadjusted)

![Correlation](https://raw.githubusercontent.com/Jonathan-Vincent/DataVisualisationPortfolio/main/The%20Future%20of%20British%20Trade%20Graph%202.png)
