# Data Sources

Für das Dashboard werden verschiedene Datenquellen verwendet.
- Our World in Data https://github.com/owid/covid-19-data/blob/master/public/data/README.md
- Divi Intensivregister https://www.intensivregister.de/
- RKI https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Aktuell_Deutschland_Impfquoten_COVID-19.csv / https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Aktuell_Deutschland_Landkreise_COVID-19-Impfungen.csv

Darüber hinaus werden GEO-Daten abgefragt, die lokal vorliegen. Hierbei handelt es sich um Geojson Daten hinsichtlich aller Länder sowie der einzelnen Landkreise.
Die GEO-Daten werden zum einen zur Zuordnung der jeweiligen Ländercodes benötigt, um Choropleth Maps zu erstellen, als auch für die Zuordnung der jeweiligen Landkreise zur Anreicherung der Datenquellen.
